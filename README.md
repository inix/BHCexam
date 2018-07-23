# BHCexam
BHCexam math exam template.

This is version 0.4 of the BHCexam document class, dated Oct 10, 2015.

The BHCexam document class attempts to make it easy for even a LaTeX novice to prepare exams.

To generate the document class files from .dtx file:
make cls;

To install the document class files to ~/texmf
make install;

To generate the user's guide document (with index)
make [full]doc;

To generate test page
make test

--------------------------------------------------------------------

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3 of this license
or (at your option) any later version.


## 介绍
BHCexam宏包介绍：

BHCexam 宏包为中国数学教师设计，提供了一个排版中学数学试卷的LATEX 文档类，由鲍宏昌制作并负责维护。

本宏包以exam 为底层文档类，部分源代码来自于盖鹤麟开发的colinexam。不知道什么原因盖鹤麟自2004 年就一直没有发布更新， colinexam 仍然使用CCT 实现中文支持，而缺乏对X?TEX 的支持。

2011 年7 月，作者在colinexam 的基础上放弃了对CCT的支持而改用X?TEX实现中文支持，用doc 和docstrip 工具编写了这个文档，增加了一些新的功能，并把新的宏包命名为BHCexam。

本宏包延续了colinexam 和exam 的宗旨，那就是能让一个刚刚接触LATEX 的初学者，也能轻松用它来排版试卷。希望BHCexam 能提高中学教师的工作效率，并把注意力放在试卷的内容上。

通过BHCexam可以实现：

1. 自动对题目编号。
2. 自动生成试卷页脚。
3. 自动计算简答题各小问的和并显示在简答题的第一行。
4. 用一条命令生成试卷标题、考试须知。
5. 用一条命令输出简答题、选择题、填空题前的提示语。
6. 用一条命令在页左（右）生成装订线。
7. 可以选择试卷的纸张。
8. 可以选择将答案和试题排在一起。
9. 可以选择生成计分框。
10. 同时支持xelatex和pdflatex。
