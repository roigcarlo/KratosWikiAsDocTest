  
**KratosMultiphysics.FindGlobalNodalNeighboursProcess** = class
FindGlobalNodalNeighboursProcess([Process](KratosMultiphysics.Process))  
---  
`    `|   |

Method resolution order:

    [FindGlobalNodalNeighboursProcess](KratosMultiphysics.FindGlobalNodalNeighboursProcess)
    [Process](KratosMultiphysics.Process)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**ClearNeighbours**(...)

    `ClearNeighbours(self: Kratos.FindGlobalNodalNeighboursProcess) -> None`

**GetNeighbourIds**(...)

    `GetNeighbourIds(self: Kratos.FindGlobalNodalNeighboursProcess, arg0: Kratos.NodesArray) -> Dict[int, List[int]]`

**__init__**(...)

    `__init__(self: Kratos.FindGlobalNodalNeighboursProcess, arg0: Kratos::DataCommunicator, arg1: Kratos.ModelPart) -> None`

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

