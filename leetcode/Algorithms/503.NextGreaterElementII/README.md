Given a circular array (the next element of the last element is the first element of the array), print the Next Greater Number for every element. The Next Greater Number of a number x is the first greater number to its traversing-order next in the array, which means you could search circularly to find its next greater number. If it doesn't exist, output -1 for this number.

**Example 1:**
<pre>
<b>Input:</b> [1,2,1]
<b>Output:</b> [2,-1,2]
<b>Explanation:</b> The first 1's next greater number is 2; 
The number 2 can't find next greater number; 
The second 1's next greater number needs to search circularly, which is also 2.
</pre>

**Note:** The length of given array won't exceed 10000.

### [Editorial](https://leetcode.com/articles/next-greater-element-ii/)