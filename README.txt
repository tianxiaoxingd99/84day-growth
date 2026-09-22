84天成长计划 App（PWA）
======================

文件说明
- index.html：App 主界面
- manifest.webmanifest：PWA 安装信息
- sw.js：离线缓存
- icon-192.png / icon-512.png：桌面图标

使用方式
1. 直接使用：打开 index.html 即可查看计划与打卡（本地文件模式）。
2. 安装到手机桌面：需要把整个文件夹部署到 HTTPS 静态网站后访问。
   可使用 GitHub Pages、Cloudflare Pages、Vercel、Netlify 等静态托管。
3. iPhone Safari：打开部署后的网址 → 分享 →“添加到主屏幕”。
4. Android Chrome：打开部署后的网址 → 菜单 →“安装应用”或“添加到主屏幕”。

数据
- 进度和备注存储在浏览器 localStorage。
- App 内“设置 → 导出数据”可备份为 JSON。
- 更换浏览器/设备前建议导出备份。
