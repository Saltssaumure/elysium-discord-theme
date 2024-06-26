[screenshot]:       https://saltssaumure.github.io/elysium-discord-theme/preview/preview.avif "Screenshot of Discord Elysium applied to Discord"

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length
[css-percentage]:   https://developer.mozilla.org/en-US/docs/Web/CSS/percentage
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://vencord.dev/

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-css-dl]:    https://img.shields.io/github/downloads/Saltssaumure/elysium-discord-theme/Elysium.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/elysium-discord-theme/net.saltssaumure.Elysium.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/Saltssaumure/elysium-discord-theme?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/Saltssaumure/elysium-discord-theme
[issues]:           https://github.com/Saltssaumure/elysium-discord-theme/issues
[license]:          https://github.com/Saltssaumure/elysium-discord-theme/blob/main/LICENSE
[.theme.css]:       https://github.com/Saltssaumure/elysium-discord-theme/blob/main/Elysium.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Elysium "Replugged store page"
[release-css-gh]:   https://github.com/Saltssaumure/elysium-discord-theme/releases/latest/download/Elysium.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/Saltssaumure/elysium-discord-theme/releases/latest/download/net.saltssaumure.Elysium.asar "Get latest release"

# Discord Elysium
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![CSS GitHub downloads][shield-css-dl]][release-css-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***INTERFACING [Challenging: Success] - This tape contains a Disco Elysium styled Discord theme.***

![Screenshot of Discord Elysium applied to Discord][screenshot]

## Installation

### [BetterDiscord][BetterDiscord]
<details>
    <summary>Click to expand</summary>

1. Download `Elysium.theme.css`:
    <!-- - [BetterDiscord store][release-bd] -->
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details>
    <summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Elysium.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details>
    <summary>Click to expand</summary>

#### Local
1. Download `Elysium.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltssaumure.github.io/elysium-discord-theme/Elysium.theme.css`
</details>

## Customisation

| Variable name                  | Description          | Valid values                              | Default value                                                                   |
| ------------------------------ | -------------------- | ----------------------------------------- | ------------------------------------------------------------------------------- |
| `--disco-portrait`             | User portrait image  | Image link encased in `url()`.            | `url("https://saltssaumure.github.io/elysium-discord-theme/img/portrait.avif")` |
| `--disco-background`           | Background image     | Image link encased in `url()`.            | `url("https://saltssaumure.github.io/elysium-discord-theme/img/revachol.avif")` |
| `--disco-channellist-width`    | Channel list width   | Any [length][css-length].                 | `360px`                                                                         |
| `--disco-memberslist-width`    | Members list width   | Any [length][css-length].                 | `240px`                                                                         |
| `--disco-accent-color`         | Accent colour        | Space-separated [`RGB`][css-color] value. | `0 0 0`                                                                         |
| `--disco-accent-opacity-heavy` | Heavy accent opacity | Any [percentage][css-percentage].         | `80%`                                                                           |
| `--disco-accent-opacity-light` | Light accent opacity | Any [percentage][css-percentage].         | `60%`                                                                           |

### BetterDiscord
<details>
    <summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details>
    <summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-24 of [`Elysium.theme.css`][.theme.css].
3. Edit the variable values and save.
</details>

### Vencord
<details>
    <summary>Click to expand</summary>

#### Local
2. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
3. Open `Elysium.theme.css` with your favourite text editor.
4. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-24 of [`Elysium.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
Copyright (c) 2024 Saltssaumure

This theme is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This theme is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Affero General Public License][license] for more details.

## Credits
### Fonts
[sinanova]:   https://www.fontsquirrel.com/fonts/sina-nova

- [Sina Nova][sinanova] by [Hoftype](https://www.hoftype.com) (Dieter Hofrichter) - Fontspring Webfont End User License Agreement 1.7.0

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].