# U-Net: Convolutional Networks for Biomedical Image Segmentation
Olaf Ronneberger, Philipp Fischer, and Thomas Brox (2015)

## Models

| Implementation | Dataset| Accuracy | Weights | Memory | Conv Ops | etc |
|---|---|---|---|---|---|---|
| Keras |   |   |  |  |   |    |
| Keras (Google Colab) | COCO |   | 31,030,658 | 124.12 MB |   |   |
| Pytorch | VOC2012 |  | 31,033,045 | 124.13MB |  | training source code [here](https://github.com/Jooong/segmentation-pytorch) |

## Tip & Trick

| name | for What | reference |
|---|---|---|
| weight map  | compensate different frequency of pixels from a certain class | - |
| elastic distortion | data augmentation | [paper - section2](http://cognitivemedium.com/assets/rmnist/Simard.pdf) |
| bicubic interpolation | per-pixel displacement | [wikipedia](https://en.wikipedia.org/wiki/Bicubic_interpolation) |
| Overlap-title | to predict the pixels in the border region of the image | - |
| weighted loss | to learn the border pixels of touching cells | - |
## Error of paper
- add this if any errors
