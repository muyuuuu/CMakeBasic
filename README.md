# Intro

作为一个练习时长 6 年多的 `python` 程序员，面对工程时写好 `__init__.py` 直接导包就可以使用，命令行一句 `python main.py` 原地起飞。

自从转到 `C/C++`，竟然还要头文件，还要链接库，要写 `MakeFile` 手动把工程给组织起来，直接 `g++ main.cpp` 竟然不行！！！还有王法吗？？？这让初入门的我一度怀疑人生。

所以本仓库诞生了：通过几个由浅入深、层层递进的小例子，让没接触过 `CMake` 或者没写过 `C/C++` 工程的人快速上手，所以一定要从头看起哦~

由于 `CMake` 的写法高度依赖项目和文件夹的结构，所以在每个示例中会给出详细的介绍。

# 示例

|  项目  | 备注                                                                                                                                  |
| :----: | :------------------------------------------------------------------------------------------------------------------------------------ |
| demo0  | 介绍为何使用 `CMake`                                                                                                                  |
| demo1  | 入门示例，其他文件中定义函数，在 `main.cpp` 中引用                                                                                    |
| demo2  | 批量引用源文件，在 `main.cpp` 中引用                                                                                                  |
| demo3  | 初步工程化，更好的引用头文件和代码文件                                                                                                |
| demo4  | 生成动/静态链接库                                                                                                                     |
| demo5  | 导出库和头文件                                                                                                                        |
| demo6  | 使用动/静态链接库                                                                                                                     |
| demo7  | `include <test/test.h>` 行，`include <test.h>` 不行；处理同名头文件                                                                   |
| demo8  | 特殊宏定义                                                                                                                            |
| demo9  | 一个含有加载库、自动化测试、日志输出多级目录的小项目，从此之后 `cmake` 问题不大                                                       |
| demo10 | `demo9` 感觉不太行，有炫技的嫌疑，可以参考我另外的计算框架 [`CUFX`](https://github.com/muyuuuu/CUFX/tree/main/CUFX) 中的 `cmake` 写法 |

# 参考

1. https://subingwen.cn/cmake/CMake-primer/
