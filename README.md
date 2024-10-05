# macOS Wallpapers
WIP!

An archive of every macOS wallpaper officially released by Apple

This repository aims to preserve every macOS wallpaper released by Apple, all the way from macOS 10.0 up to (currently) macOS 15 Sequoia.
Wallpapers are sorted by os version.

All wallpapers are extracted directly from `/System/Desktop Pictures` and have not been touched in any way.

> Video wallpapers are not currently included. Only static, dynamic and light/dark pictures.

## How to add the wallpapers to system settings
1. In your terminal make a Desktop Pictures folder: `mkdir /Library/Desktop\ Pictures`
2. And a thumbnail folder therein: `mkdir /Library/Desktop\ Pictures/.thumbnails`
> Not `System/Library/Desktop Pictures` or `~/Library/Desktop Pictures`!
3. Navigate to `/Library/Desktop Pictures` by opening Finder and pressing `shift + command + G`
4. Copy your desired wallpapers into the folder, and their thumbnails into the `.thumbnails` folder
> if you don't see the `.thumbnails` folder, press `shift + command + .` to show hidden folders
5. ???
6. Profit
7. Your wallpapers should now appear in system settings alongside the built-in wallpapers
> Restart system settings to see the changes
## How to add the Mojave dynamic wallpaper properly
In a recent update macOS changed how wallpapers are stored / downloaded. According to the `/System/Library/Desktop Pictures/.orderedPictures.plist` file, the Mojave dynamic wallpaper was apparently supposed to be available as a downloadable wallpaper with it's own `.madesktop` file.
We can trick the system into thinking we have it downloaded so it will show up next to catalina in system settings.
1. Copy the `Mojave.madesktop` file from this reposetory into `/Library/Desktop\ Pictures`
2. Copy the `Mojave.heic` file into `~/Library/Application Support/com.apple.mobileAssetDesktop/`
3. Thats it!
> Restart system settings to see the changes

## Legal stuff

All of the wallpapers included are © 2007 - 2023 Apple Inc. and their respective creators/owners. This repository is created merely for archival purposes.

## Credits & honorable mentions

* Apple, Inc: For creating macOS and these wallpapers.
