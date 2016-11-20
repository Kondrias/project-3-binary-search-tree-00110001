CSUF CPSC 131, Fall 2016
Project 3
"Binary Search Tree" (using the data structures learned in CPSC 131)

Group members:

David Feinzimer dfeinzimer@csu.fullerton.edu

## You need to answer the following question. 
Two binary search trees contains exactly the same number of entries of student information but in different orders. Do they give the same performance in terms of key searching or firstname searching? if not, why? use the data you obtain from your code to explain your answer. 

## Answer
No two different binary trees that were constructed from the same information but of differing order will not have the same performance as eachother. This is due to the fact that binary trees take shape from the way in which they were created. In the case of alphabetical characters if many strings beginning with 'A' are entered first, the beginnings of a search of a tree of this type will have to wade through the many leveles of strings beginning with 'A's to advance. The binary tree is hereby unbalanced. If a binary tree is constructed from an unsorted list of strings however, strings beginning with letters in the second half of the alphabet may be placed much closer to the top of the tree, resulting in much better performance. Take for example the results of this project, when searching for key 'Steven' in the tree built from a sorted list, it took 147 steps where as it only took 9 steps in the tree constructed from an unsorted list. When searching for key 'David' in the tree built from a sorted list, it took 45 steps where as it only took 11 steps in the tree constructed from an unsorted list.
