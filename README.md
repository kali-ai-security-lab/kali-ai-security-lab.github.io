# KALI Lab

Website for the **Knowledge, Adversaries, Language & Intelligence Lab** at Northern Arizona University, led by Dr. Mithun Paul Saint-Germain.

The static site is in `dist/`. A GitHub Actions workflow publishes it to GitHub Pages on every push to `main`.

## Local preview

```bash
python3 -m http.server 4173 --directory dist
```
