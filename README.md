# Hi, I'm DaftKen

**Practical macOS tools and playful desktop experiences.**

我开发解决日常问题的 macOS 工具与互动产品：让显示器更好用，让桌面更有趣，也让输入问题更容易排查。

[个人主页 / Portfolio](https://tech.wenmq.cn/) · [体验 PetApp / Try PetApp](https://tech.wenmq.cn/petapp/)

My background is in Android and Flutter. Today I build local utilities and interactive products, with an interest in reusable AI workflows. I care about useful results, clear setup, and evidence that matches the claims.

## Selected work

### [DisplayDJ](https://github.com/hellowmq/displaydj) · Display control for macOS

Two apps for different display-control needs:

- **Full 1.2.0 · stable** — Brightness, display modes, profiles and disconnect/reconnect, with a standalone CLI and optional local HTTP service. [Download Full](https://github.com/hellowmq/displaydj/releases/tag/v1.2.0)
- **Lite 0.3.0 · prerelease** — Basic hardware brightness and external-display disconnect/reconnect, with saved recovery. No CLI or local service. [Try Lite](https://github.com/hellowmq/displaydj/releases/tag/lite-v0.3.0)

Both apps can now check for updates. If you have an earlier version, download this release manually. Apple Silicon ZIP and DMG builds are ad-hoc signed and not notarized; hardware support varies by display, connection, and macOS version.

[中文使用说明](https://github.com/hellowmq/displaydj/blob/master/README.zh-CN.md) · [Compare the real app windows](https://github.com/hellowmq/displaydj#readme)

### [PetApp](https://github.com/hellowmq/pet-apps) · Interactive desktop companions

Pet, feed, and play with Tuanzi and Roundhead Maodie in your browser. The Electron desktop app adds a floating pet, dragging, and tray controls; it currently runs from source.

<img src="https://raw.githubusercontent.com/hellowmq/pet-apps/master/docs/media/tuanzi-canvas.gif" width="320" alt="团子在画布中活动的渲染预览">

[Try the live demo](https://tech.wenmq.cn/petapp/) · [Run the desktop app](https://github.com/hellowmq/pet-apps#从源码运行桌面版)

### [FocusTrace](https://github.com/hellowmq/FocusTrace) · macOS input diagnostics

Investigate interrupted typing by correlating keyboard, pointer, and frontmost-app events. The Swift CLI listens without blocking or changing input. Synthetic tests verify the documented rules, not real-world detection accuracy.

[中文排查指南](https://github.com/hellowmq/FocusTrace/blob/master/README.zh-CN.md) · [Verification and limits](https://github.com/hellowmq/FocusTrace/blob/master/docs/verification-report.md)

## More tools

- **[Tact Taste](https://github.com/hellowmq/tact-taste)** — A UI and interaction design skill for AI coding assistants: layout, typography, materials and operation feedback. [在线体验 / Live examples](https://tech.wenmq.cn/tact-taste/) · [演示短片 / Showreel](https://tech.wenmq.cn/tact-taste/showreel.html)
- **[Keyboard Hajimi Groove](https://github.com/hellowmq/keyboard-hajimi-groove)** — Musical feedback for macOS shortcuts. Build from source and bring your own permitted audio. [中文说明](https://github.com/hellowmq/keyboard-hajimi-groove/blob/main/README.zh-CN.md)
- **[MCR Mahjong Calculator](https://github.com/hellowmq/mcr-mahjong-calculator)** — An offline-capable scoring tool and 81-pattern reference. [国内入口 / Mainland China](https://tech.wenmq.cn/mcr-mahjong-calculator/) · [ChatGPT 版备用 / ChatGPT backup](https://guobiao-mahjong-calculator.firehorsek.chatgpt.site/)
- **[emoji-to-pet](https://github.com/hellowmq/emoji-to-pet)** — A resumable workflow for animated-pet candidate packages, with explicit asset and verification steps.
- **[skill-adapter](https://github.com/hellowmq/skill-adapter)** — Convert skill packages, commands, and rules into formats used by different coding tools.

For project questions and reproducible bugs, open an issue in the relevant repository. I’m also exploring how these focused tools and AI workflows can support practical engineering delivery.
