## Reinforcement-Learning
### Improve [Softmax Deep Double Deterministic Policy Gradients](https://arxiv.org/abs/2010.09177) performance by [Evolution Strategy](https://arxiv.org/abs/1810.01222)

This repository is based on the open-source [CEM-RL](https://github.com/apourchot/CEM-RL) codebase.

### Usage

<img src='https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667' width=100 class="left">(https://colab.research.google.com/drive/1qkaq29_pvPg0XOsZEbQY2EL5FB2HRuET?usp=sharing)

To run the CEM-SD3 (single actor) algorithm in each single environment:
```
python es_grad_sd.py --use_sd3 --env <environment_name>
```

### Experiments

<img src="https://github.com/bdghuy/Reinforcement-Learning/blob/main/perf.PNG">
