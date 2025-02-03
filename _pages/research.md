---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My name is Senan, and I am a labour economist.
I am in the 5th year of an Economics PhD at Cornell University, where I am building my dissertation.

## Work in Progress

### The Direct and Indirect Effects of Genetics and Education (2024--).

Recent advances in genetic technology measure genetic locations in the human genome associated with health and social outcomes, such as years of education --- polygenic indices.
I show how that the Education year PolyGenic Index (Ed PGI, [Lee et al 2018](https://doi.org/10.1038/s41588-018-0147-3)) is related to later-life earnings, using random variation away from parents' genes to infer causal effects.
A nascent social science literature has speculated that genes associated with education relate to intelligence, and so would have independent, direct genetic effects on labour market outcomes.
I investigate this systematically by decomposing the causal effects into a direct genetic effect, and an indirect effect from returns to education, using genetic and labour market data for thousands of members of the British public in the UK Biobank.
I use a legal change in school-leaving age to instrument for random variation in education, estimating direct and indirect effects by control function approach.
Correlational evidence with public data shows that direct genetic associations are indistinguishable from zero --- all causal associations of the Ed PGI are explained by the indirect education channel, and not by a direct genetic channel.
Causal estimates using restricted UK Biobank data are to follow.

### Causal Mediation in Natural Experiments (2024--).
[(2025).](https://github.com/shoganhennessy/mediation-natural-experiment/blob/main/mediation-natural-experiment-2025.pdf)

Natural experiments are a cornerstone of applied economics, providing settings for estimating causal effects with a compelling argument for treatment ignorability.
Causal Mediation (CM) methods aim to estimate how much of the treatment effect operates through a proposed mediator, illuminating mechanisms that causal effects operate through.
The most popular approach to CM relies on assumptions which are unrealistic in natural experiment settings: assuming the mediator is conditionally ignorable --- in addition to the causal research design for the initial treatment.
This paper shows that this approach leads to biased inference, solving for explicit bias terms when the mediator is not ignorable.
Individuals' selection based on expected gains and costs is inconsistent with mediator ignorability in a natural experiment setting, suggesting bias would be present in practice.
I consider a control function approach, which overcomes these hurdles under alternative assumptions, using cost of mediator take-up as an instrument.
Simulations confirm that this method corrects for persistent bias in conventional CM estimates, though require large sample sizes for correct inference.
This approach gives applied researchers an alternative method to estimate CM effects when they can only establish a credible argument for randomisation of the initial treatment, and not a mediator, as is common in natural experiments.


### Food Insecurity Among Military Veterans (2023--), joint with Seungmin Lee (Notre Dame), Chris Barrett, John Hoddinott (Cornell), Matthew Rabbitt (USDA)

Economics project measuring food insecurity among military veterans, using newly crafted data from the PSID to causally measure the impact of military enlistment on food insecurity outcomes.


## Working Papers

### Less Funding, More Lecturers, and Fewer Professors: Stagnating State Funding for Higher Education and its Effect on Faculty [(2024).](https://github.com/shoganhennessy/state-funding-faculty/blob/main/state-funding-faculty-2024.pdf)

Empirical economics project that causally links two recent trends:

- Public universities' substitution towards contingent lecturers and teaching faculty, away from tenure-track/tenured professors
- Stagnating state funding for US public universities.

The analysis uses a shift-share approach to show that declining state funding explains the substitution towards lecturers away from professors.
Analysis of every public university faculty member in Illinois shows that incumbent professors are unaffected, implying changes in faculty composition at public universities arise via falls in future hiring after funding cuts.

### [Market Interventions in a Large-Scale Virtual Economy (2022),](https://doi.org/10.48550/arXiv.2210.07970) joint with Peter Xenopoulos, Claudio Silva (NYU)

Study of large market interventions in an online multiplayer game's economy, and the causal effects on market activity.
Combines insights from applied econometrics and data science in the study of virtual games.
