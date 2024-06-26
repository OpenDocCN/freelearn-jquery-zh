# 序言

假设你是一个中级开发者，对编写代码相当熟悉，但觉得开发 jQuery 不应该只是在文本编辑器中敲击键盘那么简单。

你说得对；任何人都能写代码。为了成为更全面的开发者，我们必须思考更广泛。那些需要理解和调试的长串代码的时代已经过去了，取而代之的是帮助我们更明智地使用 jQuery 并更有效地利用我们忙碌生活中时间的决策。

作为作者，我坚持认为简单的解决方案通常比复杂的解决方案更有效；在本书中，我们将涉及各种主题，帮助提升你的技能，让你考虑所有选项，并理解编写 jQuery 代码的更多要点。

这将是一次很棒的旅程，比侦探小说的情节更扑朔迷离；问题是，“你准备好了吗？” 如果答案是肯定的，让我们开始吧…

# 本书内容概述

第一章, *安装 jQuery*，开启了我们掌握 jQuery 世界的旅程，你将会了解到下载和安装 jQuery 不仅仅是使用 CDN 或本地链接那么简单。我们将看看如何使用包管理器安装 jQuery，如何定制我们下载的元素，以及如何添加源映射等等，以帮助调整库的副本。

第二章, *自定义 jQuery*，进一步深入；你可能会发现 jQuery 的元素并不完全符合你的要求。在本章中，我们将看看如何创建和分发补丁，以便临时应用于扩展或更改 jQuery 核心功能。

第三章, *组织你的代码*，探讨了 jQuery 设计模式的使用，这是一个在维护良好组织的代码并使开发和调试更容易的有用概念。我们将看看一些模式的示例以及它们与 jQuery 的结合方式。

第四章, *处理表单*，介绍了表单功能的权威 - 对表单响应进行验证。我们将探讨如何更有效地进行表单验证，然后在一个使用 AJAX 的联系表单中将其发挥到极致，并开发一个文件上传表单。

第五章, *整合 AJAX*，探讨了如何通过使用回调来提高静态站点上数据加载的速度，以及如何使用 jQuery 的 Deferreds 和 Promises 功能来更好地管理这些请求。我们将探讨 AJAX 的最佳实践，并探索如何通过 jQuery 的 Deferreds 和 Promises 功能来更好地管理这些请求。

第六章, *jQuery 中的动画*，带我们进入发现如何更加聪明地管理 jQuery 中的动画，并探索如何最好地管理 jQuery 队列以防止动画积压的旅程。我们还将学习如何实现自定义动画，以及为什么 jQuery 并不总是移动页面元素的正确工具。

第七章, *高级事件处理*，探讨了许多开发者可能仅使用 .on() 或 .off() 来处理事件，但您将看到，如果您真的想充分利用 jQuery，这些方法使用起来更为复杂。在我们探索如何更好地管理这些事件处理程序在我们的代码中何时被调用之前，我们将创建一些自定义事件。

第八章, *使用 jQuery 效果*，继续我们的旅程，通过快速回顾在 jQuery 中使用效果，我们将探讨如何使用回调创建自定义效果，并学习如何更好地管理形成 jQuery 中使用效果的基础的队列。

第九章, *使用 Web 性能 API*，开启了本书的第二部分，我们将在其中探讨在使用 jQuery 时可用的一些更有趣的选项。在本章中，我们将了解如何使用 Page Visibility API 与 jQuery，并了解如何使用它来提供更平滑的外观，减少资源，并仍然在我们的页面上保持复杂的动画。感兴趣吗？当您访问这一章时，您会的！

第十章, *操作图像*，演示了如何通过使用 jQuery 和一些相对简单的数学知识，我们可以对图像应用各种效果。我们可以执行诸如模糊图像之类的简单操作，也可以创建自定义效果。然后，我们将使用其中一些技术来创建一个简单的签名页面，该页面可以导出图像，并对从您自己的网络摄像头提取的图像应用各种效果。

第十一章, *编写高级插件*，涵盖了使用 jQuery 的一个关键主题：创建和分发插件。随着越来越多的功能被移到使用插件，我们将介绍一些创建自己插件背后的技巧和窍门；您会发现，这不仅仅是编写代码那么简单！

第十二章，*使用 jQuery 与 Node-WebKit 项目*，探索了一个有趣的库，它将 Node、JavaScript/jQuery、CSS 和纯 HTML 的最佳元素结合起来，形成了一种模糊了桌面和在线世界界限的东西。我们将通过一些现有的在线代码，并将其转换为桌面应用程序的使用方式，然后将其打包并在网上提供下载。

第十三章，*增强 jQuery 的性能*，带您了解一些优化和增强代码性能的考虑因素、技巧和窍门。您将看到如何轻松地从 DOM 检查器（例如 Firebug）获取基础知识，直到使用 Grunt 自动化您的测试，并最终制定一种监视代码性能的策略。

第十四章，*测试 jQuery*，是我们在 jQuery 掌握世界之旅中的结束篇章，我们将探讨使用 QUnit 测试我们的代码以及如何利用 Grunt 自动化开发中一个否则常规但重要的任务。

# 您需要本书的什么

您需要工作通过本书中大多数示例的只是一个简单的文本或代码编辑器，一个 jQuery 库的副本，互联网访问和一个浏览器。我建议您安装 Sublime Text——无论是版本 2 还是 3；它与 Node 和 Grunt 很好地配合，我们将在本书的各个阶段使用它们。

一些示例使用了额外的软件，比如 Node 或 Grunt——在适当的章节中包含了相关细节，以及从其源中下载应用程序的链接。

# 本书适合谁

本书适合希望不仅仅是编写代码的前端开发人员，而是想要探索可用于扩展他们在 jQuery 开发中技能的提示和技巧的人。要充分利用本书，您应该具备良好的 HTML、CSS 和 JavaScript 知识，并且最好在 jQuery 方面处于中级水平。

# 惯例

在本书中，您会发现一些区分不同信息类型的文本样式。以下是一些这些样式的示例，以及它们含义的解释。

文本中的代码词语如下所示：“我们将从本书的代码下载中提取相关文件；对于这个演示，我们需要`clicktoggle.css`、`jquery.min.js`和`clicktoggle.html`。”

代码块设置如下：

```js
$(this).on("click", function() {
  if (clicked) {
    clicked = false;
      return b.apply(this, arguments);
    }
    clicked = true;
    return a.apply(this, arguments);
  });
});
```

当我们希望引起您对代码块特定部分的注意时，相关行或项目将以粗体显示：

```js
$('#section').hide(2000, 'swing', function() {
 $(this).html("Animation Completed");
});

```

任何命令行输入或输出如下所示：

```js
npm install jquery

```

新术语和重要单词都用粗体显示。你在屏幕上看到的字词，例如菜单或对话框中的字词，都会出现在文字中，就像这样：“当我们查看页面并选择**图像**标签后，经过短暂的延迟，我们应该看到六张新的图片。”

### 注意

警告或重要备注将出现在这样的一个框内。

### 贴士

贴士和技巧会以这种方式出现。
