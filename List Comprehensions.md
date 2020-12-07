## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# [] list comprehension

## Description

Returns a list based on existing iterables.

## Syntax

> [expression(variable) for variable in input_set [predicate][, …]]

* expression 
    Optional. An output expression producing members of the new set from members of the input set that satisfy the predicate expression.
* variable 
    Required. Variable representing members of an input set.
* input_set 
    Required. Represents the input set.
* predicate 
    Optional. Expression acting as a filter on members of the input set.
[, …]]
    Optional. Another nested comprehension.

## Return Value
list

## Time Complexity
TODO

## Remarks

A list comprehension follows the form of the mathematical set-builder notation (set comprehension) as distinct from the use of map() and filter() functions.

Consider the following example:
```
 l = [2 * n for n in (0, 1, 2) if n > 0]
 l
[2, 4]
```
This can be read as:

l is the list of all numbers 2 times n where n is an item in the (0, 1, 2) tuple, for which tuple element is greater than zero.

## Example 1

``` 
[n for n in [1, 2, 3]]
[1, 2, 3]
 [n * 2 for n in [1, 2, 3]]
[2, 4, 6]
 [n**2 for n in range(10)]
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```


![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/01/Python-List-Comprehension.jpg)
