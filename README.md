# BERT-news-classifier

- **By:** Rodrigo Pari

- **Contact:** rodrigo.parisusao25201@gmail.com

BERT classifier trained in El Deber news. This is just a demo, the model is not trained with a lot of data.

## License

This project has not a license file

## Directories Distribution

```
├── data
│   ├── processed
│   │   ├── test.json
│   │   ├── train.json
│   │   └── valid.json
│   └── raw
│       └── sample-data.json
├── models
│   ├── metrics.pt
│   └── model.pt
├── notebooks
│   ├── 0_preproc.ipynb
│   ├── 1_creating-model-bert.ipynb
│   └── 2_eval.ipynb
├── README.md
├── requirements.txt
```

## Requirements

- Python 3.8
- pytorch-transformers==1.2.0
- torch==1.10.1
- torchaudio==0.10.1
- torchtext==0.11.1
- torchvision==0.11.2
- transformers==4.13.0
