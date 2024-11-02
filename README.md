# Distribution Probability NP

A Python package for calculating and visualizing Binomial and Gaussian distributions. This package provides functionalities for statistical calculations and visualizations of the probability distributions, including mean, standard deviation, probability density functions, and plotting.

PyPi redirect: https://pypi.org/project/distribution-probability-np/

## Features

- **Binomial Distribution**: Calculate mean and standard deviation, visualize with bar charts, and compute probability density functions.
- **Gaussian Distribution**: (To be implemented or included if you have similar functionalities).

## Installation

You can install the package using pip.

```bash
pip install pip install distribution-probability-np

# Create a Binomial distribution instance with probability of success 0.5 and 20 trials
binom = Binomial(prob=0.5, size=20)

# Calculate mean and standard deviation
mean = binom.calculate_mean()
stdev = binom.calculate_stdev()

# Replace stats with data if you have a dataset
# binom.replace_stats_with_data(data)

# Plotting the distribution
binom.plot_bar_pdf()
