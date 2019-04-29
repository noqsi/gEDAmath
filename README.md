# gEDAmath
*Mathematica* functions for using the "mathematica" exporter of gEDA and Lepton-EDA

# Usage
You'll need either geda-gaf (see [http://wiki.geda-project.org/geda:gaf]()) or Lepton-EDA (see [https://github.com/lepton-eda/lepton-eda]()).

To make the netlist from the sample schematic, from the command line issue:

**gnetlist -g mathematica Shaper.sch -o Shaper.m** (geda-gaf)

or

**lepton-netlist -g mathematica Shaper.sch -o Shaper.m** (Lepton)

To reduce the circuit equations to a model, see gEDAmath.nb.

This predates *Mathematica* system models, but it can produce a transfer function expression suitable as input to the system modeling machinery.