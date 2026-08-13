# pract1-DAA-1 
SUMMARY
1.Bubble Sort
Repeatedly compares adjacent elements and swaps them if they are in the wrong order.
Best case: O(n)
Average/Worst case: O(n²)
Space: O(1)
2.Selection Sort
Finds the smallest element from the unsorted portion and places it at the correct position.
Best/Average/Worst case: O(n²)
Space: O(1)
3.Insertion Sort
Builds the sorted array one element at a time by inserting each element into its proper position.
Best case: O(n)
Average/Worst case: O(n²)
Space: O(1)
4.Merge Sort
Divides the array into smaller parts, recursively sorts them, and merges the sorted parts.
Best/Average/Worst case: O(n log n)
Space: O(n)
5.Quick Sort
Selects a pivot and divides the elements into smaller and larger groups, then recursively sorts them.
Best/Average case: O(n log n)
Worst case: O(n²)
Space: O(n) for this particular implementation.

Each algorithm takes numbers from the user, sorts them, displays the sorted array, and measures execution time using Python's
CONCLUSION OF PRACT-1
The notebook demonstrates how different sorting algorithms perform and highlights the importance of time and space complexity. Bubble Sort, Selection Sort, and Insertion Sort are simple and easy to understand but become inefficient for large datasets because their average or worst-case performance is O(n²). Merge Sort provides consistently good performance of O(n log n), making it suitable for large datasets. Quick Sort also generally performs very efficiently with O(n log n) average performance, although its worst case can reach O(n²).

Overall, Merge Sort and Quick Sort are more suitable for large inputs, while Insertion Sort can be effective for small or nearly sorted arrays. The execution-time measurements in the notebook can be used to experimentally observe these theoretical differences.
