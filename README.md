# ActionScript `removeChild()` Loop Bug

This repository demonstrates a common ActionScript bug involving the incorrect use of the `removeChild()` method within a loop iterating over an array of display objects.

The `bug.as` file contains the buggy code, which fails to correctly remove all intended display objects from a parent container. The `bugSolution.as` file provides a corrected version that demonstrates the proper way to handle this situation.

## Problem

Removing an element from an array while iterating over it using a for loop often leads to incorrect index referencing. This is because removing an element shifts the indices of the subsequent elements, causing the loop to skip or incorrectly remove elements.