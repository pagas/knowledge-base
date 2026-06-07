Given an array of integers and a target value, return the indices of the two numbers whose sum equals the target.
## Fast solution

```python
    for i, num in enumerate(nums):
	    # calculate the needed pair
        complement = target - num
        if complement in seen:
            return [seen[complement], i]
        seen[num] = i
```
Time complexity: **O(n)**
## Slow solution

```python
for i in range(len(nums)):
    for j in range(i+1, len(nums)):
        if nums[i] + nums[j] == target:
            return [i, j]
```

Time complexity: **O(n²)**

[Code](https://codesandbox.io/p/devbox/ytgtvv?file=%2Fmain.py%3A11%2C5)