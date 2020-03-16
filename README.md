<!-- Author : Jingxuan Yang-->
<!-- Program Email: yanglatex2e@gmail.com -->

# hitszbeamer: A Beamer Theme for Harbin Institute of Technology, ShenZhen (HITSZ)

# hitszbeamer：哈尔滨工业大学（深圳）Beamer模板

[Github](https://github.com/YangLaTeX/hitszbeamer) | [Download](https://github.com/YangLaTeX/hitszbeamer/releases) | [Wiki](https://github.com/YangLaTeX/hitszbeamer/wiki) | [CTAN](https://www.ctan.org/pkg/hitszbeamer)

# Introduction to hitszbeamer

**hitszbeamer** is a **beamer theme** designed for Harbin Institute of Technology, ShenZhen (HITSZ). Current version is 1.0.0, updated on 2020/03/17.

```latex
  |- figures
    |- hitlogo.jpg
    |- hitlogo-mask.jpg
  |- hitszbeamer.bst
  |- hitszbeamer.dtx
  |- hitszbeamer.pdf
  |- main.tex
  |- main.pdf
  |- makebeamer.bat
  |- makeclean.bat
  |- makecleanall.bat
  |- makedoc.bat
  |- Makefile
  |- README.md
  |- reference.bib
```

# hitszbeamer简介

hitszbeamer是哈尔滨工业大学（深圳）Beamer模板，当前版本1.0.0，更新于2020年03月17日。

# Documentation

Download and unzip the template. Specific usage documentation and examples can be found in the files below:

* Template usage (hitszbeamer.pdf, in Chinese)
* Template example (main.pdf, in Chinese)
* Brief Introduction (README.md, both in Chinese and English)

# 说明文档

下载并解压本模板，文件夹中包含以下说明文档：

* 模板开发文档（hitszbeamer.pdf，中文版）
* 模板撰写示例（main.pdf，中文版）
* 模板简介（README.md，中英双语）

# Downloads

* Published version: [CTAN](https://www.ctan.org/pkg/hitszbeamer)
* Developer version: [GitHub](https://github.com/YangLaTeX/hitszbeamer)

# 下载

* 发布版本：[CTAN](https://www.ctan.org/pkg/hitszbeamer)
* 开发版本：[GitHub](https://github.com/YangLaTeX/hitszbeamer)

# Reporting Issues

Please follow the procedure below:

* QQ group: 1039392552
* [GitHub Issues](https://github.com/YangLaTeX/hitszbeamer/issues)
* [Educational Email](mailto:yangjingxuan@stu.hit.edu.cn)
* [Gmail](mailto:yanglatex2e@gmail.com)

# 模板问题反馈

请按照以下顺序反馈问题：

* QQ group: 1039392552
* [GitHub 问题反馈](https://github.com/YangLaTeX/hitszbeamer/issues)
* [教育邮箱](mailto:yangjingxuan@stu.hit.edu.cn)
* [Gmail 邮箱](mailto:yanglatex2e@gmail.com)

# Makefile Usage

To use Makefile, you should have GNU `make` tool installed.

```bash
make doc       # compile documentation (required before compiling the beamer)
make beamer    # compile beamer
make clean     # clean auxiliary files
make cleanall  # clean auxiliary files and style files
```

# 使用Makefile

使用Makefile之前请确保已安装GNU `make`工具。

```bash
make doc       # 编译说明文档（在编译 beamer之前必须编译说明文档）
make beamer    # 编译 beamer
make clean     # 清除辅助文件
make cleanall  # 清除辅助文件与样式文件
```

# batch Usage

`makedoc.bat`, `makebeamer.bat` and `makeclean.bat` are designed for windows platform. Double click these files, then they will echo corresponding functions automatically.

```bash
makedoc       # compile documentation (required before compiling the beamer)
makebeamer    # compile beamer
makeclean     # clean auxiliary files
makecleanall  # clean auxiliary files and style files
```

# 使用编译脚本

`makedoc.bat`、`makebeamer.bat`与`makeclean.bat`为windows编译脚本，双击即可执行相应的功能。

```bash
makedoc       # 编译说明文档（在编译 beamer之前必须编译说明文档）
makebeamer    # 编译 beamer
makeclean     # 清除辅助文件
makecleanall  # 清除辅助文件与样式文件
```

# License

This material is subject to the [LATEX Project Public License 1.3c](https://ctan.org/license/lppl1.3) or any later version.

# 协议

本模板的发布遵照[LATEX Project Public License 1.3c](https://ctan.org/license/lppl1.3)协议或其后版本。

# Acknowledgements（致谢）

* [XDUstyle](https://github.com/StickCui/XDUstyle-Beamer-Theme)
* [thubeamer](https://github.com/tl3shi/THUBeamer)
