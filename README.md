# 🌟 Daily GitHub Activity

自动化每日 GitHub 活动，让你的仓库每日都有动静 📈

---

## 🚀 功能概览

| 功能 | 描述 | Emoji |
|------|------|-------|
| 每日随机日志 | 自动在 `update.md` 生成日志记录日常灵感或小操作 | 🌱 |
| 自动创建 Issue/PR | 随机创建每日 Issue 或 PR | 📦 |
| 自动 Review & Merge PR | 自动审查并合并待合并 PR | ✅ |
| 随机 Star 仓库 | 给热门仓库加星或指定用户仓库加星 | ⭐ |
| 自动 Fork 仓库 | 自动 Fork 指定用户的仓库 | 🍴 |
| 自动清理日志 & 分支 | 清理超过 7 天的日志和已合并分支 | 🧹 |
| 日终总结 | 自动统计各类操作数量，生成日报 | 🌙 |

---

## 📁 文件说明

- `update.md`：每日日志记录  
- `.github/workflows/daily-activity.yml`：GitHub Actions 工作流配置  
- `README.md`：项目介绍

---

## ⚙️ 使用方法

1. Fork 或克隆本仓库  
2. 创建 [Personal Access Token (PAT)](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)  
3. 在仓库 Secrets 中添加 `GH_PAT`  
4. 工作流会每天自动运行，也可手动触发 `workflow_dispatch`

---

## 📊 日志示例

```markdown
## 2025-09-08

### 🌱 日常记录
[08:05:00] ☕ 边喝咖啡边写点代码～
[10:22:03] 🎯 试试新点子

### 📦 Issue / PR
[11:00:05] 📝 创建了 Issue #12 - Daily Issue - 2025-09-08
[11:05:20] 📦 提交了一个 PR

### ✅ 自动审查与合并
[11:30:40] ✅ 自动合并了 PR #15

### ⭐🍴 Star & Fork
[13:20:01] ⭐ Starred vercel/next.js
[13:20:02] 🍴 Forked facebook/react
[14:05:11] ⭐ Starred octocat/Hello-World
[14:05:12] 🍴 Forked octocat/Spoon-Knife

### 🧹 清理任务
[18:00:00] 🗑️ 删除已合并超过 7 天的分支: daily-pr-20250901080000
[18:01:00] ✂️ 删除 7 天前的日志

### 🌙 今日总结
- 📝 日志条目：2
- 🔧 创建 Issue：1
- 📦 创建 PR：1
- ✅ 合并 PR：1
- ⭐ 随机 Star：1
- 🍴 随机 Fork：1
- ⭐ 用户 Star：1
- 🍴 用户 Fork：1
- 🧹 清理日志：完成
- 🧹 清理分支：1
