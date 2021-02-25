  
**KratosMultiphysics.IO** = class IO(pybind11_builtins.pybind11_object)  
---  
`    `|   |

Method resolution order:

    [IO](KratosMultiphysics.IO)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**ReadConditions**(...)

    `ReadConditions(self: Kratos.IO, arg0: Kratos.NodesArray, arg1: Kratos.PropertiesArray, arg2: Kratos.ConditionsArray) -> None`

**ReadElements**(...)

    `ReadElements(self: Kratos.IO, arg0: Kratos.NodesArray, arg1: Kratos.PropertiesArray, arg2: Kratos.ElementsArray) -> None`

**ReadInitialValues**(...)

    `ReadInitialValues(*args, **kwargs)  
Overloaded  function.  
  
1. ReadInitialValues(self: Kratos.IO, arg0: Kratos.NodesArray, arg1: Kratos.ElementsArray, arg2: Kratos.ConditionsArray) -> None  
  
2. ReadInitialValues(self: Kratos.IO, arg0: Kratos.ModelPart) -> None`

**ReadMesh**(...)

    `ReadMesh(self: Kratos.IO, arg0: Kratos.Mesh) -> None`

**ReadModelPart**(...)

    `ReadModelPart(self: Kratos.IO, arg0: Kratos.ModelPart) -> None`

**ReadNode**(...)

    `ReadNode(self: Kratos.IO, arg0: Kratos.Node) -> bool`

**ReadNodes**(...)

    `ReadNodes(self: Kratos.IO, arg0: Kratos.NodesArray) -> bool`

**ReadProperties**(...)

    `ReadProperties(*args, **kwargs)  
Overloaded  function.  
  
1. ReadProperties(self: Kratos.IO, arg0: Kratos.Properties) -> None  
  
2. ReadProperties(self: Kratos.IO, arg0: Kratos.PropertiesArray) -> None`

**WriteConditions**(...)

    `WriteConditions(self: Kratos.IO, arg0: Kratos.ConditionsArray) -> None`

**WriteElements**(...)

    `WriteElements(self: Kratos.IO, arg0: Kratos.ElementsArray) -> None`

**WriteModelPart**(...)

    `WriteModelPart(self: Kratos.IO, arg0: Kratos.ModelPart) -> None`

**WriteNodes**(...)

    `WriteNodes(self: Kratos.IO, arg0: Kratos.NodesArray) -> None`

**__init__**(self, /, *args, **kwargs)

    ` Initialize self.  See help(type(self)) for accurate signature.`

* * *

Data and other attributes defined here:  

**APPEND** =  <Kratos.Flags object>

**IGNORE_VARIABLES_ERROR** =  <Kratos.Flags object>

**MESH_ONLY** =  <Kratos.Flags object>

**READ** =  <Kratos.Flags object>

**SKIP_TIMER** =  <Kratos.Flags object>

**WRITE** =  <Kratos.Flags object>

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

