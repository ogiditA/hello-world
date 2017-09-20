# hello-world

Anthoy Ogidi
Programming Assignment1
9/19/2017

To write a reusable library of basic arithmetic functions that should be able to perform integers and floating point numbers (as well as numbers provided in octal, binary, and hexadecimal). The operations to be supported are: - Addition, Subtraction, Multiplication, Divisio, Square Root, Exponent, and Conversion between the various types (octal, hexadecimal, integer, binary).

Measures taken to ensure that the library is reusable include making sure that the right C++ header files are included such as the <iostream> for standard input/output functions and the <cmath> for mathematical operations functions. Under the cmath header file, the C++pow() function and the C++sqrt() (square root) function used to compute square root of a number are included. 
The C++pow()takes two parameters , base (the base value) and exponent (exponent of the base) such as
    double pow(double base, double exponent);
    float pow(float base, float exponent);
    long double pow(long double base, long double exponent);
    Promoted pow(Type1 base, Type2 exponent); // For other argument types
The sqrt() function takes a single non-negative argument (domain error occurs if negative argument is passed to sqrt() function), such as,
    double sqrt(double x);
    float sqrt(float x);
    long double sqrt(long double x);
    double sqrt(T x); // For integral type

