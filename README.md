# BONC仪表读数大赛-使用深度学习读取仪表盘数值
------------------------------------------
## 工程结构介绍：
* scripts目录下:
  * data_augmentation.ipynb脚本为数据增强脚本，用于图片分割、landmark标注等。
  * CNN-model.ipynb脚本为模型定义脚本，存放模型以及部分预处理、推理代码。
* example目录下：
  * origin_annotate.csv为data_augmentation.ipynb自动生成的landmark标注文件实例。
## 样本数据集：
来自[BONC Cloudiip工业仪表表盘读数大赛](http://www.turingtopia.com/competitionnew/detail/53aa39e8d46048d8a4de2c6d21adafb1/sketch)
* [Google Drive的数据集下载地址](https://drive.google.com/drive/folders/13mCXyg8BRs91phxNCfyCeoIcW23hXp67?usp=sharing)
## 使用方法：
  直接git clone，然后将scripts代码和原始数据集(存放于目录：BONC/)放在一个文件夹内即可。
### 注意：项目在Colab中开发，因此部分代码根据Colab环境做了适配。
参见Colab项目文件：
* [Colab:卷积网络模型](https://drive.google.com/file/d/1ydyJOyZ7qVOCXY5sI2fRGlBy-1gBa5QV/view?usp=sharing)
* [Colab:数据增强脚本](https://drive.google.com/file/d/1OHfB9g0Bn4dZrbQQev0OIyPBroWLrjq4/view?usp=sharing)

