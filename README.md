# 李彦毅 · Li Yanyi

- 通用主页：https://liyanyi1123.github.io/
- PhD / 研究主页：https://liyanyi1123.github.io/research/
- AI 产品 / AI 开发求职主页：https://liyanyi1123.github.io/career/

本仓库存放 Astro 网站的静态发布文件。GitHub Pages 从 main 分支根目录发布。
研究页默认英文、求职页默认中文；语言选择和明暗模式支持切换及记忆。

本次新增两个面向不同读者的页面，原通用主页及其资源保留。
新页面的教育、论文和实习信息集中维护于源码的 `src/data/profile.ts`。
构建命令：`SITE_URL=https://liyanyi1123.github.io pnpm build`。
发布时保留 `.nojekyll`，确保 `_astro` 资源可用。

本站基于 MIT 授权的 [Astro Nano](https://github.com/markhorn-dev/astro-nano)。原始授权见 LICENSE。
