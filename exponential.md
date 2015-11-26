# Exponential

The word exponential makes this concept sound unnecessarily difficult.
If a function is exponential, the relative difference between any two
evenly spaced values is the same, anywhere on the graph.  This is
similar to linear functions where the absolute difference between any
two values separated by the same x-axis distance is the same.

## Graph illustrating this point

## Folding paper
- Zero folds 2$^0$ makes one sheet thick
- One fold 2$^1$ is two sheets thick
- How many times can you fold?
- How can we express the number of pages by the number of folds?
- Can we write out the pattern?

<!-- my max is six -->

## Folding Paper
$$ \textrm{pages} = 2^{\textrm{folds}} $$

## Rabbits
- start with two
- wait one year
- now we have double (4)
- wait another year
- now we have eight (8)
- how many in 5 years?

## Rabbits
The number of rabbits at the start of the generation (starting with
generation zero) is
$$ \textrm{rabbits} = 2^{\textrm{generations+1}} $$

## Doubling
![](../figures/doubling.pdf)


## Which gets bigger faster?
$x^2$ or $2^x$

Draw these out in your notebook to see

<!-- note you are moving the x from the base to the exponent -->

## Money grows the same way
- Start with $1000
- Grow by 10%
- Now $1100
- Grow by 10%
- Now $1210

$$ 1000 \cdot (1+0.10)^{years} $$

## Exponential growth
- The rate of change is proportional to the total number
- The doubling time is constant over the entire range
- What things exhibit these characteristics?

## Exponential growth
- Populations
- Disease spread
- Credit card balances
- Viruses

## Exponential growth
![](../figures/exponential.pdf)


## Exponential growth
![](../figures/exponential.pdf)

## Exponential Decay
What if instead of doubling every year, something fell by half each
year?

<!-- tear a piece of paper in half repeatedly -->

## Halving
![](../figures/halving.pdf)

## Exponential Decay
![](../figures/exponential-decay.pdf)

## Exponential decay
- A quantity loses the same fraction of itself for a given time interval
- Nuclear waste
- Toxins in a body

## Inverse functions
- Recall that the square root and the cube root were the inverse of the
    squared function and the cube function

## Logarithm
- The inverse of exponentiation is the logarithm
- Properties of $e$
- You have to specify your base on a computer (2, e, 10)

## Logarithm
- Inverse of exponential function
- If $y = 10^x$ then $\log y = x$
- If $y = e^x$ then $\ln y = x$
- For any other number (called the base, $b$):
    - If $y = b^x$ then $\log_b y = x$

## Logarithm
The logarithm in base 10 basically asks, if you are in base 10, how many digits?

## Logarithmic scales
- Musical pitch
- Richter scale
- Vision
- Sound

In each of these, we perceive or use the logarithm.

## Unexpected connections
The natural logarithm is the area under the 1/x curve

## This rule is a consequence of logarithms
$$ 10^a \cdot 10^b = 10^{a+b} $$

Take log of both sides

$$ a \cdot \log 10 + b \cdot \log 10 = (a+b) \cdot \log 10 $$
## Calculation examples
- Julia
- Calculator

<!-- flipping equations -->

## Differential equation

$$ \frac{dP}{dt} = rP $$

- P is the population
- r is the rate of growth

Any equation where the change is proportional to the population is
exponential growth

<!-- draw out some rise over run graphs -->

## Differential equation

$$ \frac{dP}{dt} = \textrm{constant} $$

Linear growth has the changes is constant


## Definitions of e

$$ e = \lim_{n \to \infty} (1 + 1/n)^n $$

$$ e = 1 + 1 + \frac{1}{2 \cdot 1} +  \frac{1}{3 \cdot 2 \cdot 1}  +  \frac{1}{4 \cdot 3
\cdot 2 \cdot 1} + \cdots $$


## Euler

$$ e^{i \theta} = \cos \theta + i \sin \theta $$

$$ e^{i \pi} + 1 = 0 $$

where $i = \sqrt{-1}$

## Logistic function

Here the rate of change decreases as the population gets very large

This gives an s-shaped function.

<!-- like in the gangham style video -->




