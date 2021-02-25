  
**KratosMultiphysics.ConstitutiveLaw** = class
ConstitutiveLaw([Flags](KratosMultiphysics.Flags))  
---  
`    `|   |

Method resolution order:

    [ConstitutiveLaw](KratosMultiphysics.ConstitutiveLaw)
    [Flags](KratosMultiphysics.Flags)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**CalculateMaterialResponse**(...)

    `CalculateMaterialResponse(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.StressMeasure) -> None`

**CalculateMaterialResponseCauchy**(...)

    `CalculateMaterialResponseCauchy(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**CalculateMaterialResponseKirchhoff**(...)

    `CalculateMaterialResponseKirchhoff(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**CalculateMaterialResponsePK1**(...)

    `CalculateMaterialResponsePK1(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**CalculateMaterialResponsePK2**(...)

    `CalculateMaterialResponsePK2(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**CalculateValue**(...)

    `CalculateValue(*args, **kwargs)  
Overloaded  function.  
  
1. CalculateValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.BoolVariable, arg2: bool) -> bool  
  
2. CalculateValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.IntegerVariable, arg2: int) -> int  
  
3. CalculateValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.DoubleVariable, arg2: float) -> float  
  
4. CalculateValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.Array1DVariable3, arg2: Kratos.Array3) -> Kratos.Array3  
  
5. CalculateValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.VectorVariable, arg2: Kratos.Vector) -> Kratos.Vector  
  
6. CalculateValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.MatrixVariable, arg2: Kratos.Matrix) -> Kratos.Matrix`

**Check**(...)

    `Check(self: Kratos.ConstitutiveLaw, arg0: Kratos.Properties, arg1: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >, arg2: Kratos.ProcessInfo) -> int`

**Clone**(...)

    `Clone(self: Kratos.ConstitutiveLaw) -> Kratos.ConstitutiveLaw`

**Create**(...)

    `Create(self: Kratos.ConstitutiveLaw, arg0: Kratos::Parameters) -> Kratos.ConstitutiveLaw`

**FinalizeMaterialResponse**(...)

    `FinalizeMaterialResponse(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.StressMeasure) -> None`

**FinalizeMaterialResponseCauchy**(...)

    `FinalizeMaterialResponseCauchy(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**FinalizeMaterialResponseKirchhoff**(...)

    `FinalizeMaterialResponseKirchhoff(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**FinalizeMaterialResponsePK1**(...)

    `FinalizeMaterialResponsePK1(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**FinalizeMaterialResponsePK2**(...)

    `FinalizeMaterialResponsePK2(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**FinalizeSolutionStep**(...)

    `FinalizeSolutionStep(self: Kratos.ConstitutiveLaw, arg0: Kratos.Properties, arg1: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >, arg2: Kratos.Vector, arg3: Kratos.ProcessInfo) -> None`

**GetLawFeatures**(...)

    `GetLawFeatures(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawFeatures) -> None`

**GetStrainSize**(...)

    `GetStrainSize(*args, **kwargs)  
Overloaded  function.  
  
1. GetStrainSize(self: Kratos.ConstitutiveLaw) -> int  
  
2. GetStrainSize(self: Kratos.ConstitutiveLaw) -> int`

**GetStressMeasure**(...)

    `GetStressMeasure(self: Kratos.ConstitutiveLaw) -> Kratos.StressMeasure`

**GetValue**(...)

    `GetValue(*args, **kwargs)  
Overloaded  function.  
  
1. GetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.BoolVariable, arg1: bool) -> bool  
  
2. GetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.IntegerVariable, arg1: int) -> int  
  
3. GetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.DoubleVariable, arg1: float) -> float  
  
4. GetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3) -> Kratos.Array3  
  
5. GetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.VectorVariable, arg1: Kratos.Vector) -> Kratos.Vector  
  
6. GetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix) -> Kratos.Matrix`

**Has**(...)

    `Has(*args, **kwargs)  
Overloaded  function.  
  
1. Has(self: Kratos.ConstitutiveLaw, arg0: Kratos.BoolVariable) -> bool  
  
2. Has(self: Kratos.ConstitutiveLaw, arg0: Kratos.IntegerVariable) -> bool  
  
3. Has(self: Kratos.ConstitutiveLaw, arg0: Kratos.DoubleVariable) -> bool  
  
4. Has(self: Kratos.ConstitutiveLaw, arg0: Kratos.Array1DVariable3) -> bool  
  
5. Has(self: Kratos.ConstitutiveLaw, arg0: Kratos.VectorVariable) -> bool  
  
6. Has(self: Kratos.ConstitutiveLaw, arg0: Kratos.MatrixVariable) -> bool`

**InitializeMaterial**(...)

    `InitializeMaterial(self: Kratos.ConstitutiveLaw, arg0: Kratos.Properties, arg1: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >, arg2: Kratos.Vector) -> None`

**InitializeMaterialResponse**(...)

    `InitializeMaterialResponse(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters, arg1: Kratos.StressMeasure) -> None`

**InitializeMaterialResponseCauchy**(...)

    `InitializeMaterialResponseCauchy(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**InitializeMaterialResponseKirchhoff**(...)

    `InitializeMaterialResponseKirchhoff(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**InitializeMaterialResponsePK1**(...)

    `InitializeMaterialResponsePK1(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**InitializeMaterialResponsePK2**(...)

    `InitializeMaterialResponsePK2(self: Kratos.ConstitutiveLaw, arg0: Kratos.ConstitutiveLawParameters) -> None`

**InitializeSolutionStep**(...)

    `InitializeSolutionStep(self: Kratos.ConstitutiveLaw, arg0: Kratos.Properties, arg1: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >, arg2: Kratos.Vector, arg3: Kratos.ProcessInfo) -> None`

**IsIncremental**(...)

    `IsIncremental(self: Kratos.ConstitutiveLaw) -> bool`

**PullBackConstitutiveMatrix**(...)

    `PullBackConstitutiveMatrix(self: Kratos.ConstitutiveLaw, arg0: Kratos.Matrix, arg1: Kratos.Matrix) -> None`

**PushForwardConstitutiveMatrix**(...)

    `PushForwardConstitutiveMatrix(self: Kratos.ConstitutiveLaw, arg0: Kratos.Matrix, arg1: Kratos.Matrix) -> None`

**ResetMaterial**(...)

    `ResetMaterial(self: Kratos.ConstitutiveLaw, arg0: Kratos.Properties, arg1: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >, arg2: Kratos.Vector) -> None`

**SetValue**(...)

    `SetValue(*args, **kwargs)  
Overloaded  function.  
  
1. SetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.IntegerVariable, arg1: int, arg2: Kratos.ProcessInfo) -> None  
  
2. SetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.DoubleVariable, arg1: float, arg2: Kratos.ProcessInfo) -> None  
  
3. SetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.Array1DVariable3, arg1: Kratos.Array3, arg2: Kratos.ProcessInfo) -> None  
  
4. SetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.VectorVariable, arg1: Kratos.Vector, arg2: Kratos.ProcessInfo) -> None  
  
5. SetValue(self: Kratos.ConstitutiveLaw, arg0: Kratos.MatrixVariable, arg1: Kratos.Matrix, arg2: Kratos.ProcessInfo) -> None`

**TransformCauchyStresses**(...)

    `TransformCauchyStresses(self: Kratos.ConstitutiveLaw, arg0: Kratos.Vector, arg1: Kratos.Matrix, arg2: float, arg3: Kratos.StressMeasure) -> Kratos.Vector`

**TransformKirchhoffStresses**(...)

    `TransformKirchhoffStresses(self: Kratos.ConstitutiveLaw, arg0: Kratos.Vector, arg1: Kratos.Matrix, arg2: float, arg3: Kratos.StressMeasure) -> Kratos.Vector`

**TransformPK1Stresses**(...)

    `TransformPK1Stresses(self: Kratos.ConstitutiveLaw, arg0: Kratos.Vector, arg1: Kratos.Matrix, arg2: float, arg3: Kratos.StressMeasure) -> Kratos.Vector`

**TransformPK2Stresses**(...)

    `TransformPK2Stresses(self: Kratos.ConstitutiveLaw, arg0: Kratos.Vector, arg1: Kratos.Matrix, arg2: float, arg3: Kratos.StressMeasure) -> Kratos.Vector`

**TransformStrains**(...)

    `TransformStrains(self: Kratos.ConstitutiveLaw, arg0: Kratos.Vector, arg1: Kratos.Matrix, arg2: Kratos.StrainMeasure, arg3: Kratos.StrainMeasure) -> Kratos.Vector`

**WorkingSpaceDimension**(...)

    `WorkingSpaceDimension(*args, **kwargs)  
Overloaded  function.  
  
1. WorkingSpaceDimension(self: Kratos.ConstitutiveLaw) -> int  
  
2. WorkingSpaceDimension(self: Kratos.ConstitutiveLaw) -> int`

**__init__**(...)

    `__init__(self: Kratos.ConstitutiveLaw) -> None`

* * *

Data descriptors defined here:  

**ANISOTROPIC**

**AXISYMMETRIC_LAW**

**COMPUTE_CONSTITUTIVE_TENSOR**

**COMPUTE_STRAIN_ENERGY**

**COMPUTE_STRESS**

**FINALIZE_MATERIAL_RESPONSE**

**FINITE_STRAINS**

**INCREMENTAL_STRAIN_MEASURE**

**INFINITESIMAL_STRAINS**

**INITIALIZE_MATERIAL_RESPONSE**

**ISOCHORIC_TENSOR_ONLY**

**ISOTROPIC**

**MECHANICAL_RESPONSE_ONLY**

**PLANE_STRAIN_LAW**

**PLANE_STRESS_LAW**

**THERMAL_RESPONSE_ONLY**

**THREE_DIMENSIONAL_LAW**

**USE_ELEMENT_PROVIDED_STRAIN**

**U_P_LAW**

**VOLUMETRIC_TENSOR_ONLY**

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

**__str__**(...)

    `__str__(self: Kratos.Flags) -> str`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

