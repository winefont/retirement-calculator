# 退休資產計算器

Retirement Wealth Projection — an interactive calculator that models long-term asset accumulation from five inputs and highlights key milestones.

## Features

- **Five sliders**: current age, existing assets, monthly investment, annual return rate, retirement age
- **Live SVG chart**: area + curve showing total asset growth vs. principal-only contributions
- **Milestone markers**: when assets cross 1,000萬 / 3,000萬 / 5,000萬 / 1億
- **Age checkpoints**: projected asset value at age 40 / 50 / 60 / 70
- **Retirement marker**: vertical line at target retirement age with the projected amount
- **Tweaks panel** (press `t`): accent color, chart style (area/line), principal line, linear/log Y-axis

## Assumptions

- The annual return input is treated as an effective annual rate and converted to an equivalent monthly rate
- Monthly contributions are added at the end of each month
- Inflation and taxes are not modeled
- For planning reference only

## Stack

Pure HTML + CSS + vanilla JS. No build step. No dependencies except Google Fonts (Fraunces, IBM Plex Mono, Inter).

## Local preview

```
python3 -m http.server 8000
# open http://localhost:8000
```
