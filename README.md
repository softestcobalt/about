cobalt — single-screen personal card

[available here](https://hardestbed.dev/)

english | [русский](./README_ru.md)

```
┌─────────────────────────────────────────────────────────────┐
│                      hey, i'm bohdan                        │
│  i'm 17 and learning to build clean, thoughtful web pages…  │
│  learn more about me   ···································  │
│  get in touch          ···································  │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│ about                                                       │
│  you can reach me on contacts page…                         │
│  back home           ·····································  │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│ contacts                                                    │
│  email  - hi@hardestbed.dev                                 │
│  github - github.com/softestcobalt                          │
│  telegram - t.me/hardestbed                                 │
│  back home           ·····································  │
└─────────────────────────────────────────────────────────────┘
```

# quick start

1. open [link](https://hardestbed.dev/).
2. switch sections using the dashed links; each view animates into place without scrolling or changing the URL.
3. the layout stays within a single screen, optimized for both desktop and mobile.
4. use the toggles in the top-right corner to switch theme (dark / light) and language (en / ru); your choices are saved locally.

# tech notes

- pure `HTML` + `CSS`, no frameworks.
- dark palette with accent `#161413`, monospaced typography, dashed underlines for interactions.
- single-screen view switching handled in JavaScript keeps the URL clean and the page static.
- theme and language preferences persist via `localStorage`, respecting system defaults on first visit.
- bilingual copy (EN / RU) powered by a lightweight client-side dictionary.
