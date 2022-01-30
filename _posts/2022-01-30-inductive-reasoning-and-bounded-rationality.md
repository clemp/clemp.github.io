---
title: "Inductive Reasoning and Bounded Rationality"
author: W. Brian Arthur
date: 2022-01-30
categories:
  - notes
tags:
  - complexity
  - research paper
completeness: 4
---
## Quick summary

Humans are not perfectly rational. The complexity of a problem, and the lack of information about how others will make their decision forces individuals to guess the behavior of others and rely on subjective intuition the make the best choice. ^504562

## Notes

Perfect rationality breaks down for two reasons: the human mind has a limit to the amount of complexity it can process about a situation, and when interacting with each other it is impossible to know for certain how anyone will behave.

In complicated, ill-defined situations humans use *inductive reasoning* to fill in the gaps of unknown information.

Humans are excellent at pattern matching and intuition, both of which yield evolutionary benefit. The idea of "evolutionary benefit" can be applied creatively to describe positive outcomes over time in many different types of system.

A person will hold several hypotheses in their mind based on simple deductions about the people they interact with and the information available to them. Each hypothesis has a *weight* corresponding to its usefullness or accuracy. These weights are constantly updated as new information comes available.

Rather than a single model of rational behavior that's held by all agents in the system, each agent uses several subjective models that are individual to them, and only maybe shared by other agents. 

### El Farol Problem

The major importance of this paper is the introduction of the *El Farol* problem and a model to explore collective actions with limited information.

The *El Farol* problem was named after a restaurant in Santa Fe, NM, with the imagined situation that there are 100 patrons who like going to the bar on a particular night. However, if more than 60 patrons show up, the bar is too crowded to be enjoyed by anyone. Each patron decides independently whether to go, and only has the information of previous week's attendence to base their decision on.

This paper proposes a few very simple agent strategies that each agent can assume and use in their decision to either go, or not go to *El Farol*, given their *inductive expectations* about the other patrons.

The importance of this paper was not the actual results of the model, but the simple model itself because it provides a template to explore many collective action problems where information is distributed and limited across a population.

## References

1. Arthur, W. B. (1994). Inductive Reasoning and Bounded Rationality. The American Economic Review, 84(2), 406–411. http://www.jstor.org/stable/2117868