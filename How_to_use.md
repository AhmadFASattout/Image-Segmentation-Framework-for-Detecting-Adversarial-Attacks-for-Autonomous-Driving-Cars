# Image Segmentation Framework for Detecting Adversarial Attacks for Autonomous Driving Cars

# 1. The Segmented Datasets are found in the following files : 
              0CIFAR_10_Mask_Seg, 0GTSRB-8_Mask_Seg, 0MNIST_Mask_Seg.

# 2. The Jupyters notebooks for generating the UNet models for each dataset are found inside the corresponding  rar files:
              0CIFAR_10_Mask_Seg, 0GTSRB-8_Mask_Seg, 0MNIST_Mask_Seg.
# 3. Detecting_* folders for each dataset contains :

    1. OCSVM trained Models with the corresponding Jupyter notebooks.
    2. Verifier Models with the corresponding Jupyter notebooks. 
    3. Detecting_Adv_* Jupyter notebooks that generate and detect the adversarial images for each dataset.
    4. The generated adversarial images for the 11 adversarial attacks.
# 4. Note: Copy the files downloads and externals inside all Detecting_*  folders to work correctly.
# 5. Note: merge the contents of adv_examples1 and adv_examples2 files into the new folder adv_examples and copy the new folder adv_examples in this location Detecting_GTSRB --> results --> GTSRB-8_96_8dfa8_densenet --> Here, in order to make detecting_Adv_GTSRB.ipynb work successfully.

# 6. All the weights of the generated Models of the proposed detection Framework are saved for reproducing the results of the Paper.
