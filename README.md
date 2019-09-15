# 2019 级问题求解 LaTeX 教学引导

`对理工科同学来说，LaTeX 是必备技能。问题求解系列课程的平时作业也是要求同学们使用 TeX 的，这里是我和17级化拔高嵩同学一起制作的 LaTeX 教程，为了让同学们能在短时间内快速上手，问题求解教学组决定为大家提供 LaTeX 学习路径。`

# LaTeX 环境配置推荐
- 在线
  - Overleaf  
  不需要安装，不需要担心 package 的问题，但是网不好的话会很慢，挂梯子会好一点。
- 本地
  - TeX 发行版
    - TeX Live  
	优点：完整。缺点：太大。
    - MiKTeX（仅限 Windows）  
	优点：需要用到包的时候再下载。缺点：如果需要包的时候服务器挂了，就会很尴尬。
  - TeX 编辑器
    - Texmaker
    - TeXstudio
    - Visual Studio Code + Latex Workshop 插件
    - WinEdt（仅限 Windows，收费）
    - 还有很多，请自己上网查
  
# 该教程的构成

教程主体就是`LaTeXtutorials.pdf`这个文件，其中`img\`和` part\`文件夹都是该文件的组成部分，有这些文件在，编译`LaTeXtutorials.tex`就能得到我们的教程 pdf 文件了。

两个安装教程看一个就行了，教你如何配置好 LaTeX 的环境 (texlive + texmaker的教程是我写的，如果用这个教程出了问题，能提供更多的指导)。

`\material\`文件夹中，是教程附带的一些资料，包括

- 练习题`\practice\`：教程中对应的地方，会提示你到该文件夹下的相应练习处巩固知识点
- 学习资料`\LM\`：放着很多文档、手册，这些材料更能为全面，像工具书一样
- 效果展示`\pre\`：是我的两份作业，用于展示 LaTeX 排版的实际效果
- 模板`\Template\`：包括化学论文模板、数学建模论文模板、作业模板、==问求作业模板==、南大主题的beamer模板(beamer可以理解成幻灯片)

# 该教程的学习路线

为了尽快上手，我们推荐同学们按照下列顺序学习章节。

- 能编译出基本的文档
  - 与 LaTeX 相遇
  - 文档
  - 文章结构 (多文件编译这一节，可以结合你们的问求作业模板，和本教程的源文件，思考学习。也可以暂时跳过，留到后面学)
  - 文本环境举隅
  - 自动化工具——目录
  - 其他 (该章节是教程制作者提供的一些小建议)
- 理工科学生需要掌握的基本技能
  - 强大的数学公式 (这一章节较为枯燥，同学们了解基本语法就行，日后可以边查边用)
  - 表格与浮动体
  - 自动化工具——交叉引用、索引
- 进阶
  - 来做幻灯片
  - 自动化工具——页面格式、文献引用
  - 中文支持

# 一些其他的 LaTeX 资源

- 官方文档和教程
  - [CTAN: Comprehensive TEX Archive Network](http://www.ctan.org/)   
  常用的文档或手册都可以在这里搜索到
  - [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)
  - [TeX Frequently Asked Questions](http://www.tex.ac.uk/)   
  这些问题挺好的，大家有空可以多看看，能提前避开不少坑
- 问答社区、博客
  - [TeX Stack Exchange](http://tex.stackexchange.com/)   
  Stack系列社区是非常棒的专业知识问答平台，比如计算机，专业的数学，不那么专业的数学，物理，LaTeX 等等
  - [TeXblog](http://texblog.net/)
- 在线编辑器 
  - [Overleaf](https://www.overleaf.com/)  
  一方面能让你直接在网上编译TeX文件而无需自己配置环境，一方面也提供了许多模板和一些教程
- 数学公式辅助
  - [在线编辑器](https://www.codecogs.com/latex/eqneditor.php)
  - [Detexify](http://detexify.kirelabs.org/classify.html)   
  识别符号
  - [帮助:数学公式 - 维基百科](https://zh.wikipedia.org/wiki/Help:%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F)  
  不完全和 LeTeX 中的符号集合相等，但很有用
