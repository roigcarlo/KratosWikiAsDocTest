  
  
 **[KratosMultiphysics](KratosMultiphysics.html).kratos_globals**| [index](.)  
[/home/vicente/src/Kratos/bin/Release/KratosMultiphysics/kratos_globals.py](file:/home/vicente/src/Kratos/bin/Release/KratosMultiphysics/kratos_globals.py)  
---|---  
  
  
**Classes**  
---  
`       `|   |

[builtins.object](builtins.html#object)

    

[KratosGlobalsImpl](KratosMultiphysics.kratos_globals.html#KratosGlobalsImpl)

|  
class **KratosGlobalsImpl**([builtins.object](builtins.html#object))  
---  
`    ` | `KratosGlobalsImpl(ThisKernel, ApplicationsRoot)  
  
  
 `  
  | Methods defined here:  

**GetConstitutiveLaw**(self, ConstitutiveLawName)

    ` This method returns the constitutive law with the given name  
  
Keyword arguments:  
self -- It signifies an instance of a class.  
ConstitutiveLawName -- The name of the constitutive law to return`

**GetFlag**(self, FlagName)

    ` This method returns the flag with the given name  
  
Keyword arguments:  
self -- It signifies an instance of a class.  
FlagName -- The name of the flag to return`

**GetVariable**(self, VarName)

    ` This method returns the variable with the given name  
  
Keyword arguments:  
self -- It signifies an instance of a class.  
VarName -- The name of the variable to return`

**GetVariableType**(self, VarName)

    ` This method checks the type of variable  
  
Keyword arguments:  
self -- It signifies an instance of a class.  
VarName -- The name of the variable to check`

**HasConstitutiveLaw**(self, ConstitutiveLawName)

    ` This method checks if a constitutive law exists  
  
Keyword arguments:  
self -- It signifies an instance of a class.  
ConstitutiveLawName -- The name of the constitutive law to check`

**HasVariable**(self, VarName)

    ` This method checks if a variable exists  
  
Keyword arguments:  
self -- It signifies an instance of a class.  
VarName -- The name of the variable to check`

**__init__**(self, ThisKernel, ApplicationsRoot)

    ` Initialize self.  See help(type(self)) for accurate signature.`

**__setattr__**(self, name, value)

    ` Implement setattr(self, name, value).`

**echo**(self)

* * *

Data descriptors defined here:  

**__dict__**

    ` dictionary for instance variables (if defined)`

**__weakref__**

    ` list of weak references to the object (if defined)`  
  
  
**Data**  
---  
`       `|   | **absolute_import** = _Feature((2, 5, 0, 'alpha', 1), (3, 0, 0,
'alpha', 0), 16384)  
**division** = _Feature((2, 2, 0, 'alpha', 2), (3, 0, 0, 'alpha', 0), 8192)  
**print_function** = _Feature((2, 6, 0, 'alpha', 2), (3, 0, 0, 'alpha', 0),
65536)

