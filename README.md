# ESPCN

ESPCN is the first convolutional neural network (CNN) capable of real-time SR of 1080p videos on a single K2 GPU. To achieve this, a novel CNN architecture is proposed where the feature maps are extracted in the LR space. In addition, an efficient sub-pixel convolution layer which learns an array of upscaling filters to upscale the final LR feature maps into the HR output is proposed which solves the problems with deconvolution. The results are significantly better than traditional bicubic upsampling.
