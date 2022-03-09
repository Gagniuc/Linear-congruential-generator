# Linear congruential generator
<i>Linear congruential generator</i> is an application that demonstrates the generation of pseudo-random numbers.

There are specialized mathematical functions (deterministic algorithms) for simulation of “random” numbers. The numbers generated by these functions are called pseudo-random
numbers. This name comes from the fact that the random numbers are generated based on mathematical formulas, which explode an initial “seed” (usually, a
number extracted from the computer clock) into a sequence of numbers that follow a pattern. Thus, each new number in the sequence will be dependent on the
previous number provided by the same formula. An example of a pseudo-random generator is the linear congruential generator:

Where X1 is an integer seed, n indicates the total number of terms in the sequence, m is the modulus, a is the multiplier, and c is the increment. The pattern of
such a function shows a characteristic distribution for long numerical sequences that exceed the period (the cycle of repetition). The range of numbers of the
above function is between 0 and m −1, with a uniform distribution of integers. The length of a period can be controlled by setting the value of m. However, a
narrow portion over this sequence shows a small piece of the wider pattern, thus simulating randomness without showing the real distribution derived from the
initial seed (X1).

Note that the construction and theory behind the chart of this application can be found [here](https://github.com/Gagniuc/World-smallest-js-chart-v1.0).

Live demo: https://gagniuc.github.io/Linear-congruential-generator/

<kbd><img src="https://github.com/Gagniuc/Linear-congruential-generator/blob/main/%5BG%5D%20Linear%20congruential%20generator.png" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>
