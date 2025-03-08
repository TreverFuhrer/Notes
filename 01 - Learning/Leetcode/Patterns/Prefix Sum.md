---
tags: 
Hub: "[[Patterns]]"
---
### Description
---
- 

### Example Code
--- 
[238. Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)
```python
# Code written by Trever Fuhrer
class Solution:
	def productExceptSelf(self, nums: List[int]) -> List[int]:
		answer = []
		
		prefix = 1
		for i in range(len(nums)):
			answer.append(prefix)
			prefix *= nums[i]
		
		suffix = 1
		for i in range(len(nums) -1, -1, -1):
			answer[i] *= suffix
			suffix *= nums[i]
			
		return answer
```