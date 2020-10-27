# Among Us for macOS
Play [Among Us](http://www.innersloth.com/gameAmongUs.php) on your Mac. Download and open the [Among Us Installer](https://github.com/CartoonChess/among-us-mac/raw/transfer/Among%20Us%20Installer.zip) to get started.

## Instructions
1. Make sure you already have a copy of Among Us for Windows, available at [itch.io](https://innersloth.itch.io/among-us) and [Steam](https://store.steampowered.com/app/945360/Among_Us/). If you haven't already purchased, the itch.io version is recommended for this installer.
2. Download the [support files](https://github.com/CartoonChess/among-us-mac/releases/download/v1.0.0-beta.1/AmongUsMac.zip).
3. Download and open the [Among Us Installer](https://github.com/CartoonChess/among-us-mac/raw/transfer/Among%20Us%20Installer.zip).
4. Follow the installer's instructions to continue.

## Updating
The installer can be used to update the Mac version when the Windows version is updated. If the Mac version is already installed, open the installer again and provide the updated Windows game files.

## Installation details
The installer requires two things to work: the game app or wrapper, called **AmongUsMac**`.zip` or **Among Us**`.app`, and the game files, which will typically be a file called **among-us-windows**`.zip` or a folder of the same name or **Among Us** (with or without a space). The installer will look for these files in the following order:
1. Drag-and-dropped onto the installer icon
2. In the same folder as the installer
3. Steam game files on Boot Camp drive (`/Volumes/BOOTCAMP/Program Files (x86)/Steam/steamapps/common/Among Us/`)
4. Provided via file selection window.

The installer can fail to detect any of the above for various reasons, and each is prone to its own set of errors as well. If you face difficulty, try one of the other methods instead.

Note as well that the installer will make some assumptions, such as that the game files are being updated if `Among Us`.app already exists at `/Applications`.

## Troubleshooting
* There is a [known bug](https://forum.winehq.org/viewtopic.php?f=9&t=34348) which partially breaks keyboard support when switching applications. Return to the game by *clicking*, not cmd-tabbing, on the *game screen*, not the icon.
* Despite some best efforts, macOS security still thwarts this installer at times. If you face errors, try moving this installer to a different folder than the AmongUsMac zip and the game data, and try again.
* If you'd rather not pay to play on your Mac, you can use an Android emulator instead.

## Attributions
* Game by [InnerSloth](http://www.innersloth.com)
* [Wine](https://www.winehq.org) —> [Wineskin](https://sourceforge.net/p/wineskin/code/ci/master/tree/) —> [Gcenx](https://github.com/Gcenx/WineskinServer)

## Attributions of the future
Can you help make this project better? Please do!

## More Among Us!!
What about a ~~terrible Among Us bot~~ [Discord verified-bot bot](https://github.com/CartoonChess/are-we-ver-yet) that automatically sends you a message when a really good Among Us bot can be invited to your server?
