  
**KratosMultiphysics.ResidualBasedBlockBuilderAndSolver** = class
ResidualBasedBlockBuilderAndSolver([BuilderAndSolver](KratosMultiphysics.BuilderAndSolver))  
---  
`    `|   |

Method resolution order:

    [ResidualBasedBlockBuilderAndSolver](KratosMultiphysics.ResidualBasedBlockBuilderAndSolver)
    [BuilderAndSolver](KratosMultiphysics.BuilderAndSolver)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**__init__**(...)

    `__init__(self: Kratos.ResidualBasedBlockBuilderAndSolver, arg0: Kratos.LinearSolver) -> None`

* * *

Methods inherited from [BuilderAndSolver](KratosMultiphysics.BuilderAndSolver):  

**ApplyDirichletConditions**(...)

    `ApplyDirichletConditions(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

**Build**(...)

    `Build(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector) -> None`

**BuildAndSolve**(...)

    `BuildAndSolve(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

**BuildLHS**(...)

    `BuildLHS(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.CompressedMatrix) -> None`

**BuildRHS**(...)

    `BuildRHS(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.Vector) -> None`

**BuildRHSAndSolve**(...)

    `BuildRHSAndSolve(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

**CalculateReactions**(...)

    `CalculateReactions(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

**Check**(...)

    `Check(self: Kratos.BuilderAndSolver, arg0: Kratos.ModelPart) -> int`

**Clear**(...)

    `Clear(self: Kratos.BuilderAndSolver) -> None`

**FinalizeSolutionStep**(...)

    `FinalizeSolutionStep(self: Kratos.BuilderAndSolver, arg0: Kratos.ModelPart, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector) -> None`

**GetCalculateReactionsFlag**(...)

    `GetCalculateReactionsFlag(self: Kratos.BuilderAndSolver) -> bool`

**GetDofSet**(...)

    `GetDofSet(self: Kratos.BuilderAndSolver) -> Kratos.DofsArrayType`

**GetDofSetIsInitializedFlag**(...)

    `GetDofSetIsInitializedFlag(self: Kratos.BuilderAndSolver) -> bool`

**GetEchoLevel**(...)

    `GetEchoLevel(self: Kratos.BuilderAndSolver) -> int`

**GetEquationSystemSize**(...)

    `GetEquationSystemSize(self: Kratos.BuilderAndSolver) -> int`

**GetReshapeMatrixFlag**(...)

    `GetReshapeMatrixFlag(self: Kratos.BuilderAndSolver) -> bool`

**InitializeSolutionStep**(...)

    `InitializeSolutionStep(self: Kratos.BuilderAndSolver, arg0: Kratos.ModelPart, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector) -> None`

**ResizeAndInitializeVectors**(...)

    `ResizeAndInitializeVectors(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector, arg4: Kratos.ModelPart) -> None`

**SetCalculateReactionsFlag**(...)

    `SetCalculateReactionsFlag(self: Kratos.BuilderAndSolver, arg0: bool) -> None`

**SetDofSetIsInitializedFlag**(...)

    `SetDofSetIsInitializedFlag(self: Kratos.BuilderAndSolver, arg0: bool) -> None`

**SetEchoLevel**(...)

    `SetEchoLevel(self: Kratos.BuilderAndSolver, arg0: int) -> None`

**SetReshapeMatrixFlag**(...)

    `SetReshapeMatrixFlag(self: Kratos.BuilderAndSolver, arg0: bool) -> None`

**SetUpDofSet**(...)

    `SetUpDofSet(self: Kratos.BuilderAndSolver, arg0: Kratos.Scheme, arg1: Kratos.ModelPart) -> None`

**SetUpSystem**(...)

    `SetUpSystem(self: Kratos.BuilderAndSolver, arg0: Kratos.ModelPart) -> None`

**SystemSolve**(...)

    `SystemSolve(self: Kratos.BuilderAndSolver, arg0: Kratos.CompressedMatrix, arg1: Kratos.Vector, arg2: Kratos.Vector) -> None`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

