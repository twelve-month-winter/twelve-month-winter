---
title: "Beyond separability: Convergence rate of vanishing viscosity approximations to mean field games via FBSDE stability"
collection: publications
category: manuscripts
permalink: /publication/nonseparable-mfg-vv-rate
excerpt: 'This paper is about vanishing viscosity approximations to the system of PDEs to which a mean field game corresponds. We show that the vanishing viscosity approximation has a rate of convergence that is at least as fast as the classical case; namely, it is at most $\mathcal{O}(\beta^2)$.' 
date: November 2026
venue: 'Stochastic Processes and their Applications'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0304414926001936' 
citation: 'Yu, Winston and Du, Qiang and Tang, Wenpin. (2026). &quot;Beyond separability: Convergence rate of vanishing viscosity approximations to mean field games via FBSDE stability.&quot; <i>Stochastic Processes and their Applications 1</i>. 1(1).'
---
To give an informal overview: a mean field game (MFG) is a model for how a very large number of indistinguishable agents interact, when each agent is trying to minimize the amount of cost it incurs. An agent's cost often depends on both the action that the agent takes at some state and where all the other agents are (i.e. the distribution of agents). A solution to a MFG is a Nash equilibrium: one where no agent can do better by changing its action, given what all the other agents are doing.

Much of the literature assumes that the cost is "separable", meaning that it is a sum of a function of an action and a function of the distribution of agents. This is a convenient and useful assumption for proving nice properties of the MFG, such as existence and uniqueness of a solution. Unfortunately, the assumption of separability does not hold in some applications, such as certain economic models of household wealth. So, the case that this paper addresses is the non-separable case.  

Frequently, the position of each agent in an MFG is assumed to be affected by some noise with some intensity of $\beta > 0$. The reason that this assumption might be made is that introducing noise tends to make things easier (by making solutions to the MFG smoother, or by making numerical solutions easier to obtain, for instance). However, the system may not be noisy in practice, i.e. $\beta = 0$. What "vanishing viscosity approximations" means is that we approximate a noiseless system with a noisy system (one where $\beta > 0$) and let $\beta$ go to $0$. But this approximation introduces some error, which is some function of $\beta$. This paper bounds the error of that approximation as $\mathcal{O}(\beta)$.
