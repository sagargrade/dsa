## Analysis of algorithm

- Asymptotic Analysis - Measure of order of growth of function based on input size 
    > Mathematical Operation or Comparison Operation takes constant time
    
    > Loops take time proportional to number of iterations

- Order of growth - Function that describes the rate at which time taken by algorithm grows as function of input size
    - Constant time - O(1)
    - Logarithmic time - O(log n) - Binary Search
    - Linear time - O(n) - Linear Search 
    - Linearithmic time - O(n log n) - Heap Sort, Merge Sort
    - Quadratic time - O(n^2) - Bubble Sort, Selection Sort, Insertion Sort, Bucket Sort
    - Cubic time - O(n^3)
    - Exponential time - O(2^n) - Tower of Hanoi
    - Factorial time - O(n!) - Traveling Salesman Problem

- Time Complexity - Time taken by algorithm to run as function of input size
- Space Complexity - Space taken by algorithm to run as function of input size
  - Ideal algorithm - O(1) - Linear Search, Binary Search,
    Bubble Sort, Selection Sort, Insertion Sort, Heap Sort, Shell Sort.
  - Logarithmic algorithm - O(log n) - Merge Sort.
  - Linear algorithm - O(n) - Quick Sort.
  - Sub-linear algorithm - O(n+k) - Radix Sort.

- We can have three cases to analyze an algorithm:

  > Worst Case - In the worst case analysis, we calculate upper bound on running time of an algorithm.

  > Average Case - In average case analysis, we take all possible inputs and calculate computing time for all of the inputs. Sum all the calculated values and divide the sum by total number of inputs.

  > Best Case - In the best case analysis, we calculate lower bound on running time of an algorithm.

- Asymptotic Notations
  - Theta notation - The theta notation bounds a function from above and below, so it defines exact asymptotic behavior.
  - Big O Notation - The Big O notation defines an upper bound of an algorithm, it bounds a function only from above.
  - Omega Notation - The omega notation defines a lower bound of an algorithm, it bounds a function only from below.
