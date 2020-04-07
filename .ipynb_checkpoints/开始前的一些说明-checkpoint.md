# 开始前的一些说明


## 模块的含义及其用处

模块(modules)，指的是可调用的Python脚本(即.py文件)。模块可以封装保存代码。除此之外，它还可以实现文本文件所不能实现的功能：**模块中的所有内容(变量、函数、方法(Methods)都可以被其他代码所调用(import)**。

这一点至关重要。有了模块，我们便可以从其他文件调用函数，而不用在自己的代码前先定义函数，让自己的代码又臭又长。最为重要的是，我们可以**调用别人设计好的函数来为我们服务**。如果碰到那些超出自己能力范围之外的问题，或者那些没有任何解决思路的问题，我们可以借助别人设计好的模块来辅助我们解决它。

比如说，我决定用Python来做一个图像化(2D)的小游戏，但是我不知道怎么用Python来实现GUI(graphical user interface)。这个时候我通过Google [python make game](https://www.google.com/search?q=python+make+game&oq=python+make+game&aqs=chrome..69i57j0l7.5207j0j7&sourceid=chrome&ie=UTF-8)，发现pygame这个模块可以帮我解决这个问题。通过调用pygame里的函数、方法和类，即便不知道如何实验GUI，我也能做出一个2D小游戏。

再比如，我想用Python来做一个二维码，但是以我现有的知识明显没有办法实现。于是通过Google，我找到了一个叫[myqr](https://github.com/sylnsfar/qrcode)的模块。通过调用myqr，我也可以轻松地用Python来DIY一个二维码。

pass

## 从哪里入手



