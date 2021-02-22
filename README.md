# PointNet

<!--- ![alt-text-1](https://github.com/Manojkl/Point_net/blob/main/data_gif/bathtub.gif "title-1") ![alt-text-2](https://github.com/Manojkl/Point_net/blob/main/data_gif/bed.gif "title-2") -->

<p float="centre">
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/bathtub.gif " width="300" alt="Girl in a jacket" title="bathtub"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/bed.gif " width="300" title="bed"/> 
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/chair.gif " width="300" title="chair"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/desk.gif " width="300" title="desk"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/dresser.gif " width="300" title="dresser"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/monitor.gif " width="300" title="monitor"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/night_stand.gif " width="300" title="Night stand"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/sofa.gif " width="300" title="sofa"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/table.gif " width="300" title="table"/>
  <img src="https://github.com/Manojkl/Point_net/blob/main/data_gif/toilet.gif " width="300" title="toilet"/>
</p>

PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation

Implemetation of Pointnet in pytorch using Modelnet10[5] dataset containing 10 classes. 

# Abstract [1]

Point cloud is an important type of geometric data structure. Due to its irregular format, most researchers transform such data to regular 3D voxel grids or collections of images. This, however, renders data unnecessarily voluminous and causes issues. In this paper, we design a novel type of neural network that directly consumes point clouds and well respects the permutation invariance of points in the input. Our network, named PointNet, provides a unified architecture for applications ranging from object classification, part segmentation, to scene semantic parsing. Though simple, PointNet is highly efficient and effective. Empirically, it shows strong performance on par or even better than state of the art. Theoretically, we provide analysis towards understanding of what the network has learnt and why the network is robust with respect to input perturbation and corruption.

# Refrence:
[1] [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/abs/1612.00593) <br>
[2] [An introduction towards 3D Computer Vision](https://medium.com/@jianshi_94445/an-introduction-towards-3d-computer-vision-71be8ce11956) <br> 
[3] [An In-Depth Look at PointNet](https://medium.com/@luis_gonzales/an-in-depth-look-at-pointnet-111d7efdaa1a) <br>
[4] [Deep Learning on Point clouds: PointNet](https://towardsdatascience.com/deep-learning-on-point-clouds-implementing-pointnet-in-google-colab-1fd65cd3a263) <br>
[5] [Modelnet dataset](https://modelnet.cs.princeton.edu/)
