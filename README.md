# 🎤 Voice Claw

**Voice-to-text for Clawpilot** — speak, transcribe, enhance, paste.

🔗 **Try it now:** [https://neelmitra.github.io/voice-claw/](https://neelmitra.github.io/voice-claw/)

## What is Voice Claw?

Voice Claw is a browser-based voice-to-text tool built for [Clawpilot](https://github.com/anthropics/clawpilot). Speak naturally, and Voice Claw transcribes, cleans up, and formats your text — ready to paste into Clawpilot or any app.

- **No installation** — just open the URL in Edge or Chrome
- **4x faster** than typing (~150 wpm speaking vs ~45 wpm typing)
- **Works offline** — core features need no API key

## Features

| Feature | Needs API? |
|---|---|
| 🎤 Speech-to-text with live waveform | ❌ Free |
| 🧹 Auto filler word removal (um, uh, like...) | ❌ Free |
| 📖 Personal dictionary (auto-correct names) | ❌ Free |
| ⚡ Voice snippets ("trigger greeting" → expands) | ❌ Free |
| 🗣️ Voice commands (period, comma, new line, cancel last 3 words) | ❌ Free |
| 📜 Searchable transcription history | ❌ Free |
| 📋 Auto-copy to clipboard | ❌ Free |
| 🌍 9 languages with → English translation | ✅ API key |
| ✉️📝💭💻 Writing modes (email, notes, chat, code) | ✅ API key |
| 🎯 Make Prompt (speech → structured LLM prompt) | ✅ API key |
| 👔 Professional / ✂️ Concise rewriting | ✅ API key |

## Quick Start

1. Open [https://neelmitra.github.io/voice-claw/](https://neelmitra.github.io/voice-claw/) in **Edge** or **Chrome**
2. Allow microphone access (one-time)
3. Press **Space** to start recording
4. Speak your message
5. Press **Space** to stop — text is auto-copied to clipboard
6. Switch to Clawpilot → **Ctrl+V** → Enter

## AI Features (Optional)

To enable AI-powered features (writing modes, translation, prompt engineering), configure an API key in the ⚙️ **Settings** sidebar tab:

| Provider | API Base | Model |
|---|---|---|
| OpenAI | `https://api.openai.com/v1` | `gpt-4o-mini` |
| Ollama (free, local) | `http://localhost:11434/v1` | `llama3` |
| Azure OpenAI | Your endpoint URL | Your deployment |

Your API key is stored in your browser's localStorage only — never sent anywhere except the API you configure.

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Start/stop recording |
| `Ctrl+C` | Copy transcript |
| `Esc` | Clear transcript |

## Voice Commands

| Say... | Does... |
|---|---|
| "period" / "comma" / "question mark" | Inserts punctuation |
| "new line" / "new paragraph" | Line breaks |
| "cancel last 3 words" | Removes last 3 words |
| "cancel the line" | Removes last sentence |
| "clear all" | Clears everything |
| "trigger [name]" | Expands a saved snippet |

## Browser Support

- ✅ Microsoft Edge
- ✅ Google Chrome
- ❌ Firefox (no Web Speech API)
- ❌ Safari (no Web Speech API)

## License

MIT
