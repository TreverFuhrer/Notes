---
tags: 
Hub: "[[Patterns]]"
---
### Description
---
- **Greedy Choice Property** → At each step, you make the best immediate choice without reconsidering past decisions.
- **Optimal Substructure** → A globally optimal solution can be built by combining locally optimal choices.

**Different Types of Greedy Problems:**
1. **Tracking Smallest/Largest Values** → Like this problem (increasing triplet subsequence).
2. **Interval Scheduling** → "Select the most efficient job or meeting first" (e.g., Activity Selection Problem).
3. **Priority Queue Based** → Huffman Encoding, Dijkstra’s Algorithm (greedy with a heap).
4. **Sorting-Based** → "Process the smallest/largest first" (e.g., Minimum Number of Arrows to Burst Balloons).

### Example Code
--- 
<!--Leetcode problem-->
```python
# Code written by Trever Fuhrer
class Solution:
	def increasingTriplet(self, nums: List[int]) -> bool:
		i, j = inf, inf
		for num in nums:

		# Whats greedy about this is
			if num <= i:
				i = num
			elif num <= j:
				j = num
			else:
				return True

		return False
```