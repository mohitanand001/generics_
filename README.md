# generics_
Generic implementations of C++ STL vector, stack, queue, ...

# Challenges faced
1. Temporary objects cannot be initialized with non-const reference
2. What to return from overloaded `[]` operator, so that it does not result in a Rvalue
3. What does it mean to return a reference( related to 2).