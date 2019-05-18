---
title: Bayesian Methods
---


#### Compare Bayesian vs frequentist statistics probability

|   |Frequentist  | |Bayesian   |   
|---|---|---|---|
|Concept |Relative frequency of an event | |Bayes theorem   |
|Information |Data | |Data + Prior |
|Data   |Vary   | |Fixed   |
|Parameters   |Fixed   | |Vary   |   
|Significance Assessment  |Null hypothesis test (Probability)   | |Direct interpretation of the posterior(Probability of meaningful hypotheses)  |  
|Uncertainty Measurement  |Confidence Interval  | |Credible Interval  |

<br>
<br>

#### What's the relationship between bayesian statistics and machine learning?
Bayesian statistics encompasses a specific class of models that could be used for machine learning. Typically, one draws on Bayesian models for one or more of a variety of reasons, such as:

* Having relatively few data points
* Having strong prior intuitions (from pre-existing observations/models) about how things work
* Having high levels of uncertainty, or a strong need to quantify the level of uncertainty about a particular model or comparison of models
* Wanting to claim something abut the likelihood of the alternative hypothesis, rather than simply accepting/rejecting the null hypothesis

Looking at this list, you might think that people would want to use Bayesian methods in machine learning all of the time. However, that’s not the case, and I suspect the relative dearth of Bayesian approaches to machine learning is due to:

Most machine learning is done in the context of “big data” where the signature of Bayesian models — priors — don’t actually play much of a role.
Sampling posterior distributions in Bayesian models is computationally expensive and slow.

<br>
<br>

---

#### References  
* [Relationship between bayesian statistics and machine learning](https://www.quora.com/Whats-the-relationship-between-bayesian-statistics-and-machine-learning)
* [Introduction to Bayesian Statistics Slides by Korner](https://slideplayer.com/slide/9158781/)
