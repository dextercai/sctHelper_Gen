# sctHelper_Gen
一个由sctHelper地面扇助手制作的Euroscope地面扇区数据

# 使用 How TO USE?
每一个机场文件夹中含有FREETEXT,GEO,REGION三个数据文件，其中FREETEXT一般需要加入ese文件中，其余两个文件需要加入到sct文件的[GEO]和[Region]块中。
一般由VatPRC发布的情报区扇中，ese文件与sct文件均位于 \XXXX FIR VATPRC\Data\Public\Sectors 下可见。

# 注意点
由于Euroscope雷达的扇区绘制顺序，绘制有相互覆盖的情况下，小行数的数据先绘制，大行数的数据后绘制且覆盖小行数的数据。

# 特别鸣谢
本数据制作时参考了以下作者的模拟飞行地景内的机位、机坪等相关关键数据：
 - k44 :[ZGHA](https://bbs.fscenter.cn/thread-6506-1-1.html)
 - TeruM :[ZSXZ](https://bbs.sinofsx.com/forum.php?mod=viewthread&tid=183263)
