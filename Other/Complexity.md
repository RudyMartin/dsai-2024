| **Name/Description** | **Math Example** |
|----------------------|------------------|
| **O(1) - Constant Time** | **Accessing an Array Index**: Given `ARR = [3, 8, 5, 12]`, accessing `ARR[2]` simply returns `5`. |
| **O(n) - Linear Time** | **Traversing an Array**: Sum all elements in an array `ARR = [2, 4, 6, 8]`.<br>Equation: \( \text{Sum} = 2 + 4 + 6 + 8 = 20 \)<br>Solution: `20` |
| **O(log n) - Logarithmic Time** | **Binary Search**: Find `4` in the sorted array `ARR = [1, 2, 4, 7, 9]`. Start by comparing the middle element.<br>Steps:<br>1. Compare `4` to `4` (middle of the array).<br>2. Found `4` at index 2.<br>Solution: Index `2` |
| **O(n log n) - Linearithmic Time** | **Merge Sort**: Sort the array `ARR = [4, 2, 7, 1]`.<br>Steps:<br>1. Split into `[4, 2]` and `[7, 1]`.<br>2. Split further into `[4]`, `[2]`, `[7]`, `[1]`.<br>3. Merge into `[2, 4]` and `[1, 7]`.<br>4. Merge into `[1, 2, 4, 7]`.<br>Solution: `[1, 2, 4, 7]` |
| **O(n²) - Quadratic Time** | **Bubble Sort**: Sort `ARR = [4, 3, 2, 1]` by comparing each pair.<br>Steps:<br>1. Compare and swap `4` & `3`, then `4` & `2`, then `4` & `1`. Now `[3, 2, 1, 4]`.<br>2. Repeat process for remaining elements.<br>Solution: `[1, 2, 3, 4]` |
| **O(n!) - Factorial Time** | **Permutations**: Find all permutations of `ARR = [1, 2, 3]`.<br>Permutations: `[1, 2, 3]`, `[1, 3, 2]`, `[2, 1, 3]`, `[2, 3, 1]`, `[3, 1, 2]`, `[3, 2, 1]`.<br>Solution: `6` permutations |
