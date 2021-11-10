# Git笔记

## Clone

```git
git clone https://github.com/theMeiLin/Gitnotes Git
```

https://github.com/theMeiLin/Gitnotes：克隆仓库的url  Git：指定仓库的文件名 可以自己随机起名

| `git add`    | 添加文件到仓库                           |
| ------------ | ---------------------------------------- |
| `git status` | 查看仓库当前的状态，显示有变更的文件。   |
| `git diff`   | 比较文件的不同，即暂存区和工作区的差异。 |
| `git commit` | 提交暂存区到本地仓库。                   |
| `git reset`  | 回退版本。                               |
| `git rm`     | 删除工作区文件。                         |
| `git mv`     | 移动或重命名工作区文件。                 |

```
git commit -m '第一次版本提交'
```

push

git add *

git status

git commit -m "new gitnotes pushed!"

git push origin main

