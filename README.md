# NapCat 全量备份

NapCatQQ 项目已官方宣布 Ending（v4.18.42 为最终版本）。本备份生成于 2026-11-12。

## 目录结构
- 源码/ —— 7 个仓库的 HEAD 源码导出（不含 .git 历史）
  - NapCatQQ（主仓库，最终 main 提交）
  - NapCatQQ-Desktop（原 NapNeko 仓库，后转移到 AQiaoYo 名下）
  - NapCatDocs / NapCat-Docker / NapCat-Installer / NapCatQQ-CLI / NapCat-Termux
- Release包/
  - NapCatQQ-v4.18.42/：4 个发行 zip 已解压（Shell / Shell-Windows-Node / OneKey / Framework）
  - NapCatQQ-Desktop-v3.5.20/：msi/deb/AppImage 安装器原样保留 + SHA256SUMS

## 完整性
- 全部 zip 已通过结构校验；Desktop 包 SHA256 全部 OK
