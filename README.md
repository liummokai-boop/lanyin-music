# lanyin-music

听屿音乐 App 的公网更新发布仓库。

## 文件

- `update.json`：App 启动时读取的版本清单
- `releases/tingyu-1.7.apk`：当前需要上传的安装包文件

## 更新线路

当前配置为双线路：

1. `cdn.jsdelivr.net`，中国区域通常比 GitHub raw 更友好
2. `raw.githubusercontent.com`，备用线路

## 后续发版

1. 上传新版 APK 到 `releases/` 目录。
2. 修改 `update.json` 里的 `latestVersionCode`、`latestVersionName`、`apkUrl` 和 `apkMirrors`。
3. 手机端打开听屿后会自动弹出更新提示。
