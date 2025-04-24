# Image-Segmentation-Framework-for-Detecting-Adversarial-Attacks-for-Autonomous-Driving-Cars
This is a GitHub implementaion of our paper titled "Image Segmentation Framework for Detecting Adversarial Attacks for Autonomous Driving Cars".

# The Goal of this GitHub:
* To let the researchers reproduce the same results of our paper.
* The development of more advanced adversarial detection methods based on our updated code and framework will be easier and faster.


Generating adversarial attacks was based on **Feature Squeezing** code with updating the code to work using Python 3.6. Please

**Feature Squeezing**
```
@inproceedings{xu2018feature,
  title={{Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks}},
  author={Xu, Weilin and Evans, David and Qi, Yanjun},
  booktitle={Proceedings of the 2018 Network and Distributed Systems Security Symposium (NDSS)},
  year={2018}
}
```

## 1. Install dependencies.

Please install all the required Python packages from the Yaml files and create two different environments.
spd_adv_env.Yaml representing the required Python packages to run eleven Attacks on the MNIST, CIFAR-10, and GTSRB-8 datasets.
tensorenv_adv_env.Yaml representing the required Python packages to run our adversarial detection framework.

## 2. Follow How_to_Use.md file to set up the detection Method.

## Cite this work
@Article{app15031328,
AUTHOR = {Sattout, Ahmad Fakhr Aldeen and Chehab, Ali and Mohanna, Ammar and Tajeddine, Razane},
TITLE = {Image Segmentation Framework for Detecting Adversarial Attacks for Autonomous Driving Cars},
JOURNAL = {Applied Sciences},
VOLUME = {15},
YEAR = {2025},
NUMBER = {3},
ARTICLE-NUMBER = {1328},
URL = https://www.mdpi.com/2076-3417/15/3/1328,
ISSN = {2076-3417},
DOI = {10.3390/app15031328}
}
