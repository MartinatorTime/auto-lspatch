# Auto-LSPatch

Auto-LSPatch is a tool designed to automate the process of patching Android applications with modules using the LSpatcher jar. It is configured to check for new releases in Xposed modules and Telegram client repositories every day at midnight. When it detects new releases, it automatically runs the patcher with the modules specified in the `build-telegram.yml` file.

## Features

- **Customizable**: Easy to fork and adapt for your specific needs, apps, and modules.
- **Flexible Source**: Modules and apps for the patcher can be sourced from the web or can be included in the repo as an APK.
- **Latest Patches**: Access the latest patched apps from the [releases](https://github.com/MartinatorTime/auto-lspatch/releases/tag/LSpatched) page.

## Acknowledgements

We would like to thank the following:

- The Patcher: [LSPatch](https://github.com/LSPosed/LSPatch)
- The Xposed modules:
  - [Telegram Helper Re: Fantasy City](https://t.me/ReFantasyCity) (Not Open-Source)
  - [Tmoe](https://github.com/cinit/TMoe)
  - [Telespeed](https://github.com/Xposed-Modules-Repo/io.github.tehcneko.telespeed)
  - [Killergram](https://github.com/shatyuka/Killergram)
  - [ReTelegram](https://github.com/Sakion-Team/Re-Telegram)
  - [TGramHooks](https://4pda.to/forum/index.php?showtopic=603033&st=1060#entry124676967) (Not Open-Source)
- The Telegram clients:
  - [Telegram](https://telegram.org/android)
  - [Forkgram](https://github.com/forkgram/TelegramAndroid)
  - [Nagram](https://github.com/NextAlone/Nagram)
  - [Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)
  - [Plus-Messanger](https://plusmessenger.org/)