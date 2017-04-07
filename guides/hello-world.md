## 简介

**Hello World** 在编程界是一个由来已久的项目。通过这个项目可以让你在学习新知识的时候快速入门。下面我们就开始这个Github的Hello World项目。

**在这个项目中你将学会：**

* 创建并使用仓库
* 创建或合并分支
* 修改文件并提交到Github
* 创建或合并Pull Request


## Github是什么

Github是一个集版本管理和团队协作于一身的代码托管平台。通过它可以让你和来自世界各地的人一起开发项目。

本教程会告诉你Github中一些比较关键的要素，如： _仓库_ 、 _分支_ 、 _提交_ 以及 _Pull Request_ 等。通过这个Hello World项目你将会创建自己的仓库，了解Github的Pull Request的工作流程—— 一个比较流行的创建和评审代码的方式。


### 不需要编写任何程序代码

学习本教程有两个要求：

1. 你已经有了Github的[账户](http://github.com/)
2. 你能访问Internet网络

本教程不需要你了解任何的编程语言，也不需要使用命令行，更不需要安装Git（Github所依赖的版本管理软件）。

> ** 小提示 **: 在一个单独的浏览器窗口或是页签中打开这个教程，这样就可以在完成教程中的步骤时参考这个教程了。


## 第一步 创建仓库

一个 **仓库** 通常用来管理一个单独的项目。仓库中可以包含目录和文件，图片、视频、电子表格和资料等等 —— 你项目中需要的任何文件都可以放到仓库中。推荐在仓库中放一个 _README_ 或是其他描述你项目信息的文件。Github可以在创建新仓库的时候顺便添加项目的说明，并且它还提供了其它的一些常见文件，如license文件。

你的 `hello-world` 项目可能是一个用来保存你的想法或是资源的地方，甚至可以在那里与他人进行共享或是讨论。

### 创建新仓库

1. 在右上角你头像或ID的旁边有一个<span class="octicon octicon-plus"></span>号，点击它然后选择 **New repository**
2. 给你的仓库起个名，这里我们使用 `hello-world`
3. 写下关于这个仓库的说明
4. 选中 **Initialize this repository with a README**

![创建新仓库](https://guides.github.com/activities/hello-world/create-new-repo.png)

最后点击 **Create repository** :tada:


## 第二步 创建分支

**分支** 允许你同时管理仓库的不同版本。

默认情况下你的仓库中有一个名为 `master` 的分支，这个分支通常被当作是稳定分支。我们通常会在其他的分支中时行实验或是进行更改，在确保没有问题的时候才会提交到`master`分支。

当你基于`master`分支创建新分支的时候，实际上是对`master`进行了一次快照，把`master`分支当时的状态另存了一份，这也可以理解为“复制”。如果你在其他的分支工作的时候，有人修改了`master`分支的话，你可以通过pull来获取那些更改。

下图展示了：

* `master` 分支
* 一个名为`feature`的新分支（因为我们正在这个分支上开发新功能）
* 把`feature`分支合并到`master`之前做的尝试

![feature分支](https://guides.github.com/activities/hello-world/branching.png)

你有没有把同一个文件保存成不同版本的经历？就像这样：

* 故事.txt
* 故事_张三编辑后.txt
* 故事_张三编辑后_已审核.txt

Github仓库中的分支实现了类似的功能。

在Github里，我们开发人员、作家或是设计师用分支来将Bug修复、新功能开发与 `master` （生产环境）隔离开。当变更可以合并到`master`的时候再进行合并。


### 创建新分支

1. 打开你的`hello-world`仓库
2. 打开文件列表上面的写着 **branch:master** 的下拉菜单
3. 在新分支的文本框中输入分支名称，如`readme-edits`
4. 点击下面的 **Create branch** 或者敲一下回车

![创建分支](https://guides.github.com/activities/hello-world/readme-edits.gif)

现在你的仓库里已经有两个分支了，`master`和`readme-edits`。他们看起来是一模一样的，但是很快就不同了，因为我们会在新分支中进行修改。


## 第三步 编辑并提交

漂亮！你现在是在`readme-edits`分支，是从`master`分支复制过来的。现在我们来进行一些修改。

在Github里，保存的修改被称为 _提交_ 。每一个提交都有一个与之相关的 _提交信息_ ，里面描述了为什么要进行这些修改。提交信息能反应你的变更历史，这样其他的贡献者就能了解你做了什么以及为什么要那么做。

### 进行编辑并提交

1. 点击 `README.md` 文件
2. 点击右上角的<span class="octicon octicon-pencil"></span>图标开始编辑
3. 在编辑器中填入一些内容
4. 在Commit Change里输入你改了什么
5. 点击 **Commit changes** 按钮

![提交](https://guides.github.com/activities/hello-world/commit.png)

这些修改仅会对`readme-edits`分支里的README文件生效，此时这个分支与`master`分支里的内容就不同了。


## 第四步 创建Pull Request

改的好！现在你在从基于`master`分支创建的新分支中有了变更，可以创建 _pull request_ 了。

Pull Request是Github中协作的核心。当你创建 _pull request_ 的时候，你是在把自己的修改建议给原作者，经大家来评审后，由原作者把这些变更合并到他的分支。Pull Request会显示两个分支的差异。变化的内容会以不同的颜色显示，新添加的显示成绿色，删除的显示成红色。

在提交之后，你随即就可以创建Pull Request进行讨论，而不用必须等到编码完成。

你可以在你的Pull Request中用[@系统](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar)来邀请特定的人或是团队来给你反馈，不管他们是就在大厅还是与你隔了10个时区的远方。

你甚至可以在自己的仓库里创建Pull Request然后自己合并。在参与大的项目前了解Github的工作流程是一种非常不错的选择。

### 创建修改README的Pull Request

_点击图片查看大图_

| 步骤 | 截图 |
|------|------|
| 点击 **<span class="octicon octicon-git-pull-request"></span>Pull Request** 页签，然后在Pull Request页面里点击 **New pull request** 按钮| ![点击New pull request按钮](https://guides.github.com/activities/hello-world/pr-tab.gif) |
| 选择你修改的分支 `readme-edits`，与`master`分支进行比较 | ![比较分支变化](https://guides.github.com/activities/hello-world/pick-branch.png) |
| 查看比较结果，确定这些差异是你想提交的内容 | ![查看比较结果](https://guides.github.com/activities/hello-world/diff.png) |
| 如果你确定这就是你想提交的变更，点击那个超大的绿色 **Create Pull Request** 按钮 | ![点击按钮](https://guides.github.com/activities/hello-world/create-pr.png) |
| 给你的Pull Request起个名，再写一些关于变更的概要描述 | ![标题和描述](https://guides.github.com/activities/hello-world/pr-form.png) |


完成以上的步骤后，点击 **Create pull request** 按钮！

> 可以在Pull Request或评论中使用[emoji表情符号](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji)，还可以通过[拖拽的方式上传图片](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/)。


## 第五步 合并Pull Request

到最后一步了，是时候把你的修改合并到一起了——把`readme-edits`分支合并到`master`分支中。

1. 点击那个绿色的 ** Merge pull request ** 按钮，把修改合并到`master`
2. 点击 **Confirm merge**
3. 使用 **Delete branch** 按钮删除那个分支吧，因为它里的修改已经包含在master里了

![合并Pull Request](https://guides.github.com/activities/hello-world/merge-button.png)

### 庆祝

通过这个教程，相信你已经学会了如何在Github中创建项目以及如何处理pull request。 :tada: :octocat: :zap:

下面是你在教程中完成的内容：

* 创建了一个开源仓库
* 创建并合并了新分支
* 修改了文件，并将修改提交到了Github
* 创建并合并了一个Pull Request

你可以在个人信息中看到你的[贡献广场](https://help.github.com/articles/viewing-contributions)!

要学习更多关于Pull Request的知识的话，推荐你看一下[Github流程指南](http://guides.github.com/overviews/flow/)。你也可以访问[Github浏览器](http://github.com/explore)参与某个开源项目。 :octocat:

> **小技巧**: 浏览我们的[指南](http://guides.github.com/)、[Youtube频道](http://youtube.com/githubguides)以及[技能培训](https://services.github.com/on-demand/)获得更多关于Github的知识。
