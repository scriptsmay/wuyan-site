# Wuyan Site - 无言粉丝应援站

无言粉丝应援站静态页面仓库，由 Vercel 部署。

## 预览

[https://kplwuyan.site](https://kplwuyan.site)

![站点预览](snapshot.png)

## 项目结构

```
wuyan-site/
├── homepage/          # 粉丝应援站（静态页面）
│   ├── index.html     # 主页面
│   ├── config.js      # 环境配置（需手动创建）
│   ├── config.example.js # 配置模板
│   ├── favicon.svg    # 网站图标
│   └── assets/        # 静态资源
├── README.md
└── .gitignore
```

## 快速开始

```bash
cd homepage
npm install
npm run dev
```

## 构建

```bash
cd homepage
npm run build
```

## 部署

通过 Vercel 自动部署，关联 GitHub 仓库：scriptsmay/wuyan-site

## 文档

- [homepage/README.md](homepage/README.md) - 构建说明

---

**项目维护者**: scriptsmay
