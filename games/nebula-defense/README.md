# 星云防线：超新星（Nebula Defense v2.0）

一款 **零依赖、开源、移动端与桌面端兼容** 的科幻纵版射击游戏。使用 HTML5 Canvas、原生 JavaScript 与 Web Audio API，下载 `index.html` 后离线即可游玩。

## 运行

- 在线（GitHub Pages 已部署的情况下）：https://hankaiyanh-dot.github.io/kaige/games/nebula-defense/
- 离线：直接在 Chrome、Edge 或其他现代浏览器打开 `index.html`。

## 玩法

- 手机：在画布上拖动战机；点击「💨 冲刺」闪避；充能后点击「⚡ 等离子脉冲」清屏。
- 电脑：WASD 或方向键移动，Q 冲刺，空格 / Shift 脉冲，P / Esc 暂停。
- 自动射击、多种敌机与精英敌机、周期性旗舰 Boss、武器升级与限时道具。
- 连续击杀积累连击，最高 5 倍积分；本地浏览器记录最高分。

## 技术说明

- 不使用第三方 CDN、字体或素材，不上传用户数据。
- 音效由 Web Audio API 实时合成，并非 Spotify 音轨；不需要 Spotify 登录或音乐许可。
- 游戏逻辑按 `requestAnimationFrame` 的时间差推进；页面失去焦点时自动暂停。
- 最高分仅储存在当前浏览器 `localStorage` 中；无账号同步。

## 开源

本目录代码使用 MIT License 开源，允许修改和再发行，请保留版权与许可声明。欢迎提 Issue 或 Pull Request。

## 已知限制

游戏是轻量街机作品，没有服务端排行榜、云存档或多人联网。浏览器兼容性与手机性能存在差异，建议使用现代 Chromium 浏览器。
