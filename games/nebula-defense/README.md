# 星云防线 · NEBULA DEFENSE (v2.0)

轻量、零依赖的 HTML5 Canvas 太空射击游戏。手机和桌面浏览器均可运行，单个 `index.html` 无需联网。

## 立即游玩

- 源码： https://github.com/hankaiyanh-dot/kaige/tree/main/games/nebula-defense
- GitHub Pages（若仓库已启用 Pages）： https://hankaiyanh-dot.github.io/kaige/games/nebula-defense/
- 离线：下载 `index.html` 并在现代浏览器中打开。

## 操作

- 手机：触摸画布拖动战机；等离子脉冲蓄满点击右下方按钮；双击画布也可触发。
- 电脑：方向键/WASD 移动，空格/Shift 释放脉冲，P/Esc 暂停；强化选择按 1/2/3。

## v2.0 内容

- 自动射击与最高五弹道武器升级，最多两个辅助僚机
- 普通敌人、精英敌机与周期性旗舰 Boss
- 连击积分倍率（最高 ×5）、波次、生存时间和最高分
- 每三波一次三选一战术强化：伤害、暴击、再生、武器、护盾、磁吸等八种强化
- 陨石障碍及粒子爆炸特效
- 回血、护盾、极速射击、能量、僚机、磁吸战利品
- 动态星云背景、粒子爆炸、震屏与 Web Audio API 合成音效
- 自动暂停、触屏与键盘支持；本地最高分记录

## 技术与隐私

原生 JavaScript + HTML5 Canvas + CSS。无第三方库、外链依赖、广告、分析 SDK 和网络请求；最高分保存在浏览器 localStorage。声音由代码实时合成，未使用 Spotify 商业音乐。

## 开源

本游戏目录以 MIT License 开源，详见 [LICENSE](LICENSE)。欢迎提交 Issue / PR。

## 已知限制

无云存档、账号、联网排行榜。GitHub Pages 的公开地址是否可访问取决于仓库 Pages 配置。建议在 Chrome / Edge 浏览器运行。
