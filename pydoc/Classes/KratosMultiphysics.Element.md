  
**KratosMultiphysics.Element** = class
Element([GeometricalObject](KratosMultiphysics.GeometricalObject))  
---  
`    `|   |

Method resolution order:

    [Element](KratosMultiphysics.Element)
    [GeometricalObject](KratosMultiphysics.GeometricalObject)
    [IndexedObject](KratosMultiphysics.IndexedObject)
    [Flags](KratosMultiphysics.Flags)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**Calculate**(...)

    `Calculate(*args, **kwargs)  
Overloaded  function.  
  
1. Calculate(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: Kratos::ProcessInfo) -> float  
  
2. Calculate(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: Kratos::ProcessInfo) -> Kratos.Array3  
  
3. Calculate(self: Kratos.Element, arg0: Kratos.VectorVariable, arg1: Kratos::ProcessInfo) -> Kratos.Vector  
  
4. Calculate(self: Kratos.Element, arg0: Kratos.MatrixVariable, arg1: Kratos::ProcessInfo) -> Kratos.Matrix`

**CalculateDampingMatrix**(...)

    `CalculateDampingMatrix(self: Kratos.Element, arg0: Kratos.Matrix, arg1: Kratos::ProcessInfo) -> None`

**CalculateFirstDerivativesLHS**(...)

    `CalculateFirstDerivativesLHS(self: Kratos.Element, arg0: Kratos.Matrix, arg1: Kratos::ProcessInfo) -> None`

**CalculateLocalSystem**(...)

    `CalculateLocalSystem(self: Kratos.Element, arg0: Kratos.Matrix, arg1: Kratos.Vector, arg2: Kratos::ProcessInfo) -> None`

**CalculateLocalVelocityContribution**(...)

    `CalculateLocalVelocityContribution(self: Kratos.Element, arg0: Kratos.Matrix, arg1: Kratos.Vector, arg2: Kratos::ProcessInfo) -> None`

**CalculateMassMatrix**(...)

    `CalculateMassMatrix(self: Kratos.Element, arg0: Kratos.Matrix, arg1: Kratos::ProcessInfo) -> None`

**CalculateOnIntegrationPoints**(...)

    `CalculateOnIntegrationPoints(*args, **kwargs)  
Overloaded  function.  
  
1. CalculateOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: Kratos::ProcessInfo) -> list  
  
2. CalculateOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: Kratos::ProcessInfo) -> list  
  
3. CalculateOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.VectorVariable, arg1: Kratos::ProcessInfo) -> list  
  
4. CalculateOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.MatrixVariable, arg1: Kratos::ProcessInfo) -> list`

**CalculateSecondDerivativesLHS**(...)

    `CalculateSecondDerivativesLHS(self: Kratos.Element, arg0: Kratos.Matrix, arg1: Kratos::ProcessInfo) -> None`

**CalculateSensitivityMatrix**(...)

    `CalculateSensitivityMatrix(*args, **kwargs)  
Overloaded  function.  
  
1. CalculateSensitivityMatrix(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: Kratos.Matrix, arg2: Kratos::ProcessInfo) -> None  
  
2. CalculateSensitivityMatrix(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: Kratos.Matrix, arg2: Kratos::ProcessInfo) -> None`

**GetArea**(...)

    `GetArea(self: Kratos.Element) -> float`

**GetFirstDerivativesVector**(...)

    `GetFirstDerivativesVector(*args, **kwargs)  
Overloaded  function.  
  
1. GetFirstDerivativesVector(self: Kratos.Element, arg0: Kratos.Vector) -> None  
  
2. GetFirstDerivativesVector(self: Kratos.Element, arg0: Kratos.Vector, arg1: int) -> None`

**GetGeometry**(...)

    `GetGeometry(self: Kratos.Element) -> Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >`

**GetIntegrationPoints**(...)

    `GetIntegrationPoints(self: Kratos.Element) -> list`

**GetNode**(...)

    `GetNode(self: Kratos.Element, arg0: int) -> Kratos.Node`

**GetNodes**(...)

    `GetNodes(self: Kratos.Element) -> list`

**GetSecondDerivativesVector**(...)

    `GetSecondDerivativesVector(*args, **kwargs)  
Overloaded  function.  
  
1. GetSecondDerivativesVector(self: Kratos.Element, arg0: Kratos.Vector) -> None  
  
2. GetSecondDerivativesVector(self: Kratos.Element, arg0: Kratos.Vector, arg1: int) -> None`

**GetValue**(...)

    `GetValue(*args, **kwargs)  
Overloaded  function.  
  
1. GetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
2. GetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
3. GetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
4. GetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
5. GetValue(self: Kratos.Element, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
6. GetValue(self: Kratos.Element, arg0: Kratos.IntegerVectorVariable) -> Kratos.DenseVectorInt  
  
7. GetValue(self: Kratos.Element, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
8. GetValue(self: Kratos.Element, arg0: Kratos.IntegerVariable) -> int  
  
9. GetValue(self: Kratos.Element, arg0: Kratos.DoubleVariable) -> float  
  
10. GetValue(self: Kratos.Element, arg0: Kratos.BoolVariable) -> bool  
  
11. GetValue(self: Kratos.Element, arg0: Kratos.StringVariable) -> str`

**GetValuesOnIntegrationPoints**(...)

    `GetValuesOnIntegrationPoints(*args, **kwargs)  
Overloaded  function.  
  
1. GetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.BoolVariable, arg1: Kratos::ProcessInfo) -> list  
  
2. GetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: Kratos::ProcessInfo) -> list  
  
3. GetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: Kratos::ProcessInfo) -> list  
  
4. GetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.VectorVariable, arg1: Kratos::ProcessInfo) -> list  
  
5. GetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.MatrixVariable, arg1: Kratos::ProcessInfo) -> list`

**Has**(...)

    `Has(*args, **kwargs)  
Overloaded  function.  
  
1. Has(self: Kratos.Element, arg0: Kratos.Array1DVariable3) -> bool  
  
2. Has(self: Kratos.Element, arg0: Kratos.Array1DVariable4) -> bool  
  
3. Has(self: Kratos.Element, arg0: Kratos.Array1DVariable6) -> bool  
  
4. Has(self: Kratos.Element, arg0: Kratos.Array1DVariable9) -> bool  
  
5. Has(self: Kratos.Element, arg0: Kratos.VectorVariable) -> bool  
  
6. Has(self: Kratos.Element, arg0: Kratos.IntegerVectorVariable) -> bool  
  
7. Has(self: Kratos.Element, arg0: Kratos.MatrixVariable) -> bool  
  
8. Has(self: Kratos.Element, arg0: Kratos.IntegerVariable) -> bool  
  
9. Has(self: Kratos.Element, arg0: Kratos.DoubleVariable) -> bool  
  
10. Has(self: Kratos.Element, arg0: Kratos.BoolVariable) -> bool  
  
11. Has(self: Kratos.Element, arg0: Kratos.StringVariable) -> bool`

**Initialize**(...)

    `Initialize(*args, **kwargs)  
Overloaded  function.  
  
1. Initialize(self: Kratos.Element, arg0: Kratos::ProcessInfo) -> None  
  
2. Initialize(self: Kratos.Element) -> None`

**ResetConstitutiveLaw**(...)

    `ResetConstitutiveLaw(self: Kratos.Element) -> None`

**SetValue**(...)

    `SetValue(*args, **kwargs)  
Overloaded  function.  
  
1. SetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
2. SetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
3. SetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
4. SetValue(self: Kratos.Element, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
5. SetValue(self: Kratos.Element, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
6. SetValue(self: Kratos.Element, arg0: Kratos.IntegerVectorVariable, arg1: Kratos.DenseVectorInt) -> None  
  
7. SetValue(self: Kratos.Element, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
8. SetValue(self: Kratos.Element, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
9. SetValue(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
10. SetValue(self: Kratos.Element, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
11. SetValue(self: Kratos.Element, arg0: Kratos.StringVariable, arg1: str) -> None`

**SetValuesOnIntegrationPoints**(...)

    `SetValuesOnIntegrationPoints(*args, **kwargs)  
Overloaded  function.  
  
1. SetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.VectorVariable, arg1: list, arg2: int, arg3: Kratos::ProcessInfo) -> None  
  
2. SetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.ConstitutuveLawVariable, arg1: list, arg2: Kratos::ProcessInfo) -> None  
  
3. SetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: List[float], arg2: Kratos::ProcessInfo) -> None  
  
4. SetValuesOnIntegrationPoints(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: list, arg2: Kratos::ProcessInfo) -> None`

**__getitem__**(...)

    `__getitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __getitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
2. __getitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
3. __getitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
4. __getitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
5. __getitem__(self: Kratos.Element, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
6. __getitem__(self: Kratos.Element, arg0: Kratos.IntegerVectorVariable) -> Kratos.DenseVectorInt  
  
7. __getitem__(self: Kratos.Element, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
8. __getitem__(self: Kratos.Element, arg0: Kratos.IntegerVariable) -> int  
  
9. __getitem__(self: Kratos.Element, arg0: Kratos.DoubleVariable) -> float  
  
10. __getitem__(self: Kratos.Element, arg0: Kratos.BoolVariable) -> bool  
  
11. __getitem__(self: Kratos.Element, arg0: Kratos.StringVariable) -> str`

**__init__**(...)

    `__init__(self: Kratos.Element, arg0: int) -> None`

**__setitem__**(...)

    `__setitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __setitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
2. __setitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
3. __setitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
4. __setitem__(self: Kratos.Element, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
5. __setitem__(self: Kratos.Element, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
6. __setitem__(self: Kratos.Element, arg0: Kratos.IntegerVectorVariable, arg1: Kratos.DenseVectorInt) -> None  
  
7. __setitem__(self: Kratos.Element, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
8. __setitem__(self: Kratos.Element, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
9. __setitem__(self: Kratos.Element, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
10. __setitem__(self: Kratos.Element, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
11. __setitem__(self: Kratos.Element, arg0: Kratos.StringVariable, arg1: str) -> None`

**__str__**(...)

    `__str__(self: Kratos.Element) -> str`

* * *

Data descriptors defined here:  

**Properties**

    ``

* * *

Data descriptors inherited from [IndexedObject](KratosMultiphysics.IndexedObject):  

**Id**

    ``

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

