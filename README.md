# Hi, I'm DaftKen

**Building practical tools for everyday work, focused diagnostics, and playful interactions.**

My background is in Android and Flutter. Today, I build local-first macOS utilities, offline web tools, desktop companions, and reusable workflows. I care about the full path from a real problem to a runnable result, with clear setup instructions and honest limits.

## Selected work

### [Keyboard Hajimi Groove](https://github.com/hellowmq/keyboard-hajimi-groove) · Shortcut audio for macOS

A macOS menu-bar app that gives copy, paste, undo, save, find, and function keys musical feedback using local audio you provide. Ordinary typing stays quiet, and a local segment editor helps prepare and tune clips.

The repository currently provides source code rather than a signed app bundle. Audio is not included; users must supply files they have the right to use.

[中文使用说明](https://github.com/hellowmq/keyboard-hajimi-groove/blob/main/README.zh-CN.md)

### [FocusTrace](https://github.com/hellowmq/FocusTrace) · macOS input diagnostics

A Swift command-line tool for investigating interrupted typing and unexpected focus changes. Its listen-only event tap correlates keyboard, pointer, and frontmost-app events without blocking or modifying input.

Its automated verification uses synthetic timelines to test the documented rules; those suite results do not establish real-world accuracy.

[中文排查指南](https://github.com/hellowmq/FocusTrace/blob/master/README.zh-CN.md) · [Verification report](https://github.com/hellowmq/FocusTrace/blob/master/docs/verification-report.md)

### [MCR Mahjong Calculator](https://github.com/hellowmq/mcr-mahjong-calculator) · Offline scoring tool

A mobile-first, offline-capable calculator and 81-pattern reference for Mahjong Competition Rules. It uses a self-made SVG tile set and needs no account, backend, database, or runtime API.

[Try the live calculator](https://guobiao-mahjong-calculator.firehorsek.chatgpt.site/)

### [pet-apps](https://github.com/hellowmq/pet-apps) · Desktop pets

An Electron desktop-pet monorepo with two original characters, direct manipulation, tray controls, and an embeddable `createPetRuntime`. The README includes renderer-only previews and separates source builds from distributable installers.

### [emoji-to-pet](https://github.com/hellowmq/emoji-to-pet) · Reusable creation workflow

A resumable Codex workflow for turning an emoji or visual reference into an animated-pet candidate package. It prepares prompts and evidence records while keeping image generation, asset rights, processing, and installation verification explicit.

## Other tools

[skill-adapter](https://github.com/hellowmq/skill-adapter) converts skill packages, slash commands, and rules into formats used by several coding tools, reducing repeated maintenance across tool-specific copies.

## What I'm working toward

I'm interested in software that earns its place in daily use: small tools that solve a concrete problem, explain what they need, and make their limits visible. For project questions or reproducible bugs, open an issue in the relevant repository.

---

中文：我从 Android / Flutter 开发出发，现在主要做能解决日常问题的 macOS 本地工具、离线 Web 工具、桌面互动产品和可复用工作流。代表作品优先展示真实用途、首次运行路径与限制，并区分源码可构建、已验证和仍需真实使用检验的部分。
