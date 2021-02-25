  
**KratosMultiphysics.GidIO** = class GidIO([IO](KratosMultiphysics.IO))  
---  
`    `|   |

Method resolution order:

    [GidIO](KratosMultiphysics.GidIO)
    [IO](KratosMultiphysics.IO)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**ChangeOutputName**(...)

    `ChangeOutputName(self: Kratos.GidIO, arg0: str) -> None`

**CloseResultFile**(...)

    `CloseResultFile(self: Kratos.GidIO) -> None`

**FinalizeMesh**(...)

    `FinalizeMesh(self: Kratos.GidIO) -> None`

**FinalizeResults**(...)

    `FinalizeResults(self: Kratos.GidIO) -> None`

**Flush**(...)

    `Flush(self: Kratos.GidIO) -> None`

**InitializeMesh**(...)

    `InitializeMesh(self: Kratos.GidIO, arg0: float) -> None`

**InitializeResults**(...)

    `InitializeResults(self: Kratos.GidIO, arg0: float, arg1: Kratos.Mesh) -> None`

**PrintFlagsOnGaussPoints**(...)

    `PrintFlagsOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.Flags, arg1: str, arg2: Kratos.ModelPart, arg3: float) -> None`

**PrintOnGaussPoints**(...)

    `PrintOnGaussPoints(*args, **kwargs)  
Overloaded  function.  
  
1. PrintOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.BoolVariable, arg1: Kratos.ModelPart, arg2: float) -> None  
  
2. PrintOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.IntegerVariable, arg1: Kratos.ModelPart, arg2: float) -> None  
  
3. PrintOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.DoubleVariable, arg1: Kratos.ModelPart, arg2: float) -> None  
  
4. PrintOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.Array1DVariable3, arg1: Kratos.ModelPart, arg2: float) -> None  
  
5. PrintOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.VectorVariable, arg1: Kratos.ModelPart, arg2: float) -> None  
  
6. PrintOnGaussPoints(self: Kratos.GidIO, arg0: Kratos.MatrixVariable, arg1: Kratos.ModelPart, arg2: float) -> None`

**WriteCircleMesh**(...)

    `WriteCircleMesh(self: Kratos.GidIO, arg0: Kratos.Mesh) -> None`

**WriteClusterMesh**(...)

    `WriteClusterMesh(self: Kratos.GidIO, arg0: Kratos.Mesh) -> None`

**WriteLocalAxesOnNodes**(...)

    `WriteLocalAxesOnNodes(self: Kratos.GidIO, arg0: Kratos.Array1DVariable3, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None`

**WriteLocalAxesOnNodesNonHistorical**(...)

    `WriteLocalAxesOnNodesNonHistorical(self: Kratos.GidIO, arg0: Kratos.Array1DVariable3, arg1: Kratos.NodesArray, arg2: float) -> None`

**WriteMesh**(...)

    `WriteMesh(self: Kratos.GidIO, arg0: Kratos.Mesh) -> None`

**WriteNodalFlags**(...)

    `WriteNodalFlags(self: Kratos.GidIO, arg0: Kratos.Flags, arg1: str, arg2: Kratos.NodesArray, arg3: float) -> None`

**WriteNodalResults**(...)

    `WriteNodalResults(*args, **kwargs)  
Overloaded  function.  
  
1. WriteNodalResults(self: Kratos.GidIO, arg0: Kratos.BoolVariable, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None  
  
2. WriteNodalResults(self: Kratos.GidIO, arg0: Kratos.DoubleVariable, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None  
  
3. WriteNodalResults(self: Kratos.GidIO, arg0: Kratos.IntegerVariable, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None  
  
4. WriteNodalResults(self: Kratos.GidIO, arg0: Kratos.Array1DVariable3, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None  
  
5. WriteNodalResults(self: Kratos.GidIO, arg0: Kratos.VectorVariable, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None  
  
6. WriteNodalResults(self: Kratos.GidIO, arg0: Kratos.MatrixVariable, arg1: Kratos.NodesArray, arg2: float, arg3: int) -> None`

**WriteNodalResultsNonHistorical**(...)

    `WriteNodalResultsNonHistorical(*args, **kwargs)  
Overloaded  function.  
  
1. WriteNodalResultsNonHistorical(self: Kratos.GidIO, arg0: Kratos.BoolVariable, arg1: Kratos.NodesArray, arg2: float) -> None  
  
2. WriteNodalResultsNonHistorical(self: Kratos.GidIO, arg0: Kratos.DoubleVariable, arg1: Kratos.NodesArray, arg2: float) -> None  
  
3. WriteNodalResultsNonHistorical(self: Kratos.GidIO, arg0: Kratos.IntegerVariable, arg1: Kratos.NodesArray, arg2: float) -> None  
  
4. WriteNodalResultsNonHistorical(self: Kratos.GidIO, arg0: Kratos.Array1DVariable3, arg1: Kratos.NodesArray, arg2: float) -> None  
  
5. WriteNodalResultsNonHistorical(self: Kratos.GidIO, arg0: Kratos.VectorVariable, arg1: Kratos.NodesArray, arg2: float) -> None  
  
6. WriteNodalResultsNonHistorical(self: Kratos.GidIO, arg0: Kratos.MatrixVariable, arg1: Kratos.NodesArray, arg2: float) -> None`

**WriteNodeMesh**(...)

    `WriteNodeMesh(self: Kratos.GidIO, arg0: Kratos.Mesh) -> None`

**WriteSphereMesh**(...)

    `WriteSphereMesh(self: Kratos.GidIO, arg0: Kratos.Mesh) -> None`

**__init__**(...)

    `__init__(self: Kratos.GidIO, arg0: str, arg1: GiD_PostMode, arg2: Kratos::MultiFileFlag, arg3: Kratos::WriteDeformedMeshFlag, arg4: Kratos::WriteConditionsFlag) -> None`

* * *

Methods inherited from [IO](KratosMultiphysics.IO):  

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

* * *

Data and other attributes inherited from [IO](KratosMultiphysics.IO):  

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

