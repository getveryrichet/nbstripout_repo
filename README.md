# nbstripout_repo

## How to RUN

forking this repo and following steps below will automatically delete your jupyter notebook's output when commiting ipynb file to your git repo

### 1) Install `nbstripout`

#### If you are using conda

```
conda install -c conda-forge nbstripout
```

#### If you are using python

```
pip install --upgrade nbstripout
```

### 2) Run nbstripout

```
nbstripout --install --attributes .gitattributes
```
