# DP

DL packages installation commands for Ubuntu and Python3

python3 -m pip install --upgrade pip

pip3 install torch torchvision torchaudio

pip3 install tensorflow keras

python3 -m pip install --user jupyterlab notebook

python3 -m pip install --user ipykernel
python3 -m ipykernel install --user --name=deeplearning --display-name "Python 3.10 (Deep Learning)"

# To launch JupyterLab (modern interface)
jupyter lab

# Or to launch the classic Notebook interface
jupyter notebook

(inside jupyter notebook cell)
import torch
import tensorflow as tf
import keras

print("PyTorch Version:", torch._version_)
print("PyTorch GPU Available:", torch.cuda.is_available())
print("TensorFlow Version:", tf._version_)
print("TensorFlow GPU Available:", len(tf.config.list_physical_devices('GPU')) > 0)
print("Keras Version:", keras._version_)
