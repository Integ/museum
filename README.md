# Geek Museum · 极客博物馆

一个极简的静态展示网站，用于展示个人收藏：Olympus M-1 胶片相机、Apple II 电脑、Mac Pro（"垃圾桶"）。

结构：

- `index.html` — 主页面
- `css/styles.css` — 样式文件（系统字体、苹果风格简约设计）
- `assets/*.svg` — 占位矢量图，建议替换为照片

快速预览（macOS）：

直接在 Finder 双击 `index.html` 打开，或在终端中运行：

```bash
# 在项目目录运行下面任意一条：
open index.html
# 或者启动一个简单的 HTTP 服务：
python3 -m http.server 8000
# 然后在浏览器打开 http://localhost:8000
```

可选改进：

- 使用真实照片替换 `assets/*.svg`。
- 添加按类别过滤或搜索功能。
- 使用静态站点生成器或 Netlify/Cloudflare Pages 部署。

设计说明：采用苹果风格属性：系统字体栈、充裕留白、柔和阴影与圆角、简洁配色。