  
**KratosMultiphysics.VariableUtils** = class
VariableUtils(pybind11_builtins.pybind11_object)  
---  
`    `|   |

Method resolution order:

    [VariableUtils](KratosMultiphysics.VariableUtils)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AddDof**(...)

    `AddDof(*args, **kwargs)  
Overloaded  function.  
  
1. AddDof(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart) -> None  
  
2. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.ModelPart) -> None  
  
3. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.ModelPart) -> None  
  
4. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.ModelPart) -> None  
  
5. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.ModelPart) -> None  
  
6. AddDof(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos.ModelPart) -> None  
  
7. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.Array1DComponentVariable, arg2: Kratos.ModelPart) -> None  
  
8. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.Array1D4ComponentVariable, arg2: Kratos.ModelPart) -> None  
  
9. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.Array1D6ComponentVariable, arg2: Kratos.ModelPart) -> None  
  
10. AddDof(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.Array1D9ComponentVariable, arg2: Kratos.ModelPart) -> None`

**ApplyFixity**(...)

    `ApplyFixity(*args, **kwargs)  
Overloaded  function.  
  
1. ApplyFixity(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
2. ApplyFixity(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
3. ApplyFixity(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
4. ApplyFixity(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
5. ApplyFixity(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: bool, arg2: Kratos.NodesArray) -> None`

**ApplyVector**(...)

    `ApplyVector(*args, **kwargs)  
Overloaded  function.  
  
1. ApplyVector(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None  
  
2. ApplyVector(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None  
  
3. ApplyVector(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None  
  
4. ApplyVector(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None  
  
5. ApplyVector(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None`

**CheckDofs**(...)

    `CheckDofs(self: Kratos.VariableUtils, arg0: Kratos.ModelPart) -> bool`

**CheckVariableKeys**(...)

    `CheckVariableKeys(self: Kratos.VariableUtils) -> bool`

**ClearNonHistoricalData**(...)

    `ClearNonHistoricalData(*args, **kwargs)  
Overloaded  function.  
  
1. ClearNonHistoricalData(self: Kratos.VariableUtils, arg0: Kratos.NodesArray) -> None  
  
2. ClearNonHistoricalData(self: Kratos.VariableUtils, arg0: Kratos.ConditionsArray) -> None  
  
3. ClearNonHistoricalData(self: Kratos.VariableUtils, arg0: Kratos.ElementsArray) -> None`

**CopyComponentVar**(...)

    `CopyComponentVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.Array1DComponentVariable, arg2: Kratos.NodesArray) -> None`

**CopyModelPartElementalVar**(...)

    `CopyModelPartElementalVar(*args, **kwargs)  
Overloaded  function.  
  
1. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
2. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
3. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
4. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
5. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
6. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
7. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None  
  
8. CopyModelPartElementalVar(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart) -> None`

**CopyModelPartNodalVar**(...)

    `CopyModelPartNodalVar(*args, **kwargs)  
Overloaded  function.  
  
1. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
2. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
3. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
4. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
5. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
6. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
7. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
8. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
9. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: Kratos.BoolVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
10. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
11. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
12. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array1DVariable4, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
13. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array1DVariable6, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
14. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array1DVariable9, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
15. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.VectorVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
16. CopyModelPartNodalVar(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.MatrixVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None`

**CopyModelPartNodalVarToNonHistoricalVar**(...)

    `CopyModelPartNodalVarToNonHistoricalVar(*args, **kwargs)  
Overloaded  function.  
  
1. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
2. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
3. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
4. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
5. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
6. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
7. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
8. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.ModelPart, arg2: Kratos.ModelPart, arg3: int) -> None  
  
9. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: Kratos.BoolVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
10. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
11. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
12. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array1DVariable4, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
13. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array1DVariable6, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
14. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array1DVariable9, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
15. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.VectorVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None  
  
16. CopyModelPartNodalVarToNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.MatrixVariable, arg2: Kratos.ModelPart, arg3: Kratos.ModelPart, arg4: int) -> None`

**CopyScalarVar**(...)

    `CopyScalarVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos.NodesArray) -> None`

**CopyVectorVar**(...)

    `CopyVectorVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: Kratos.NodesArray) -> None`

**FlipFlag**(...)

    `FlipFlag(*args, **kwargs)  
Overloaded  function.  
  
1. FlipFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.NodesArray) -> None  
  
2. FlipFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.ConditionsArray) -> None  
  
3. FlipFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.ElementsArray) -> None  
  
4. FlipFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.MasterSlaveConstraintsArray) -> None`

**ResetFlag**(...)

    `ResetFlag(*args, **kwargs)  
Overloaded  function.  
  
1. ResetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.NodesArray) -> None  
  
2. ResetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.ConditionsArray) -> None  
  
3. ResetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.ElementsArray) -> None  
  
4. ResetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: Kratos.MasterSlaveConstraintsArray) -> None`

**SaveScalarNonHistoricalVar**(...)

    `SaveScalarNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos.NodesArray) -> None`

**SaveScalarVar**(...)

    `SaveScalarVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos.NodesArray) -> None`

**SaveVectorNonHistoricalVar**(...)

    `SaveVectorNonHistoricalVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: Kratos.NodesArray) -> None`

**SaveVectorVar**(...)

    `SaveVectorVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array1DVariable3, arg2: Kratos.NodesArray) -> None`

**SelectNodeList**(...)

    `SelectNodeList(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray) -> Kratos.NodesArray`

**SetFlag**(...)

    `SetFlag(*args, **kwargs)  
Overloaded  function.  
  
1. SetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
2. SetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: bool, arg2: Kratos.ConditionsArray) -> None  
  
3. SetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: bool, arg2: Kratos.ElementsArray) -> None  
  
4. SetFlag(self: Kratos.VariableUtils, arg0: Kratos.Flags, arg1: bool, arg2: Kratos.MasterSlaveConstraintsArray) -> None`

**SetHistoricalVariableToZero**(...)

    `SetHistoricalVariableToZero(*args, **kwargs)  
Overloaded  function.  
  
1. SetHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: Kratos.NodesArray) -> None  
  
2. SetHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.NodesArray) -> None  
  
3. SetHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.NodesArray) -> None`

**SetNonHistoricalScalarVar**(...)

    `SetNonHistoricalScalarVar(*args, **kwargs)  
Overloaded  function.  
  
1. SetNonHistoricalScalarVar(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: int, arg2: Kratos.NodesArray) -> None  
  
2. SetNonHistoricalScalarVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
3. SetNonHistoricalScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
4. SetNonHistoricalScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
5. SetNonHistoricalScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
6. SetNonHistoricalScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None`

**SetNonHistoricalVariable**(...)

    `SetNonHistoricalVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: int, arg2: Kratos.NodesArray) -> None  
  
2. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
3. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
4. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray) -> None  
  
5. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.NodesArray) -> None  
  
6. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.NodesArray) -> None  
  
7. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.NodesArray) -> None  
  
8. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None  
  
9. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.NodesArray) -> None  
  
10. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.ConditionsArray) -> None  
  
11. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.ConditionsArray) -> None  
  
12. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.ConditionsArray) -> None  
  
13. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.ConditionsArray) -> None  
  
14. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.ConditionsArray) -> None  
  
15. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.ConditionsArray) -> None  
  
16. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.ConditionsArray) -> None  
  
17. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.ConditionsArray) -> None  
  
18. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.ElementsArray) -> None  
  
19. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.ElementsArray) -> None  
  
20. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.ElementsArray) -> None  
  
21. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.ElementsArray) -> None  
  
22. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.ElementsArray) -> None  
  
23. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.ElementsArray) -> None  
  
24. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.ElementsArray) -> None  
  
25. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.ElementsArray) -> None  
  
26. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
27. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
28. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
29. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
30. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
31. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
32. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
33. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
34. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
35. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
36. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
37. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
38. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
39. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
40. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
41. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.ConditionsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
42. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
43. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
44. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
45. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
46. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
47. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
48. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
49. SetNonHistoricalVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.ElementsArray, arg3: Kratos.Flags, arg4: bool) -> None`

**SetNonHistoricalVariableToZero**(...)

    `SetNonHistoricalVariableToZero(*args, **kwargs)  
Overloaded  function.  
  
1. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: Kratos.NodesArray) -> None  
  
2. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.NodesArray) -> None  
  
3. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ElementsArray) -> None  
  
4. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: Kratos.ElementsArray) -> None  
  
5. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ConditionsArray) -> None  
  
6. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: Kratos.ConditionsArray) -> None  
  
7. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.MasterSlaveConstraintsArray) -> None  
  
8. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.NodesArray) -> None  
  
9. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ElementsArray) -> None  
  
10. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ConditionsArray) -> None  
  
11. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.MasterSlaveConstraintsArray) -> None  
  
12. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.NodesArray) -> None  
  
13. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.ElementsArray) -> None  
  
14. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.ConditionsArray) -> None  
  
15. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.MasterSlaveConstraintsArray) -> None  
  
16. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.NodesArray) -> None  
  
17. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.ElementsArray) -> None  
  
18. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.ConditionsArray) -> None  
  
19. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.MasterSlaveConstraintsArray) -> None  
  
20. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.NodesArray) -> None  
  
21. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.ElementsArray) -> None  
  
22. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.ConditionsArray) -> None  
  
23. SetNonHistoricalVariableToZero(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.MasterSlaveConstraintsArray) -> None`

**SetNonHistoricalVectorVar**(...)

    `SetNonHistoricalVectorVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray) -> None`

**SetScalarVar**(...)

    `SetScalarVar(*args, **kwargs)  
Overloaded  function.  
  
1. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
2. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
3. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
4. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
5. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
6. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
7. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
8. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
9. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
10. SetScalarVar(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None`

**SetVariable**(...)

    `SetVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.IntegerVariable, arg1: int, arg2: Kratos.NodesArray) -> None  
  
2. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.NodesArray) -> None  
  
3. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray) -> None  
  
4. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray) -> None  
  
5. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray) -> None  
  
6. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.NodesArray) -> None  
  
7. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.BoolVariable, arg1: bool, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
8. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
9. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
10. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
11. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
12. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
13. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None  
  
14. SetVariable(self: Kratos.VariableUtils, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None`

**SetVectorVar**(...)

    `SetVectorVar(*args, **kwargs)  
Overloaded  function.  
  
1. SetVectorVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray) -> None  
  
2. SetVectorVar(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.NodesArray, arg3: Kratos.Flags, arg4: bool) -> None`

**SumConditionScalarVariable**(...)

    `SumConditionScalarVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SumConditionScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart) -> float  
  
2. SumConditionScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.ModelPart) -> float  
  
3. SumConditionScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.ModelPart) -> float  
  
4. SumConditionScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.ModelPart) -> float  
  
5. SumConditionScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.ModelPart) -> float`

**SumConditionVectorVariable**(...)

    `SumConditionVectorVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart) -> Kratos.Array3`

**SumElementScalarVariable**(...)

    `SumElementScalarVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SumElementScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart) -> float  
  
2. SumElementScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.ModelPart) -> float  
  
3. SumElementScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.ModelPart) -> float  
  
4. SumElementScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.ModelPart) -> float  
  
5. SumElementScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.ModelPart) -> float`

**SumElementVectorVariable**(...)

    `SumElementVectorVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart) -> Kratos.Array3`

**SumHistoricalNodeScalarVariable**(...)

    `SumHistoricalNodeScalarVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SumHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart, arg2: int) -> float  
  
2. SumHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.ModelPart, arg2: int) -> float  
  
3. SumHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.ModelPart, arg2: int) -> float  
  
4. SumHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.ModelPart, arg2: int) -> float  
  
5. SumHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.ModelPart, arg2: int) -> float`

**SumHistoricalNodeVectorVariable**(...)

    `SumHistoricalNodeVectorVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart, arg2: int) -> Kratos.Array3`

**SumNonHistoricalNodeScalarVariable**(...)

    `SumNonHistoricalNodeScalarVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SumNonHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart) -> float  
  
2. SumNonHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.ModelPart) -> float  
  
3. SumNonHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.ModelPart) -> float  
  
4. SumNonHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.ModelPart) -> float  
  
5. SumNonHistoricalNodeScalarVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.ModelPart) -> float`

**SumNonHistoricalNodeVectorVariable**(...)

    `SumNonHistoricalNodeVectorVariable(self: Kratos.VariableUtils, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart) -> Kratos.Array3`

**UpdateCurrentPosition**(...)

    `UpdateCurrentPosition(*args, **kwargs)  
Overloaded  function.  
  
1. UpdateCurrentPosition(self: Kratos.VariableUtils, arg0: Kratos.NodesArray) -> None  
  
2. UpdateCurrentPosition(self: Kratos.VariableUtils, arg0: Kratos.NodesArray, arg1: Kratos.Array1DVariable3) -> None  
  
3. UpdateCurrentPosition(self: Kratos.VariableUtils, arg0: Kratos.NodesArray, arg1: Kratos.Array1DVariable3, arg2: int) -> None`

**UpdateCurrentToInitialConfiguration**(...)

    `UpdateCurrentToInitialConfiguration(self: Kratos.VariableUtils, arg0: Kratos.NodesArray) -> None`

**UpdateInitialToCurrentConfiguration**(...)

    `UpdateInitialToCurrentConfiguration(self: Kratos.VariableUtils, arg0: Kratos.NodesArray) -> None`

**__init__**(...)

    `__init__(self: Kratos.VariableUtils) -> None`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

