# Sorting Algorithms & Big O

## Overview

This project aims to implement various sorting algorithms in C and understand their time complexities using Big O notation. The project is designed to be completed in teams of two, with each team pair programming for at least the mandatory part. The tasks include implementing sorting algorithms such as Bubble sort, Insertion sort, Selection sort, Quick sort, Shell sort (using the Knuth sequence), and Cocktail shaker sort.

## Background Context

The project focuses on understanding sorting algorithms and their efficiency through Big O notation. Resources provided include readings on sorting algorithms, Big O notation, and animations illustrating sorting techniques. The learning objectives include understanding different sorting algorithms, evaluating time complexity using Big O notation, selecting appropriate sorting algorithms for given inputs, and understanding stable sorting algorithms.

## Requirements

- Programming Language: C
- Editors: vi, vim, emacs
- Compiler: gcc on Ubuntu 20.04 LTS
- Code style: Follow Betty style guidelines
- No global variables allowed
- Limit of 5 functions per file
- No use of standard library functions unless explicitly allowed
- Header file (`sort.h`) should contain function prototypes and be include guarded
- Implement print_array and print_list functions for testing
- Use a doubly linked list data structure for list operations
- Each sorting algorithm should be tested with appropriate test cases

## Tasks

### 0. Bubble sort

- Implement Bubble sort algorithm in C
- Prototype: `void bubble_sort(int *array, size_t size);`
- Print array after each swap
- Calculate time complexity for best, average, and worst cases in `0-O`

### 1. Insertion sort

- Implement Insertion sort algorithm for doubly linked lists
- Prototype: `void insertion_sort_list(listint_t **list);`
- Print list after each swap
- Calculate time complexity for best, average, and worst cases in `1-O`

### 2. Selection sort

- Implement Selection sort algorithm in C
- Prototype: `void selection_sort(int *array, size_t size);`
- Print array after each swap
- Calculate time complexity for best, average, and worst cases in `2-O`

### 3. Quick sort

- Implement Quick sort algorithm in C using Lomuto partition scheme
- Prototype: `void quick_sort(int *array, size_t size);`
- Print array after each swap
- Calculate time complexity for best, average, and worst cases in `3-O`

### 4. Shell sort - Knuth Sequence

- Implement Shell sort algorithm using the Knuth sequence
- Prototype: `void shell_sort(int *array, size_t size);`
- Print array after reducing interval
- No need to calculate Big O notation

### 5. Cocktail shaker sort

- Implement Cocktail shaker sort algorithm for doubly linked lists
- Prototype: `void cocktail_sort_list(listint_t **list);`
- Print list after each swap
- Calculate time complexity for best, average, and worst cases in `101-O`

## Testing

Test each sorting algorithm with appropriate test cases to ensure correctness and efficiency.

## Copyright

This project is part of a learning experience. Avoid plagiarism and ensure original solutions to meet learning objectives.
