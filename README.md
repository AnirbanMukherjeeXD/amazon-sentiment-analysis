
# Utilization of Oversampling for Multiclass Sentiment Analysis on Amazon Review Dataset

**Paper:** [IEEE Xplore Link](https://ieeexplore.ieee.org/abstract/document/8923260)  
Published in: *2019 IEEE 10th International Conference on Awareness Science and Technology (iCAST)*  
**Authors:** Anirban Mukherjee, Sabyasachi Mukhopadhyay, Prasanta K. Panigrahi, Saptarsi Goswami



## Overview

The task of this project was to perform sentiment analysis (multi-class classification) on Amazon Review data using various sequential models, and to see the difference in the performance before and after performing random oversampling on the dataset to reduce class imbalance.



## Folder Structure

```
├── dataset/
│   ├── Amazon_Instant_Video_5.json
│   ├── Digital_Music_5.json
│   └── Musical_Instruments_5.json
├── LSTM_30_Sentiment_Analysis.ipynb
├── LSTM_60_Sentiment_Analysis.ipynb
├── LSTM_datasets_variations_Sentiment_Analysis.ipynb
├── LSTM_oversample_Sentiment_Analysis.ipynb
├── Multi_class_Sentiment_Analysis.ipynb
└── README.md
```



## Notebooks Included

Each notebook contains experiments with slightly different setups:

- `Multi_class_Sentiment_Analysis.ipynb` - Main notebook for multiclass sentiment classification on the Amazon review dataset.
- `LSTM_oversample_Sentiment_Analysis.ipynb` - Preliminary experiments using oversampling to handle class imbalance.
- `LSTM_30_Sentiment_Analysis.ipynb` - Model using an LSTM layer with 30 hidden units.
- `LSTM_60_Sentiment_Analysis.ipynb` - Model using an LSTM layer with 60 hidden units.
- `LSTM_datasets_variations_Sentiment_Analysis.ipynb` - Experiments conducted across multiple product category datasets.




## Dataset

The data used comes from subsets of the [Amazon Product Review Dataset](https://nijianmo.github.io/amazon/index.html), in `.json` format under the `dataset/` folder.



## Requirements

This project uses standard Python data science and deep learning libraries:

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `tensorflow` / `keras`



## Citation

```
@inproceedings{mukherjee2019utilization,
  title={Utilization of oversampling for multiclass sentiment analysis on amazon review dataset},
  author={Mukherjee, Anirban and Mukhopadhyay, Sabyasachi and Panigrahi, Prasanta K and Goswami, Saptarsi},
  booktitle={2019 IEEE 10th international conference on awareness science and technology (iCAST)},
  pages={1--6},
  year={2019},
  organization={IEEE}
}

```
