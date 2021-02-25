  
**KratosMultiphysics.LineSearchStrategy** = class
LineSearchStrategy([ResidualBasedNewtonRaphsonStrategy](KratosMultiphysics.ResidualBasedNewtonRaphsonStrategy))  
---  
`    `|   |

Method resolution order:

    [LineSearchStrategy](KratosMultiphysics.LineSearchStrategy)
    [ResidualBasedNewtonRaphsonStrategy](KratosMultiphysics.ResidualBasedNewtonRaphsonStrategy)
    [SolvingStrategy](KratosMultiphysics.SolvingStrategy)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.LineSearchStrategy, arg0: Kratos.ModelPart, arg1: Kratos.Scheme, arg2: Kratos.LinearSolver, arg3: Kratos.ConvergenceCriteria, arg4: int, arg5: bool, arg6: bool, arg7: bool) -> None  
  
2. __init__(self: Kratos.LineSearchStrategy, arg0: Kratos.ModelPart, arg1: Kratos.Scheme, arg2: Kratos.LinearSolver, arg3: Kratos.ConvergenceCriteria, arg4: Kratos.BuilderAndSolver, arg5: int, arg6: bool, arg7: bool, arg8: bool) -> None  
  
3. __init__(self: Kratos.LineSearchStrategy, arg0: Kratos.ModelPart, arg1: Kratos.Scheme, arg2: Kratos.LinearSolver, arg3: Kratos.ConvergenceCriteria, arg4: Kratos::Parameters) -> None  
  
4. __init__(self: Kratos.LineSearchStrategy, arg0: Kratos.ModelPart, arg1: Kratos.Scheme, arg2: Kratos.LinearSolver, arg3: Kratos.ConvergenceCriteria, arg4: Kratos.BuilderAndSolver, arg5: Kratos::Parameters) -> None`

* * *

Methods inherited from
[ResidualBasedNewtonRaphsonStrategy](KratosMultiphysics.ResidualBasedNewtonRaphsonStrategy):  

**GetInitializePerformedFlag**(...)

    `GetInitializePerformedFlag(self: Kratos.ResidualBasedNewtonRaphsonStrategy) -> bool`

**GetKeepSystemConstantDuringIterations**(...)

    `GetKeepSystemConstantDuringIterations(self: Kratos.ResidualBasedNewtonRaphsonStrategy) -> bool`

**GetMaxIterationNumber**(...)

    `GetMaxIterationNumber(self: Kratos.ResidualBasedNewtonRaphsonStrategy) -> int`

**GetSolutionVector**(...)

    `GetSolutionVector(self: Kratos.ResidualBasedNewtonRaphsonStrategy) -> Kratos.Vector`

**GetSystemMatrix**(...)

    `GetSystemMatrix(self: Kratos.ResidualBasedNewtonRaphsonStrategy) -> Kratos.CompressedMatrix`

**GetSystemVector**(...)

    `GetSystemVector(self: Kratos.ResidualBasedNewtonRaphsonStrategy) -> Kratos.Vector`

**SetInitializePerformedFlag**(...)

    `SetInitializePerformedFlag(self: Kratos.ResidualBasedNewtonRaphsonStrategy, arg0: bool) -> None`

**SetKeepSystemConstantDuringIterations**(...)

    `SetKeepSystemConstantDuringIterations(self: Kratos.ResidualBasedNewtonRaphsonStrategy, arg0: bool) -> None`

**SetMaxIterationNumber**(...)

    `SetMaxIterationNumber(self: Kratos.ResidualBasedNewtonRaphsonStrategy, arg0: int) -> None`

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

