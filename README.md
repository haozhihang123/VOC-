# VOC-
VOC数据集制作脚本：
本人在制作ＶＯＣ数据集时，由于用手机拍的图片，所以每张图尺寸太大，不利于训练，所以用resize_pic.py重新统一了图片的尺寸

然后用ｌａｂｍａｐ标记图像，标记好后用shwo_poly_myself.py将原始图片和标注信息整合，查看是否有问题

用mean.py计算图像均值

最后用creat_file.py生成用于训练的训练集txt，测试集txt和验证集txt。此文件和三个ＶＯＣ文件平级（Annotations,ImageSets,JPEGImages）
生成的txt文件存放在ImageSets/Main文件下

