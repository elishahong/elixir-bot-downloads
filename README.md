# EliXir Bot downloads

AI agents that work on a computer of their own, inside an app on your Mac or PC.

Once it is installed, the app **updates itself**: when a newer version is published here, the app fetches it, tells you, and puts it in place when your agents are not busy. Nothing to install again.

## Which file do I need?

### EliXir Bot (uses an AI service you have a key for: OpenAI or Alibaba Cloud)

| Your computer | Download |
|---|---|
| Mac bought in late 2020 or after (Apple chip: M1, M2, M3, M4…) | [EliXir-Bot-0.1.0-arm64.dmg](https://github.com/elishahong/elixir-bot-downloads/releases/latest/download/EliXir-Bot-0.1.0-arm64.dmg) |
| Older Mac with an Intel chip | [EliXir-Bot-0.1.0-x64.dmg](https://github.com/elishahong/elixir-bot-downloads/releases/latest/download/EliXir-Bot-0.1.0-x64.dmg) |
| Windows PC | [EliXir-Bot-Setup-0.1.0.exe](https://github.com/elishahong/elixir-bot-downloads/releases/latest/download/EliXir-Bot-Setup-0.1.0.exe) |

### EliXir SHllm (the AI model is built in; nothing leaves your computer)

| Your computer | Download |
|---|---|
| Mac with an Apple chip | [EliXir-SHllm-0.1.0-arm64.dmg](https://github.com/elishahong/elixir-bot-downloads/releases/latest/download/EliXir-SHllm-0.1.0-arm64.dmg) |
| Windows PC | [EliXir-SHllm-Setup-0.1.0.exe](https://github.com/elishahong/elixir-bot-downloads/releases/latest/download/EliXir-SHllm-Setup-0.1.0.exe) |

**Not sure which Mac you have?** Click the Apple logo at the top left, then "About This Mac". "Chip: Apple M…" means Apple chip. "Processor: … Intel …" means Intel.

## Installing on a Mac

1. Double-click the `.dmg` file. A window opens.
2. Drag **EliXir Bot** onto the Applications folder in that window.
3. Open EliXir Bot from Applications.
4. The first time, the Mac says it could not check the app. That is expected: the app is not registered with Apple yet. Press **Done**, then open **System Settings → Privacy & Security**, scroll down to the line about EliXir Bot, and press **Open Anyway**. (On older Macs: right-click the app, choose Open, then Open.)

You only do step 4 once.

## Installing on a Windows PC

1. Double-click the `.exe` file.
2. On the blue "Windows protected your PC" screen, click **More info**, then **Run anyway**.

Nothing else is needed: **no Docker**. Your agents work on the PC itself, each with its own hidden browser.

## First start

The app asks for one API key, which is what lets your agents think: an **OpenAI** key or an **Alibaba Cloud** (Model Studio) key. Paste it and press Start.

## Updating

Installed apps update themselves. To install a newer file by hand, close EliXir Bot first, then install it the same way. Your agents and their sign-ins are kept.

## Older versions

Every version ever published stays on the [Releases page](https://github.com/elishahong/elixir-bot-downloads/releases).
