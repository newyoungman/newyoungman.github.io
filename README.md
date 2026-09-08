# Personal Homepage

Source of https://newyoungman.github.io

## 发布步骤（一次性）

1. 登录 GitHub → New repository → 名称填 `newyoungman.github.io`，Public，Create
2. 在本目录：
   git init
   git add index.html style.css README.md
   git commit -m "init: personal homepage"
   git branch -M main
   git remote add origin https://github.com/newyoungman/newyoungman.github.io.git
   git push -u origin main
3. 等待 1–2 分钟，访问 https://newyoungman.github.io

## 更新内容

改 `index.html` → `git add . && git commit -m "update" && git push`，1 分钟内生效。

## 本地预览

在github-homepage 目录：`python3 -m http.server 8765`，浏览器开 http://localhost:8765

## 待填占位符清单

- [ ] Publications：论文条目（替换 [PAPER TITLE] 等）
- [ ] Experience：既往工作经历条目
- [ ] Education：学校、专业、学位、年份
- [ ] Projects：项目名称、描述、链接
- [ ] Contact：邮箱（mailto 链接和显示文字两处）、Google Scholar
- [ ] 可选：头像照片（assets/avatar.jpg，放开 index.html 里注释的 img 标签）
