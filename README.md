<div align="center">

<img src="assets/logo.svg" alt="Lambda Bot" width="168" height="168">

# Lambda Bot

### A background assistant for Windows

**It works quietly in the background, notices when you might need a hand, and always asks first.**

<a href="https://github.com/atozuser0224/jevis-installer/releases/latest"><img src="https://img.shields.io/github/v/release/atozuser0224/jevis-installer?style=for-the-badge&label=DOWNLOAD&color=2f86e0" alt="Download the latest release"></a>
<img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0d5fc8?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows 10 and 11">
<img src="https://img.shields.io/github/downloads/atozuser0224/jevis-installer/total?style=for-the-badge&color=6b5cf0" alt="Downloads">

**English** · [한국어](README.ko.md)

<br>

<img src="assets/main.png" alt="The Lambda Bot main window with its conversation panel and the voice orb" width="920">

</div>

<br>

## What is Lambda Bot?

Lambda Bot is an assistant that lives on your PC instead of in a browser tab. A small glowing **orb** sits in your taskbar. Talk to it or type, and it gets things done with the models and tools you choose. Work runs in the background, so what you are doing in front is never interrupted.

It also pays attention, if you let it. When something looks stuck, such as an error dialog that just popped up, the orb peeks out and **asks whether you want help**. You answer with one click. Nothing is done behind your back.

<div align="center">
<img src="assets/orb-offer.png" alt="The orb asks: shall I look into this error? Yes, later or no" width="560">
<br><sub>The orb offers help. Yes runs it, Later asks again in half an hour, No is remembered for a day.</sub>
</div>

## Highlights

|   |   |
|---|---|
| **A voice orb, not a chat tab** | Speak or type. The orb follows the conversation, listens, thinks and answers right where you are working. |
| **Asks before it acts** | Help is offered as a question. Actions that change something ask for your approval first, unless you pre-authorized them, and an approval covers that one action only. |
| **Works in the background** | Apps are driven in hidden windows, so nothing jumps to the front and your typing is never stolen. |
| **Bring your own models** | OpenAI, Anthropic, Gemini, OpenRouter, DeepSeek, Groq, xAI, Mistral and more, or the CLIs you already use (Codex, Claude Code, OpenCode). Keys stay in Windows' protected storage. |
| **Skills** | Built-in skills for research, writing documents, checking and fixing projects, notes and Discord drafts. Add more from the community registry. |
| **Your phone as a remote** | Scan a QR code on the same Wi-Fi to talk to your PC's assistant from your phone. |
| **Yours to arrange** | Drag the conversation anywhere, resize it, or shrink it away until only the orb is left. |

<div align="center">
<img src="assets/orb-holds-chat.png" alt="The orb holding the conversation panel with both hands while it is dragged" width="760">
<br><sub>Move or resize the conversation and the orb takes hold of it.</sub>
</div>

## Private by design

Lambda Bot can learn what you are working on so its offers are timely, but only if you say yes, and only what is needed.

<div align="center">
<img src="assets/consent.png" alt="The consent screen listing what is and is not recorded" width="760">
</div>

- **Opt-in.** Nothing is recorded until you agree in Settings, and you can pause or erase everything at any time.
- **Just app names and time.** It records which app was in front and for how long. It does **not** record your screen, window contents, keystrokes or what you say.
- **Skips sensitive places.** Titles of messaging and mail windows are never kept, and password managers, private windows and Lambda Bot itself are left out.
- **Stays on your PC.** The record is encrypted with Windows and deleted after 90 days.
- **Quiet when it should be.** No offers while you are in a full-screen app, presenting or away, and the orb's bubbles are hidden from screen capture.

## Install

1. Download **`JevisSetup.exe`** from the [latest release](https://github.com/atozuser0224/jevis-installer/releases/latest) and run it.
2. Pick what to install. The installer downloads and sets up what is missing:
   - Lambda Bot (required)
   - .NET 8 Desktop Runtime (only if you do not have it)
   - Python 3.11 with the voice and AI libraries (required, about 3 GB)
   - A desktop shortcut
3. Start Lambda Bot and follow the first-run screen. Voice models are downloaded there, and you connect a model provider or a CLI you already use.

**Requirements:** Windows 10 or 11.

> [!NOTE]
> The installer is not code-signed yet, so Windows SmartScreen may warn you. Choose **More info**, then **Run anyway**.

Lambda Bot was previously called Jevis, which is why the installer file and install folder still carry that name.

## Updating

Lambda Bot checks this page for new releases and tells you inside the app. **Update** downloads the latest version into the same folder.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/atozuser0224/jevis-installer/issues).

<div align="center">
<br>
<sub>Lambda Bot · a background assistant for Windows</sub>
</div>
