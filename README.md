# 猩猩拆楼 · 三时代 Web / Build50

[在线游玩](https://rampage-recreation.github.io/play.html?level=area17&build=50) · [选择时代](https://rampage-recreation.github.io/)

已验收 Build50：George，Old West 八栋、Avalon 七栋、Area17 十一栋。支持电脑键盘和手机屏幕按钮，纯静态网页，无需后端或构建。

方向键/WASD 移动，靠墙 ↑ 攀爬，J 抓取/拆楼，K 拳击，Space 跳跃，满 POWER 按 L，P 暂停，R 重开。声音默认关闭，可点击声音按钮启用。

## 来源与范围

对 PS1《Rampage Through Time》（USA，SLUS-01065）的研究复刻，包含原作提取图像及部分逆向移植逻辑。原作名称及内容的权利归相应权利人；本仓库公开不构成第三方内容授权。未为原作素材添加开源许可。音效为合成音效，没有原版音乐；不包含 ROM、EXE、BIOS、完整 RAM/VRAM 或光盘，运行时无需这些文件。不是完整原引擎或完整游戏。

详见 [来源与边界](provenance.json)、[交付报告](REPORT50.md) 和 [用户验收记录](acceptance.json)。Avalon/Area17 恢复后的短暂保护为网页游玩适配。

本地运行：在此目录执行 `python3 -m http.server 8777`，打开 http://localhost:8777/ 。GitHub Pages 使用 main 分支根目录发布。
