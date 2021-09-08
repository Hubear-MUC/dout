dout 1.0
--------

The function 

  dout()
  
provides a routine to show a number of the data type double on the screen (in the terminal).

The "d" in the function name means "double" as data type.

The usage is like this:

  double a;
  
  a = 1.2345;
  
  dout (a);
  
The usage of  dout()  saves bytes of code space compared to a full call of  printf()  including format information needed to show double numbers.

Just include in your program with

  #include "dout.cpp"
  
to use it.



Version history
---------------

Version 1.0

Initial version

