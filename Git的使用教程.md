<h1>Git的使用教程：</h1>

​			<sub>如何便捷的使用git</sub>

<h4>Repository（仓库）:</h4>类似一个项目的文件夹，多个项目即有多个仓库

<h4>Star（收藏）：</h4>方便下次查看

<h4>Fork（复制克隆项目）：</h4><p>简单理解就是，你看到别人的项目很好，你可以fork他的项目，这是你的主页上就多了一个项目

<h4>pull request（发起请求）：</h4>基于fork的，别人fork你的项目做了修改，想把他的修改合并到你的项目里，会发起pull request 的请求。

<h4>watch（关注）：</h4>如果你 watch 了一个项目 ，那么项目更新后，你会收到提醒

<h4>issue（事务卡片）：</h4>发现代码bug，但是没有成型代码，相当与建议

<h4>仓库主页：</h4>仓库主页显示项目的信息

<h4>个人主页：</h4>头像，个人简介，我关注的，关注我的，我关注的git库，我的开源项目，我贡献的开源项目信息

<h4>私有仓库：</h4>私有仓库只能自己或指定的朋友才有权限（私有仓库时收费的），在创建仓库的时候，在底部会有一个选项，是否创建一个README文件，这其实时一个说明文件，为markdown格式



<h4>仓库管理：</h4>创建文件，创建文件后，会自动跳转到仓库主页 修改删除文件：点击文件名，到文件详情也可以修改，也可以删除

<img src="E:\笔记\Typora\git教程图片\1.jpg">

​					<img src="E:\笔记\Typora\git教程图片\2.jpg">

<img src="E:\笔记\Typora\git教程图片\3.jpg">



<img src="E:\笔记\Typora\git教程图片\4.jpg">										

<h4>搜索文件:</h4>可以点击 go to file，也可以使用快捷键T

<h4>Issue:</h4>点击 close issue，可以关闭issue，相当于已解决

<img src="E:\笔记\Typora\git教程图片\5.jpg">

<h4>Fork:</h4>

<img src="E:\笔记\Typora\git教程图片\6.jpg">

<h4>Pull Request:</h4>

<img src="E:\笔记\Typora\git教程图片\7.jpg">



<img src="E:\笔记\Typora\git教程图片\8.jpg">



<h2>开源项目贡献流程:</h2>

1.新建issue，提交使用问题或者建议或者想法 

2.Pull Request 发起请求



<h1>Git安装和使用</h1>

目的：通过git管理GitHub托管项目代码



<h3>Git 的基本工作流程 </h3>

<h4>桌面的两个软件</h4>

Git Gui 是图形界面

Git Bash 是命令行界面

<h4>Git 工作区域 (working Directory):</h4>添加，编辑，修改文件等动作

<h4>暂存区（stage）:</h4>暂存已经修改的文件，最后统一提交到 git 仓库中

<h4>常见的Git指令：</h4>

git status: 查看状态

git add:将工作区的文件提交到暂存区

git commit -m  “提交描述”：将代码提交到 git 仓库

<h4>Git 初始化及仓库的创建和操作:</h4>

1. 设置用户名：git config-global user.name  '名字（要输正确） '
2. 设置用户名邮箱：git config-global user.name  '邮箱'
3. 查看设置： git config --list





