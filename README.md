# CV-SSD-Yolo

任务3
SSD
https://arxiv.org/abs/1512.02325
https://arleyzhang.github.io/articles/786f1ca3/
https://zhuanlan.zhihu.com/p/33544892
https://tfhub.dev/google/openimages_v4/ssd/mobilenet_v2/1
SSD是当前业界常用的一个针对低性能设备的高速one stage detection算法，更多的介绍和原理在上文的链接中已有，不再做过多阐述。
本任务要求你接触面向web端的实验性框架tf.js，尝试用tf.js搭建一个使用笔记本摄像头就能完成的SSD检测程序。SSD已经在tf.js中内置，能够直接调用模型。Tensorflow hub提供了mobilenet作基分类器在Coco2017预训练的模型：https://tfhub.dev/tensorflow/ssd_mobilenet_v2/2


任务4
Yolo是目标检测界无法绕开的优秀算法，经过了五六代的迭代，它现在已经在速度和精度上有相当的优势。它在当今业界可以代表一种实现思路，版本从v1开始更新迭代，迄今为止已经有v2、v3、v4、v5、tiny、F以及旷视科技最新推出的YoloX，总计7个主流变体。
Yolo综述：
https://zhuanlan.zhihu.com/p/136382095
Yolo V3-V4：
https://zhuanlan.zhihu.com/p/143747206
https://github.com/ultralytics/yolov3
本次任务要求从论文理解Yolo v1的核心思想，并且从v3开始实践，使用预训练模型训练一个v5模型，部署自训练模型并评估YoloX性能。
Yolo v5：
https://zhuanlan.zhihu.com/p/172121380
https://github.com/ultralytics/yolov5
Yolo x：
https://zhuanlan.zhihu.com/p/397993315
https://yolox.readthedocs.io/en/latest/
https://github.com/Megvii-BaseDetection/YOLOX
本节任务需要我们在Classification的基础上更进一步，做一个road traffic的detection网络。
跟随YoloX的自训练教程：https://github.com/Megvii-BaseDetection/YOLOX/blob/main/docs/train_custom_data.md
