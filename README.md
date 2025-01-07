# Swift filter method not working as intended

This repository contains a simple Swift code snippet that demonstrates a common error in Swift where the filter method is used on an array. In this specific instance, the filter method is used to filter out the even numbers from an array of numbers. However, the filter method is not used correctly and will not filter out the even numbers as intended.

The bug is that the filter method is not used correctly. The correct way to use the filter method is to pass in a closure that takes an element of the array as input and returns a boolean value indicating whether the element should be included in the filtered array. In this case, the closure should return true if the element is an even number and false otherwise.

The solution is to correct the closure that is passed into the filter method. The correct closure should be `$0 % 2 == 0`, which returns true if the element is an even number and false otherwise.