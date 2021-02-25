  
**KratosMultiphysics.ModelPart** = class
ModelPart([DataValueContainer](KratosMultiphysics.DataValueContainer),
[Flags](KratosMultiphysics.Flags))  
---  
`    `|   |

Method resolution order:

    [ModelPart](KratosMultiphysics.ModelPart)
    [DataValueContainer](KratosMultiphysics.DataValueContainer)
    [Flags](KratosMultiphysics.Flags)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**AddCondition**(...)

    `AddCondition(*args, **kwargs)  
Overloaded  function.  
  
1. AddCondition(self: Kratos.ModelPart, arg0: Kratos::Condition) -> None  
  
2. AddCondition(self: Kratos.ModelPart, arg0: Kratos::Condition, arg1: int) -> None  
  
3. AddCondition(self: Kratos.ModelPart, arg0: Kratos::Condition, arg1: int) -> None`

**AddConditions**(...)

    `AddConditions(self: Kratos.ModelPart, arg0: List[int]) -> None`

**AddElement**(...)

    `AddElement(self: Kratos.ModelPart, arg0: Kratos::Element, arg1: int) -> None`

**AddElements**(...)

    `AddElements(self: Kratos.ModelPart, arg0: List[int]) -> None`

**AddMasterSlaveConstraint**(...)

    `AddMasterSlaveConstraint(self: Kratos.ModelPart, arg0: Kratos::MasterSlaveConstraint) -> None`

**AddMasterSlaveConstraints**(...)

    `AddMasterSlaveConstraints(self: Kratos.ModelPart, arg0: List[int]) -> None`

**AddNodalSolutionStepVariable**(...)

    `AddNodalSolutionStepVariable(*args, **kwargs)  
Overloaded  function.  
  
1. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.BoolVariable) -> None  
  
2. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.IntegerVariable) -> None  
  
3. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.DoubleVariable) -> None  
  
4. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.Array1DVariable3) -> None  
  
5. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.VectorVariable) -> None  
  
6. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.MatrixVariable) -> None  
  
7. AddNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.DoubleQuaternionVariable) -> None`

**AddNode**(...)

    `AddNode(self: Kratos.ModelPart, arg0: Kratos::Node<3ul, Kratos::Dof<double> >, arg1: int) -> None`

**AddNodes**(...)

    `AddNodes(self: Kratos.ModelPart, arg0: List[int]) -> None`

**AddProperties**(...)

    `AddProperties(*args, **kwargs)  
Overloaded  function.  
  
1. AddProperties(self: Kratos.ModelPart, arg0: Kratos::Properties) -> None  
  
2. AddProperties(self: Kratos.ModelPart, arg0: Kratos::Properties, arg1: int) -> None`

**AddTable**(...)

    `AddTable(self: Kratos.ModelPart, arg0: int, arg1: Kratos::Table<double, double, 1ul>) -> None`

**Check**(...)

    `Check(self: Kratos.ModelPart, arg0: Kratos::ProcessInfo) -> int`

**CloneSolutionStep**(...)

    `CloneSolutionStep(self: Kratos.ModelPart) -> int`

**CloneTimeStep**(...)

    `CloneTimeStep(*args, **kwargs)  
Overloaded  function.  
  
1. CloneTimeStep(self: Kratos.ModelPart) -> int  
  
2. CloneTimeStep(self: Kratos.ModelPart, arg0: float) -> int`

**ConditionsArray**(...)

    `ConditionsArray(self: Kratos.ModelPart, arg0: int) -> List[Kratos::Condition]`

**CreateNewCondition**(...)

    `CreateNewCondition(self: Kratos.ModelPart, arg0: str, arg1: int, arg2: List[int], arg3: Kratos::Properties) -> Kratos::Condition`

**CreateNewElement**(...)

    `CreateNewElement(self: Kratos.ModelPart, arg0: str, arg1: int, arg2: List[int], arg3: Kratos::Properties) -> Kratos::Element`

**CreateNewMasterSlaveConstraint**(...)

    `CreateNewMasterSlaveConstraint(*args, **kwargs)  
Overloaded  function.  
  
1. CreateNewMasterSlaveConstraint(self: Kratos.ModelPart, arg0: str, arg1: int, arg2: List[Kratos::Dof<double>], arg3: List[Kratos::Dof<double>], arg4: Kratos.Matrix, arg5: Kratos.Vector) -> Kratos::MasterSlaveConstraint  
  
2. CreateNewMasterSlaveConstraint(self: Kratos.ModelPart, arg0: str, arg1: int, arg2: Kratos::Node<3ul, Kratos::Dof<double> >, arg3: Kratos.DoubleVariable, arg4: Kratos::Node<3ul, Kratos::Dof<double> >, arg5: Kratos.DoubleVariable, arg6: float, arg7: float) -> Kratos::MasterSlaveConstraint  
  
3. CreateNewMasterSlaveConstraint(self: Kratos.ModelPart, arg0: str, arg1: int, arg2: Kratos::Node<3ul, Kratos::Dof<double> >, arg3: Kratos.Array1DComponentVariable, arg4: Kratos::Node<3ul, Kratos::Dof<double> >, arg5: Kratos.Array1DComponentVariable, arg6: float, arg7: float) -> Kratos::MasterSlaveConstraint`

**CreateNewNode**(...)

    `CreateNewNode(self: Kratos.ModelPart, arg0: int, arg1: float, arg2: float, arg3: float) -> Kratos::Node<3ul, Kratos::Dof<double> >`

**CreateNewProperties**(...)

    `CreateNewProperties(*args, **kwargs)  
Overloaded  function.  
  
1. CreateNewProperties(self: Kratos.ModelPart, arg0: int, arg1: int) -> Kratos::Properties  
  
2. CreateNewProperties(self: Kratos.ModelPart, arg0: int) -> Kratos::Properties`

**CreateSolutionStep**(...)

    `CreateSolutionStep(self: Kratos.ModelPart) -> int`

**CreateSubModelPart**(...)

    `CreateSubModelPart(self: Kratos.ModelPart, arg0: str) -> Kratos.ModelPart`

**CreateTimeStep**(...)

    `CreateTimeStep(self: Kratos.ModelPart, arg0: float) -> int`

**ElementsArray**(...)

    `ElementsArray(self: Kratos.ModelPart, arg0: int) -> List[Kratos::Element]`

**FullName**(...)

    `FullName(self: Kratos.ModelPart) -> str`

**GetBufferSize**(...)

    `GetBufferSize(self: Kratos.ModelPart) -> int`

**GetCommunicator**(...)

    `GetCommunicator(self: Kratos.ModelPart) -> Kratos.Communicator`

**GetCondition**(...)

    `GetCondition(*args, **kwargs)  
Overloaded  function.  
  
1. GetCondition(self: Kratos.ModelPart, arg0: int) -> Kratos::Condition  
  
2. GetCondition(self: Kratos.ModelPart, arg0: int, arg1: int) -> Kratos::Condition`

**GetConditions**(...)

    `GetConditions(*args, **kwargs)  
Overloaded  function.  
  
1. GetConditions(self: Kratos.ModelPart) -> Kratos::PointerVectorSet<Kratos::Condition, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Condition>, std::vector<Kratos::intrusive_ptr<Kratos::Condition>, std::allocator<Kratos::intrusive_ptr<Kratos::Condition> > > >  
  
2. GetConditions(self: Kratos.ModelPart, arg0: int) -> Kratos::PointerVectorSet<Kratos::Condition, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Condition>, std::vector<Kratos::intrusive_ptr<Kratos::Condition>, std::allocator<Kratos::intrusive_ptr<Kratos::Condition> > > >`

**GetElement**(...)

    `GetElement(*args, **kwargs)  
Overloaded  function.  
  
1. GetElement(self: Kratos.ModelPart, arg0: int) -> Kratos::Element  
  
2. GetElement(self: Kratos.ModelPart, arg0: int, arg1: int) -> Kratos::Element`

**GetElements**(...)

    `GetElements(*args, **kwargs)  
Overloaded  function.  
  
1. GetElements(self: Kratos.ModelPart) -> Kratos::PointerVectorSet<Kratos::Element, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Element>, std::vector<Kratos::intrusive_ptr<Kratos::Element>, std::allocator<Kratos::intrusive_ptr<Kratos::Element> > > >  
  
2. GetElements(self: Kratos.ModelPart, arg0: int) -> Kratos::PointerVectorSet<Kratos::Element, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Element>, std::vector<Kratos::intrusive_ptr<Kratos::Element>, std::allocator<Kratos::intrusive_ptr<Kratos::Element> > > >`

**GetMasterSlaveConstraint**(...)

    `GetMasterSlaveConstraint(self: Kratos.ModelPart, arg0: int) -> Kratos::MasterSlaveConstraint`

**GetMasterSlaveConstraints**(...)

    `GetMasterSlaveConstraints(self: Kratos.ModelPart) -> Kratos.MasterSlaveConstraintsArray`

**GetMesh**(...)

    `GetMesh(*args, **kwargs)  
Overloaded  function.  
  
1. GetMesh(self: Kratos.ModelPart) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>  
  
2. GetMesh(self: Kratos.ModelPart, arg0: int) -> Kratos::Mesh<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::Properties, Kratos::Element, Kratos::Condition>`

**GetModel**(...)

    `GetModel(self: Kratos.ModelPart) -> Kratos::Model`

**GetNodalSolutionStepDataSize**(...)

    `GetNodalSolutionStepDataSize(self: Kratos.ModelPart) -> int`

**GetNodalSolutionStepTotalDataSize**(...)

    `GetNodalSolutionStepTotalDataSize(self: Kratos.ModelPart) -> int`

**GetNode**(...)

    `GetNode(*args, **kwargs)  
Overloaded  function.  
  
1. GetNode(self: Kratos.ModelPart, arg0: int) -> Kratos::Node<3ul, Kratos::Dof<double> >  
  
2. GetNode(self: Kratos.ModelPart, arg0: int, arg1: int) -> Kratos::Node<3ul, Kratos::Dof<double> >`

**GetNodes**(...)

    `GetNodes(*args, **kwargs)  
Overloaded  function.  
  
1. GetNodes(self: Kratos.ModelPart) -> Kratos::PointerVectorSet<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::vector<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::allocator<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > > > > >  
  
2. GetNodes(self: Kratos.ModelPart, arg0: int) -> Kratos::PointerVectorSet<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::vector<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::allocator<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > > > > >`

**GetParentModelPart**(...)

    `GetParentModelPart(self: Kratos.ModelPart) -> Kratos.ModelPart`

**GetProperties**(...)

    `GetProperties(*args, **kwargs)  
Overloaded  function.  
  
1. GetProperties(self: Kratos.ModelPart, arg0: int, arg1: int) -> Kratos::Properties  
  
2. GetProperties(self: Kratos.ModelPart, arg0: str, arg1: int) -> Kratos::Properties  
  
3. GetProperties(self: Kratos.ModelPart) -> Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >  
  
4. GetProperties(self: Kratos.ModelPart, arg0: int) -> Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >`

**GetRootModelPart**(...)

    `GetRootModelPart(self: Kratos.ModelPart) -> Kratos.ModelPart`

**GetSubModelPart**(...)

    `GetSubModelPart(self: Kratos.ModelPart, arg0: str) -> Kratos.ModelPart`

**GetTable**(...)

    `GetTable(self: Kratos.ModelPart, arg0: int) -> Kratos::Table<double, double, 1ul>`

**HasNodalSolutionStepVariable**(...)

    `HasNodalSolutionStepVariable(*args, **kwargs)  
Overloaded  function.  
  
1. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.BoolVariable) -> bool  
  
2. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.IntegerVariable) -> bool  
  
3. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.DoubleVariable) -> bool  
  
4. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.Array1DVariable3) -> bool  
  
5. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.VectorVariable) -> bool  
  
6. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.MatrixVariable) -> bool  
  
7. HasNodalSolutionStepVariable(self: Kratos.ModelPart, arg0: Kratos.DoubleQuaternionVariable) -> bool`

**HasProperties**(...)

    `HasProperties(*args, **kwargs)  
Overloaded  function.  
  
1. HasProperties(self: Kratos.ModelPart, arg0: int, arg1: int) -> bool  
  
2. HasProperties(self: Kratos.ModelPart, arg0: int) -> bool  
  
3. HasProperties(self: Kratos.ModelPart, arg0: str, arg1: int) -> bool  
  
4. HasProperties(self: Kratos.ModelPart, arg0: str) -> bool`

**HasSubModelPart**(...)

    `HasSubModelPart(self: Kratos.ModelPart, arg0: str) -> bool`

**IsDistributed**(...)

    `IsDistributed(self: Kratos.ModelPart) -> bool`

**IsSubModelPart**(...)

    `IsSubModelPart(self: Kratos.ModelPart) -> bool`

**NodesArray**(...)

    `NodesArray(self: Kratos.ModelPart, arg0: int) -> List[Kratos::Node<3ul, Kratos::Dof<double> >]`

**NumberOfConditions**(...)

    `NumberOfConditions(*args, **kwargs)  
Overloaded  function.  
  
1. NumberOfConditions(self: Kratos.ModelPart) -> int  
  
2. NumberOfConditions(self: Kratos.ModelPart, arg0: int) -> int`

**NumberOfElements**(...)

    `NumberOfElements(*args, **kwargs)  
Overloaded  function.  
  
1. NumberOfElements(self: Kratos.ModelPart) -> int  
  
2. NumberOfElements(self: Kratos.ModelPart, arg0: int) -> int`

**NumberOfMasterSlaveConstraints**(...)

    `NumberOfMasterSlaveConstraints(*args, **kwargs)  
Overloaded  function.  
  
1. NumberOfMasterSlaveConstraints(self: Kratos.ModelPart) -> int  
  
2. NumberOfMasterSlaveConstraints(self: Kratos.ModelPart, arg0: int) -> int`

**NumberOfMeshes**(...)

    `NumberOfMeshes(self: Kratos.ModelPart) -> int`

**NumberOfNodes**(...)

    `NumberOfNodes(*args, **kwargs)  
Overloaded  function.  
  
1. NumberOfNodes(self: Kratos.ModelPart, arg0: int) -> int  
  
2. NumberOfNodes(self: Kratos.ModelPart) -> int`

**NumberOfProperties**(...)

    `NumberOfProperties(*args, **kwargs)  
Overloaded  function.  
  
1. NumberOfProperties(self: Kratos.ModelPart, arg0: int) -> int  
  
2. NumberOfProperties(self: Kratos.ModelPart) -> int`

**NumberOfSubModelParts**(...)

    `NumberOfSubModelParts(self: Kratos.ModelPart) -> int`

**NumberOfTables**(...)

    `NumberOfTables(self: Kratos.ModelPart) -> int`

**OverwriteSolutionStepData**(...)

    `OverwriteSolutionStepData(self: Kratos.ModelPart, arg0: int, arg1: int) -> None`

**PropertiesArray**(...)

    `PropertiesArray(self: Kratos.ModelPart, arg0: int) -> List[Kratos::Properties]`

**RecursivelyHasProperties**(...)

    `RecursivelyHasProperties(*args, **kwargs)  
Overloaded  function.  
  
1. RecursivelyHasProperties(self: Kratos.ModelPart, arg0: int, arg1: int) -> bool  
  
2. RecursivelyHasProperties(self: Kratos.ModelPart, arg0: int) -> bool`

**ReduceTimeStep**(...)

    `ReduceTimeStep(self: Kratos.ModelPart, arg0: Kratos.ModelPart, arg1: float) -> None`

**RemoveCondition**(...)

    `RemoveCondition(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveCondition(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveCondition(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveCondition(self: Kratos.ModelPart, arg0: Kratos::Condition) -> None  
  
4. RemoveCondition(self: Kratos.ModelPart, arg0: Kratos::Condition, arg1: int) -> None`

**RemoveConditionFromAllLevels**(...)

    `RemoveConditionFromAllLevels(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveConditionFromAllLevels(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveConditionFromAllLevels(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveConditionFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Condition) -> None  
  
4. RemoveConditionFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Condition, arg1: int) -> None`

**RemoveConditions**(...)

    `RemoveConditions(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveConditionsFromAllLevels**(...)

    `RemoveConditionsFromAllLevels(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveElement**(...)

    `RemoveElement(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveElement(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveElement(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveElement(self: Kratos.ModelPart, arg0: Kratos::Element) -> None  
  
4. RemoveElement(self: Kratos.ModelPart, arg0: Kratos::Element, arg1: int) -> None`

**RemoveElementFromAllLevels**(...)

    `RemoveElementFromAllLevels(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveElementFromAllLevels(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveElementFromAllLevels(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveElementFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Element) -> None  
  
4. RemoveElementFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Element, arg1: int) -> None`

**RemoveElements**(...)

    `RemoveElements(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveElementsFromAllLevels**(...)

    `RemoveElementsFromAllLevels(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveMasterSlaveConstraint**(...)

    `RemoveMasterSlaveConstraint(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveMasterSlaveConstraint(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveMasterSlaveConstraint(self: Kratos.ModelPart, arg0: Kratos::MasterSlaveConstraint) -> None`

**RemoveMasterSlaveConstraintFromAllLevels**(...)

    `RemoveMasterSlaveConstraintFromAllLevels(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveMasterSlaveConstraintFromAllLevels(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveMasterSlaveConstraintFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::MasterSlaveConstraint) -> None`

**RemoveMasterSlaveConstraints**(...)

    `RemoveMasterSlaveConstraints(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveMasterSlaveConstraintsFromAllLevels**(...)

    `RemoveMasterSlaveConstraintsFromAllLevels(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveNode**(...)

    `RemoveNode(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveNode(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveNode(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveNode(self: Kratos.ModelPart, arg0: Kratos::Node<3ul, Kratos::Dof<double> >) -> None  
  
4. RemoveNode(self: Kratos.ModelPart, arg0: Kratos::Node<3ul, Kratos::Dof<double> >, arg1: int) -> None`

**RemoveNodeFromAllLevels**(...)

    `RemoveNodeFromAllLevels(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveNodeFromAllLevels(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveNodeFromAllLevels(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveNodeFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Node<3ul, Kratos::Dof<double> >) -> None  
  
4. RemoveNodeFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Node<3ul, Kratos::Dof<double> >, arg1: int) -> None`

**RemoveNodes**(...)

    `RemoveNodes(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveNodesFromAllLevels**(...)

    `RemoveNodesFromAllLevels(self: Kratos.ModelPart, arg0: Kratos.Flags) -> None`

**RemoveProperties**(...)

    `RemoveProperties(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveProperties(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemoveProperties(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemoveProperties(self: Kratos.ModelPart, arg0: Kratos::Properties) -> None  
  
4. RemoveProperties(self: Kratos.ModelPart, arg0: Kratos::Properties, arg1: int) -> None`

**RemovePropertiesFromAllLevels**(...)

    `RemovePropertiesFromAllLevels(*args, **kwargs)  
Overloaded  function.  
  
1. RemovePropertiesFromAllLevels(self: Kratos.ModelPart, arg0: int) -> None  
  
2. RemovePropertiesFromAllLevels(self: Kratos.ModelPart, arg0: int, arg1: int) -> None  
  
3. RemovePropertiesFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Properties) -> None  
  
4. RemovePropertiesFromAllLevels(self: Kratos.ModelPart, arg0: Kratos::Properties, arg1: int) -> None`

**RemoveSubModelPart**(...)

    `RemoveSubModelPart(*args, **kwargs)  
Overloaded  function.  
  
1. RemoveSubModelPart(self: Kratos.ModelPart, arg0: str) -> None  
  
2. RemoveSubModelPart(self: Kratos.ModelPart, arg0: Kratos.ModelPart) -> None`

**SetBufferSize**(...)

    `SetBufferSize(self: Kratos.ModelPart, arg0: int) -> None`

**SetConditions**(...)

    `SetConditions(*args, **kwargs)  
Overloaded  function.  
  
1. SetConditions(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Condition, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Condition>, std::vector<Kratos::intrusive_ptr<Kratos::Condition>, std::allocator<Kratos::intrusive_ptr<Kratos::Condition> > > >) -> None  
  
2. SetConditions(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Condition, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Condition>, std::vector<Kratos::intrusive_ptr<Kratos::Condition>, std::allocator<Kratos::intrusive_ptr<Kratos::Condition> > > >, arg1: int) -> None`

**SetElements**(...)

    `SetElements(*args, **kwargs)  
Overloaded  function.  
  
1. SetElements(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Element, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Element>, std::vector<Kratos::intrusive_ptr<Kratos::Element>, std::allocator<Kratos::intrusive_ptr<Kratos::Element> > > >) -> None  
  
2. SetElements(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Element, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Element>, std::vector<Kratos::intrusive_ptr<Kratos::Element>, std::allocator<Kratos::intrusive_ptr<Kratos::Element> > > >, arg1: int) -> None`

**SetNodes**(...)

    `SetNodes(*args, **kwargs)  
Overloaded  function.  
  
1. SetNodes(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::vector<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::allocator<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > > > > >) -> None  
  
2. SetNodes(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Node<3ul, Kratos::Dof<double> >, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::vector<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > >, std::allocator<Kratos::intrusive_ptr<Kratos::Node<3ul, Kratos::Dof<double> > > > > >, arg1: int) -> None`

**SetProperties**(...)

    `SetProperties(*args, **kwargs)  
Overloaded  function.  
  
1. SetProperties(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >) -> None  
  
2. SetProperties(self: Kratos.ModelPart, arg0: Kratos::PointerVectorSet<Kratos::Properties, Kratos::IndexedObject, std::less<unsigned long>, std::equal_to<unsigned long>, std::shared_ptr<Kratos::Properties>, std::vector<std::shared_ptr<Kratos::Properties>, std::allocator<std::shared_ptr<Kratos::Properties> > > >, arg1: int) -> None`

**__init__**(self, /, *args, **kwargs)

    ` Initialize self.  See help(type(self)) for accurate signature.`

**__str__**(...)

    `__str__(self: Kratos.ModelPart) -> str`

* * *

Data descriptors defined here:  

**Conditions**

    ``

**Elements**

    ``

**MasterSlaveConstraints**

    ``

**Name**

    ``

**Nodes**

    ``

**ProcessInfo**

    ``

**Properties**

    ``

**SubModelParts**

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

