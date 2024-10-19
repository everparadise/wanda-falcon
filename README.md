# Pruning LLMs by Weights and Activations
Forked from Official PyTorch implementation of **Wanda** (Pruning by **W**eights **and a**ctivations), as presented in paper:

**A Simple and Effective Pruning Approach for Large Language Models** </br>
*Mingjie Sun\*, Zhuang Liu\*, Anna Bair, J. Zico Kolter* (* indicates equal contribution) <br>
Carnegie Mellon University, Meta AI Research and Bosch Center for AI  <br>
[Paper](https://arxiv.org/abs/2306.11695) - [Project page](https://eric-mingjie.github.io/wanda/home.html)

```bibtex
@article{sun2023wanda,
  title={A Simple and Effective Pruning Approach for Large Language Models}, 
  author={Sun, Mingjie and Liu, Zhuang and Bair, Anna and Kolter, J. Zico},
  year={2023},
  journal={arXiv preprint arXiv:2306.11695}
}
```

--- 
<p align="center">
<img src="https://user-images.githubusercontent.com/20168304/273351964-53c3807e-3453-49c5-b855-b620b1026466.png" width=100% height=100% 
class="center">
</p>


## Update
- [x] (8.24.2024) Modify to [prune Falcon-7b with mlp layer only]()
- [x] (8.28.2024) Modify to [prune Falcon-7b]()


## Acknowledgement
This repository is build upon the [locuslab/wanda](https://github.com/IST-DASLab/sparsegpt](https://github.com/locuslab/wanda)) repository.
