# AU521F 型锭子清洗加油机销售网站

纯静态销售网站，通过 GitHub Pages 部署。

## 目录结构

- `index.html` — 首页（产品概览、参数、文章卡片）
- `product.html` — 产品详情（用途、图片、技术参数、结构、使用方法）
- `application.html` — 应用领域（适用设备、锭子型号与枪管匹配）
- `contact.html` — 联系方式（邮箱 548827878@qq.com）
- `articles/` — SEO 文章（6 篇，含 Article JSON-LD 结构化数据）
- `images/` — 产品照片
- `css/style.css` — 样式
- `sitemap.xml` / `robots.txt` — SEO 文件
- `drafts/gen_articles.py` — 文章生成脚本（新增文章时运行）

## 新增 SEO 文章

编辑 `drafts/gen_articles.py` 中的 ARTICLES 列表，运行脚本即可生成新文章；随后把新文章 URL 加入 `sitemap.xml`、首页与 `articles/index.html` 的卡片。

## 部署

推送 main 分支后，GitHub Pages 自动发布到 `https://mfujun2025.github.io/dingzi/`。
