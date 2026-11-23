# mlstudy

机器学习学习平台：记录机器学习模型学习方法论，用 [Quartz](https://quartz.jzhao.xyz/) 把 `content/` 下的笔记发布成网站。

笔记内容本身见 [content/README.md](content/README.md)。

## 本地开发

```bash
npm install
npx quartz build --serve
```

## 部署

推送到 `v5` 分支后，GitHub Actions 会自动构建并发布到 GitHub Pages。
