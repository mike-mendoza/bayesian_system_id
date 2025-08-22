# Bayesian system identification

**Bayesian updating**: Updating the parameters of a finite element model after sensor data

Can be used for: 
- System identification
- Model updating
- Model calibration



![Bayes theorem](../figures/bayestheorem.png)

Performing Bayesian system identification is hard: 
- Complex statistical methods
- High computational costs
- Programming skills

Then… why doing it?
- ✅ Theoretically consistent method to integrate measurement data with structural models
- ✅ Estimates the uncertainties of predictions rather than just giving a ‘best guess’
- ✅ Incorporates knowledge of the structure via the priors


## Typical workflow

This how a typical workflow looks like: 

![Typical workflow](../figures/workflow.png)


## Methods for Bayesian inference

In general, there are "three" main types of methods for performing Bayesian inference:

1. **Exact Methods**: 

    Exact methods provide precise solutions to Bayesian inference problems. These methods typically involve calculating the posterior distribution directly using Bayes' Theorem. They are most effective when the model is simple and the data is manageable. 

2. **Exact Methods if runs long enough**: 

    Exact methods can still be applicable in more complex scenarios if computational resources allow for longer run times. In such cases, these methods may yield accurate results, but they require significant time and processing power. This approach is often used in high-performance computing environments where resources are available.


3. **Approximate Methods**

    Approximate methods are used when exact solutions are infeasible due to complexity or high dimensionality. These methods provide estimates of the posterior distribution rather than exact values.

![Methods for Bayesian inference](../figures/methods_bayesian_inference.png)


% An admonition containing a note
:::{note}
Only  Methods 1 and 2 are cover in this crash course. 
:::