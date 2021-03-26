---
title: KRATOS_API for Windows Compilation
keywords: 
tags: [KRATOS_API-for-Windows-Compilation.md]
sidebar: kratos_sidebar
summary: 
---

Windows does not allow the default visibility of symbols and this will cause problems if the implementation of your class is located in a source file (typically your `*.cpp`) and you intend to use it in other applications or expose it to the python layer.

In order to ease the compilation pipeline and the structure of the project we offer a collection of decorators that automatically import / export symbols when compiling with MSVC.

{% include warning.html content="Its important only to use this if your implementation is in a `cpp` file. If your class is header-only the decorator cause a compilation error." %}

## Classes
If a class is having seperated header file and cpp, add `KRATOS_API(<APPLICATION_NAME>)` before class name in the header file as explained in following code snippet.

```c++
class KRATOS_API(FLUID_DYNAMICS_APPLICATION) TestClass
{
    // Rest of the code is unchanged
};
```

## Methods
If someone implemnets methods in a namespace and it has declaration in header and definition in cpp, then add `KRATOS_API(<APPLICATION_NAME>)` to the front of the method declaration in the header file as explained in following code snippet.

```c++
void KRATOS_API(FLUID_DYNAMICS_APPLICATION) TestMethod(int Value);
```

## Templated Classes and Methods
If the class or method is templated, and you have explicit template instantiations or definitions, then you need to again add `KRATOS_API(<APPLICATION_NAME>)` to all of the template instantiations as explained in following code snippets (example for a templated method).

In the header file:

```c++
template<class T>
void KRATOS_API(FLUID_DYNAMICS_APPLICATION) TestTemplatedMethod(const T& Value);
```

In the source file:

```c++
// Template definition
template<class T>
void TestTemplatedMethod<T>(const T& value)
{
    // Function body unchanged
}

// Explicit template instantiation and definition
template<>
void KRATOS_API(FLUID_DYNAMICS_APPLICATION) TestTemplatedMethod<int>(const int& Value)
{
    // Function body unchanged
}

// Explicit template instantiation
template void KRATOS_API(FLUID_DYNAMICS_APPLICATION) TestTemplatedMethod<double>(const double&);
```

{% include note.html content="Note that only explicitly instantiated versions of the class/method will be visible, in the example above `<double>` version would be visible but the `<int>` one would **NOT**." %}