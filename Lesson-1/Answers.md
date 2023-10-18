# Homework 1

## Modular Arithmetic

### Questions

1. Working with the following set of integers $S={0,1,2,3,4,5,6}$. What is:
   a). $4 + 4$
   b). $3 X 5$
   c). what is the inverse of $3$?
2. For $S={0,1,2,3,4,5,6}$. Can we consider the $S$ and the operation $+$ to be a group?
3. What is $-13 \bmod{5}$?

### Answers

- 1.  The set $S$ is closed under $mod 7$ so:
  - a). $4+4\equiv 8 \bmod{7}=1$
  - b). $3x5\equiv 15 \bmod{7}=1$
  - c).
    - i). For the additive inverse we are looking for a variable that satisfies $a+b=0 \bmod{7}$. If $3$ is the given number then we look to satisfy $3+a=0 \bmod{7}$. We can see that $4$ staisfiys the equation - $3+4=0 \bmod{7}$.
    - ii). For the multiplicative inverse we are looking for a variable that satisfies $a*b=1 \bmod{7}$. If $3$ is the given number then we look to satisfy $3*a=1 \bmod{7}$. We can see that $5$ staisfiys the equation - $3*5=1 \bmod{7}$.
- 2. To be considered a group, the set of elements $S$ should have the properties of *Closure*, *Associativity*, *Identiity Element*, and *Inverse Element* under a spcified binary operation.  We will consider the two different binary operations, i) addition $(S,+_s \bmod{7})+$ and ii) multiplication $(S,*_s \bmod{7})$.
- - a). *Closure*
-  - i). $\forall{a,b} \in{S}$  the following is satisfied $(a+b)\bmod 7 \in S$ so we can consider the group closed
-  - ii). $\forall{a,b} \in{S}$  the following is satisfied $(a*b)\bmod 7 \in S$ so we can consider the group closed

## Polynomials

### Questions

4. For the polynomial $x^3-x^2+4x-12$.  
   a). Find the positive root?
   b). What is the degree of this polynomial?

### Answers
