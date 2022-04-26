# Algorithms

Algorithms: methods for solving problems that are suited for computer
implementation. 

Data Structures: schemes for organizing data that leave them amenable to
efficient processing by an algorithm. 

Abstract Data Types(ADTs)
- bag
- queue
- stack

Performance is central consideration when implementing algorithms. We use the
scientific method when analyzing algorithmic performance by developing
hypotheses, create mathematical models, and run experiments to test them. 

The term algorithm is used in computer science to describe a finite,
deterministic, and effective problem-solving method suitable for implementation
as a computer program. 

We can define an algorithm by describing a procedure for solving a problem in a
natural language, or by writing a computer program that implements the
procedure. 

For example, Euclid's algorithm for finding the greatest common divisor of two
numbers. 

English-language description:
Compute the greatest common divisor of two nonnegative integers p and q as
follows:
- If q is 0, the answer is p
- If not, divide p by q and take the remainder r.
- The answer is the greatest common divisor of q and r. 

java-language description:
```
public static int gcd(int p, int q) {
    if (q == 0) {
        return p;
    int r = p % q;
    }
    return gcd(q, r)
}
```





Algoriths: methods for solving problems that are suited for computer implementation. 

We also pay careful attention to performance characteristics of our algorithms, to help us develop improved versions, compare different algorithms for the same task, and predict or guarantee performance for large problems.

The term algorithm is used in computer science to describe a problem-solving method suitable for implementation as a computer program

Most algorithms of interest involve methods of organizing the data involved in the computation. Objects created in this way are called data structures

the view that data structures exist as the byproducts or end products of algorithms,

When we use a computer to help us solve a problem, we typically are faced with a number of possible different approaches. For small problems, it hardly matters which approach we use, as long as we have one that solves the problem correctly.
For huge problems (or applications where we need to solve huge numbers of small problems), however, we quickly become motivated to devise methods that use time or space as efficiently as possible.

