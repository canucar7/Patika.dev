

Request:

1. [22,27,16,2,18,6] -> Insertion Sort
 
  a- Show the steps of sorting the array above
  b- Write Big-O notation.
  c- Write three cases which are average case, worst case and best case.
  d- Which case is correct for number 18 after arrey sorted?

2.
Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.


Answer:

1.
  a- [22,27,16,2,18,6], 
   [2,27,16,22,18,6], 
   [2,6,16,22,18,27], 
   [2,6,16,18,22,27]
   
  b- O(n^2)

  c- 
   Average case: The number we are looking for is in the middle (16,18).

   Worst case: The number we are looking for is at the end (27).

   Best case: The number we are looking for is at the beginning (2).
   
  d- Average Case
  
2.  [7,3,5,8,2,9,4,15,6], 
  [2,3,5,8,7,9,4,15,6], 
  [2,3,4,8,7,9,5,15,6], 
  [2,3,4,5,7,9,8,15,6], 
  [2,3,4,5,6,9,8,15,7]
  

