# 拾光日记 · 发布仓库

本仓库存放「拾光日记」Android 应用的发布产物，供应用内在线更新使用：

- `update_manifest.json` — 版本清单（versionCode / versionName / apkUrl / changelog / minSupported）
- [Releases](../../releases) — 各版本 APK 下载

应用通过以下地址检查更新（兼容 GitHub Contents API）：

```
https://api.github.com/repos/willewu/shiguang-releases/contents/update_manifest.json
```

发布新版本时：递增 `versionCode`，上传新 APK 到 Release，并同步更新本清单。
