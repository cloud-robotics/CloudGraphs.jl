![GitHub Logo](/logo.png)

# CloudGraphs.jl

[![Build Status][build-img]][build-url]
[![CloudGraphs][cg-badge-v0.5]][cg-pkg-v0.5]
[![CloudGraphs][cg-badge-v0.6]][cg-pkg-v0.6]

Repository for the CloudGraphs project, an ongoing project on http://semisortedblog.wordpress.com.

## Installation

This package is written for the [Julia language](http://www.julialang.org) (and [JuliaPro](http://www.juliacomputing.com)), and can be cloned via:

```julia
Pkg.clone("https://github.com/GearsAD/CloudGraphs.jl.git")
```
We are in the process of registering the package for easier install.

Please note that this package requires MongoDB version `3` or higher for local DB usage.

## Users

This package is extensively used by the [Caesar.jl](http://www.github.com/dehann/Caesar.jl) package.

## Contributors

- GearsAD

# References

    [1]  Fourie, D., Claassens, S., Pillai, S., Mata, R., Leonard, J.: "SLAMinDB: Centralized graph
         databases for mobile robotics" IEEE International Conference on Robotics and Automation (ICRA),
         Singapore, 2017.


[cov-img]: https://codecov.io/github/GearsAD/CloudGraphs.jl/coverage.svg?branch=master
[cov-url]: https://codecov.io/github/GearsAD/CloudGraphs.jl?branch=master
[build-img]: https://travis-ci.org/GearsAD/CloudGraphs.jl.svg?branch=master
[build-url]: https://travis-ci.org/GearsAD/CloudGraphs.jl

[cg-badge-v0.5]: http://pkg.julialang.org/badges/CloudGraphs_0.5.svg
[cg-pkg-v0.5]: http://pkg.julialang.org/?pkg=CloudGraphs&ver=0.5
[cg-badge-v0.6]: http://pkg.julialang.org/badges/CloudGraphs_0.6.svg
[cg-pkg-v0.6]: http://pkg.julialang.org/?pkg=CloudGraphs&ver=0.6
