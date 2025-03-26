# Pointer-Sorting-Algorithm-using-Insertion-Sort-
## Student Information
- **Name**: Natnael Girma
- **Student ID**: 0425/23
- **Course**: DSA
## Algorithm
- Function Definition:
The insertionSort function takes an array (arr[]) and its size (n) as arguments.
It iterates through the array starting from the second element (index 1).
-Key Element:
For each element (arr[i]), it is compared to the elements before it.
This element (key) is temporarily stored, and a pointer (ptr) is created to refer to it
- Shifting Larger Elements:
The algorithm shifts elements that are larger than the key element to the right. This "shifting" happens in the inner while loop: while (j >= 0 && arr[j] > key).
- Placing the Key Element:
Once the correct position is found for the key element, it is inserted in the correct position, and the next element is processed.
- Helper Function pr:
The pr function is used to print the array before and after sorting.
## Time Complexity:

- **Best Case**: O(n) when the array is already sorted. In this case, only the outer loop runs, and the inner loop doesn't perform any shifts.
- **Worst Case**: O(n²) when the array is sorted in reverse order. Each element will need to be compared with all previously sorted elements.
- **Average Case**: O(n²) for random data, because every element might require shifting.
  
## Summary:

- Insertion Sort works by building up a sorted section of the array one element at a time.
- The use of pointers here (*ptr = &arr[i]) demonstrates how pointers can be used to access and modify elements in the array.
- This implementation works well for small to moderately sized datasets but is inefficient for large datasets due to its O(n²) time complexity.
