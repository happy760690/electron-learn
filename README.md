## 使用 Electron + React Hooks + 七牛云 完成一个云同步 Markdown 笔记本

本 repo 为主项目源代码

### 使用代码前必看！！

本项目使用两个分支管理整个项目

**master分支**

master 分支是和课程教学完全同步的一个分支，现在更新到了 11-10 小节，为了方便同学看代码并且和课程做比较，采用了每节课一次 commit 这种方式，你可以轻松的找到每节课老师添加和删除的代码。最新的小节是最上面的提交，以此类推。大家可以注意看 commit 的描述，非常详细的描述了每次的修改。如下图所示：

![project commits](./screenshots/commits.png)



**develop分支**

develop 分支是开发分支，开发分支现在已经将整个项目开发完毕，如果想体验最终结果的同学，可以使用这个分支。

### 环境参数

Node 版本  > 10.0.0
Npm 版本 > 6.0.0

### 常用命令

第一次 clone 完毕该 repo，需要**安装依赖**

```bash
npm install
```

本地启动**开发环境**

```bash
npm run dev
```

打包为**应用程序**(目前仅限在 develop 分支中使用)

```bash
npm run dist
```# electron-learn
