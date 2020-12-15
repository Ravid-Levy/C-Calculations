# C-EX

## Makefile
make all - create two exe program one with static lib and one with dynamic lib.
<br />
make mains - compile the program with creation static library libmyMath.a. 
<br />
make maind - compile the program with creation dynamic library libmyMath.so. 
## main.c
<br />
calculate f(x)=e^x + x^3 -2 with given x
<br />
calculate f(x)=3x+2x^2 with given x
<br />
calculate f(x)=(4x^3)/5 -2x with given x

## basicMath.c
<br />
add (float x, float y) - return x+y
<br />
sub (float x, float y) - return x-y
<br />
mul (float x, float y) - return x*y
<br />
div (float x, float y) - return x/y
<br />

## power.c
<br />
Power(double x, int y) - return x^y
<br />
Exponent(int x) - return e^x
<br />

## myMath.h
### content
<br />
#ifndef _MYMATH_H
<br />
#define _MYMATH_H
<br />
float add (float x , float y); 
<br />
float sub(float x,float y);
<br />
float mul(float x,float y );
<br />
float div(float x,float y);
<br />
double Power(double x, int y);
<br />
double Exponent(int x);
<br />
#endif



