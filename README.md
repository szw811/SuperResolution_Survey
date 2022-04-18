# SuperResolution_Survey
[Deep Learning for Image Super-Resolution: A Survey](https://ieeexplore.ieee.org/abstract/document/9044873)<br />
[Super-resolution Frameworks 超分辨框架](#index0)<br />
[Datasets 数据集](#index1)<br />
[Representative Models 经典模型](#index2)

<span id='index0'></span>
## Super-resolution Frameworks 超分辨框架
### Pre-upsampling
[Learning a Deep Convolutional Network for Image Super-Resolution](https://ieeexplore.ieee.org/abstract/document/7115171)(SRCNN)<br />
[Memnet: A persistent memory network for image restoration](https://openaccess.thecvf.com/content_iccv_2017/html/Tai_MemNet_A_Persistent_ICCV_2017_paper.html)(MemNet)<br />
[Deeply-recursive convolutional network for image super-resolution](https://openaccess.thecvf.com/content_cvpr_2016/html/Kim_Deeply-Recursive_Convolutional_Network_CVPR_2016_paper.html)(DRCN)<br />

### Post-upsampling
[Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network](https://openaccess.thecvf.com/content_cvpr_2017/html/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.html)(SRGAN)<br />

### Progressive Upsampling

### Iterative Up-and-down Sampling

<span id='index1'></span>
## Datasets 数据集
### Visible Images 可见光图像
|Name|Amount|Format|Link|
|-|-|-|-|
|Set5|5|PNG|[Downoad](https://uofi.box.com/shared/static/kfahv87nfe8ax910l85dksyl2q212voc.zip)|
|Set14|14|PNG|[Downoad](https://uofi.box.com/shared/static/igsnfieh4lz68l926l8xbklwsnnk8we9.zip)|
|BSDS300|300|JPG|[Downoad](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/segbench/BSDS300-images.tgz)|
|BSDS500|500|JPG|[Downoad](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz)|
|DIV2K(NTIRE2017)|1000|PNG|[Website](https://data.vision.ee.ethz.ch/cvl/DIV2K/)|
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
