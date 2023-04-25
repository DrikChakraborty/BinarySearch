 Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 
 When to use Binary Search?
When searching a large dataset as it has a time complexity of O(log n), which means that it is much faster than linear search.
When the dataset is sorted.
When data is stored in contiguous memory.
Data does not have a complex structure or relationships.
How to Implement Binary Search?
The basic steps to perform Binary Search are:

Set the low index to the first element of the array and the high index to the last element.
Set the middle index to the average of the low and high indices.
If the element at the middle index is the target element, return the middle index.
Otherwise, based on the value of the key to be found and the value of the middle element, decide the next search space.
If the target is less than the element at the middle index, set the high index to middle index – 1.
If the target is greater than the element at the middle index, set the low index to middle index + 1.
Perform step 2 repeatedly until the target element is found or the search space is exhausted.
The Binary Search Algorithm can be implemented in the following two ways
Iterative Binary Search Algorithm
Recursive Binary Search Algorithm
![image](https://user-images.githubusercontent.com/125429673/234377663-d9f5886b-0355-47a7-a0bf-4d6adcaf573c.png)
