# PS-1-CycleGAN

## SAR-to-RGB-CycleGAN

This repository contains the implementation of a Cycle Generative Adversarial Network (CycleGAN) model for converting Synthetic Aperture Radar (SAR) satellite imagery to Photorealistic-RGB (PS-RGB) optical images.

<<<<<<< HEAD
### Downloading the dataset:
#### Prerequisites:
- AWS Account (create one if you dont have one)
- Install awscli (Run this on bash/terminal depending on your OS)
```
pip install awscli
```
#### Procedure
- Create a data floder, inside which,Cceate 2 new directories SAR-Intensity & PS-RGB(optical images)

In SAR-Intensity folder execute:
```
aws s3 sync s3://spacenet-dataset/spacenet/SN6_buildings/train/AOI_11_Rotterdam . --exclude "*" --include "SAR-Intensity/*"
```
In PS-RGB folder execute:
```
aws s3 sync s3://spacenet-dataset/spacenet/SN6_buildings/train/AOI_11_Rotterdam . --exclude "*" --include "PS-RGB/*"
```
=======
---
>>>>>>> 83d704c881c6962ac2953f1a54adc17fcc8b80a3

## Presentation:
[Link]()

---
<<<<<<< HEAD
##  Notebook Links
=======

## Colab Notebook Links
>>>>>>> 83d704c881c6962ac2953f1a54adc17fcc8b80a3

### Final Approach
[Notebook](./Notebooks/Final-Approach.ipynb) 
[Colab](https://colab.research.google.com/drive/16uxCb3kWBFjbrDGN6iqIR9yl5wfi7JdD?usp=sharing)
- Image prediction
[Notebook]
[Colab](https://colab.research.google.com/drive/16uxCb3kWBFjbrDGN6iqIR9yl5wfi7JdD?usp=sharing)
- Initial Analysis
[Colab](https://colab.research.google.com/drive/1WWUBCR1jre3hP1NDSKRpjaihsUIJJRAv?usp=sharing)
[Notebook](./Notebooks/Initial-Analysis.ipynb)
- Alternative Approach
[Notebook](./Notebooks/Alternative-Approach.ipynb)

## Model and 5 images

(./OutputImages/image1.png)
(./OutputImages/image2.png)
(./OutputImages/image3.png)
(./OutputImages/image4.png)
(./OutputImages/image5.png)