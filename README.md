# Steg GAN analysis on PVD and DWT

3/17/2023: data preprocessing

datasets:
## datasets are categorized by image shapes

- total      # 4319 elements

- filtered_1 # 469  elements with highest count

- filtered_2 # 368  elements with second-highest count

- filtered_3 # 294  elements with third-highest count

---
3/19/2023: finish codes to generate stego images

- RGB channel histograms

- psnr value between original and stego images

---
3/21/2023: discard the original PVD functions due to the pixel information loss

- RGB channel histograms

- psnr value

---
3/27/2023: histogram analysis and generate new dataset

- SSIM for image similarity to check if the image is suitable to insert

-- divide the images into two parts, then check SSIM, find best match pairs
