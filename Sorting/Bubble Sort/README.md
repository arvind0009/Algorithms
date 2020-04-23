# Bubble Sort

Bubble Sort is a sorting algorithm which continuously swaps adjacent elements of a list till a completely sorted list is obtained.

## Pseudo code:
BUBBLESORT(A)
1   for i ← 1 to length[A]
2     do for j ← length[A] downto i + 1
3       do if A[j] < A[j - 1]
4         then exchange A[j] ↔ A[j - 1]

## Time complexity and space complexity
Worst case time complexity: O(n^2)
Average case time complexity: O(n^2)
Best case time complexity: O(n)

Worst case and average case time complexity is O(n^2) as a result of the two for loops and the list is unsorted.
Best case time complexity occcurs when the list is already sorted.

The space complexity is O(1)

## Optimized bubble sort
If in an iteration no swapping occurs, this means that the list has been sorted, and thus the program stops.

## Comparison of time for the different bubble sorts
1> Number of elements: 1000 (List is unsorted)
  
  a) Bubble Sort: 2737100 ns
  
  b) Optimized Bubble Sort: 800 ns
  
  
2> Number of elements: 1000 (List is sorted)
  
  a) Bubble Sort: 1207300 ns
  
  b) Optimized Bubble Sort: 400 ns
  
  
3> Number of elements: 100 (List is unsorted)
  
  a) Bubble Sort: 38300 ns
  
  b) Optimized Bubble Sort: 1000 ns
  
  
2> Number of elements: 100 (List is sorted)
  
  a) Bubble Sort: 15700 ns
  
  b) Optimized Bubble Sort: 400 ns
  
## Conclusion: 
It can be seen that optimized bubble sort is much more time efficient in comparison with normal bubble sort.