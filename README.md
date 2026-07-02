# 全球每日资讯简报

一个简洁优雅的全球每日资讯简报静态网站，涵盖科技、金融、AI、医疗、新能源、消费、房地产、制造业、教育、文化娱乐十大行业。

## 功能特点

- 🎨 **精美设计**：采用青色与金色配色方案，现代简约风格
- 📱 **响应式布局**：完美适配桌面端与移动端
- 📊 **结构化呈现**：十大行业分类，清晰易读
- ⚡ **纯静态部署**：无需后端，部署简单快速

## 技术栈

- HTML5
- CSS3
- JavaScript（原生）

## 项目结构

```
.
├── index.html          # 首页
├── daily/              # 每日简报归档
│   └── 2026-07-02.html # 示例简报
└── README.md
```

## 本地运行

直接在浏览器中打开 `index.html` 即可查看。

## 一键部署到 Cloudflare Pages

[![Deploy to Cloudflare Pages](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/your-username/global-daily-briefing)

### 部署步骤

1. 点击上方按钮登录 Cloudflare 账户
2. 选择 GitHub 仓库或直接部署
3. 配置构建设置：
   - **Build command**: `none`
   - **Build output directory**: `./`
4. 点击部署即可

## 自定义内容

编辑 `index.html` 中的 `archives` 数组来添加历史资讯链接：

```javascript
const archives = [
  {
    date: '2026-07-02',
    title: '资讯标题',
    url: 'daily/2026-07-02.html'
  }
];
```

在 `daily/` 目录下创建新的日期文件来发布每日简报。
