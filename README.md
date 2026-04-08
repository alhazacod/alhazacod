# Manuel Angel García

---

🔭 Theoretical Cosmology - 🌌 Multi‑Field Dark Energy - 🧩 Quantum Gravity

---


## Who am I 👨‍🔬

Physics undergraduate at **Universidad Nacional de Colombia**. Final semester. Thesis on **multi‑field quintessence**, how non‑geodesic trajectories in curved field spaces let steep potentials drive cosmic acceleration while dodging the de Sitter swampland conjecture.

I build numerical tools to simulate cosmological dynamics, plus the occasional quantum tomography or astronomy pipeline. I read Akrami, Vafa, Maldacena like morning papers. Fine‑tuning is for people who gave up.

## Research & Code I actually ship 🚀

### 🔥 `multifield_cosmology_dynamics`
*Python toolkit to reproduce background dynamics from Akrami et al. (2021)*

Replicates phase‑space trajectories ($\omega_\phi$, $\Omega_\phi$) for power‑law and hyperbolic field‑space metrics, plus the swampland ratio $|\nabla V|/V$.
**Key result from my thesis:**
- Hyperbolic metric $f(r)=e^{\beta r}$ → $\omega_{\text{DE}}$ evolves from $>-1$ at high redshift toward $-1$ today (matches DESI hints).
- Power‑law metric $f(r)=r^p$ works for $p=2$, fails for $p=3$.
- Verified $|\nabla V|/V \gtrsim \mathcal{O}(1)$ everywhere, no swampland violation.

[![Repo](https://img.shields.io/badge/➡️_Code-multifield_cosmology_dynamics-blue)](https://github.com/alhazacod/multifield_cosmology_dynamics)

---

### 📡 `coltess` – TESS FFI Photometry Pipeline
*Light curves from TESS Full Frame Images, your way*

Automated catalog from Gaia DR3, direct FFI downloads from MAST, aperture photometry with background subtraction, parallel processing, Lomb‑Scargle periodograms.
**Why not just use Lightkurve?** Coltess gives you full control – custom apertures, faint targets, anything not in the TIC. When you need raw FFI photometry without black boxes.

[![Repo](https://img.shields.io/badge/➡️_Code-coltess-blue)](https://github.com/alhazacod/coltess) [![PyPI](https://img.shields.io/badge/PyPI-not_yet-yellow)](https://pypi.org/)

---

### 🧪 `qtom` – Neural Network Quantum State Tomography
*Deep learning for density matrix reconstruction*

Implementation of Koutný et al. (2022). Maps measurement probabilities directly to physical density matrices via Cholesky decomposition. Architecture: 200→180→180→160→160→160→160→100 neurons, Nadam optimizer. Handles noise and finite statistics better than MLE.

[![Repo](https://img.shields.io/badge/➡️_Code-qtom-blue)](https://github.com/alhazacod/qtom) [![PyPI](https://img.shields.io/badge/PyPI-package-blue)](https://pypi.org/project/qtom/)

---

## Tech knowledge ⚙️

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-1.24-blue?logo=numpy)
![SciPy](https://img.shields.io/badge/SciPy-1.10-blue?logo=scipy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-blue)
![Astropy](https://img.shields.io/badge/Astropy-5.0-blue?logo=astropy)
![Photutils](https://img.shields.io/badge/Photutils-1.5-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-2.x-red?logo=keras)
![Mathematica](https://img.shields.io/badge/Mathematica-13-red?logo=wolfram)
![Linux](https://img.shields.io/badge/Linux-Arch-blue?logo=archlinux)
![Bash](https://img.shields.io/badge/Bash-5.1-green?logo=gnubash)

**Numerical ODE solvers · Phase‑space analysis · Field‑space geometry · Aperture photometry · Quantum state reconstruction**

## Non‑physics shit I also build 🖥️

- **Homelab** - because fuck Google Drive and subscription models. Local NAS, self‑hosted services (Tailscale, Jellyfin, the usual rabbit hole).
- **Arch Linux daily driver** - I use Arch btw. (Yes, I'll mention it in every conversation.)
- **Random CLI tools for automating life** – Check out my repos, maybe something is useful for you.

## Random facts 🎲

- Native Spanish, fluent English.
- I read arXiv: hep-th and astro-ph.CO like it's Twitter.
- My thesis advisor is **Prof. Juan Pablo Beltran Almeida**, ask him if I'm full of shit.
- Homelab addict. If it can be self‑hosted, it will be.
- `I use Arch btw`.


---

"The universe is under no obligation to make sense to you."

— Not me, but I feel it in my bones debugging ODEs at 2 AM.

---


*Last updated: April 2026 – thesis defense incoming.*
