# Team Pandas Submission for the Problem Statement 1 - Neural Style Transfer at Satellite Imagery Track Shaastra 2023 Indian Institute of Technology (IIT), Madras .

## SAR-to-RGB-CycleGAN 🎆

This repository contains the implementation of a Cycle Generative Adversarial Network (CycleGAN) model for converting Synthetic Aperture Radar (SAR) satellite imagery to Photorealistic-RGB (PS-RGB) optical images.


### Downloading the dataset: 💽
#### Prerequisites:
- AWS Account (create one if you dont have one)
- Install awscli (Run this on bash/terminal depending on your OS)
```
pip install awscli
```
#### Procedure 🚲
- Create a data folder, inside which,Cceate 2 new directories SAR-Intensity & PS-RGB(optical images)

In SAR-Intensity folder execute:
```
aws s3 sync s3://spacenet-dataset/spacenet/SN6_buildings/train/AOI_11_Rotterdam . --exclude "*" --include "SAR-Intensity/*"
```
In PS-RGB folder execute:
```
aws s3 sync s3://spacenet-dataset/spacenet/SN6_buildings/train/AOI_11_Rotterdam . --exclude "*" --include "PS-RGB/*"
```



## Presentation: 🎬
[Link](https://pitch.com/public/07bf3b30-13b5-4e41-a50e-73ec3ee042ed)


##  Notebook Links 📙


### Data Preprocessing and Model Training

- [Notebook](./Notebooks/Final-Approach.ipynb)

- [Colab](https://colab.research.google.com/drive/16uxCb3kWBFjbrDGN6iqIR9yl5wfi7JdD?usp=sharing)

#### Generating Optical Images with Trained Model

- [Colab](https://colab.research.google.com/drive/16uxCb3kWBFjbrDGN6iqIR9yl5wfi7JdD?usp=sharing)


#### Other resources on drive 🚗
- [Model](https://drive.google.com/file/d/1-DwuJozH5IEV-D9i2EgbWrN-ORqZEH17/view?usp=sharing)

## Generated Samples (5 images as mentioned) 📸

<img src="./OutputImages/image1.png" >



<img src="./OutputImages/image2.png" >



<img src="./OutputImages/image3.png" >



<img src="./OutputImages/image4.png" >



<img src="./OutputImages/image5.png" >


<img src="./OutputImages/msedge_IFMOM950bn.png" >

<img src="./OutputImages/msedge_lRU9sQxd4K.png" >

---
<p align="center">Made with ❤️ and 💻</p>
