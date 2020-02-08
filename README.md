# Hybrid Hierarchical Attention Network 

We propose a Hybrid Hierarchical Attention Network (HHAN) to detect whether the event is real or fake. The model consists of three modules. The first module captures the hierarchical text information and temporal information of the event. The second module is used to model the manually extracted features. The last module combines the previous two modules Information and performs misinformation detection tasks. If you are interested, please read our paper titled "A Hybrid Hierarchical Attention Network for Misinformation Detection on WeChat"


## Require

- Python3
- numpy
- pandas
- jieba
- keras


## Project Architecture

- data/sgns.weibo.word: Word embedded files, you can download from https://github.com/Embedding/Chinese-Word-Vectors.
- data/stop_words.txt: File to remove stop_words.
- data/all_data.csv: Our WeChat misinformation dataset.
- HAN-cate-side.ipynb: Code file
