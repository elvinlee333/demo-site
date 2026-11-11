# demo-site

单文件静态演示页，用于验证 GitHub 仓库创建与文件推送链路。

## 内容

| 文件 | 说明 |
|---|---|
| `index.html` | 页面本体，样式内联，无外部依赖 |
| `README.md` | 本文件 |

## 本地预览

直接用浏览器打开 `index.html`，或起一个本地服务：

```bash
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## 发布到 GitHub Pages

1. 仓库 Settings → Pages
2. Source 选 `Deploy from a branch`
3. Branch 选 `main`，目录选 `/ (root)`
4. 保存，等待约 1 分钟，访问 `https://elvinlee333.github.io/demo-site/`
