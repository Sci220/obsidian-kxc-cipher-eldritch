# KXC Cipher Eldritch for Obsidian

A readability-optimized dark theme for [Obsidian](https://obsidian.md). Re-skin of [KXC Cipher](https://github.com/Sci220/obsidian-kxc-cipher) (by Korthcore) using the [Eldritch](https://github.com/eldritch-theme) color palette.

Lovecraftian deep-oceanic tones with WCAG AAA body text and H1-H3 headings.

## Palette

| Colour                     | Hex       | Contrast on `#212337` | Role                                     |
|----------------------------|-----------|-----------------------|------------------------------------------|
| Sunken Depths Grey         | `#212337` | —                     | Primary editor background                |
| Shallow Depths Grey        | `#323449` | —                     | Panels, line highlight, modals           |
| Lighthouse White           | `#ebfafa` | 14.40:1 AAA           | Primary text, bold, italic               |
| Watery Tomb Blue           | `#04d1f9` | 8.45:1 AAA            | Accent, links, H1, checkboxes, caret     |
| Great Old One Green        | `#37f499` | 10.71:1 AAA           | H2, strings, success                     |
| Dreaming Orange            | `#f7c67f` | 9.81:1 AAA            | H3, numbers, warnings, unresolved        |
| Lovecraft Purple           | `#a48cf2` | 5.60:1 AA             | H4, tags, keywords, external links       |
| Pustule Pink               | `#f265b5` | 5.37:1 AA             | H5, functions                            |
| Lifted Old One Purple (H6) | `#7d8dd5` | ~4.9:1 AA             | H6 (AA heading)                          |
| The Old One Purple         | `#7081d0` | 4.22:1 (large AA)     | Muted text, comments, nav, graph default |
| R'lyeh' Red                | `#f16c75` | 5.25:1 AA             | Errors, danger callouts                  |
| Gold of Yuggoth            | `#f1fc79` | 13.92:1 AAA           | Question callouts, highlights            |

## Install

### Manual

1. Download `manifest.json` and `theme.css`.
2. Create a folder called `KXC Cipher Eldritch` inside your vault's `.obsidian/themes/` directory.
3. Copy both files into that folder.
4. Open **Settings → Appearance → Themes** and select **KXC Cipher Eldritch**.

```
YourVault/
  .obsidian/
    themes/
      KXC Cipher Eldritch/
        manifest.json
        theme.css
```

## Features

- Full dark theme using the Eldritch palette
- AAA contrast for body text and H1-H3 headings; AA for H4-H6
- Distinct hue rotation across heading levels (cyan → green → orange → purple → pink → muted purple)
- Code syntax highlighting follows Eldritch's documented semantic roles (string = green, keyword = purple, function = pink, comment = muted purple, number = orange)
- Callouts: info (cyan), tip/success (green), warning (orange), danger (red), question (yellow), example/todo (purple), quote (muted)
- Graph view colors, tag styling, table striping, blockquote and embed styling
- Italic text is **not** tinted — slant alone provides distinction, preserving readability of long italic passages
- Watery Tomb Blue accent for links, checkboxes, caret, active tab

## Compatibility

- Obsidian v1.0.0 and later
- Dark mode only

## Credits

- Theme structure: [Korthcore](https://github.com/Korthcore) — [KXC Cipher](https://github.com/Sci220/obsidian-kxc-cipher) (MIT)
- Color palette: [Eldritch theme project](https://github.com/eldritch-theme) (MIT)

## Licence

[MIT](LICENSE)
