# 猩猩拆楼 · Old West Web

[在线游玩](https://rampage-recreation.github.io/)

Build46：浏览器中的 Old West 八栋建筑挑战，以及单栋练习。支持电脑键盘与手机屏幕按钮。纯静态网页，无需后端或构建。

## 操作

方向键或 WASD 移动；靠墙按 ↑ 攀爬；J 抓取/拆楼；K 拳击；楼顶 ↓＋J 砸楼；Space 跳跃；POWER 蓄满按 L；P 暂停；R 重开。声音默认关闭，可点击声音按钮启用。

## 来源与范围

这是对 PS1《Rampage Through Time》（USA，SLUS-01065）Old West 场景的研究复刻，包含 George 角色、原作提取图像和部分逆向移植逻辑。图像并非本项目原创。原作名称及原作内容的权利归相应权利人；本仓库公开不构成对第三方内容的授权。

音效为合成音效，没有原版音乐。本仓库不包含 ROM、EXE 或 BIOS；运行时也不需要这些文件。项目不是原版完整引擎或完整游戏，具体来源、适配边界及验收记录见 [provenance.json](provenance.json)。

## 本地运行

在此目录运行 `python3 -m http.server 8777`，打开 `http://localhost:8777/`。

## 部署

GitHub Pages 使用 main 分支根目录发布。`.nojekyll` 保证按静态文件发布。
