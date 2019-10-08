# Rain Water Collection

Water scarcity and security is an important topic.
Rain water collection barrels are a way to address water efficiency.

Our building has a collection system on the roof.
We want to determine the impact of the system by asking two quantitative questions.

- How much rain we can capture in our barrels before they are full and we can no longer collect rain?
- How much extra watering we can provide from the rain collection barrels to the areas in the garden that we want to irrigate.

# Strategy

These and related problems are a good use of our models for volume.

Notice that the answer we want to find is the "height" of a box that we know how to find the volume of.

To estimate the rainfall we can capture, we create models for the volumes of water for both the roof and the tanks.

Then find the amount of rain by setting these two volumes equal and solving for the thickness of the rectangular prism we are using to model the roof.

# Estimation Method

## Roof Area

11 strides east to west
6 strides north south from roof peak to gutter

$$ 11 strides\ \cdot 6 strides\ (\frac{5 ft}{stride})^2 = 1650 ft^2 $$

## Tank Volume

circumference of 5 wingspans

$$ 5 wingspans\ \cdot \frac{5 feet}{wingspan} = 25 feet$$

Since $$C = 2\pi r$$, the radius is

$$ r = \frac{25 feet}{2\cdot3.14} = 4.0 feet $$

Now we find the area from $$A = \pi r^2$$.

$$ A = 3.14 \cdot (4 feet)^2 = 50 square feet $$

The cylinder volume is the area times the height

$$ V = 50 square feet \cdot 6 feet = 300 cubic feet $$

## Inches of Rain

We set the volume of two tanks equal to the volume of the roof "area" with an unknown height.

$$ 2 V_{tank} = V_{roof} $$

$$ 2 \cdot 300 cubic feet = 1650 square feet \cdot height $$

$$ height = \frac{2 \cdot 300 cubic feet}{1650 square feet} = 0.36 feet $$

$$ 0.36 feet \cdot \frac{12 inches}{foot} = 4.4 inches $$

# Precise Method

We'll use the measuring wheel to get a more precise estimate.







