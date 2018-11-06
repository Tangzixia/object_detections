# object_detections
此代码直接复制该https://gist.github.com/tarlen5/008809c3decf19313de216b9208f3734代码，
用于计算某个类别的AP值，
如果要计算多个类别的mAP，
则可以对不同类别的进行求解，然后求平均即可，
注意AP指的是对于不同置信度下的p,r，方便起见可以先对其进行排序，然后求得p,r,
p一直在降低，r一直在升高～

可以根据/methods/voc_api中看到在计算mAP的时候，我们对该类的所有图片的检测置信度进行了排序，然后进行mAP计算，
可以参考：http://blog.sina.com.cn/s/blog_9db078090102whzw.html
