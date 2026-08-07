# vedic-astrology

Personal study notes on Jyotisha (Vedic astrology), leaning toward the
Kerala school where source material allows it. Built the same way as
[system-notes](https://github.com/karthik-dev-82/system-notes): real,
checkable mechanics first, wrapped in a small interactive "Play With
It" widget wherever a static explanation would leave the actual
structure invisible.

📖 **Full rendered docs: https://karthik-dev-82.github.io/vedic-astrology/**

## Quick Navigation

| Page | What it covers | Key terms |
| --- | --- | --- |
| 🎮 **[Rashis, Nakshatras & Padas (Interactive)](docs/source/rashi_nakshatra_interactive.rst)** | Interactive rashi/nakshatra/pada wheel -- drag to any longitude and see its rashi, nakshatra, pada, and both lords live | rashi, nakshatra, pada, rashi lord, nakshatra lord |

## Repository Layout

```text
vedic-astrology/
├── README.md
└── docs/
    ├── requirements.txt
    └── source/
        ├── conf.py
        ├── index.rst
        ├── rashi_nakshatra_interactive.rst
        └── _static/
            ├── custom.css
            └── rashi_nakshatra_widget.html
```

## Scope & Sources

Foundational material (rashi/nakshatra order, the fixed nakshatra-lord
cycle, rashi rulerships) follows the standard Parashari framework
shared across Jyotisha schools. Anything more specific -- dashas,
prashna technique, yogas -- is meant to be grounded in specific
reference texts (Kerala-school works like Prashna Marga among them)
as those pages get built, not general recall alone. Each page says
plainly what it's sourced from.
