# Breast-Cancer-MRI-Classification

**Background:** Breast cancer has emerged as a prevalent global health concern, affecting individuals across diverse demographics. Dynamic contrast-enhanced magnetic resonance imaging (DCE-MRI) has notablyrisen as a pivotal modality for breast cancer detection, boasting superior sensitivity compared to conventional methods such as mammography or ultrasound (4). However, the reliance on gadolinium- based contrast agents poses significant challenges due to associated risks and adverse effects. These include costs, time, potential allergic reactions, and discomfort, particularly among patients with underlying health conditions like asthma or cardiovascular diseases (3). To address these challenges, this project leverages 3 generative models to produce synthetic breast MRI images and access their risk of cancer recurrence to enhance the performance of breast segmentation tasks.

**Objective:** Generate post contrast images using pix2pix and diffusion model and comparing cancer reccurance classification with raw image.


**Models Implemented:**
1. Pix2Pix
<p align="center">
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <img src="https://github.com/user-attachments/assets/9d7c1427-fab1-4a5a-b67a-297cd6615483" alt="Breast_MRI_922_pix2pix" width="400"/>
  </figure>
</p>
2. Diffusion model
<p align="center">
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <img src="https://github.com/user-attachments/assets/d5ec96c9-57aa-41e4-926c-5e0a923424f7" alt="Breast_MRI_922_diffusion" width="400"/>
  </figure>
</p>
      
3. Vision Transformer Classification Model (ViT from Hugging Face Library)
