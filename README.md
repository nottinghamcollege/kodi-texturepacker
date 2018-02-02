# Kodi `TexturePacker`

Compiled x86_64 TexturePacker binary for Windows, macOS and Linux to compile assets in skins for faster loading when used on Kodi.

SHA1SUM for each binary are published in each respective OS folder.

#### Windows

Static binary without any DLL files taken from http://mirrors.kodi.tv/build-deps/win32/texturepacker-1.1.1-win32.7z.

#### macOS

Compiled from source on macOS High Sierra (10.13).

#### Linux

Compiled from source on Ubuntu 16.04 (Xenial).

## Usage

```
TexturePacker -dupecheck -input skin.name\media -output skin.name\media\Textures.xbt
```

For skins that use themes you should compile the assets for each theme:

```
TexturePacker -input skin.name\themes\Blue -output skin.name\media\Blue.xbt
```