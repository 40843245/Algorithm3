# Edit Distance Problem
## Introduction
It is string metric. 

i.e. Given two string, a counting the minimum number of operation required to transform one string to another.

Available operations are 

1. insertion
2. deletion
3. substitution

          1. insertion : 
          insert a letter in one string.
          Such as 
          abc -> ab1c
          2. deletion :
          delete a letter from one string.
          Such as 
          abc -> ac
          3. substitution :
          Substitute a letter with one other letter in one string.
          such as 
          abc -> a1c
          
## Solution or Algorithm
### Brute-Force Algorithm
Solve it by viewing all possibles.

### Dynamic Programming
Store it into variable then use it once it is needed. The one do NOT have to calculate it again.

### Fuzzy Search Algorithm

## Applications
It is commonly used in spell checking.


## Ref
For Fuzzy Search Algorithm, visit the website.

https://stackoverflow.com/questions/32337135/fuzzy-search-algorithm-approximate-string-matching-algorithm

What is difference between fuzzy search and wildcard search?

https://en.wikipedia.org/wiki/Approximate_string_matching

https://www.techtarget.com/whatis/definition/fuzzy-search

https://learn.microsoft.com/en-us/azure/search/search-query-fuzzy
