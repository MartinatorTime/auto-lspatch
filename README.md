### LSPatch Status

The official GitHub repository for LSPatch was archived on December 13, 2023, and the project is no longer under active development. This means:

*   There will be no further updates to support new Android or Telegram versions.
*   Compatibility with modern Telegram builds is not guaranteed, and users have reported that patched applications may crash or fail to work correctly on updated systems.

# Auto-LSPatch

Auto-LSPatch is a tool designed to automate the process of patching Android applications with modules using the LSpatcher jar. It is configured to check for new releases in Xposed modules and Telegram client repositories every day at midnight. When it detects new releases, it automatically runs the patcher with the modules specified in the `build-telegram.yml` file.

## Features

- **Customizable**: Easy to fork and adapt for your specific needs, apps, and modules.
- **Flexible Source**: Modules and apps for the patcher can be sourced from the web or can be included in the repo as an APK.
- **Latest Patches**: Access the latest patched apps from the [releases](https://github.com/MartinatorTime/auto-lspatch/releases/tag/LSpatched) page.

## Acknowledgements

We would like to thank the following:

- The Old Patcher: [LSPatch](https://github.com/LSPosed/LSPatch)
- The New Patcher: [LSPatch](https://github.com/JingMatrix/LSPatch)
- The Xposed modules:
  - [TeleVip](https://github.com/Xposed-Modules-Repo/com.my.televip)
  - [SpeedHook](https://github.com/araafroyall/Telegram-Speed-Hook)
  - [Killergram](https://github.com/JeelsBoobz/Killergram)
- The Telegram clients:
  - [Telegram](https://telegram.org/android)
  - [Forkgram](https://github.com/forkgram/TelegramAndroid)
  - [Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)

- Code update:
  - [dsys1100](https://github.com/dsys1100/tg-autolspatch)