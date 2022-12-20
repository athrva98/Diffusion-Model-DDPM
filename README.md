# Diffusion-Model-DDPM
In this repository, we include some basic implementations of Diffusion models as seen in the original paper. We use the Conditional UNet architecture, and train the model on the FashionMNIST and the Stanford Cars Dataset.

# Instructions for running

1. Download the relevant Datasets (we used the Stanford Cars dataset and the FashionMNIST dataset). The stanford cars dataset can be found at [Stanford Cars](https://ai.stanford.edu/~jkrause/cars/car_dataset.html).

2. You need to have the following directories for training on the Cars dataset

    ```
    parent_dir
      |
      |---- gen_images # for the generated images
      |
      |---- model_checkpoints # for saving the model_checkpoints during training
      |
      |---- data # for the dataset (note please recheck this in the .ipynb)
      
   ```

# How to run training / inference?

For the FashionMNIST dataset, please refer to ``Code_DDPM_MNIST_Fashion.ipynb`` file and for training the larger model for the Cars dataset, please refer to the ``DDPM_cars.ipynb`` notebook. Other instructions can be found in the relevant notebooks.

# Links for the trained models.

> For the FashionMNIST dataset : [FashionMNIST model](https://drive.google.com/file/d/10XeDbPmLpgALlbB4BXJUd-vN_PPEgBqI/view?usp=sharing)
> For the Cars dataset : [Stanford Card Dataset](https://drive.google.com/file/d/1-HxXqshIfaFCchl4Or6dgeEEwzgWM9Wn/view?usp=sharing)
