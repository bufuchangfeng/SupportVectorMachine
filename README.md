# 使用numpy实现svm

## 数据

* mnist_all.mat                         mnist手写数字识别数据集

## 模型

* kernel svm

## 说明

实现了非线性支持向量机，并通过one vs one和one vs rest两种方法将二分类的svm扩展到了多分类。
选取mnist的部分数据集进行训练、验证和测试。

其中，one vs rest在1000张mnist图片上的分类准确率为0.865, 用几乎相同的方法使用sklearn中的svm接口进行测试，准确率为0.868。因此认为这个svm的实现可以接受。
one vs one在1000张mnist图片上的分类准确率为0.87，没有进行对比实验。

欢迎star、fork和纠错。