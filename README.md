# causal-terms
Description of terms used in causality

| Term                                | Idea                                                                                                                                                                                                                                                                                     | Synonyms                                           |
| --- | --- | --- |
| Bayesian Network | Decompose a large joint distribution into several small conditional distributions based on an assumed DAG. The drawback is Bayesian Networks are oblivious to interventions on the distribution's underlying process. Deals with rung one of Pearl's Ladder of Causation |  |
| Causal Bayesian Network             | Allows for interventions but not counterfactuals. Deals with rung two of Pearl's Ladder of Causation  |  |
| Structural Causal Models            | Allows for the construction of counterfactual distributions. Deals with rung three of Pearl's Ladder of Causation |  Structural Equation Model, Functional Causal Model |
| Principle of Independent Mechanisms | Basic premise; interventions are local and intervening on a variable Xi only changes the causal mechanism Xi, leaving the other mechanisms invariant. This allows us to encode many different interventional distributions in a single graph | Autonomy, Modularity |
| Identifiability                     | A causal estimand is identifiable if it is possible to compute it from a purely statistical quantity. If it is NOT identifiable, regardless of how much data we have, we will not be able to isolate the causal association of interest in our data |  |
| Identification                      | Identification of causal estimands refers to the process of moving from the causal estimand e.g. p(y \| do(x)) to an equivalent statistical estimand e.g. p(y \| x) which we can estimate from the data |  |
