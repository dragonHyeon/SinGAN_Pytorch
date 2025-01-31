# SinGAN_Pytorch
Reimplementing the paper "SinGAN: Learning a Generative Model from a Single Natural Image"
# Requirements
1. python3
2. torch1.1.0
3. pillow
4. numpy
5. imageio
# Training phase what you need to do
1. Modifying the image path in "train.py"
2. Executing the file "train.py"
# Testing phase what you can do
1. Random sample from single image, "random_sample_from_single.py"
2. Harmonization, "harmonization.py"
3. Creating an animation, "animation.py"
4. Converting painting to image, "harmonization.py"
# Results
|Raw img|random sampled|animation|
|-|-|-|
|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/star_raw.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/star.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/star.gif)|
|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/huashan_raw.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/huashan.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/huashan.gif)|
|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/lantingjixu_raw.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/lantingjixu.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/lantingjixu.gif)|

### Harmonization
|Raw img|n=1|n=2|n=3|n=4|
|-|-|-|-|-|
|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/star_cat.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/1.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/2.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/3.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/4.jpg)|

|Raw img|n=5|n=6|n=7|n=8|
|-|-|-|-|-|
|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/star_cat.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/5.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/6.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/7.jpg)|![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/harmonization/8.jpg)|
# Problems
The results of this code still have some problems. Sometimes, it generates the distortion image. I really don't know how to fix it.
![](https://github.com/MingtaoGuo/SinGAN_Pytorch/blob/master/IMGS/problem.jpg)

# Acknowledgement
Thanks for the [source code](https://github.com/tamarott/SinGAN) of SinGAN, it's very helpful!
# Author
Mingtao Guo

Xi'an University of technology

# Reference
[1]. Shaham, Tamar Rott, Tali Dekel, and Tomer Michaeli. "Singan: Learning a generative model from a single natural image." Proceedings of the IEEE International Conference on Computer Vision. 2019.
