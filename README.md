# realtime-face-detection

```python
conda create --name p04 python=3.6
source activate p04
conda install numpy pyyaml mkl mkl-include setuptools cmake cffi typing
python -c "import numpy;numpy.test()"
clang --version
git checkout v0.4.0
git submodule update --init
MACOSX_DEPLOYMENT_TARGET=10.13 CC=clang CXX=clang++ python setup.py install

cd test/
python run_test.py

pip install torchvision
pip install tensorflow tensorboardX
```
