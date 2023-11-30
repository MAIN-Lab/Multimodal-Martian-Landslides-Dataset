# C-PLES: Contextual Progressive Layer Expansion with Self-attention
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

In this research, we present C-PLES (Contextual Progressive Layer Expansion with Self-attention), a deep learning architecture for multi-class landslide segmentation in the Valles Marineris (VM) on Mars. 


<p align="center">
  <img width=500 src="images/Figure_1.png">
</p>

Figure 1. Location of Valles Marineris (VM) on Mars used for landslide mapping in this study. (a) The multi-modality imagery used to train the (b) proposed segmentation model. (c) The output landslide segmentation map.


## Model
<img src="images/CPLES_architecture_4.png"/>

Figure 2. Detailed illustration of the proposed C-PLES architecture


## Results

<img src="images/prediction_samples.png"/>

Figure 3. Visual comparison of multi-class Martian landslide segmentation outputs. (a) Input RGB image, (b) the segmentation mask (ground truth), (c) - (i) the segmentation outputs of experimented DL architectures: U-Net, Attention U-Net, TransUNet, R2UNet, UNet 3+, UNet++, and Swin-Unet, (j) the proposed C-PLES, respectively

<img src="images/fullmap.png"/>

Figure 4. Segmentation map of the landslides in the Martian Valles Marineris region. Four random regions are zoomed in to show in detail a comparison between the ground truth and the predicted segmentation. The IoU scores for each class are shown on the bottom right side of the figure.


## Citation

If you use [C-PLES](https://github.com/MAIN-Lab/C-PLES/) in your research, we would appreciate a citation to the original paper:

Reyes, A. A., Paheding, S., Rajaneesh, A., Sajinkumar, K. S., & Oommen, T. (2023, June). C-PLES: Contextual Progressive Layer Expansion With Self-Attention for Multi-Class Landslide Segmentation on Mars Using Multimodal Satellite Imagery. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 354–364.

```
@InProceedings{Reyes_2023_CVPR,
    author    = {Reyes, Abel A. and Paheding, Sidike and Rajaneesh, A. and Sajinkumar, K.S. and Oommen, Thomas},
    title     = {C-PLES: Contextual Progressive Layer Expansion With Self-Attention for Multi-Class Landslide Segmentation on Mars Using Multimodal Satellite Imagery},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2023},
    pages     = {354-364}
}
```

