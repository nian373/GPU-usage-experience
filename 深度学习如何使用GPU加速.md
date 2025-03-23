# 深度学习如何使用GPU加速

上连接：[pycharm连接服务器autodl 集显连接云服务器使用gpu加速深度学习训练_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1ZN411B7ov/?spm_id_from=333.1391.0.0)

①去[AutoDL](https://www.autodl.com/home)租赁GPU，按量计费，也可按日、周、月计费。

![image-20250323171944742](C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20250323171944742.png)

②选择镜像，就是Pytorch 和 cuda等，注意版本配对。（选错也没关系，后期可更换）

![image-20250323172027407](C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20250323172027407.png)



③采用专业版的pycharm进行远程连接（社区版的不行）

![image-20250323172217694](C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20250323172217694.png)

④学会上传数据集，和相应的py文件，用来跑模型

![image-20250323172312435](C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20250323172312435.png)



⑤在JupyterLab中，安装GPU环境中没有的包。比如Pandas、d2l等

![4277b38311070bc691647630cb003c22](C:\Users\ASUS\Documents\Tencent Files\2293856497\nt_qq\nt_data\Pic\2025-03\Ori\4277b38311070bc691647630cb003c22.png)⑥开始训练，得出结果。







tips：①使用无卡模式上传数据集，可以极大的节省经费。   ②使用按量计费时，你选定的GPU不开机，则GPU可能会被其他人使用，出现冲突需要等待，但好在可以克隆实例（比较麻烦）。   ③使用按日计费时，则不存在GPU被占用的问题，但花销较大。
