---
layout: post
title:  Jekyll基本实现写博客功能
date:   2015-02-08 ‏‎‏‎18:23:10
categories: jekyll
---
今天又研究了一天jekyll。
现在已经实现这种效果了。

![finish-basic-jekyll-1](/images/finish-basic-jekyll/finish-basic-jekyll-1.png)

页面部分我使用的就是jekyll本身的效果没有任何美化的过程。

大概总结一下有几点我觉得比较重要的。

 * 1.git的使用。

> 因为我全程基本上都是在linux下进行操作，所以git用的是全部的命令行。
至于git命令行的使用我还是没有太明白，我觉得多上传几次代码应该就会慢慢熟悉，到时候大概我会将git的基本命令写一个博客出来，还希望到时候有人来访问。

 * 2.前端知识

> 因为对前端接触较少，所以可能再代码方面是十分不熟悉，所以也只能用原生的模板。
实在是太丑。

 * 3.Markdown

> 整个jekyll的文章发布是用的Markdown。
我使用了github推出的编辑器atom。
讲句实在话我没觉得atom哪里好用，但是它可以实时预览你的Markdown文件。
因为我想早点发文章出去，所以Markdown的语法基本上没怎么熟悉就直接上了，看上去肯定不美观。但是Markdown确实给我的感觉很好，不复杂，但是很舒服。而且语法上也没有很难。

##下面我将对我从hello world改动到现在这个样子进行一个阐述。

![finish-basic-jekyll-2](/images/finish-basic-jekyll/finish-basic-jekyll-2.png)

这是原来的样子。

首先我打开的是_config.yml

![finish-basic-jekyll-3](/images/finish-basic-jekyll/finish-basic-jekyll-3.png)

Title对应了博客的名称。
Email就对应了左下方的email。
我将twitter那一行删了…后面我再考虑要不要换成我的微博啥的。
然后description就是右下角那一串字。

全部修改完毕就会得到我的首页的样子。

还有右上角的About。
我们打开 about.md，这是Markdown文件了。
修改title会修改about显示的文字，修改里面的内容就可以点击About跳转进去了。

![finish-basic-jekyll-4](/images/finish-basic-jekyll/finish-basic-jekyll-4.png)

还有最后就是我发布的那几篇文章。和posts这个文字的修改。
Posts那个文字修改是在index.html里修改。

![finish-basic-jekyll-5](/images/finish-basic-jekyll/finish-basic-jekyll-5.png)

发布的所有文章都放在_posts文件夹里。
Jekyll提供了一个例子可以研究一下。
发布就会在首页显示。
我连续发布了三篇所以就显示了~

怎么发布就需要Markdown的语法了，可以把我博客从github上download下来看看。
不要问我看的谁的我看的迪哥的。

总之大概就是这样。
后期计划还是要把Markdown的语法研究一下，不然文章看上去太丑了。
还有就是研究一下怎么设置可以评论和查看访问记录。
最后就是美化我的jekyll，不管是修改别人的还是我自己设计。

总之，前面几篇可能水分有点大，但是这一篇确实可以迅速搭建一个在github上的博客。

另附我博客的github地址和迪哥博客的github的地址。

我的[github.com/judi0713/judi0713.github.com](https://github.com/judi0713/judi0713.github.com)
迪哥的[github.com/icindy/icindy.github.io](https://github.com/icindy/icindy.github.io)