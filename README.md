# Model-Based Co-Training for Multi-Agent Reinforcement Learning

Opponent-aware, model-based co-training for multi-agent reinforcement learning.
The project studies how an agent can keep improving while the other agents in
its environment are also learning and changing.

## Idea

- Multi-agent environments are non-stationary: a policy trained against today's
  opponents can become stale as those opponents adapt.
- The method co-trains a latent model of the other agents' strategies alongside
  the policy.
- Planning then uses that learned opponent model instead of treating other
  agents as fixed environment dynamics.

## Status

Collaborative research project; manuscript in preparation. Code and results will
be released with the paper.

## Links

- Project page: [raj-singh.com/projects/model-based-cotraining](https://raj-singh.com/projects/model-based-cotraining)
- Author: [Rajdeep Singh](https://raj-singh.com)
