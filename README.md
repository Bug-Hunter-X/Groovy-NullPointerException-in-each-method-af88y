# Groovy NullPointerException in `each` method

This example demonstrates a common error in Groovy when using the `each` method with a potentially null list.  The `each` method doesn't handle null input gracefully, resulting in a `NullPointerException`.

## Bug Description

The `myMethod` function iterates over a list of strings using the `each` method. However, if the input list is `null`, a `NullPointerException` is thrown because the `each` method tries to invoke methods on a null object. 

## Solution

The provided solution demonstrates how to handle this situation by first checking if the list is null before iterating.

