# Clais Blog (GitHub Pages - 方案A)

静态博客页面（`index.html + styles.css`），可直接部署到 GitHub Pages。

## 本地预览

```bash
cd /home/niko/.openclaw/workspace/clais-blog
python3 -m http.server 8090
```

打开：`http://127.0.0.1:8090`

## 发布到 GitHub Pages

1. 创建仓库：`<your-username>.github.io`
2. 将本目录文件推送到该仓库 `main` 分支
3. 等待 1~3 分钟生效
4. 访问：`https://<your-username>.github.io`
