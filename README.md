# 彭雨璇 · 个人研究档案网站

线上地址：https://yuxuanpeng6340-debug.github.io/

## 文件
- `index.html`：网站全部内容（单页）
- `assets/style.css`：样式；`assets/portrait.jpg` 照片；`assets/og.png` 分享卡片；`assets/favicon.svg` 图标
- `cv.html` → `cv.pdf`：可下载的公开版简历（只含邮箱，不含手机号）

## 更新方法
1. 改简历：编辑 `cv.html`，用 Edge 无界面打印成 `cv.pdf`（或浏览器打开 cv.html → 打印 → 另存为 PDF，覆盖 cv.pdf）。
2. 加作品卡片：在 `index.html` 的 `<div class="cards">` 里复制一个 `<article class="card">…</article>` 改文字；有公开链接才加 `<a class="link">`。
3. 提交：`git add -A && git commit -m "更新" && git push`，约 1 分钟后生效。

保密原则：私募与财务顾问项目只写行业层面的研究问题与方法，不写被投企业、客户名称、财务数据与结论。
