# Nova · Calc

A premium, single-file web calculator with a glassmorphism UI and an animated aura background.

![Nova Calc](https://img.shields.io/badge/status-live-brightgreen) ![HTML](https://img.shields.io/badge/build-single--file%20HTML-6c5ce7)

## ✨ Features

- **Standard operations** — addition, subtraction, multiplication, division, percent, and sign toggle
- **Live preview** — see the result of the pending calculation before pressing `=`
- **Running history** — displays the previous value and operator above the current entry
- **Full keyboard support** — numbers, `+ - * /`, `Enter`/`=`, `Backspace`, `Esc`, and `%` all work
- **Micro-interactions** — button ripple effect, active-operator highlighting, and a subtle "pop" animation on value changes
- **Polished visuals** — frosted-glass panel, rotating conic-gradient aura, and custom typography (Space Grotesk + Inter)
- **Accessible & responsive** — respects `prefers-reduced-motion`, visible focus states, no external JS dependencies

## 🚀 Getting Started

No build step or dependencies required — it's a single HTML file.

```bash
git clone https://github.com/your-username/nova-calc.git
cd nova-calc
open calculator.html   # or just double-click the file
```

Alternatively, serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/calculator.html
```

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `0`–`9` | Enter digit |
| `.` | Decimal point |
| `+` `-` `*` `/` | Operators |
| `Enter` / `=` | Evaluate |
| `Backspace` | Delete last digit |
| `Esc` | Clear all |
| `%` | Percent |

## 🛠️ Tech Stack

- Vanilla HTML, CSS, and JavaScript — no frameworks or build tools
- Google Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) & [Inter](https://fonts.google.com/specimen/Inter)

## 📄 License

[MIT](LICENSE) — feel free to use and modify.
