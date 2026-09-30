# TP-DATA-TYPE

Travaux pratiques sur la manipulation de différents types de données (audio, image, vidéo) en Python.

[tp4 - data](https://drive.google.com/drive/folders/1CNV3l9jcjTTNuq3j1Vxn8Sv9nvLUB7na?usp=sharing)

| Notebook | Sujet | Outils |
|---|---|---|
| [tp2.ipynb](tp2.ipynb) | Audio : chargement, waveform, spectrogramme, ajout de bruit | librosa |
| [tp3.ipynb](tp3.ipynb) | Images : dimensions, normalisation, canaux RVB, bounding boxes | NumPy, matplotlib, OpenCV |
| [tp4.ipynb](tp4.ipynb) | Vidéo : métadonnées, extraction de frames, fps, différence entre frames | OpenCV, ffmpeg |

## Données

- TP2 : [TP-02 Audio](https://www.kaggle.com/datasets/ouaraskhelilrafik/tp-02-audio)
- TP3 : [Food-101 Tiny](https://www.kaggle.com/datasets/msarmi9/food101tiny)
- TP4 : `vtest.avi`, vidéo d'exemple d'OpenCV

Les datasets sont téléchargés automatiquement à l'exécution (via `kagglehub` ou depuis GitHub).

## Installation

Le projet utilise [uv](https://docs.astral.sh/uv/) (Python 3.11) :

```bash
uv sync
uv run jupyter lab
```

Sélectionner ensuite le kernel du dossier `.venv` et exécuter les notebooks dans l'ordre des cellules.
