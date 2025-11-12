# Sorting Algorithm Visualizer

A dynamic, interactive web application that visualizes popular sorting algorithms in real-time. Watch how different sorting algorithms work by seeing the step-by-step process of sorting an array with beautiful animations and real-time complexity analysis.

## 🚀 Features

- **Interactive Visualization**: Watch sorting algorithms work in real-time with smooth animations
- **Multiple Algorithms**: Supports 6 different sorting algorithms
- **Customizable Array Size**: Generate arrays with 20-150 elements
- **Variable Speed Control**: Adjust sorting speed from slow to fast
- **Complexity Analysis**: Real-time display of time and space complexity
- **Responsive Design**: Works on desktop and mobile devices
- **Educational Tool**: Perfect for learning and teaching sorting algorithms

## 🔢 Supported Algorithms

| Algorithm | Best Case | Average Case | Worst Case | Space Complexity |
|-----------|-----------|--------------|------------|------------------|
| **Bubble Sort** | O(n) | O(n²) | O(n²) | O(1) |
| **Selection Sort** | O(n²) | O(n²) | O(n²) | O(1) |
| **Insertion Sort** | O(n) | O(n²) | O(n²) | O(1) |
| **Merge Sort** | O(n log n) | O(n log n) | O(n log n) | O(n) |
| **Quick Sort** | O(n log n) | O(n log n) | O(n²) | O(log n) |
| **Heap Sort** | O(n log n) | O(n log n) | O(n log n) | O(1) |

## 🎮 How to Use

1. **Generate Array**: Click "Generate New Array" to create a new random array
2. **Adjust Settings**:
   - Use the "Array Size" slider to change the number of elements (20-150)
   - Use the "Sorting Speed" slider to control animation speed (1-5)
3. **Choose Algorithm**: Click on any algorithm button to start visualization
4. **Watch Magic**: Observe the sorting process with color-coded animations:
   - **Blue**: Unsorted elements
   - **Red**: Elements being compared
   - **Green**: Sorted elements
   - **Yellow**: Pivot elements (Quick Sort)

## 📁 Project Structure

```
Sorting-Algorithm-Visualizer/
├── index.html              # Main HTML file
├── style.css              # Styling and layout
├── README.md              # Project documentation
└── scripts/
    ├── main.js           # Core functionality and UI controls
    ├── visualizations.js # Animation and visualization logic
    ├── bubble_sort.js    # Bubble sort implementation
    ├── selection_sort.js # Selection sort implementation
    ├── insertion_sort.js # Insertion sort implementation
    ├── merge_sort.js     # Merge sort implementation
    ├── quick_sort.js     # Quick sort implementation
    └── heap_sort.js      # Heap sort implementation
```

## 🎨 Color Coding

- **🔵 Blue**: Default/unsorted elements and elements returned to normal state
- **🔴 Red**: Elements are being swapped during the sorting process
- **🟢 Green**: Elements in their final sorted position
- **🟡 Yellow**: Element is currently being compared or is selected as the pivot

⭐ **Star this repository if you found it helpful!** ⭐

*Made with ❤️ for the developer and education community by Kavya Sharma*
