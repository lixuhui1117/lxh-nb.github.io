## 今天学习了MarkDown
MarkDown是一种超文本语言，今天我第一次学习了它.
'Hello MarkDown!'
接下来我还会学习：
1. Git的基础命令
1. Hexo框架
1. Hexo更换主题
用命令行敲命令是一种**Geek**行为，我觉得还挺有趣的。
Geek是指极客，通常被用于形容对计算机和网络技术有狂热兴趣并通入大量时间钻研的人。所以俗称发烧友或怪杰。
有点意思，下面这张gif可以形容我的心情：
![](https://qgt-style.oss-cn-hangzhou.aliyuncs.com/newcoursep4/g1/g1-2-2/tenor.gif)
##git push 新学的内容

Git 提交的三部曲

1，git add

git add -A   （A是all 的意思）

2，git commit

git commit -m "本次提交的修改的备注"

新创建的文件必须要按照顺序进行提交，如果只是修改文件，并没有创建文件，也可以使用

git commit -am "本次提交的修改的备注" 来合并前两个步骤

3，git push

git push 分为以下几种情形

• 第一次提交到本分支

• 第2-n次提交到本分支

• 提交到其他分支

第一次提交到本分支时，命令比较长

git push origin master              master是远程仓库的默认名称，master是我们的分支名称（主分支）

第2-n次提交到本分支

从第2次开始提交到本分支时，提交的命令可以简化为

git push

提交到其他分支

若果我们需要提交到b分支，那么我们可以输入这个命令

git push origin b

抓取远程仓库的内容

git pull