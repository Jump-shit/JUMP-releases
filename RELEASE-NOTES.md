# JUMP 1.0.0 Public Beta

首发面向 Apple Silicon Mac。免费访客版，无需账户。JUMP 支持富文本编辑、本地保存、DOCX 与 PDF 导出，以及 PDF 阅读、缩放、全文搜索和本地文字高亮。

- 安装包：`JUMP-1.0.0-beta.1-macos-arm64.dmg`
- 对应候选：`ffbbb8c`
- SHA-256：`fa16467174bdb7acd4ca56c71a7c66b30b8e5225e991e67f17f6bbef4a21ecf0`
- 系统：Apple Silicon。最低兼容系统以最终实测结果为准。
- 安装：核对同目录的 `.sha256` 文件，打开 DMG，将 JUMP 拖入「应用程序」。已有 JUMP 的用户请先备份。
- 签名：此包没有 Apple Developer ID 签名或公证。遇到首次打开提示，请查看 [Apple 官方说明](https://support.apple.com/102445)。
- 限制：高亮保存在 JUMP 本地阅读库，当前不会写入 PDF。扫描 PDF 无文字层时无法直接搜索或文字高亮。复杂 DOCX 的格式可能有差异。更新须手动下载。
- 反馈：saidwanderman@gmail.com。请附上 JUMP 版本、macOS 版本与复现步骤。

## English

JUMP is a free, local-first document editor and PDF reader for Apple Silicon Macs. This public beta runs in guest mode and requires no account.

- Edit rich-text documents, save locally, and export DOCX or PDF. Open, zoom, and search PDFs with a text layer.
- Highlights are saved in the local JUMP library and are not written to the original PDF. Scanned PDFs without a text layer cannot be searched or highlighted as text. Complex DOCX formatting can differ.
- Verify the DMG using the accompanying SHA-256 file, open it, and drag JUMP to Applications. This build has no Apple Developer ID signature or notarization. See [Apple's opening instructions](https://support.apple.com/102445).
- Updates are manual. For feedback, email saidwanderman@gmail.com with the JUMP and macOS versions and steps to reproduce.
