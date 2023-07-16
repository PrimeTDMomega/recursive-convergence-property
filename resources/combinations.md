## Calculating the Total Number of Combinations on a 3x3 Rubik's Cube

To determine the total number of combinations on a 3x3 Rubik's cube, we must consider the arrangements of its individual components: edges and corners. Let's break down the process step by step, employing a formal mathematical approach.

### Edges:

The 3x3 cube has 12 edges. When placing the edges, there are 12 spots available for the first edge, 11 for the second, and 10 for the third. Therefore, the total number of edge arrangements is given by 12!.

Each edge can have two orientations (flipped or not flipped). Initially, we might have 2^12 (2 to the power of 12) possible edge orientations. However, not all orientations are achievable since the cube cannot be in a state where only a single edge is flipped (odd number of edges flipped). This constraint reduces the number of edge orientations to 2^11.

### Corners:

The cube contains 8 corners. Similar to the edges, the number of possible corner arrangements is 8!.

Each corner can have three orientations (three ways it can be twisted). We might think there are 3^8 possible corner orientations, but again, this is not entirely accurate. Having only a single twisted corner is not achievable, reducing the corner orientations to 3^7.

### Parity Constraint:

At this stage, we need to consider the parity constraint of the 3x3 Rubik's cube. Due to its even permutation parity, it's impossible to have only two edges swapped in an otherwise solved cube. Thus, we divide the total number of combinations by two to account for this constraint.

### Final Calculation:

The total number of combinations on a 3x3 Rubik's cube is given by:

Total combinations = ![calculaton](https://raw.githubusercontent.com/PrimeTDMomega/repetition-convergence-property/main/resources/imgs/calculation.png)

This remarkable number, approximately 43 quintillion (4.3 x 10^19), illustrates the immense complexity and challenge of solving the Rubik's cube from any scrambled configuration.

I hope this explanation clarifies the process of calculating the total number of combinations on a 3x3 Rubik's cube. Happy cubing!

## Sources

1.  Singmaster, D. (1980). _Notes on Rubik's "Magic Cube"_. Enslow Publishers, Inc.
2.  Joyner, D., & Kreher, D. (2011). _Rubik's Cube and Beyond_. CRC Press.
3.  Korf, R. E. (1997). Finding Optimal Solutions to Rubik's Cube Using Pattern Databases. _Proceedings of the AAAI National Conference on Artificial Intelligence (AAAI-97)_. (for algorithms and computational complexity related to the cube)
