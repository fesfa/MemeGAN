# MemeData-2020
## 详细
MemeData-2020是一个国内社交用户的常用表情包数据集，主要包括熊猫头、蘑菇头两种类型的表情包。每个样本去除了图中文字部分和其他干扰部分，整个数据集分为训练集和测试集。训练集包括512个样本，测试集包括70个样本。每个样本包括一张全局的表情包图像，一条包含14个特征的文本标注，每张表情包图像拆分为头型、五官、上半身、下半身、左手和右手6个部分，每个部分图像与全局图像的文件名相对应。测试集中图像同样有6个部分，另外每张图像有一个包含1条与图片对应的文本标注和4条不匹配的文本标注的文本池。
## 样本图片
#### 蘑菇头
![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_global.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_global.jpg)   
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;全局&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;全局  
![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_head.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_face.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_upbody.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_head.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_face.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_upbody.jpg)  
&emsp;&emsp;&emsp;&emsp;头型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;脸型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;上半身&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;头型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;脸型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;上半身  
![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_downbody.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_lefthand.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/453_righthand.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_downbody.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_lefthand.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/026_righthand.jpg)  
&emsp;&emsp;&emsp;&emsp;下半身&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;左手&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;右手&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;下半身&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;左手&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;右手     
#### 熊猫头
![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_global.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_global.jpg)  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;全局&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;全局  
![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_head.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_face.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_upbody.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_head.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_face.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_upbody.jpg)  
&emsp;&emsp;&emsp;&emsp;头型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;脸型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;上半身&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;头型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;脸型&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;上半身  
![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_downbody.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_lefthand.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/110_righthand.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_downbody.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_lefthand.jpg)  ![Image text](https://github.com/fesfa/MemeGAN/blob/main/images/319_righthand.jpg)  
&emsp;&emsp;&emsp;&emsp;下半身&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;左手&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;右手&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;下半身&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;左手&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;右手        
## 训练集下载
[MemeData-2020](https://github.com/fesfa/MemeGAN/blob/main/MemeData-2020.rar)
## 测试集下载
[MemeData-2020-eval](https://github.com/fesfa/MemeGAN/blob/main/MemeGAN-2020-eval.rar)
## 联系我们
更多请联系lixiaorui@mail.ynu.edu.cn咨询有关该数据集的问题
