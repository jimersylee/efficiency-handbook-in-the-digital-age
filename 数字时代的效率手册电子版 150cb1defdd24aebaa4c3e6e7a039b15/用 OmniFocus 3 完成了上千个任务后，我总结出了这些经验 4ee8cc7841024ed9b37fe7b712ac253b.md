# 用 OmniFocus 3 完成了上千个任务后，我总结出了这些经验

[https://sspai.com/post/49105](https://sspai.com/post/49105)

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/f3da99eaa14aef620ccc39680c28a54a.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/f3da99eaa14aef620ccc39680c28a54a.png)

OmniFocus 3 距离发布到现在已经有半年多时间了，在这半年多时间里面，我用 OmniFocus 3 完成了**上千个任务**。在这个过程中，经过不断尝试和优化，最终找到了一套非常适合自己的工作流程。

这篇文章篇幅较长，全文总共约八千字，建议分成两次阅读。前半部分内容主要介绍一些时间管理方面的理论，后半部分内容我会结合 OmniFocus 3 分享自己的一套工作流程。

首先在开始之前，我想说的是「工具其实是次要的，想法才是关键」。有了基本的思路，无论是 OmniFocus、Todoist 还是 Things，都可以有自己的一套方式来实践。另外每个人都有一套适合自己的工作流，所以读者不必要完全按照我所写的来操作，正确的方式是从中获取一些灵感，实践并融合到自己的工作流当中。

## 什么是一个好的任务管理系统

首先，任务管理系统的目的是为了更好得完成任务，一切脱离这个基本条件的系统都是不可用的。如果你觉得一个最简单的 Todo List 就能很好地完成任务，那么这就是最适合你的任务管理系统。

在我看来，一个优秀的任务管理系统至少需要满足以下条件：

1. **收集能力**
2. **在特定的情况下要知道可以做哪些事情**

为什么需要至少满足这两个条件呢，或者说这两个条件对于任务管理系统来说，重要在哪里？

「收集能力」指的是这个任务系统要能够容纳（几乎）所有的内容，一个任务、一条想法、一封未读的邮件、一个笔记、一个链接、没有报销的发票等等。

如果有读过《Getting Things Done》或者了解过 GTD 理论的同学可能就知道，「收集」是整个流程中最开始的一环。如果要做的任务散乱在各处，难免会有遗忘的时候，任务没有被收集到，也就没有后面的处理流程了。

具体实践起来并不是真的需要把所有的东西都塞进任务系统里面，例如我使用 Evernote 作为剪裁和笔记的工具，很显然把每条笔记都复制一份到 OmniFocus 中很不现实，但是我会在 OmniFocus 中添加一个「定期清理 Evernote Inbox」的任务，这样就相当于把 Evernote 作为 OmniFocus 的子 Inbox，来统一进行管理。对于一些支持 URL Schema 的应用，完全可以在 OmniFocus 中建立一个链接直接指定，这样在 OmniFocus 中也可以直接打开其他应用中的内容了。

**收集能力决定了要处理的内容，第二个条件则决定了一个任务系统是否是稳定可用的**。具体的情境来说，你要知道早上的时候该干哪些事，工作的时候该干哪些事，无聊的时候又该干哪些事等。这样，在某一情境下，可以直接进入状态，而不是要花时间思考现在到底要做什么。

一个任务系统如果做好了这两件事情，那么就不会让你身处「感觉有很多事情要做，却不知道要做什么」的尴尬境地了。

## 任务管理系统的三要素

到现在为止，我还没有讲到具体工具的使用。因为工具是次要的，了解了本质的思想，使用什么工具都没有问题。纵观各种任务管理的工具：OmniFocus、Todoist、Things、org-mode，它们支持的功能也各不相同，Project、无限层级、Defer、Due、Repeat、Context、Label、Tag、Filter、Perspective 等等，有没有被这些名词给吓到？难道我们每切换一种系统都需要再重新学习一遍？

抛开这些名词，我们来分析一下一个任务系统到底是由什么组成的。在我看来，一个任务系统最本质的东西只有三个：任务、附加元素和过滤器。

**任务**：一个最小可执行的单元即为一个任务。这个是最好理解的，所以不做过多解释。

**附加元素**：作用在任务上的不同维度的限制。这句话读起来有点拗口，举个简单例子，「去 XXX 取快递（截止今天 10:00）」，其中，「截止今天 10:00」就是在时间维度上对这个任务的一个限制。同样的，「项目」、「标签」等等这些都是作用在某个任务上的附加元素。

**过滤器**：组合不同附加元素的过滤规则。只有附加元素并没有什么实际的作用，但是有了过滤器之后，就可以编写不同的过滤规则来过滤指定规则的任务。例如，我想知道「最近 10 天内重要的事情」，那么过滤规则可能就是「Due date < 10 and flagged」。

了解了上面三个基本的概念，那么再重新审视各种任务管理工具，就可以从一个比较宏观的角度来看待了，这也可以避免切换工具造成的重新学习成本。

这三个概念和 Hum 在[《用更现代的方式做任务管理》](https://sspai.com/series/1)提出的「**LTF（列表、标签、过滤）**」理论十分类似，并且 Hum 用了更大的篇幅来叙事这个概念，有兴趣的可以订阅这个栏目阅读。

## OmniFocus 3 实践

把上面任务系统的基本三要素运用到 OmniFocus 上，任务就是一个个的单独 Todo item，附加元素就是 Todo item 所属的项目、Due Date、Defer Date、Tags、Flag、Repeat rule 等，过滤器就是透视（Perspective）。

接下来的内容我会通过 OmniFocus 3 为载体，来具体介绍如何实现一个可靠的任务管理系统，并介绍一些实际实践过的 Workflow 流程。

### 项目的设定

项目的设定建议使用统一的一套项目设定，例如，我的 OmniFocus 的项目和 Evernote 笔记的项目几乎是一一对应的，这样做的好处可以保证你的项目分类始终处于一个有序的状态。

如果想保证项目比较有序，分成三个层级即可：**大的领域（Folder）- 子领域（Folder）- 项目（Project）**。

例如，我的项目分级如下：

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/dad99ce26e36cead15327a93650c063e.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/dad99ce26e36cead15327a93650c063e.png)

OmniFocus 项目分类（点击查看大图）

我主要分成了 5 个比较大的项目：工作、学习、生活、兴趣、系统，基本上可以涵盖涉及到的所有领域了。在每个大的项目中再细分出小的项目，这个可以根据自己的需要来进行细分。OmniFocus 支持无限层级的项目划分，但是个人只建议分三层，最后一层直接是任务就可以了，这样可以保证项目层级不会过于复杂。

可以看到很多项目下面都有用`[]`括起来的项目，这个是 Single List 项目，这样一些不属于某个项目里面的内容就可以放到这个列表里了。

项目的分类并不一定要按照我的来，只要保证一定的规整化即可。

一些项目设定的 Tips：

- 如果不是 Single List，项目需要一个既定的完成条件，在某一时刻或某一条件下，这个项目是要能够被标记为 Completed 或者 Dropped，这样可以避免一个项目长时间地呆在任务系统中；
- 项目中的任务最好是最小可执行的，如果是比较大的任务，可以利用 OmniFocus 的无限任务层级继续细分。

### 标签的设定

OmniFocus 3 的标签系统可以在自带功能的基础上添加更多的附加元素，从而在设定过滤器的时候更加准确地过滤出符合的任务。基于此目的，可以根据需求设定出适合自己的标签系统。

OmniFocus 3 缺失的一个很常见的功能就是 Schedule，一个任务在时间维度上应该有有截止日期（Due）和安排日期（Schedule）两个元素，Due 表示在某一天之前必须被完成，Schedule 表示被安排到某一天做，所以可以设定如下标签来完成 Schedule 的功能：

- Schedule
- ThisMonth：被安排到这个月
- ThisWeek：被安排到这周
- Today：被安排到今天
- Recently：最近需要做的事

这样在做计划的时候，打上对应的标签，就可以使用过滤器过滤出对应的任务了，比如我想看「这个月和工作相关的任务」，那么就可以指定 Project 为「Work」项目，标签为「ThisMonth」，这样对应的任务就可以使用这个过滤器过滤出来，具体的过滤器设定下面会讲到。

另外一个可以借鉴的设定就是精力值标签：

- Energy
- LowEnergy
- MediumEnergy
- HighFocus

例如，我们工作了一整天之后，还剩一段时间才下班，精力已经下降到一个很低的值，这个时候已经不适合完成一些需要非常专注的工作了，但是一些工作上的杂事，例如打印东西，提交报表等简单的工作可以利用这个时间来完成，这个时候我们就可以设定一个过滤器，过滤出 Project 为「Work」，标签为「LowEnergy」的任务。

我们可以看到，标签系统可以极大地扩展附加元素的内容，给过滤器添加更多的过滤维度。标签系统的设定应该根据自己的需求来，如果设定的标签却没有在过滤器中用到的话，那么也仅仅是个任务添加了一个没有用上的附加元素而已，意义不大。

### 过滤器的设定

过滤器的目的就是组合各种条件，过滤出所需要的任务来，之前所有的任务上的附加元素都是为了过滤器而设定的。

过滤器在 OmniFocus 3 中就是透视（Perspective）。在 OmniFocus 3 中，透视功能被很大的增强了，支持类似于 iTunes 智能播放列表一样的设定。

iTunes 智能过滤器

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/eed9478b74c91372eb12e002fbe9e1c7.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/eed9478b74c91372eb12e002fbe9e1c7.png)

但是仔细使用下来会发现，OmniFocus 3 的过滤器设定依然是有局限的，并不能想 iTunes 那样自由地对元素进行操作。

OmniFocus 过滤器可设定元素

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/c97692c906884df2762ca08318b12829.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/c97692c906884df2762ca08318b12829.png)

尽管如此，相比较 OmniFocus 2 残疾一样的过滤器设定，已经好太多了。用过 Todoist 的同学可能会知道，Todoist 的过滤器设定支持自定义的一套语法，OmniFocus 3 与之相比，还是要差了许多，主要是提供的可过滤元素太少，过滤条件也不够自由，但是结合标签系统也基本上能满足日常的使用。

同标签系统一样，过滤器的设定依然需要结合自己的情况来。我主要设定了以下几个过滤器，这些过滤器都是在实践中经常使用到的。

OmniFocus 过滤器

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/b05ac79d69bb1dd3d087e311d603e7b9.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/b05ac79d69bb1dd3d087e311d603e7b9.png)

### Routine 过滤器

这个过滤器主要被用于制定计划，例如，我每天早上去公司都会有 Morning Review，来规划今天一天的工作任务。这个时候，我只需要打开这个过滤器，依次把上面的事情做完，今天的计划安排就被制定好了。

过滤器的详细设定如下：

Routine 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/34fc1e02c6b4344dff1335ccb24743af.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/34fc1e02c6b4344dff1335ccb24743af.png)

其中，「Routine」Folder 中就是设定的具体内容：

Routine 过滤器视图

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/ea316f9bcad7e4bcee8651ae319c7ea8.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/ea316f9bcad7e4bcee8651ae319c7ea8.png)

这一个过滤器的设定是和我的 Workflow 紧密相连的，如果你没有做 Morning Review 之类的习惯，可以不需要设定这个过滤器。

### Today 过滤器

这个过滤器被使用的次数最多，类似于 Forecast 的功能，但是相比较 Forecast，自定义的程度更大。

过滤器的详细设定如下：

Today 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/5a26cdedabb120eae33d48b75bd4fdbb.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/5a26cdedabb120eae33d48b75bd4fdbb.png)

这个过滤器将会把符合以下条件的任务过滤出来：

- 即将截止或者标注为 Today 标签的任务
- 状态为 Available 的任务
- 非 Routine Folder 下的任务

显示方式以 Project 为维度显示：

Today 过滤器视图

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/6e584d0713f592dba7318e39931a1d51.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/6e584d0713f592dba7318e39931a1d51.png)

对比 Forecast Perspective，它只是把对应的任务都展示了出来，在任务的层级上没有自定义的那么清晰。

Forecast 过滤器视图

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/49e4929c692acd0081f9c02bc136d8eb.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/49e4929c692acd0081f9c02bc136d8eb.png)

如果想要 Forecast 显示特定标签的任务，可以参考如下设定：

Forecast 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/6b1d6134b0a87bb5648729b2937b4e21.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/6b1d6134b0a87bb5648729b2937b4e21.png)

### Work 过滤器

这个过滤器和 Today 类似，只不过指定了所属项目为「Work」文件夹下面的任务，这个主要是在工作中只想专注于和工作相关的任务。

过滤器的详细设定如下：

Work 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/de222c8adda99c45f0eba7816fca4a68.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/de222c8adda99c45f0eba7816fca4a68.png)

除了指定了特殊的项目目录，其他的设置和 Today 的设定没有区别。

### To-Sth 过滤器

日常的使用中，我会把没有看的文章、需要写的东西、要读的书、要搜索的内容都存在 OmniFocus 中，所以需要一个过滤器能够快速过滤出这些内容。

首先使用这个过滤器需要先设置一套标签系统：

To-Sth 标签设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/1043b7faa553e1879ddb4b5a6950c49e.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/1043b7faa553e1879ddb4b5a6950c49e.png)

过滤器的详细设定如下：

To-Sth 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/24447d851a3572447825b333f6f8787c.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/24447d851a3572447825b333f6f8787c.png)

实际的使用场景：比如我想阅读一些和 Python（一门编程语言）相关的内容，那么我只需要打开这个 Perspective，挑选标签为「To-Read」，然后从搜索框中搜索 Python 关键字就可以了。

To-Sth 过滤器视图

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/2405d7e3a3c81fcebc074e25faf94b9b.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/2405d7e3a3c81fcebc074e25faf94b9b.png)

### Future 过滤器

这个过滤器主要被用于制定计划，在 Weekly Review 和 Daily Review 中会被频繁地使用到。需要基于以下的标签设定：

Schedule 标签设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/2224a6248003049383c0d66adb2f3966.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/2224a6248003049383c0d66adb2f3966.png)

过滤器的详细设定如下：

Future 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/c3fa356de106cc74c4f9a9718a0ba72b.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/c3fa356de106cc74c4f9a9718a0ba72b.png)

### EasyDo 过滤器

这个过滤器会把一些简单的或者不需要太多精力的任务过滤出来

过滤器的详细设定如下：

EasyDo 过滤器设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/a3f71c72d594c866f4a702a2562db62a.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/a3f71c72d594c866f4a702a2562db62a.png)

完成时间小于 15 分钟或者被标注为「LowEnergy」标签的任务会被过滤出来。

### Workflow

今年使用 OmniFocus 已经完成了 1500+ 的任务，经过这么长时间的使用，已经有了自己的一套任务处理流程了，随着 OmniFocus 3 的更新，这套任务处理的流程也经过了一些优化。在这整个 Workflow 中，主要分为三个部分：计划、执行、总结。

### 计划

很多人都不重视计划这个环节，想到什么做什么，这样不仅会做事没有条理，也会分不清任务的优先级。

一般来说，如果不知道怎么做计划的话，有一个长期计划和一个短期计划就可以了。长期计划主要是一个大体的方向，可以是年度计划或者月度计划；短期计划则需要明确具体要做哪些事情，可以是周计划或者日计划。

实践过程中使用最多的就是周计划和日计划。在 OmniFocus 中，我设定了两个项目，分别是 Weekly Review 和 Morning Review。

在做 Weekly Review 的时候，我会先在 Evernote 中大概写一下这周需要做哪些事情，然后在 OmniFocus 中打开 Future 过滤器，选择 ThisMonth 标签，把需要完成的项目和任务打上 ThisWeek 标签。

在做 Morning Review 的时候，我会打开 Future 过滤器，选择 ThisWeek 和 Recently 标签，然后挑选今天需要完成的事情打上 Today 标签，这样，在 Today 和 Work 过滤器中就可以看到今天要做的事情了。

### 执行

执行应该是整个 Workflow 中最重要的一个环节，如果只是计划了，但是最后任务却没有被完成，那做计划也只是白费力气。

执行的关键就是要在对的时间内做对的事，这也是为什么要设置那么多过滤器的原因，在工作的时候就只展示工作相关要做的事，在没有精力的时候就只展示简单易做的事情。

如果你做事情的时候很容易分心，可以参考一下番茄工作法，一般我会设置为专注 50 分钟，然后休息 10 分钟。默认的 25 分钟时间过短，可能刚进入状态就要被打断。

另外可以尝试使用「结构化拖延法」（Structured Procrastination）。结构化拖延法就是忽略优先级高的事，而是从小的事，优先级比较低的事情开始做，这样慢慢地进入工作的状态，然后再去完成优先级高的事情。

### 总结

总结是为了更好地计划。总结给计划提供了更多的参考条件，可以当做计划的一把标尺。

很多时候我们做计划都会看高自己完成任务的能力，结果就是一周过去了发现实际上并没有能够完成计划的内容，如果没有总结的话，下次做计划的时候还是按照这种量来计划，必定也是完成不了的，久而久之，就失去了做计划的动力。如果每周都做总结的话就能够知道这周完成了哪些内容，哪些内容没有完成，原因是什么，这样就能在下周的计划里面做改进。这种「反馈-调节」的机制可以促进整个任务处理流程的良性循环。

一方面，如果你在 Evernote 中有写周计划的话，那么在每周的 Review 时候就可以打开对应的项目，在 Project 视图里面选择 All，这样就可以把所有的任务（包括已完成的）都展示出来，方便对照查看完成了哪些，又有哪些是没有完成的。

Project 视图设置

![%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/cb72826e8eb03a115b68ac07b76e18f8.png](%E7%94%A8%20OmniFocus%203%20%E5%AE%8C%E6%88%90%E4%BA%86%E4%B8%8A%E5%8D%83%E4%B8%AA%E4%BB%BB%E5%8A%A1%E5%90%8E%EF%BC%8C%E6%88%91%E6%80%BB%E7%BB%93%E5%87%BA%E4%BA%86%E8%BF%99%E4%BA%9B%E7%BB%8F%E9%AA%8C%204ee8cc7841024ed9b37fe7b712ac253b/cb72826e8eb03a115b68ac07b76e18f8.png)

另一方面，OmniFocus 3 提供了自带的 Review 透视，建立每个项目的时候可以选择多少天 Review 一次。实践上，一般工作上需要每天跟进的项目，会把 Review 的时间设置为每天一次，一般的项目设置为一周 Review 一次即可。为了防止忘记 Review，可以把这个 Review 的任务添加到 Morning Review 或者 Weekly Review 中。

## 后记

OmniFocus 2 刚发布时就开始使用了，期间还使用过 org-mode 和 Todoist，OmniFocus 3 发布了之后就立马重新迁移过来。虽然 OmniFocus 3 还存在着一些不足，但是已经能够很好地满足目前的工作流了。主要的使用场景大部分是在 macOS 上，iOS 基本上只是用来查看。

这篇文章中所写的内容都是经过了很长时间实践之后得出的经验，一个好的任务系统是需要不断优化迭代的，如果你觉得自己的系统不怎么好用，不妨想一下哪些地方需要优化，然后慢慢改进它。掌握了任务管理的本质之后，不管是切换到什么工具都能够游刃有余。

注：如果你想**系统学习 OmniFocus 的使用**，Sainho 的基于 OmniFocus 3 的教程[《用 OmniFocus 3 搭建任务管理系统》](https://sspai.com/series/69) 即将开始连载，在这个教程中你将会学到：

- 系统的任务管理理论
- 实用的任务管理经验
- 细致的功能介绍
- 紧跟新功能
- 进阶 OmniFocus 技巧

更多详情，请见[专栏主页](https://sspai.com/series/69)，现在订阅还有优惠哦。