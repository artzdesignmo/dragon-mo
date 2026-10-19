# Dragon Mo 🐉

Pure mathematical formula animation. No images, no sprites, no libraries — only `sin` and `cos`. Each animation core is small enough to fit on a napkin.

## Four modes

| Mode | Formula |
|------|---------|
| 🐉 **Dragon** | Adapted parametric point field: `k=9·cos(x/8)`, `d=(k²+e²)/99+sin(t)/6+.5`, `q=99−e·sin(atan2(k,e)·7)/d+k·(3+cos(d²−t)·2)` → swirling dragon |
| 🐟 **Fish** | Parametric body: `wiggle=sin(7u−5t)·46u²` (tail swings), `width=58·sin(πu)·(1−.55u)` (tapered body) |
| 🌸 **Flower** | Rhodonea rose: `r=(cos(3θ+t/2.5)·.5+.5)·230·(1+.12·sin(1.5t))` — breathing petals |
| 🔤 **Letters** | 5×5 vector font as bitmasks, particles floating on a sine sea: `x+sin(2t)·10`, `y+cos(1.6t)·10` |

## Controls

- **Mode buttons** — switch between dragon / fish / flower / letters
- **Word input** (letters mode) — type any word up to 8 characters
- **Speed / Trail sliders** — animation speed and motion-blur persistence
- **Drag on canvas** — stir time directly
- **EN / 中** — language toggle, **◐** — white / silver / black theme

## Tech

Single `index.html`, vanilla JS + Canvas 2D, zero dependencies. Dela Gothic One display type, OpenX house style.

## Demo

https://artzdesignmo.github.io/dragon-mo/

## License

MIT
