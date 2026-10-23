# 张霖的个人学术主页

基于 [HugoBlox Academic CV](https://github.com/HugoBlox/theme-academic-cv)（原 Hugo Academic）构建，并通过 GitHub Actions 自动发布到 GitHub Pages。

## 本地预览

需要 Hugo Extended 0.162.0、Node.js 22 和 pnpm。

```bash
pnpm install
pnpm dev
```

访问 `http://localhost:1313/`。

## 发布到 GitHub Pages

目标仓库为 [`ZZZLLin/ZZZLLin.github.io`](https://github.com/ZZZLLin/ZZZLLin.github.io)，发布地址为 `https://zzzllin.github.io/`。

1. 将本目录推送到仓库的 `main` 分支：

   ```bash
   git remote add origin https://github.com/ZZZLLin/ZZZLLin.github.io.git
   git push -u origin main
   ```

2. 打开仓库的 **Settings → Pages**，将 **Source** 设为 **GitHub Actions**。
3. 打开 **Actions** 页面，等待 `Deploy website to GitHub Pages` 完成。工作流会自动使用 GitHub Pages 提供的正确基础网址。

## 修改内容

- 个人资料、教育、经历、技能与荣誉：`data/authors/me.yaml`
- 首页区块：`content/_index.md`
- 项目：`content/projects/`
- 导航：`config/_default/menus.yaml`
- 站点外观与 SEO：`config/_default/params.yaml`
- 头像：`assets/media/authors/me.png`

出于隐私考虑，网站没有附带含手机号的原始 PDF 简历。如需提供公开版简历，建议先移除手机号与不希望公开的信息，再放入 `static/uploads/resume.pdf` 并在首页添加下载按钮。
