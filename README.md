# FOC Complete Course — Interactive Dashboard

An interactive, browser-based course covering **Field-Oriented Control (FOC)** from first principles through EV traction drive implementation. All content is packed into a single `index.html` — no server, no build step, no dependencies.

> Course material developed with thanks to [Dr. B. Dastagiri Reddy](https://eee.nitk.ac.in/faculty/b-dastagiri-reddy), Department of Electrical & Electronics Engineering, NITK Surathkal.

---

## What's Inside

| Stat | Value |
|------|-------|
| Slides | 77 |
| Modules | 10 |
| Animated slides | 9 |
| Static diagrams | 4 |
| Estimated content | ~14 h |

### Modules

| # | Module | Topics |
|---|--------|--------|
| M0 | Magnetics Foundations | B/H/μ, Faraday, Ampere, inductance, torque production |
| M1 | Three-Phase Systems | Rotating field, synchronous speed, motor type overview |
| M2 | Motor Construction & Saliency | SPMSM, IPMSM, PM-SyRM, IM, Ld vs Lq, back-EMF |
| M3 | The dq Reference Frame | Clarke, Park, inverse transforms, three-frame master animation |
| M4 | PMSM dq Model | Voltage equations, cross-coupling, torque (PM + reluctance) |
| M5 | FOC Control Structure | Current PI, speed PI, decoupling feedforward, anti-windup |
| M6 | Optimal Operating Points | MTPA, field weakening, MTPV, id-iq plane operating limits |
| M7 | Sensorless & Startup | SMO, PLL, HFI, IPD, I-f ramp startup |
| M8 | Induction Motor FOC | IFOC, DFOC, slip estimation, Rr detuning |
| M9 | EV Traction Drive | Full drive implementation, thermal management, real-world case studies |

---

## Features

- **Zero dependencies** — pure HTML + CSS + vanilla JavaScript in one file
- **Animated slides** auto-play on click (purple dot indicates interactive animation)
- **Collapsible sidebar** with slide search
- **Progress bar** tracks position through the course
- **Nomenclature panel** — searchable glossary of 50+ FOC terms and acronyms (📖 button, bottom-right)
- **Keyboard navigation** — arrow keys to move between slides, Space to pause/play animations
- **Dark theme** optimised for projection and self-study

---

## Usage

### Local

Open `index.html` directly in any modern browser — no server required.

```
index.html
```

### GitHub Pages

The site is deployed automatically via the included Jekyll CI workflow on every push to `main`.

Live URL: `https://<your-username>.github.io/FOC_Course/`

---

## Repository Structure

```
FOC_Course/
├── index.html              # Entire course application (single file)
├── LICENSE
└── .github/
    └── workflows/
        └── jekyll-docker.yml   # GitHub Pages CI/CD
```

---

## License

See [LICENSE](LICENSE).
