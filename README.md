# 轻松记账（离线版）

这是静态网页应用样稿。账目保存在手机浏览器的 IndexedDB 中，不会上传到账本服务器。首次打开需要联网；添加到 iPhone 主屏幕后，缓存完成后可离线打开。

## 免费发布到 GitHub Pages

1. 在目标账号创建一个新的**公开**仓库，例如 `light-ledger-offline`。
2. 将本文件夹中的文件上传到仓库根目录。
3. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，选择 `main` 分支和 `/ (root)`，保存。
4. 发布完成后用 Safari 打开 GitHub Pages 给出的 HTTPS 网址，选择“分享 → 添加到主屏幕”。

离线账本只在当前设备浏览器中。请定期用“更多功能 → 导出账本”保存 CSV 备份。微信 CSV 可直接导入；XLSX 和 ZIP 需要先转换为 CSV。
