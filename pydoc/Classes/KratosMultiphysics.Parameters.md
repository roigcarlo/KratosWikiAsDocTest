  
**KratosMultiphysics.Parameters** = class
Parameters(pybind11_builtins.pybind11_object)  
---  
`    `|   |

Method resolution order:

    [Parameters](KratosMultiphysics.Parameters)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AddEmptyArray**(...)

    `AddEmptyArray(self: Kratos.Parameters, arg0: str) -> None`

**AddEmptyList**(...)

    `AddEmptyList(self: Kratos.Parameters, arg0: str) -> None`

**AddEmptyValue**(...)

    `AddEmptyValue(self: Kratos.Parameters, arg0: str) -> Kratos.Parameters`

**AddMissingParameters**(...)

    `AddMissingParameters(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**AddValue**(...)

    `AddValue(self: Kratos.Parameters, arg0: str, arg1: Kratos.Parameters) -> None`

**Append**(...)

    `Append(*args, **kwargs)  
Overloaded  function.  
  
1. Append(self: Kratos.Parameters, arg0: int) -> None  
  
2. Append(self: Kratos.Parameters, arg0: bool) -> None  
  
3. Append(self: Kratos.Parameters, arg0: float) -> None  
  
4. Append(self: Kratos.Parameters, arg0: Kratos.Vector) -> None  
  
5. Append(self: Kratos.Parameters, arg0: Kratos.Matrix) -> None  
  
6. Append(self: Kratos.Parameters, arg0: str) -> None  
  
7. Append(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**Clone**(...)

    `Clone(self: Kratos.Parameters) -> Kratos.Parameters`

**GetBool**(...)

    `GetBool(self: Kratos.Parameters) -> bool`

**GetDouble**(...)

    `GetDouble(self: Kratos.Parameters) -> float`

**GetInt**(...)

    `GetInt(self: Kratos.Parameters) -> int`

**GetMatrix**(...)

    `GetMatrix(self: Kratos.Parameters) -> Kratos.Matrix`

**GetString**(...)

    `GetString(self: Kratos.Parameters) -> str`

**GetStringArray**(...)

    `GetStringArray(self: Kratos.Parameters) -> List[str]`

**GetVector**(...)

    `GetVector(self: Kratos.Parameters) -> Kratos.Vector`

**Has**(...)

    `Has(self: Kratos.Parameters, arg0: str) -> bool`

**HasSameKeysAndTypeOfValuesAs**(...)

    `HasSameKeysAndTypeOfValuesAs(self: Kratos.Parameters, arg0: Kratos.Parameters) -> bool`

**IsArray**(...)

    `IsArray(self: Kratos.Parameters) -> bool`

**IsBool**(...)

    `IsBool(self: Kratos.Parameters) -> bool`

**IsDouble**(...)

    `IsDouble(self: Kratos.Parameters) -> bool`

**IsEquivalentTo**(...)

    `IsEquivalentTo(self: Kratos.Parameters, arg0: Kratos.Parameters) -> bool`

**IsInt**(...)

    `IsInt(self: Kratos.Parameters) -> bool`

**IsMatrix**(...)

    `IsMatrix(self: Kratos.Parameters) -> bool`

**IsNull**(...)

    `IsNull(self: Kratos.Parameters) -> bool`

**IsNumber**(...)

    `IsNumber(self: Kratos.Parameters) -> bool`

**IsString**(...)

    `IsString(self: Kratos.Parameters) -> bool`

**IsSubParameter**(...)

    `IsSubParameter(self: Kratos.Parameters) -> bool`

**IsVector**(...)

    `IsVector(self: Kratos.Parameters) -> bool`

**PrettyPrintJsonString**(...)

    `PrettyPrintJsonString(self: Kratos.Parameters) -> str`

**RecursivelyAddMissingParameters**(...)

    `RecursivelyAddMissingParameters(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**RecursivelyValidateAndAssignDefaults**(...)

    `RecursivelyValidateAndAssignDefaults(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**RecursivelyValidateDefaults**(...)

    `RecursivelyValidateDefaults(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**RemoveValue**(...)

    `RemoveValue(self: Kratos.Parameters, arg0: str) -> bool`

**SetBool**(...)

    `SetBool(self: Kratos.Parameters, arg0: bool) -> None`

**SetDouble**(...)

    `SetDouble(self: Kratos.Parameters, arg0: float) -> None`

**SetInt**(...)

    `SetInt(self: Kratos.Parameters, arg0: int) -> None`

**SetMatrix**(...)

    `SetMatrix(self: Kratos.Parameters, arg0: Kratos.Matrix) -> None`

**SetString**(...)

    `SetString(self: Kratos.Parameters, arg0: str) -> None`

**SetVector**(...)

    `SetVector(self: Kratos.Parameters, arg0: Kratos.Vector) -> None`

**ValidateAndAssignDefaults**(...)

    `ValidateAndAssignDefaults(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**ValidateDefaults**(...)

    `ValidateDefaults(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**WriteJsonString**(...)

    `WriteJsonString(self: Kratos.Parameters) -> str`

**__getitem__**(...)

    `__getitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __getitem__(self: Kratos.Parameters, arg0: str) -> Kratos.Parameters  
  
2. __getitem__(self: Kratos.Parameters, arg0: int) -> Kratos.Parameters`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.Parameters) -> None  
  
2. __init__(self: Kratos.Parameters, arg0: str) -> None  
  
3. __init__(self: Kratos.Parameters, arg0: Kratos.Parameters) -> None`

**__iter__**(...)

    `__iter__(self: Kratos.Parameters) -> iterator`

**__setitem__**(...)

    `__setitem__(*args, **kwargs)  
Overloaded  function.  
  
1. __setitem__(self: Kratos.Parameters, arg0: str, arg1: Kratos.Parameters) -> None  
  
2. __setitem__(self: Kratos.Parameters, arg0: int, arg1: Kratos.Parameters) -> None`

**__str__**(...)

    `__str__(self: Kratos.Parameters) -> str`

**items**(...)

    `items(self: Kratos.Parameters) -> list`

**keys**(...)

    `keys(self: Kratos.Parameters) -> list`

**size**(...)

    `size(self: Kratos.Parameters) -> int`

**values**(...)

    `values(self: Kratos.Parameters) -> list`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

