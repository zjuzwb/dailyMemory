# dailyMemory
3D-slicer：
1. https://www.slicer.org/
2. https://github.com/arcadelab/FastSAM3D_slicer
3. https://github.com/arcadelab/FastSAM3D_slicer/tree/main
3DCT:
1. 3DGR-CAR: Coronary artery reconstruction from ultra-sparse 2D X-ray views with a 3D Gaussians representation  https://github.com/windrise/3DGR-CAR
2. 3DGR-CT: Sparse-View CT Reconstruction with a 3D Gaussian Representation  https://github.com/SadVoxel/3DGR-CT
dataset：
1. x-ray: https://github.com/NeelBhowmik/xray
2. Medical dataset：https://github.com/linhandev/dataset
Pre-train model：
1. Improving Representation of High-frequency Components for Medical Foundation Models
      Frepa is proposed to address the limitations of previous medical foundation models in representing fine-grained information and high-frequency components. Frepa demonstrates that even when using a vanilla Vision Transformer (ViT), foundation models can learn more fine-grained representations through a frequency dual-component masking strategy. Additionally, the equal-histogram image-domain masking extends the Masked Autoencoder (MAE) beyond ViT to other architectures, such as scale-feature networks (e.g., Swin Transformer) and convolutional networks, without requiring modifications to the pretraining pipeline.      
      Frepa achieves substantial success in various tasks, including vessel segmentation, small lung nodule detection, and image restoration, which were previously considered highly challenging or even inapplicable for foundation models. 
      We introduce Frepa, a novel approach that significantly enhances the high-frequency capturing capability of foundation models without compromising their low-frequency representation.
      We extend the MAE beyond vanilla ViT to improve its generalizability, as well as enable pretrained 2D encoders directly deployed on volume data.
      We develop Frepa on 17 million images and validated it on 32 downstream tasks for both 2D and 3D data, without requiring fine-tuning.
      Extensive experiments demonstrate that Frepa outperforms SOTA methods on most downstream tasks, particularly those involving fine-grained information. Frepa also exhibits exceptional performance on previously unseen modalities.
      <img width="2439" height="1312" alt="image" src="https://github.com/user-attachments/assets/d5c066d3-15c0-435f-8f65-482b1ba1349c" />
      <img width="1292" height="638" alt="image" src="https://github.com/user-attachments/assets/819eb164-c11f-43b9-9837-f580f582e5d1" />


