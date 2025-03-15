# sorting-algorithm-visualizer
Sorting Algorithms Explained
Sorting algorithms are methods used to arrange elements in a specific order, typically ascending or descending. They are crucial in computer science for optimizing search operations, organizing data, and improving efficiency in various applications.

Types of Sorting Algorithms
Sorting algorithms are broadly classified into two types:

Comparison-based Sorting – Elements are compared with each other to determine their order.
Non-comparison-based Sorting – Sorting is done using techniques like counting, hashing, or digit-based sorting.


1. Bubble Sort
Concept: Compares adjacent elements and swaps them if they are in the wrong order. Repeats until the list is sorted.
Time Complexity:
Best Case: O(n) (already sorted)
Worst & Average Case: O(n²)
Stable? ✅ Yes
Use Case: Best for small datasets or when the list is nearly sorted.


2. Heap Sort
Concept: Converts the array into a max heap (or min heap) and repeatedly extracts the largest (or smallest) element to sort the array.
Time Complexity: O(n log n) (always)
Stable? ❌ No
Use Case: When you need efficient, in-place sorting without recursion.


3. Selection Sort
Concept: Finds the minimum element in the array and swaps it with the first unsorted position.
Time Complexity: O(n²) (always)
Stable? ❌ No
Use Case: When swaps are more expensive than comparisons.


4. Insertion Sort
Concept: Takes one element at a time and places it in its correct position by shifting elements.
Time Complexity:
Best Case: O(n) (already sorted)
Worst & Average Case: O(n²)
Stable? ✅ Yes
Use Case: Best for small datasets or nearly sorted arrays.


5. Quick Sort
Concept: Picks a pivot, partitions the array so that elements smaller than the pivot are on one side and larger on the other, and recursively sorts both sides.
Time Complexity:
Best & Average Case: O(n log n)
Worst Case: O(n²) (if poorly partitioned)
Stable? ❌ No
Use Case: One of the fastest sorting algorithms for large datasets.


6. Merge Sort
Concept: Uses a divide and conquer approach to split the array into halves, sort them recursively, and merge the sorted halves.
Time Complexity: O(n log n) (always)
Stable? ✅ Yes
Use Case: Best for large datasets and linked lists.


#HOW TO RUN 
Install the libraries which are required and run and give the command:
pyhton main.py funtion_call
for example:
python main.py bubble_sort
