# DNL Training

### Known Working Environment

python=3.8

cuda=11.1

cudnn=8.0

mmcv=0.2.11

Other dependencies can be installed as in the `README.md`. For installation, first change all `AT_CHECK` to `AT_ASSERT` in `mmdet/*/src/*_cuda.cpp`. Then do

```
python setup.py build develop --user
```

