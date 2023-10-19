# Homework 2

## Modular Arithmetic

### Questions

- 1).
  - a). Is it true that all odd squares are $\equiv 1\bmod{8}$?
  - b). What about even squares $\bmod{8}$

### Answers

- 1).
  - a). If we consider an odd square expressed as $(2k+1)^2$, this expands to $4k(k+1)+1$. The product of two consecutive numbers $k(k+1)$ should be even so therefore $k(k+1)=2n$. Then $(2k+1^2)$=4(2n)+1=8n+1\equiv 1mod 8$
  - b). Consider $(2n)^2=8m+1 => 4n^2=8m+1$. If n is odd, for example 1 , then $4(1)^2=8m+1 =>  m=8/3$ which disproves this.

## Vanity Bitcoin Address

### Questions

- 2). Try out the vanity bitcoin address example at asecurity

### Answers

- 2). Using the repeating characters "BC" for bootcamp, as the prefix on the Eth vanity generator. It was interesting to see the complexity increase:

| PREFIX   | COMPLEXITY        |
| -------- | ----------------- |
| B        | 32                |
| BC       | 1024              |
| BCB      | 32,768            |
| BCBC     | 1,048,576         |
| BCBCB    | 33,554,432        |
| BCBCBC   | 1,073,741,824     |
| BCBCBCB  | 34,359,738,368    |
| BCBCBCBC | 1,099,511,627,776 |

## Efficiency

### Questions

- 3. What do you understand by:
  - a). $O(n)$
  - b). $O(1)$
  - c). $O(\log{n})$
  - d). For a proof size, which of thses do you want?

### Answers

- 3.
  - a). $O(n)$ shows that the complexity scales linearly with regard to an input $n$.
  - b). $O(1)$ show that the complexity remains constant regardless of input.
  - c). $O(\log{n})$ shows that complexity scales as the logarithm of the input $n$.
  - d). For computating a proof, the ideal would be $O(1)$ so that a proof can be generated a timely fashion for any input size.
