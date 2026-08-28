# 南京王俊凯旅行 Todo

这是一个纯静态、单文件的旅行清单网页，适合通过微信打开。

## 功能

- 勾选 / 取消勾选 48 个旅行事项
- 自动统计完成数量和完成度
- 勾选状态保存在当前手机浏览器的 `localStorage`
- 支持临时新增事项
- 支持移动端微信内置浏览器和桌面端响应式布局
- 无第三方依赖，无需服务器端代码
- 使用 `logo.png` 作为网页 Logo、favicon 和 iPhone 主屏图标

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `travel-todolist`。
2. 上传本文件夹里的 `index.html` 和 `README.md`。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`，保存。
5. 等待 GitHub Pages 发布后，会得到一个类似 `https://你的用户名.github.io/travel-todolist/` 的地址。
6. 把这个 HTTPS 地址发到微信即可。若微信内置页面显示异常，点右上角“…”选择“在 Safari 中打开”。

发布后，在 iPhone Safari 中点击“分享 → 添加到主屏幕”，可以像小 App 一样使用。

## 说明

这是“单设备保存”版本：勾选状态只保存在当前 iPhone / 当前浏览器中。若希望多人或多台设备同步，需要接入数据库或改造成微信小程序。
