# Dragon Mo 🐉

Pure mathematical formula animation. No images, no sprites, no libraries — only `sin` and `cos`.

## 14 modes

| Mode | Formula |
|------|---------|
| 🐉 **Dragon** | `k=9·cos(x/8)`, `d=(k²+e²)/99+sin(t)/6+.5` — swirling dragon point field |
| 🐟 **Fish** | `wiggle=sin(7u−5t)·46u²` — tail swings, tapered body |
| 🌸 **Flower** | Rhodonea rose `r=(cos(3θ+t/2.5)·.5+.5)·230·(1+.12·sin(1.5t))` — breathing petals |
| 🔤 **Letters** | 5×5 vector font bitmasks on a sine sea |
| 🦋 **Butterfly** | Flapping wings `flap=sin(3t)·.4+.6` |
| 💗 **Heart** | `x=16·sin³θ`, `y=13cosθ−5cos2θ−2cos3θ−cos4θ` — beating |
| 🌀 **Spiral** | `θ=i/N·12π+t`, `r=θ·8` |
| 🌊 **Wave** | Interfering sine field `y=sin(c·.15+3t)·40+cos(r·.2+2t)·30` |
| ⭐ **Star** | 5-point star, inner radius morphs with `sin(.8t)` |
| 🌌 **Galaxy** | 3 rotating spiral arms |
| 🪢 **Knot** | Torus knot p=2, q=3 |
| 🪶 **Feather** | Shaft sway + barbs `sin(uπ)·80` |
| 🐚 **Shell** | Archimedean spiral `r=12θ` with chamber ripple |
| 🐦 **Bird** | Flapping wings `flap=sin(4t)·60` |
| 🔮 **Formula A** | `k=(4+sin(2y−t)·3)·cos(x/29)`, `q=3sin(2k)+.3/k+…` |
| 🌪️ **Formula B** | `k=(y<7?8+sin(y^9)·6:4+cos(y))·cos(i+t/2)` |

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
