<<<<<<< HEAD
# canvasRelated
跟canvas画布相关的一些功能操作，fabric.js等库的使用
=======

## 第一步：注册GitHub账号
如果你还没有GitHub账号，需要先注册一个。访问 GitHub官网 并按照指示完成注册流程。

## 第二步：安装Git客户端
确保你的电脑上已经安装了Git。如果未安装，可以从 Git官方网站 下载并安装Git客户端。

## 第三步：创建GitHub仓库
登录你的GitHub账号。
在GitHub主页或用户页面点击“New”或“+ New repository”按钮。
输入仓库名称、描述、选择公开或私有仓库，并可选择是否初始化仓库文件（如README.md）。
点击“Create repository”。

## 第四步：在本地项目中初始化Git仓库
打开你的项目文件夹。
在项目根目录下打开终端或命令行窗口。
输入 `git init` 初始化一个新的Git仓库。

## 第五步：添加文件到Git仓库
使用 `git add .` 命令将所有文件添加到暂存区。
如果只想添加特定文件，可以用 `git add <filename>`。
使用 `git commit -m "Initial commit"` 提交文件到本地仓库。

## 第六步：关联GitHub仓库
获取GitHub仓库的URL，通常在创建仓库时会有提示。
在本地仓库中使用以下命令关联远程仓库：

    `git remote add origin <repository-url>`
   
## 第七步：推送代码到GitHub
使用以下命令将本地的master/main分支推送到GitHub：

    `git push -u origin master`
   
或者如果是新创建的仓库可能默认分支名为main：

    `git push -u origin main`
   
## 第八步：确认上传
登录GitHub，你应该可以在你的仓库中看到已上传的代码。

以上步骤适用于使用命令行操作的情况。如果你使用的是IDE（如IntelliJ IDEA）或其他图形界面工具，这些工具通常会提供集成的Git功能，你可以直接在IDE内完成大部分操作，具体步骤可能会有所不同，但基本原理是一致的。
>>>>>>> master
