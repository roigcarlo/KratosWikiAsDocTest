  
**KratosMultiphysics.Communicator** = class
Communicator(pybind11_builtins.pybind11_object)  
---  
`    `|   |

Method resolution order:

    [Communicator](KratosMultiphysics.Communicator)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AssembleCurrentData**(...)

    `AssembleCurrentData(*args, **kwargs)  
Overloaded  function.  
  
1. AssembleCurrentData(self: Kratos.Communicator, arg0: Kratos.IntegerVariable) -> bool  
  
2. AssembleCurrentData(self: Kratos.Communicator, arg0: Kratos.DoubleVariable) -> bool  
  
3. AssembleCurrentData(self: Kratos.Communicator, arg0: Kratos.Array1DVariable3) -> bool  
  
4. AssembleCurrentData(self: Kratos.Communicator, arg0: Kratos.VectorVariable) -> bool  
  
5. AssembleCurrentData(self: Kratos.Communicator, arg0: Kratos.MatrixVariable) -> bool`

**AssembleNonHistoricalData**(...)

    `AssembleNonHistoricalData(*args, **kwargs)  
Overloaded  function.  
  
1. AssembleNonHistoricalData(self: Kratos.Communicator, arg0: Kratos.IntegerVariable) -> bool  
  
2. AssembleNonHistoricalData(self: Kratos.Communicator, arg0: Kratos.DoubleVariable) -> bool  
  
3. AssembleNonHistoricalData(self: Kratos.Communicator, arg0: Kratos.Array1DVariable3) -> bool  
  
4. AssembleNonHistoricalData(self: Kratos.Communicator, arg0: Kratos.VectorVariable) -> bool  
  
5. AssembleNonHistoricalData(self: Kratos.Communicator, arg0: Kratos.MatrixVariable) -> bool`

**Barrier**(...)

    `Barrier(self: Kratos.Communicator) -> None`

**GetDataCommunicator**(...)

    `GetDataCommunicator(self: Kratos.Communicator) -> Kratos::DataCommunicator`

**GetNumberOfColors**(...)

    `GetNumberOfColors(self: Kratos.Communicator) -> int`

**GhostMesh**(...)

    `GhostMesh(*args, **kwargs)  
Overloaded  function.  
  
1. GhostMesh(self: Kratos.Communicator) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>  
  
2. GhostMesh(self: Kratos.Communicator, arg0: int) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>`

**InterfaceMesh**(...)

    `InterfaceMesh(*args, **kwargs)  
Overloaded  function.  
  
1. InterfaceMesh(self: Kratos.Communicator) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>  
  
2. InterfaceMesh(self: Kratos.Communicator, arg0: int) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>`

**LocalMesh**(...)

    `LocalMesh(*args, **kwargs)  
Overloaded  function.  
  
1. LocalMesh(self: Kratos.Communicator) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>  
  
2. LocalMesh(self: Kratos.Communicator, arg0: int) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>`

**MaxAll**(...)

    `MaxAll(*args, **kwargs)  
Overloaded  function.  
  
1. MaxAll(self: Kratos.Communicator, arg0: int) -> int  
  
2. MaxAll(self: Kratos.Communicator, arg0: float) -> float`

**MinAll**(...)

    `MinAll(*args, **kwargs)  
Overloaded  function.  
  
1. MinAll(self: Kratos.Communicator, arg0: int) -> int  
  
2. MinAll(self: Kratos.Communicator, arg0: float) -> float`

**MyPID**(...)

    `MyPID(self: Kratos.Communicator) -> int`

**NeighbourIndices**(...)

    `NeighbourIndices(self: Kratos.Communicator) -> Kratos.DenseVectorInt`

**ScanSum**(...)

    `ScanSum(*args, **kwargs)  
Overloaded  function.  
  
1. ScanSum(self: Kratos.Communicator, arg0: int, arg1: int) -> int  
  
2. ScanSum(self: Kratos.Communicator, arg0: float, arg1: float) -> float`

**SumAll**(...)

    `SumAll(*args, **kwargs)  
Overloaded  function.  
  
1. SumAll(self: Kratos.Communicator, arg0: int) -> int  
  
2. SumAll(self: Kratos.Communicator, arg0: float) -> float  
  
3. SumAll(self: Kratos.Communicator, arg0: Kratos.Array3) -> Kratos.Array3`

**SynchronizeDofs**(...)

    `SynchronizeDofs(self: Kratos.Communicator) -> bool`

**SynchronizeNodalSolutionStepsData**(...)

    `SynchronizeNodalSolutionStepsData(self: Kratos.Communicator) -> bool`

**SynchronizeNonHistoricalVariable**(...)

    `SynchronizeNonHistoricalVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SynchronizeNonHistoricalVariable(self: Kratos.Communicator, arg0: Kratos.IntegerVariable) -> bool  
  
2. SynchronizeNonHistoricalVariable(self: Kratos.Communicator, arg0: Kratos.DoubleVariable) -> bool  
  
3. SynchronizeNonHistoricalVariable(self: Kratos.Communicator, arg0: Kratos.Array1DVariable3) -> bool  
  
4. SynchronizeNonHistoricalVariable(self: Kratos.Communicator, arg0: Kratos.VectorVariable) -> bool  
  
5. SynchronizeNonHistoricalVariable(self: Kratos.Communicator, arg0: Kratos.MatrixVariable) -> bool`

**SynchronizeVariable**(...)

    `SynchronizeVariable(*args, **kwargs)  
Overloaded  function.  
  
1. SynchronizeVariable(self: Kratos.Communicator, arg0: Kratos.IntegerVariable) -> bool  
  
2. SynchronizeVariable(self: Kratos.Communicator, arg0: Kratos.DoubleVariable) -> bool  
  
3. SynchronizeVariable(self: Kratos.Communicator, arg0: Kratos.Array1DVariable3) -> bool  
  
4. SynchronizeVariable(self: Kratos.Communicator, arg0: Kratos.VectorVariable) -> bool  
  
5. SynchronizeVariable(self: Kratos.Communicator, arg0: Kratos.MatrixVariable) -> bool`

**TotalProcesses**(...)

    `TotalProcesses(self: Kratos.Communicator) -> int`

**__init__**(...)

    `__init__(self: Kratos.Communicator) -> None`

**__str__**(...)

    `__str__(self: Kratos.Communicator) -> str`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

