---
date: '1'
title: 'Shadow Removal'
cover: './shadow_2.jpg'
github: 'https://github.com/abhinavvsharma/shadow-diffusion'
external: 'https://github.com/abhinavvsharma/shadow-diffusion/blob/main/report/CV_Shadow_Removal_Report.pdf'

tech:
  - PyTorch
  - CUDA & cuDNN
  - OpenCV
  - PIL
  - NumPy
---
Implemented Diffusion Models for shadow removal tasks using two methodologies - first, using the [shadow mask](https://github.com/openai/improved-diffusion) for conditional inpainting task; without using Shadow Masks here, we use the novel [intermediate-conditional sampling](https://github.com/openai/guided-diffusion) method for shadow removal.

