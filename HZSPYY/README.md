# 尤迈线上系统录屏演示

这个文件夹已准备为 GitHub Pages 网站，视频可以在电脑和手机浏览器中在线播放。

## 使用 GitHub Desktop 发布

1. 打开 GitHub Desktop。
2. 选择 `File` → `Add Local Repository`。
3. 选择本文件夹：`youmai-video-page`。
4. 在左下角填写提交说明，例如“发布尤迈演示视频”，然后点击 `Commit to main`。
5. 点击顶部的 `Publish repository`。
6. 仓库名称建议填写 `youmai-video-demo`。
7. 如果希望任何拿到链接的客户都能打开，请取消勾选 `Keep this code private`，然后发布。
8. 在浏览器打开该 GitHub 仓库，进入 `Settings` → `Pages`。
9. 在 `Build and deployment` 下选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/(root)`，点击 `Save`。

稍等一两分钟后，页面地址通常是：

`https://你的GitHub用户名.github.io/youmai-video-demo/`

## 文件说明

- `index.html`：视频播放页面
- `youmai-demo.mp4`：网页兼容的 H.264 视频
- `poster.jpg`：视频封面

> 注意：公开 GitHub Pages 页面和其中的视频都可以被任何获得链接的人访问。播放器隐藏下载按钮只能减少误操作，不能阻止有技术能力的人保存视频。
