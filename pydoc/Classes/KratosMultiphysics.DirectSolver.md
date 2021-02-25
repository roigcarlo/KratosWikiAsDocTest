  
**KratosMultiphysics.DirectSolver** = class
DirectSolver([LinearSolver](KratosMultiphysics.LinearSolver))  
---  
`    `|   |

Method resolution order:

    [DirectSolver](KratosMultiphysics.DirectSolver)
    [LinearSolver](KratosMultiphysics.LinearSolver)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.DirectSolver) -> None  
  
2. __init__(self: Kratos.DirectSolver, arg0: Kratos::Parameters) -> None`

**__str__**(...)

    `__str__(self: Kratos.DirectSolver) -> str`

* * *

Methods inherited from [LinearSolver](KratosMultiphysics.LinearSolver):  

**Clear**(...)

    `Clear(self: Kratos.LinearSolver) -> None`

**Initialize**(...)

    `Initialize(self: Kratos.LinearSolver, arg0: Kratos.CompressedMatrix, arg1: Kratos.Vector, arg2: Kratos.Vector) -> None`

**Solve**(...)

    `Solve(*args, **kwargs)  
Overloaded  function.  
  
1. Solve(self: Kratos.LinearSolver, arg0: Kratos.CompressedMatrix, arg1: Kratos.Vector, arg2: Kratos.Vector) -> bool  
  
2. Solve(self: Kratos.LinearSolver, arg0: Kratos.CompressedMatrix, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Matrix) -> None`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

