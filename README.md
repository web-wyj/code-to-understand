# code-to-understand
学习中遇到的不清楚的概念，用程序和代码解释

1.[事件冒泡与事件捕获](https://web-wyj.github.io/code-to-understand/bubble-and-capture.html)
```
单击 div 并在 <F12> console 查看效果
```

2.[canvas中的文字绘制与方块绘制的高度偏差](https://web-wyj.github.io/code-to-understand/text-vertical.html)
```
行内元素，汉字、数字、英文存在 top, baseline, bottom 三条准线
其中，汉字的底线与英文的底线不同，介于 baseline 与 bottom 的中间

因此canvas中的文本绘制与方块绘制的存在一定的高度差
要使得等高的文本与方块水平对齐，必然要注意这之间的高度差

粗略估算，仅有汉字，要水平对齐，顶部差约为1/7
不考虑汉字的顶部差，底部基线填充约为1/3
```
关于baseline的概念与css的关系，可在下列问题回答中了解：
* [知乎 - 中文到底有没有基线（baseline）的概念？](https://www.zhihu.com/question/22183501)
* [SegmengtFault - img的间隙](https://segmentfault.com/a/1190000006808606)