# SORTING-ALGORITHMS


#  Aim: To implement and understand various sorting algorithms using C++, analyze their time and space complexities, and compare their performance based on different input sizes.

# Software Used:

   - IDE: Code::Blocks / Visual Studio Code / Dev C++
- Compiler: GNU GCC Compiler
   - Operating System: Windows/Linux/MacOS
  -  Language: C++

  # Objectives:

 1.   To understand the working of popular sorting algorithms such as:
    -    Bubble Sort
     -   Selection Sort
     -   Insertion Sort
      -  Merge Sort
      -  Quick Sort
 -  2. To implement these algorithms in C++.
  - 3. To analyze and compare their time and space complexity.
  - 4. To visualize and understand flowcharts for sorting mechanisms.
  - 5. To construct tables for performance comparison.

================================================================================

  # Theory:

Sorting is the process of arranging data in a particular order (ascending or descending). Efficient sorting is crucial for optimizing the performance of other algorithms like search and merge.

Sorting algorithms can be classified based on the following:

  -Time Complexity (Best, Average, Worst Case)
  -  Space Complexity
  -  Stability (Maintaining relative order of equal elements)
  -  Method (Comparison-based or non-comparison-based)
    

     #   Algorithm: (Quick Sort - Example)

void quickSort(int arr[], int low, int high) { if (low < high) { int pivot = partition(arr, low, high); // partition index quickSort(arr, low, pivot - 1); // sort left sub-array quickSort(arr, pivot + 1, high); // sort right sub-array } }

int partition(int arr[], int low, int high) { int pivot = arr[high]; // pivot int i = (low - 1); // index of smaller element



   #     Conclusion:

Through this project, we have implemented and compared multiple sorting algorithms. We observed that:

   - Simple algorithms like Bubble, Selection, and Insertion are easy to implement but inefficient for large datasets.
   -  Merge Sort and Quick Sort are more efficient for larger datasets.
   - Quick Sort generally outperforms Merge Sort in practical applications, though its worst-case performance is worse.
   - Choice of sorting algorithm depends on factors like dataset size, the need for stability, and memory constraints.

