<div align="center">

# One · Prism

**A clean page holds the morning; a quiet charcoal page keeps the evening. Between them, small colors make room for thought.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-61afef?labelColor=282c34)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-61afef?labelColor=282c34)
[![License: MIT](https://img.shields.io/badge/license-MIT-61afef?labelColor=282c34)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-one-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-one-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-one-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

One Light and One Dark come together in a single Tine theme, pairing quiet neutral surfaces with familiar blue and violet accents.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![One · Prism in Tine dark mode](docs/one-dark.png)

### Light mode

![One · Prism in Tine light mode](docs/one-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-one-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#fafafa` | `#282c34` |
| Sidebar | `#f0f0f0` | `#21252b` |
| Body | `#383a42` | `#abb2bf` |
| Heading | `#383a42` | `#abb2bf` |
| Accent | `#4078f2` | `#61afef` |
| Links | `#0066cc` | `#61afef` |
| Tags | `#a626a4` | `#c678dd` |
| Mark background | `#f4e7c5` | `#514b3b` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Atom One Light / One Dark](https://github.com/atom/one-dark-syntax) at `9c96f4454362267ac45322063e193ccf9d2debb1`, under MIT; see [LICENSE](LICENSE). Based on the official Atom One Light and One Dark syntax theme repositories at fixed revisions d84579027410c576086dfca14d934c4bd74b0438 and 9c96f4454362267ac45322063e193ccf9d2debb1. Color roles are independently mapped to the Tine theme API.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-one-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.
