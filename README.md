# python-utils
一些关于python的习的学

源自B站up主[AI匠](https://space.bilibili.com/2832208)

暂时杂乱记录，有空分类归档

运行环境为conda虚拟环境python-utils，执行`conda env create -f python-utils.yaml -y`安装虚拟环境

### fire
将函数快速转变为命令行可调用的工具
- 可接受python基本类型作为命令行的输入：int, float, str, list, tuple, dict；
- 示例：执行`python test_fire.py 1 2`，会发现函数自动接受命令行输入并执行



