# Frozen LLMs for Temporal Link Prediction

Code and outputs for a course project on temporal link prediction with frozen (not fine-tuned) language models, evaluated on the ICEWS1819 dataset from the DTGB benchmark.

Course: Social Networking and Mining, IGDTUW
Supervisor: Dr. Jyoti Shokeen
Authors: Kanishka, Aviral, Gunnika Aggarwal

## Repository layout

```
.
├── SNM_LLM_link_prediction_final.ipynb   # full pipeline, run top to bottom
├── data/                   # dataset files (see below)
├── figs/                   # all figures produced by the notebook
├── tables/                 # all result tables produced by the notebook
└── README.md
```

## Data

The dataset is ICEWS1819 from DTGB, which is publicly available:
https://github.com/zjs123/DTGB

Place the files inside `data/` before running the notebook. [Or: the files are already included in `data/`.]

## How to run

1. Open the notebook in Google Colab (a T4 GPU runtime is enough) or in a local Jupyter setup with a CUDA GPU.
2. Upload or mount the `data/` folder and set the data path in the first cells.
3. Run all cells in order. Dependencies are installed in the first cell of the notebook.
4. Figures are written to `figs/` and tables to `tables/`.

## Outputs

- `figs/` holds the figures used in the paper.
- `tables/` holds the result tables used in the paper.

Please refer to the paper for descriptions and discussion of the results.


## Acknowledgement

AI tools were used for code assistance and language editing; the authors verified the experiments and reported numbers.

## License

MIT
