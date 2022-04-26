# SuperResolution_Survey<br />
[Deep Learning for Image Super-Resolution: A Survey](https://ieeexplore.ieee.org/abstract/document/9044873)<br />
# Table of Contents
### [Super-resolution Frameworks 超分辨框架](#index0)<br />
&emsp;[Pre-upsampling ](#index00)<br />
&emsp;[Post-upsampling ](#index01)<br />
&emsp;[Progressive Upsampling ](#index02)<br />
&emsp;[Iterative Up-and-down Sampling ](#index03)<br />
### [Datasets 数据集](#index1)<br />
&emsp;[Visible Images ](#index10)<br />
&emsp;[Infrared Images ](#index11)<br />
### [Representative Models 经典模型](#index2)

<span id='index0'></span>
## Super-resolution Frameworks 超分辨框架

<span id='index00'></span>
### Pre-upsampling
[Learning a Deep Convolutional Network for Image Super-Resolution](https://ieeexplore.ieee.org/abstract/document/7115171)(SRCNN)<br />
[Memnet: A persistent memory network for image restoration](https://openaccess.thecvf.com/content_iccv_2017/html/Tai_MemNet_A_Persistent_ICCV_2017_paper.html)(MemNet)<br />
[Deeply-recursive convolutional network for image super-resolution](https://openaccess.thecvf.com/content_cvpr_2016/html/Kim_Deeply-Recursive_Convolutional_Network_CVPR_2016_paper.html)(DRCN)<br />

<span id='index01'></span>
### Post-upsampling
[Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network](https://openaccess.thecvf.com/content_cvpr_2017/html/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.html)(SRGAN)<br />

<span id='index02'></span>
### Progressive Upsampling

<span id='index03'></span>
### Iterative Up-and-down Sampling

<span id='index1'></span>
## Datasets 数据集

<span id='index10'></span>
### Visible Images 可见光图像
|Name|Amount|Format|Link|
|-|-|-|-|
|Set5|5|PNG|[Downoad](https://uofi.box.com/shared/static/kfahv87nfe8ax910l85dksyl2q212voc.zip)|
|Set14|14|PNG|[Downoad](https://uofi.box.com/shared/static/igsnfieh4lz68l926l8xbklwsnnk8we9.zip)|
|BSDS300|300|JPG|[Downoad](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/segbench/BSDS300-images.tgz)|
|BSDS500|500|JPG|[Downoad](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz)|
|DIV2K(NTIRE2017)|1000|PNG|[Website](https://data.vision.ee.ethz.ch/cvl/DIV2K/)|

<span id='index11'></span>
### Infrared Images 红外图像
|Name|Amount|Resolution|Format|Link|
|-|-|-|-|-|
|CVC-09|13184|640\*480|PNG|[Website](http://adas.cvc.uab.es/elektra/enigma-portfolio/item-1/)|
|CVC-14|31962|640\*471, 64\*128|TIF|[Website](http://adas.cvc.uab.es/elektra/enigma-portfolio/cvc-14-visible-fir-day-night-pedestrian-sequence-dataset/)|

<span id='index2'></span>
## Representative Models 经典模型
|Method|Publication|Keywords(Framkworks,  Upsampling Methods, Network Design, Learning Strategies)|
|-|-|-|
|[SRResNet](https://openaccess.thecvf.com/content_cvpr_2017/html/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.html)|2017, CVPR|Post-upsampling, Sub-pixel, Residual|
|[SRGAN](https://openaccess.thecvf.com/content_cvpr_2017/html/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.html)|2017, CVPR||
|[BSRGAN](https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Designing_a_Practical_Degradation_Model_for_Deep_Blind_Image_Super-Resolution_ICCV_2021_paper.html?ref=https://githubhelp.com)|2021, ICCV|Blind SR, Complex Degradation Model, Random Shuffle|
|[USRNet](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Deep_Unfolding_Network_for_Image_Super-Resolution_CVPR_2020_paper.html)|2020, SVPR|Integrating Model-based Method and Learning-based Method, Data Module + Prioe Module + Hyper-parameter Module|
