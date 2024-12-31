# INTRODUCTION-OF-C++NOTES


INTRODUCTION OF C++ 


What is C++ 

C++ is a very extensive language that can be used both within basic structured programming and object oriented
programming. Furthermore, windows programming in the graphic Windows environment is supported. C++ has, thanks
to its level of detail, its strength in digging deeply into the most obscure corners of the computer, control the operating
system, communicate with hardware, circuit boards and external equipment like measurement units and communication
devices. In this course, however, we will stick to basic structured programming.

C++ is a compact language with many symbols having their own meanings. This means that C++ code looks complicated
to the novice. On the other hand it provides many tools for efficient coding. Programs written in C++ are very rapid due
to the fact that the compiler optimizes them to each specific processor type. That is the reason why you mostly use C++
in situations where processor time and performance are ultimate.


Why Use C++
C++ is one of the world's most popular programming languages.
C++ can be found in today's operating systems, Graphical User Interfaces, and embedded systems.
C++ is an object-oriented programming language which gives a clear structure to programs and allows code to be reused, lowering development costs.
C++ is portable and can be used to develop applications that can be adapted to multiple platforms.
C++ is fun and easy to learn!
As C++ is close to C, C# and Java, it makes it easy for programmers to switch to C++ or vice versa.







To Start your First Project: 

Install the IDE or (Integrated Development Environment).


Learn the basic the Syntax of C++ 

Print the Basic (Hello World);





    The Basic of Syntax of C++


#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}





Variables

A variable is used by the program to store a calculated or entered value. The program might need the value later, and
must then be stored in the computer’s working memory. Example:

Variable name
 Variable value
dTaxpercent 0.25
Here we have selected the name ’dTaxpercent’ to hold the value 0.25. You can in principle use any variable name, but it is
recommended to use a name that corresponds to the use of the variable. When the variable name appears in a calculation
the value will automatically be used, for example:




Declaring Variables
The purpose of declaring a variable is to tell the program to allocate space in the working memory for the variable. The
declaration:

int iNo;


tells that we have a variable with the name iNo and that is of integer type (int). You must always specify the data type to
allocate the correct memory space. An integer might for instance require 4 bytes while a decimal value might require 16
bytes. How many bytes to allocate depends on the operating system. Different operating systems use different amounts
of bytes for the different data types.
The variable name should tell something about the usage of the variable. Also, a standard used by many people is to
allocate 1-3 leading characters to denote the data type (i for integer).
Note that each program statement is ended by a semicolon.
Below we declare a variable of decimal type:
double dUnitPrice;
double means decimal number with double precision. Compare to float which has single precision. Since double
requires twice as many bytes, a double variable can of course store many more decimals, which might be wise in
technical calculations which require high precision.


 



