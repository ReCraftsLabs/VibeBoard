# VibeBoard

An Android keyboard in the Material 3 Expressive style, built with Kotlin and Jetpack Compose.
Highly customizable and extensible with plugins and JavaScript mods.

<!-- Add 2–3 screenshots here, for example:
<p>
  <img src="screenshots/keyboard.png" width="250">
  <img src="screenshots/settings.png" width="250">
</p>
-->

## Download

Get the latest APK from [Releases](https://github.com/ReCraftsLabs/VibeBoard/releases/latest).

Follow VibeBoard: [Telegram](https://t.me/MrRetiZiXD) · [VK](https://vk.ru/mrretizix)

Requires Android 8.0 or newer.

## Features

- **Typing:** word suggestions, autocorrect, glide (swipe) typing
- **Languages:** 90+ layouts; Chinese (Pinyin, simplified and traditional) and Japanese (Romaji → Kana) input; Indic scripts (InScript)
- **Emoji:** all Unicode 16 emoji, search in English and Russian, skin tones, built-in styles (Twemoji, Noto, Blob, OpenMoji)
- **Designs:** Material You Expressive, Material 3 (Google guidelines), Liquid Glass, Classic, Neon, Neumorphism — one tap
- **App language:** Russian or English
- **Panels:** emoji, GIFs, clipboard, translator, voice input
- **Look:** Material You colors, seasonal themes, skins, adjustable Nunito font weight, custom fonts (.ttf/.otf), a photo from your gallery behind the keys
- **Layout:** key height and corner radius, spacing, keyboard width, one-handed mode
- **Feedback:** adjustable vibration and sound
- **Privacy:** incognito mode; suggestions and dictionary learning are turned off in password fields
- **Plugins and mods:** custom buttons, shortcuts, layouts, symbols and JavaScript scripts that can draw and animate over the keyboard, press keys and change layouts on the fly; kaomoji categories, recent symbols and favorites

## Installation

1. Download and install the APK from [Releases](https://github.com/ReCraftsLabs/VibeBoard/releases/latest).
2. Open the app and enable the keyboard in system settings.
3. Select VibeBoard as your input method.

## Permissions

| Permission | Why |
|---|---|
| Internet | GIFs (Giphy), translator, downloading suggestion dictionaries, mods with the `network` permission |
| Microphone | Voice input |
| Vibration | Haptic feedback on key press |

Your typed text is not sent anywhere unless you use the translator yourself or install a mod
that has both network and text-reading permissions.

## Plugins and mods

Plugins are imported in **Settings → Plugins and mods**. The format and JavaScript API are described
in [PLUGINS.md](PLUGINS.md) (in Russian); examples live in [`app/src/main/assets/plugins`](app/src/main/assets/plugins).

## License

[MIT](LICENSE)
