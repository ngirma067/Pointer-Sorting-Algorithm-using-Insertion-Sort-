# Pointer-Sorting-Algorithm-using-Insertion-Sort-
## Student Information
- **Name**: Natnael Girma
- **Student ID**: 0425/23
- **Course**: DSA
## Time Complexity:
- **Best Case**: O(n) when the array is already sorted. In this case, only the outer loop runs, and the inner loop doesn't perform any shifts.
- **Worst Case**: O(n²) when the array is sorted in reverse order. Each element will need to be compared with all previously sorted elements.
- **Average Case**: O(n²) for random data, because every element might require shifting.
##Summary:
- Insertion Sort works by building up a sorted section of the array one element at a time.
- The use of pointers here (*ptr = &arr[i]) demonstrates how pointers can be used to access and modify elements in the array.
- This implementation works well for small to moderately sized datasets but is inefficient for large datasets due to its O(n²) time complexity.
