# Borozdov Ledger

A theme from the Borozdov collection. Two faces — light **Frost**, a cool-white ledger, and
dark **Navy**, the same ledger after hours. Whisper-weight type, crisp hairline rules, 4px
corners and one indigo ink for action.

![Borozdov Ledger in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/ledger/main/screenshots/light.png)

![Borozdov Ledger in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/ledger/main/screenshots/dark.png)

## Principles

- **One ink.** Indigo marks links, tags, checked tasks, enabled toggles and the main
  button; everything else is a cool neutral.
- **Headlines whisper.** Inter at weight 300 for prose and headlines, 400 for the
  interface, 500 for bold — authority from restraint, not volume.
- **Tint, not shadow.** Depth comes from steps of white, mist and frost; no element
  casts a shadow.
- **Ledger corners.** 4px on every button, field, card and tag — never a pill.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Tabular figures everywhere, so amounts and IDs line up
- Callouts as tinted entries with a hairline frame and a thin rule in the type's color:
  indigo, green, amber or ruby
- Code on a quiet panel with green strings and violet keywords
- Ledger tables: a hairline frame, an uppercase header band and tabular numbers
- Tags as periwinkle washes with an indigo label
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colors meet WCAG contrast on both faces
- The phone layout keeps the same colors and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Ledger** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/ledger/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Ledger/`, then choose Borozdov Ledger under
Settings → Appearance → Themes.

## Font

Inter (© The Inter Project Authors) is embedded in `theme.css` as base64 WOFF2 under the
SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). Weights 300–500, Latin
and Cyrillic.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Иней» — прохладно-белый
гроссбух, и тёмный «Синий» — тот же гроссбух после закрытия. Тонкий шрифт Inter веса 300,
чёткие линейки, углы 4px, никаких теней и одни индиговые чернила для действий.
В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Ledger в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
