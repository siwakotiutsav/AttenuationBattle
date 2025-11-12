# AttenuationBattle
This will be a comparison between different attenuation models used or galactic center


A compact and extensible Python notebook for visualizing and integrating infrared attenuation models into PAHFIT. This project compares several silicate extinction laws and demonstrates how to incorporate custom attenuation models into the PAHFIT framework for spectral fitting.

## 🔬 What It Does

- Plots attenuation curves for:
  - **S07** (Smith et al. 2007) — from PAHFIT
  - **G23** (Galliano et al. 2023) — from `dust_extinction`
  - **Fritz** and **Lutz** — custom implementations
- Normalizes attenuation at 9.7 µm using mixed geometry
- Integrates custom models into PAHFIT for full spectral fitting
- Provides a reproducible workflow for modifying PAHFIT components

## 📦 Dependencies

Install required packages:

```bash
pip install numpy matplotlib dust_extinction
pip install git+https://github.com/PAHFIT/pahfit.git
```


## 📚 References

- Smith et al. (2007), ApJ
- Fritz et al. (2011), ApJ
- Galliano et al. (2023), PAHFIT v2
- Lutz et al. (1996), A&A

## 🧠 License

MIT License — free to use, modify, and share.
