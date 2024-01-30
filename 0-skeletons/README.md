# mono-unstable/0-skeletons

Online supplementary material for the paper
> D. Papp, K. Regős, G. Domokos, S. Bozóki. The smallest mono-unstable convex polyhedron with point masses has 8 faces and 11 vertices. (Submitted.)

## Overview
The compressed CSV file `monounstable_3_0_10_certificates.csv.zip` contains the computed certificates of the non-existence of mono-unstable polyhedra with point masses (of any dimension) with fewer than 11 vertices, as described in Section 2 (Theorem 9 and Lemma 10) of the paper above.

This also proves that the smallest number faces that such a polyhedron can have is at least 8. A mono-unstable convex polyhedron with point masses has 8 faces and 11 vertices has already been found.

The Mathematica notebook `mono-unstable_0-skeletons.nb` can be used to generate the certificates.

The Maple notebook `verification-Maple.mw` can be used to independently verify the generated certificates in rational arithmetic.

## Format description
* Each line in the CSV file encodes a certificate of infeasbility of a system of linear inequalities and equations of the form (1a)-(1b) of the paper.
* Each line contains 18 positive integers: the first 9 integers are the subscripts `j2, j3, ..., j10` identifying an instance of the system (1a)-(1b) whose infeasibility is certified. The next 9 integers in the same line are the coefficients `c1, ..., c9` that prove the infeasibility of the system, as explained in Lemma 6.
