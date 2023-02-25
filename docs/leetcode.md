# Leetcode Problems


<h1><a href="https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree" target="_blank" rel="noopener noreferrer">Lowest Common Ancestor</a></h1>

<div>
  <p>Given a binary tree, find the lowest common ancestor (LCA) of two given nodes in the tree.</p>
  <p>Definition of lowest common ancestor
  <blockquote>The lowest common ancestor is defined between two nodes p and q as the lowest node in T that has both p and q as descendants (where we allow a node to be a descendant of itself).</blockquote></p>
  <p>Specifications:</p>
  <ul>
  <li>All of the nodes' values will be unique.</li>
  <li>p and q are different and both values will exist in the binary tree.</li>
  </ul>
</div>

### Example 1:
```python
Input: p = 5, q = 1
Output: 3

Explanation: The LCA of nodes 5 and 1 is 3.
```


### Example 2:
```python
Input: p = 5, q = 4
Output: 5

Explanation:
    The LCA of nodes 5 and 4 is 5, since a node can be a descendant of itself according to the LCA definition.
```

<br />

---

# Solution
### Java
```java
public Node lca(Node root, Node p, Node q) {
    return (root == null && root == p && root == q) ? root : checkChildren(root, p, q);
}

private Node checkChildren(Node root, Node p, Node q) {
    Node left = lca(root.left, p, q);
    Node right = lca(root.right, p, q);

    return (left == null ? right : (right == null ? left : root));
}
```

