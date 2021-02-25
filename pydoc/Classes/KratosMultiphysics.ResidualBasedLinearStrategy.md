  
**KratosMultiphysics.ResidualBasedLinearStrategy** = class
ResidualBasedLinearStrategy([SolvingStrategy](KratosMultiphysics.SolvingStrategy))  
---  
`    `|   |

Method resolution order:

    [ResidualBasedLinearStrategy](KratosMultiphysics.ResidualBasedLinearStrategy)
    [SolvingStrategy](KratosMultiphysics.SolvingStrategy)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**GetResidualNorm**(...)

    `GetResidualNorm(self: Kratos.ResidualBasedLinearStrategy) -> float`

**GetSolutionVector**(...)

    `GetSolutionVector(self: Kratos.ResidualBasedLinearStrategy) -> Kratos.Vector`

**GetSystemMatrix**(...)

    `GetSystemMatrix(self: Kratos.ResidualBasedLinearStrategy) -> Kratos.CompressedMatrix`

**GetSystemVector**(...)

    `GetSystemVector(self: Kratos.ResidualBasedLinearStrategy) -> Kratos.Vector`

**SetBuilderAndSolver**(...)

    `SetBuilderAndSolver(self: Kratos.ResidualBasedLinearStrategy, arg0: Kratos.BuilderAndSolver) -> None`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.ResidualBasedLinearStrategy, arg0: Kratos.ModelPart, arg1: Kratos.Scheme, arg2: Kratos.LinearSolver, arg3: bool, arg4: bool, arg5: bool, arg6: bool) -> None  
  
2. __init__(self: Kratos.ResidualBasedLinearStrategy, arg0: Kratos.ModelPart, arg1: Kratos.Scheme, arg2: Kratos.LinearSolver, arg3: Kratos.BuilderAndSolver, arg4: bool, arg5: bool, arg6: bool, arg7: bool) -> None`

* * *

Methods inherited from [SolvingStrategy](KratosMultiphysics.SolvingStrategy):  

**CalculateOutputData**(...)

    `CalculateOutputData(self: Kratos.SolvingStrategy) -> None`

**Check**(...)

    `Check(self: Kratos.SolvingStrategy) -> int`

**Clear**(...)

    `Clear(self: Kratos.SolvingStrategy) -> None`

**FinalizeSolutionStep**(...)

    `FinalizeSolutionStep(self: Kratos.SolvingStrategy) -> None`

**GetEchoLevel**(...)

    `GetEchoLevel(self: Kratos.SolvingStrategy) -> int`

**GetRebuildLevel**(...)

    `GetRebuildLevel(self: Kratos.SolvingStrategy) -> int`

**Initialize**(...)

    `Initialize(self: Kratos.SolvingStrategy) -> None`

**InitializeSolutionStep**(...)

    `InitializeSolutionStep(self: Kratos.SolvingStrategy) -> None`

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

