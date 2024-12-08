---
tags: R ChatGPT
---

# Nightly Practice ChatGPT
Stephen Garcia (wqr974)
2024-11-29

# Night 1 Practice

## Load Libraries

``` r
# Basic math
2 + 3
```

    [1] 5

``` r
10 - 4
```

    [1] 6

``` r
5 * 6
```

    [1] 30

``` r
8 / 2
```

    [1] 4

``` r
# Assigning values to variables
x <- 10
y <- 5
z <- x + y
z
```

    [1] 15

``` r
# printing values
print(z)
```

    [1] 15

# Night 2 Practice

``` r
# Vectors
numbers <- c(10, 20, 30, 40, 50)
numbers
```

    [1] 10 20 30 40 50

``` r
# Create a Character Vector
fruits <- c("Apple", "Banana", "Orange", "Grapes")
fruits
```

    [1] "Apple"  "Banana" "Orange" "Grapes"

``` r
# Create a Logical Vector
logical_vals <- c(TRUE, FALSE, TRUE, TRUE)
logical_vals
```

    [1]  TRUE FALSE  TRUE  TRUE

``` r
# Arithmetic Operations on Vectors
numbers + 10
```

    [1] 20 30 40 50 60

``` r
numbers * 2
```

    [1]  20  40  60  80 100

``` r
# Combining Vectors
more_numbers <- c(60, 70, 80, 90, 100)
all_numbers <- c(numbers, more_numbers)
all_numbers
```

     [1]  10  20  30  40  50  60  70  80  90 100

``` r
# Accessing Elements of a Vector
numbers[1]
```

    [1] 10

``` r
numbers[1:3]
```

    [1] 10 20 30

``` r
numbers[-1]
```

    [1] 20 30 40 50

``` r
numbers[length(numbers)]
```

    [1] 50

``` r
# Exercise
# 1. Create a vector of your favorite numbers and perform arithmetic operations on it.
fav_numbers <- c(3, 10, 23, 71, 82, 88)
fav_numbers * 2
```

    [1]   6  20  46 142 164 176

``` r
# 2. Create a vector of your favorite hobbies and access the second element of the vector.
fav_hobbies <- c("Gaming", "Coding", "Reading")
fav_hobbies[2]
```

    [1] "Coding"

``` r
# 3. Generate a sequence of numbers from 1 to 50, stepping by 5.
seq(1, 50, by = 5)
```

     [1]  1  6 11 16 21 26 31 36 41 46

``` r
# 4. Add 10 to the second and fourth elements of fav_numbers.
fav_numbers[c(2, 4)] + 10
```

    [1] 20 81

``` r
# 5. Double the values of all elements greater than 20 in fav_numbers.
fav_numbers[fav_numbers > 20] * 2
```

    [1]  46 142 164 176

``` r
# 6. Subtract 5 from all elements between 10 and 30 in fav_numbers.
fav_numbers[fav_numbers >= 10 & fav_numbers <= 30] - 5
```

    [1]  5 18
