# 什么是 TypeScript？TypeScript 与 JavaScript 的优缺点

> 原文：<https://www.stxnext.com/blog/typescript-pros-cons-javascript/>

 当我们想到  [前端开发](https://stxnext.com/services/javascript-development/)时，首先想到的是 HTML、CSS 和 JavaScript 等关键术语——浏览器标准的页面显示、样式和脚本方式。

但是如果我们再深入一点，我们肯定会遇到一些流行词汇，比如 [React](/services/react-native-development/) 、Angular 或 TypeScript。

等一下…打字稿？既然已经有了广泛使用的标准化解决方案，为什么还有人想要或需要另一个“脚本”呢？

继续读下去，你会发现的。**我们来展示一下哟**

1.  **什么是 TypeScript 以及它与 JavaScript 的关系，**

3.  **提升你正在进行的(甚至是长期运行的)是多么容易啊！)带有 TypeScript 的项目。**

[![Read or download as PDF](img/2c383262489e8aa11258f165230cd3e3.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/70673cfa-2089-46d5-a7af-25b9b668f19e) 

#### TypeScript vs. JavaScript:什么是 TypeScript，它与 JavaScript 有什么不同？

你可能已经听说过“TypeScript”这个词了。这当然不会是一个惊喜；2019 年，TypeScript 是 GitHub 上第 7 个使用最多的  [和第 5 个增长最快的语言](https://octoverse.github.com/) ，其编译器的周下载量超过 500 万次。

但是到底什么是 TypeScript 呢？

简单来说， **TypeScript 是微软开发的编译成 JavaScript 的开源编程语言。** 自 2012 年发布以来，这种语言一直保持着积极的发展，每年都在继续流行。

开发社区在早期强烈地将 TypeScript 与 Angular 联系在一起，尽管它们从一开始就是不同的创造。这是因为 Angular 迫使您使用 TypeScript，尽管绕过它是可能的。在我们的[React 和 Angular](/stx-new-blog/react-vs-angular-comparison/) 的比较中，我们会更多地讨论这些技术之间的关系。

TypeScript 和 JavaScript 之间最重要的区别是它们是两种独立的编程语言，尽管 TypeScript 在很大程度上基于 JavaScript。 其实 TypeScript 是 JavaScript 的一个  *超集* ，意思是所有有效的 JavaScript 代码也是有效的 TypeScript 代码。

TypeScript 没有改变 JavaScript，而是用新的有价值的特性扩展了它。  凡是能用 JavaScript 写的，也能用 TypeScript 写:

*   [任何框架中的前端](/stx-new-blog/react-vs-angular-comparison/)，
*   [node . js 中的后端](https://stxnext.com/blog/2018/10/16/python-vs-nodejs-comparison/)，
*   [React Native 中的跨平台移动应用](/stx-new-blog/cross-platform-mobile-development/)。

这意味着你也可以毫不费力地用 TypeScript 编写 React 应用程序！

##### TypeScript 如何改进 JavaScript？

**TypeScript 带给 JavaScript 的关键增强是一个类型系统** (因此得名“TypeScript”)。

如果您不熟悉这个词，“类型”是一个定义，它告诉您给定数据的预期用途(例如，我们有数字、布尔或字符串类型，仅举几例)。

传统上，JavaScript 是  **动态** 类型化的([很像 Python](https://stxnext.com/python-vs-other-programming-languages/) )。这意味着单个变量可以包含文本、数字，甚至是整个数据库实体，这取决于具体情况——这就很好。**TypeScript 做的是严格定义一个给定的变量可以包含什么。**

假设你的一个开发人员写了一个*add numbers*函数，并使用类型定义该函数只能接受两个数字。如果另一个开发人员试图向函数提供文本，TypeScript 将返回一个错误，而在 JavaScript 中这样的操作是完全可以接受的。

##### TypeScript 的主要优势是什么？

更深入地研究技术细节，TypeScript 为您提供了:

##### **1。严格打字**

一切都保持我们定义的样子。需要一个变量总是一个数字吗？那就永远是个数字。

##### **2。结构分类**

当您关心完全定义您使用的实际结构时，这是必不可少的。JavaScript 允许做很多奇怪的事情，所以依赖特定的结构是一个更安全的解决方案。

##### **3。类型注释**

明确说明应该使用什么类型的简便方法。

##### **4。类型推断**

由 TypeScript 本身执行的隐式类型，这样您的开发人员就不需要提供编译器可以自己找到的类型。

对我来说，打字稿的主要优点是自我暗示。目前，我正在用 JavaScript 编写代码，这是我最想念 TypeScript 的地方。仅仅为了查看类型而不得不来回跳转文件很快就让人厌倦了。

我个人的 TypeScript 成功故事是，由于它，我已经能够说服我们的 Java 团队为 web 编写我们应用程序的新部分，并从我们遗留的 Swing/JavaFX 堆栈转向 React。习惯于静态类型编程语言的开发人员根本离不开编译器的指导。你需要类似于 TypeScript 的东西把它们转到 web 或 Node.js 上

**—Dawid Czarnik，STX Next 的 Node.js 开发人员**

##### TypeScript 的几个附加功能

您会很高兴地了解到 TypeScript 不仅仅是关于类型的。

微软最初打算创造一种更适合大规模解决方案的语言。那是在 ECMAScript 5 糟糕的旧时代，ECMAScript 5 现在是 JavaScript 的同义词。

不要误解我的意思，那个版本的 JavaScript 是绝对可用的，直到今天它仍然在 web 上使用。但是用 ECMAScript 5 编程，说得委婉一点，对于来自完全面向对象的环境(如 Java 或 C#)的开发人员来说，是特别特别困难的。

微软已经在使用 C#，通常被称为“更好的 Java”，并越来越多地进入服务器端应用程序。然而，在前端，市场上最常用的解决方案是 JavaScript。这就是为什么微软决定写一种基于 JavaScript 的语言，但与那些后端语言有更多的相似之处。

**TypeScript 引入了大量取自面向对象编程的语法，包括但不限于:**

*   **接口，**
*   **类，**
*   **枚举类型，**
*   **仿制药，**
*   **模块。**

诚然，ECMAScript 6(或 ECMAScript 2015)向 JavaScript 引入了其中一些功能——但不是全部。例如， **抽象类或访问修饰符在 JavaScript 中仍然找不到，而 TypeScript 却有。**

作为 JavaScript 的超集，最好的部分是什么？ **每一个新的 JavaScript 特性也是一个新的 TypeScript 特性。**

*根据我的经验，TypeScript 在中型和大型项目中提供了特别显著的好处。我鼓励开发人员从头开始在 TypeScript 中创建这些项目，因为迁移现有的代码库总是需要大量的工作，即使当你采用“软”策略时也是如此。*

**—Krzysztof kósy，STX Next 的 JavaScript 开发者**

**[![Read our case studies](img/eaf2d73bc39be15e20451ce86a36ad75.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/ccf9def3-1cba-4781-a997-a8c43f67adca)** 

##### 在 Twitter 上加入讨论吧！

> 听说过 [#TypeScript](https://twitter.com/hashtag/TypeScript?src=hash&ref_src=twsrc%5Etfw) ？
> 
> 肯定有。
> 
> 每个开发商都有。
> 
> 但是你*用*它了吗？
> 
> 如果没有，让我们告诉你为什么你应该
> 👇👇
> 
> 螺纹
> 
> — STX Next (@STXNext) [May 5, 2022](https://twitter.com/STXNext/status/1522122469380968448?ref_src=twsrc%5Etfw)

#### 打字稿的缺点

当然，世界上没有完美的东西，无论是物理的还是数字的。TypeScript 也不例外，它确实有一些缺点。

##### 1.过于复杂的打字系统

首先，打字系统虽然在很多方面都是一个很好的工具，但有时使用起来有点太复杂了。不过，严格来说，这并不是 TypeScript 的缺点，而是因为它与 JavaScript 完全互操作，这本身就给复杂性留下了更大的空间。

##### 2.必需的编译

反对 TypeScript 的另一个理由是它需要编译，而 JavaScript 不需要。但是，老实说，现在大多数 JavaScript 应用程序都需要一个构建步骤。无论是 Gulp、Grunt、Webpack、Rollup、Babel 还是 Closure——构建步骤都是必要的，没有什么能真正阻止你扩展它。

##### 3.虚假的安全感

在我看来，TypeScript 最大的缺点就是会给你带来一种虚假的安全感。是的，这是一个巨大的好处，语言可以为我们检查类型，并在我们的代码有问题时警告我们。然而，过于依赖这一点会带来很大的风险:  **一些开发人员倾向于认为他们用 TypeScript 编写的任何东西都是 100%防弹的。不是的。**

TypeScript 仅在编译期间执行类型检查。之后，我们处理的是不具备这种功能的纯 JavaScript。这意味着我们可能仍然会遇到一些编译器没有发现的错误，尽管不可否认的是，这些错误会比我们没有使用 TypeScript 时少得多。

#### TypeScript 的优点和缺点:STX Next 开发人员的观点

我们问我们的程序员，对于使用 TypeScript 工作，他们真正喜欢和不喜欢什么。以下是我们的高级 JavaScript 开发人员之一 przemyslaw Lewandowski 对此的看法。

如果你知道什么时候使用 TypeScript，并且它的配置符合你的需求，那么与普通的 JavaScript 相比，这将是一个巨大的优势。如果你是一个项目的新手，拥有类型是有益的。您将立即知道每个函数需要的确切参数或它返回的复杂结构。

与适当的命名和代码分割相结合，键入是另一种编写可读性强、不需要额外注释的自解释代码的工具。

当我和我在 STX 的同事接下来将它引入我们接手的 fintech 中的一个普通 JavaScript 项目时，它在应用程序的新部分中工作得很好。我们不再需要通读大量的函数组合来知道它们的结果是什么。

它还帮助我们组织和标准化具有大量嵌套对象的复杂财务数据结构。

最后，在类型不匹配的情况下，它帮助我们避免了许多问题。简而言之，我们有了更具体的、更好记录的、更高质量的防弹代码。

然而，和其他任何东西一样，TypeScript 也有它的缺点。过于严格地设置 TypeScript，例如，不得不在不依赖类型推断的情况下手动键入所有内容，这可能会令人疲惫和沮丧。

另外，如果你需要快速原型化一些东西，我个人会选择普通的 JavaScript，因为它给了我更大的自由和更少的代码。

在向 TypeScript 项目中引入新的库时，你也需要小心——向它们添加类型定义仍然不是一个标准。满足您需求的那个库不一定要编写它们。你要么自己写，要么另找一本。

我还发现对 TypeScript 要求更高的是编写单元测试。当您刚刚学习 TypeScript 时，模仿事物是具有挑战性的，因为所有事物都要求获得特定类型及其所有属性。在 JavaScript 中，您不必担心这一点。只传递在这个特定测试中需要的属性。

#### 有哪些替代打字稿的方法？

TypeScript 并不是将类型引入 JavaScript 或前端开发的唯一工具。还有其他的，我们现在来看看。

##### 1.TypeScript vs . Flow——脸书的类型检查系统

Flow 也是 JavaScript 的一个超集，但它没有被归类为一种独立的语言。像 TypeScript 一样，Flow 提供了类型注释…仅此而已。没有额外的语法，一切都和 JavaScript 中的一样。

那么，当 Flow 涵盖了它最重要的特性时，为什么使用 TypeScript 更好呢？

首先，  [TypeScript 更受欢迎](https://www.npmtrends.com/typescript-vs-@babel/preset-flow-vs-babel-preset-flow)，这意味着它有更好的支持。因此，更好的支持意味着与使用 Flow 相比，您更有可能获得外部库的 TypeScript 类型定义。

其次，2019 年，  [脸书决定将 Jest——其最受欢迎的项目之一——从 Flow 转移到 TypeScript](https://github.com/facebook/jest/pull/7554#issuecomment-454358729) 。我相信这是不言自明的。

##### 2.TypeScript vs . JSDoc—支持类型的文档标准

JSDoc 是记录 JavaScript 代码的活标准。它不仅允许您使用文本来编写每段代码在做什么，还允许您注释类型。

开发环境支持 JSDoc，但它远非完美。用 JSDoc 进行正确的输入是困难的，它需要比 TypeScript 多得多的代码。

不过，真正的亮点是，您可以用 TypeScript 编写 JSDocs 这也是那里的一个标准。唯一的区别是您不需要提供类型，因为默认情况下 TypeScript 有更好的工具。

##### 3.其他编译成 JavaScript 的严格类型语言

多年来，我们已经看到许多语言提供了严格的类型系统，并且可以以某种方式编译成前端代码:

1.  **Kotlin** 有官方的 JavaScript 编译解决方案。
2.  **锈** 可能在前端工作；然而，它不直接编译成 JavaScript，而是 WebAssembly。然后，这个 WebAssembly 代码可以与 JavaScript 代码结合使用。
3.  **Go** 可以有效地编译成 JavaScript——通过一个叫做 GopherJS 的非官方工具——或者 WebAssembly，就像 Rust 一样。
4.  **榆树****原因** 是为 JavaScript 编译而设计的。

所有这些语言都很棒，但 TypeScript 有一个关键优势，使其更适合前端开发:  **对于当前的 JavaScript 开发人员来说，TypeScript 更容易学习，主要是因为它只是增强的 JavaScript。**

我列出的备选方案也有不同的语法——其中一些甚至使用了其他编程范式——这使得从 JavaScript 切换到 TypeScript 更加费力和复杂。

[![Software development](img/839cbcb352d37e77995fce8799fa8662.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/0234a030-b669-4efc-af8d-baa810d43217) 

#### 如何将正在进行的项目从 JavaScript 迁移到 TypeScript？

阅读了所有对 TypeScript 的高度赞扬之后，您可能想知道您当前的 JavaScript 项目如何从中受益。好吧，让我告诉你，很有可能他们已经是了！

这是因为像 WebStorm 这样的最先进的开发环境正在使用 TypeScript 类型定义来促进使用外部库的代码开发。

当然，那只是部分好处。当前的情况使开发人员的工作变得稍微容易了一点，但是它仍然没有提供像类型检查这样的好东西。

因此，在您将您的项目迁移到 TypeScript 之前，还有一个关键问题需要我们回答:  **正在进行的项目可以轻松迁移到 TypeScript 吗？**

**答案是:可以，他们可以。** 更重要的是，过渡很可能不会像看起来那么耗时！这里有两种方法来执行这种迁移。

##### 1.困难的方法:所有的东西一次打印出来

简单地将所有代码重写为 TypeScript 可能看起来是进行转换的最明显的方式，但这也是最困难和最耗时的(至少在开始时)。

正如我们已经知道的，有效的 JavaScript 代码也是有效的 TypeScript 代码，所以从技术上讲，您并不是从头开始编写所有代码。大多数时候，您将更改文件扩展名，运行编译器，并修复您发现的所有键入错误。此外，您可以用不同的方式配置类型检查机制，因此您对它越严格，修复所有问题所需的时间就越长。

这是完全可行的。然而， **这种全员参与的方法最适合小项目和小团队。** 这不是你可以轻易并行化的工作，你必须在这个过程中暂停你的开发，所以你不可能同时实现新的特性。

**走这条路的好处是，它是面向未来的**。

##### 2.软方法:在 TypeScript 中只有新的东西

由于 TypeScript 和 JavaScript 的互操作性，可以在编写 JavaScript 代码的同时编写 TypeScript 代码。TypeScript 模块可以在 JavaScript 中使用，反之亦然；编译器会知道该怎么做。

这很好，因为这意味着您实际上不需要一次移动整个项目。您的团队需要做的就是花几个小时在您的项目中配置 TypeScript，并移动一些基本代码——就是这样！

之后，由开发人员负责确保每个新特性都是用 TypeScript 而不是 JavaScript 编写的。自然地，只要有一些旧代码需要编辑，您就可以安全地将它转移到 TypeScript 中。修复一个文件中的错误比修复成百上千个文件中的错误更容易。

**这种方式最适合有很多人参与的大中型项目**。

不利的一面是，以后您仍然需要处理遗留的 JavaScript 代码。 最终，你将不得不把剩下的代码转移到 TypeScript，这将需要一些时间。这种划分的另一个可能的副作用是，您的 TypeScript 代码的某些部分可能键入错误，尤其是在使用旧代码的地方。

尽管有这些小缺点，如果你决定在你正在进行的项目中包含 TypeScript，我仍然推荐选择这种方式。

#### 关于打字稿的最终想法

总的来说，TypeScript 对于 JavaScript 开发人员来说是一个非常棒的工具。它使大型项目的工作变得更加容易，并提供了一个更好的代码编写工具包，可以极大地改进您的软件开发过程。

TypeScript 很受欢迎，受到业内最大玩家的信任，并不像许多人认为的那样困难。  **说到底，TypeScript 在骨子里还是刚刚好的 ol' JavaScript。**

最重要的是，TypeScript 为您的开发人员和项目涉众提供了切实的好处。只要多写一点代码，这种语言就能帮助您的团队快速实现  **更好的整体性能:更少的 bug，更快的发布，对代码质量更有信心。**

每一个使用或者将要使用 JavaScript 的项目都会从 TypeScript 中获益。事实不会说谎，纵观 JavaScript 的世界里漂浮的所有数字和科技新闻，  **TypeScript 是未来，未来就是现在。**

你的项目会是下一个加入前端革命的项目吗？由你决定！

感谢您阅读我们关于使用 TypeScript 进行前端开发的好处的文章。我们希望你能在你的下一个软件项目中尝试这个令人敬畏的解决方案。

你对 TypeScript 或软件开发有什么问题或建议吗？请随意将它们留在这里，我们会很乐意与您联系。

如果您需要或  [后端](https://stxnext.com/services/python-development/) 任何形式的支持，  [我们的大门永远为您敞开](https://stxnext.com/contact-us/)！

[![Get a project estimate](img/33a5cf5f1dda99377719e33bff42de03.png)](https://cta-redirect.hubspot.com/cta/redirect/4542168/1ec1ddae-fe98-45ce-ad83-e2e4a20ca20e)