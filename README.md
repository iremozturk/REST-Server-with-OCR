# REST-Server-with-OCR

### Recommended working environment:
PaddlePaddle >= 2.1.2
Python 3.8
CUDA 10.1 / CUDA 10.2
cuDNN 7.6

### Install Anaconda
Note: To use PaddlePaddle you need to install python environment first, here I used python integrated environment Anaconda toolkit

Anaconda is a common python package manager
After installing Anaconda, you can install the python environment, as well as numpy and other required toolkit environment.
Create a new Conda environment
```
# Enter the following command at the command line to create an environment named paddle_env
# Here to speed up the download, use the Tsinghua source
conda create --name paddle_env python=3.8 --channel https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/ # This is a one line command
```
Depending on the state of the network, this command will construct an executable environment using Python version 3.8 called paddle env.

After that, a prompt from the command line will appear; press Y and Enter to continue the installation.

```
# Activate the paddle_env environment
conda activate paddle_env
# View the current location of python
where python
```
The above anaconda environment and python environment are installed
