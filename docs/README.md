# 并行与分布式计算基础(2019秋)

## 课程基本信息
> * 课程名称：并行与分布式计算基础
> * 英文名称：Foundations of Parallel and Distributed Computing
> * 授课教师：杨超（chao_yang@pku.edu.cn，理科1号楼1520）
> * 课程助教：尹鹏飞（pengfeiyin@pku.edu.cn）
> * 学分：3，周学时：3，总学时：51
> * 考核方式：平时作业(50%) + 期末考试(50%)
> * 教材：无

## 主要授课内容（待定）
> * 引言
> * 硬件体系结构
> * 并行计算模型
> * 编程与开发环境
> * MPI编程与实践
> * OpenMP编程与实践
> * GPU编程与实践
> * 前沿问题选讲

## 课件

|           |日期      |   课件
|------     |:---     |:---|
|第一讲      |2019 09 10| <a href="ppt/fpdc2019_lec01.pdf" target="_blank">fpdc2019_lec01.pdf</a>
|第二讲      |2019 09 12| <a href="ppt/fpdc2019_lec02.pdf" target="_blank">fpdc2019_lec02.pdf</a>
|第三讲(上机) |2019 09 17| <a href="ppt/fpdc2019_lec03.pdf" target="_blank">fpdc2019_lec03.pdf</a> &emsp; <a href="ppt/fpdc2019_lec03-slides.pptx" target="_blank">fpdc2019_lec03-slides.pptx</a>
|第四讲      |2019 09 24| <a href="ppt/fpdc2019_lec04.pdf" target="_blank">fpdc2019_lec04.pdf</a>
|第五讲      |2019 09 26| <a href="ppt/fpdc2019_lec05.pdf" target="_blank">fpdc2019_lec05.pdf</a> &emsp; <a href="ppt/mpi-ex1.tgz" target="_blank">mpi-ex1.tgz</a>


[^_^]: 注释

<!--
- 第一讲 2019 09 10 &emsp; &emsp;
[fpdc2019_lec01.pdf](https://www.baidu.com)

- 第二讲 2019 09 12 &emsp; &emsp;
[fpdc2019_lec02.pdf]()

- 第三讲 2019 09 17(上机) 
[fpdc2019_lec03.pdf]() &emsp;
[fpdc2019_lec03-slides.pptx]()

- 第四讲 2019 09 24 &emsp; &emsp;
[fpdc2019_lec04.pdf]()

- 第五讲 2019 09 26 &emsp; &emsp;
[fpdc2019_lec05.pdf]() &emsp;
[mpi-ex1.tgz]()
-->

## 上机代码摘要
- 第五讲 2019 09 26

```
cp /mnt/lustrefs/share/fpdc2019/mpi-ex1.tgz mpi-ex1.tgz
tar -zxvf mpi-ex1.tgz
cd mpi-ex1/
module add mpich
make
salloc mpiexec -np 4 ./hello
```
[filename](./_coverpage.md ':include :type=code :fragment=demo')




