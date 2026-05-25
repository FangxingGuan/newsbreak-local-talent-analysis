# NewsBreak · 本地化战略人才分析

围绕 NewsBreak 从「本地新闻推荐平台」演进为「本地信息与服务平台」的战略人才盘点（算法与架构方向）。

## 核心路径

```
Content → Intent → POI → Marketplace
```

## 内容结构

1. **战略背景** — 演进路径与当前定位
2. **系统演进阶段** — Stage 1（已完成）/ Stage 2（核心缺失）/ Stage 3（未来）
3. **关键人才结构** — 三位核心负责人（P0 / P0.5 / P1）
4. **当前能力 vs 目标能力差距** — 已具备 vs 三大缺口
5. **人才招聘优先级** — P0 / P0.5 / P1 排序
6. **关键结论** — 最大风险与破局点

## 本地预览

```bash
# 直接打开
open index.html

# 或起一个本地 HTTP 服务（推荐）
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 部署

仓库已配置 GitHub Actions 自动部署到 GitHub Pages。
push 到 `main` 分支会自动发布。

> 私有仓库的 GitHub Pages 需要 GitHub Pro/Team/Enterprise 订阅。
> 免费账号可将仓库改为 Public 后启用。

## 文件结构

```
.
├── index.html      # 单页结构
├── styles.css      # 样式（深色主题，响应式）
├── README.md
└── .github/workflows/deploy.yml  # GitHub Pages 自动部署
```
