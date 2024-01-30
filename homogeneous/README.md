# mono-unstable/homogeneous

Online supplementary material for the paper
> S. Bozóki, G. Domokos, D. Papp, K. Regős. The smallest mono-unstable, homogeneous convex polyhedron  has at least 7 vertices. *Submitted*, 2024.

## Overview
The compressed CSV file `cases56.csv.zip` contains the list of cases that need to be examined to prove the the non-existence of mono-unstable, homogeneous, convex polyhedra (in 3 dimensions) with 5 or 6 vertices, as described in the paper above.

The Mathematica notebook `mono-unstable_homogeneous_56.nb` contains scripts to
1. generate the cases (and the CSV file above),
2. read the cases and generate infeasibility certificates using semidefinite programming,
3. rigorously verify the infeasibility certificates in rational arithmetic.

See the detailed comments in the notebook for details.
