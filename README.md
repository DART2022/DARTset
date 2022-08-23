# DARTset

This is the toolkit for the DARTset project.

To visualize the data, please follow the instructions:

## Environment

Please make sure you have the following dependencies installed:
* numpy
* cv2
* pytorch
* pytorch3d (>= 0.6)
* [manotorch](https://github.com/lixiny/manotorch.git)



## Data

Please download the data from [train]() and [test]() and put them in the `data/DARTset` folder.

Then download [mano](https://mano.is.tue.mpg.de) from the official website and put it in the `assets` folder.

Your directory should look like this:

```shell
.
├── DARTset.py
├── DARTset_utils.py
├── assets
│   └── mano_v1_2
├── data
│   └── DARTset
│       ├── train
│       │   ├── 0
│       │   ├── 0_wbg
│       │   ├── part_0.pkl
│       │   |-- ...
│       └── test
```

## Visualization

```python
python DARTset.py
```

You can modify Line165 in DARTset.py to change the `train/test` data split.