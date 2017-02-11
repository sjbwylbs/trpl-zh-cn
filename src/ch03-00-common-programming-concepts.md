# 通用编程概念

> [ch03-00-common-programming-concepts.md](https://github.com/rust-lang/book/blob/master/src/ch03-00-common-programming-concepts.md)
> <br>
> commit 2067b6e2bff990bceb39ae8f35780bd3bed08644

这一章涉及到几乎出现在所有编程语言中的概念，以及他们在 Rust 中如何工作。很多编程语言在核心概念上都是共通的。本章中展示的所有概念没有一个是 Rust 所特有的，不过我们会在 Rust 环境中讨论他们并解释他们的使用习惯。

具体的，我们将会学习变量，基本类型，函数，注释和控制流。这些基础知识将会出现在每一个 Rust 程序中，提早学习这些概念会使你在起步时拥有一个核心的基础。

<!-- PROD: START BOX -->

> ### 关键字
> 
> Rust 语言有一系列被保留为只能被语言使用的*关键字*（*keywords*），如大部分语言一样。注意你不能使用这些关键字作为变量或函数的名称。大部分关键字有特殊的意义，并将会被用来进行 Rust 程序中的多种任务；一些关键字目前没有相关的功能不过为了将来可能添加进 Rust 的功能而被保留。可以在附录 A 中找到一份关键字的列表

<!-- PROD: END BOX -->