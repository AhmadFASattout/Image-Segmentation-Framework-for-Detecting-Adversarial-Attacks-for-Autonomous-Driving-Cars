# Image Segmentation Framework for Detecting Adversarial Attacks for Autonomous Driving Cars

# 1. The Segmented Datasets are found in the following files : 
              0CIFAR_10_Mask_Seg, 0GTSRB-8_Mask_Seg, 0MNIST_Mask_Seg.

# 2. The Jupyters notebooks for generating the UNet models for each dataset are found inside the corresponding  rar files:
              0CIFAR_10_Mask_Seg, 0GTSRB-8_Mask_Seg, 0MNIST_Mask_Seg.
# 3. Detecting_* folders for each dataset contains :

    1. OCSVM traind Models with the corresponding Jupyters notebooks.
    2. Verifier Models with the corresponding Jupyters notebooks. 
    3. Detecting_Adv_* Jupyter notebooks that generate and detect the adversarail images for each dataset.
    4. The generated adversrail images for the 11 adversrail attacks.
# 4. Note: Copy the files downloads and externals inside all Detecting_*  folder to work correctly.
# 5. Note: merge the contents of adv_examples1 and adv_examples2 file into new folder adv_examples and copy the new folder adv_examples in this location Detecting_GTSRB --> results --> GTSRB-8_96_8dfa8_densenet --> Here, inorder to make detecting_Adv_GTSRB.ipynb work successfully.

# 6. All the weights of the generated Models of the proposed detection Framework are saved for reproducing the results of the Paper.