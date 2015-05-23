##北师大信息学院大数据与物联网实验室beamer模板

### 来源
这个模板参考了交大的一位同学的毕业论文的模板。在此基础上我略微做了些修改，去掉了一些我不太喜欢的配置。基本上还原了Berkeley主题的配置，同时增加了对中文的支持。

参考自[mx's Blog](http://x-wei.github.io/beamer_template.html)。感兴趣的同学可以进入看一看。感谢mx同学的分享！！

### 效果
![](http://cl.ly/image/2l132o160T2S/Image%202015-05-23%20at%206.43.52%20%E4%B8%8B%E5%8D%88.png)


### 注意事项

1. 使用xelatex编译生成, latex估计不行, xelatex的配置参考<http://x-wei.github.com/xelatex_zh.html>

2. 编辑内容直接修改main.tex即可, 改变设置一般在header.tex里

3. 中文字体我用的是Adobe字体，英文字体主要用的是Arial，可以在header.tex中修改自己喜欢的字体。查看已安装的中文字体的命令为: `fc-list :lang=zh-cn`

4. 不喜欢Berkeley主题，可以修改header.tex的`\usetheme{Berkeley}`。Beamer默认提供了非常丰富的主题可供选择。更多Beamer主题参考<http://deic.uab.es/~iblanes/beamer_gallery/individual/Berkeley-default-default.html>
5. 用beamer做ppt其实也比较费事，特别是对latex不熟的人来说。使用beamer做ppt一来觉得新鲜好玩，二来确实做出来ppt感觉很学术，很喜欢。个人就是爱折腾，没事找事，如果嫌麻烦，请直接忽视。
