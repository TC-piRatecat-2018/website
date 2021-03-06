---
title: Some common types of data
excerpt: Vectors, tibbles, and matrices oh my...
---
![pipe img]({{ site.url }}{{ site.baseurl}}/assets/images/pipe.jpg)

## Objects
R is an object oriented programming language where you assign things to objects and it is similar to python, S, etc. Objects can be vectors, arrays, matrices, data frames, a single character string, functions, etc.

## Data Structures - vectors, matrices, arrays, lists, and data frames
* Data contained as vectors, matrices, and arrays are homogeneous.
* Lists and data frames are heterogeneous.
* Indices start at 1, not 0.
* Each row is a single observation.
* Each column is a single variable of the same data type.

### Vectors
* _atomic_: logical, integer, double, character, complex, raw
* _lists_: recursive vectors (you can have a list of lists)
* _augmented vectors_: factors, dates, date-times, tibbles

### _Arrays_
Arrays are like vectors with a dimensional attribute.

### _Matrices_
Matrices are like two dimensional arrays.

### Data Frames (and Tibbles)
A data frame is a what one would commonly think of as a table (your typical spreadsheet) that consists of vectors. A tibble is a type of data frame that retains the data type (e.g. character, date, integer) for each attribute (column). Each variable within a data frame or tibble must be of equal length.

### Lists
A data frame can be a list, but a list can not always be a data frame. Lists can be composed of a list of lists, or a list of data frames, where variables and data frames do not need to be of equal length.
