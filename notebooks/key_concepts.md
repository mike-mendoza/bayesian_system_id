# Key Concepts

By understanding these key concepts, you will be able to apply Bayesian updating in practical scenarios, enhancing your analytical capabilities and decision-making skills. Let's get started!


1. **Bayes' Theorem**: The cornerstone of Bayesian updating, Bayes' Theorem mathematically describes how to update the probability of a hypothesis based on new evidence. It is expressed as:
   $$P(H|E) = \frac{P(E|H) \cdot P(H)}{P(E)}$$
   where $P(H|E)$ is the posterior probability, $P(E|H)$ is the likelihood, $P(H)$ is the prior probability, and $P(E)$ is the marginal likelihood.

2. **Prior Probability**: This represents our initial belief about a hypothesis before observing any new evidence. It reflects what we know or assume about the situation.

3. **Likelihood**: The likelihood quantifies how probable the observed evidence is, given a specific hypothesis. It helps us assess the strength of the evidence in relation to our prior beliefs.

4. **Posterior Probability**: After incorporating new evidence, the posterior probability represents our updated belief about the hypothesis. It combines the prior probability and the likelihood to provide a more informed estimate.

5. **Conjugate Priors**: In Bayesian analysis, certain prior distributions are chosen because they simplify the updating process. These are known as conjugate priors, and they lead to a posterior distribution that is in the same family as the prior.

% An admonition containing a note
:::{note}
Bayesian system identification uses Bayes’ theorem to update uncertain model parameters
:::