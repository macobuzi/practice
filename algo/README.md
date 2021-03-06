Step for solving:

A. Solving strategy:
  1. Complete Search: list all possible solution for selecting optimized solution or counting
       a. list all solution (brute force) (recursive or iterative or generation)
	   b. backtracking: begin with empty solution, generate RIGHT solution step by step
	   c. pruning the search: recognize when partial solution is not optimal and cut earlier
	   d. meet in the middle (or divide and conquer ?): search space divide to 2 parts of about equal size,
	                                                    search separately then combine

  2. Greedy: construct a solution by making the choice looks best at the moment, hard to prove correctness
  3. Dynamic programing: combine correctness of complete search and speed of greedy (optimal and counting problems only)
  4. Adhoc:
      - Write down test case
	  - Simulation if too complex then may be it is math problem (generating solution directly)
	  

B. Common algorithm - data structure:
  1. Binary search: note:
       - return low, which is rank of search element in sorted array
	   - how to prove: analyse last computing before halting
  2. Tree visit: inorder (lvr) , preorder (vlr), postorder (lrv)
  3. Binary search tree:
       - inorder give sorted order
  4. Balance binary search tree:
       - Red black tree: Java TreeMap, TreeSet
  5. Fastest access: HashMap, array
  6. Dynamic array: Java List (use when N is large instead of static array)
  7. Dijkstra SSSP algorithms is greedy, BellmanFord is dp
  8. Dequeue is helpful for keeping invariant (to optimized)
  9. 2 stack or 2 queue solution
  10. DFS, BFS, FloodFill
  11. DSU
  12. Trie, pass trie node along recursive computation step

C. Major Topic:
The Major Five topics are:-
  1. Ad hoc/ Implementation Problems
  2. Programming Paradigm(Greedy, backtracking, branch and bound, DP, Divide and Conquer, Brute force etc.)
  3. Graph Theory(directed, undirected, weighted, rooted(IN & OUT) and unrooted tree, DAG etc.)
  4. Math(Number theory, Computational Geometry, Combinatorics, Linear Algebra etc.)
  5. Others(String Processing, Bit Manipulation etc.)
