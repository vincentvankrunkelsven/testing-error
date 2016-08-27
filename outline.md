## Introduction to Ideas of Inference

Using case studies:

* Examples/definition of null and alternative hypotheses
* Examples of simulated randomization distributions
  * Based on swapping data, create a randomized sample
  * Use dotplots and histograms
  * Count number of randomized samples above/below various cutoffs (including zero)
* Conclusions based on randomization distributions
  * Sometimes we can conclude the data are different from the population, sometimes we can't.
* R: ggplot2 - histograms and dotplots 

## Running Randomization Test: gender discrimination

* Start with numerical and graphical summaries of the data, remind ourselves what we'd like to investigate about the population.
* Create many randomized samples, for the first few find the statistic(s) of interest.
* Plot the many sample statistics from the randomized samples.
* Evaluate the consistency of the observed data with the distribution of the randomized sample statistics.
* R: sample(), resample(), shuffle()

## Running Randomization Test: opportunity cost

* Repeat the complete randomization hypothesis test analysis
* Define statistical significance and significance level
   * what would the data need to be for significance?
* Define decision errors
  * Different types of errors have different consequences.
   * which error is worse?
   * what error might we have made?
* R: quantile(), count(), prop(), perc()

## Power Simulation

* Using alternative (not null) setting, define power
* Power simulation using randomization distribution
* Analysis of different aspects of power (sample size, effect size)
* R: ggplot2 - density plot, summary()

## Confidence Intervals (???)

* The original outline mentions CIs, but I'm not totally convinced that they flow nicely here.
