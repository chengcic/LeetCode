# LeetCode

This project is LeetCode note for myself.

| Problem | Algorithm | Python | C++ |
| ------------- | ------------- | ------------- | ------------- |
| 1. Two Sum | Hash | Dict | unordered_map<int, int>, count, find |
| 2. Add Two Numbers | Recursion | None | None |
| 3. Longest Substring Without Repeating Characters | Hash | Dict | bitset, set, reset |
| 4. Median of Two Sorted Arrays | Binary Search | // and /, raise ValueError | swap |
| 5. Longest Palindromic Substring | Brute Force| self.helper | substr |
|10. Regular Expression Matching | Recursive | | |
|11. Container With Most Water | Analysis | | |
|13. Roman to Integer | Analysis | | unordered_map<> = {{,}, {,}} |
|14. Longest Common Prefix | Straght Forward | |string +=
|15. 3Sum | PreProcess | | vector<int>({a, b, c}), sort() |
|17. Letter Combinations of a Phone Number | Analysis | | |
|19. Remove Nth Node From End of List | Corner Case | | add dummpy head |
|20. Valid Parentheses | Stack | |stack<char> empty, top, push, pop |
|21. Merge Two Sorted Lists | Recursive | | |
|22. Generate Parentheses | Utilize the call stack | | |
|33. Search in Rotated Sorted Array | Binary Search | | +1 and = condition |
|48. Rotate Image | Analysis | | reverse |
|49. Group Anagrams | Hash Map | | auto it, it->fisrt, it-> second, for (m : mp) |
|53. Maximum Subarray | Dymanic Programming | | max_element(begin(), end()) |
|55. Jump Game | Greedy | | |
|66. Plus One | Straight Forward | | vector insert(it, val), rbegin, rend |
|70. Climbing Stairs | Dynamic Programming | | | 
|75. Sort Colors | Analysis | | |
|76. Minimum Window Substring | Analysis | | | numeric_limits<int>::max(), INT_MAX |
|88. Merge Sorted Array | Analysis | | | 
|94. Binary Tree Inorder Traversal | Recursive | | |
|98. Validate Binary Search Tree | Recursive | | numeric_limits<long>::min() |
|101. Symmetric Tree | Recursive | | |
|102. Binary Tree Level Order Traversal | Queue | | front(), pop(), push() |
|103. Binary Tree Zigzag Level Order Traversal | Queue | | |
|104. Maximum Depth of Binary Tree | Recursive & Queue | | |
|105. Construct Binary Tree from Preorder and Inorder Traversal | Recursive | | find, it arithmetic |
|108. Convert Sorted Array to Binary Search Tree | Recursive | | const_iterator, iterator ||
|116. Populating Next Right Pointers in Each Node | Recursive Or layer loop | | |
|345. Reverse Vowels of a String | Two pointers | | find_first_of, find_last_of |
|173. Binary Search Tree Iterator | Stack | | top, push, pop |
|657. Robot Retrun to Origin | Count | | switch, default |
|832. Flipping an Image | For loop | | |
|760. Find Anagram Mappings | Hash Map | | |
|463. Island Perimeter | Math method | | |
|228. Summary Ranges | Tow pointer | | |
|739. Daily Temperatures | Daynamic Programming | | |
|118. Pascal's Triangle | Straight Forward | | |
|121. Best Time to Buy and Sell Stock | Straight Forward | | |
|136. Single Number | XOR | | ^ |
|141. Linked List Cycle | Two Pointer | | |
|148. Sort List | Divide and Conquer | | Corner case |
|150. Evaluate Reverse Polish Notation | Stack | | stoi, stof, stol, stod, stoll, stoul, to_string|
|155. Min Stack | Stack | | |
|160. Intersection of Two Linked Lists | Analysis | | |
|169. Majority Element | Vote analysis | | |
|189. Rotate Array | Reverse | | |
|198. House Robber | Dynamic Programming | | |
|206. Reverse Linked List | Straight Forward | | Corner Case |
|217. Contains Duplicate | Hash | | unordered_set, insert, clear, count, erase |
|230. Kth Smallest Element in a BST | Recursive | | INT_MIN used as invalid answer|
|234. Palindrome Linked List | Analysis | | Reverse the list, corner case 
|236. Lowest Common Ancestor of a Binary Tree | Recursive | | |
|268. Missing Number | XOR | | ^ |
|279. Perfect Squares | Dynamic Programming | | |
|283. Move Zeroes | Swap | | |
|287. Find the Duplicate Number | Hash & Cycle Link | | |
|347. Top K Frequent Elements | Hash & Heap sort | | make_pair, multi_map use insert |
| 41. First Missing Positive | Hash & Position Check | | count, insert |
| 42. Trapping Rain Water | Dynamic Programming | | |
| 122. Best Time to Buy and Sell Stock II | Analysis | | |
| 125. Valid Palindrome | Two Pointer | | isalnum, isalpha, tolower, toupper, isdigit, isblank, atoi, atof, atol |
| 171. Excel Sheet Column Number | Numeric Conversion | | |
| 172. Factorial Trailing Zeroes | Numeric Analysis | | |
| 190. Reverse Bits | Numeric Analysis | | |
| 191. Number of 1 Bits | Numeric Analysis | | n &= (n - 1), >>=|
| 202. Happy Number | Hash & Cycle | | |
| 204. Count Primes | Flag | | |
| 237. Delete Node in a Linked List | Value | | |
| 242. Valid Anagram | Count histogram | | |
| 328. Odd Even Linked List | Corner Case | | |
| 326. Power of Three | Numeric Analysis | | |
| 231. Power of Two | Numeric Analysis | | (1 << 31) % n == 0  n&(n-1)==0 |
| 344. Reverse String | Straigt Forward | | |
| 350. Intersection of Two Arrays II | Hash | | |
| 371. Sum of Two Integers | Analysis | | |
| 387. First Unique Character in a String | Histogram & Hash | | |
| 412. Fizz Buzz | Straight Forward| | |
| 238. Product of Array Except Self | Straight Forward | | |
| 34. Find First and Last Position of Element in Sorted Array | Binary Search | | Terminate condition for binary search is crucial|
| 44. Wildcard Matching | Dynamic Programming | | DPBook meaning | 
| 46. Permutations | Recursive | | | 
| 50. Pow(x, n) | Divde and Conquer | | Pay attention to overflow | 
| 54. Spiral Matrix | Code | |Pay attention to corner case | 
| 56. Merge Intervals | Sort | | sort, function pointer | 
| 62. Unique Paths | Dynamic Programming | | fill(begin, end, val), formula C(m,n)| 
| 73. Set Matrix Zeroes | Axis perspective | | find(begin, end, val) | 
| 78. Subsets | Divide and Conquer | | insert(begin, begin, end), bitmanipulate| 
| 91. Decode Ways | Dynamic Programming | | Test use case, 0 manipulate | 
| 139. Word Break | Dynamic Programming | | | 
| 128. Longest Consecutive Sequence | Hash | | | 
| 130. Surrounded Regions | Replace | | |
| 179. Largest Number | Sort | | Corner case '0'|
| 200. Number of Islands | Replace | | |
| 215. Kth Largest Element in an Array | Heap && Quick sort | | |
| 240. Search a 2D Matrix II | Analysis | | |
| 322. Coin Change | Dynamic Programming | | |
| 329. Longest Increasing Path in a Matrix | Dynamic Programming | | |
| 134. Gas Station | Analysis | | |
| 295. Find Median from Data Stream | Heap | | lower_bound, upper_bound is using binary search to find the place, priority_queue, pop, push, top|
| 378. Kth Smallest Element in a Sorted Matrix | Heap | | make_pair, greater<int>, bool operator() (const T&, const T&) |
| 239. Sliding Window Maximum | deque | | deque, pop_front(), pop_back(), back(), front() |
| 127. Word Ladder | BFS | | queue, front(), pop(), push() |
| 297. Serialize and Deserialize Binary Tree | DFS | | substr, find |
| 324. Wiggle Sort II | Sort | | |
| 138. Copy List with Random Pointer | Tricky weave | | |
| 454. 4Sum II | Hash | | |
| 149. Max Points on a Line | map | | gcd |
| 380. Insert Delete GetRandom O(1) | Hash | | erase, rand() |
| 166. Fraction to Recurring Decimal | Hash | | string.insert(pos, n, char) |
| 79. Word Search | DFS | | |
| 162. Find Peak Element | Binary Search | | |
| 289. Game of Life | | |
| 131. Palindrome Partitioning | DFS | | push_back -> pop_back in DFS|
| 208. Implement Trie (Prefix Tree) | Data structure | | |
| 384. Shuffle an Array | | | rand(), swap() |
| 334. Increasing Triplet Subsequence | | | use mark |
| 69. Sqrt(x) | Binary Search && Newton | | |
| 12. Integer to Roman | Look up | | |
| 84. Largest Rectangle in Histogram | Stack | | |
| 207. Course Schedule | TopSort | | |
| 210. Course Schedule II | TopSort | | |
| 212. Word Search II | Tries & DFS | | |
| 395. Longest Substring with At Least K Repeating Characters | Divide and Conquer | | |
| 341. Flatten Nested List Iterator | Stack | | |
| 300. Longest Increasing Subsequence | Dynamic Programming | | |
| 67. Add Binary | Recursive | | |
| 349. Intersection of Two Arrays | Hash | | unordered_set (vector.begin(), vector.end()) |
| 441. Arranging Coins | | | |
| 39. Combination Sum | Recursive | | |
|336. Palindrome Pairs | Hash Table | | |
|280. Wiggle Sort | Swap | | |
|146. LRU Cache | Hash & List | | struct remember ";", list, push_front, pop_front, pop_front, push_back, splice, auto iterator, list iterator regard as pointer | 
|252. Meeting Rooms | Sort | | struct bool operator() (const T& a, const T& b) |
|236. Meeting Rooms II | Sort Heap | | priority_queue<T, vector<T>, less> default maxHeap|
|100. Same Tree | Recursive | | |
|904. Fruit Into Baskets | Hash Count | | |
|205. Isomorphic Strings | Position check | | |
|120. Triangle | Dynamic Programming | | |
|81. Remove Duplicates from Sorted List | Two pointers | | |
|63. Unique Paths II | Dynamic Programming | | |
|119. Pascal's Triangle II | Analysis | | |
|96. Unique Binary Search Trees | Dynamic Programming | | |
|157. Read N Characters Given Read4 | Corner Case | | |
|153. Find Minimum in Roatated Sorted Array | Binary Search | | |
|285. Inorder Successor in BST | Recursive | | |
|203. Remove Linked List Elements | Two pointer | | |
|246. Strobogrammatic Number | Analysis | | |
|346. Moving Average from Data Stream | Sliding Window | | |
|416. Partition Equal Subset Sum | Dynamic Programming | | |
|325. Maximum Size Subarray Sum Equals k | Hash map | | |
|540. Single Element in a Sorted Array | Binary Search | | |
| 43. Multiply Strings | Simulation | | find_first_not_of, substr, string::npos |
| 57. Insert Interval | Analysis | | |
| 316. Remove Duplicate Letters | Record | | |
| 68. Text Justification | Analysis | | ceil |
| 77. Combinations | Analysis index | | |
| 58. Length of Last Word | Loop | | |
| 85. Maximal Rectangle | Dynamic Programming | | |
| 109. Convert Sorted List to Binary Search Tree | Recursive | | |
| 113. Path Sum II | Recursive | | |
| 114. Flatten Binary Tree to Linked List | Recursive | | |
| 163. Missing Ranges | Analysis | | Be careful on overflow | 

Google Interview
1. Data structure & algoritm. Time complexity and space complexity
	NP problems - what does NP complete actutally means.
		travels salsman
		nap stocks
2. Math problem
	Probablity & Counting problem & 排列组合
3. Operating System
	Process & Thread, semaphores new Texas locks
	Resource
	Context Switching
	How scheduling works
4. System design

Quadratic
Linear
1. Ask question
2. Talk constantly
3. Watch out the edge case

Blog
1. Merge sort
2. Hash Table -> How does they work
3. Trees -> Binary tree, Trie Trees, n-ary tree, AVL tree, red-black tree, 
4. Dijkstra, A*
5. traveling salesman, knapsack
6. NP-hard problem
7. OS: locks, mutex, semaphores, monitors
	deadlock, livelock 
Know what resources a processes needs, and a thread needs, and how context switching works, and how it's initiated by the operating system and underlying hardware.
