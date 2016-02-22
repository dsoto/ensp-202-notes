# Computation Fundamentals

In professional environments, you will use a computer to perform your
computations.  You likely have lots of practice on calculators.  There
are significant similarities between the calculator and the computer but
there are some important differences.

# Materials

You can find an interactive set of files
[here.](http://mybinder.org/repo/dsoto/computing-tutorial)

If the link above doesn't work, you can find the files
[here](https://github.com/dsoto/computing-tutorial).  Clicking on this
icon
![Binder](http://mybinder.org/badge.svg)
should launch an interactive session.

# Types

The computer uses ones and zeros to represent all data.  Anything stored
on the computer, a poem, a photo, or a number, is represented using ones
and zeros.  In order to correctly interpret the ones and zeros the
computer needs to know what you are storing.

## Integers

These are the counting numbers.  No fractions, no decimals.

## Strings

This is how the computer stores words.

## Floats

These are numbers with a fractional part.  If you think you are using
floats but are using integers, you may get strange results like one
divided by two equals zero.


# Variables

To make the details of a computation more clear, we can use readable
names for our numbers and then use the names in the calculation.

    power = 100
    time = 30
    energy = power * time

This makes the intention of the calculation more clear to the reader.

In our language (python) the computer decides how to interpret each
variable by what you put inside it.




# Numerical Computing Environment

- Matlab
- Scientific Python
- Julia
- Sage Math Cloud

<!-- There is a subtle difference between computer programming and numerical -->
<!-- computing. -->

# Learning Objectives

- Able to use numerical computing environment to create and narrate computations
- Able to use spreadsheets to create computations




## Written
- Explanation of unit factor with inches and centimeters


## Unit Factor

$$ 1 \textrm{inch} = 2.54 \textrm{cm} $$
Dividing, we get
$$ \frac{2.54\textrm{cm}}{\textrm{inch}} = 1 $$
Note that 2.54 does not equal one, but with the units the two physical
quantities of length are equal.


## Combinations of units
- We often combine units to express new quantities



## Scientific Notation

$$6 \cdot 10^3$$ is entered as ``6E3``.

## Units

Computation of physical quantities often relies on the human to define
and use a consistent set of units of measurement.  There are tools that
allow us to add physical quantities to our calculations, but they are
not as rich as I could like them to be.  One good practice is to
explicitly include the unit name in the variable name.

    power_watt = 100
    time_sec = 30
    energy_joule = power_watt * time_sec



## Units

There are also computer libraries that allow you to include units in the
definition of your variables.

- Pint python library

## Defining Functions

A custom function can be created and used.  The syntax for this often
varies but the idea is usually the same.

    m = 1
    b = 10
    f(x) = m * x + b
    f(5) => 15


For Julia:

    m = 1
    b = 10
    f(x) = m * x + b

Python has a different syntax but it is the same idea.

## Narration

- You can add text and mathematics to your document
- ``# Title`` makes bold text
- ``$$ \frac{1}{2} $$`` creates mathematics $$ \frac{1}{2} $$


## Google Docs

- be sure you have access to your new sonoma.edu drive account
- access the template file that I shared
- fill in the different values and sheets

## Pandas
- assumes mastery of single variables
- now we do vector calculations (numpy or pandas?)
- to do TMY calculation we need to take difference and plot
- then we need to add up only the positive values

## Scale of energy quantities
![](../figures/ipcc_energy_primer.png)
- from IPCC Energy Primer

## Energy Units
- Joule
    - SI Unit.  One Newton-Meter.
- Kilowatt-Hour
    - Energy consumed by 1 kW load over one hour
- Calorie
    - Energy to heat one gram of water one degree Celsius
- Kilo-calorie
    - One thousand calories.  Used in food energy content.
- British Thermal Unit (BTU)
    - Energy to heat one pound of water by one degree Fahrenheit
- Quad
    - One quadrillion ($10^{15}$) BTU

## Unit Conversions
- We may wish to compare energy units that are not consistent
- Often you can look up conversions in a table
- Other times you may need to recreate the conversion


## Variables
- single values
- math expressions with variables
- sympy creation of math expressions?
- arrays
- linspace?
- treating an array like a variable
- data frames (groups of arrays)
- first use of conditionals (only add up positives or negatives)
- fancy indexing to get positives or negatives

<!--
i need to make ipython notebooks that take students through this
-->

## Worked Exercises

## Exercise
- Estimate the yearly use of gasoline in the US
- What is our strategy?

## Exercise
- How many gallons do you consume?
- How many persons in the US?

## Problems


