  
**KratosMultiphysics.AMGCLSolver** = class
AMGCLSolver([LinearSolver](KratosMultiphysics.LinearSolver))  
---  
`    `|   |

Method resolution order:

    [AMGCLSolver](KratosMultiphysics.AMGCLSolver)
    [LinearSolver](KratosMultiphysics.LinearSolver)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**GetIterationsNumber**(...)

    `GetIterationsNumber(self: Kratos.AMGCLSolver) -> int`

**GetResidualNorm**(...)

    `GetResidualNorm(self: Kratos.AMGCLSolver) -> float`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.AMGCLSolver, arg0: Kratos.AMGCLSmoother, arg1: Kratos.AMGCLIterativeSolverType, arg2: float, arg3: int, arg4: int, arg5: int) -> None  
  
2. __init__(self: Kratos.AMGCLSolver, arg0: Kratos.AMGCLSmoother, arg1: Kratos.AMGCLIterativeSolverType, arg2: Kratos.AMGCLCoarseningType, arg3: float, arg4: int, arg5: int, arg6: int, arg7: bool) -> None  
  
3. __init__(self: Kratos.AMGCLSolver) -> None  
  
4. __init__(self: Kratos.AMGCLSolver, arg0: Kratos::Parameters) -> None`

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

**__str__**(...)

    `__str__(self: Kratos.LinearSolver) -> str`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

