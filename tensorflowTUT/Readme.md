# Tensorflow 视频教程结构 (莫烦Python)
<img src='https://github.com/MorvanZhou/tutorials/blob/gh-pages/tensorflowTUT/Tensorflow%20course%20cover%20page.jpg?raw=true' height=200>

这是一个从基础开始,一层层添加难度的 Tensorflow 视频教程. 从代码的格式一直讲到如何创建多层神经网络, 和当下流行的CNN, RNN等等.
是新手入门的首选.

* 内容主要包括:
  * Tensorflow 基础;
  * Tensorboard 可视化工具;
  * 制作简单神经网络;
  * 处理分类, 回归问题, 深度学习;
  * CNN 卷积神经网络;
  * RNN 循环神经网络;
  * Autoencoder 自编码.
  
更多其它的学习[教程资源点这里](http://morvanzhou.github.io/tutorials/)

同时也需要大家的赞助一份力量, 让教学视频做得更加的优秀. (支付宝, 微信, paypal赞助请拉倒屏幕最下面~)

---

1. **Why?** [Youtube->](https://www.youtube.com/watch?v=vZ263nfbh8g&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=2), [优酷->](http://v.youku.com/v_show/id_XMTYxMzQzMDA3Mg==.html?f=27327189&o=1)
  * Tensorflow 简介
  * 在这之前, 为了打下点有关基础, 这两段简短的视频介绍都是很推荐的: <什么是机器学习> ([Youtube->](https://www.youtube.com/watch?v=YY7-VKXybjc&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin&index=1), [优酷->](http://v.youku.com/v_show/id_XMTYyMjk2NDIwOA==.html?f=27892935&o=1)) 
  * 还有这个: <什么是神经网络> ([Youtube->](https://www.youtube.com/watch?v=RSRkp8VAavQ&index=2&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin). [优酷->](http://v.youku.com/v_show/id_XMTU5NDc3MDQwOA==.html?f=27892935&o=1))
  

2. **安装** [Youtube->](https://www.youtube.com/watch?v=pk6sAg2M-fU&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=3), [优酷->](http://v.youku.com/v_show/id_XMTYxMzQzMjEyNA==.html?f=27327189&o=1)
  * 介绍如何安装和安装时的限制
  


3. **例子1** [Youtube->](https://www.youtube.com/watch?v=tM4z02cDNa4&index=4&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYxMzQzNDc5Ng==.html?f=27327189&from=y1.2-3.4.4&spm=a2h0j.8191423.item_XMTYxMzQzNDc5Ng==.A)
  * 用一个线性回归的例子来说明神经网络究竟在干什么. 我们还可视化了整个学习的过程. 代码和实现我们会在[例子3](https://www.youtube.com/watch?v=FTR36h-LKcY&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=11)中慢慢说.
  


4. **处理结构** [Youtube->](https://www.youtube.com/watch?v=9l_c5260JQ8&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=5), [优酷->](http://v.youku.com/v_show/id_XMTYxMzQ1NzUwOA==.html?f=27327189&o=1)
  * Tensorflow 的处理,代码结构可能和我们想象得不一样. 我们需要先定义好整个 graph, 也就是神经网络的框架,才能开始运算.
  


5. **例子2** [Youtube->](https://www.youtube.com/watch?v=JKR1Dxinwwc&index=6&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYxMzQ2NzE0OA==.html?f=27327189&o=1)
  * 这个例子是我们第一个开始将代码的例子. 我们来熟悉一下 tf 的代码吧. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf5_example2)
  


6. **Session 会话控制** [Youtube->](https://www.youtube.com/watch?v=HhjtJ73AwIY&index=7&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYxMzYzNTc2OA==.html?f=27327189&o=1)
  * Session 是 tf 的主要结构之一, 他骑着控制整个运算结构的功能. 
  * [代码](https://github.com/MorvanZhou/tutorials/blob/master/tensorflowTUT/tensorflow6_session.py)
  


7. **Variable 变量** [Youtube->](https://www.youtube.com/watch?v=jGxK7gfglrI&index=8&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYxMzY2MDM2OA==.html?f=27327189&o=1)
  * 我们会把 weights 还有 biases 当做变量来储存, 更新. 这个是介绍 variable 的基本使用方法. 
  * [代码](https://github.com/MorvanZhou/tutorials/blob/master/tensorflowTUT/tensorflow7_variable.py)
  


8. **Placeholder 传入值** [Youtube->](https://www.youtube.com/watch?v=fCWbRboJ4Rs&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=9), [优酷->](http://v.youku.com/v_show/id_XMTYxMzY5NzI4MA==.html?f=27327189&o=1)
  * 定义好的神经网络结构, 我们就能用 placeholder 当作数据的接收口, 一次次传入数据. 
  * [代码](https://github.com/MorvanZhou/tutorials/blob/master/tensorflowTUT/tensorflow8_feeds.py)
  


9. **激励函数** [Youtube->](https://www.youtube.com/watch?v=6gbGCxBGxZA&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=10), [优酷->](http://v.youku.com/v_show/id_XMTU5NjA2MTk0MA==.html?f=27327189&o=1)
  * 请参考在 <机器学习-简介系列> 中 激励函数的简短介绍 ([Youtube->](https://www.youtube.com/watch?v=tI9AbaBfnPc&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin&index=9), [优酷->](http://v.youku.com/v_show/id_XMTcxMTExNjA5Mg==.html?f=27892935&o=1))
  


10. **例子3 添加神经层** [Youtube->](https://www.youtube.com/watch?v=FTR36h-LKcY&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=11), [优酷->](http://v.youku.com/v_show/id_XMTU5NjEzOTA4NA==.html?f=27327189&o=1)
  * 用简单的函数做一个添加神经层的功能, 以后再不断套用这个功能 
  * [代码](https://github.com/MorvanZhou/tutorials/blob/master/tensorflowTUT/tensorflow10_def_add_layer.py)
  


11. **例子3 建造神经网络** [Youtube->](https://www.youtube.com/watch?v=S9wBMi2B4Ss&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=12), [优酷->](http://v.youku.com/v_show/id_XMTU5OTA5NDI1Mg==.html?f=27327189&o=1)
  * 运用上上次的添加层功能, 开始搭建神经网络. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf11_build_network)
  


12. **例子3 结果可视化** [Youtube->](https://www.youtube.com/watch?v=nhn8B0pM9ls&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=13), [优酷->](http://v.youku.com/v_show/id_XMTU5OTQzOTMzNg==.html?f=27327189&o=1)
  * 对于怎个例子3的学习步骤的可视化教程. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf12_plot_result)
  


13. **Optimizer 优化器** [Youtube->](https://www.youtube.com/watch?v=9BmaWixFwj8&index=14&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYwMzk1NDM4OA==.html?f=27327189&o=1)
  * 请参考在 <机器学习-简介系列> 中对优化器的简短介绍 ([Youtube->](https://www.youtube.com/watch?v=UlUGGB7akfE&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin&index=11), [优酷->](http://v.youku.com/v_show/id_XMTc2MjA0ODQyOA==.html?f=27892935&o=1))
  


14. **Tensorboard1 可视化好帮手** [Youtube->](https://www.youtube.com/watch?v=SDeQRRRMUHU&index=15&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYxMTYwMjEwMA==.html?f=27327189&o=1)
  * 神经网络结构和参数, 数据的可视化. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf14_tensorboard)
  


15. **Tensorboard2 可视化好帮手** [Youtube->](https://www.youtube.com/watch?v=L-RDrbYNWDk&index=16&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8), [优酷->](http://v.youku.com/v_show/id_XMTYxMTcxODYyMA==.html?f=27327189&o=1)
  * 同上. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf15_tensorboard)
  


16. **Classification 分类神经网络** [Youtube->](https://www.youtube.com/watch?v=aNjdw9w_Qyc&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=17), [优酷->](http://v.youku.com/v_show/id_XMTYxMjQ2NTYyNA==.html?f=27327189&o=1)
  * 搭建一个用于分类的神经网络. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf16_classification)
  


17. **Dropout 过拟合问题** [Youtube->](https://www.youtube.com/watch?v=f2F9Xsd7KVk&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=18), [优酷->](http://v.youku.com/v_show/id_XMTYxODI2Mzk5Ng==.html?f=27327189&o=1)
  * 请参考在 <机器学习-简介系列> 中对过拟合的简短介绍 ([Youtube->](https://www.youtube.com/watch?v=e9OKufD6lRM&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin&index=10), [优酷->](http://v.youku.com/v_show/id_XMTczNjA2Nzc5Ng==.html?f=27892935&o=1)). 
  * 这节实现了用 dropout 解决过拟合的途径. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf17_dropout)
  


18. **CNN 1 卷积神经网络** [Youtube->](https://www.youtube.com/watch?v=tjcgL5RIdTM&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=19), [优酷->](http://v.youku.com/v_show/id_XMTYyMTUyMjc0OA==.html?f=27327189&o=1)
  * 请参考 <机器学习-简介系列> 中对 CNN 的简短介绍 ([Youtube->](https://www.youtube.com/watch?v=hMIZ85t9r9A&index=3&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin), [优酷->](http://v.youku.com/v_show/id_XMTY4MzAyNTc4NA==.html?f=27892935&o=1))
  


19. **CNN 2 卷积神经网络** [Youtube->](https://www.youtube.com/watch?v=JCBe_yjDmY8&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=20), [优酷->](http://v.youku.com/v_show/id_XMTYyMTY1MjMwOA==.html?f=27327189&o=1)
  * 代码部分. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf18_CNN2)
  


20. **CNN 3 卷积神经网络** [Youtube->](https://www.youtube.com/watch?v=pjjH2dGGwwY&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=21), [优酷->](http://v.youku.com/v_show/id_XMTYyMTc3ODc0OA==.html?f=27327189&o=1)
  * 代码部分. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf18_CNN3)
  


21. **Saver 保存参数** [Youtube->](https://www.youtube.com/watch?v=R-22pnDezHU&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=22), [优酷->](http://v.youku.com/v_show/id_XMTYyNzE2MDUwOA==.html?f=27327189&o=1)
  * 训练好了以后, 我们可以保存这些 weights 和 biases 的参数,避免重复训练. 
  * [代码](https://github.com/MorvanZhou/tutorials/blob/master/tensorflowTUT/tf19_saver.py)
  


22. **RNN 循环神经网络** [Youtube->](https://www.youtube.com/watch?v=i-cd3wzsHtw&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=23), [优酷->](http://v.youku.com/v_show/id_XMTcyNjE0ODM4MA==.html?f=27327189&o=1)
  * 请参考在 <机器学习-简介系列> 中对 RNN 的4分钟介绍 ([Youtube->](https://www.youtube.com/watch?v=EEtf4kNsk7Q&index=4&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin), [优酷->](http://v.youku.com/v_show/id_XMTcyNzYwNjU1Ng==.html?f=27892935&o=1)). 
  * 同时还请参考 <机器学习-简介系列> 中对 LSTM 的4分钟介绍 ([Youtube->](https://www.youtube.com/watch?v=Vdg5zlZAXnU&index=5&list=PLXO45tsB95cIFm8Y8vMkNNPPXAtYXwKin), [优酷->](http://v.youku.com/v_show/id_XMTc0MzY5MTQxMg==.html?f=27892935&o=1))
  


23. **RNN LSTM 例子1 分类** [Youtube->](https://www.youtube.com/watch?v=IASyrQamTQk&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=24), [优酷->](http://v.youku.com/v_show/id_XMTcyNjE5ODU3Mg==.html?f=27327189&o=1)
  * 使用LSTM RNN 做 MNIST 图片集的分类问题. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf20_RNN2)
  


24. **RNN LSTM 例子2 回归** [Youtube->](https://www.youtube.com/watch?v=nMLPYT_SMRo&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=25), [优酷->](http://v.youku.com/v_show/id_XMTczMDY5Mjc5Ng==.html?f=27327189&o=1)
  * 使用LSTM RNN 做 sin, cos 曲线的回归问题. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf20_RNN2.2)
  


25. **RNN LSTM 例子2 回归的学习过程可视化** [Youtube->](https://www.youtube.com/watch?v=V-pvtUThhNE&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=26), [优酷->](http://v.youku.com/v_show/id_XMTczMDcxMjEwNA==.html?f=27327189&o=1)
  * 对于上面的例子的训练可视化. 
  * 代码同上
 
26. **Autoencoder 神经网络非监督学习** [Youtube->](https://www.youtube.com/watch?v=F2h3tbC-sBk&list=PLXO45tsB95cKI5AIlf5TxxFPzb-0zeVZ8&index=27), [优酷->](http://v.youku.com/v_show/id_XMTc3NjQ4NjE0OA==.html?f=27327189&o=1)
  * 使用 Autoencoder 达到非监督学习的目的. 
  * [代码](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT/tf21_autoencoder)

---

## 赞助, 让教学变得更好
支付宝赞助:<img src='https://github.com/MorvanZhou/tutorials/blob/gh-pages/Donation/zhifubao.jpeg?raw=true' height='200'>    微信赞助:<img src='https://github.com/MorvanZhou/tutorials/blob/gh-pages/Donation/WechatIMG1.png?raw=true' height='200'>   Paypal赞助: [![paypal](https://www.paypalobjects.com/zh_XC/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=morvanzhou%40gmail%2ecom&lc=C2&item_name=MorvanPython&currency_code=AUD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)
