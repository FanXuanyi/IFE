# 百度前端技术学院练习

## [有趣的鼠标悬停模糊按钮](https://github.com/FanXuanyi/IFE/blob/master/CSS3/mouse-hover.html)

主要用以下几个CSS属性实现：

- background-image：绘制背景图
- background-clip：裁剪背景图
- text-fill-color：设置字体颜色
- background-size：设置背景图大小
- animation：动画

制作流光文字的几个要点：

text-fill-color（color）一般设置为transparent（透明色），利用background-image和linear-gradient（渐变颜色）来设置文字的背景色，利用background-clip来实现文字的截取，利用background-size设置扩大背景，使用animation达到动画效果。

 ## [CSS3饼状loading效果](https://github.com/FanXuanyi/IFE/blob/master/CSS3/pie-loading.html)

主要涉及到以下内容：

- 制作圆环：使用伪元素，border。
- 制作圆饼：使用了animation-timing-function属性。
- 圆饼和圆环的旋转：使用animation属性，使用transform设置旋转角度，使用transform-origin设置旋转中心。

具体分析可以参考这篇[文章](http://ife.baidu.com/note/detail/id/1016)。
