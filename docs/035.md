# FastAPI 与 Flask:比较构建 Python REST API 的顶级微框架的优缺点

> 原文：<https://www.stxnext.com/blog/fastapi-vs-flask-comparison/>

 创建 REST APIs 之类的 web 应用程序是后端开发人员的主要工作。因此，使用 web 框架应该快速而简单。

对于需要 REST API 的小型项目、MVP 甚至大型系统来说，微框架是一个很好的开端——包括 Flask 和 FastAPI。

我在这两个框架中编写了一个应用程序来创建、更新、下载和删除新闻。结果，下面是我对 FastAPI 和 Flask 的对比。 

#### 烧瓶是什么？为什么要用？

Flask 是用 [Python](/services/python-development/) 构建 web 应用程序最流行的库之一。开始编程冒险的人会很容易找到很多 Flask 教程和常见问题的解决方案。

它是轻量级的(一个“微框架”)，并且有很好的文档，有许多扩展和一个大型社区。

#### 什么是 FastAPI？为什么要用？

FastAPI 是构建 API 的性能最高的 Python web 框架[](https://fastapi.tiangolo.com/#performance)之一，并且每天都被越来越多的人使用。

它对速度的重视，不仅体现在每秒处理的查询数量上，还体现在开发速度和内置的数据验证上，这使它成为 web 应用程序后端的理想选择。

#### 数据有效性

在这里，我们可以找到两个库之间的第一个显著差异。

通过安装 Flask，我们没有得到任何数据验证工具。然而，我们可以通过使用社区提供的扩展来解决这个问题，例如[Flask-Marshmallow](https://flask-marshmallow.readthedocs.io/en/latest/)或 [Flask-Inputs](https://pythonhosted.org/Flask-Inputs/) 。

这种解决方案的缺点是，我们必须依赖独立于我们的主框架开发的库，这意味着我们不能 100%确定它们是兼容的。

另一方面，FastAPI 给了我们使用的 [Pydantic](https://pydantic-docs.helpmanual.io/) 库，这使得数据验证比手工输入要简单和快速得多。它与 FastAPI 本身密切相关，因此我们可以确信 Pydantic 将始终与我们的框架兼容。

那么，基于我们简单的 API，各个库中的验证是什么呢？

我们创建名为“news schema ”/“creator schema”的类，这些类将作为验证新闻和作者的基类。