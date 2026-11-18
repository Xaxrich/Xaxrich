# XtaxRich GitHub 主页 · 2026-11-18

本项目的入口是 [github.com/Xaxrich](https://github.com/Xaxrich)。个人主页由根目录的 Profile README 展示。2026-11-18 更新采用英文横幅、中文正文和英文概要。横幅以金属循环表现智能体的反馈过程。正文用公开项目呈现评测、权限和 AI 成本三个产品取舍，找房示例展示不同状态对应的下一步和验证指标。

## 横幅复现

| 内容 | 文件 |
| --- | --- |
| GitHub 使用的 1280 × 400 WebP | [profile-cover.webp](../media/profile-cover.webp) |
| 构图、字形和版式 | [banner.html](banner.html) |
| 内置 ImageGen 生成的 1536 × 1024 原件 | [feedback-loop.png](feedback-loop.png) |
| 本地字体及使用许可 | [Space Grotesk](space-grotesk.woff2) · [SIL Open Font License](space-grotesk-OFL.txt) |

在浏览器中以 1280 × 400 打开 `banner.html`，等本地字体和图像加载，截取 `.cover` 元素后导出 WebP。横幅中的文字可以在 HTML 里编辑。若移动素材目录，同时更新 `banner.html` 的相对引用。

原始生成简报用深色金属的开放环形雕塑展示反馈循环。抛光深铬色、同心细鳍片和酸绿色边缘灯是主要视觉依据。背景留黑，以适应左侧文字与窄横幅构图。原件保留完整画幅。

## 案例依据

- 显示名、产品定位、原有公开作品和岗位意向沿用 Git 历史中的上一版。 [个人简介原版](https://github.com/Xaxrich/Xaxrich/blob/060a8eb5492daaf1c5f88802c94b5059b40279d4/README.md)
- 评测平台是前端演示，案例依据包括用例、回归比较与 Trace 回放。 [Agent Eval Platform](https://github.com/Xaxrich/eval-platform/blob/28057761677d98aeacbde14a7fbd77701745431a/README.md)
- Claude Code Mini 是教学实现，依据是公开的五文件结构、Agent loop 和应用层权限规则。 [Claude Code Mini](https://github.com/Xaxrich/claude-code-mini/blob/ef268fd3e3126a83ee77b838b62f5fa77cbb1824/README.md)
- AI Cost Dashboard 是原型，依据是用户自填订阅和使用情况生成报告的流程。 [AI Cost Dashboard](https://github.com/Xaxrich/ai-cost-dashboard/blob/7bfa4bdaa1f0a33148d5ca11f615ca3185070c21/README.md)

## 初版验证

Chrome 加载了源图与字体，导出的 WebP 为 1280 × 400，约 57 KB。GitHub 的 GFM 渲染验证了相对路径横幅和替代文本、两个原生表格、三个可展开区以及三个代表作品的源码链接。
