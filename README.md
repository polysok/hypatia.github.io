<div align="center">

# 🦉 hypatia

### An AI study companion that *guides* students to the answer — instead of handing it over.

**Privacy-first · On-device options · Built for homework**

[![Platform](https://img.shields.io/badge/platform-iOS%2017%2B-blue)](https://www.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-SwiftUI-orange)](https://developer.apple.com/swift/)
[![Privacy](https://img.shields.io/badge/privacy-on--device-success)](#-privacy--security)
[![Languages](https://img.shields.io/badge/i18n-10%20languages-purple)](#-languages)

</div>

---

## ✨ The idea

Most AI assistants are answer machines. **hypatia is the opposite.**

When a student asks *“What’s the solution to this equation?”*, the tutor replies with a
guiding question, a method reminder, or a hint about the next step — **never the final
answer**. The goal isn’t to copy a result; it’s to *learn how to get there*.

This behaviour is enforced by a level-aware system prompt and adapts to where the
student is:

| Level | How the tutor adapts |
|-------|----------------------|
| 🎓 **Collège** *(middle school)* | Simpler vocabulary, smaller steps, more encouragement |
| 🎓 **Lycée** *(high school)* | More rigour, references to methods and theorems |
| 🎓 **Higher education** | Concise, assumes foundations, focuses on reasoning depth |

The student picks their level once in their **Profile** — the right guiding prompt is
selected automatically.

---

## 🚀 Features

- **🧠 Socratic chat** — the AI guides instead of solving, adapting pacing and rigour to the student’s level.
- **➗ Rich scientific rendering** — inline & block **LaTeX** (KaTeX), **scientific SVG diagrams** (atomic models, geometry figures), and full **Markdown**, all rendered inline in the conversation.
- **📝 Markdown notes** — a dedicated Notes tab with optional AI-suggested titles and **one-tap OCR from the clipboard** (Apple Vision) to capture an exercise from a screenshot.
- **🔌 Multi-model AI** — bring your own backend:
  - **Remote API** — any OpenAI-compatible endpoint (free models via [OpenRouter](https://openrouter.ai) / [Groq](https://groq.com), or Claude, GPT, Mistral…)
  - **Apple Intelligence** — fully on-device (iOS 26+)
  - **Qwen 3.5 Local** — runs entirely on your iPhone, no internet required
- **🖼️ Multi-modal input** — text, photos of exercises (camera / library / clipboard), and PDF/document attachments.

---

## 🔒 Privacy & security

hypatia is **privacy-first by design**:

- **Your data stays on your device** — the local database is never synced to any cloud.
- **API keys in the iOS Keychain** — encrypted, never exposed.
- **No telemetry** — no analytics, no tracking.
- **Prompt-injection protection** — user input is sanitized and truncated before any LLM call.

To stay focused on studying, hypatia deliberately leaves out email, calendar, knowledge
graphs, and long-term “user facts” memory. **Chat and Notes are the whole app.**

---

## 🌍 Languages

French · English · Spanish · Chinese (Simplified) · Japanese · Hindi · Indonesian · Tamil · Vietnamese · Khmer

---

## 🛠️ Tech stack

`Swift` · `SwiftUI` · `Realm` (local DB) · `FoundationModels` (Apple Intelligence) ·
`MNN` (on-device Qwen 3.5) · `KaTeX` / `markdown-it` (rich rendering) · Apple `Vision` (OCR)

---

<div align="center">

*Named after [Hypatia of Alexandria](https://en.wikipedia.org/wiki/Hypatia) — mathematician, astronomer, and teacher.*

**Learn how to get there.**

</div>
