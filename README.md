

# Instructions

* Install [julia](https://julialang.org/downloads/)
* Download and uncompress the [code](https://github.com/Alexander-Barth/Julia-Earth-Observation-Workshop-2024/archive/refs/heads/main.zip) in this repository (or use `git clone https://github.com/gher-uliege/Julia-Earth-Observation-Workshop`)
* Activate and instantiate the environement by running the following Julia commands

 ```julia
using Pkg
Pkg.add("IJulia")
using IJulia
cd("this_directory")
Pkg.activate(".")
Pkg.instantiate() # install all package
```

where `"this_directory"` is the directory containing the ipynb files. Note, in Windows a path `C:\Users\Foo\Bar` should be written as `raw"C:\Users\Foo\Bar"` or `"C:\\Users\\Foo\\Bar"`.
