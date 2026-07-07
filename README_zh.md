# Loop-Harness

Loop-Harness 是一个桌面级 Agent 工作区，用于本地自动化、项目工作流、Artifacts、定时任务和工具集成。

## 本地开发

环境要求：

- Node.js `>=24.15.0 <25`
- npm

```bash
npm install
npm run electron:dev:openclaw
```

本地 runtime 构建完成后，日常开发通常可以使用：

```bash
npm run electron:dev
```

## 项目说明

Loop-Harness 的上游跟踪信息只保留在本地。不要把本地上游快照分支或私有同步分支推送到公开远端。

本地仓库状态检查：

```bash
node scripts/loop-harness/upstream-status.cjs
```

