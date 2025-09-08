# 🌟 Daily GitHub Activity

**每日 GitHub 自动化任务**  
目标：保持仓库活跃，增加贡献绿格子，并生成每日日志。

---

## 📊 最近统计（自动更新）

| 指标 | 今日 | 最近 7 天 |
|------|------|------------|
| 📝 日志条目 | 0 | 0 |
| 🔧 创建 Issue | 0 | 0 |
| 📦 创建 PR | 0 | 0 |
| ✅ 合并 PR | 0 | 0 |
| ⭐ Star | 0 | 0 |
| 🍴 Fork | 0 | 0 |
| 🧹 清理日志 | 0 | 0 |
| 🧹 清理分支 | 0 | 0 |

> **提示**：这些数字可以通过 GitHub Actions 自动统计并更新。

---

## 🚀 功能概览

| 功能 | 描述 |
|------|------|
| 每日随机日志 | 自动生成 `update.md` 日志，记录日常操作 |
| 自动创建 Issue/PR | 保证每日有贡献记录 |
| 自动 Review & Merge PR | 自动审查并合并仓库内 PR |
| 自动 Star 仓库 | 给热门仓库或指定用户仓库加星 |
| 自动 Fork 仓库 | Fork 指定用户仓库 |
| 自动清理日志 & 分支 | 删除超过 7 天的日志和已合并分支 |
| 日终总结 | 自动统计每日操作数量并写入日志 |

---

## 📁 文件说明

- `update.md`：每日操作日志  
- `.github/workflows/daily-activity.yml`：GitHub Actions workflow  
- `README.md`：项目说明文档  

---

## ⚙️ 使用方法

1. Fork 或克隆本仓库  
2. 创建 [GitHub PAT](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)  
3. 添加仓库 Secrets：`GH_PAT`  
4. Workflow 每天自动运行，也可手动触发  

---
