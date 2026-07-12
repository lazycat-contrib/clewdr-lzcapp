# clewdr-lzcapp

## 自动发布

每天 23:00 UTC 检查 `ghcr.io/xerxes-2/clewdr` 稳定版本，将镜像复制到 LazyCat Registry，构建版本化 GitHub Release Asset，并发布到懒猫官方商店和喵喵私有商店。推送 `v*` tag 可触发完整发布。
