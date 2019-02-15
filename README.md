# chain-comparison-operators
# Example to show how to chain comparison operators



Chaining comparison operators in Python
Checking more than two conditions is very common in Programming Languages. Let say we want to check below condition:

a < b < c
Most common syntax to do it is as follows:

if a < b and b < c :
   {...}
In Python, there is a better way to write this using Comparison operator Chaining. The chaining of operators can be written as follows:

if a < b < c :
    {.....}
According to associativity and precedence in Python, all comparison operations in Python have the same priority, which is lower than that of any arithmetic, shifting or bitwise operation. Also unlike C, expressions like a < b < c have the interpretation that is conventional in mathematics.


