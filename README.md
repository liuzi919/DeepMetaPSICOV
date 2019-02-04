# DeepMetaPSICOV 1.0
### Deep residual neural networks for protein contact prediction

Shaun M. Kandathil and David T. Jones
University College London

Requirements:
-------------
- Bash shell
- Perl5 (tested on 5.22.X and 5.16.3)
- C and C++ compilers (tested with GCC 4.8.5, 5.4.0)
- Python 2 or 3 (preferably miniconda/anaconda, as this makes the PyTorch install much easier)
- The following Python modules:
  - PyTorch 0.3.0+

On some distributions, the C++ compiler is a separate add-on package and may not be installed by default. For example, on CentOS you will need to `yum install` packages `gcc` AND `gcc-c++`.

### GPU support
If you are installing PyTorch from conda, conda should automatically detect a usable GPU and install an appropriate version.
Although not necessary for predicting contacts, for faster runtimes we recommend using a GPU.

Setup and testing:
------------------



Running:
--------


Citing:
-------
If you find DeepCov useful, please cite our paper (details to be added).
