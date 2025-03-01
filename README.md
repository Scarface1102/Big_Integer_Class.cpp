# Big_Integer_Class.cpp

This BigInt class supports all relational, arithmetical, assignment and Unary operators.

* Make sure you include the following headerfiles :- iostream, iomanip and vector.

* This class will works on C++ 14 and above.

* Karatsuba multiplication is used here for multiplication and as a result if the length of the number (number of digits) is more than 2.5 * 10 ^ 8 (approx) then it may give wrong results (This error will be inevitable with such large numbers). There is also a function named Multiply_Naive which use O(N ^ 2) algorithm that will work with any length (Though no need to multiply numbers of order 10 ^ 8 as it will be computationally expensive, so using Karatsuba is good enough) ( Multiply_Naive will work better for small Numbers ).
