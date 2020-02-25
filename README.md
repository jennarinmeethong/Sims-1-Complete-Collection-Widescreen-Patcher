# The Sims 1: Complete Collection Widescreen Patcher

Patches `The Sims 1: Complete Collection` to a custom resolution. You must be using the NoCD executable with MD5 hash 42F9A3E11BD1A03515C77777CB97B5BC. Running this application will:

1. Create a backup of your existing Sims.exe as Sims Backup.exe
2. Edit Sims.exe to your custom resolution
3. Optionally downloads dgVoodoo2
4. Resize UI graphics to your custom resolution

![Main Application](https://i.imgur.com/GdEFFTk.png)

## Requirements

* .NET 4.5

## Usage

1. Download the latest [release](https://github.com/FaithBeam/Sims-1-Complete-Collection-Widescreen-Patcher/releases)
2. Run Sims1WidescreenPatcher.exe as administrator
3. Select your Sims.exe
4. Enter your preferred resolution
5. Click Patch

## Selecting Valid Resolutions

While this application does allow you to input any resolution you want, your game most likely will crash on startup if you don't enter a valid resolution your monitor supports. You can find out which resolutions your monitor supports by:

1. Right Clicking your desktop
2. Select Display Settings
3. Select Advanced display settings
4. Select Display adapter properties for Display 1
5. Select List All Modes

These are resolutions that will potentially work for The Sims 1. There are resolutions that don't work without dgVoodoo2, however. These resolutions are > 1080p.

I'm sure you can increase the range of valid resolutions by creating custom resolutions using [Custom Resolution Utility](https://www.monitortests.com/forum/Thread-Custom-Resolution-Utility-CRU)

## Uninstall

If you want to go back to your default Sims executable and optionally no dgVoodoo2 files, select the uninstall button.

## Screenshots

[Wiki](https://github.com/FaithBeam/Sims-1-Complete-Collection-Widescreen-Patcher/wiki)

## Known Issues

### Missing Next / Back Arrows

In certain resolutions, the Next / Back Arrows are missing in buy mode making purchasing every product impossible. The known resolutions that have this issue are:

* 1600x900
* 1600x1200

There is no solution for this bug but a workaround is to choose a different resolution.

## Credits

[WSGF](http://www.wsgf.org/dr/sims)

[dgVoodoo2](http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2.html)

[Magick.NET](https://github.com/dlemstra/Magick.NET)
