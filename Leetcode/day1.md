Day 1 [Task](https://docs.qq.com/doc/DUG9UR2ZUc3BjRUdY) 

[数组理论基础](https://programmercarl.com/%E6%95%B0%E7%BB%84%E7%90%86%E8%AE%BA%E5%9F%BA%E7%A1%80.html)

- 1D array: 内存地址 / 字符数组 /下标
- 2D array：a[row][column]

- 数组的元素是不能删的，只能覆盖

[704. Binary Search](https://leetcode.com/problems/binary-search/description/) - Easy


- time complexity `nlog(n)`

- 边界条件
    1. [left, right]: left <= right; right = middle +1 
    2. [left, right): left < right; right = middle 


[27. Remove Element](https://leetcode.com/problems/remove-element/description/) - Easy

- space complexity: O(1) 
- 数组中地址是连续的，不能删除，只能覆盖
- solution:
    1. Brute Force: two for loop: time O(n^2)
    2. slow/fast pointer: time O(n)