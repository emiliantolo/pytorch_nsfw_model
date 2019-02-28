# PyTorch model for NSFW detection

## Description

This constains a PyTorch model for NSFW images detection.
It's based on a ResNet50 neural network trained on ~250k images (~40 gb of data) 

The dataset contains images of the following categories:
- `porn` - pornography images
- `hentai` - hentai images and pornographic drawings
- `sexy` - sexually explicit images, but not pornography
- `neutral` - safe for work neutral images
- `drawings` - safe for work drawings and anime

## Usage example

The repository contains a Jupiter notebook with an example code for perfoming simple inference on images to make predictions.
The directory `images` constains some sample images for running the example.

### Prerequisites

Tested on Debian 9

```
matplotlib
numpy
pillow
pytorch
torchvision
```

### Run

Enter a shell and type the following commands:

```shell
$ git clone https://github.com/emiliantolo/pytorch_nsfw_model.git
$ cd pytorch_nsfw_model
$ jupyter notebook Inference_example.ipynb
```

### Output

The output will follow this line:

![Recordit GIF](https://raw.githubusercontent.com/emiliantolo/pytorch_nsfw_model/master/Output_example.png)
