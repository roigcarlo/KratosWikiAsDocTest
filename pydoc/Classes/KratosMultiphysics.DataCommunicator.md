  
**KratosMultiphysics.DataCommunicator** = class
DataCommunicator(pybind11_builtins.pybind11_object)  
---  
`    `|   |

Method resolution order:

    [DataCommunicator](KratosMultiphysics.DataCommunicator)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AllGatherDoubles**(...)

    `AllGatherDoubles(self: Kratos.DataCommunicator, arg0: List[float]) -> List[float]`

**AllGatherInts**(...)

    `AllGatherInts(self: Kratos.DataCommunicator, arg0: List[int]) -> List[int]`

**Barrier**(...)

    `Barrier(self: Kratos.DataCommunicator) -> None`

**Broadcast**(...)

    `Broadcast(*args, **kwargs)  
Overloaded  function.  
  
1. Broadcast(self: Kratos.DataCommunicator, arg0: int, arg1: int) -> int  
  
2. Broadcast(self: Kratos.DataCommunicator, arg0: float, arg1: int) -> float`

**BroadcastDoubles**(...)

    `BroadcastDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[float]`

**BroadcastInts**(...)

    `BroadcastInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[int]`

**GatherDoubles**(...)

    `GatherDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[float]`

**GatherInts**(...)

    `GatherInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[int]`

**GathervDoubles**(...)

    `GathervDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[List[float]]`

**GathervInts**(...)

    `GathervInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[List[int]]`

**IsDistributed**(...)

    `IsDistributed(self: Kratos.DataCommunicator) -> bool`

**Max**(...)

    `Max(*args, **kwargs)  
Overloaded  function.  
  
1. Max(self: Kratos.DataCommunicator, arg0: int, arg1: int) -> int  
  
2. Max(self: Kratos.DataCommunicator, arg0: float, arg1: int) -> float  
  
3. Max(self: Kratos.DataCommunicator, arg0: Kratos.Array3, arg1: int) -> Kratos.Array3`

**MaxAll**(...)

    `MaxAll(*args, **kwargs)  
Overloaded  function.  
  
1. MaxAll(self: Kratos.DataCommunicator, arg0: int) -> int  
  
2. MaxAll(self: Kratos.DataCommunicator, arg0: float) -> float  
  
3. MaxAll(self: Kratos.DataCommunicator, arg0: Kratos.Array3) -> Kratos.Array3`

**MaxAllDoubles**(...)

    `MaxAllDoubles(self: Kratos.DataCommunicator, arg0: List[float]) -> List[float]`

**MaxAllInts**(...)

    `MaxAllInts(self: Kratos.DataCommunicator, arg0: List[int]) -> List[int]`

**MaxDoubles**(...)

    `MaxDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[float]`

**MaxInts**(...)

    `MaxInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[int]`

**Min**(...)

    `Min(*args, **kwargs)  
Overloaded  function.  
  
1. Min(self: Kratos.DataCommunicator, arg0: int, arg1: int) -> int  
  
2. Min(self: Kratos.DataCommunicator, arg0: float, arg1: int) -> float  
  
3. Min(self: Kratos.DataCommunicator, arg0: Kratos.Array3, arg1: int) -> Kratos.Array3`

**MinAll**(...)

    `MinAll(*args, **kwargs)  
Overloaded  function.  
  
1. MinAll(self: Kratos.DataCommunicator, arg0: int) -> int  
  
2. MinAll(self: Kratos.DataCommunicator, arg0: float) -> float  
  
3. MinAll(self: Kratos.DataCommunicator, arg0: Kratos.Array3) -> Kratos.Array3`

**MinAllDoubles**(...)

    `MinAllDoubles(self: Kratos.DataCommunicator, arg0: List[float]) -> List[float]`

**MinAllInts**(...)

    `MinAllInts(self: Kratos.DataCommunicator, arg0: List[int]) -> List[int]`

**MinDoubles**(...)

    `MinDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[float]`

**MinInts**(...)

    `MinInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[int]`

**Rank**(...)

    `Rank(self: Kratos.DataCommunicator) -> int`

**ScanSum**(...)

    `ScanSum(*args, **kwargs)  
Overloaded  function.  
  
1. ScanSum(self: Kratos.DataCommunicator, arg0: int) -> int  
  
2. ScanSum(self: Kratos.DataCommunicator, arg0: float) -> float`

**ScanSumDoubles**(...)

    `ScanSumDoubles(self: Kratos.DataCommunicator, arg0: List[float]) -> List[float]`

**ScanSumInts**(...)

    `ScanSumInts(self: Kratos.DataCommunicator, arg0: List[int]) -> List[int]`

**ScatterDoubles**(...)

    `ScatterDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[float]`

**ScatterInts**(...)

    `ScatterInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[int]`

**ScattervDoubles**(...)

    `ScattervDoubles(self: Kratos.DataCommunicator, arg0: List[List[float]], arg1: int) -> List[float]`

**ScattervInts**(...)

    `ScattervInts(self: Kratos.DataCommunicator, arg0: List[List[int]], arg1: int) -> List[int]`

**SendRecvDoubles**(...)

    `SendRecvDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int, arg2: int) -> List[float]`

**SendRecvInts**(...)

    `SendRecvInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int, arg2: int) -> List[int]`

**SendRecvString**(...)

    `SendRecvString(self: Kratos.DataCommunicator, arg0: str, arg1: int, arg2: int) -> str`

**Size**(...)

    `Size(self: Kratos.DataCommunicator) -> int`

**Sum**(...)

    `Sum(*args, **kwargs)  
Overloaded  function.  
  
1. Sum(self: Kratos.DataCommunicator, arg0: int, arg1: int) -> int  
  
2. Sum(self: Kratos.DataCommunicator, arg0: float, arg1: int) -> float  
  
3. Sum(self: Kratos.DataCommunicator, arg0: Kratos.Array3, arg1: int) -> Kratos.Array3`

**SumAll**(...)

    `SumAll(*args, **kwargs)  
Overloaded  function.  
  
1. SumAll(self: Kratos.DataCommunicator, arg0: int) -> int  
  
2. SumAll(self: Kratos.DataCommunicator, arg0: float) -> float  
  
3. SumAll(self: Kratos.DataCommunicator, arg0: Kratos.Array3) -> Kratos.Array3`

**SumAllDoubles**(...)

    `SumAllDoubles(self: Kratos.DataCommunicator, arg0: List[float]) -> List[float]`

**SumAllInts**(...)

    `SumAllInts(self: Kratos.DataCommunicator, arg0: List[int]) -> List[int]`

**SumDoubles**(...)

    `SumDoubles(self: Kratos.DataCommunicator, arg0: List[float], arg1: int) -> List[float]`

**SumInts**(...)

    `SumInts(self: Kratos.DataCommunicator, arg0: List[int], arg1: int) -> List[int]`

**__init__**(self, /, *args, **kwargs)

    ` Initialize self.  See help(type(self)) for accurate signature.`

**__str__**(...)

    `__str__(self: Kratos.DataCommunicator) -> str`

* * *

Static methods defined here:  

**GetDefault**(...) from builtins.PyCapsule

    `GetDefault() -> Kratos.DataCommunicator`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

