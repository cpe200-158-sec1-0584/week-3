﻿# Implement the Fraction class according to the following requirements:

## Propeties:
- Numer: Numerator
- Denom: Denominator (default=1, cannot be 0)
- Count: counting #objects of this class (static)
Note: Numerator and Denominator have to in the minimal form.
      See r3 and r6.

## Constructors:
- Fraction (): default constructor
- Fraction (Fraction a): copy constructor
- Fraction (numerator, denominator)
note: increment the Count property when an object is created

## Methods
- setValue: set fraction value
- GCD: calculate Greatest Common Divisor of two integers (static)

## Operator Overloading:
many many operators need to be overloaded!!! 

## Question?
1. Is the number of Fraction objects equal to the 'new' keywords used
   in the 'main' methods? How come?

   Answer : No, it isn't. Because you can create object in method by using word 'new'.

2. Are the result, r3 and r7, in case#1 and case#2 the same? Why?

   Answer : No, there aren't the same. Case#1 create new object (create r7 by use value of r3).
			Case#2 doesn't create new object but point to old object before (point r7 to r3).

## Expected Output:

***** 3 Fraction objects have been created *****
***** 8 Fraction objects have been created *****
***** 12 Fraction objects have been created *****
[Rational: 0/1], value=0]
[Rational: 2/1], value=2]
[Rational: 1/3], value=0.333333333333333]
[Rational: 2/1], value=2]
[Rational: 5/3], value=1.66666666666667]
[Rational: 4/1], value=4]
[Rational: 4/3], value=1.33333333333333]
[Rational: 8/1], value=8]
[Rational: 6/5], value=1.2]
True
True
False
[Rational: 10/1], value=10]
***** 12 Fraction objects have been created *****
GCD of 3650 and 360: 10
GCD of 3600 and 360: 360

