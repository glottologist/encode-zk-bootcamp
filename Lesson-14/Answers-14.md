# Homework 14

## Secret Sharing

### Questions

Try out Shamir secret sharing

-1). Create a polynomial with the secret being the constant term $a0$ , the other a values $(a_1. . . a_4)$ can be chosen at
random. The polynomial will be of the form

$y(x) = a_4x^4 + a_3x^3 + a_2x^2 + a_1x + a_0$

- 2). Calculate the y values for five x values by evaluating the polynomial, these are the shares.

- 3). Reconstruct the polynomial using those shares and an online interpolation calculator such as https://planetcalc.com/8680/

### Answers

- 1). Chosen polynomial is :

  $y(x) = 7x^4 +  6x^3 + 2x^2 + 5x + 42$

  where 42 is the secret (to life, the universe and everything)

- 2). Choosing the values of x :

       | x   | y             |
       | --- | ------------- |
       | 2   | 220   |
       | 4   | 2270        |
       | 6   | 10512      |
       | 13  | 213,554    |
       | 21  | 1,417,962 |

- 3). Choosing 4 of the 5 shares:

       | x   | y             |
       | --- | ------------- |
       | 2   | 220   |
       | 4   | 2270        |
       | 13  | 213,554    |
       | 21  | 1,417,962 |

[PlanetCalc](https://planetcalc.com/8680/) requires all 5 interpolation points because you cannot specify the degree of the polynomial to find. The calculator uses the Lagrangian Interpolation method:

$P(X)=\sum_{j=0}^{n}y_{j}(\prod_{i=0,i\neqj}^{n}\frac{X-x_{i}}{x_{j}-x_{i})$
