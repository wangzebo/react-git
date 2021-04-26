# 项目说明

> 这是一个新的项目

## 学习git常用命令

*****

- 连接仓库
  - 创建一个新的仓库
      `git init`
  - 将现有的目录添加到仓库
      `git remote add origin git@github.com:wangzebo/git-demo.git`
- 将文件添加到跟踪清单，`git add`，尽量把相关的改动打成同一个`commit`。
- 将文件添加到跟踪排除清单

>> - 将不想跟踪的文件(文件夹)，添加到根目录下`.gitignore`中让`git`不跟踪文件

- 将本地修改的文件保存到本地仓库
       `git stash / git stash pop`
- 将本地仓库推送到远程仓库, 常规推送、强制推送
       `git push/git push --force`
- 从远程仓库拉取代码
       `git pull/git pull --rebase`
- 创建新分支
       `git branch --create develop`
- 切换分支
       `git checkout master`
- 合并分支
       将develop合并到当前分支：`git merge develop` 将master合并到当前分支：`git merge master`
- 关于标签的操作

``` javascript
      - git tag NAME
      - git log --pretty=oneline --abbrev-commit
      - git tag v0.5.0 666a1a9
      - git show v0.5.0
```

``` javascript
const name = ''
const fun = ()=> {

}
```

``` java
String name = ''
Inter age = 1
```

``` less
$w = 10
.block{
   width: $w;    
}
```

## 学习markdown语法

 *****

- 标题

    1. 一级标题 # 六级标题 ######
    2. **这是加粗的文字**
    3. *这是倾斜的文字*`
    4. ***这是斜体加粗的文字***
    5. ~~这是加删除线的文字~~
    6. [百度](http://baidu.com)

- 列表
- 代码块
- **引用**
- ...

## 无序列表

- aaaa
- bbb
- ccc

## 有序列表

1. dsdfsdf
2. sdfsdsf
3. zdfsdfsdf

## [Markdown基本语法](https://www.jianshu.com/p/191d1e21f7ed)