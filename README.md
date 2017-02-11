# Plan
Plan for undergraduate study

#需要学习的知识
掌握C/C++编译型语言，同时要掌握一门解释性语言Python。推荐学习完C语言之后，先学习Python，然后再学习C++。C++比较难，可以再掌握了面向对象编程技术之后，学习STL就点到为止。后面的泛型编程和模版元编程，可以让你对STL的构建过程有深刻的认识，但是对于本科生来说没有太必要。大学四年把《C++ Primer》《深入探索C++对象模型》《Effective Modern C++》看完就已经很不错了。然后再找一本书学习一下STL就可以了。

学会使用git版本管理，ssh远程连接其他计算机，cmake和make构建项目。在Windows上有msbuild，UNIX上的是make。cmake可以产生适合msbuild和make的文件，所以cmake其实是跨平台的为项目构建工具产生代码的工具，是更高一级的抽象。

学会使用一种编译器，推荐LLVM/Clang，懂得各种option。Clang是苹果公司主导开发的一个开源编译器，主要用在苹果电脑的MacOS上，在Unix操作系统中广泛使用gcc编译器，和clang的很多编译选项时相同的。了解编译、链接和库的概念，这三者的关系，本质上来讲就是操作系统和编译原理的知识，除了专业课上好之外，推荐《程序员的自我修养》、《深入理解计算机系统》和《Linkers & Loaders》这三本书。

学会使用shell命令行解释器，在Unix系统中使用bash，在Windows系统中使用PowerShell。如果想要对操作系统有更深的、从源代码级别的了解，可以看《UNIX环境高级编程》了解UNIX操作系统，而对于Windows操作系统由于是闭源，可以找一本书学习一下Windows API。

学会使用VIM编辑器，掌握基本的操作。推荐使用Vundle进行插件管理，掌握VIMscript自己写插件。

以上这些东西，在大三之前掌握即可。除了C++、编译原理、操作系统还有VIMscript之外，这些工具都比较简单和基础。C++需要花费很多精力才能学好，学好之后对于学习其他比如JAVA之类的语言很有帮助。
