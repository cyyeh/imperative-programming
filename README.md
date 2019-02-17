# CS 15-122: Principles of Imperative Computation

- [course website](https://www.cs.cmu.edu/~15122/home.shtml)

## Learning Objectives

### Computational Thinking

Students who complete this course should be able to explain abstraction and other key computer science concepts, apply these fundamental concepts as problem-solving tools, and wield _contracts_ as a tool for reasoning about the safety and correctness of programs. In particular, we expect students to be able to:

1.  develop contracts (preconditions, postconditions, assertions, and loop invariants) that establish the safety and correctness of imperative programs.
2.  develop and evaluate proofs of the safety and correctness of code with contracts.
3.  develop and evaluate informal termination arguments for programs with loops and recursion.
4.  evaluate claims of both asymptotic complexity and practical efficiency of programs by running tests on different problem sizes.
5.  define the concept of programs as data, and write programs that use the concept.
6.  defend the use of abstractions and interfaces in the presentation of algorithms and data structures.
7.  identify the difference between _specification_ and _implementation_.
8.  compare different implementations of a given specification and different specifications that can be applied to a single implementation.
9.  explain data structure manipulations using data structure invariants.
10.  identify and evaluate the use of fundamental concepts in computer science as problem-solving tools:
    1.  order (sorted or indexed data),
    2.  asymptotic worst case, average case, and amortized analysis,
    3.  randomness and (pseudo-)random number generation, and
    4.  divide-and-conquer strategies.

### Programming Skills

Students who complete this course should be able to read and write code for imperative algorithms and data structures. In particular, we expect students to be able to:

1.  trace the operational behavior of small imperative programs.
2.  identify, describe, and effectively use basic features of C0 and C:
    1.  integers as signed modular arithmetic,
    2.  integers as fixed-length bit vectors,
    3.  characters and strings,
    4.  Boolean operations with short-circuiting evaluation,
    5.  arrays,
    6.  loops (<tt>while</tt> and <tt>for</tt>),
    7.  pointers,
    8.  structs,
    9.  recursive and mutually recursive functions,
    10.  <tt>void</tt> pointers and casts between pointer types,
    11.  contracts (in C0), and
    12.  casts between different numeric types (in C).
3.  translate between high-level algorithms and correct imperative code.
4.  translate between high-level loop invariants and data structure invariants and correct contracts.
5.  write code using external libraries when given a library interface.
6.  develop, test, rewrite, and refine code that meets a given specification or interface.
7.  develop and refine small interfaces.
8.  document code with comments and contracts.
9.  identify undefined and implementation-defined behaviors in C.
10.  write, compile, and test C programs in a Unix-based environment using <tt>make</tt>, <tt>gcc</tt>, and <tt>valgrind</tt>.

### Algorithms and Data Structures

Students who complete this course should be able to describe the implementation of a number of basic algorithms and data structures, effectively employ those algorithms and data structures, and explain and interpret worst-case asymptotic complexity arguments. In particular, we expect students to be able to:

1.  determine the big-O complexity of common code patterns.
2.  compare common complexity classes like _O(1)_, _O(n)_, _O(n log(n))_, _O(n<span class="sup">2</span>)_, and _O(2<span class="sup">n</span>)_.
3.  explain the structure of basic amortized analysis proofs that use potential functions.
4.  apply principles of asymptotic analysis and amortized analysis to new algorithms and data structures.
5.  recognize properties of simple self-adjusting data structures.
6.  recognize algorithms and data structures using divide-and-conquer.
7.  describe and employ a number of basic algorithms and data structures:
    1.  integer algorithms,
    2.  linear search,
    3.  binary search,
    4.  sub-quadratic complexity sorting (mergesort and quicksort),
    5.  stacks and queues,
    6.  pseudo-random number generators,
    7.  hash tables,
    8.  priority queues,
    9.  balanced binary search trees,
    10.  disjoint-set data structures (union/find), and
    11.  simple graph algorithms.