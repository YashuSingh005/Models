# RPO — Repository of Models

A living collection of every ML/AI model I build on my learning journey.

## About

This repo is my personal archive of every model I learn to build — from my first regression model to whatever I'm training years from now. Each model gets its own folder, its own mini-writeup, and a line in the log below.

The goal isn't a polished portfolio (yet) — it's a record of growth I can look back on.

## Repo Structure

```
RPO/
├── 01-molecule-prediction/
│   ├── model.py / model.ipynb
│   ├── README.md          # what it does, dataset, results
│   └── requirements.txt
├── 02-.../
│   └── ...
├── assets/                 # shared plots, diagrams, sample outputs
└── README.md                # you are here
```

Convention: each model folder is numbered in the order I built it, so the repo doubles as a timeline.

## Model Log

| # | Model | Type | Framework | Status | Notes |
|---|-------|------|-----------|--------|-------|
| 01 | Molecule Prediction | Regression | scikit-learn | Done | First model, learned train/test split |

Add a row every time a new model lands in this repo.

## How to Run Any Model

Each model folder is self-contained.

```bash
# clone the repo
git clone https://github.com/YashuSingh005/RPO.git
cd RPO/<model-folder>

# install that model's dependencies
pip install -r requirements.txt

# run it
python model.py
# or open model.ipynb in Jupyter
```

## Why This Repo Exists

- Track my progress as I go from student to software engineer
- Force myself to document, not just code and forget
- Build a body of work I can point to for internships/jobs
- Revisit old models later and see how much better I've gotten

## Skills Being Tracked Here

- [ ] Classical ML (regression, classification, clustering)
- [ ] Deep Learning (CNNs, RNNs, Transformers)
- [ ] NLP models
- [ ] Computer Vision models
- [ ] Deployment (model to API to real usage)
- [ ] Full AI-integrated apps

## Progress

- Models built: 1
- Concepts learned: growing
- Deployed anywhere: not yet

## License

MIT — use anything here freely.
