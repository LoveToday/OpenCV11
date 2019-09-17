# OpenCV11
形态学操作-open close

开操作-open

-先腐蚀后膨胀

-可以取消小的对象，假设对象是前景色，北京市黑色。

morphologyEx(src, dest, CV_MOP_BLACKHAT, kernel)

-Mat src -输入图像
-Mat dest -输出结果

-int OPT - CV_MOP_OPEN/CV_MOP-CLOSE/CV_MOP_GRADIENT/CV_MOP_TOPHAT/CV_MOP_BLACKHAT 形态学操作类型

int iteration 迭代次数，默认值是1
