用了一段时间 Github 之后，你可能就该开始想参与其他人的项目了。或者你想以其他人的项目为基础开始自己的项目。这个过程就叫做 _Forking_ 。

创建“Forking”就是对他人项目的复制。“Forking”将源项目与你自己的副本关联起来。你可以通过提交包含你的修改内容的 _Pull Request_ 到源项目来帮且他人改进他们的项目。“Forking”是 Github 社会环境的核心。

在这个教程中，我们将用 [刀叉项目](https://github.com/octocat/Spoon-Knife) —— 一个托管在 Github 上的测试仓库，来测试 Pull Request 工作流以及 Github 桌面程序。移步到 https://desktop.github.com/ 下载桌面程序。

## Fork 仓库

点击仓库头部的 **Fork** 按钮来创建刀叉仓库的副本。

坐下来观察 forking 魔术的表演吧。当它完成后，会跳转到你的副本仓库。


## 克隆你的 fork 仓库

你已经成功的 fork 了刀叉项目，但是它目录还在Github上。如果想处理这个项目，还需要将它克隆到你本地。

这个过程对于安装了 Github 桌面程序的你来讲真是轻而易举。在 Github 上找到你 fork 的刀叉项目，在右侧边栏偏下的位置找到 **Clone in Desktop**。当我们点击了这个按钮后，它会询问是否想运行桌面程序来克隆仓库，以及仓库保存的位置。选择一个你喜欢的用来存放目录和文件的位置。

![clone your fork](https://guides.github.com/activities/forking/clone-in-desktop.png)


## 修改并提交更改

用你最喜欢的文本编辑器——比如 [Atom](https://atom.io/) 来修改项目中的文件。比如你可以在 _index.html_ 中添加自己的名字。

当编辑完成后，在桌面程序里输入 _提交信息_ ，并点击 **Commit** 按钮。

![commit changes](https://github-images.s3.amazonaws.com/mac/changes/changes.jpg)

此时你本质上是在告诉Git：“好吧，我想给这些变化弄个快照！”。你可以继续进行其它的编辑工作，并提交更多的快照。当你准备好将修改同步到 Github 的时候，点击 **Sync** 按钮，就在你的变更列表的上面。


## 创建 Pull Request

最后，你已经准备好往主项目中建议修改了。这是 fork 他人项目的最后一步，也是最重要（有待讨论）的一步。如果你觉得你的修改对于项目是有益的，就应该考虑贡献他们到源仓库。

要达到这个目的，登录Github并找到你 fork 的项目，对于这个例子来讲，它应该在 `https://www.github.com/<your_username>/Spoon-Knife`。 在上面会出现一个Banner提示你刚刚推送了一个新分支，可以将这个分支提交到它的“上游”，即源仓库。

点击 **Compare and Pull Request** 会跳转到讨论页面，在那里可以输入标题以及可选的描述。应该将你创建这个 Pull Request 的原因写在最前面，并尽可能详细的描述有关变化的信息。项目的所有者会通过这些描述来确定你做的变更是否对其他人有用。

在你认真的输入完这些信息之后，就可以点击 **Send pull request** 按钮了。

Pull Request 是进行讨论的地方。在这个例子中，Octocat 非常忙，可能不会合并你的变更。而对于其他的项目，如果项目负责人拒绝了你的 Pull Request，也不要生气，当然你可以问问作者为什么要拒绝你。甚至有可能项目的作者就是不想合并你的代码，这也是有可能的。但是你的信息坐一直保存在那里，也许某一天有个你素未谋面的人觉得你的变更对他来说比原项目更有价值。多（分）享多善。


## 庆祝

你已经成功的 fork 了一个项目并贡献了代码。继续吧，别停下。
