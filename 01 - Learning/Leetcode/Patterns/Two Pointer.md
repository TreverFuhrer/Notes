---
tags: 
Hub: "[[Patterns]]"
---
### Description
---
- This pattern is done by creation two variables that act as pointers. One pointer will point to the start and the second pointer will point to the end of a iterable data structure. The each pointer will traverse toward each other till they meet.

### Example Code
--- 
[345. Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/)
```python
class Solution:
def reverseVowels(self, s: str) -> str:
	result = list(s)
	vowels = {'a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U'}

	# Two pointers created	
	start = 0
	end = len(s) - 1

	# Pointed go till they meet
	# 1st pointer iterates normally
	# 2nd pointer iterates in reverse
	while (start < end):
		
		# Only increment start if a vowel
		if s[start] not in vowels:
			start += 1
			
		# Only increment end if a vowel
		if s[end] not in vowels:
			end -= 1
		
		# If both are vowels swap and increment
		if s[start] in vowels and s[end] in vowels:
			result[start] = s[end]
			result[end] = s[start]
			start += 1
			end -= 1

	return "".join(result)
```