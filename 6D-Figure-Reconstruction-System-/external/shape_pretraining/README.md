## By:Farkad Adnan
  [link](https://github.com/FarkadAdnan/6D-Figure-Reconstruction-System-).

### Install  

```
conda activate ./env/
cd $CenterSnap_Repo
conda install -c bottler nvidiacub
conda install -c conda-forge -c fvcore -c iopath fvcore iopath
./env/bin/python -m pip install  
```

### Dataset Prepration
1. Download [object models]

2. Download NOCS [preprocess data]

```
data
├── obj_models
    ├── train
    ├── val
    ├── real_train
    ├── real_test
    ├── mug_meta.pkl
```
