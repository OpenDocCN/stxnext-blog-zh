# 数据工程的 Python:数据工程师为什么要用 Python？

> 原文：<https://www.stxnext.com/blog/python-for-data-engineering/>

 Python 是 [全球最流行的编程语言之一](/python-vs-other-programming-languages/) 。它经常在调查中排名很高——例如，它声称在编程语言指数 的 [受欢迎程度中排名第一，在](https://pypl.github.io/PYPL.html) [TIOBE 指数](https://www.tiobe.com/tiobe-index/) 中排名第二。

在最权威的开发者调查之一的 [栈溢出](https://insights.stackoverflow.com/survey/2021) 中，Python 始终稳居榜首；根据 2021 年的调查，它是最受欢迎和第三受欢迎的编程语言。

Python 也是数据科学家 和 [的首选语言，是 R](/blog/r-and-python-comparison/) 等机器学习专业语言的绝佳替代品。它通常被称为数据语言，在[数据工程](/services/data-engineering/)中不可或缺。

作为一名数据工程师，我无法想象没有 Python 的工作。在这篇文章中，我想分享一下我对 Python 如何使我的工作变得更简单的想法，在某些情况下，这是完全可能的。 

#### 云中的数据工程

数据工程师面临的日常挑战与数据科学家面临的挑战相似。以各种形式处理数据是这两种专业化的关注中心。然而，在数据工程背景下，我们更关注工业过程，比如数据管道和 ETL(提取-转换-加载)作业。无论解决方案是用于内部部署还是云平台，这些都需要强大、可靠和高效。

说到云，Python 已经证明了自己足够优秀，足以激励云平台提供商使用它来实现和控制他们的服务。如果我们看看最大的玩家——即亚马逊网络服务(AWS)、谷歌云平台(GCP)和微软 Azure——他们都在其解决方案中为 Python 用户提供了许多问题。

首先，无服务器计算原理允许按需触发数据 ETL 过程，而不需要维护和支付持续运行的服务器。物理处理基础设施在这里由用户透明地共享，以便优化成本并将管理开销严格限制在最低限度。

Python 是为数不多的三个平台(AWS Lambda 函数、GCP 云函数和 Azure 函数)的无服务器计算服务都支持的编程语言之一。

反过来，并行计算对于大数据问题的繁重 ETL 工作也是必要的。在许多工作节点之间划分转换工作流是在内存方面(当数据无法保存在一台物理机器的内存中时)和时间方面(当顺序处理需要太长时间时)实现目标的唯一可行的方法。

虽然 Apache Spark 现在是数据并行的首选技术，但 AWS Elastic MapReduce (EMR)、GCP 的 Dataproc 和 Azure 的 HDInsight 都支持 Spark 引擎的 Python 包装器 PySpark。

就控制和管理云中的资源而言，每个平台都有适当的应用程序编程接口(API)。

API 对于执行编程数据检索或作业触发特别有用。那些由 AWS、GCP 和 Azure 开发的软件被方便地封装在 Python SDKs 中: *boto、google_cloud_*、*和 *azure-sdk-for-python、*，这使得它们很容易集成到 Python 应用程序中。

因此，Python 可以在所有云计算平台上广泛使用。但该语言也是执行数据工程师工作的有用工具，数据工程师的工作是建立数据管道和 ETL 作业，以便从不同来源检索数据(摄取)，处理/聚合数据(转换)，并最终将它们提供给用户，通常是业务分析师、数据科学家和机器学习专家。

#### 关注 Python 中的数据摄取

业务数据可能来自不同性质的各种来源，包括数据库(SQL 和 noSQL)、平面文件(例如 CSV)、公司使用的其他文件(例如电子表格)、外部系统、API 和 web 文档。

Python 作为一种编程语言的流行产生了大量的库和模块，包括那些用于访问数据的库和模块，例如一些 SQL 数据库的 SQLAlchemy、Scrapy、Beautiful Soup，或者带有 web 源的数据请求，等等。

一个特别有趣的图书馆是 [熊猫](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html) 。它能够将数据从各种不同的格式读入“数据帧”，包括 CSV、tsv、JSON、XML、HTML、LaTeX、SQL、Microsoft、open spreadsheets 和其他几种二进制格式，这些格式是不同业务系统导出的结果。

该库还支持面向列的格式，包括 Apache Parquet，这使得以后可以使用 AWS Athena 之类的工具来优化对该数据的查询。

Pandas 基于其他科学和计算优化的软件包，提供了一个丰富的编程接口，具有可靠有效地处理和转换数据所需的大量功能。

aws 实验室维护着一个名为“AWS 上的熊猫”的 aws-data-wrangler 库，以促进 AWS 上众所周知的数据帧操作。例如，该包可以用作 Lambda 函数的层，从而使无服务器功能部署更加容易。

#### PySpark 并行计算

Apache Spark 是一个用于处理大量数据的开源引擎，它以高效和容错的方式利用并行计算原理。虽然最初是在 Scala 中实现的，并且原生支持这种语言，但它在 Python 中有一个广泛使用的接口: [PySpark](https://spark.apache.org/docs/latest/api/python/) 。

PySpark 支持 Spark 的大部分功能，比如 Spark SQL、DataFrame、Streaming、MLlib(机器学习)、Spark Core 等。这使得开发 ETL 工作对于熊猫专家来说非常简单。

我上面提到的所有云计算平台都支持 PySpark: Elastic MapReduce (EMR)、Dataproc 和 HDInsight，分别用于 AWS、GCP 和 Azure。此外，您可以连接一个 Jupyter 笔记本来促进分布式处理 Python 代码的开发，例如在 AWS 中使用本机支持的 EMR 笔记本。

因此，PySpark 是一个强大的工具，用于转换和聚合海量数据，使其随时可供最终用户(如业务分析师)或其他组件(例如通过机器学习)使用。

#### 基于 Apache Airflow 的作业调度

本地系统上流行且广受好评的基于 Python 的工具的存在，促使平台云提供商以“托管”服务的形式将其商业化，从而更易于设置和操作。

其中，亚马逊的 Apache Airflow 管理工作流就是如此，该工作流于 2020 年推出，便于在一些 AWS 区域(撰写本文时有 9 个)使用 Airflow。Cloud Composer 是 GCP 管理气流服务的替代产品。

Apache Airflow 是用 Python 编写的，它是一个开源的工作流管理平台。它允许您以编程方式创作和安排工作流处理序列，然后通过内置的 Airflow 用户界面对其进行监控。

转换的逻辑和调用的子服务也是用 Python 实现的。对于开发人员来说，一个巨大的优势是他们可以导入其他 Python 类来扩展工作流管理功能。

有几种气流的替代品，包括提督和达格斯特。两者都是基于 Python 的数据工作流编排器，具有用于构建、运行和监控管道的 UI(在 Dagster 的情况下是通过 Dagit)。他们的目标是解决用户对 Airflow 的一些问题，air flow 是更受欢迎和更知名的前身。在这两种工具中，工作流都可以使用 Python 进行管理。

#### 关于 Python 用于数据工程的最终想法

Python 在数据工程中有很多用例，该语言是任何数据工程师不可或缺的工具。

在我们的博客 上，我们已经写了很多关于 Python [的好处。您可能也对查看这些资源感兴趣:](/blog)

*   [Python 是用来做什么的？](/what-is-python-used-for/)
*   [最流行的 Python 科学库](/blog/most-popular-python-scientific-libraries/)
*   [如何用 Docker、JupyterLab 和 Apache Livy 构建 Spark 集群 Apache Spark 的 REST API](/blog/docker-jupyterlab-apache-livy-rest-api-apache-spark/)

由于大部分相关技术和流程都可以用 Python 来实现和控制， [作为一家专门研究 Python](/services/python-development/) 的软件公司，我们自然要解决行业中与数据相关的业务需求，并提供 [数据工程服务](/services/data-engineering/) 以及 [web 开发](/services/web-development/) 。

请随时 [与我们](/contact/) 联系，讨论您可能有的任何数据工程需求——我们很乐意与您交谈，并找出我们可以如何帮助您！