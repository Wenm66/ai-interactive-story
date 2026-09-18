# AI Interactive Story

面向“雏雁计划”的 AI 互动叙事项目仓库。

## 项目目标

构建一个可由玩家选择推动剧情、并带有角色状态与分支记忆的 AI 互动叙事原型。

## 规划技术栈

- 前端：React + TypeScript
- 后端：Python + FastAPI
- AI：通过后端统一调用生成式 AI 服务
- 数据交换：HTTP + JSON
- 剧情内容：Markdown / JSON
- 设计：Figma
- 素材：图片、音频、视频（大型源文件不直接提交到 Git）

## 目录结构

```text
frontend/   前端应用
backend/    后端服务与 AI 接口
story/      剧情、分支、角色设定和世界观
design/     UI/UX 设计说明与原型链接
assets/     轻量素材、素材索引和占位资源
docs/       项目文档、接口约定和开发记录
```

## 协作约定

- `main` 分支保持可运行、可演示。
- 新功能使用独立分支，通过 Pull Request 合并。
- 前后端接口遵循 `docs/` 中的 JSON 约定。
- 不提交密钥、API Key、个人配置、大型视频或设计源文件。
- 大型素材应存放在团队约定的云盘中，并在 `assets/` 记录索引。

## 当前状态

仓库初始化阶段。后续将补充产品范围、接口草案、剧情数据结构与首个可运行 Demo。
