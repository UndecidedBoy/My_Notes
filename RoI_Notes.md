## Families of RoI

### 1] Roi Pooling
Introduced in *Fast R-CNN [1]*\
**Goal?**\
Convert a *region of interest (RoI)* of a feature map into a smaller feature map with a fixed size (*H*x*W*).\

**How does it work?**\
An RoI is defined by a four tuple (*r*, *c*, *h*, *w*); where (*r*, *c*) --> Top-left corner, and (*h*, *w*) --> height, width of the rectangular shaped RoI.\
The RoI Pooling operation works by dividing the RoI window(*h*, *w*) with the pooling size (*H*, *W*). This results into a grid of size *H*x*W*, where each grid contains sub-channels of the RoI, and a Max Pooling operation occurs.

[Insert images or GIF on how this works]

Nota Bene:

### 2] Roi Align
Introduced in *Mask R-CNN [2]*\

Nota Bene:

### 3] PrROI Pooling
Introduced in *IoU-Net [3]*\

Nota Bene:

References:
[1] Girshick, Ross. "Fast r-cnn." Proceedings of the IEEE international conference on computer vision. 2015.
[2] He, Kaiming, et al. "Mask r-cnn." Proceedings of the IEEE international conference on computer vision. 2017.
[3] Jiang, Borui, et al. "Acquisition of localization confidence for accurate object detection." Proceedings of the European conference on computer vision (ECCV). 2018.

Additional Material (i.e., links):
