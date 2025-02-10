# Dart Reduce() Error on Empty List

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list.  The `reduce()` method requires at least one element in the list; otherwise, it throws a `StateError`.  The solution provides a simple way to handle this scenario gracefully.

## Bug

The `bug.dart` file shows the error: an empty list passed to `reduce()` throws a `StateError`. 

## Solution

The `bugSolution.dart` file provides a solution by adding a check to ensure the list isn't empty before calling `reduce()`.  This prevents the error and handles the case of an empty list appropriately.

This example highlights the importance of defensive programming and checking for edge cases when working with collection methods.