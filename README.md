# Thu2ScutThesis

本项目为**华南理工大学博士学位论文LaTeX 模板**，从清华大学学位论文 LaTeX 模板 `thuthesis-v7.2.1`修改而来。详细使用方法请参考原模板相关说明：[ThuThesis](https://github.com/tuna/thuthesis)

​                                                                                                                                                             ——[Sherry Liang](mailto:cssherryliang@gmail.com)


## Overleaf链接

https://www.overleaf.com/project/60f7f4bd72ab976ab44eedd7

### 设置

* Compiler: XeLatex
* Tex Live Version: 2020
* Main Document: main.tex

## 用法

通过命令行工具（如cmd，bash）进入项目所在目录：

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```

### 目标

* `make thesis`    生成论文 main.pdf；
* `make spine`     生成书脊 spine.pdf；
* `make doc`       生成模板使用说明书 thuthesis.pdf；
* `make all`       生成论文和书脊，相当于 `make thesis && make spine`；
* `make clean`     删除示例文件的中间文件（不含 main.pdf）；
* `make cleanall`  删除示例文件的中间文件和 main.pdf；
* `make distclean` 删除示例文件和模板的所有中间文件和 PDF。
