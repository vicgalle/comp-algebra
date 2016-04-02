# Computational Algebra

Fundamental Computer Algebra algorithms implemented in Maple


## euclides.mws


**Euclides algorithm for Z, Zp, Z[i], Q[X], Fp[X] and Fq[X] with q=p^n.**


 Euclides algorithm calculates the gcd of two elements using the subtraction operation.
 
 
(*) For example, gcd(126,35):
126 = 3*35 + 21;
35   = 1*21 + 14;
21   = 1*14 + 7;
14   = 2*7 ;


Execution of examples that use mcd in euclides.wms:

![alt Euclides examples](https://github.com/Ana06/comp-algebra/blob/master/images/euclides.jpg "Euclides examples")


Execution of examples that use mcdq in euclides.wms (case Fq[X]). For example, we work in F16[X]:

![alt Euclides examples in Fq[X]](https://github.com/vicgalle/comp-algebra/blob/master/images/euclidesFq.PNG "Euclides examples in Fq[X]")

## extendedEuclides.mws

**Extended euclidean algorithm**

It computes the gcd of the given inputs and represents it as a linear combination, following the equalities (*) in the previous section in ascending order.

Some examples that use this function:

![alt Extended Euclides examples](https://github.com/vicgalle/comp-algebra/blob/master/images/extendedEuclides.PNG "Extended Euclides examples")


## additionProduct64.mws


**Addition and product in base 64.**

Numbers are unsigned and represented as integer lists. Take into consideration that the most significant position is the first in the right.

Execution of examples that use functions in additionProduct64.wms:

![alt Addition and product in base 64 examples](https://github.com/Ana06/comp-algebra/blob/master/images/additionProduct64.JPG "Addition and product in base 64 examples")
 
 
## Authors

This project is being developed by Ana María Martínez Gómez and Víctor Adolfo Gallego Alcalá.



## Licence

Code published under MIT License (see [LICENSE](LICENSE))

