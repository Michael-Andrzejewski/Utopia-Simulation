# Principle: Behavioral Design

*Certainty over severity, reward over punishment, and the Goodhart tax. A load-bearing principle for designing institutions, policy, and organizations in a robust utopia. Started 2026-06-30.*

## The claim

Behavior , of dogs, children, offenders, employees, firms, and whole societies , is shaped by its consequences, and the same small set of rules governs how well you can shape it. Operant conditioning is the everyday name; **reinforcement learning** is its mathematical formalization. Most failures of policy and management are failures to apply these rules (or failures of the one big caveat, Goodhart).

## The rules

1. **Contingency (certainty).** The consequence must reliably follow the behavior. Uncertain consequences barely shape behavior , and worse, an *intermittent* reward of bad behavior (the shoplifter who sometimes succeeds, the slot machine) is the *most* persistent reinforcement schedule there is. Uncertainty is not neutral; it can be a jackpot.
2. **Immediacy (speed).** The consequence must follow quickly. The brain credits whatever happened just before it (the dog 30 minutes later learns nothing; the annual performance review is useless feedback). In RL this is the *credit-assignment problem*.
3. **Magnitude (severity) matters least**, with sharp diminishing returns. This is why "certain + immediate + mild" beats "rare + delayed + severe" , the core of the criminal-justice finding (certainty beats severity) and the tax-compliance finding (perceived audit probability beats penalty size).
4. **Reward over punishment.** Reward *builds* the desired behavior and supplies the replacement; punishment only *suppresses*, leaves a vacuum, and has side effects , fear, avoidance of the punisher (not the behavior), hidden problems, damaged trust. Suppressed behavior returns when the punisher leaves; reward-built behavior is self-sustaining. Optimal: rich immediate reward for the desired behavior + a *mild, certain, immediate* consequence for the undesired one, weighted toward reward (differential reinforcement).
5. **Address the function; make the good path easy.** A behavior serves a need. You cannot extinguish it without supplying an alternative route to that need (feed the hungry kid; unblock the worker). *Shaping*: reward successive approximations and progress, not only finished outcomes.

## The generalization: this is incentive and institutional design

The rules scale from individuals to systems. An incentive is a reinforcement signal. The same law governs management (reward-weighted, immediate, specific feedback; psychological safety so the truth flows), tax compliance, markets, habit formation, public policy, and , literally as math , reinforcement-learning agents. A robust society is in large part a well-designed reinforcement system: arrange incentives so prosocial behavior is the easy, immediately-and-reliably-rewarded path, with mild-certain backstops, and address the functions that drive antisocial behavior.

## The caveat that ruins naive behaviorism at scale: Goodhart's law

A dog cannot game "sit." A corporation can game "build fast." When you reward a **proxy** for the goal, agents smart enough to model the rewarder optimize the proxy, not the goal: builders cut corners, police reclassify crimes, teachers teach to the test, an AI reward-hacks. **"When a measure becomes a target, it ceases to be a good measure."** This is absent in dog training and dominant in institutional design.

So the complete principle = **contingency + immediacy + reward-bias + address-the-function + defend-against-gaming.** Anti-Goodhart engineering: reward outcomes rather than proxies, use multiple cross-checking metrics, audit, and make gaming harder than doing the real thing.

## Worked applications

- **Criminal justice:** certain, swift, *modest* consequences from the first offense + treatment + opportunity (CBT, jobs, environmental fixes), escalating proportionately, never a delayed severe cliff. (See `../discussions/2020-2025-policy-evidence.md`.)
- **Management:** a manager runs a team's reinforcement system , clear expectations, immediate reward-weighted feedback, psychological safety (don't punish honesty/mistakes, or problems get hidden), unblock the good path, manage to outcomes not gameable metrics, and make the mindset shift that the job is to *multiply* people, not do the work. Warm and demanding (high care + high standards).
- **Eunomia's corporate-incentive policy** already groped toward this (tiered rewards for speed *and inspected quality* = anti-Goodhart), and toward its failure mode (speed-only bonuses get gamed).

## Open edges

- Where reward-bias is hardest: preventing rare catastrophic harm (no time to shape), and adversaries who exploit reward channels faster than you can patch them.
- The measurement problem: the more important the goal, the harder it is to measure without a gameable proxy.
