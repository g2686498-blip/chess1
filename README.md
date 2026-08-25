# 开局弱点分析 + 鳕鱼引擎 + AI（平铺版）

所有文件在同一层，方便手机上传 GitHub，无需文件夹。

## 文件列表

- `index.html` — 页面
- `main.css` — 样式
- `chess.js` — 棋盘库
- `app.js` — 业务逻辑
- `apk-data.js` — 内嵌 APK（可选）
- `README.md`

## 上传到 GitHub

把上面这些文件全部传到仓库**根目录**（同一层），然后：

Settings → Pages → Deploy from a branch → main → / (root) → Save

访问：`https://你的用户名.github.io/仓库名/`

## 本地预览

```bash
python3 -m http.server 8080
```

打开 http://localhost:8080
