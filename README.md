# Hi, I'm DaftKen

**Practical macOS tools and playful desktop experiences.**

我开发解决日常问题的 macOS 工具与互动产品：让显示器更好用，让桌面更有趣，也让输入问题更容易排查。

[个人主页 / Portfolio](https://tech.wenmq.cn/) · [体验 PetApp / Try PetApp](https://tech.wenmq.cn/petapp/)

My background is in Android and Flutter. Today I build local utilities and interactive products, with an interest in reusable AI workflows. I care about useful results, clear setup, and evidence that matches the claims.

## Selected work

### [DisplayDJ](https://github.com/hellowmq/displaydj) · Display control for macOS

Control brightness, switch display modes, and disconnect or reconnect a display from the Mac desktop without unplugging it. Use the menu bar app or standalone CLI; the local HTTP service is optional.

Apple Silicon ZIP and DMG downloads are available. Builds are ad-hoc signed and not notarized; hardware support varies by display, connection, and macOS version.

[Download latest](https://github.com/hellowmq/displaydj/releases/latest) · [中文使用说明](https://github.com/hellowmq/displaydj/blob/master/README.zh-CN.md)

### [PetApp](https://github.com/hellowmq/pet-apps) · Interactive desktop companions

Pet, feed, and play with Tuanzi and Roundhead Maodie in your browser. The Electron desktop app adds a floating pet, dragging, and tray controls; it currently runs from source.

<img src="https://raw.githubusercontent.com/hellowmq/pet-apps/master/docs/media/tuanzi-canvas.gif" width="320" alt="团子在画布中活动的渲染预览">

[Try the live demo](https://tech.wenmq.cn/petapp/) · [Run the desktop app](https://github.com/hellowmq/pet-apps#从源码运行桌面版)

### [FocusTrace](https://github.com/hellowmq/FocusTrace) · macOS input diagnostics

Investigate interrupted typing by correlating keyboard, pointer, and frontmost-app events. The Swift CLI listens without blocking or changing input. Synthetic tests verify the documented rules, not real-world detection accuracy.

[中文排查指南](https://github.com/hellowmq/FocusTrace/blob/master/README.zh-CN.md) · [Verification and limits](https://github.com/hellowmq/FocusTrace/blob/master/docs/verification-report.md)

## More tools

- **[Keyboard Hajimi Groove](https://github.com/hellowmq/keyboard-hajimi-groove)** — Musical feedback for macOS shortcuts. Build from source and bring your own permitted audio. [中文说明](https://github.com/hellowmq/keyboard-hajimi-groove/blob/main/README.zh-CN.md)
- **[MCR Mahjong Calculator](https://github.com/hellowmq/mcr-mahjong-calculator)** — An offline-capable scoring tool and 81-pattern reference. [Try it online](https://guobiao-mahjong-calculator.firehorsek.chatgpt.site/)
- **[emoji-to-pet](https://github.com/hellowmq/emoji-to-pet)** — A resumable workflow for animated-pet candidate packages, with explicit asset and verification steps.
- **[skill-adapter](https://github.com/hellowmq/skill-adapter)** — Convert skill packages, commands, and rules into formats used by different coding tools.

For project questions and reproducible bugs, open an issue in the relevant repository. I’m also exploring how these focused tools and AI workflows can support practical engineering delivery.
