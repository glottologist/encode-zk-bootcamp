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
- 2. To be considered a group, the set of elements $S$ should have the properties of _Closure_, _Associativity_, _Identiity Element_, and _Inverse Element_ under a spcified binary operation. We will consider the two different binary operations, i) addition $(S,+_s \bmod{7})+$ and ii) multiplication $(S,*_s \bmod{7})$.
  - a). _Closure_
    - i). $\forall{a,b} \in{S}$ the following is satisfied $(a+b)\bmod{7} \in S$ so we can consider the group closed
    - ii). $\forall{a,b} \in{S}$ the following is satisfied $(a*b)\bmod{7} \in S$ so we can consider the group closed
  - b). _Associativity_
    - i). $\forall{a,b,c} \in{S}$ the following is satisfied $(a+b)+c\bmod{7}=a+(b+c)\bmod{7}$ so we can consider the group to be associative under the operation $+ \bmod{7}$
    - ii). $\forall{a,b,c} \in{S}$ the following is satisfied $(a*b)*c\bmod{7}=a*(b*c)\bmod{7}$ so we can consider the group to be associative under the operation $\* /root/
  - c). _Identity Element_
    - i). $\forall{a,b} \in{S}$ the following is satisfied $(a+b)\bmod{7}=(a+b)\bmod{7}=a$ if the identify element is $0$ which is also in $S$.
    - ii). $\forall{a,b} \in{S}$ the following is satisfied $(a*b)\bmod{7}=(a*b)\bmod{7}=a$ if the identity element is $1$ which is also in $S$.
  - d). _Inverse Element_
    - i). $\forall{a,b} \in{S}$ the following is satisfied $(a+b)\bmod{7}=0$, where $0$ is the identity element, so we can conclude that there exists an inverse for elevry element.
    - ii). $\forall{a,b} \in{S}$ the following is not satisfied $(a*b)\bmod{7}=1$, where $1$ is the identity element. Any element that is multiplied by the element $0$ will be zero which means that there is no inverse for that element and so no all elements have an inverse.

Thus, $(S,+_s\bmod{7})$ is a group but $(S, *_s\bmod{7})$ is not.

3. $-13\bmod{5}=2$?

## Polynomials

### Questions

4. For the polynomial $x^3-x^2+4x-12$.  
   a). Find the positive root?
   b). What is the degree of this polynomial?

### Answers

4. Attempting to factorize this gives $x^3-x^2+4x-12=(x-2)(x^2+x+6)=0$.
 - a). $x^2+x+6$ cannot be simplified further which means it has complex roots so that leaves the only real root as $(x-2)=0$, which means that 2 is the positive root.
 - b). The degree of a polynomial is the highest power of the variables, which in this case, is 3.
