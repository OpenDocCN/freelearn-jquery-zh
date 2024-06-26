# 前言

*jQuery 2.0 开发手册* 将为您提供许多可重用的代码示例，以使用最流行的客户端框架 jQuery 创建常见和独特的网站和网络应用程序元素、插件和界面。按照每个示例的逐步说明不仅会为您提供可用的代码，还会提供扩展和改进代码所需的理解。

# 本书涵盖内容

第一章，*文档对象模型操作*，讲述如何使用 jQuery 在客户端操作网页的 HTML 代码，从而创建丰富的视觉用户体验。

第二章，*利用 jQuery 事件与用户交互*，利用 jQuery 的力量来检测和响应用户交互，从而创建直观的用户界面。

第三章，*使用 AJAX 和 JSON 加载和操作动态内容*，利用 jQuery 的 AJAX 功能与 JSON 格式的数据，通过更新内容而无需刷新页面，为页面注入生机。

第四章，*用 jQuery 特效添加吸引人的视觉效果*，解释如何使用 jQuery 的特效和基本动画为网站或网络应用添加光泽，创建难忘的设计。

第五章，*表单处理*，讲述如何利用 jQuery 构建健壮的客户端验证和直观的网页表单用户体验。

第六章，*用户界面*，讲述如何打破常规，从零开始创建强大直观的界面，并通过高水平的互动吸引用户。

第七章，*用户界面动画*，讲述如何扩展 jQuery 的内置动画，并将 CSS 与 jQuery 结合起来创建可与任何网站一起使用的精彩网站模块。

第八章，*理解插件开发*，解释如何创建可重用的代码，为一系列常见的网站和网络应用程序问题提供解决方案。

第九章，*jQuery UI*，讲述如何利用 jQuery 的用户界面库来为网站或网络应用程序增添引人注目且用户友好的页面元素和界面。

第十章，*使用 jQuery Mobile*，讲述如何使用 jQuery 强大的移动框架创建移动和跨平台的网站。

# 本书所需条件

在本书中的所有配方中，您将需要一个 IDE 来编写 JavaScript、HTML 和 CSS 代码，以及一个 Web 浏览器来执行您的代码。对于本书中一些更高级的配方，您将需要一个运行 MySQL 和 PHP 的 Web 服务器。

# 本书适合谁

这本书适用于那些对 jQuery 还很新，并希望学习一些基础知识的人，或者熟悉 jQuery 并希望扩展他们的知识，并为他们的网站或 Web 应用创建一些高级组件的人。这本书是所有技能和经验水平的 Web 开发人员的绝佳资源。

# 习惯用法

在这本书中，您会发现一些区分不同信息类型的文本样式。这里有一些这些样式的示例，以及它们的含义解释。

文本中的代码词、数据库表名、文件夹名、文件名、文件扩展名、路径名、虚拟 URL、用户输入和 Twitter 句柄显示如下："任何 `$(function(){ });` 中的代码将在页面加载时由 jQuery 自动执行。"

代码块设置如下：

```js
<!DOCTYPE html>
<html>
<head>
  <title>Creating DOM elements</title>
  <script src="img/jquery.min.js"></script>
  <script></script>
</head>
<body>
<div id="container">
  <ul id="myList">
    <li>List Item 1</li>
    <li>List Item 2</li>
    <li>List Item 3</li>
  </ul>
</div>
</body>
</html>
```

**新术语**和**重要词汇**以粗体显示。屏幕上显示的文字，如菜单或对话框中的文字，都会以这种方式出现在文本中："这将向用户显示一个弹出窗口，其中包含消息**您确定要删除此用户吗？**"

### 注意

警告或重要说明将显示在这样的框中。

### 提示

提示和技巧会以这种方式出现。
