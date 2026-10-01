# 步天 (Butian) 官网、技术支持与隐私政策

本项目是「步天」App（`com.funvalvar.xuan`）的 GitHub Pages 静态文档站点。

- **官方网站 / 技术支持：** [https://butian.funvalvar.com](https://butian.funvalvar.com)
- **隐私政策 (Privacy Policy)：** [https://butian.funvalvar.com/privacy.html](https://butian.funvalvar.com/privacy.html)
- **标准使用条款 (EULA)：** [Apple Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
- **联系邮箱：** funvalvar@proton.me

## 目录结构

```text
.
├── .gitignore         # Git 忽略配置
├── .nojekyll          # 禁用 Jekyll 编译（防止文件被过滤）
├── CNAME              # 自定义域名配置 (butian.funvalvar.com)
├── favicon.png        # 网站图标
├── icon.png           # App 高清墨盘图标
├── index.html         # 官网首页与技术支持 (Support) 页面
├── privacy.html       # 符合 Apple 5.1.1 规范的中英双语隐私政策页面
└── README.md          # 本说明文档
```

## GitHub Pages 与 DNS 配置

1. **GitHub 仓库设置：**
   - 进入 GitHub 仓库 `Settings` -> `Pages`
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `root`
   - **Custom domain:** `butian.funvalvar.com`
   - 勾选 **Enforce HTTPS**

2. **DNS 解析配置：**
   在您的域名解析服务商（如 Cloudflare、DNSPod 等）添加 CNAME 记录：
   - **主机记录：** `butian`
   - **记录类型：** `CNAME`
   - **记录值：** `kebasiji.github.io`
