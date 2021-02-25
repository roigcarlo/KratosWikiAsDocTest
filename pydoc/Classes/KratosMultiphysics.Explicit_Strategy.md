  
**KratosMultiphysics.Explicit_Strategy** = class
Explicit_Strategy([SolvingStrategy](KratosMultiphysics.SolvingStrategy))  
---  
`    `|   |

Method resolution order:

    [Explicit_Strategy](KratosMultiphysics.Explicit_Strategy)
    [SolvingStrategy](KratosMultiphysics.SolvingStrategy)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AssembleLoop**(...)

    `AssembleLoop(self: Kratos.Explicit_Strategy) -> None`

**ExplicitUpdateLoop**(...)

    `ExplicitUpdateLoop(self: Kratos.Explicit_Strategy, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: float) -> None`

**FinalizeSolutionStep**(...)

    `FinalizeSolutionStep(self: Kratos.Explicit_Strategy) -> None`

**InitializeSolutionStep**(...)

    `InitializeSolutionStep(self: Kratos.Explicit_Strategy) -> None`

**NormalizeVariable**(...)

    `NormalizeVariable(self: Kratos.Explicit_Strategy, arg0: Kratos.Array1DVariable3, arg1: Kratos.DoubleVariable) -> None`

**__init__**(...)

    `__init__(self: Kratos.Explicit_Strategy, arg0: Kratos.ModelPart, arg1: int, arg2: bool) -> None`

* * *

Methods inherited from [SolvingStrategy](KratosMultiphysics.SolvingStrategy):  

**CalculateOutputData**(...)

    `CalculateOutputData(self: Kratos.SolvingStrategy) -> None`

**Check**(...)

    `Check(self: Kratos.SolvingStrategy) -> int`

**Clear**(...)

    `Clear(self: Kratos.SolvingStrategy) -> None`

**GetEchoLevel**(...)

    `GetEchoLevel(self: Kratos.SolvingStrategy) -> int`

**GetRebuildLevel**(...)

    `GetRebuildLevel(self: Kratos.SolvingStrategy) -> int`

**Initialize**(...)

    `Initialize(self: Kratos.SolvingStrategy) -> None`

**IsConverged**(...)

    `IsConverged(self: Kratos.SolvingStrategy) -> bool`

**MoveMesh**(...)

    `MoveMesh(self: Kratos.SolvingStrategy) -> None`

**MoveMeshFlag**(...)

    `MoveMeshFlag(self: Kratos.SolvingStrategy) -> bool`

**Predict**(...)

    `Predict(self: Kratos.SolvingStrategy) -> None`

**SetEchoLevel**(...)

    `SetEchoLevel(self: Kratos.SolvingStrategy, arg0: int) -> None`

**SetMoveMeshFlag**(...)

    `SetMoveMeshFlag(self: Kratos.SolvingStrategy, arg0: bool) -> None`

**SetRebuildLevel**(...)

    `SetRebuildLevel(self: Kratos.SolvingStrategy, arg0: int) -> None`

**Solve**(...)

    `Solve(self: Kratos.SolvingStrategy) -> float`

**SolveSolutionStep**(...)

    `SolveSolutionStep(self: Kratos.SolvingStrategy) -> bool`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

