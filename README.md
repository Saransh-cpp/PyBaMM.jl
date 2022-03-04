# PyBaMM.jl

PyBaMM.jl is a common interface binding for the [PyBaMM](pybamm.org) Python battery modeling package. 
It uses the [PyCall.jl](https://github.com/JuliaPy/PyCall.jl) interop in order to retrieve the equations from python in a Julia-readable form.

## Installation

To install PyBaMM.jl, first you need to separately install the pybamm package in a virtual/condaenvironment.
Since the PyBaMM/Julia integration is a WIP, this requires downloading a specific branch from git:
For example, in Linux/Julia do

```bash
pip install git+https://github.com/pybamm-team/pybamm.git@issue-1129-julia
```

use the following:

```julia
Pkg.clone("https://github.com/tinosulzer/PyBaMM.jl")
```

## Using PyBaMM.jl

See examples in docs folder
