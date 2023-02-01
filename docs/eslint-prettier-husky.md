# 如何防止 ESLint、Prettier 和 Husky 的意外代码错误

> 原文：<https://www.stxnext.com/blog/eslint-prettier-husky/>

 任何软件工程师，不管他们的进步水平和经验有多少年，都可能有糟糕的一天，并意外地引入将导致错误或不适合良好代码开发实践的更改。

幸运的是，有几种方法可以保护您的 JavaScript 项目免受这种情况的影响。

我假设你首先想到的是使用各种类型的测试。当然，它们是最有效的方法，但是我们将在本文中处理其他内容。

我们将关注代码本身，而不是测试应用程序的功能来保护你的软件项目免受开发人员的意外错误。为此，我们将使用:

*   **ESLint** 用于分析 [JavaScript](/services/javascript-development/) 代码，发现潜在的 bug 和不良做法，
*   **更漂亮**按照 [采用的标准](https://prettier.io/docs/en/option-philosophy.html) 对代码进行格式化，
*   Husky 允许我们与 Git 挂钩集成，这反过来又允许我们自动化之前的两个工具。

所有这些工具都可以很好地与 [any Node.js 项目](/services/nodejs-development/) 配合使用。因为我想给你一些配置的具体例子，所以我将用一个用 Create React App (CRA)创建的“纯”React.js 项目来讨论这些例子。 

#### 使用 ESLint 进行代码分析

先说 ESLint。这是一个所谓的 **linter，**是一个静态分析 JavaScript 代码以发现任何潜在问题的工具。它可以以两种不同的方式对它们做出反应——要么将其标记为**警告**(并在控制台中显示适当的消息)，要么标记为**错误**(在这种情况下，我们不仅会看到消息，而且代码的编译也会失败)。

如果您使用过 React，您可能会在浏览器控制台中看到不止一个警告或错误。有些是 ESLint 的效果。它与我们使用 CRA 创建的应用程序相集成。然而，它有一个非常简约的配置。