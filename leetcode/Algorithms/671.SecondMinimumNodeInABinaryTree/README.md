Given a non-empty special binary tree consisting of nodes with the non-negative value, where each node in this tree has exactly `two` or `zero` sub-node. If the node has two sub-nodes, then this node's value is the smaller value among its two sub-nodes.

Given such a binary tree, you need to output the **second minimum** value in the set made of all the nodes' value in the whole tree.

If no such second minimum value exists, output -1 instead.

**Example 1:**
<pre>
<b>Input:</b>
    2
   / \
  2   5
     / \
    5   7

<b>Output:</b> 5
<b>Explanation:</b> The smallest value is 2, the second smallest value is 5.
</pre>

**Example 2:**
<pre>
<b>Input:</b>
    2
   / \
  2   2

<b>Output:</b> -1
<b>Explanation:</b> The smallest value is 2, but there isn't any second smallest value.
</pre>
