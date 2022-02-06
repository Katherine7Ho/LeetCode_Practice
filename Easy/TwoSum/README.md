# Title
**1. Two Sum**
<br>Given an array of integers `nums` and an integer `target`, return _indices of the two numbers such that they add up to `target`_. 

<br>You may assume that each input would have **_exactly_ one solution**, and you may not use the _same_ element twice. 

<br>You can return the answer in any order.

# 中文
<br>輸入 整數`array`以及 整數 `target`，輸出 任兩個元素相加為`target`的元素位置(index)。每次只會有一種答案，而且不能重複使用同一個元素，也就是答案不能出現同樣位置。

# 舉例

    try

**Example 1:**
  <br>**Input:** nums = [2, 7, 11, 15], target = 9
  Output: [0, 1]
  Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].


**Example 2:**
```
Input: nums = [3, 2, 4], target = 6
Output: [1, 2]
```

**Example 3:**
```
Input: nums = [3, 3], target = 6
Output: [0, 1]
```
