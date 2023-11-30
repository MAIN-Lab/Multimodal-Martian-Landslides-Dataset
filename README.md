# MarsLS-Net: Martian Landslides Segmentation Network and Benchmark Dataset
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Martian landslide segmentation is a challenging task compared to the same task on Earth. One of the reasons is that vegetation is typically lost or significantly less compared to its surroundings in the regions of landslide on Earth. In contrast, Mars is a desert planet, and there is no vegetation to aid landslide detection and segmentation. Recent work has demonstrated the strength of vision transformer (ViT) based deep learning models for various computer vision tasks. Inspired by the multi-head attention mechanism in ViT, which can model the global long range spatial correlation between local regions in the input image, we hypothesize self-attention mechanism can effectively capture pertinent contextual information for the Martian landslide segmentation task. Furthermore, considering parameter efficiency or model size is another important factor for deep learning algorithms, we construct a new feature representation block, namely Progressively Expanded Neuron Attention (PEN-Attention), to extract more relevant features with significantly fewer trainable parameters. Overall, we refer to our deep learning architecture as the Martian landslide segmentation network (MarsLS-Net). 


<p align="center">
  <img width=500 src="images/Figure_1.png">
</p>

Figure 1. Location of Valles Marineris (VM) on Mars used for landslide segmentation in this study. The elevation map of VM draped over hillshade.


## Model
<img src="images/CPLES_architecture_4.png"/>

Figure 2. Detailed illustration of the proposed C-PLES architecture


## Results

<img src="images/prediction_samples.png"/>

Figure 3. Visual comparison of multi-class Martian landslide segmentation outputs. (a) Input RGB image, (b) the segmentation mask (ground truth), (c) - (i) the segmentation outputs of experimented DL architectures: U-Net, Attention U-Net, TransUNet, R2UNet, UNet 3+, UNet++, and Swin-Unet, (j) the proposed C-PLES, respectively

<img src="images/fullmap.png"/>

Figure 4. Segmentation map of the landslides in the Martian Valles Marineris region. Four random regions are zoomed in to show in detail a comparison between the ground truth and the predicted segmentation. The IoU scores for each class are shown on the bottom right side of the figure.


## Citation

If you use [MarsLS dataset](https://github.com/MAIN-Lab/Multimodal-Martian-Landslides-Dataset) in your research, we would appreciate a citation to the original paper:

Paheding, S., Reyes, A. A., Rajaneesh, A., Sajinkumar, K. S., & Oommen, T. (2024, January). MarsLS-Net: Martian Landslides Segmentation Network and Benchmark
Dataset. Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024.

```

```

