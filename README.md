# HGEMD(Heterogeneous Graph Embedding Malware Detection)
Please indicate the source and references as follows when using the code, thank you.
``` 
Gu Y., Li L., Zhang Y. Robust Android Malware Detection Based on Attributed Heterogenous Graph Embedding. In: Frontiers in Cyber Security(FCS), pp. 432-446, 2020. Communications in Computer and Information Science, vol 1286. Springer, Singapore.

for train model, run: 
``` 
python3 train.py --view multi
```

for adversarial attack, run: 
``` 
python3 attack.py jsma 50 --view multi
```

The repository is organised as follows:

- `train.py`  entry script for training model.
- `attack.py`  entry script for adversarial attack.
- `setting.py`  config file.
- `layers/` define layers used in models
- `model_zoo/` define models
- `data/` data path  
- `adv/`  adversarial attacks. jsma and fgsm
