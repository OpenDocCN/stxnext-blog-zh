# 使用 Python 的最有趣的公司

> 原文：<https://www.stxnext.com/blog/most-interesting-companies-using-python/>

 STX Next 开发团队对 [Python](/what-is-python-used-for/) 的喜爱是无止境的。但这不是盲目或有毒的爱。这是一种美丽的编程语言和热情的人们之间的关怀关系。

好吧，也许我一开始太浪漫了。为了向您展示 Python 值得如此热爱的原因，我准备了几个使用 Python 实现非凡成果的公司的例子。

这不仅仅是另一篇关于“顶级 Python 公司”的无聊文章，也是你已经知道的老例子。  **在本文中，我们将看看 Python 在现实世界中的非凡应用——制造药物、运行大型 MMO 游戏、打击腐败和扰乱市场。**

**[![Read or download as PDF](img/98e9a9956944ee0caa2bfa710ecf2448.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/9f52debf-f498-4faf-9ecf-dbe0f2f3e7ab)** 

#### 制造药物的 Python 公司和其他鲜为人知的 Python 使用实例

##### 1.麻省理工学院——使用 Python 发现新抗生素

如果你一直在阅读我们的博客，那么你会知道  [Python 是学者们选择的编程语言](/stx-new-blog/python-vs-ruby-comparison/)。它一直被用于突破性的科学发现。

你可能听说过  [麻省理工学院的研究人员最近利用神经网络发现了一种新药](http://news.mit.edu/2020/artificial-intelligence-identifies-new-antibiotic-0220) ，这种药可能有助于人类对抗抗生素耐药性。

首先，他们在 2500 种 FDA 批准的药物和生物活性分子的数据集上训练了一个神经网络模型。

接下来，他们让该模型在一个包含 6000 种化合物的不同数据集上运行。该模型挑选出了一种具有高度抗菌性的分子，它不同于现有的抗生素。

这项研究的作者将这种分子命名为 halicin。初步测试表明，它比任何其他抗生素都更有效。旁注:科学家们从来不会错过一个好的双关语，而“halicin”这个名字被选为 HAL 的参考，HAL 是《2001:太空漫游》中  *的 AI。*

为了实现这一伟大的科学壮举，这项研究的作者使用了开源软件  [RDKit](https://www.rdkit.org/) 。正如  [RDKit GitHub 页面](https://github.com/rdkit/rdkit) 所说，“RDKit 是一个用 C++和 Python 编写的化学信息学和机器学习软件的集合。”

据我所知，核心算法是用 C++编写的，带有 Python 3.x 包装器和一个 Python API。

***你知道吗？** 包装器意味着复杂的计算函数可以被“包装”成一个简单得多的 Python 函数。包装的代码可以来自另一种语言，也可以是 Python。C++代码是低级的，所以本质上它有较少的模糊性。研究人员经常定制函数，以便正确地运行他们的实验，而 C++允许最大程度的定制。Python 是一种高级语言，它可以快速执行包装的 C++函数，因此研究人员可以利用这两种语言。*

##### 2.exscientia——引领人工智能药物研发市场的 Python 公司

2020 年前几周的又一大头条。这是一个关于人工智能药物研发公司 Exscientia 如何使用 Python 开发出一种治疗强迫症的新药的  [成功故事。](https://www.bbc.com/news/technology-51315462)

整个过程花了他们一年时间。似乎很长，对吧？但是在医学界，这是一个令人难以置信的短时间内将药物从开发到人体试验。公司通常需要至少五年的时间才能做到这一点！

要找到一个明确指出 Exscientia 是一家 Python 公司的来源并不容易。他们不在 Stackshare 上，也不在 Github 上发布他们的代码库。这对于像这样的小众、高科技、前沿公司来说是可以理解的。

幸运的是，有几个巨大的迹象表明，事实上，他们是一家使用 Python 作为人工智能药物发现主要工具的公司。

首先，在 Exscientia 工作的软件工程师之一 Nathan Dedman 在 2016 年合写了一篇题为“[想要药物？用 Python](https://arxiv.org/abs/1607.00378) 。”

其次，[Exscientia](https://www.exscientia.ai/careers)的程序员招聘都包含“精通 Python”的要求。一些帖子还包括对 Python 框架  [Flask 和 Django](/stx-new-blog/flask-vs-django-comparison/) 的要求。

如果你问我，没有更多的证据是必要的。Exscientia 显然是一家 Python 公司。

##### 3.制药巨头阿斯利康:自 2001 年以来也是一家 Python 公司

冒着重复我自己的风险，我不能不提到另一家使用 Python 解决严重的、现实世界的问题的药物公司。这一次，是全球制药巨头。

为了简化发现新药物分子的工作，该公司开发了一种软件，可以帮助实验化学家完成他们的工作。

该软件创建于 2000 年，第一个版本不是 Python。但是不久之后，在 2001 年，一位聪明的软件顾问说服了阿斯利康团队，Python 是满足他们需求的最佳选择。这导致了 PyDrone 的诞生，这是“阿斯利康的一个巨大成功”，仅用了 6 个月的时间就完成了。

如果你对更多细节感兴趣，这里有一篇关于阿斯利康如何爱上 Python 的长文， 。)

PyDrone 是一场革命。对于不是软件开发人员的研究人员来说，Python 是最容易理解的语言，因此阿斯利康的化学家可以专注于改进他们的实验，而不是担心代码是否正确计算。

另外，PyDrone 的代码库最终只有 5600 行代码。如果你认为这很多，那么实际上用其他语言构建类似的软件需要更多的代码。以 Java 为例——正如  [Python 软件基金会所说](https://www.python.org/doc/essays/comparisons/)“Python 程序通常比同等的 Java 程序短 3-5 倍。”

##### 4.eve Online——一家使用 Python 在复杂的 MMO 中模拟宇宙的公司

好了，不要再制毒了，因为我开始觉得自己像沃尔特·怀特了。让我们转向一些更愉快的事情——游戏！

世界上最大的免费大型多人在线游戏之一 Eve Online 是由一家使用 Python 的公司开发的。

对于那些不知道的人来说，Eve Online 是一个宇宙模拟器，具有大量的功能和非常复杂的游戏性。如果关于我们的宇宙是一个模拟的理论是真的，那么 Eve Online 就是一个上帝(或者你相信的其他创造者实体)将会扮演什么角色的好例子。

这有点牵强，因为该公司唯一一篇关于使用 Python 的官方开发者博客文章是在 2010 年。这是他们开发团队的一篇关于使用无堆栈 Python 的文章。

然而，对于一个如此复杂的项目来说，将整个游戏完全移植到一种不同的编程语言上是非常困难的。如果他们正在进行这样的迁移，他们肯定会写下来，而我没有找到任何这样的信息。

还有一个来自 2018 年的  [Eve 在线论坛主题](https://forums.eveonline.com/t/how-is-the-eve-online-client-written/60555) ，其中一名用户表示，该游戏使用 C++进行底层计算，使用 Python 进行其他一切，包括界面和图形资源管理。

因此，如果你是 Eve Online 的粉丝，请记住你正在玩一款由 Python 公司开发的游戏。

##### 5.开放数据—一家使用 Python 对抗腐败的公司

让我们回到正题上来。  [开放数据服务](https://opendataservices.coop/) 是一个为数据交换创建标准的机构，在政府和私营软件公司之间的合同中促进开放数据，并以各种不同的方式打击软件开发中的腐败。

他们工作中最耀眼的例子之一就是他们的  [开放承包数据标准如何帮助乌克兰政府节省了 15 亿美元](https://www.wired.co.uk/article/ukraine-revolution-government-procurement)。

他们的任务很艰巨，但是他们使用的工具不像开发新药的软件那样复杂。这家公司使用 Python 进行数据分析，并为他们的一个基本工具  [展平工具](https://flatten-tool.readthedocs.io/en/latest/)，这是一个 Python 库，用于将大型电子表格转换为 JSON 文档，反之亦然。

电子表格是一个简单的工具，对吗？在 Python 中使用它们时就不会了。然后他们成为做伟大工作的有力武器，这家公司证明了这一点。

使用 Python 的额外好处是 Open Data 的分析师和开发人员能够合作而不会产生误解，因为  [Python 代码易于阅读和理解](https://stxnext.com/python-vs-other-programming-languages/)。

[![Get your free ebook](img/e57940c366dfeae1f4b1d73244fdc8d0.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/dfc7061b-1a6c-40c6-8752-871f5425acf3) 

#### 您每天都在使用他们，但是您知道他们的技术堆栈中有 Python 吗？

到目前为止，我们介绍的例子只是冰山一角。

根据 Python 的  [Stackshare 页面显示，现实世界中有 6200 家公司在使用 Python。这实际上比我们上次在 2019 年 9 月](https://stackshare.io/python)的一篇文章  [中提到的时候多了约 400。我们不要忘记，这些只是选择宣传其技术堆栈的公司。](/stx-new-blog/python-vs-ruby-comparison/)

显然，Python 公司的数量正在增长。这不仅仅发生在利基市场。一些你喜欢的、全球市场领先的公司使用 Python。让我们一起探索吧！

##### 1.zapier——用 Python 实现业务流程自动化

" [Zapier 自豪地支持 Python 和开源。](https://zapier.com/engineering/zapier-at-pycon-2019/)“还需要我多说吗？

好吧，我再多说一点。首先，如果你不知道 Zapier，他们是易于使用的软件自动化的领先提供商。如果你不是程序员，你可以使用 Zapier 将收到的客户支持邮件直接发送到电子表格中，这只是一个例子。如果你是一名程序员，你可以通过编写自己的集成来做到这一点，甚至更多。

Zapier 最初是一个运行在 Python 和 Django 上的单片应用程序。  **如今构建 app 主要有两种方式:单片和微服务。** 单片是微服务的天然对立面。Monoliths 是作为包含应用程序所有功能的单一代码库构建的(我将在下一个关于优步的小节中解释微服务的不同之处)。

根据他们的开发者博客，自 2017 年以来，Zapier 团队一直在慢慢向微服务迈进。但是当你已经统治了你的市场并且想要改变你的软件的基本设计的时候，这不是一件容易的事情。

尽管如此，修改架构并不能改变他们是一家 Python 公司的事实。Zapier 以 Python 为动力而自豪。

##### 2.优步——用 Python 颠覆出租车市场

全球出租车市场的打车颠覆者不需要介绍。优步的架构基于微服务。这意味着他们为不同的功能使用不同的语言，并将它们“粘合”在一起。它不是一个单一的代码库，而是不同的、更小的代码库的混合，这些代码库相互通信。

Python 是他们架构中最大的组件之一。优步的核心从一开始就是用 Python 写的，从那以后他们就没有停止使用它。

根据优步的博客，他们还使用  [Python 机器学习](https://stxnext.com/what-is-python-used-for/#machine-learning) 框架 NumPy 和 PyTorch 来实现他们的许多 AI 魔法。他们还不断创造不同的开源 Python 工具，如[Hypothesis GU Funcs](https://eng.uber.com/hypothesis-gu-funcs-unit-testing/)，这有助于他们测试他们广泛的机器学习模型，或[Michelangelo PyML](https://eng.uber.com/michelangelo-pyml/)，这使他们能够首先更快地建立这些模型。

##### 3.udemy——用 Python 革新在线教育

你可以在 Udemy 上学习任何东西，甚至是如何用 Python 编程。  [公司的平台在后端使用 Python](https://stackshare.io/udemy/udemy) 搭建，使用 Django web 开发框架。

Udemy 向用户提供内容，处理支付，并有几项服务，如教师管理面板等。这不是人工智能药物开发，但这种规模的教育项目本身就相当复杂，要求也很高。

他们的平台上有  *很多* 的内容，还有很多动人的元素，以及一吨的流量。但是这个网站运行得很完美，它很快，很流畅，一点也不拖沓。如果你发现自己在学习新技能时欣赏 Udemy 的流畅，请记住这要感谢该公司使用 Python 这一事实。

##### 4.Spotify——使用 Python 让每个人都能欣赏音乐

音乐流媒体最大的公司之一，  [Spotify 在其后端使用 Python，并用于数据分析](https://labs.spotify.com/2013/03/20/how-we-use-python-at-spotify/)。像优步一样，Spotify 的架构也是基于微服务，他们说他们 80%的服务都是用 Python 写的。

为什么？他们提到的最大原因之一是 Python 支持的开发速度。

Python 也是最棒的数据分析语言，Spotify 知道这一点。想想 Spotify 上正在进行的所有分析:你推荐的播放列表、Spotify 收音机上的自动随机播放、发现功能、你听得最多的艺术家的年度统计。所有这些都要归功于 Python 的数据分析能力。

他们还使用 Python 进行测试和一些 API。用他们自己的话说，“甚至还有一两个 Django 的 app！”

**如果你对更多公司使用 Python 的例子感兴趣，** 查看  [Python 的 Stackshare 页面](https://stackshare.io/python)。你会发现很多你喜欢的 web 服务都使用这种强大的编程语言。

[![Read or download as PDF](img/2c383262489e8aa11258f165230cd3e3.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/70673cfa-2089-46d5-a7af-25b9b668f19e) 

#### Python 公司创造新药，模拟宇宙，扰乱市场，等等

如果你正在考虑 Python 是否是适合你公司的语言，现在你知道了  [对于各种不同的真实世界用例来说，Python 是一种非常棒的语言](https://stxnext.com/what-is-python-used-for/)。

你可以用它来发现新药，模拟宇宙，扰乱出租车市场或音乐流媒体市场，或者建立一个具有巨大内容库的颠覆性教育服务，即使在巨大的流量负载下也能顺利工作。

澄清一下，我并不是说 Python 是每个公司的最佳选择。这种说法对任何编程语言都不成立。否则就不会有这么多，也就没有理由将 Python 与其他编程语言进行比较。

然而，Python 是 STX Next 的首选工具，希望在阅读完本文后，您会理解为什么我们如此喜欢它。

如果您正在寻找一家 Python 公司来构建您的软件，我们随时准备迎接挑战！  [我们聊聊吧，告诉我们你需要什么](https://stxnext.com/contact-us/)。