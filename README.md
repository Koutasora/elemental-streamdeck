# Elemental – Stream Deck plugins

Three free Stream Deck plugins for **Windows and macOS**. Each one is developed in its own repository; this page collects them, and the [latest release](../../releases/latest) has all three packages in one place.

| Plugin | What it does | Windows | macOS |
| --- | --- | --- | --- |
| [Elemental Temps](https://github.com/Koutasora/Elemental-Temps) | CPU, GPU and disk temperatures, RAM usage and any sensor on a key, as a gauge, bar, history graph or big number | HWiNFO | macmon (Apple Silicon); no disk temperature |
| [Elemental Infobar](https://github.com/Koutasora/Elemental-infobar) | Clock, time zones, readings and progress on the Stream Deck Neo infobar, with colored side lights | HWiNFO for CPU / GPU | macmon for CPU / GPU |
| [Elemental USB](https://github.com/Koutasora/elemental-usb) | One key to switch between USB drives and safely remove them | Yes | Yes (USB drives and SD cards) |

![Elemental Temps](https://raw.githubusercontent.com/Koutasora/Elemental-Temps/main/docs/showcase.png)
![Elemental Infobar](https://raw.githubusercontent.com/Koutasora/Elemental-infobar/main/docs/showcase.png)
![Elemental USB](https://raw.githubusercontent.com/Koutasora/elemental-usb/main/docs/showcase.png)

## Install

1. Download the `.streamDeckPlugin` files from the [latest release](../../releases/latest) (or from each plugin's own releases).
2. Double-click a file – the Stream Deck app installs it. The same file works on Windows and macOS.

## Requirements

- Stream Deck software **7.1** or newer (**7.6** for the Infobar, which needs a Stream Deck Neo)
- Windows 10/11 or macOS 12+
- Windows: [HWiNFO](https://www.hwinfo.com/) with *Shared Memory Support* for CPU / GPU / disk readings
- macOS: [macmon](https://github.com/vladkens/macmon) (`brew install macmon`) for CPU / GPU readings

Setup details, options and troubleshooting are in each plugin's README. Bugs and ideas: please open an issue in the plugin's own repository.

## License

MIT – see [LICENSE](LICENSE) and each plugin's repository.
