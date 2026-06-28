# Catalyst-PEtab-Workshop-ECTMB-SMB-2026

This is a workshop on computational tools for mathematical systems biology in the Julia language. It is focused on how to use [Catalyst.jl](https://github.com/SciML/Catalyst.jl) for model creation, simulation, and analysis, and how to use [PEtab.jl](https://github.com/sebapersson/PEtab.jl) for inferring model properties from data. More information of the workshop can be found here: https://ecmtb2026.org/contributions/minisymposia/ms30.

## Preparations and Setup

#### To set up Julia and download required packages (ideally do this before the workshop)

- Generally, VSCode is the recommended IDE for all Julia programming. See how to install it
  and its Julia extension here: https://code.visualstudio.com/docs/languages/julia.
- Download this repository and place somewhere on your computer (or clone using
  `git clone https://github.com/TorkelE/BonnBiomathWorkshop2026.git`).
- Open this repository in VSCode.
- Start a Julia terminal (e.g. through the
  [VSCode Command Palette](https://code.visualstudio.com/api/ux-guidelines/command-palette)
  followed by "Julia: Start REPL").
- Run `]activate .` in your Julia terminal (`]` will open
  [_Pkg mode_](https://docs.julialang.org/en/v1/stdlib/REPL/#Pkg-mode), from where you enter
  "activate .").
- Still in Pkg mode, run `instantiate`. This will download all Julia packages that are used
  in this workshop.

#### To run the workshop

The workshop consists of a set of notebook. To run the workshop, go through each notbook in
order. When starting a notebook for the first time, you have to designate a kernel. Here
select the "Julia release channel kernel".
