# GAMES101-S2021-Skeleton

GAMES101 代码框架

包含作业1-8 及 Final Project

你可以 Fork 一份开始作业, 不过由于 Github 的限制, 目前 Fork 的仓库只能为 Public 状态.

若你需要创建 Private 仓库可以按照以下步骤:

1. 在 github 中创建一个新的空白私有仓库 [新建](https://github.com/new)
2. 克隆本仓库 
```bash
git clone git@github.com:Jinof/GAMES101-S2021-Skeleton.git
```
3. 删除原 origin
```bash
git remote remove origin
```
4. 新增 origin 为私有仓库地址 
```bash
git remote add origin git@github.com:<Username>/GAMES101-S2021-Skeleton-Private.git
```
5. 上传代码
```bash
git push --set-upstream origin master
```