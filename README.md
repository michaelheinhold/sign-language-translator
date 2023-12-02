# Neural Network to translate ASL into English

This repository includes all source code for the neural network including:
- A real-time sign language translator based on a live feed.
- Utilities used for portions of the tutorial, such as dataloaders.
- Simple convolutional neural network written in [PyTorch](http://pytorch.org), with pretrained model.

This codebase was developed and tested using `Python 3.6`. If you're familiar with Python, then see the below to skip the tutorial and get started quickly:

> (Optional) [Setup a Python virtual environment](https://www.digitalocean.com/community/tutorials/common-python-tools-using-virtualenv-installing-with-pip-and-managing-packages#a-thorough-virtualenv-how-to) with Python 3.6.

1. Install all Python dependencies.

```
pip install -r requirements.txt
```

2. Launch the script for a sign language translator:

```
python step_5_camera.py
```

created by [Alvin Wan](http://alvinwan.com), November 2019
Built using the tutorial found on [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-build-a-neural-network-to-translate-sign-language-into-english)