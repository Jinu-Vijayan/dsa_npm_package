# Array Algorithms Library

This is a JavaScript library containing various array manipulation algorithms implemented as functions. These algorithms are useful for sorting, searching, and manipulating arrays efficiently.

## Installation

You can install this library via npm:

```bash
npm install @jivij/dsa_package
```

## Usage

```javaScript
// Import the library
const arrayAlgorithms = require('array-algorithms-library');

// Example usage of functions
const arr = [3, 1, 4, 1, 5, 9, 2, 6, 5];
console.log(arrayAlgorithms.bubbleSort(arr)); // [1, 1, 2, 3, 4, 5, 5, 6, 9]
```

## Functions

### bubbleSort(arr)
Sorts an array in ascending order using the bubble sort algorithm.

### selectionSort(arr)
Sorts an array in ascending order using the selection sort algorithm.

### insertionSort(arr)
Sorts an array in ascending order using the insertion sort algorithm.

### kthSmallestElem(arr, k)
Finds the kth smallest element in an array.

### maxSumSubArr(arr)
Finds the maximum sum of a contiguous subarray within the given array.

### maxProduct(arr)
Finds the maximum product of a contiguous subarray within the given array.

### reverseArr(arr)
Reverses the elements of the given array.

### interleavingArray(arr)
Interleaves the elements of the given array.

### sortZeroOneTwo(arr)
Sorts an array containing only 0s, 1s, and 2s in ascending order.

### duplicateZero(arr)
Duplicates each occurrence of 0 in the array.