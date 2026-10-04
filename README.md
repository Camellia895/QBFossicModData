# QBFossicModData

QBMBAMM（远行星号模组管理器）的 fossic.org 数据镜像仓库。

仓库根目录的 `fossic-data-snapshot.json` 由 GitHub Actions 每天自动从
[api.fossic.org](https://api.fossic.org/docs#/) 拉取生成（`/mods` + 分类/语言元数据的合成快照），
供 QBMBAMM 客户端以"镜像优先、API 兜底"的方式获取中文社区模组数据，
降低 fossic API 的直接访问压力。

## 快照地址

- jsDelivr（大陆推荐）：`https://cdn.jsdelivr.net/gh/Camellia895/QBFossicModData@main/fossic-data-snapshot.json`
- raw（海外）：`https://raw.githubusercontent.com/Camellia895/QBFossicModData/refs/heads/main/fossic-data-snapshot.json`

## 手动刷新

Actions → Update fossic data mirror → Run workflow。
