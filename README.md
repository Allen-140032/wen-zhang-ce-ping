# AI爆款潜力测评器

> 一个面向公众号创作者的开源文章自评工具。粘贴标题和正文，即可从 6 个维度获得评分、诊断和改稿建议。

[![在线体验](https://img.shields.io/badge/demo-%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C-brightgreen)](https://allen-140032.github.io/wen-zhang-ce-ping/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## 项目背景

公众号创作者在发布前通常只能依靠经验判断一篇文章是否值得发：标题够不够抓人、开头有没有钩子、段落是否适合手机阅读、结尾有没有转化出口。这些判断往往分散在脑子里，很难复盘，也很难让团队形成统一标准。

AI爆款潜力测评器把这套发布前检查清单做成一个纯前端工具，帮助创作者在发文前快速完成自检，并获得可执行的修改建议。

## 核心功能

| 维度 | 评分范围 | 检查重点 |
|:----:|:--------:|----------|
| 标题吸引力 | 1-10 | 是否包含数字、反差、痛点、悬念或明确价值 |
| 开篇钩子 | 1-10 | 首屏是否能迅速提出问题、冲突或结果 |
| 段落节奏 | 1-10 | 段落长度、小标题密度、移动端阅读压力 |
| 情绪曲线 | 1-10 | 是否有起伏、转折和情绪峰值 |
| 可读性 | 1-10 | 句子长度、技术术语密度、表达清晰度 |
| 行动号召 | 1-10 | 是否引导关注、评论、收藏、转发或继续阅读 |

工具会输出 60 分制总分、每个维度的单项反馈，以及一组综合修改建议。

## 在线体验

https://allen-140032.github.io/wen-zhang-ce-ping/

## 本地运行

```bash
git clone https://github.com/Allen-140032/wen-zhang-ce-ping.git
cd wen-zhang-ce-ping
```

然后直接用浏览器打开 `index.html`。

这个项目目前是零依赖纯前端实现，不需要安装 Node.js、Python 或后端服务。

## 截图

![网页版界面](screenshots/index_1280x800.png)

## 技术栈

- HTML / CSS / JavaScript
- LocalStorage 保存测评历史和本地使用状态
- GitHub Pages 静态托管

## 数据与隐私

- 默认演示模式在浏览器本地运行，不需要账号。
- 测评历史保存在用户自己的浏览器 LocalStorage 中。
- 当用户主动选择第三方 API 模式时，文章内容会发送到用户配置的 API 服务。
- 项目不内置后端数据库，也不收集用户文章内容。

详见 [PRIVACY.md](PRIVACY.md)。

## 评分规则

当前 MVP 使用透明的编辑启发式规则，不声称能客观预测真实流量。详见 [SCORING_RULES.md](SCORING_RULES.md)。

## Roadmap

- [x] 本地演示评分
- [x] GitHub Pages 在线版本
- [x] 测评历史记录
- [x] 报告复制与分享
- [ ] 更细的评分解释与可视化报告
- [ ] 可配置评分维度
- [ ] 多语言 README 与界面文案
- [ ] Chrome / Edge 扩展版本
- [ ] 自动化测试与发布流程

## 贡献

欢迎提交 Issue 和 PR。当前特别需要帮助的方向：

- 评分维度和启发式规则优化
- 更好的移动端阅读体验
- 报告导出为图片或 PDF
- 浏览器扩展权限和隐私说明完善
- 英文界面与多语言支持

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 协议

MIT License © 2026 Three-Body Work Group

---

Made by Three-Body Work Group: Friday, Zhang San, Boebo, and Allen.
