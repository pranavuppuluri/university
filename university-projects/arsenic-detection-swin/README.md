# Arsenic detection with vision transformers

Image classification experiments from September and October 2024 for detecting
arsenic contamination from images. The main model is a Swin transformer; the
other notebooks compare it against several transformer variants on the same data.

| Notebook | What it is |
| --- | --- |
| `swin-arsenic-baseline.ipynb` | First Swin transformer run |
| `swin-arsenic-final.ipynb` | Final version with early stopping and augmentation |
| `ceit.ipynb` | CeiT comparison |
| `cait-transformer.ipynb` | CaiT comparison |
| `deit.ipynb` | DeiT comparison |
| `t2t-transformer.ipynb` | Tokens-to-Token ViT comparison |
| `tnt-transformer.ipynb` | Transformer-in-Transformer comparison |

The notebooks were run on Kaggle and expect the dataset at the Kaggle input
path. The dataset is not included.
