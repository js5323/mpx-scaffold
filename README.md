# mpx-scaffold

> A mpx project

## Dev

```bash
# install dep
npm i

# for dev
npm run watch

# for online
npm run build
```

npm script 规范 [build|watch]:[dev|prod]:[cross|web|none]

build 默认 prod，watch 默认 dev。另单独提供了 build:dev 和 watch:prod，用于单次构建分析看未压缩代码分析问题和持续压缩代码便于大体积项目真机调试。

建议自行调整 cross 的目标。npm-run-all 是为了兼容 windows 下无法同时执行两个 npm script，若不需要转 web 平台，可考虑去掉。

## git commit 规范：

- http://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html
- build : 改变了 build 工具 如 webpack
- ci : 持续集成新增
- chore : 构建过程或辅助工具的变动
- feat : 新功能
- docs : 文档改变
- fix : 修复 bug
- perf : 性能优化
- refactor : 某个已有功能重构
- revert : 撤销上一次的 commit
- style : 代码格式改变
- test : 增加测试
- anno: 增加注释

## VsCode 插件加持

- mpx
