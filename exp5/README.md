## 环境搭建
```bash
conda create -n GNN_GCN
conda activate GNN_GCN

conda install python=3.8
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia

conda install ipykernel
conda install platformdirs
pip3 install ipywidgets
pip3 install --upgrade jupyter_core jupyter_client

python -m ipykernel install --user --name GNN_GCN
```


## 仓库参考
https://github.com/fczhang0606/4.1-Graph-Neural-Networks/tree/main
