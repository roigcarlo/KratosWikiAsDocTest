  
**KratosMultiphysics.Node** = class Node([Point](KratosMultiphysics.Point),
[Flags](KratosMultiphysics.Flags))  
---  
`    `|   |

Method resolution order:

    [Node](KratosMultiphysics.Node)
    [Point](KratosMultiphysics.Point)
    [Array3](KratosMultiphysics.Array3)
    [Flags](KratosMultiphysics.Flags)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AddDof**(...)

    `AddDof(*args, **kwargs)  
Overloaded  function.  
  
1. AddDof(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> None  
  
2. AddDof(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> None  
  
3. AddDof(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> None  
  
4. AddDof(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> None  
  
5. AddDof(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> None  
  
6. AddDof(self: Kratos.Node, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable) -> None  
  
7. AddDof(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.Array1DComponentVariable) -> None  
  
8. AddDof(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable, arg1: Kratos.Array1D4ComponentVariable) -> None  
  
9. AddDof(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable, arg1: Kratos.Array1D6ComponentVariable) -> None  
  
10. AddDof(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable, arg1: Kratos.Array1D9ComponentVariable) -> None`

**Fix**(...)

    `Fix(*args, **kwargs)  
Overloaded  function.  
  
1. Fix(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> None  
  
2. Fix(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> None  
  
3. Fix(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> None  
  
4. Fix(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> None  
  
5. Fix(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> None`

**Free**(...)

    `Free(*args, **kwargs)  
Overloaded  function.  
  
1. Free(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> None  
  
2. Free(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> None  
  
3. Free(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> None  
  
4. Free(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> None  
  
5. Free(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> None`

**GetBufferSize**(...)

    `GetBufferSize(self: Kratos.Node) -> int`

**GetSolutionStepValue**(...)

    `GetSolutionStepValue(*args, **kwargs)  
Overloaded  function.  
  
1. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.BoolVariable, arg1: int) -> bool  
  
3. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> int  
  
4. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.IntegerVariable, arg1: int) -> int  
  
5. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> float  
  
6. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.DoubleVariable, arg1: int) -> float  
  
7. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
8. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3, arg1: int) -> Kratos.Array3  
  
9. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
10. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4, arg1: int) -> Kratos.Array4  
  
11. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
12. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6, arg1: int) -> Kratos.Array6  
  
13. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
14. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9, arg1: int) -> Kratos.Array9  
  
15. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> float  
  
16. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable, arg1: int) -> float  
  
17. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> float  
  
18. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable, arg1: int) -> float  
  
19. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> float  
  
20. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable, arg1: int) -> float  
  
21. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> float  
  
22. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable, arg1: int) -> float  
  
23. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
24. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.VectorVariable, arg1: int) -> Kratos.Vector  
  
25. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
26. GetSolutionStepValue(self: Kratos.Node, arg0: Kratos.MatrixVariable, arg1: int) -> Kratos.Matrix`

**GetValue**(...)

    `GetValue(*args, **kwargs)  
Overloaded  function.  
  
1. GetValue(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. GetValue(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> int  
  
3. GetValue(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> float  
  
4. GetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
5. GetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
6. GetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
7. GetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
8. GetValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> float  
  
9. GetValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> float  
  
10. GetValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> float  
  
11. GetValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> float  
  
12. GetValue(self: Kratos.Node, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
13. GetValue(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> Kratos.Matrix`

**Has**(...)

    `Has(*args, **kwargs)  
Overloaded  function.  
  
1. Has(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. Has(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> bool  
  
3. Has(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> bool  
  
4. Has(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> bool  
  
5. Has(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> bool  
  
6. Has(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> bool  
  
7. Has(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> bool  
  
8. Has(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> bool  
  
9. Has(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
10. Has(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
11. Has(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> bool  
  
12. Has(self: Kratos.Node, arg0: Kratos.VectorVariable) -> bool  
  
13. Has(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> bool`

**HasDofFor**(...)

    `HasDofFor(*args, **kwargs)  
Overloaded  function.  
  
1. HasDofFor(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> bool  
  
2. HasDofFor(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> bool  
  
3. HasDofFor(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
4. HasDofFor(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
5. HasDofFor(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> bool`

**HasSolutionStepValue**(...)

    `HasSolutionStepValue(*args, **kwargs)  
Overloaded  function.  
  
1. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> bool  
  
3. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> bool  
  
4. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> bool  
  
5. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> bool  
  
6. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> bool  
  
7. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> bool  
  
8. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> bool  
  
9. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
10. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
11. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> bool  
  
12. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.VectorVariable) -> bool  
  
13. HasSolutionStepValue(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> bool`

**IsFixed**(...)

    `IsFixed(*args, **kwargs)  
Overloaded  function.  
  
1. IsFixed(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> bool  
  
2. IsFixed(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> bool  
  
3. IsFixed(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
4. IsFixed(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
5. IsFixed(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> bool`

**OverwriteSolutionStepData**(...)

    `OverwriteSolutionStepData(self: Kratos.Node, arg0: int, arg1: int) -> None`

**SetSolutionStepValue**(...)

    `SetSolutionStepValue(*args, **kwargs)  
Overloaded  function.  
  
1. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
2. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.BoolVariable, arg1: int, arg2: bool) -> None  
  
3. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
4. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.IntegerVariable, arg1: int, arg2: int) -> None  
  
5. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
6. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.DoubleVariable, arg1: int, arg2: float) -> None  
  
7. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
8. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3, arg1: int, arg2: Kratos.Array3) -> None  
  
9. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
10. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4, arg1: int, arg2: Kratos.Array4) -> None  
  
11. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
12. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6, arg1: int, arg2: Kratos.Array6) -> None  
  
13. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
14. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9, arg1: int, arg2: Kratos.Array9) -> None  
  
15. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable, arg1: float) -> None  
  
16. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable, arg1: int, arg2: float) -> None  
  
17. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable, arg1: float) -> None  
  
18. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable, arg1: int, arg2: float) -> None  
  
19. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable, arg1: float) -> None  
  
20. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable, arg1: int, arg2: float) -> None  
  
21. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable, arg1: float) -> None  
  
22. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable, arg1: int, arg2: float) -> None  
  
23. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
24. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.VectorVariable, arg1: int, arg2: Kratos.Vector) -> None  
  
25. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
26. SetSolutionStepValue(self: Kratos.Node, arg0: Kratos.MatrixVariable, arg1: int, arg2: Kratos.Matrix) -> None`

**SetValue**(...)

    `SetValue(*args, **kwargs)  
Overloaded  function.  
  
1. SetValue(self: Kratos.Node, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
2. SetValue(self: Kratos.Node, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
3. SetValue(self: Kratos.Node, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
4. SetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
5. SetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
6. SetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
7. SetValue(self: Kratos.Node, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
8. SetValue(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable, arg1: float) -> None  
  
9. SetValue(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable, arg1: float) -> None  
  
10. SetValue(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable, arg1: float) -> None  
  
11. SetValue(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable, arg1: float) -> None  
  
12. SetValue(self: Kratos.Node, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
13. SetValue(self: Kratos.Node, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None`

**SolutionStepsDataHas**(...)

    `SolutionStepsDataHas(*args, **kwargs)  
Overloaded  function.  
  
1. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> bool  
  
3. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> bool  
  
4. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> bool  
  
5. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> bool  
  
6. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> bool  
  
7. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> bool  
  
8. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.VectorVariable) -> bool  
  
9. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> bool  
  
10. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> bool  
  
11. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
12. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
13. SolutionStepsDataHas(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> bool`

**__contains__**(...)

    `__contains__(*args, **kwargs)  
Overloaded  function.  
  
1. __contains__(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. __contains__(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> bool  
  
3. __contains__(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> bool  
  
4. __contains__(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> bool  
  
5. __contains__(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> bool  
  
6. __contains__(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> bool  
  
7. __contains__(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> bool  
  
8. __contains__(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> bool  
  
9. __contains__(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
10. __contains__(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
11. __contains__(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> bool  
  
12. __contains__(self: Kratos.Node, arg0: Kratos.VectorVariable) -> bool  
  
13. __contains__(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> bool`

**__getitem__**(...)

    `__getitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __getitem__(self: Kratos.Node, arg0: Kratos.BoolVariable) -> bool  
  
2. __getitem__(self: Kratos.Node, arg0: Kratos.IntegerVariable) -> int  
  
3. __getitem__(self: Kratos.Node, arg0: Kratos.DoubleVariable) -> float  
  
4. __getitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
5. __getitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
6. __getitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
7. __getitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
8. __getitem__(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable) -> float  
  
9. __getitem__(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable) -> float  
  
10. __getitem__(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable) -> float  
  
11. __getitem__(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable) -> float  
  
12. __getitem__(self: Kratos.Node, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
13. __getitem__(self: Kratos.Node, arg0: Kratos.MatrixVariable) -> Kratos.Matrix`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.Node, arg0: int, arg1: float, arg2: float, arg3: float) -> None  
  
2. __init__(self: Kratos.Node, arg0: int, arg1: Kratos.Point) -> None`

**__setitem__**(...)

    `__setitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __setitem__(self: Kratos.Node, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
2. __setitem__(self: Kratos.Node, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
3. __setitem__(self: Kratos.Node, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
4. __setitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
5. __setitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
6. __setitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
7. __setitem__(self: Kratos.Node, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
8. __setitem__(self: Kratos.Node, arg0: Kratos.Array1DComponentVariable, arg1: float) -> None  
  
9. __setitem__(self: Kratos.Node, arg0: Kratos.Array1D4ComponentVariable, arg1: float) -> None  
  
10. __setitem__(self: Kratos.Node, arg0: Kratos.Array1D6ComponentVariable, arg1: float) -> None  
  
11. __setitem__(self: Kratos.Node, arg0: Kratos.Array1D9ComponentVariable, arg1: float) -> None  
  
12. __setitem__(self: Kratos.Node, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
13. __setitem__(self: Kratos.Node, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None`

**__str__**(...)

    `__str__(self: Kratos.Node) -> str`

* * *

Data descriptors defined here:  

**Id**

    ``

**X0**

    ``

**Y0**

    ``

**Z0**

    ``

* * *

Data descriptors inherited from [Point](KratosMultiphysics.Point):  

**X**

    ``

**Y**

    ``

**Z**

    ``

* * *

Methods inherited from [Array3](KratosMultiphysics.Array3):  

**Resize**(...)

    `Resize(self: Kratos.Array3, arg0: int) -> None`

**Size**(...)

    `Size(self: Kratos.Array3) -> int`

**__add__**(...)

    `__add__(self: Kratos.Array3, arg0: Kratos.Array3) -> Kratos.Vector`

**__div__**(...)

    `__div__(self: Kratos.Array3, arg0: float) -> Kratos.Array3`

**__iadd__**(...)

    `__iadd__(*args, **kwargs)  
Overloaded  function.  
  
1. __iadd__(self: Kratos.Array3, arg0: float) -> Kratos.Array3  
  
2. __iadd__(self: Kratos.Array3, arg0: Kratos.Array3) -> Kratos.Array3`

**__imul__**(...)

    `__imul__(self: Kratos.Array3, arg0: float) -> Kratos.Array3`

**__isub__**(...)

    `__isub__(*args, **kwargs)  
Overloaded  function.  
  
1. __isub__(self: Kratos.Array3, arg0: float) -> Kratos.Array3  
  
2. __isub__(self: Kratos.Array3, arg0: Kratos.Array3) -> Kratos.Array3`

**__iter__**(...)

    `__iter__(self: Kratos.Array3) -> iterator`

**__itruediv__**(...)

    `__itruediv__(self: Kratos.Array3, arg0: float) -> Kratos.Array3`

**__len__**(...)

    `__len__(self: Kratos.Array3) -> int`

**__mul__**(...)

    `__mul__(self: Kratos.Array3, arg0: float) -> Kratos.Array3`

**__rdiv__**(...)

    `__rdiv__(self: Kratos.Array3, arg0: float) -> None`

**__rmul__**(...)

    `__rmul__(self: Kratos.Array3, arg0: float) -> Kratos.Array3`

**__sub__**(...)

    `__sub__(self: Kratos.Array3, arg0: Kratos.Array3) -> Kratos.Vector`

**__truediv__**(...)

    `__truediv__(self: Kratos.Array3, arg0: float) -> Kratos.Array3`

**fill**(...)

    `fill(self: Kratos.Array3, arg0: float) -> None`

**norm_1**(...)

    `norm_1(self: Kratos.Array3) -> float`

**norm_2**(...)

    `norm_2(self: Kratos.Array3) -> float`

* * *

Methods inherited from [Flags](KratosMultiphysics.Flags):  

**Clear**(...)

    `Clear(self: Kratos.Flags) -> None`

**Flip**(...)

    `Flip(self: Kratos.Flags, arg0: Kratos.Flags) -> None`

**Is**(...)

    `Is(self: Kratos.Flags, arg0: Kratos.Flags) -> bool`

**IsDefined**(...)

    `IsDefined(self: Kratos.Flags, arg0: Kratos.Flags) -> bool`

**IsNot**(...)

    `IsNot(self: Kratos.Flags, arg0: Kratos.Flags) -> bool`

**IsNotDefined**(...)

    `IsNotDefined(self: Kratos.Flags, arg0: Kratos.Flags) -> bool`

**Reset**(...)

    `Reset(self: Kratos.Flags, arg0: Kratos.Flags) -> None`

**Set**(...)

    `Set(*args, **kwargs)  
Overloaded  function.  
  
1. Set(self: Kratos.Flags, arg0: Kratos.Flags) -> None  
  
2. Set(self: Kratos.Flags, arg0: Kratos.Flags, arg1: bool) -> None`

**__and__**(...)

    `__and__(self: Kratos.Flags, arg0: Kratos.Flags) -> Kratos.Flags`

**__or__**(...)

    `__or__(self: Kratos.Flags, arg0: Kratos.Flags) -> Kratos.Flags`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

