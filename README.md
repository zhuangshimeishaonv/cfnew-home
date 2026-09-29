# cfnew-home

cfnew v3.1 家宽节点部署备份（Cloudflare Worker）。

- Worker 名称：cfnew-home
- 兼容日期：2026-01-20
- 环境变量：u=<UUID>、jk=yes（家宽链式）
- 上游：byJoey/cfnew（明文源吗）
- 每日自动同步上游：由部署侧定时任务完成，有新版自动重部署

UUID 与订阅地址不写入仓库，保存在部署机本地。
