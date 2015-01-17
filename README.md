#1.项目说明
##项目基本功能

本项目主要实现了Markdown语法的解析，能够正确解析的 markdown 语法最要有：

    MarkDown  Html
    #  -->     H1
    ## -->     H2
    ###-->     H3 
    列表-->    ol
    代码块-->  <code>
    .....
    即实现了test01.md test02.md test03.md的编译


##测试文件和测试方法

测试文件位于项目目录MdCompiler下
测试：
>python  MdCompiler.py  filename.md

##项目特别说明


#2.组队信息
##小组成员贡献说明
1.李杰初 1252853 （组长）

**主要工作：**
+ Python编译器的Coding
+ LexTokens的识别与YACC文法

贡献率： 60%

2.赵沈彬 1252901

**主要工作：**
+ 项目test优化
+ Python，ply，MarkDown语法资料查找

贡献率： 40%
