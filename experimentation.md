# Experimentation

## Intro
Experimentation has grown to be widely adopted by all major internet economy companies as a quantitative validation tool. The most well-known form of experimentation is AB Testing, where the regular version of a product (called Control) is compared against a modified version (the B Variant or the Challenger) and checked for effects on a company's guiding metrics (or Overall Evaluation Criteria, OEC). The results are then measured and teams make a decision on whether to incorporate the new changes into the main product. Typically teams will run a series of experiments, iterating on a concept, to validate (or invalidate) their hypotheses and solutions.

## When to Run
Experimentation is typically run when teams have enough traffic to empirically and scientifically test whether a change will produce the intended effects with a cohort of real users - the change's target users. Teams using experimentation should ensure they have adequate levels of traffic, they understand the problem they are trying to solve and they have ensured the impact of their changes can and should be measured through an experiment.

## Why to Run
Experimentation allows teams to assess with a pre-defined level of certainty whether a change to a product will produce its intended effect. Typically teams choose the standard level of confidence used in scientific experimentation (95%) and run the experiment for a number of business cycles on a large enough group of users to verify whether an impact is produced. This allows teams to test their assumptions cheaply, without assuming their ideas (or their execution) will work for users, spending months of development effort. It's a powerful learning tool to understand how people use a product.

## Roles
* Development team
* Users

## How to Run
* 0. Familiarize yourself with common experimentation pitfalls.
* 1. Define a hypothesis based on a known insight or customer problem - A good resource to understand how these should be formulated is the [hypothesis kit](http://www.experimentationhub.com/hypothesis-kit.html)
* 2. Establish how that hypothesis can be tested - What changes need to be made, what metrics it will affect (OEC).
* 3. Determine the Minimum Detectable Effect (MDE), the change to the metrics that can be measured within a certain timeframe (which should also be defined). A good resource is the [AB Test Guide Calculator's Pre-Test Analysis](https://abtestguide.com/calc/). Choose a two-sided test if you wish to be confident about negative effects as well. Typically, tests are run at 95% confidence (p<0.05).
* 4. Run the experiment for the defined period of time - NOT until you reach statistical significance.
* 5. Collect results and analyse them according to your OEC.
* 6. Choose to accept or reject your experiment results, incorporating them into your main codebase.

## Tips and Resources
* [Evan Miller - How not to run an A/B Test](http://www.evanmiller.org/how-not-to-run-an-ab-test.html)
* [Microsoft Experimentation](http://exp-platform.com/large-scale/)
* [Experimentation Hub](http://www.experimentationhub.com)
* [Experimentation at Airbnb]( https://medium.com/airbnb-engineering/experiments-at-airbnb-e2db3abf39e7)
* [Booking.com's Chasing Statistical Ghosts]( https://blog.booking.com/is-your-ab-testing-effort-just-chasing-statistical-ghosts.html)
* [Dan McKinley - Design for Continuous Experimentation]( http://mcfunley.com/design-for-continuous-experimentation)
* [Hilary Robert's Science and Sensibility - Thoughts on Experimentation and Growth](https://vimeo.com/189598824)

## Related plays:
