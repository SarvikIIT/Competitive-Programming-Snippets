# Competitive Programming Snippets

A comprehensive collection of **391+ code snippets** for competitive programming, covering algorithms and data structures commonly used in programming contests.

## Table of Contents

- [Overview](#overview)
- [Categories](#categories)
  - [Basics](#basics)
  - [Data Structures](#data-structures)
  - [Dynamic Programming Optimizations](#dynamic-programming-optimizations)
  - [Game Theory](#game-theory)
  - [Geometry](#geometry)
  - [Graph Theory](#graph-theory)
  - [Math](#math)
  - [Miscellaneous](#miscellaneous)
  - [Number Theory](#number-theory)
  - [Strings](#strings)
- [Usage](#usage)
- [Contributing](#contributing)

## Overview

This repository contains battle-tested code snippets that I have developed and used throughout my competitive programming journey. All implementations are in C++ (with a few Python scripts) and are designed to be efficient and easy to integrate into contest solutions.

## Categories

### Basics (17 snippets)

Fundamental algorithms and techniques every competitive programmer should know.

| Snippet | Description |
|---------|-------------|
| Binary Exponentiation | Fast exponentiation in O(log n) |
| Binary Search | Classic binary search implementation |
| Binomial Coefficients | Computing nCr efficiently |
| Bitmasks | Bit manipulation techniques |
| Bitwise Operations | Common bitwise operations and tricks |
| Bubble Sort | Simple comparison-based sorting |
| Counting Sort | Linear time sorting for integers |
| Divisors | Finding all divisors of a number |
| GCD and LCM | Greatest common divisor and least common multiple |
| Harmonic Number Example | Harmonic series applications |
| Insertion Sort | Simple sorting algorithm |
| Merge Sort | Divide and conquer sorting O(n log n) |
| Prefix Sum | 1D prefix sum array |
| Prefix Sum 2D | 2D prefix sum for submatrix queries |
| Prefix Xor | XOR prefix array |
| Selection Sort | Simple comparison-based sorting |
| Two Pointers | Two pointer technique |

### Data Structures (62 snippets)

Advanced data structures for efficient query processing.

| Category | Snippets |
|----------|----------|
| **Trees** | Segment Tree, Segment Tree Lazy, Segment Tree Persistent, Segment Tree 2D Dynamic, Segment Tree Beats, XOR Segment Tree, Sparse Table, Sparse Table 2D, Disjoint Sparse Table, SQRT Tree |
| **BIT/Fenwick** | BIT, BIT with Range Update and Range Query, BIT 2D with Range Update and Range Query |
| **DSU** | DSU, DSU with Rollbacks, DSU Partially Persistent, DSU on Tree, Augmented DSU |
| **Treaps** | Treap, Treap Persistent, Implicit Treap, Cartesian Tree |
| **Trees (Advanced)** | Link Cut Tree, Top Tree, HLD, LCA, Centroid Decomposition, Centroid Decomposition Persistent, Binarizing a Tree, Balanced Bracket Tree |
| **Other** | BST, BST using STL, Trie, Persistent Trie, Wavelet Tree, Permutation Tree, Reachability Tree, KD Tree |
| **Queries** | MO's Algorithm, MO's Online, MO's on Tree, MO's with DSU, MO's with Update, 4D MO, Monotonous Queue, Interval Set |
| **Persistence** | Persistent Array, Persistent Queue, Persistent Meldable Heap, Persistent UnionFind |
| **Special** | GP Hash Table, Ordered Set, Queue Undo Trick, Dynamic Connectivity Problem, Dynamic Diameter Online, Square Root Decomposition, Static to Dynamic Trick, Venice Technique |

### Dynamic Programming Optimizations (22 snippets)

Techniques to optimize DP solutions.

| Snippet | Description |
|---------|-------------|
| 1D1D DP | Optimization for specific DP recurrences |
| Bounded Knapsack | Knapsack with limited item counts |
| Connected Component DP | DP on connected components |
| Convex Hull Trick | Optimizing DP with linear functions |
| DP Over Divisors | DP optimized for divisor-based problems |
| DP on Convex Hulls | DP combined with convex hull |
| Digit DP | DP on digits of numbers |
| Divide and Conquer Optimization | D&C for specific DP types |
| Dynamic Convex Hull Trick | Online convex hull trick |
| Dynamic Submask Count | Counting submasks dynamically |
| Hirschberg's Algorithm | Space-efficient LCS |
| Knuth Optimization | O(n²) to O(n log n) optimization |
| Li Chao Tree | Alternative to convex hull trick |
| Persistent CHT | Persistent convex hull trick |
| Persistent Li Chao Tree | Persistent version of Li Chao tree |
| SOS DP | Sum over subsets DP |
| SOS Convolutions | Convolutions using SOS DP |
| Subset Sum in SQRT | SQRT decomposition for subset sum |
| Subset Union of Bitsets | Efficient subset union |
| XOR Equation | Solving XOR-based equations |
| x² + 1 Trick | Specific DP optimization |
| Number of Subsequences Having Product at least K | Counting subsequences |

### Game Theory (4 snippets)

Algorithms for solving combinatorial games.

| Snippet | Description |
|---------|-------------|
| Alpha Beta Pruning | Minimax optimization |
| Blue Red Hackenbush | Hackenbush game variant |
| Green Hackenbush | Another Hackenbush variant |
| Matching Game On A Graph | Graph-based game theory |

### Geometry (13 snippets)

Computational geometry algorithms.

| Snippet | Description |
|---------|-------------|
| Geometry 2D | Basic 2D geometry primitives |
| Geometry 3D | 3D geometry operations |
| Closest Pair of Points | Finding closest pair in O(n log n) |
| Convex Hull Dynamic | Dynamic convex hull maintenance |
| Half Plane Intersection | Intersection of half-planes |
| Half Plane Intersection Dynamic | Dynamic half-plane intersection |
| Delaunay Triangulation | Triangulation algorithm |
| Voronoi Diagram | Voronoi diagram construction |
| All Pair Segment Intersection | Detecting all segment intersections |
| Onion Decomposition | Decomposing point set into convex layers |
| Point Location | Locating points in planar subdivisions |
| Rectangle Union | Area of union of rectangles |
| Maximum Area of Triangle | Given lengths, find maximum area |

### Graph Theory (90 snippets)

Comprehensive graph algorithms collection.

| Category | Snippets |
|----------|----------|
| **Traversal** | BFS, DFS, Topological Sorting |
| **Shortest Paths** | Dijkstra, Bellman Ford, Floyd Warshall, Johnson's Algorithm, SPFA, Dijkstra on Segment Tree |
| **MST** | Kruskal's MST, Prim's MST, Boruvka's Algorithm, Directed MST, Manhattan MST, Dynamic MST Offline, Minimum Diameter Spanning Tree |
| **Connectivity** | Articulation Points, Articulation Bridges, SCC, Block Cut Tree, Three Edge Connectivity, Online Articulation Bridges |
| **Matching** | Blossom Algorithm, Blossom Algorithm Weighted, HopCroft Karp, Hungarian Algorithm, Kuhn's Algorithm, Randomized Matching |
| **Flow** | Dinic's Algorithm, Min Cost Max Flow, L-R Flow, Maximum Closure Problem, Maximum Density Subgraph |
| **Trees** | LCA, LCA in O(1), Centroids, Tree Diameter, Tree Isomorphism, Virtual Tree, Dominator Tree, Prufer Code, Long Path Decomposition |
| **Cuts** | Gomory Hu Tree, Stoer Wagner Algorithm, Min Cut in Planar Graph, Unique Min Cut |
| **SAT** | 2-SAT, 3-SAT |
| **Cycles** | Cycle Detection, 3-Cycle and 4-Cycle, Minimum Mean Weight Cycle, Euler Path |
| **Special** | Chromatic Number, Chromatic Polynomial, Maximum Clique, Cactus Graph, Chordal Graph, ST Numbering, DAG Reachability Dynamic, Eppstein's Algorithm, Steiner Tree Problem |

### Math (60 snippets)

Linear algebra, polynomials, and mathematical algorithms.

| Category | Snippets |
|----------|----------|
| **FFT/NTT** | FFT, NTT, NTT 2D, NTT Online, NTT with Any Prime MOD |
| **Polynomials** | Polynomial, Polynomial Sum, Polynomial Factorization, Polynomial with Binomial Coefficients |
| **Matrices** | Matrix Exponentiation, Determinant, Inverse of a Matrix, Gaussian Elimination, Hafnian, Permanent |
| **Linear Algebra** | Basis Vector, BerleKamp Massey, Linear Recurrence, Characteristic Polynomial |
| **Transforms** | FWHT, FWHT in Any Base, FWHT in Ternary Base, Cyclic Convolution |
| **Interpolation** | Lagrange Interpolation, Vandermonde Matrix |
| **Optimization** | Simplex Algorithm, Lagrange Multiplier |
| **Other** | Modint, BigInt operations, Integration methods |

### Miscellaneous (25 snippets)

Various useful algorithms and techniques.

| Snippet | Description |
|---------|-------------|
| BigInt | Arbitrary precision integers |
| Bitset Custom | Custom bitset implementation |
| Dates | Date manipulation utilities |
| Expression Parsing | Parsing mathematical expressions |
| Fraction Binary Search | Binary search on fractions |
| Gray Code | Gray code generation |
| Inversions | Counting inversions |
| Josephus Problem | Classic Josephus problem |
| K-th Root of a Permutation | Permutation operations |
| Knight Moves in Infinity Grid | Chess knight problems |
| Matroid Intersection | Color graphic/linear matroid |
| MEX of all Subarrays | Minimum excludant queries |
| Min Plus Convolution | Convex min-plus convolution |
| Parallel Binary Search | Parallelized binary search |
| Permutation Cycles | Cycle decomposition |
| Schreier–Sims Algorithm | Group theory algorithm |
| Stress Testing | Template for stress testing |
| And more... | |

### Number Theory (74 snippets)

Number theoretic algorithms and functions.

| Category | Snippets |
|----------|----------|
| **Primes** | Sieve, Sieve Linear, Segmented Sieve, Sieve upto 1e9, Miller Rabin, Pollard Rho, Prime Counting Function |
| **Modular** | CRT, Extended Euclid, Modular Inverse, Multiplicative Order, Discrete Log, Discrete Root, Tonelli Shanks |
| **Combinatorics** | Combinatorics Basics, Derangement, Bell Number, Stirling Numbers (1st and 2nd kind), Lucas Theorem, nCr Modulo Any Mod |
| **Divisors** | Phi Function, Mobius Function, K Divisors, Sum of Divisors, Linear Sieve for Multiplicative Functions |
| **Equations** | Linear Diophantine Equations (2 and N variables), Linear Congruence, Pell's Equation |
| **Special** | Fibonacci (fast), Pisano Period, Partition Function, Continued Fractions, Floor Sum, Power Tower |
| **Sieves** | Min_25 Sieve, Powerful Number Sieve |

### Strings (24 snippets)

String processing algorithms.

| Snippet | Description |
|---------|-------------|
| Aho Corasick | Multi-pattern matching |
| Aho Corasick Dynamic | Dynamic version |
| KMP | Knuth-Morris-Pratt algorithm |
| Z Algorithm | Z-function computation |
| Manacher's | Palindrome detection |
| Suffix Array | Suffix array construction |
| Suffix Array Isomorphic | Isomorphic suffix array |
| Suffix Automaton | String automaton |
| Palindromic Tree | Eertree structure |
| Palindromic Tree Persistent | Persistent version |
| String Hashing | Polynomial hashing |
| String Hashing 2D | 2D string hashing |
| String Hashing With Updates | Dynamic hashing |
| String Matching With FFT | FFT-based matching |
| String Matching using Bitsets | Bitset-based matching |
| De Bruijn Sequence | Generating De Bruijn sequences |
| LCS variants | Bit LCS, Cyclic LCS, All Substring LCS |
| Prefix Automaton | Automaton for prefixes |
| Minimum Palindrome Factorization | Factorizing into palindromes |
| Number of Palindromes in Range | Counting palindromes |

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/SarvikIIT/Competitive-Programming-Snippets.git
   ```

2. Navigate to the desired category folder and copy the snippet you need.

3. Adapt the code to your specific problem requirements.

**Note:** Most snippets are self-contained and can be directly copied into your solution. Some may require minor modifications based on problem constraints.

## Contributing

Contributions are welcome! If you have improvements or new snippets to add:

1. Fork the repository
2. Create a new branch for your feature
3. Add your snippet with clear comments
4. Submit a pull request

---

*Happy Competitive Programming! 🚀*
