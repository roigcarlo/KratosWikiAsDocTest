  
**KratosMultiphysics.ComplexSkylineLUSolver** = class
ComplexSkylineLUSolver([ComplexDirectSolver](KratosMultiphysics.ComplexDirectSolver))  
---  
`    `|   |

Method resolution order:

    [ComplexSkylineLUSolver](KratosMultiphysics.ComplexSkylineLUSolver)
    [ComplexDirectSolver](KratosMultiphysics.ComplexDirectSolver)
    [ComplexLinearSolver](KratosMultiphysics.ComplexLinearSolver)
    pybind11_builtins.pybind11_object
    [builtins.object](builtins.html#object)

* * *

Methods defined here:  

**__init__**(...)

    `__init__(*args, **kwargs)  
Overloaded  function.  
  
1. __init__(self: Kratos.ComplexSkylineLUSolver) -> None  
  
2. __init__(self: Kratos.ComplexSkylineLUSolver, arg0: Kratos::Parameters) -> None`

**__str__**(...)

    `__str__(self: Kratos.ComplexSkylineLUSolver) -> str`

* * *

Methods inherited from [ComplexLinearSolver](KratosMultiphysics.ComplexLinearSolver):  

**Clear**(...)

    `Clear(self: Kratos.ComplexLinearSolver) -> None`

**Initialize**(...)

    `Initialize(self: Kratos.ComplexLinearSolver, arg0: boost::numeric::ublas::compressed_matrix<std::complex<double>, boost::numeric::ublas::basic_row_major<unsigned long, long>, 0ul, boost::numeric::ublas::unbounded_array<unsigned long, std::allocator<unsigned long> >, boost::numeric::ublas::unbounded_array<std::complex<double>, std::allocator<std::complex<double> > > >, arg1: boost::numeric::ublas::vector<std::complex<double>, boost::numeric::ublas::unbounded_array<std::complex<double>, std::allocator<std::complex<double> > > >, arg2: boost::numeric::ublas::vector<std::complex<double>, boost::numeric::ublas::unbounded_array<std::complex<double>, std::allocator<std::complex<double> > > >) -> None`

**Solve**(...)

    `Solve(self: Kratos.ComplexLinearSolver, arg0: boost::numeric::ublas::compressed_matrix<std::complex<double>, boost::numeric::ublas::basic_row_major<unsigned long, long>, 0ul, boost::numeric::ublas::unbounded_array<unsigned long, std::allocator<unsigned long> >, boost::numeric::ublas::unbounded_array<std::complex<double>, std::allocator<std::complex<double> > > >, arg1: boost::numeric::ublas::vector<std::complex<double>, boost::numeric::ublas::unbounded_array<std::complex<double>, std::allocator<std::complex<double> > > >, arg2: boost::numeric::ublas::vector<std::complex<double>, boost::numeric::ublas::unbounded_array<std::complex<double>, std::allocator<std::complex<double> > > >) -> bool`

* * *

Static methods inherited from pybind11_builtins.pybind11_object:  

**__new__**(*args, **kwargs) from pybind11_builtins.pybind11_type

    ` Create and return a new object.  See help(type) for accurate signature.`

