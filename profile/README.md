# FACTS2: Framework for Assessing Changes To Sea level 2

*THIS README IS A WORK IN PROGRESS*

FACTS2 is an open-source software ecosystem that provides a unified framework for computing and examining probabilistic projections of global mean, regional, and extreme sea-level change and its uncertainties. It is designed so users can easily explore deep uncertainty by investigating the implications on GMSL, RSL, and ESL of different choices for different processes. FACTS2 is a refactoring of the original [`facts`](https://github.com/radical-collaboration/facts) ([Kopp et al. 2023](https://doi.org/10.5194/gmd-16-7461-2023)) codebase into a more loosely coupled set of scientific modules and framework software.

## Overview

FACTS2 is made up of a suite of independent, command-line applications (or, "modules") that can be executed with `uv` or with its accompanying Docker container. Typically, these applications are linked together by `facts-experiment-builder` into a FACTS "experiment" that entails a 1. climate step, 2. sea-level step, 3. totaling step, and 4. extreme sea-level step. Most experiment steps have multiple module options from which to choose. These are:

  - climate: `fair-temperature`, `fair2-climate`
  - sea level: ....
  - totaling: `facts-total`
  - extreme sea level: `extremesealevel-pointsoverthreshold`, `extremesealevel2-AFs`
  - framework: `facts-experiment-builder`

## References
For the original FACTS description paper, see [Kopp, R. E., Garner, G. G., Hermans, T. H. J., Jha, S., Kumar, P., Reedy, A., Slangen, A. B. A., Turilli, M., Edwards, T. L., Gregory, J. M., Koubbe, G., Levermann, A., Merzky, A., Nowicki, S., Palmer, M. D., & Smith, C. (2023). The Framework for Assessing Changes To Sea-Level (FACTS) v1.0: A platform for characterizing parametric and structural uncertainty in future global, relative, and extreme sea-level change. Geoscientific Model Development, 16, 7461–7489](https://doi.org/10.5194/gmd-16-7461-2023).

<!---
## Getting started

## User guide

## Contributions

## Licenses

## How to cite
--->
