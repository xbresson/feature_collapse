# Feature Collapse
https://arxiv.org/pdf/2305.16162.pdf


<br>

## Python environment

conda create --name pytorch_env python=3.8 pip -y  
conda activate pytorch_env  
conda install pytorch pytorch-cuda=11.7 -c pytorch -c nvidia  
conda install -c conda-forge scikit-learn -y  
conda install -c conda-forge matplotlib-base -y  
conda install jupyter ipython -y  
jupyter notebook


<br>

## Experiments

Run the repo notebooks to reproduce figure 3, figure 4a, figure 4b and figure 4c of the paper.

<br>


## Citation

```
@misc{laurent2023featcollapse,
      title={Feature Collapse}, 
      author={Thomas Laurent and James von Brecht and Xavier Bresson},
      year={2023},
      booktitle={https://arxiv.org/abs/2305.16162}
}
```
