# Zhou Xinpei — Personal Website (Interactive)

这是一个简单的静态交互式个人主页模板，使用 HTML/CSS/vanilla JS + JSON 数据驱动，支持多语言（EN/FR/ZH），可直接部署到 GitHub Pages（仓库名应为 `zhou.xinpei.github.io`）。

主要功能
- 多语言切换（English / Français / 中文）
- 从 data/resume.json 加载简历内容（职位、教育、出版物、技能等）
- 互动时间轴（鼠标悬停/点击显示条目）
- 筛选与搜索出版物
- 联系信息一键复制、下载简历链接

如何使用
1. 将本仓库文件放到 `main` 分支或 `gh-pages` 分支。
2. 在仓库设置 > Pages 中启用 GitHub Pages（branch: main 或 gh-pages）。
3. 将 `data/resume.json` 中的内容替换为你的最终简历文本（已包含你的主要条目）。
4. 上传你的 PDF 简历文件到 `assets/files/`（例如 `CV_Zhou_Xinpei_EN.pdf`）。
5. 自定义样式与图片 `assets/img/`。

如果你愿意，我可以：
- 把这些文件推送到你的仓库（需要你确认推送分支）。
- 帮你把英文/法文/中文的完整翻译补齐（目前已填英文与中文，法文仅做界面翻译占位）。