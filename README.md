# evcharge-graphnets

Reference implementation for **"Graph Neural Demand Forecasting for Urban EV Charging Networks"** (Applied Energy).

This repository contains the complete training and evaluation pipeline used in the
paper: dataset loaders, the model, the training loop, the evaluation script and the
released metrics.

## Contents

```
configs/
  default.yaml
src/
  __init__.py
  graphnet.py
train.py
eval.py
results/
  metrics.md
requirements.txt
```

## Quick start

```
pip install -r requirements.txt
python train.py --config configs/default.yaml
python eval.py --checkpoint checkpoints/best.pt
```

The released checkpoint reproduces the numbers in `results/metrics.md`.

## Citation

```bibtex
@inproceedings{evcharge-graphnets2026,
  title={Graph Neural Demand Forecasting for Urban EV Charging Networks},
  booktitle={Applied Energy},
  year={2026}
  
}
```
