# audio_ML_demo

Run `python -m pip install -r requirements.txt` to install the python dependencies for the demos. 

## UrbanSound8k

Audio demos done with the UrbanSound8k dataset <https://urbansounddataset.weebly.com/urbansound8k.html>

The dataset includes 8732 labeled sound excerpts of urban sounds from 10 classes.

To run the demos below, create a data directory to the project root with contents 
```bash
data
└── UrbanSound8K
    ├── fold1
    ├── fold10
    ├── fold2
    ├── fold3
    ├── fold4
    ├── fold5
    ├── fold6
    ├── fold7
    ├── fold8
    ├── fold9
    └── metadata
        └── UrbanSound8K.csv
```

### Classification demo

Built and trained a neural network that can classify sounds from the dataset, following this article <https://towardsdatascience.com/audio-deep-learning-made-simple-part-1-state-of-the-art-techniques-da1d3dff2504> with slight modifications.

### Generative demo

Use LSTM to create a neural network that can generate sounds based on the data it was trained on. [TODO]
