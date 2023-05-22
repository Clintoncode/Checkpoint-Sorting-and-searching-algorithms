# Checkpoint-Sorting-and-searching-algorithms

To implement the Insertion Sort algorithm, you can follow these instructions:

Start with the second element (index 1) of the array.
Iterate over the array from the second element to the last element (index N-1), where N is the size of the array.
For each iteration, store the current element in a temporary variable.
Compare the current element with the previous elements in the sorted sequence (elements from 0 to i-1), where i is the current iteration.
While the previous element is greater than the current element and we haven't reached the beginning of the array:
Move the previous element one position ahead in the array to make space for the current element.
Decrement the index to check the next previous element.
Insert the current element into its correct position in the sorted sequence.
Continue the iteration until all elements are sorted.
