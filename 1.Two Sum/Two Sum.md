# Two Sum

## **Problem**

Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

**Example 1:**
```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].
```

**Example 2:**
```
Input: nums = [3,2,4], target = 6
Output: [1,2]
```

**Example 3:**
```
Input: nums = [3,3], target = 6
Output: [0,1]
```

**Constraints:**
- <table><tr><td bgcolor=#ffffff><!-- $2\leq\mathrm{nums.length}\leq10^4$ --> <img style="transform: translateY(0.1em); background: white; color: yellow" src="svg\MBg0w2btcZ.svg"></td></tr></table>
- <table><tr><td bgcolor=#ffffff><!-- $-10^9\leq\mathrm{nums}\left[i\right]\leq10^9$ --> <img style="transform: translateY(0.1em); background: white;" src="svg\neympIz3XT.svg"></td></tr></table>
- <table><tr><td bgcolor=#ffffff><!-- $-10^9\leq\mathrm{target}\leq10^9$ --> <img style="transform: translateY(0.1em); background: white;" src="svg\kQBALEWwkM.svg"></td></tr></table>
- **Only one valid answer exists.**

**Follow-up:**\
Can you come up with an algorithm that is less than <!-- $O(n^2)$ --> <img style="transform: translateY(0.1em); background: white;" src="svg\8xtv7tt1gK.svg"> time complexity?

## **Solution**
