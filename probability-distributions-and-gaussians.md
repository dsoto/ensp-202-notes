# Probability Distributions and Gaussians

So far, we have focused on single estimates.
How much volume is this tank, how long is this room, etc.
Now we ask questions about several objects at once.

- How tall are the students in this class?
- How big are the classes at my university?
- How big are the departments at my university?

Here we are interested in the behavior of a single variable.
Is it evenly distributed or are some values more present than others?
What are the largest and smallest values?

## Histogram

A common tool for looking at single-variable (univariate) data is a histogram.

A histogram

- Shows data of a single variable
- Shows the value of that data on the x-axis
- Divides the x-axis into evenly spaced bins
- On the y-axis shows the number of values in each bin


## Probability Distribution

A probability distribution is a model that explains the relative probability of different events happening.
The probability distribution is an ideal mathematical model.
The real world doesn't fit it exactly, but the model provides lots of practical power.

The x-axis is the value of a measurement and the y-axis is the relative frequency.

The area under the curve of a (normalized) probability distribution is exactly one.

The probability of a measurement occurring between two intervals is the area under the curve between those two intervals.

These probability distributions are models just like a rectangle or a circle.
This probability distribution is usually a mathematical function.

For example, the gaussian distribution is given by

$$f = \frac{1}{\sqrt{2\pi\sigma^2}}e^{-(x-\mu)^2/\sigma^2}$$

![](./figures/Normal_Distribution_PDF.svg)

Notice our new friend, the number e, showing up.

## Relative probability

If you can calculate or estimate the area under the curve of a probability distribution, you can predict the probability of an event occurring.
