# Install JUMP / 安装 JUMP

JUMP 1.0.0-beta.1 targets Apple Silicon Macs. The application uses ad hoc signing and has no Apple Developer ID signature or notarization.

1. When the beta is available, download the DMG and matching `.sha256` file from [GitHub Releases](https://github.com/Jump-shit/JUMP-releases/releases). Keep them together and run `shasum -a 256 -c JUMP-1.0.0-beta.1-macos-arm64.dmg.sha256` in that folder.
2. If verification returns `OK`, open the disk image, drag JUMP into Applications, eject the disk image, and open JUMP from Applications. Back up existing JUMP documents and the previous app before upgrading.
3. macOS may block the first launch. If you trust the source and verified the checksum, follow [Apple’s instructions](https://support.apple.com/102445). Stop if verification fails or macOS reports damage or malware.

当前支持 Apple Silicon Mac。应用未使用 Apple Developer ID 签名，也未经过 Apple 公证。

1. 公测上线后，从 GitHub Releases 下载 DMG 和同名 `.sha256`，放在同一目录，并在终端用上面的命令校验。
2. 确认显示 `OK` 后打开 DMG，把 JUMP 拖到「应用程序」，推出磁盘映像，再从「应用程序」启动。升级前备份现有 JUMP 文档和应用。
3. 首次打开如遇系统拦截，在确认来源可信且校验通过后参照 Apple 官方说明。校验失败、系统提示文件受损或有恶意软件时请停止安装。

Updates are manual. 更新须手动下载。
