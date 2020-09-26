# Data-Science-from-scratch
Data Science algorithms, python

# lbs_lab.ipynb
Libraries: numpy, scipy, pandas
1. Implement function which creates a  𝑛𝑥𝑚  matrix and fills it with a checkerboard pattern
2. Implement function which solves system of linear equations
3. Implement function which multiplies 2 matrixes and returns the max value of each column of the resulting matrix
4. Implement function add_mean_and_calc_det(matrix), which adds to each element in the matrix row the mean of this row and returns the determinant of the resulting matrix
5. Implement function nearest_to_scalar(matrix, n), which returns the closest to n number in the matrix
6. Implement function svd_ranks(Z) which performs SVD of given matrix and returns a list of ranks of matrices U, S and V
6. Implement function svd_ranks(Z) which performs SVD of given matrix and returns a list of ranks of matrices U, S and V
7. Implement function to sort a given complex array using the real part first, then the imaginary part
8. Implement a function that computes the Mandelbrot fractal
9. Consider the following dictionary "data" and list "labels"
9.1 Implement function repl_nan(data, labels) which creates a dataframe from dictionary "data" with indexes from the list "labels", replaces the values "nan" in the age field by the mean age depending on the animal's type and returns a new dataframe
9.2 Implement function weight_to_type(data, labels) which creates a dataframe from dictionary "data" with indexes from the list "labels", calculates average weight of each animal type and returns dictionary with these values, where keys are animal types and values are animal weights
9.3 Implement function kittens(data, labels) which creates a dataframe from dictionary "data" with indexes from the list "labels" and returns dataframe with data about cats with age < 3
9.4 Implement function sorted_df(data, labels) which creates a dataframe from dictionary "data" with indexes from the list "labels" which returns dataframe sorted firstly by age in a decreasing order, secondly, for the number of weight in ascending order
10. Markov Chain

# Python Lab.ipynb
Python and algorithms
Сomplete this part of test without using any libs (your code must not contain keyword 'import')
1. Implement function str_to_dict(some_str) which returnes dictionary, where keys are string characters, and values are their quantity in the string
2. Implement function sec_smallest(numbers) which returns second smallest item in the list, without using the built-in sorting methods (your code mustn't contain such words as 'sort', 'sorted')
3. Implement function prime_nums(n) that returns list of numbers which are simple and < n
4. Implement function max_sum_index(tuples), which returnes index of tuple in the list with maximum sum of elements
5. Implement function gcd(x, y), which returns the greatest common divisor of n and m
6. Implement recursive sum of the list
7. Implement decorator which returns function signature and it's return value
8. Implement class Conv, that contains method to_roman(self, n), which converts decimal numbers to Roman numerals
9. Implement class CombinationsList, that contains method get_combinations(self, my_list), which returns all combinations of elements of given list, including empty element and in order, law of which can be discrovered from the expected output
10. Create base class Rocket and it's subclass Shuttle. The parent class contains methods getMission(), addMission() and getName(). The subclass Shuttle contains method getDescription(). Notice that we have not defined getName(), getMission(), addMission() in the Shuttle class but we are still able to access them, because the class Shuttle inherits them from the Rocket class. Use super() method to have ability to call those methods of the base class

