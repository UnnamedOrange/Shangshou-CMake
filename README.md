# 上手 CMake

> 书名：《上手 CMake》
>
> Book Name: *Shangshou CMake*

正在写，每天写一点。跟我一起学 CMake！

## 动机

希望写一本适合中国学生编程基础的 CMake 教程，牢固地掌握 CMake。

## 重要参考资料

在产生动机之后、开始写作之前，找到了一本全网最好的 CMake 书籍：《CMake Best Practices: Discover proven techniques for creating and maintaining project with CMake》。没有其他任何教程有这本书详细、现代、工程正确。它将是重要的学习参考，但本书的结构、侧重点会与它大不相同。当然，本书与它最大的区别是本书使用中文编写；不过读者最好已熟练掌握英文、了解除中英文外的其他自然语言，以应对当今复杂的国际化软件开发需求。

## 如何编译

使用 `latexmk -xelatex` 或 `texify --engine=xetex --pdf` 编译 `book/book.tex`。

如果你没有安装任何 $\mathrm{\TeX}$ 发行版，可以 fork 该仓库，然后在 Actions 页面手动触发 `build` 工作流，GitHub Actions 将通过云服务为你生成一份 PDF 并上传为 artifacts。点击 Artifacts 列表下的 `book` 即可下载。注意只能下载自己的，因此必须先 fork。

## License

Licensed under the Creative Commons Attribution Share Alike 4.0 International. See the LICENSE file in the repository root for full license text.
