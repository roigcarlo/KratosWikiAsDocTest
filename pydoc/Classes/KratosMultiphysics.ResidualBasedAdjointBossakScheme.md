  
**KratosMultiphysics.ResidualBasedAdjointBossakScheme** = class
ResidualBasedAdjointBossakScheme([Scheme](KratosMultiphysics.Scheme))  
---  
`    `|   |

Method resolution order:

    [ResidualBasedAdjointBossakScheme](KratosMultiphysics.ResidualBasedAdjointBossakScheme)
    [Scheme](KratosMultiphysics.Scheme)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**__init__**(...)

    `__init__(self: Kratos.ResidualBasedAdjointBossakScheme, arg0: Kratos::Parameters, arg1: Kratos::AdjointResponseFunction) -> None`

* * *

Methods inherited from [Scheme](KratosMultiphysics.Scheme):  

**CalculateOutputData**(...)

    `CalculateOutputData(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos::PointerVectorSet<Kratos::Dof<double>, Kratos::SetIdentityFunction<Kratos::Dof<double> >, std::less<Kratos::Dof<double> >, std::equal_to<Kratos::Dof<double> >, Kratos::Dof<double>*, std::vector<Kratos::Dof<double>*, std::allocator<Kratos::Dof<double>*> > >, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

**Check**(...)

    `Check(self: Kratos.Scheme, arg0: Kratos.ModelPart) -> int`

**Clean**(...)

    `Clean(self: Kratos.Scheme) -> None`

**Clear**(...)

    `Clear(self: Kratos.Scheme) -> None`

**ConditionsAreInitialized**(...)

    `ConditionsAreInitialized(self: Kratos.Scheme) -> bool`

**ElementsAreInitialized**(...)

    `ElementsAreInitialized(self: Kratos.Scheme) -> bool`

**FinalizeNonLinIteration**(...)

    `FinalizeNonLinIteration(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector) -> None`

**FinalizeSolutionStep**(...)

    `FinalizeSolutionStep(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector) -> None`

**Initialize**(...)

    `Initialize(self: Kratos.Scheme, arg0: Kratos.ModelPart) -> None`

**InitializeConditions**(...)

    `InitializeConditions(self: Kratos.Scheme, arg0: Kratos.ModelPart) -> None`

**InitializeElements**(...)

    `InitializeElements(self: Kratos.Scheme, arg0: Kratos.ModelPart) -> None`

**InitializeNonLinIteration**(...)

    `InitializeNonLinIteration(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector) -> None`

**InitializeSolutionStep**(...)

    `InitializeSolutionStep(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos.CompressedMatrix, arg2: Kratos.Vector, arg3: Kratos.Vector) -> None`

**MoveMesh**(...)

    `MoveMesh(self: Kratos.Scheme, arg0: Kratos.NodesArray) -> None`

**Predict**(...)

    `Predict(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos::PointerVectorSet<Kratos::Dof<double>, Kratos::SetIdentityFunction<Kratos::Dof<double> >, std::less<Kratos::Dof<double> >, std::equal_to<Kratos::Dof<double> >, Kratos::Dof<double>*, std::vector<Kratos::Dof<double>*, std::allocator<Kratos::Dof<double>*> > >, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

**SchemeIsInitialized**(...)

    `SchemeIsInitialized(self: Kratos.Scheme) -> bool`

**Update**(...)

    `Update(self: Kratos.Scheme, arg0: Kratos.ModelPart, arg1: Kratos::PointerVectorSet<Kratos::Dof<double>, Kratos::SetIdentityFunction<Kratos::Dof<double> >, std::less<Kratos::Dof<double> >, std::equal_to<Kratos::Dof<double> >, Kratos::Dof<double>*, std::vector<Kratos::Dof<double>*, std::allocator<Kratos::Dof<double>*> > >, arg2: Kratos.CompressedMatrix, arg3: Kratos.Vector, arg4: Kratos.Vector) -> None`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

