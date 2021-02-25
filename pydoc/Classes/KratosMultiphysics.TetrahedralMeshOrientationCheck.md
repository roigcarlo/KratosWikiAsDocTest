  
**KratosMultiphysics.TetrahedralMeshOrientationCheck** = class
TetrahedralMeshOrientationCheck([Process](KratosMultiphysics.Process))  
---  
`    `|   |

Method resolution order:

    [TetrahedralMeshOrientationCheck](KratosMultiphysics.TetrahedralMeshOrientationCheck)
    [Process](KratosMultiphysics.Process)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**SwapAll**(...)

    `SwapAll(self: Kratos.TetrahedralMeshOrientationCheck) -> None`

**SwapNegativeElements**(...)

    `SwapNegativeElements(self: Kratos.TetrahedralMeshOrientationCheck) -> None`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.TetrahedralMeshOrientationCheck, arg0: Kratos.ModelPart, arg1: bool) -> None  
  
2. __init__(self: Kratos.TetrahedralMeshOrientationCheck, arg0: Kratos.ModelPart, arg1: bool, arg2: Kratos.Flags) -> None`

* * *

Data and other attributes defined here:  

**ASSIGN_NEIGHBOUR_ELEMENTS_TO_CONDITIONS** =  <Kratos.Flags object>

**COMPUTE_CONDITION_NORMALS** =  <Kratos.Flags object>

**COMPUTE_NODAL_NORMALS** =  <Kratos.Flags object>

**NOT_ASSIGN_NEIGHBOUR_ELEMENTS_TO_CONDITIONS** =  <Kratos.Flags object>

**NOT_COMPUTE_CONDITION_NORMALS** =  <Kratos.Flags object>

**NOT_COMPUTE_NODAL_NORMALS** =  <Kratos.Flags object>

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

