# Image expansion with GANs
In this project, we are presenting a deep learning approach for adversarially training
neural networks to naturally expend image boundaries. We use a three-phase training schedule to
stably train a DCGAN architecture on a subset of the Places365 dataset. Once trained, our model
is able to expend 128 × 128 color images relatively realistically, thus allowing for recursive
expansion.

# Install Requirement

```
sudo apt-get install curl
sudo pip3 install -r requirements.txt
```
# Get Started

1. Download and prepare data:

```
./prepare_data.sh
```

2. Training the model:

```
python image_expansion_main.py
```

## Built With

* [Keras](https://www.tensorflow.org/guide/keras)
* [TensorFlow](https://www.tensorflow.org)
* [OpenCV](https://opencv.org)
