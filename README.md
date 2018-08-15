# generics_
Generic implementations of C++ STL vector, stack, queue, ...

# Challenges faced
1. Temporary objects cannot be initialized with non-const reference
2. What to return from overloaded `[]` operator, so that it does not result in a Rvalue
3. What does it mean to return a reference( related to 2)
4. Operator overloading chaining, in equality operator, used for 
   operations like `a=b=c`.	

# Useful Links
[What does it mean to return a reference
and when should we do it](https://stackoverflow.com/questions/752658/is-the-practice-of-returning-a-c-reference-variable-evil)