# DifferentialEquations.jl

[![Join the chat at https://gitter.im/ChrisRackauckas/DifferentialEquations.jl](https://badges.gitter.im/ChrisRackauckas/DifferentialEquations.jl.svg)](https://gitter.im/ChrisRackauckas/DifferentialEquations.jl?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/ChrisRackauckas/DifferentialEquations.jl.svg?branch=master)](https://travis-ci.org/ChrisRackauckas/DifferentialEquations.jl) [![Build status](https://ci.appveyor.com/api/projects/status/032otj4kh462tq2l/branch/master?svg=true)](https://ci.appveyor.com/project/ChrisRackauckas/differentialequations-jl/branch/master) [![Coverage Status](https://coveralls.io/repos/github/ChrisRackauckas/DifferentialEquations.jl/badge.svg?branch=master)](https://coveralls.io/github/ChrisRackauckas/DifferentialEquations.jl?branch=master) [![codecov](https://codecov.io/gh/ChrisRackauckas/DifferentialEquations.jl/coverage.svg?branch=master)](https://codecov.io/gh/ChrisRackauckas/DifferentialEquations.jl)
[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://ChrisRackauckas.github.io/DifferentialEquations.jl/stable)
[![](https://img.shields.io/badge/docs-latest-blue.svg)](https://ChrisRackauckas.github.io/DifferentialEquations.jl/latest)

This is a package for solving numerically solving differential equations in Julia by Chris Rackauckas. The purpose of this package is to supply efficient Julia implementations of solvers for various differential equations. Equations within the realm of this package include ordinary differential equations (ODEs), stochastic ordinary differential equations (SODEs or SDEs), stochastic partial differential equations (SPDEs), partial differential equations (with both finite difference and finite element methods), and differential delay equations. It includes algorithms free very recent research, as well as algorithms optimized for HPC applications. It integrates with the Julia package sphere, for example
using Juno's progress meter, and wraps other differential equation solvers so that many different methods for solving the equations can be accessed by simply switching a keyword arguement.

For information on using the package, see the [documentation](http://chrisrackauckas.github.io/DifferentialEquations.jl/latest/).

If you have any questions, or just want to chat about solvers/using the package, please feel free to message me in the Gitter channel. For bug reports, feature requests, etc., please submit an issue.
