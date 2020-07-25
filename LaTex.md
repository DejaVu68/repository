[toc]

# LaTeX

## 字体属性

加粗：textbf{文字}

斜体：\emph{文字}

花体大写：\mathscr{大写字母}

罗马体：\mathrm{字符}

加粗斜体：\boldsymbol

\mathcal：$\mathcal A$

\mathbb：$\mathbb{E}$

![img](https://img-blog.csdn.net/20160927145319800?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

上划线$\overline{A}$：\overline{式子}

下划线$\underline{A}$：\underline{式子}

顶部曲线$\tilde{A}$：\tilde{}

字母顶部的小折线$\hat{A}$：\hat{}——$\widehat{A}$：\widehat{}



## 符号

### math

正负$\pm$：\pm——plus minus

不等$\neq$：\neq

约等$\approx$：\approx

点乘：\cdot

梯度$\nabla$：\nabla

偏导$\partial$：\partial

存在$\exists$：\exists

任意$\forall$：\forall

无穷：\infty

正比于：\propto

空集$\varnothing$：\varnothing

属于：\in

给公式编号：\tag{}

***

真包含$ \subset$ ：\subset

包含$ \subseteq  $：\subseteq

$\supset$：\supset

$\in$：\in

$\cap$：\cap

$\cup$：\cup

$\mid$ : \mid

$\notin$ : \notin

### symbol

省略号：\cdots，单个为\cdot

首行缩进， 可以在全文之前设置首行缩进：

\parindent=19pt

设置好之后，如某一段需要改变缩进，比如说需要顶格，那么可以在这一段的之前加上：

\hangafter=-1\hangindent=19pt\noindent

#### 空格

两个quad空格： 对应的命令是 \qquad ，表示2m的宽度      

一个quad空格：对应的命令是\quad，表示 间距1m宽度

**大空格**：  对应的命令 \   表示 间距1/3m宽度 实例：  a\ b

**中等空格**： 对应的命令 \;  表示间距2/7m宽度。实例：  a\;b

**小空格**： 对应的命令\, 表示**间距**1/6m宽度

**没有空格**：直接输入即可，表示不需要额外加入空格。

**紧缩**： 即使他们之间的距离我负值，对应的命令\!，表示缩进1/6m宽度； 如果缩进的距离还不满意，请输入\!\! 这样来调节。

### 任意符号上下任意添加

$\mathop{top}\limits_{down}$ : `\mathop{}\limits_{}`



## 求和

右写式：$\sum_{i = 1}^{P}$

上下式：$$\sum\limits_{i = 1}^{P}$$