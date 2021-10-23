# Generating 3D models from 2D images using Deep Learning Models!!

### Problem Statement
Generating 3D models requires certain amount of information which is usually not available from 2D image files like JPG, PNG etc, thus making much more difficult to generate 3D model from 2D image. To generate 3D models we require 3 components ie: Height, Width and Depth and an 2D image consist of only 2 components that is Length and width.

Thus converting a single 2D image like a family photo into an 3D model is quite a challenging task. But if we are provided with multiple 2D images we can pre-process them to generate the missing information and generate a 3D model. The process is called [photogrammetry](https://en.wikipedia.org/wiki/Photogrammetry#:~:text=Photogrammetry%20is%20the%20science%20and,radiant%20imagery%20and%20other%20phenomena.). 

There are several documents for such methods you can check out the 3D scanning resources in the [3D Scanning guide](https://help.sketchfab.com/hc/en-us/articles/202591983-3D-Scanning-Software) and several other methods shown in this [blog](https://www.rankred.com/convert-2d-images-to-3d/).

The process of generating 3D models can still be done using some external software which requires a bit of time and patience. 

### What can we do beter?
Why not generate some AI models to reduce the redudent work done to generate 3D models from 2D images.

Let us understand different methods one can use to represent the 3D models.
- [Point Cloud](https://arxiv.org/pdf/1612.00603.pdf)
- [Voxel Representation](https://arxiv.org/pdf/1604.00449.pdf) 
- [Mesh Representation](https://arxiv.org/pdf/1804.01654.pdf)

### Leading Research going on in the field:  

- [Google Deepmind](https://deepmind.com/blog/article/neural-scene-representation-and-rendering)
- [Facebook AI : Mesh R-CNN :](https://arxiv.org/pdf/1906.02739.pdf)
- [Facebook AI : PIFuHD](https://arxiv.org/pdf/2004.00452.pdf)
- [NVIDIA](https://nv-tlabs.github.io/DIB-R/files/diff_shader.pdf)

### Reading Material: on techniques for generating 3d model from 2D images using deep learning

1. PIFuHD: 
- https://interestingengineering.com/facebooks-new-ai-tool-transforms-2d-image-to-3d-models
2. Facebook blog: 3D: 
- https://ai.facebook.com/blog/powered-by-ai-turning-any-2d-photo-into-3d-using-convolutional-neural-nets/
3. NVIDIA: 
- https://venturebeat.com/2019/12/09/nvidia-trains-ai-to-transform-2d-images-into-3d-models/
- https://nv-tlabs.github.io/DIB-R/files/diff_shader.pdf
- https://github.com/nv-tlabs/DIB-R
4. Facebook (Mesh R-CNN) : 
- https://venturebeat.com/2019/10/29/facebook-highlights-ai-that-converts-2d-objects-into-3d-shapes/
- https://ai.facebook.com/blog/pushing-state-of-the-art-in-3d-content-understanding/
- https://gkioxari.github.io/meshrcnn/
- https://github.com/facebookresearch/meshrcnn/issues

### Implementation using PyTorch model: 
- https://medium.com/vitalify-asia/create-3d-model-from-a-single-2d-image-in-pytorch-917aca00bb07
- https://github.com/lkhphuc/pytorch-3d-point-cloud-generation

### Results from PIFuHD Implementation:


![test](https://user-images.githubusercontent.com/28274170/138573199-98f8ea07-a745-438a-9ec5-ea36238ef0be.png)
![Object_in_Unity](https://user-images.githubusercontent.com/28274170/138573201-f8159268-accf-42e2-a84e-244c8ff989fe.JPG)

https://user-images.githubusercontent.com/28274170/138573267-cdcdbb9e-5407-4a84-95f9-d7fc1a1bf6a7.mp4

![result_test_256](https://user-images.githubusercontent.com/28274170/138573203-db8a5a2b-73e4-44b4-8b44-f628305fad20.png)
