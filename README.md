# Sorting Visualizer

## Overview

The Sorting Visualizer is a dynamic web-based application that provides a visual representation of various sorting algorithms in action. This project aims to enhance understanding of fundamental sorting algorithms through interactive and real-time visualizations.

## Features

- **Multiple Sorting Algorithms**: Visualizes five fundamental sorting algorithms:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort

- **Real-time Visualization**: Watch as the algorithms sort randomly generated arrays step by step.

- **Adjustable Speed**: Control the speed of the visualization to better comprehend the sorting process.

- **Responsive Design**: Works seamlessly across different devices and screen sizes.

## Technologies Used

- HTML5
- CSS3
- JavaScript 

## How It Works

1. **Array Generation**: The application starts by generating a random array of integers.

2. **Algorithm Selection**: Users can choose from the five implemented sorting algorithms.

3. **Visualization**: Upon selecting an algorithm, the sorting process begins, visually representing each step of the chosen algorithm.

4. **Speed Control**: Users can adjust the speed of the visualization in real-time, allowing for faster or slower execution to suit their understanding.

## Sorting Algorithms Explained

### Bubble Sort
- Time Complexity: O(n²)
- Space Complexity: O(1)
- Description: Repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order.

### Selection Sort
- Time Complexity: O(n²)
- Space Complexity: O(1)
- Description: Divides the input list into two parts: a sorted portion and an unsorted portion. It repeatedly selects the smallest element from the unsorted portion and adds it to the sorted portion.

### Insertion Sort
- Time Complexity: O(n²)
- Space Complexity: O(1)
- Description: Builds the final sorted array one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

### Merge Sort
- Time Complexity: O(n log n)
- Space Complexity: O(n)
- Description: Divides the unsorted list into n sublists, each containing one element (a list of one element is considered sorted). Then repeatedly merges sublists to produce new sorted sublists until there is only one sublist remaining.

### Quick Sort
- Time Complexity: O(n log n) on average, O(n²) in worst case
- Space Complexity: O(log n)
- Description: Picks an element as pivot and partitions the given array around the picked pivot. The key process in quickSort is partition(). Target of partitions is to place the pivot at its correct position in the sorted array and put all smaller elements to the left of pivot, and all greater elements to the right of pivot.

## Future Enhancements

- Add more sorting algorithms (e.g., Heap Sort, Radix Sort)
- Implement sound effects to represent comparisons and swaps
- Allow users to input their own arrays
- Add a feature to compare different algorithms side by side

## Installation and Usage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/sorting-visualizer.git
   ```
2. Navigate to the project directory:
   ```
   cd sorting-visualizer
   ```
3. Open `index.html` in your preferred web browser.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.



## Contact

If you have any questions, feel free to reach out to me at [chautheabhishek@gmail.com](mailto:your.email@example.com).

---

Happy Sorting!
