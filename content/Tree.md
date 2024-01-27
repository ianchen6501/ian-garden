---
title: Algorithm - Tree
draft: false
tags:
  - Algorithm
---

## [[BFT]] 廣度優先遍歷

[[Leetcode-100-sametree]]

## [[DFT]] 深度優先遍歷

又分為 pre order / in order / post order 三種

### pre order

- traverse 的順序為 root - left -right
- recursive

```
PREORFER
	write(n)
	for i from 0 to n's children count - 1
		PREORDER(n[i])
```

- leetcode 144

### in order

- traverse 順序為 left - root -right
- recursive

```
INORDER(n):
	INORDEr(n[0])
	write(n)
	for i from 1 to n's children count - 1:
		INORDER(n[i])
```

### [[BST]] 二元搜尋樹
