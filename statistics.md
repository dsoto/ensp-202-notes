# Statistics

- Statistics helps us quantify uncertainty
- Helps us infer about a large population from a small sample

## Questions that use Statistics

- How many organisms use Copeland Creek as habitat?
- How dangerous is driving?
- Is gender or racial bias an observable problem?
- What is the average class size at SSU?  What is your average class size?  Are they different?

## Topics

- Supporting questions and decisions
- Probability
- Probability Distributions
- Hypothesis testing

## Decision making
- How do we make decisions when we cannot predict the outcome?
- How do you decide to bring an umbrella?

## Probability
$$ \textrm{probability} =
   \frac{\textrm{specific outcome}}
        {\textrm{all outcomes}} $$

## Odds

$$ \textrm{odds} =
   \frac{\textrm{specific outcome}}
        {\textrm{other outcomes}} $$

If something has 1:1 odds, this means a 50% probability.

## Area representation of probabilities

- attach white board images

<!-- add tree representation? -->

## Contingency table representation

| Treatment     | Rash got better | Rash got worse |
|---------------|-----------------|----------------|
| Skin Cream    | 223             | 75             |
| No skin cream | 107             | 21             |

We can ask several questions using this data

- If you use skin cream, what is the probability your rash will get better?
- If you do not use skin cream, what is the probability your rash will get better?
- If your rash got better, what is the probability you used skin cream?
- If your rash got worse, what is the probability you used skin cream?

## Hypothesis testing

- Given your favored hypothesis, what would the world look like?
- Given the alternate hypothesis, what would the world look like?
- Based on your data, which of the two hypotheses is more likely?

## Conceptual probability
- For many things, we cannot predict a single outcome, but we can
  predict the average outcome
- Coin toss
- Roll of dice

<!-- Although we can't predict a single flip or roll, we know what percentage -->
<!-- of heads or tails we will observe over many flips. -->

# Rolling Dice

- We don't know what any outcome of a roll will be
- However, we know with high confidence what the total number of outcomes for many rolls of the dice will be.


## Rolling computer dice

- We can easily simulate these sorts of experiments with computers

## Notebooks
- 202-dice-distribution.ipynb
- 202-synthetic-dice-distribution.ipynb

# Bayes' Theorem

Bayes theorem allows us to determine the probability of a given hypothesis being true given the data if we know the probability of the data being true given the hypothesis.

$$ P(A|B) = \frac{P(B|A)P(A)}{P(B)} $$

The posterior odds are equal to the prior odds multiplied by the likelihood ratio

$$ \frac{P(H_1 | D)}{P(H_2 | D)}
   =  \frac{P(D | H_1)}{P(D | H_2)}
     \frac{P(H_1)}{P(H_2)} $$

<!-- what is a source for this odds ratio formulation? -->

# Probability distributions

- We interpret probabilities as the area under the curve

## Probability distribution
- Some events are expressed as single probabilities
- Other events are better described by a probability distribution
- We can use our intuition about areas to make probability estimates

## Probability distribution examples
- Temperature
- Wind speed
- Climate forecasts

# Motivated Numeracy

## Probability
- How do we know if a treatment is effective?

## Example: Rash treatment

| Treatment     | Rash got better | Rash got worse |
|---------------|-----------------|----------------|
| Skin Cream    | 223             | 75             |
| No skin cream | 107             | 21             |

## Which was more effective?
- Split into groups and determine why


## Full experiment
![](../figures/motivated-numeracy-2.pdf)



## Motivated numeracy
- Science Comprehension Thesis
- Identity-protective Cognition Thesis
- [Paper Link](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2319992)

"more Numerate subjects would use their quantitative-reasoning capacity
selectively to conform their interpretation of the data to the result
most consistent with their political outlooks."

## Experiment results
- Performance on politically neutral issue correlated with numeracy
- Highly numerate people with strong political beliefs found the answer
  consistent with their political beliefs


# Cancer Example

## Cancer screening example

<!-- see notes for more breast cancer details -->

|            | positive test | negative test |
|------------|---------------|---------------|
| has cancer | 72            | 8             |
| no cancer  | 694           | 9226          |

- What should the rows add up to?
- What should the columns add up to?
- What should all four numbers add up to?


## Questions

- What questions can you answer with this data?


## Cancer example as percentages

|            | positive test | negative test |
|------------|---------------|---------------|
| has cancer | 90%           | 10%           |
| no cancer  |  7%           | 93%           |

- 0.8% of population has cancer
- 99.2% of population is cancer free

<!-- this needed major scaffolding -->
<!-- students had a very hard time holding the pieces together -->
<!-- students also seemed very disinterested late in the semester -->

# Examples

## Appliance Ownership

Given appliance ownership in an electrified village, what would you expect for ownership in a village undergoing electrification?

## Classroom Seating

Given a class, what probability would you assign that you are sitting in your chair on any given day?

## Extremely hot days

The temperature in the summer in a location can be viewed as a probabliity distribution.
From this distribution, can you estimate the number of very hot days in a summer?
How would this number of hot days change under global warming?

## People v. Collins

- https://en.wikipedia.org/wiki/People_v._Collins
- https://www.maa.org/external_archive/devlin/devlin_07_08_07.html

## Random Kanye and Deep Drumpf

# Activities

## Evidence and Hypothesis

State the evidence and competing hypotheses for questions that interest you.



## Supplemental reading

- Naked Statistics, Charles Wheelan
- The Signal and the Noise, Nate Silver
- Statistical Inference for Everyone, Brian Blais

