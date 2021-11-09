# ScutThesis
​  By [Sherry Liang](mailto:cssherryliang@gmail.com)

本项目为**华南理工大学博士学位论文LaTeX 模板**，从清华大学学位论文 LaTeX 模板 `thuthesis-v7.2.1`修改而来。详细使用方法请参考原模板相关说明：[ThuThesis](https://github.com/tuna/thuthesis)



## 用法1：Overleaf在线编辑

Overleaf链接：https://www.overleaf.com/read/mqnkzqhpwdbk

点击menu，然后点击Copy Project将该项目变成自己的项目，就可以编辑啦~

#### 如何设置menu的setting栏目

* Compiler: XeLatex
* Tex Live Version: 2020
* Main Document: main.tex

## 用法2：TexStudio本地编辑

用TeXstudio打开main.tex，使用XeLaTeX进行编译

#### 如何设置XeLaTeX编译

1. 点击 选项→设置 TeXstudio，则进入了TeXstudio的设置页面

2. 选择 构建→默认编译器→XeLaTeX，点击确认

## 用法3：VSCode本地编辑

使用VSCode编辑tex文件，用[`make`](https://cmake.org/install/)生成pdf文件。

#### 如何使用`make`

通过命令行工具（如cmd，bash）进入项目所在目录：

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```


* `make thesis`    生成论文 main.pdf；
* `make spine`     生成书脊 spine.pdf；
* `make doc`       生成模板使用说明书 thuthesis.pdf；
* `make all`       生成论文和书脊，相当于 `make thesis && make spine`；
* `make clean`     删除示例文件的中间文件（不含 main.pdf）；
* `make cleanall`  删除示例文件的中间文件和 main.pdf；
* `make distclean` 删除示例文件和模板的所有中间文件和 PDF。
