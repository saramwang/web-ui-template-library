# Web UI Template Library · 网页模板库

一套可直接预览、挑选、套用的设计模板库。两个部分:**50 套响应式网页 UI 模板** + **34 套配色/版式设计风格**。全部纯 HTML/CSS、单文件、零外部图片(图表与插画均为内联 SVG),开箱即用。

🔗 **在线预览 / Live demo:** https://web-ui-template-library.vercel.app/

---

## 内容 / What's inside

### 网页 UI 模板库 · 50 套(`/ui/`)

| 分类 | 数量 | 示例 |
|------|------|------|
| 落地页 Landing | 20 | 极光玻璃 SaaS、暗黑 AI、新野兽派、渐变金融、有机护肤、赛博朋克游戏、Y2K 潮牌、奢侈腕表… |
| 仪表盘 Dashboard | 10 | 数据分析、暗色金融、CRM、医疗监护、DevOps、社媒分析、项目管理… |
| 作品集 / 博客 Portfolio & Blog | 10 | 摄影师、开发者、插画师、杂志编辑、Newsletter、简历 CV… |
| 电商 E-commerce | 10 | 轻奢时装、美妆、家居、珠宝、球鞋、生鲜、购物车结算、数码商城… |

### 配色 · 演示模板库 · 34 套(`/slides.html`)

来自 `frontend-slides` 设计风格包,每套含配色、字体、版式与适用场景,适合 PPT / 海报 / 封面。

---

## 怎么用 / How to use

1. 打开首页,进入「网页 UI 模板库」或「配色模板库」
2. 缩略图是模板的**真实渲染**(实时预览);点「打开预览」可全屏查看与交互
3. 点「选用」复制一段提示词,粘贴给 Claude(或 Claude Code),补上你的内容,即可把模板套用成你的页面 —— **保留你的内容,只换设计**

---

## 技术 / Tech

- 纯 HTML + CSS,少量原生 JS(移动端菜单等),**无框架、无构建步骤**
- 每个模板都是**单一自包含文件**,可单独下载使用
- 全部图像由 CSS 渐变 + 内联 SVG 生成,不依赖任何外部图片
- 响应式,移动端断点,符合 WCAG AA 对比度

## 目录结构 / Structure

```
.
├── index.html          # 首页 Hub
├── slides.html         # 配色模板库(34 套)
└── ui/
    ├── index.html      # 网页 UI 模板画廊(50 套)
    └── templates/      # 50 个模板文件
```

## 部署 / Deploy

静态站点,已部署于 Vercel。向本仓库 push 更新后会自动重新部署。

---

*由 Sara 构建 · Built with Claude*
