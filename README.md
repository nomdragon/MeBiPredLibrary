# MeBiPredLibrary
An updated library for the pretrained model, MeBiPred. Designed for usage with Python 3.13+. Mebipred is a machine-learning method used to identify metal-binding protein sequences. 

## 📜 Citation
This project is a modernized reimplementation of MeBiPred. If you use it, please cite the original paper:

>Aptekmann, A. A., Buongiorno, J., Giovannelli, D., Glamoclija, M., Ferreiro, D. U., & Bromberg, Y. (2022). mebipred: identifying metal-binding potential in protein sequence. Bioinformatics, 38(14), 3532–3540. https://doi.org/10.1093/bioinformatics/btac358

Legacy package: [pypi.org/project/mymetal](https://pypi.org/project/mymetal)

## Installation 
```python
import os
os.environ["TF_USE_LEGACY_KERAS"] = "1"  # must be set before any tf/keras import
```

## Prerequisites
- Python 3.13
- `tensorflow`
- `tf_keras` (Legacy Keras 2 package)
- `biopython`

```bash
pip install tensorflow tf_keras biopython
```


## Usage 
Please refer to demonstrations included in the examples directory.

Must set environment variable before any keras import
```python
import os
os.environ["TF_USE_LEGACY_KERAS"] = "1"  
```


## License
MebiPred and this project are released under the MIT license.
