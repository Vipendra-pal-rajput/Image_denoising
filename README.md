# Image_denoising : Remove Noise from image [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repo let's you denoised image that have noise in images. This Repo is mainly focused on document or Notes(Printed) images.
This repo works with opencv-python 4.1.2.30 equal or grater version.

### Overview

To test your own images follow the below steps:

 1. [Original_image](/Original_image/)
	 - Original images
 2. [Denoised_image](/Denoised_image/)
 	- Output images

+  [Denoised_image](/Denoised_image/): Here i am taking input images
+  Then running python programme to check estimated_sigma for each image
+  then applying filters according to estimated_sigma value
+  and finally Replacing input images with denoised_images in same directory
+  made Original_image directory to show you what images we are denoising there is no role of Original image directory.

### Google Colab Tutorial <a href="https://colab.research.google.com/github/Vipendra-pal-rajput/Image_denoising/blob/main/Image_denoising.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
With Google Colab you can skip most of the set up steps and start test on your own images. 

### Requisites
The only hard requirement is a running version of python 3.9. To install python 3.9 go to 
- [python.org/downloads](https://www.python.org/downloads/release/python-394/) 

and follow the installation instructions. Note that this repo has only been tested with python 3.9 thus it is recommened to use either `python3.9` or latest `python version`.

To speed up training, it is recommended to use a **GPU with CUDA** support. If you want to use your own machine,for faster perform your system specification should be very high.


## Setting up Run code

Clone this repo with:
```bash
git clone https://github.com/Vipendra-pal-rajput/Image_denoising
```

To test on your own images located in [`Image_denoising/Denoised_image`](/Denoised_image/) run the `image_denoising.py` script in the root folder with:

```bash
python image_denoising.py
```

The outputs are saved in [`Image_denoising/Denoised_image`](/Denoised_image/). 

## Stay Up-to-Date

- ⭐ **star** this repo to get notifications on future improvements and
- 🍴 **fork** this repo if you like to use it as part of your own project.

![input](/Utils/input.gif)
![output](/Utils/output.gif)

## Licensing 
This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by]. This means that you are free to:

 * **Share** — copy and redistribute the material in any medium or format
 * **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

 * **Attribution** 
 
 Cite as:
 
  ```text
  @misc{Image_denoising,
    title={Image_denoising: Image denoising from Scratch},
    author={Vipendra Pal Rajput},
    year={2021},
    url={https://github.com/Vipendra-pal-rajput/Image_denoising}
  }
  ```
If your work doesn't include a citation list, simply link this [github repo](https://github.com/Vipendra-pal-rajput/Image_denoising)!
 
[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

