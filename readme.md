# Deep Artistic Style Transfer

## Introduction

In this assignment, I have created a deep learning model capable of adapting an existing work to resemble the aesthetic of any art. The model analyzes the artistic style of a selected artwork and applies similar stylistic features to a new, original artwork, creating a piece that appears as though it could have been created by the artist themselves.

## Dependencies

Please install the following dependencies:

- TensorFlow
- NumPy
- Matplotlib
- OpenCV
- PIL

You can install them using the following command:

```bash
pip install tensorflow numpy matplotlib opencv-python pillow
```

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/ankush-agarwal-12/dashtoon-ankush.git
cd dashtoon-ankush
```

2. Download the VGG19 weights file:
   - [Download VGG19 Weights](https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg19_weights_tf_dim_ordering_tf_kernels.h5)
   - Save the file as `vgg19_weights_tf_dim_ordering_tf_kernels.h5` in the project directory.

3. Organize the content and style images:
   - Place the content images in the 'content' directory.
   - Place the style images in the 'styles' directory.

## Running the Notebook

1. Open the Jupyter notebook `deep_artistic_style_transfer.ipynb` using Jupyter.

2. Execute the cells in the notebook sequentially to load the VGG19 model, define loss functions, and train the style transfer model.

3. The trained model will generate artistic-style transferred images based on the provided content and style images.

## Results

You can see the generated images in te python notebook.
Submission by: Ankush Agarwal
Email: ankush.251218.agarwal@gmail.com
Roll no: 20CE10013