# julia-notes
Notes and Pluto.jl notebooks from documenting different aspects of the Julia language.

## Setup
To adequately, [`Pluto.jl`](https://github.com/fonsp/Pluto.jl) is required. I have packaged all of the dependencies into the `Project.toml`, which can be setup with
```bash
julia> ]
(@v1.5) pkg> activate .
(@v1.5) pkg> instantiate
```
whilst in the root directory.

## Starting Pluto.jl
Pluto may be started from the Julia command line with
```bash
julia> using Pluto; Pluto.run()
```
