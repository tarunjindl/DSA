# DSA

1. https://math.stackexchange.com/questions/1890620/finding-path-lengths-by-the-power-of-adjacency-matrix-of-an-undirected-graph
2. 
3. Don't forget the modulo:
   (a + b) % M = (a % M + b % M) % M
   (a - b) % M = (a % M - b % M) % M and in Java modulo could be negative so you need to bring into an extra M, thus (a % M - b % M + M) % M
4. This will take care of Positive and negative modulo.  
```
 next = next % nums.length + nums.length;
 next %= nums.length;
```

DP 

1. https://leetcode.com/problems/domino-and-tromino-tiling/discuss/116612/Easy-to-understand-O(n)-solution-with-Drawing-Picture-Explanation!
2. https://leetcode.com/problems/number-of-longest-increasing-subsequence/discuss/107293/JavaC++-Simple-dp-solution-with-explanation/148157
3. In this type of dp, we can do something or skip something. It's called making a decision. Using this approach, we can create the dp relationship. The general problem statement for this pattern is forgiven situation decide whether to use or not to use the current state. So, the problem requires you to make a decision at a current state.
	1. https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/discuss/108871/2-solutions-2-states-DP-solutions-clear-explanation!
	2. https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/discuss/283701/Python-recursive-solution-%2B-memoization
4. In this type of dp, Given a set of numbers find an optimal solution for a problem considering the current number and the best you can get from the left and right sides.
	1. https://leetcode.com/problems/unique-binary-search-trees/solution/
	2. 
5. DP on String 
	1. https://leetcode.com/problems/edit-distance/submissions/
	2. 

Graphs 
1. 2-color problem/Bipartite
	1. https://leetcode.com/problems/is-graph-bipartite/
2. Dijkstra's 
	1. https://leetcode.com/problems/shortest-path-in-binary-matrix/
	2. https://java2blog.com/dijkstra-java/
	3. https://stackoverflow.com/questions/57844537/what-is-the-point-of-adding-and-removing-the-element-from-priority-queue-in-the
	4. Implementation without Distance array and visited set - https://leetcode.com/problems/network-delay-time/discuss/515730/Java-Dijkstra-Solution-explained-%3A%3A-We-should-maintain-a-distance-array-too
	5. Implementation with Distance Array - https://leetcode.com/problems/network-delay-time/discuss/109968/Simple-JAVA-Djikstra's-(PriorityQueue-optimized)-Solution-with-explanation (Use this.)
3. Union Find Set
	1. https://www.youtube.com/watch?v=ID00PMy0-vE
	2. https://leetcode.com/problems/longest-consecutive-sequence/discuss/326499/Java-O(N)-Union-Set-Find  (TODO)
4. Bellman Ford (works with negative weights)
	1. 
5. Floyd Warshall -  Floyd-Warshall algorithm is used to find all pair shortest path problem from a given weighted graph and works with negative weights
	1. 
6. Topological 
	1. https://leetcode.com/problems/find-eventual-safe-states/discuss/120633/Java-Solution-(DFS-andand-Topological-Sort)
	2. 

String
1. Rabin Karp - https://www.youtube.com/watch?v=H4VrKHVG5qI
2. KMP - https://www.youtube.com/watch?v=KG44VoDtsAA
3. 

Sliding Window Techniqe
1. https://leetcode.com/problems/permutation-in-string/discuss/559278/Java-Sliding-Window-Clear-explanation-Clean-and-Concise
2. https://leetcode.com/problems/count-number-of-nice-subarrays/discuss/1701501/JAVAororO(n)ororSliding-windowororClear-solutionoror-similar-to-lc930-and-lc992
Maths 
1. https://leetcode.com/problems/count-number-of-nice-subarrays/discuss/1701501/JAVAororO(n)ororSliding-windowororClear-solutionoror-similar-to-lc930-and-lc992
Arrays
1. Floyd's tortoise and hare - https://leetcode.com/problems/find-the-duplicate-number/submissions/
2. https://leetcode.com/problems/spiral-matrix/
3. https://leetcode.com/problems/rotate-image/submissions/

Stacks
1. https://leetcode.com/problems/buildings-with-an-ocean-view/ 
2. 
