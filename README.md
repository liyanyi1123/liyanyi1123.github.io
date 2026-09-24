# 李彦毅 · Li Yanyi

个人主页：https://liyanyi1123.github.io/

此仓库存放 liyanyi-portfolio 的静态构建产物，使用 GitHub Pages 从 main 分支根目录发布。
页面支持中英文切换与浅色、深色主题。

## 更新网站

在 liyanyi-portfolio 源码项目中修改内容，并运行：

```sh
pnpm install --frozen-lockfile
SITE_URL=https://liyanyi1123.github.io pnpm build
```

将 dist 中的全部文件发布到此仓库根目录，并保留 `.nojekyll`，使 `_astro` 资源正常提供服务。
旧版本保留在 Git 提交历史中。

## 授权

本站由 MIT 授权的 [Astro Nano](https://github.com/markhorn-dev/astro-nano) 改造而来。
原始授权文本见 LICENSE。
