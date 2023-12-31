# SORTING
NAME : TARIQ AKHLAK
A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

Selection Sort
In selection sorting technique, the smallest element is fetched by comparing itself with the rest of the elements and sorted at the array's first position. The complete array is divided into two halves, the sorted subarray on the left and the unsorted subarray on the right. Once the first element is sorted, the search for the second minimum element begins from the rest of the array and is positioned at second place.

image

Similarly, all the elements are positioned on the sorted side of the subarray one after the other, and the complete array becomes a sorted array.

Insertion Sort
In this sorting technique, the elements are sorted by comparing the elements with their previous elements. It starts by comparing the second element with the first element. If the second element is smaller than the first, then we will swap it.

image

After that, we will compare the third element with all the elements that are before it. Similarly, it goes for the fourth element and so on. Once all the comparisons are made, the elements become sorted.

Bubble Sort
Bubble sort is one of the most straightforward sorting algorithms. In this sorting technique, we begin by comparing the first two elements of the array and checking if the first element is greater than the second element; if it is, we will swap those elements and move forward to the next element.

image

If the first element is not greater than the second, then we don’t need to swap it. And this process will keep on repeating till the end of the array.

image

Experiment_1:
Aim: Algorithm for the provided C++ program that sorts an array using Selection Sort

Algorithm:

1.Start

2.Declare an integer variable n to store the number of elements in the array.

Output "Enter the number of elements in the array: " to prompt the user for input.

Read the value of n from the user.

3.Declare an integer array arr of size n to store the elements of the array.

Output "Enter n elements of the array: " to prompt the user for the array elements.

Use a loop to read and store the n elements in the arr array.

Create a function to perform selection sort
5.Use a loop to display the elements of the sorted arr array.

6.Stop

OUTPUT
Exp22_1

Experiment_2:
Aim: Algorithm for the provided C++ program that sorts an array using Insertion Sort

Algorithm:

1.Start

2.Declare an integer variable n to store the number of elements in the array.

Output "Enter the number of elements in the array: " to prompt the user for input.

Read the value of n from the user.

3.Declare an integer array arr of size n to store the elements of the array.

Output "Enter n elements of the array: " to prompt the user for the array elements.

Use a loop to read and store the n elements in the arr array.

Create a function to perform insertion sort
5.Use a loop to display the elements of the sorted arr array.

6.Stop

OUTPUT
exp22_2

Experiment_3:
Aim: Algorithm for the provided C++ program that sorts an array using Bubble Sort

Algorithm:

1.Start

2.Declare an integer variable n to store the number of elements in the array.

Output "Enter the number of elements in the array: " to prompt the user for input.

Read the value of n from the user.

3.Declare an integer array arr of size n to store the elements of the array.

Output "Enter n elements of the array: " to prompt the user for the array elements.

Use a loop to read and store the n elements in the arr array.

Create a function to perform bubble sort
5.Use a loop to display the elements of the sorted array.

6.Stop

OUTPUT
exp22_3
