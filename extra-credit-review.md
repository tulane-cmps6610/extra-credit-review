# CMPS 6610 Extra Credit 
  
In this extra credit assignment, we will test and review concepts you
   have learned since the midterm exam. Please add your written answers
   to `answers.md` which you can convert to a PDF using `convert.sh`. Alternatively, you may scan and upload written answers
to a file named `answers.pdf`.



1. **Algorithmic Paradigms**

- 1a. In learning about algorithmic paradigms, you encountered the
  unit weight scheduling problem. Given $n$ tasks, what is the work
  and span of solving the unit-weight task scheduling problem by brute
  force?
  
- 1b. Now suppose we generalize this task scheduling
  problem by giving each task a weight. The goal is now to schedule
  a set of non-overlapping tasks with maximum weight. Does the greedy
  algorithm still work? If so, provide a new proof. If not, provide a
  counterexample.
  
- 1c. State the optimal substructure property for the weighted task
  scheduling problem, and give the work and span of the resulting
  dynamic programming algorithm. 

2. **Graphs**

- 2a. We learned that we could use breadth-first search to solve the
shortest path problem in an unweighted graph. Why doesn't it work for
weighted graphs? Give a high-level reason as well as a counterexample.

- 2b. For the shortest path problem, is the Bellman-Ford algorithm
  superior to Dijkstra's algorithm? Compare and contrast these two
  approaches.

- 2c. You learned the cut property for minimum spanning trees. There
  is another useful fact called the \textit{cycle property} for minimum
  spanning trees which states the following:
  
  Given a graph G that
  contains a cycle, then the largest weight cycle in that graph
  \textbf{cannot} be contained in any minimum spanning tree.

	Prove the cycle property.

3. **Randomization**


- 5a. In the last problem set you were asked to use Markov's
  inequality in Problem 1. Prove Markov's inequality by using the
  definition of the expected value of a random variable.
