  
**KratosMultiphysics.SimpleMortarMapperProcess3D4NVector** = class
SimpleMortarMapperProcess3D4NVector([Process](KratosMultiphysics.Process))  
---  
`    `|   |

Method resolution order:

    [SimpleMortarMapperProcess3D4NVector](KratosMultiphysics.SimpleMortarMapperProcess3D4NVector)
    [Process](KratosMultiphysics.Process)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**Map**(...)

    `Map(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: Kratos.Flags) -> None`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos.Array1DVariable3) -> None  
  
2. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos::Parameters) -> None  
  
3. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos.Array1DVariable3, arg3: Kratos::Parameters) -> None  
  
4. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos.Array1DVariable3, arg3: Kratos::Parameters, arg4: Kratos::LinearSolver<Kratos::UblasSpace<double, boost::numeric::ublas::compressed_matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, 0ul, boost::numeric::ublas::unbounded_array<unsigned long, std::allocator<unsigned long> >, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > >, Kratos::UblasSpace<double, boost::numeric::ublas::matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > >, Kratos::Reorderer<Kratos::UblasSpace<double, boost::numeric::ublas::compressed_matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, 0ul, boost::numeric::ublas::unbounded_array<unsigned long, std::allocator<unsigned long> >, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > >, Kratos::UblasSpace<double, boost::numeric::ublas::matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > > > >) -> None  
  
5. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos.Array1DVariable3, arg3: Kratos.Array1DVariable3) -> None  
  
6. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos.Array1DVariable3, arg3: Kratos.Array1DVariable3, arg4: Kratos::Parameters) -> None  
  
7. __init__(self: Kratos.SimpleMortarMapperProcess3D4NVector, arg0: Kratos.ModelPart, arg1: Kratos.ModelPart, arg2: Kratos.Array1DVariable3, arg3: Kratos.Array1DVariable3, arg4: Kratos::Parameters, arg5: Kratos::LinearSolver<Kratos::UblasSpace<double, boost::numeric::ublas::compressed_matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, 0ul, boost::numeric::ublas::unbounded_array<unsigned long, std::allocator<unsigned long> >, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > >, Kratos::UblasSpace<double, boost::numeric::ublas::matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > >, Kratos::Reorderer<Kratos::UblasSpace<double, boost::numeric::ublas::compressed_matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, 0ul, boost::numeric::ublas::unbounded_array<unsigned long, std::allocator<unsigned long> >, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > >, Kratos::UblasSpace<double, boost::numeric::ublas::matrix<double, boost::numeric::ublas::basic_row_major<unsigned long, long>, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > >, boost::numeric::ublas::vector<double, boost::numeric::ublas::unbounded_array<double, std::allocator<double> > > > > >) -> None`

* * *

Methods inherited from [Process](KratosMultiphysics.Process):  

**Check**(...)

    `Check(self: Kratos.Process) -> int`

**Create**(...)

    `Create(self: Kratos.Process, arg0: Kratos::Model, arg1: Kratos::Parameters) -> Kratos.Process`

**Execute**(...)

    `Execute(self: Kratos.Process) -> None`

**ExecuteAfterOutputStep**(...)

    `ExecuteAfterOutputStep(self: Kratos.Process) -> None`

**ExecuteBeforeOutputStep**(...)

    `ExecuteBeforeOutputStep(self: Kratos.Process) -> None`

**ExecuteBeforeSolutionLoop**(...)

    `ExecuteBeforeSolutionLoop(self: Kratos.Process) -> None`

**ExecuteFinalize**(...)

    `ExecuteFinalize(self: Kratos.Process) -> None`

**ExecuteFinalizeSolutionStep**(...)

    `ExecuteFinalizeSolutionStep(self: Kratos.Process) -> None`

**ExecuteInitialize**(...)

    `ExecuteInitialize(self: Kratos.Process) -> None`

**ExecuteInitializeSolutionStep**(...)

    `ExecuteInitializeSolutionStep(self: Kratos.Process) -> None`

**__str__**(...)

    `__str__(self: Kratos.Process) -> str`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

