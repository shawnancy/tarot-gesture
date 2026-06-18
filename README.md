# 幽冥塔罗 · ARCANA NOCTURNE

手势识别塔罗占卜网页。摄像头实时识别手势：移动手掌横向滚动 3D 转盘选牌、握拳抓取，凑齐牌阵张数出完整解读。纯浏览器本地运行，零后端、零 API key。

🔗 在线体验：https://shawnancy.github.io/tarot-gesture/

## 玩法

- 🖐 **移动手掌** — 左右滚动 3D 转盘选牌
- ✊ **握拳** — 抓取当前停在正前的牌
- ✌ **胜利手势** — 切换牌阵

三种牌阵：圣示牌（1 张）/ 时间之流（3 张）/ 十字牌阵（5 张）。不用摄像头也能点按钮抽牌。

## 技术

- 手势识别：[MediaPipe Tasks Vision](https://developers.google.com/mediapipe)（浏览器本地，画面不上传）
- 横向 3D 转盘：纯 CSS 3D transform
- 完整 78 张韦特塔罗（大/小阿尔卡那，正逆位牌意）
- 单文件静态站，零依赖后端

## 本地运行

```bash
python3 -m http.server 8765
# 打开 http://localhost:8765   （摄像头需 localhost 或 https，勿直接双击文件）
```

> 仅供娱乐与自我反思，命运掌握在自己手中 ✦
