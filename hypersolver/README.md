<p align="center"> 
<img src="media/hypersolvers.png" width="550" height="320">
</p>

<div align="center">
      
[![NeurIPS](https://img.shields.io/badge/NeurIPS-2020-red.svg?)](https://papers.nips.cc/paper/2020/hash/f1686b4badcf28d33ed632036c7ab0b8-Abstract.html)
[![License](https://img.shields.io/badge/License-Apache-black.svg?)](https://papers.nips.cc/paper/2020/hash/f1686b4badcf28d33ed632036c7ab0b8-Abstract.html)
[![arXiv](https://img.shields.io/badge/arXiv-2007.09601-purple.svg?)](https://arxiv.org/abs/2007.09601)

</div>


This code for the paper "Hypersolvers: Toward Fast Continuous-Depth Models" to appear in the Thirty-fourth Conference on Neural Information Processing Systems (NeurIPS 2020).

```The infinite--depth paradigm pioneered by Neural ODEs has launched a renaissance in the search for novel dynamical system-inspired deep learning primitives; however, their utilization in problems of non-trivial size has often proved impossible due to poor computational scalability. This work paves the way for scalable Neural ODEs with time-to-prediction comparable to traditional discrete networks. We introduce hypersolvers, neural networks designed to solve ODEs with low overhead and theoretical guarantees on accuracy. The synergistic combination of hypersolvers and Neural ODEs allows for cheap inference and unlocks a new frontier for practical application of continuous--depth models. Experimental evaluations on standard benchmarks, such as sampling for continuous normalizing flows, reveal consistent pareto efficiency over classical numerical methods.```

paper: [arXiv link](https://arxiv.org/abs/2007.09601)

<p align="center"> 
<img src="media/hypersolvers.png" width="550" height="320">
</p>

This repository contains supplementary code for the experiments described in the main text, namely regarding applications of Hypersolvers to tasks: `image_classification` and `density_estimation.`. These notebooks are designed to be self-contained.

Hypersolvers rely on [torchdyn](https://github.com/DiffEqML/torchdyn) and [torchdiffeq](https://github.com/rtqichen/torchdiffeq).

<p align="center"> 
<img src="media/hyperclass.gif" width="345" height="380">
</p>

This is a research project and not an official `DiffEqML` product. Expect bugs and sharp edges. Please help by trying it out, reporting bugs, and providing feedback!

If you find our work useful, consider citing:

```
@misc{poli2020hypersolvers,
      title={Hypersolvers: Toward Fast Continuous-Depth Models}, 
      author={Michael Poli and Stefano Massaroli and Atsushi Yamashita and Hajime Asama and Jinkyoo Park},
      year={2020},
      eprint={2007.09601},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
