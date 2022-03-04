# mono-unstable

Online supplementary material for the paper
> D. Papp, K. Regős, G. Domokos, S. Bozóki. The smallest mono-unstable convex polyhedron with point masses has 8 faces and 11 vertices. (Submitted.)

## Overview
The compressed CSV file `monounstable_3_0_10_certificates.csv.zip` contains the computed certificates of the non-existence of three-dimensional mono-unstable polyhedra (with point masses) with fewer than 11 vertices, as described in Section 2 (Theorem 5 and Lemma 6) of the paper above.

This also proves that the smallest number faces that such a polyhedron can have is at least 8. A mono-unstable convex polyhedron with point masses has 8 faces and 11 vertices is also shown in the paper. (Section 3.)

## Format description
* Each line in the CSV file encodes a certificate of infeasbility of a system of linear inequalities and equations of the form (1a)-(1b) of the paper.
* Each line contains 18 positive integers: the first 9 integers are the subscripts `j1, j2, ..., j9` identifying an instance of the system (1a)-(1b) whose infeasibility is certified. The next 9 integers in the same line are the coefficients `c1, ..., c9` that prove the infeasibility of the system, as explained in Lemma 6.
