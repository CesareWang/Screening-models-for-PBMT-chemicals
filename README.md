# Screening-models-for-PBMT-chemicals
Screening Models for persistent, bio-accumulative, mobile, and toxic (PBMT) chemicals

## Getting Started

### Installation

Set up conda environment

```
# create a new environment
$ conda create --name GAT python=3.7
$ conda activate GAT

# install requirements
$ pip install ipykernel
$ pip install torch==1.8.1+cu111 torchvision==0.9.1+cu111 torchaudio===0.8.1 -f https://download.pytorch.org/whl/torch_stable.html
$ conda install -c rdkit rdkit==2019.03.1.0
```


### Dataset

You can download the data in the files under `./data` folder. 

### Screening

Screening demo can be found in `./code/screening.ipynb`, and chemicals to be predicted are stored in `./data/data_example.csv`.

