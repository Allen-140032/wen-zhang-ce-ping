# AI爆款潜力测评器

> 粘贴你的公众号文章，6个维度出分，看看你的文章能打几分。

[![在线体验](https://img.shields.io/badge/demo-%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C-brightgreen)](https://allen-140032.github.io/wen-zhang-ce-ping/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 这是什么

一个纯前端工具，输入公众号文章的标题和正文，从 **6 个维度** 自动评分并给出修改建议：

| 维度 | 评分范围 | 测什么 |
|:----:|:--------:|--------|
| 标题吸引力 | 1-10 | 是否包含数字/反常识/痛点/悬念 |
| 开篇钩子 | 1-10 | 首段是否 3 秒内抓住读者 |
| 段落节奏 | 1-10 | 段落长度、小标题密度 |
| 情绪曲线 | 1-10 | 情绪是否有起伏 |
| 可读性 | 1-10 | 句式复杂度、长句比例 |
| 行动号召 | 1-10 | 结尾是否有引导关注 |

总分 **60 分**，附带针对性的改进建议。

## 快速开始

**在线使用（无需安装）：**
👉 https://allen-140032.github.io/wen-zhang-ce-ping/

**本地使用：**
```bash
git clone https://github.com/Allen-140032/wen-zhang-ce-ping.git
cd wen-zhang-ce-ping
# 直接双击 index.html 即可
open index.html
```

**Chrome 扩展（推荐）：**
在 Chrome Web Store 搜索「AI爆款潜力测评」安装（即将上架）。

**Chrome 扩展本地加载：**
1. 打开 `chrome://extensions/`。
2. 开启开发者模式。
3. 选择“加载已解压的扩展程序”。
4. 选择 `chrome-extension/` 目录。

## 评分模式

| 模式 | 需要API Key？ | 适用场景 |
|:----:|:------------:|----------|
| 本地演示 | ❌ 不需要 | 快速体验、文章自评 |
| DeepSeek API | ✅ 需输入Key | 需要更精准的AI分析 |
| API2D / GPT-4o | ✅ 需输入Key | 备选AI引擎 |

> 公开部署版本建议使用本地演示模式，无需泄露 API Key。

## 截图

<!-- 截图GIF，稍后添加 -->

## 技术栈

- 纯 HTML + CSS + JavaScript
- 零依赖，单文件部署
- 最近 10 次测评历史记录
- URL hash 分享永久链接
- 每日 5 次免费额度与 Pro 占位
- 赞赏码入口与 GitHub 开源入口
- 手机端自适应
- 支持 GitHub Pages 免费托管

## 路线图

- [x] MVP — 本地演示评分 + DeepSeek API 调用
- [x] GitHub Pages 部署
- [x] Chrome 扩展版 MVP 骨架
- [x] 测评历史记录
- [x] 报告分享/导出
- [ ] 批量测评（企业版）
- [ ] 更多评分模型接入

## 贡献

欢迎提交 Issue 和 PR！详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

特别需要帮助的领域：
- 新的评分维度/算法
- 更好的 UI/UX
- 报告导出功能（PDF/图片）
- 更多语言支持

## 协议

MIT License © 2026 三体工作组

---

**Made by 三体工作组** · 星期五（PM/策划）+ 张三（开发/设计）+ 水手勃勃（采集/运营）
