  
**KratosMultiphysics.ConstitutiveLawParameters** = class
ConstitutiveLawParameters(pybind11_builtins.pybind11_object)  
---  
`    `|   |

Method resolution order:

    [ConstitutiveLawParameters](KratosMultiphysics.ConstitutiveLawParameters)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**CheckAllParameters**(...)

    `CheckAllParameters(self: Kratos.ConstitutiveLawParameters) -> bool`

**CheckInfoMaterialGeometry**(...)

    `CheckInfoMaterialGeometry(self: Kratos.ConstitutiveLawParameters) -> bool`

**CheckMechanicalVariables**(...)

    `CheckMechanicalVariables(self: Kratos.ConstitutiveLawParameters) -> bool`

**CheckShapeFunctions**(...)

    `CheckShapeFunctions(self: Kratos.ConstitutiveLawParameters) -> bool`

**GetConstitutiveMatrix**(...)

    `GetConstitutiveMatrix(*args, **kwargs)  
Overloaded  function.  
  
1. GetConstitutiveMatrix(self: Kratos.ConstitutiveLawParameters) -> Kratos.Matrix  
  
2. GetConstitutiveMatrix(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Matrix) -> Kratos.Matrix`

**GetDeformationGradientF**(...)

    `GetDeformationGradientF(*args, **kwargs)  
Overloaded  function.  
  
1. GetDeformationGradientF(self: Kratos.ConstitutiveLawParameters) -> Kratos.Matrix  
  
2. GetDeformationGradientF(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Matrix) -> Kratos.Matrix`

**GetDeterminantF**(...)

    `GetDeterminantF(self: Kratos.ConstitutiveLawParameters) -> float`

**GetElementGeometry**(...)

    `GetElementGeometry(self: Kratos.ConstitutiveLawParameters) -> Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >`

**GetMaterialProperties**(...)

    `GetMaterialProperties(self: Kratos.ConstitutiveLawParameters) -> Kratos.Properties`

**GetOptions**(...)

    `GetOptions(self: Kratos.ConstitutiveLawParameters) -> Kratos.Flags`

**GetProcessInfo**(...)

    `GetProcessInfo(self: Kratos.ConstitutiveLawParameters) -> Kratos.ProcessInfo`

**GetShapeFunctionsValues**(...)

    `GetShapeFunctionsValues(self: Kratos.ConstitutiveLawParameters) -> Kratos.Vector`

**GetStrainVector**(...)

    `GetStrainVector(*args, **kwargs)  
Overloaded  function.  
  
1. GetStrainVector(self: Kratos.ConstitutiveLawParameters) -> Kratos.Vector  
  
2. GetStrainVector(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Vector) -> Kratos.Vector`

**GetStressVector**(...)

    `GetStressVector(*args, **kwargs)  
Overloaded  function.  
  
1. GetStressVector(self: Kratos.ConstitutiveLawParameters) -> Kratos.Vector  
  
2. GetStressVector(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Vector) -> Kratos.Vector`

**Reset**(...)

    `Reset(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Flags) -> None`

**Set**(...)

    `Set(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Flags) -> None`

**SetConstitutiveMatrix**(...)

    `SetConstitutiveMatrix(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Matrix) -> None`

**SetDeformationGradientF**(...)

    `SetDeformationGradientF(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Matrix) -> None`

**SetDeterminantF**(...)

    `SetDeterminantF(self: Kratos.ConstitutiveLawParameters, arg0: float) -> None`

**SetElementGeometry**(...)

    `SetElementGeometry(self: Kratos.ConstitutiveLawParameters, arg0: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >) -> None`

**SetMaterialProperties**(...)

    `SetMaterialProperties(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Properties) -> None`

**SetOptions**(...)

    `SetOptions(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Flags) -> None`

**SetProcessInfo**(...)

    `SetProcessInfo(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.ProcessInfo) -> None`

**SetShapeFunctionsDerivatives**(...)

    `SetShapeFunctionsDerivatives(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Matrix) -> None`

**SetShapeFunctionsValues**(...)

    `SetShapeFunctionsValues(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Vector) -> None`

**SetStrainVector**(...)

    `SetStrainVector(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Vector) -> None`

**SetStressVector**(...)

    `SetStressVector(self: Kratos.ConstitutiveLawParameters, arg0: Kratos.Vector) -> None`

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.ConstitutiveLawParameters) -> None  
  
2. __init__(self: Kratos.ConstitutiveLawParameters, arg0: Kratos::Geometry<Kratos::Node<3ul, Kratos::Dof<double> > >, arg1: Kratos.Properties, arg2: Kratos.ProcessInfo) -> None`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

