# <img src="https://media.giphy.com/media/ie8wWVDkrH6dvsy4Zn/giphy.gif" width="60" height="60"/> SapphireGAN <img src=" https://media.giphy.com/media/HdYL67CqBv8Z2/giphy.gif" width="60" height="60"/>



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FabioRovai/SapphireGAN/blob/main/SapphireGAN.ipynb)




This project aims to implement some functions to the DCGan Pytorch official tutorial https://github.com/pytorch/tutorials/blob/master/beginner_source/dcgan_faces_tutorial.py


## Motivation

Making DCGANs more accessible, cutting recurring errors and avoiding problematic directory paths.


## Implementations

Easier and faster upload with a small dataset (jenner.zip, 653 elements)

Image and model saving (h5,pkl)

Image enhancer, instead having 64x64 output we can get decent size images using cv2


##Examples

Jenner.zip training set


![alt text](https://i.ibb.co/GpkpYCB/download-3.png)


600 epochs

![alt text](https://i.ibb.co/3p4g0Pj/download-2.png)



![alt text](https://i.ibb.co/GtJ458d/image-00000.png)


Super-resolution 3x

![alt text](https://i.ibb.co/bb5Jc4V/6724cd15-5597-4e1b-a57d-6e80ac9c7dd0.png)


Further super-resolution systems are being evaluated to further enhance the result.


#Final goal

![alt text](https://i.ibb.co/YQYPqFd/Screenshot-2021-03-03-at-12-30-03-auto-x2-auto-x2-auto-x2.png)



(Further enhanced at https://letsenhance.io/v2/boost)

