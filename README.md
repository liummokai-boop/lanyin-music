# lanyin-music

澜音音乐 App 的公网更新发布仓库。

## 文件

- `update.json`：App 启动时读取的版本清单
- `releases/lanyin-1.6.apk`：当前需要上传的安装包文件

## 后续发版

1. 上传新版 APK 到 `releases/` 目录。
2. 修改 `update.json` 里的 `latestVersionCode`、`latestVersionName` 和 `apkUrl`。
3. 手机端打开澜音后会自动弹出更新提示。
