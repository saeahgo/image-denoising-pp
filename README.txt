# Supplementary Materials for Image Denoise++ Project

This folder contains the supplementary materials for the Image Denoise++ project. Below is an overview of the folder structure and file contents:

## Folders

- `train_images/`: Contains the original images used for training. 

- `test_images/`: Contains the original and noisy test images. 
  - `original/`: Original test images. 
  - `noisy/`: Noisy versions of the test images. 

## Files

- `original_train/`: Original training images (single row format). 

- `noisy_train/`: Noisy training images (single row format). 

- `original_test/`: Original test images (single row format).

- `noisy_test/`: Noisy test images (single row format).



- `denoised_bilateral/`: Images denoised using the Bilateral Filter. 

- `denoised_nl_means/`: Images denoised using the Non-local Means Filter. 

- `denoised_tv_chambolle/`: Images denoised using the Total Variation Chambolle Filter. 

- `denoised_wavelet/`: Images denoised using the Wavelet Filter. 

- `denoised_restormer/`: Images denoised using the Restormer model. 



- `rmse.png`: Table showing the RMSE values for each algorithm across all test images.

- `average_rmse.png`: Table summarizing the average RMSE values for each algorithm, used to determine the best-performing algorithm.

- `restormer_08_results.png`: Side-by-side comparison of the test image kodak_08.png:
  - Left: Noisy image 
  - Middle: Denoised image (using the Restormer Model)
  - Right: Original image 

- `restormer_09_results.png`: Another set of results following the same format.


- `Saeah Image Denoise++ Colab.pdf`: Supplementary PDF containing the Google Colab Jupyter Notebook source code with annotations. Note that this PDF does not contain all of the denoised images; please refer to the respective folders to check the output images.

- `Saeah Image Denoise++ Report.pdf`: The main project report written using the CVPR template in LaTeX, containing detailed explanations, methodology, implementation, and results.

## Notes
This supplementary material is provided to support the project and ensure reproducibility. The folder and file structure is organized for clarity and ease of navigation.