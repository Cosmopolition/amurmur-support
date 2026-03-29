# Amumur Support Site

语生 Amumur 隐私政策、用户协议和支持中心页面。

## 项目结构

```
amurmur-support/
├── index.html           # 首页（自动根据浏览器语言重定向）
├── privacy.html         # 隐私政策（自动根据浏览器语言重定向）
├── terms.html           # 用户协议（自动根据浏览器语言重定向）
├── support.html         # 支持中心（自动根据浏览器语言重定向）
├── css/
│   └── style.css        # 共享样式
├── en/                  # 英文版本
│   ├── privacy.html     # Privacy Policy
│   ├── terms.html       # Terms of Service
│   └── support.html     # Support Center
└── zh/                  # 中文版本
    ├── privacy.html     # 隐私政策
    ├── terms.html       # 用户协议
    └── support.html     # 支持中心
```

## 语言支持

- English (en)
- 中文简体 (zh)

## 页面说明

### 支持中心 (Support Center)

包含以下内容：
- **关于语生** - 应用介绍和核心功能
- **使用场景** - 会议记录、学习笔记、灵感记录、就医记录等
- **常见问题** - 隐私与数据、iCloud 同步、订阅与退款、录音质量等
- **联系我们** - 邮箱联系方式

## 部署说明

本项目为静态网站，可直接部署到 GitHub Pages、Netlify、Vercel 等静态托管平台。

### GitHub Pages 部署

1. 将项目推送到 GitHub 仓库
2. 进入仓库 Settings → Pages
3. Source 选择 `main` 分支和 root 目录
4. 点击 Save 等待部署完成

部署后访问：`https://yourusername.github.io/amurmur-support/`

### 自定义域名

如需使用自定义域名，请在仓库中添加 `CNAME` 文件，内容为你的域名（如：`support.amurmur.com`）。

## 页面链接

- `/support.html` - 支持中心
- `/privacy.html` - 隐私政策
- `/terms.html` - 用户协议
- `/` 或 `/index.html` - 首页

## 更新日志

### v1.1 (2026-03-29)
- 新增支持中心页面
- 新增页面导航菜单
- 中英文双语支持

### v1.0 (2026-03-29)
- 初始版本发布
- 支持中英文隐私政策和用户协议
- 本地 AI 处理说明（Qwen3.5-0.8B）
- iCloud 数据说明
- 儿童隐私保护（4周岁以上）

## 联系方式

- 邮箱：peer2peer.wang@gmail.com

## 许可证

本项目仅供 Amumur 官方使用。
