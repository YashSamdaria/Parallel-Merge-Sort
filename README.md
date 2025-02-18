# Parallel Merge Sort 🧵⚡

A multithreaded implementation of Merge Sort in C++ using `std::thread` for parallel execution.

## Features 🚀
- ✅ Uses `std::thread` for parallel sorting
- ✅ Switches to `std::sort` for smaller subarrays
- ✅ Efficient in-place merging

## How It Works 🛠
- Recursively divides the array into two halves
- Uses two threads to sort each half concurrently
- Merges the sorted halves into a single array

## Installation & Usage 📌
```sh
git clone https://github.com/yourusername/Parallel-Merge-Sort.git
g++ -std=c++11 -pthread parallelMergeSort.cpp -o parallelMergeSort
./parallelMergeSort
