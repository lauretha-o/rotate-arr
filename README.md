### Algorithm

Input: An integer array a and an integer d representing the number if left rotations.

Normalize Rotations: Since rotating an array by its length results in the same array, we use d = d % n
where n is the length of the array

Rotate the Array: We sliced the array into two parts and concatenate the second part followed by the first part
