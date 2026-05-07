<h1 align="center">VoiceBee</h1>

<p align="center">
  <strong>Hold a key, speak, release — your words appear at the cursor in any app.</strong><br/>
  Native macOS voice input, fully local-first.
</p>

<p align="center">
  <a href="https://github.com/answer2023/VoiceBee-Releases/releases/latest"><strong>⬇️ Download latest release</strong></a>
</p>

<p align="center">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-14%2B-1f425f?style=flat-square" />
  <img alt="Apple Silicon" src="https://img.shields.io/badge/Apple%20Silicon-required-805ad5?style=flat-square" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT-2f855a?style=flat-square" />
  <img alt="Local-first" src="https://img.shields.io/badge/local--first-✓-2f855a?style=flat-square" />
</p>

---

## English

VoiceBee is a native macOS voice input app for any text field — ChatGPT, Claude, Cursor, Notion, your editor, your terminal. Hold a key, speak, release. The transcript appears at the cursor.

The differentiator: **it can run with zero network**. VoiceBee uses Apple's built-in speech recognizer for transcription and supports Ollama for local LLM polishing — meaning the entire pipeline can stay on your machine. No API keys, no audio uploads, no vendor account. You can also point it at Claude / DeepSeek / Gemini / OpenAI-compatible endpoints if you want a stronger polish model — but you don't have to.

## 中文

VoiceBee 是一款原生 macOS 语音输入工具:在任何文本框里按住快捷键、说话、松开,转写文本立刻落到光标位置。可用于 ChatGPT、Claude、Cursor、Notion、编辑器、终端等等。

差异化在于**零网络也能跑**:语音识别使用 Apple 系统自带的 SFSpeechRecognizer,润色阶段支持 Ollama 本地模型,整条链路可以完全留在本机。不需要 API key,不上传音频,不绑定云账号。你也可以接入 Claude / DeepSeek / Gemini / OpenAI 兼容端点拿更强的润色模型,但这不是必须的。

---

## 下载 / Download

| 通道 / Channel | 链接 / URL |
|---|---|
| Latest release page | <https://github.com/answer2023/VoiceBee-Releases/releases/latest> |
| Direct DMG (current: v1.2.2) | <https://github.com/answer2023/VoiceBee-Releases/releases/download/v1.2.2/VoiceBee-1.2.2.dmg> |

> ⚠️ Current builds are **not yet notarized**. On first launch you may need to right-click the app → "Open" to bypass Gatekeeper. Notarization is on the roadmap.
>
> 当前版本暂未 Apple 公证,首次启动可能需要"右键 → 打开"绕过 Gatekeeper。公证流程是待办项。

## 系统要求 / System requirements

- **macOS 14.0 (Sonoma)** or later
- **Apple Silicon** (M1 / M2 / M3 / M4) — current builds are arm64 only; Intel Macs are not supported
- Microphone permission (prompted on first use)
- Optional: Ollama for fully local polishing, or any OpenAI-compatible endpoint

## Screenshots

_Screenshots coming soon._

## About this repository

This repository hosts **public release artifacts only** for VoiceBee — DMG installers and the Sparkle update feed. The application source code lives in a separate, currently private repository.

- **DMG installers** — see the [Releases](https://github.com/answer2023/VoiceBee-Releases/releases) tab.
- **Sparkle appcast** — [`appcast.xml`](./appcast.xml). The in-app auto-updater fetches this file from `raw.githubusercontent.com` to discover new versions.

If you have questions or feedback, please open an issue here.

## License

[MIT](./LICENSE).
