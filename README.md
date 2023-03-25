# AlgoFromScratch
learn algo from scratch


# 本项目子模块添加方法
## 方法一
如果项目已经克隆到了本地，执行下面的步骤：

初始化本地子模块配置文件

Copy
git submodule init
更新项目，抓取子模块内容。

Copy
git submodule update
## 方法二
另外一种更简单的方法，就是在执行 git clone 时加上 --recursive 参数。它会自动初始化并更新每一个子模块。例如：

Copy
git clone --recursive 本项目