Prediction of Compound-Protein Interactions
===========================================

Environment
-----------

- Python 3.9
    - Anaconda3-2020.11
- PyTorch 1.8.0
    - conda install -c conda-forge pytorch
- RDKit
    - conda install -c conda-forge rdkit

Usage
-----

```
$ python preprocess.py
$ python main.py
```

Hyperparameters
---------------

```
$ python main.py -h

usage: main.py [-h] [--datafile DATAFILE] [--modelfile MODELFILE]
               [--epochs EPOCHS] [--batch_size BATCH_SIZE] [--lr LR]
               [--weight_decay WEIGHT_DECAY] [--dropout DROPOUT]
               [--random_seed RANDOM_SEED] [--cpu]

optional arguments:
  -h, --help            show this help message and exit
  --datafile DATAFILE
  --modelfile MODELFILE
  --epochs EPOCHS
  --batch_size BATCH_SIZE
  --lr LR
  --weight_decay WEIGHT_DECAY
  --dropout DROPOUT
  --random_seed RANDOM_SEED
  --cpu
```
