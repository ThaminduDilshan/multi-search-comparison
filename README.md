# multi-search-comparison

### Task
Implement binary search and randomized search algorithms, and measure the average time taken to perform 1000 searches in a sorted array. Searching should be executed for three cases where array size is 10^4, 10^5 and 10^6.

### Constraints
* Array should be sorted.
* Each search should be for a different element within the 1000 searches.
* In the search list, 200 elements should not present in the original array. Rest 800 elements should spread roughly evenly in the original array.
* Both the binary search and randomized search algorithms should be recursive.

### How to Run
Execute the command `python search_algo.py`

### Output
* `results.txt`: Average elapsed time for each test case (All terminal logs will be redirected to this file)
* `plot_for_n_<num>.png` images: Distribution of the number list and the search list elements
> Plots are generated to verify the even distribution of the search elements within the original array
