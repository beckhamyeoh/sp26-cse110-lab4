The bug is that 2 and 3 were coerced into becoming strings, that is why the result was a concatenation of 2 and 3 which gave us 23. 

The fix would be to explicitly change num1 and num2 into numbers
