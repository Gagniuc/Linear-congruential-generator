# Linear congruential generator

<i>Linear congruential generator (LCG)</i> is an application that demonstrates the generation of pseudo-random numbers. The LCG is a specialized mathematical function (deterministic algorithm) for simulation of “random” numbers. The numbers generated by LCG are called pseudo-random numbers. This name comes from the fact that the random numbers are generated based on mathematical formulas, which explode an initial “seed” (usually, a number extracted from the computer clock) into a sequence of numbers that follow a pattern. Thus, each new number in the sequence will be dependent on the previous number provided by the same formula. The classical example of a pseudo-random generator is the linear congruential generator (X<sub>n+1</sub> = (a × X<sub>n</sub> + c) mod m):

```
X[n+1] = (a × X[n] + c) mod m
```

Where <i>X<sub>1</sub></i> is an integer seed, <i>n</i> indicates the total number of terms in the sequence, <i>m</i> is the modulus, <i>a</i> is the multiplier, and <i>c</i> is the increment. The pattern of such a function shows a characteristic distribution for long numerical sequences that exceed the period (the cycle of repetition). The range of numbers of the above function is between 0 and <i>m</i>−1, with a uniform distribution of integers. The length of a period can be controlled by setting the value of <i>m</i>. However, a narrow portion over this sequence shows a small piece of the wider pattern, thus simulating randomness without showing the real distribution derived from the initial seed (<i>X<sub>1</sub></i>). This subject of pseudo-random numbers is related to a philosophical discussion from the book entitled <i>Algorithms in Bioinformatics: Theory and Implementation</i>. Note that the construction and theory behind the chart of this application can be found [here](https://github.com/Gagniuc/World-smallest-js-chart-v1.0).

Live demo: https://gagniuc.github.io/Linear-congruential-generator/

<kbd><img src="https://github.com/Gagniuc/Linear-congruential-generator/blob/main/%5BG%5D%20Linear%20congruential%20generator.png" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>
