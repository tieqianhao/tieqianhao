# 余星乐 · 网络空间安全

四川大学网络空间安全专业 2028 届本科在读。求职方向：**渗透测试 / 安全服务 / 安全研发**，对游戏安全与内容安全方向有持续积累。

三条主线，全部开源、全部可当场复现：

## 二进制漏洞利用

- **[pwn-labs](https://github.com/tieqianhao/pwn-labs)** — 四个可复现的 x86-64 利用实验室：ret2text / ret2libc / UAF / tcache poisoning。全部在 Docker 标定的 Ubuntu 20.04 / glibc 2.31 环境中实测拿到 shell，`docker build` + `run_tests.sh` 一键 4 passed；文档含 glibc 2.23 经典手法在新版失效的实测分析。

## Web 安全

- **[portswigger-notes](https://github.com/tieqianhao/portswigger-notes)** — PortSwigger Web Security Academy 学习笔记，30+ 实验逐篇记录原理与 payload。
- **[flask-vuln-lab](https://github.com/tieqianhao/flask-vuln-lab)** — Web 安全课程靶场：Flask 用户管理系统，从 21 个漏洞到完全修复的完整攻防对照。

## AI 与内容风控

- **[aigc-forensics](https://github.com/tieqianhao/aigc-forensics)** — 多信号融合的 AIGC 图像取证检测器：免训练、可解释，15 个测试样本判定完全分离，提供 CLI / JSON / Web 三种用法。
- **[raven](https://github.com/tieqianhao/raven)** — 游戏 / 二次元社区黑产内容风控：对抗性归一化 + 字符级模型 + 分级处置。
- **[FUSED](https://github.com/tieqianhao/FUSED)** — ICME 2026 论文复现：SparseViT 取证分支，用于 AI 图像修复检测。

## 安全工程与情报

- **[vuln-daily](https://github.com/tieqianhao/vuln-daily)** — 全自动漏洞情报日报：每日聚合 CISA KEV / NVD / GitHub Advisory，去重后按游戏引擎与内容安全组件关注列表过滤，GitHub Actions 定时生成并自动提交，无需任何密钥。

## 联系

邮箱：2180572500@qq.com ｜ 求职方向：渗透测试 / 安全服务 / 安全研发实习
