# pypy_mac_jit
this is for using pypy on mac
## installation 
this is used for mac, the other version will block by defence(TAT). https://www.pypy.org/posts/2022/11/pypy-and-conda-forge.html

## set path

## test pypy
@ ternimal 
pypy

target result would like this (Python 3.10.13 (fc59e61cfbff, Jan 14 2024, 13:00:21) [PyPy 7.3.15 with GCC Apple LLVM 13.1.6 (clang-1316.0.21.2.5)] on darwin Type "help", "copyright", "credits" or "license" for more information.)

## set env
pip install virtualenv  # env need this package to install
### create env
virtualenv -p /path/to/pypy/bin/pypy my_virtual_env  #"/path/to/pypy/" change to your path
or
conda create -c conda-forge -n my-pypy-env pypy python=3.8
### activate env
source my_virtual_env/bin/activate   #"my_virtual_env" is your env name

## install libs
pip3 install torch torchvision torchaudio
https://pytorch.org/get-started/locally/


