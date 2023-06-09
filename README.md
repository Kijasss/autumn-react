# autumn-react

<div align="center">
  <img src="https://img.shields.io/badge/-React-00b4ce?style=flat&logo=react&logoColor=white">
  <img src="https://img.shields.io/badge/-TypeScript-2b6dbf?style=flat&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/-Node.js-3C873A?style=flat&logo=Node.js&logoColor=white">
  <img src="https://img.shields.io/badge/-ESLint-%234B32C3?style=flat-square&logo=eslint">
  <img src="https://img.shields.io/badge/-Rollup-ee462c?style=flat&logo=rollup&logoColor=white">
</div>
<p></p>
定义项目结构（monorepo）
定义开发规范（lint、commit、tsc、代码风格）
选择打包工具 rollup

Multi-repo 每个库有自己独立的仓库，逻辑清晰，相对应的，协同管理会更繁琐。
Mono-repo 可以很方便的协同管理不同独立的库的生命周期，相对应的，会有更高的操作复杂度。

<p style="padding-top: 8px; padding-bottom: 8px; line-height: 26px; margin-top: 10px; margin-bottom: 10px; word-spacing: 2px;"><a href="https://juejin.cn/post/6944877410827370504" style="color: rgb(145, 109, 213); font-weight: bolder; border-bottom: 1px solid rgb(145, 109, 213);">参考资料：现代前端工程为什么越来越离不开 Monorepo? </a></p>

使用 husky，用于拦截 commit 命令，通过 commitlint 对 git 提交信息进行检查，集成到 husky 中

常用的 type 值包括如下:

feat: 添加新功能
fix: 修复 Bug
chore: 一些不影响功能的更改
docs: 专指文档的修改
perf: 性能方面的优化
refactor: 代码重构
test: 添加一些测试代码等等
