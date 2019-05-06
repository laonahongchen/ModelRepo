# ModelRepo
> reproduce RL or Multi-Agent models

## Structure

`lib` contains environments designed for (Deep) RL and multi-agent RL tasks and dependency files, e.g, `lib/ma_env` is a particle environment developed by OpenAI. All algorithms listed below are implemented independently in different sub-directory.

## Guides

**[NFSP (Neural Fictitious Self-Play)](https://github.com/KornbergFresnel/ModelRepo/tree/master/NFSP)**

> NFSP is a framework for improving the performance of deep reinforcement learning tasks. You can get more details in 👇 

- arxiv link: [Deep Reinforcement Learning from Self-Play in Imperfect-Information Games](http://arxiv.org/abs/1603.01121)

- the work of implemenation is still in process ...

**[Multi-Agent Deep Deterministic Policy Gradient](https://github.com/KornbergFresnel/ModelRepo/tree/master/MADDPG)**

> A multi-agent determinstic policy gradient framework is proposed by *Ryan Lowe* and *Yi Wu* at 2017 which solves the non-stationary problem at trianing stage. Reading more by visiting 👇 arxiv link. This implementation supports gym-based multi-agent environments.

- arxiv link: [Multi-Agent Actor-Critic Mixed Cooperative-Competitive Environments](https://arxiv.org/abs/1706.02275)

- run `run.py` do traninig task, get more information about executation: `python run.py -h`

- if you wanna try different parameters configuration, you can modify the `config.py`


**[CommNet: Learning Multiagent Communication with Backpropagation](https://github.com/KornbergFresnel/ModelRepo/tree/master/CommNet)**

> A simple multi-agent communication framework proposed by *Sainbayar Sukhbaatar*, *Arthur Szlam* and *Rob Fergus* at 2016.

- arxiv link: [Learning Multiagent Communication with Backpropagation](https://arxiv.org/abs/1605.07736)

- run `leaver_train.py` to do training task, and you can also visit [KornbergFrsnel: CommNet](https://github.com/KornbergFresnel/CommNet) directly to get more information

- the paper has several different playgrounds, while there has only *Leaver* implemented in this repo so far (maybe I will add more playgrouds, but who knows.)
