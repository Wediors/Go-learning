# Go-learning
go-learning --将之前学习go语言开发/改造扫描器的过程记录下来

这里主要是我学习GO的过程，学习的书籍是雨痕老师写的

python作为主要编程语言的扫描器叫证道玉，
是内部使用的扫描器，用其在代码审计和黑盒测试中，让我收获了大量的xx。

go扫描器其实和证道玉是同一个原理，就是主要编程语言变成了Go，附以python代码；
之前研究过一下go+python，两种方法：一是讲go语言打包成so动态链接库，利用python的ctypes模块可以调用
二是go写成接口，提供python调用。觉得第一种好一点，尽管使用python去调用go会有一些性能上的损耗，但总体上还可以。