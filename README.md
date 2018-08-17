# TF_basic

## Install tensorflow 

### 1. Set up a virtual environment 

First, make a new virtual envornment with name `tf10`.
```
python3 -m venv ~/tf10
```

Next, activate it 
```
source ~/tf10/bin/activate
```

### 2. Upgrade `pip` 
```
pip install --upgrade pip
```

Output should look something like this.
```
Collecting pip
  Downloading https://files.pythonhosted.org/packages/5f/25/e52d3f31441505a5f3af41213346e5b6c221c9e086a166f3703d2ddaf940/pip-18.0-py2.py3-none-any.whl (1.3MB)
    100% |████████████████████████████████| 1.3MB 120kB/s 
Installing collected packages: pip
  Found existing installation: pip 9.0.3
    Uninstalling pip-9.0.3:
      Successfully uninstalled pip-9.0.3
Successfully installed pip-18.0
```

### 3. Install Tensorflow

Without GPU, 
```
pip install tensorflow
```

With GPU,
```
pip install tensorflow-gpu
```

Output should look something like this.
```
Collecting tensorflow
  Downloading https://files.pythonhosted.org/packages/9d/68/48b43857933875ae0a7a149d1e66dbdbef62a4a571da4c0c88c1311fdb5b/tensorflow-1.10.0-cp36-cp36m-macosx_10_11_x86_64.whl (55.5MB)
    8% |██▊                             | 4.8MB 173kB/s eta 0:04:53
```
