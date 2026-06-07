# Pokémon Ti — 宝可梦人格测试

测试你与哪只宝可梦最相似！回答 30 道题，揭晓你的宝可梦人格。

## ✨ 特色

- 🎯 **1025 只宝可梦**，覆盖全世代
- 🧠 **五维人格模型**：活力 · 理性 · 冒险 · 羁绊 · 意志
- 🎨 **宝可梦风格 UI**：精灵球动画、粒子背景、响应式设计
- 🎵 **背景音乐**：未白镇 8-bit 版
- 📱 **手机适配**：全端可用

## 🚀 在线体验

🔗 **[pokemonti.pages.dev](https://pokemonti.pages.dev)**

## 🛠 技术栈

- 纯静态前端，单文件部署
- Tailwind CSS + DaisyUI
- 精灵图来自宝可梦官方素材

## 📁 项目结构

```
├── index.html          # 主页面（全部逻辑内嵌）
├── bgm.mp3             # 背景音乐
├── vendor/             # 本地化 CDN 依赖
│   ├── daisyui.min.css
│   └── tailwind.js
├── sprites/            # 1025 张宝可梦精灵图
├── solver.js           # 答题卡计算工具（Node.js）
└── BGM/                # 原始音乐文件
```

## 🖥 本地运行

直接浏览器打开 `index.html` 即可，无需构建工具。

## 📝 答题卡计算

`solver.js` 可以根据任意宝可梦的五维档案反算最优答题卡：

```bash
node solver.js  # 默认计算 #25 皮卡丘
```

修改最后一行的宝可梦编号即可计算其他宝可梦。

## 📄 License

MIT
