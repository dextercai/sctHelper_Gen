# sctHelper_Gen
一个由sctHelper地面扇助手制作的Euroscope地面扇区数据

# 使用 How TO USE?
每一个机场文件夹中含有FREETEXT,GEO,REGION三个数据文件，其中FREETEXT一般需要加入ese文件中，其余两个文件需要加入到sct文件的[GEO]和[Region]块中。

# 注意点
由于Euroscope雷达的扇区绘制顺序，绘制有相互覆盖的情况下，小行数的数据先绘制，大行数的数据后绘制且覆盖小行数的数据。
