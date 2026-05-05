# Sorting Algorithms & Big O

## Description

This project implements various sorting algorithms in C, along with their time complexity analysis using Big O notation.

## Files

| File | Description |
|------|-------------|
| `0-bubble_sort.c` | Bubble sort on an array of integers |
| `0-O` | Big O notations for Bubble sort |
| `1-insertion_sort_list.c` | Insertion sort on a doubly linked list |
| `1-O` | Big O notations for Insertion sort |
| `2-selection_sort.c` | Selection sort on an array of integers |
| `2-O` | Big O notations for Selection sort |
| `3-quick_sort.c` | Quick sort on an array of integers (Lomuto partition) |
| `3-O` | Big O notations for Quick sort |

## Sorting Algorithms

### 0. Bubble Sort
Sorts an array by repeatedly swapping adjacent elements if they are in the wrong order.

- **Prototype:** `void bubble_sort(int *array, size_t size);`
- **Prints** the array after each swap.

| Case | Complexity |
|------|------------|
| Best | O(n) |
| Average | O(n²) |
| Worst | O(n²) |

---

### 1. Insertion Sort
Sorts a doubly linked list by shifting nodes into their correct position.

- **Prototype:** `void insertion_sort_list(listint_t **list);`
- Swaps **nodes**, not values.
- **Prints** the list after each swap.

| Case | Complexity |
|------|------------|
| Best | O(n) |
| Average | O(n²) |
| Worst | O(n²) |

---

### 2. Selection Sort
Finds the minimum element in the unsorted part and swaps it to its correct position.

- **Prototype:** `void selection_sort(int *array, size_t size);`
- **Prints** the array after each swap.

| Case | Complexity |
|------|------------|
| Best | O(n²) |
| Average | O(n²) |
| Worst | O(n²) |

---

### 3. Quick Sort (Lomuto Partition)
Sorts an array using recursion and the Lomuto partition scheme, always picking the **last element** as pivot.

- **Prototype:** `void quick_sort(int *array, size_t size);`
- **Prints** the array after each swap.

| Case | Complexity |
|------|------------|
| Best | O(n log n) |
| Average | O(n log n) |
| Worst | O(n²) |

---

## Requirements

- Language: **C**
- Compiler: `gcc -Wall -Wextra -Werror -pedantic`
- OS: Ubuntu 20.04 LTS
- Style: Betty coding style

## Authors

**Sarah Alkhubaizy** — [SarahAlkhubaizy](https://github.com/SarahAlkhubaizy)

**Abdulmalik AlAqeel** — [AbdulmalikAlAqeel](https://github.com/AbdulmalikAlAqeel)
