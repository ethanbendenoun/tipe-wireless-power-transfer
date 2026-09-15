# Optimising a wireless inductive charger for a mobile phone

TIPE research project — French *classes préparatoires* (MP\*), Lycée Pasteur, 2024–2025.

How can the transfer efficiency of an inductive phone charger be maximised? Five experiments,
retraced from the raw oscilloscope readings: non-resonant coupling, resonant coupling, resonant
coupling with a ferromagnetic core, then the effect of coil misalignment and coil separation.

**→ [Read the notebook](wireless_power_transfer.ipynb)** — method, code, figures and results in one document.

| Configuration | Best efficiency |
|---|---|
| Non-resonant coupling | 3.7 % at 60 kHz |
| Resonant coupling | 12.6 % at 29 kHz |
| Resonant coupling + ferromagnetic core | 97 % at 17 kHz (see the definition of *r* in the notebook) |

## Contents

- `wireless_power_transfer.ipynb` — the project, as an executed notebook
- `data/*.csv` — the five measurement series
- `data/raw/*.rw3` — the original Regressi files

## Reproducing the figures

```bash
pip install pandas matplotlib
jupyter notebook wireless_power_transfer.ipynb
```

Part of [ethanbendenoun.github.io](https://ethanbendenoun.github.io/).
