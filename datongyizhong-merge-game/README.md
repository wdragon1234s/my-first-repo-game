# 合成大同一中 · 海棠绽开

16 所大同及区县高中校徽合成游戏。两颗“大同一中”相撞后触发海棠花绽开动画。全部校徽已内嵌，无外部运行依赖，无需安装依赖或执行构建。

## 文件说明

- `index.html`：完整游戏，必须位于仓库根目录。
- `.nojekyll`：让 GitHub Pages 按静态文件原样发布，不经过 Jekyll 处理。
- `CREDITS.md`：校徽素材与排序口径说明。
- `README.md`：本部署说明。

## 上传到 GitHub Pages

1. 在 GitHub 新建一个仓库，建议设为 Public。
2. 解压本压缩包，将其中全部文件上传到仓库根目录，包括隐藏文件 `.nojekyll`。上传后应能直接在仓库首页看到 `index.html`，不要再套一层文件夹。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中，将 **Source** 设为 **Deploy from a branch**。
5. 选择 `main` 分支和 `/(root)` 目录，保存并等待 GitHub 完成发布。
6. 发布后，地址通常为 `https://你的用户名.github.io/仓库名/`，实际地址以仓库 Pages 页面显示为准。

本项目是纯静态 HTML，不需要 GitHub Actions、Node.js、npm 或任何构建命令。

## 本地打开

直接双击 `index.html` 即可游玩。最高分清空与保存使用浏览器 `localStorage`，仅在当前浏览器中生效，不会跨设备同步；清除浏览器数据会丢失本地最高分。

## 排名口径

当前页面明确标注为“2023 中考统招线参考排序（2026 升学数据待补）”，并未伪造 2026 年四项升学数据。详细素材来源见 `CREDITS.md`。
