  
**KratosMultiphysics.Mesh** = class
Mesh([DataValueContainer](KratosMultiphysics.DataValueContainer),
[Flags](KratosMultiphysics.Flags))  
---  
`    `|   |

Method resolution order:

    [Mesh](KratosMultiphysics.Mesh)
    [DataValueContainer](KratosMultiphysics.DataValueContainer)
    [Flags](KratosMultiphysics.Flags)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**ConditionsArray**(...)

    `ConditionsArray(self: Kratos.Mesh) -> List[Kratos.Condition]`

**ElementsArray**(...)

    `ElementsArray(self: Kratos.Mesh) -> List[Kratos.Element]`

**HasCondition**(...)

    `HasCondition(self: Kratos.Mesh, arg0: int) -> bool`

**HasElement**(...)

    `HasElement(self: Kratos.Mesh, arg0: int) -> bool`

**HasNode**(...)

    `HasNode(self: Kratos.Mesh, arg0: int) -> bool`

**HasProperties**(...)

    `HasProperties(self: Kratos.Mesh, arg0: int) -> bool`

**NodesArray**(...)

    `NodesArray(self: Kratos.Mesh) -> List[Kratos.Node]`

**NumberOfConditions**(...)

    `NumberOfConditions(self: Kratos.Mesh) -> int`

**NumberOfElements**(...)

    `NumberOfElements(self: Kratos.Mesh) -> int`

**NumberOfNodes**(...)

    `NumberOfNodes(self: Kratos.Mesh) -> int`

**NumberOfProperties**(...)

    `NumberOfProperties(self: Kratos.Mesh) -> int`

**PropertiesArray**(...)

    `PropertiesArray(self: Kratos.Mesh) -> List[Kratos.Properties]`

**__init__**(self, /, *args, **kwargs)

    ` Initialize self.  See help(type(self)) for accurate signature.`

**__str__**(...)

    `__str__(self: Kratos.Mesh) -> str`

* * *

Data descriptors defined here:  

**Conditions**

    ``

**Elements**

    ``

**Nodes**

    ``

**Properties**

    ``

* * *

Methods inherited from [DataValueContainer](KratosMultiphysics.DataValueContainer):  

**Clear**(...)

    `Clear(*args, **kwargs)  
Overloaded  function.  
  
1. Clear(self: Kratos.DataValueContainer) -> None  
  
2. Clear(self: Kratos.DataValueContainer) -> None  
  
3. Clear(self: Kratos.DataValueContainer) -> None  
  
4. Clear(self: Kratos.DataValueContainer) -> None  
  
5. Clear(self: Kratos.DataValueContainer) -> None  
  
6. Clear(self: Kratos.DataValueContainer) -> None  
  
7. Clear(self: Kratos.DataValueContainer) -> None  
  
8. Clear(self: Kratos.DataValueContainer) -> None  
  
9. Clear(self: Kratos.DataValueContainer) -> None  
  
10. Clear(self: Kratos.DataValueContainer) -> None  
  
11. Clear(self: Kratos.DataValueContainer) -> None  
  
12. Clear(self: Kratos.DataValueContainer) -> None  
  
13. Clear(self: Kratos.DataValueContainer) -> None  
  
14. Clear(self: Kratos.DataValueContainer) -> None  
  
15. Clear(self: Kratos.DataValueContainer) -> None  
  
16. Clear(self: Kratos.DataValueContainer) -> None  
  
17. Clear(self: Kratos.DataValueContainer) -> None`

**GetValue**(...)

    `GetValue(*args, **kwargs)  
Overloaded  function.  
  
1. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.BoolVariable) -> bool  
  
2. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.IntegerVariable) -> int  
  
3. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.DoubleVariable) -> float  
  
4. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
5. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
6. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
7. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
8. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
9. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
10. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.ConvectionDiffusionSettingsVariable) -> Kratos::ConvectionDiffusionSettings  
  
11. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.RadiationSettingsVariable) -> Kratos::RadiationSettings  
  
12. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DComponentVariable) -> float  
  
13. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1D4ComponentVariable) -> float  
  
14. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1D6ComponentVariable) -> float  
  
15. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1D9ComponentVariable) -> float  
  
16. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.DoubleQuaternionVariable) -> Kratos::Quaternion<double>  
  
17. GetValue(self: Kratos.DataValueContainer, arg0: Kratos.StringVariable) -> str`

**Has**(...)

    `Has(*args, **kwargs)  
Overloaded  function.  
  
1. Has(self: Kratos.DataValueContainer, arg0: Kratos.BoolVariable) -> bool  
  
2. Has(self: Kratos.DataValueContainer, arg0: Kratos.IntegerVariable) -> bool  
  
3. Has(self: Kratos.DataValueContainer, arg0: Kratos.DoubleVariable) -> bool  
  
4. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable3) -> bool  
  
5. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable4) -> bool  
  
6. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable6) -> bool  
  
7. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable9) -> bool  
  
8. Has(self: Kratos.DataValueContainer, arg0: Kratos.VectorVariable) -> bool  
  
9. Has(self: Kratos.DataValueContainer, arg0: Kratos.MatrixVariable) -> bool  
  
10. Has(self: Kratos.DataValueContainer, arg0: Kratos.ConvectionDiffusionSettingsVariable) -> bool  
  
11. Has(self: Kratos.DataValueContainer, arg0: Kratos.RadiationSettingsVariable) -> bool  
  
12. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1DComponentVariable) -> bool  
  
13. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
14. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
15. Has(self: Kratos.DataValueContainer, arg0: Kratos.Array1D9ComponentVariable) -> bool  
  
16. Has(self: Kratos.DataValueContainer, arg0: Kratos.DoubleQuaternionVariable) -> bool  
  
17. Has(self: Kratos.DataValueContainer, arg0: Kratos.StringVariable) -> bool`

**SetValue**(...)

    `SetValue(*args, **kwargs)  
Overloaded  function.  
  
1. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
2. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
3. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
4. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
5. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
6. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
7. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
8. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
9. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
10. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.ConvectionDiffusionSettingsVariable, arg1: Kratos::ConvectionDiffusionSettings) -> None  
  
11. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.RadiationSettingsVariable, arg1: Kratos::RadiationSettings) -> None  
  
12. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1DComponentVariable, arg1: float) -> None  
  
13. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1D4ComponentVariable, arg1: float) -> None  
  
14. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1D6ComponentVariable, arg1: float) -> None  
  
15. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.Array1D9ComponentVariable, arg1: float) -> None  
  
16. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.DoubleQuaternionVariable, arg1: Kratos::Quaternion<double>) -> None  
  
17. SetValue(self: Kratos.DataValueContainer, arg0: Kratos.StringVariable, arg1: str) -> None`

**__contains__**(...)

    `__contains__(*args, **kwargs)  
Overloaded  function.  
  
1. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.BoolVariable) -> bool  
  
2. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.IntegerVariable) -> bool  
  
3. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.DoubleVariable) -> bool  
  
4. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable3) -> bool  
  
5. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable4) -> bool  
  
6. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable6) -> bool  
  
7. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable9) -> bool  
  
8. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.VectorVariable) -> bool  
  
9. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.MatrixVariable) -> bool  
  
10. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.ConvectionDiffusionSettingsVariable) -> bool  
  
11. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.RadiationSettingsVariable) -> bool  
  
12. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DComponentVariable) -> bool  
  
13. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D4ComponentVariable) -> bool  
  
14. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D6ComponentVariable) -> bool  
  
15. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D9ComponentVariable) -> bool  
  
16. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.DoubleQuaternionVariable) -> bool  
  
17. __contains__(self: Kratos.DataValueContainer, arg0: Kratos.StringVariable) -> bool`

**__getitem__**(...)

    `__getitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.BoolVariable) -> bool  
  
2. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.IntegerVariable) -> int  
  
3. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.DoubleVariable) -> float  
  
4. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
5. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable4) -> Kratos.Array4  
  
6. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
7. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable9) -> Kratos.Array9  
  
8. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
9. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
10. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.ConvectionDiffusionSettingsVariable) -> Kratos::ConvectionDiffusionSettings  
  
11. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.RadiationSettingsVariable) -> Kratos::RadiationSettings  
  
12. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DComponentVariable) -> float  
  
13. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D4ComponentVariable) -> float  
  
14. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D6ComponentVariable) -> float  
  
15. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D9ComponentVariable) -> float  
  
16. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.DoubleQuaternionVariable) -> Kratos::Quaternion<double>  
  
17. __getitem__(self: Kratos.DataValueContainer, arg0: Kratos.StringVariable) -> str`

**__len__**(...)

    `__len__(self: Kratos.DataValueContainer) -> int`

**__setitem__**(...)

    `__setitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
2. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
3. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
4. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
5. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable4, arg1: Kratos.Array4) -> None  
  
6. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
7. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DVariable9, arg1: Kratos.Array9) -> None  
  
8. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
9. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
10. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.ConvectionDiffusionSettingsVariable, arg1: Kratos::ConvectionDiffusionSettings) -> None  
  
11. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.RadiationSettingsVariable, arg1: Kratos::RadiationSettings) -> None  
  
12. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1DComponentVariable, arg1: float) -> None  
  
13. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D4ComponentVariable, arg1: float) -> None  
  
14. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D6ComponentVariable, arg1: float) -> None  
  
15. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.Array1D9ComponentVariable, arg1: float) -> None  
  
16. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.DoubleQuaternionVariable, arg1: Kratos::Quaternion<double>) -> None  
  
17. __setitem__(self: Kratos.DataValueContainer, arg0: Kratos.StringVariable, arg1: str) -> None`

* * *

Methods inherited from [Flags](KratosMultiphysics.Flags):  

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

