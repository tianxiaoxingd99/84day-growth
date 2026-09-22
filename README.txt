84天成长计划 · 学习版 PWA v3

升级重点
- 每一天不再只是“任务名”，而是完整学习单元。
- 每天包含：学习目标、按顺序执行的 5 个左右步骤、动手练习、验收标准、卡住先检查、搜索关键词。
- 每个学习步骤可单独勾选。
- 继续兼容旧版 localStorage key，部署到原 GitHub Pages 地址后，原有打卡/备注应继续保留。
- Service Worker 缓存版本已升级为 v3。

更新 GitHub Pages
1. 解压 ZIP。
2. 在原仓库中用本包的 index.html、manifest.webmanifest、sw.js、icon-192.png、icon-512.png 替换旧文件。
3. Commit changes。
4. 等 GitHub Pages 更新后，iPhone 上关闭并重新打开 App。
5. 若仍显示旧页面：Safari 刷新一次站点，或稍后重新打开；PWA 缓存会更新到 v3。
