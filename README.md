# TP-DATA-TYPE

Travaux pratiques sur la manipulation de différents types de données (séries temporelles, audio, image, vidéo, graphes) en Python.

| Notebook | Sujet | Outils |
|---|---|---|
| [tp1.ipynb](tp1.ipynb) | Séries temporelles : index temporel, moyenne mobile, décomposition | pandas, statsmodels |
| [tp2.ipynb](tp2.ipynb) | Audio : chargement, waveform, spectrogramme, ajout de bruit | librosa |
| [tp3.ipynb](tp3.ipynb) | Images : dimensions, normalisation, canaux RVB, bounding boxes | NumPy, matplotlib, OpenCV |
| [tp4.ipynb](tp4.ipynb) | Vidéo : métadonnées, extraction de frames, fps, différence entre frames | OpenCV, ffmpeg |
| [tp5.ipynb](tp5.ipynb) | Graphes : format Pajek, degrés, distribution, visualisation interactive | NetworkX, ipycytoscape |

## Données

- TP1 : [Airline Passengers](https://www.kaggle.com/datasets/erogluegemen/airline-passengers)
- TP2 : [TP-02 Audio](https://www.kaggle.com/datasets/ouaraskhelilrafik/tp-02-audio)
- TP3 : [Food-101 Tiny](https://www.kaggle.com/datasets/msarmi9/food101tiny)
- TP4 : `vtest.avi`, vidéo d'exemple d'OpenCV
- TP5 : [Toy Network Datasets](https://www.kaggle.com/datasets/mateuscco/toy-network-datasets)

Les datasets sont téléchargés automatiquement à l'exécution (via `kagglehub` ou depuis GitHub).

## Installation

Le projet utilise [uv](https://docs.astral.sh/uv/) (Python 3.11) :

```bash
uv sync
uv run jupyter lab
```

Sélectionner ensuite le kernel du dossier `.venv` et exécuter les notebooks dans l'ordre des cellules. Le widget ipycytoscape du TP5 ne s'affiche que dans un notebook exécuté (pas sur GitHub).
