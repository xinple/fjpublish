2022-10-10 v2.0.3
- 升级ssh2shell到v2.0.3版本，并修复报错；
- 支持 Ed25519 的 SSH Keys；
- scp2因作者停止更新，去除依赖；
- 修复无法push history的bug；

使用方法：

```
# 切换到该程序目录然后：
npm install
npm link
```

PS：没有上传到 npm，所以本地 npm link 用吧。

查看原作者文档：`npm run docs`
