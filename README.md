# gym-pyro

OpenAI Gym environments for MDPs, POMDPs, and confounded-MDPs implemented as
pyro-ppl probabilistic programs.

## Installation

This package is dependent on the
[rl_parsers](https://github.com/abaisero/rl_parsers) package.  Install
`rl_parsers` first, then install the packaged in `requirements.txt`.

## Contents

This repository provides the `PyroMDP`, `PyroPOMDP`, and `PyroCMDP`
environments, whose dynamics are respectively loaded from the `.mdp`, `.pomdp`
and `.cmdp` file formats.

See [Cassandra's POMDP page](https://pomdp.org/code/pomdp-file-spec.html) for
the specifications of the POMDP file format.  The MDP and CMDP formats follow
suit.  Also see the `examples/` folder for sample files in the `.mdp`, `.pomdp`
and `.cmdp` file format.
