# ocr_explore
1. image.py——图像处理函数，主要是特征提取；

2. model_training.py——训练CNN单字识别模型（需要较高性能的服务器，最好有GPU加速，否则真是慢得要死）；

3. ocr.py——识别函数，包括单字分割、前面训练好的模型进行单字识别、动态规划提升效果；

4. main.py——主文件，用来调用1、3两个文件。

5. 我们的模型中包含的字.txt(UTF-8编码)


# 参考博客地址
* [OCR技术浅探：1. 全文简述](http://spaces.ac.cn/archives/3774/)
* [OCR技术浅探：2. 背景与假设](http://spaces.ac.cn/archives/3781/)
* [OCR技术浅探：3. 特征提取(1)](http://spaces.ac.cn/archives/3785/)
* [OCR技术浅探：4. 文字定位](http://spaces.ac.cn/archives/3818/)
* [OCR技术浅探：5. 文本切割](http://spaces.ac.cn/archives/3823/)
* [OCR技术浅探：6. 光学识别](http://spaces.ac.cn/archives/3831/)
* [OCR技术浅探：7. 语言模型](http://spaces.ac.cn/archives/3842/)
* [OCR技术浅探：8. 综合评估](http://spaces.ac.cn/archives/3854/)
* [OCR技术浅探：9. 代码共享(完)](http://spaces.ac.cn/archives/3856/)