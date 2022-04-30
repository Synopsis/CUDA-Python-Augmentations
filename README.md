# PyCuda-Augmentations
Test Implementations of Cinematic oriented GPU / CUDA Image Processing Augmentations for training. 


# setup

```
conda create -n cuda-python-aug python=3.7
conda activate cuda-python-aug
conda install pip
conda install -c nvidia cuda-python

#pillow simd requirements
apt-get install -y \
		pkg-config \
		python3-dev \
		libjpeg-dev \
		zlib1g-dev

pip3 install pillow-simd
pip3 install imageio
pip3 install jupyter
pip3 install numpy

```

# Usage

```
conda activate cuda-python-aug
jupyter notebook --no-browser --port=8888 --ip=0.0.0.0
```

