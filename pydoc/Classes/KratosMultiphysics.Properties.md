  
**KratosMultiphysics.Properties** = class
Properties([IndexedObject](KratosMultiphysics.IndexedObject))  
---  
`    `|   |

Method resolution order:

    [Properties](KratosMultiphysics.Properties)
    [IndexedObject](KratosMultiphysics.IndexedObject)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AddSubProperties**(...)

    `AddSubProperties(self: Kratos.Properties, arg0: Kratos.Properties) -> None`

**GetSubProperties**(...)

    `GetSubProperties(*args, **kwargs)  
Overloaded  function.  
  
1. GetSubProperties(self: Kratos.Properties, arg0: int) -> Kratos.Properties  
  
2. GetSubProperties(self: Kratos.Properties) -> Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >  
  
3. GetSubProperties(self: Kratos.Properties) -> Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >`

**GetTable**(...)

    `GetTable(*args, **kwargs)  
Overloaded  function.  
  
1. GetTable(self: Kratos.Properties, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable) -> Kratos::Table<double, double, 1ul>  
  
2. GetTable(self: Kratos.Properties, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.DoubleVariable) -> Kratos::Table<double, double, 1ul>  
  
3. GetTable(self: Kratos.Properties, arg0: Kratos.DoubleVariable, arg1: Kratos.Array1DComponentVariable) -> Kratos::Table<double, double, 1ul>  
  
4. GetTable(self: Kratos.Properties, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.Array1DComponentVariable) -> Kratos::Table<double, double, 1ul>`

**GetValue**(...)

    `GetValue(*args, **kwargs)  
Overloaded  function.  
  
1. GetValue(self: Kratos.Properties, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
2. GetValue(self: Kratos.Properties, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
3. GetValue(self: Kratos.Properties, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
4. GetValue(self: Kratos.Properties, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
5. GetValue(self: Kratos.Properties, arg0: Kratos.StringVariable) -> str  
  
6. GetValue(self: Kratos.Properties, arg0: Kratos.BoolVariable) -> bool  
  
7. GetValue(self: Kratos.Properties, arg0: Kratos.IntegerVariable) -> int  
  
8. GetValue(self: Kratos.Properties, arg0: Kratos.DoubleVariable) -> float  
  
9. GetValue(self: Kratos.Properties, arg0: Kratos.ConstitutuveLawVariable) -> Kratos::ConstitutiveLaw`

**Has**(...)

    `Has(*args, **kwargs)  
Overloaded  function.  
  
1. Has(self: Kratos.Properties, arg0: Kratos.Array1DVariable6) -> bool  
  
2. Has(self: Kratos.Properties, arg0: Kratos.Array1DVariable3) -> bool  
  
3. Has(self: Kratos.Properties, arg0: Kratos.VectorVariable) -> bool  
  
4. Has(self: Kratos.Properties, arg0: Kratos.MatrixVariable) -> bool  
  
5. Has(self: Kratos.Properties, arg0: Kratos.StringVariable) -> bool  
  
6. Has(self: Kratos.Properties, arg0: Kratos.BoolVariable) -> bool  
  
7. Has(self: Kratos.Properties, arg0: Kratos.IntegerVariable) -> bool  
  
8. Has(self: Kratos.Properties, arg0: Kratos.DoubleVariable) -> bool  
  
9. Has(self: Kratos.Properties, arg0: Kratos.ConstitutuveLawVariable) -> bool`

**HasSubProperties**(...)

    `HasSubProperties(self: Kratos.Properties, arg0: int) -> bool`

**HasTables**(...)

    `HasTables(self: Kratos.Properties) -> bool`

**HasVariables**(...)

    `HasVariables(self: Kratos.Properties) -> bool`

**IsEmpty**(...)

    `IsEmpty(self: Kratos.Properties) -> bool`

**NumberOfSubproperties**(...)

    `NumberOfSubproperties(self: Kratos.Properties) -> int`

**SetSubProperties**(...)

    `SetSubProperties(self: Kratos.Properties, arg0: Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >) -> None`

**SetTable**(...)

    `SetTable(*args, **kwargs)  
Overloaded  function.  
  
1. SetTable(self: Kratos.Properties, arg0: Kratos.DoubleVariable, arg1: Kratos.DoubleVariable, arg2: Kratos::Table<double, double, 1ul>) -> None  
  
2. SetTable(self: Kratos.Properties, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.DoubleVariable, arg2: Kratos::Table<double, double, 1ul>) -> None  
  
3. SetTable(self: Kratos.Properties, arg0: Kratos.DoubleVariable, arg1: Kratos.Array1DComponentVariable, arg2: Kratos::Table<double, double, 1ul>) -> None  
  
4. SetTable(self: Kratos.Properties, arg0: Kratos.Array1DComponentVariable, arg1: Kratos.Array1DComponentVariable, arg2: Kratos::Table<double, double, 1ul>) -> None`

**SetValue**(...)

    `SetValue(*args, **kwargs)  
Overloaded  function.  
  
1. SetValue(self: Kratos.Properties, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
2. SetValue(self: Kratos.Properties, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
3. SetValue(self: Kratos.Properties, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
4. SetValue(self: Kratos.Properties, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
5. SetValue(self: Kratos.Properties, arg0: Kratos.StringVariable, arg1: str) -> None  
  
6. SetValue(self: Kratos.Properties, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
7. SetValue(self: Kratos.Properties, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
8. SetValue(self: Kratos.Properties, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
9. SetValue(self: Kratos.Properties, arg0: Kratos.ConstitutuveLawVariable, arg1: Kratos::ConstitutiveLaw) -> None`

**__getitem__**(...)

    `__getitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __getitem__(self: Kratos.Properties, arg0: Kratos.Array1DVariable6) -> Kratos.Array6  
  
2. __getitem__(self: Kratos.Properties, arg0: Kratos.Array1DVariable3) -> Kratos.Array3  
  
3. __getitem__(self: Kratos.Properties, arg0: Kratos.VectorVariable) -> Kratos.Vector  
  
4. __getitem__(self: Kratos.Properties, arg0: Kratos.MatrixVariable) -> Kratos.Matrix  
  
5. __getitem__(self: Kratos.Properties, arg0: Kratos.StringVariable) -> str  
  
6. __getitem__(self: Kratos.Properties, arg0: Kratos.BoolVariable) -> bool  
  
7. __getitem__(self: Kratos.Properties, arg0: Kratos.IntegerVariable) -> int  
  
8. __getitem__(self: Kratos.Properties, arg0: Kratos.DoubleVariable) -> float  
  
9. __getitem__(self: Kratos.Properties, arg0: Kratos.ConstitutuveLawVariable) -> Kratos::ConstitutiveLaw`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.Properties, arg0: int) -> None  
  
2. __init__(self: Kratos.Properties, arg0: Kratos.Properties) -> None`

**__setitem__**(...)

    `__setitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __setitem__(self: Kratos.Properties, arg0: Kratos.Array1DVariable6, arg1: Kratos.Array6) -> None  
  
2. __setitem__(self: Kratos.Properties, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> None  
  
3. __setitem__(self: Kratos.Properties, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> None  
  
4. __setitem__(self: Kratos.Properties, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> None  
  
5. __setitem__(self: Kratos.Properties, arg0: Kratos.StringVariable, arg1: str) -> None  
  
6. __setitem__(self: Kratos.Properties, arg0: Kratos.BoolVariable, arg1: bool) -> None  
  
7. __setitem__(self: Kratos.Properties, arg0: Kratos.IntegerVariable, arg1: int) -> None  
  
8. __setitem__(self: Kratos.Properties, arg0: Kratos.DoubleVariable, arg1: float) -> None  
  
9. __setitem__(self: Kratos.Properties, arg0: Kratos.ConstitutuveLawVariable, arg1: Kratos::ConstitutiveLaw) -> None`

**__str__**(...)

    `__str__(self: Kratos.Properties) -> str`

* * *

Data descriptors inherited from [IndexedObject](KratosMultiphysics.IndexedObject):  

**Id**

    ``

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

