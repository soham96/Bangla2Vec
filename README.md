# Bangla2Vec

<p align="center">
<img src="https://github.com/soham96/Bangla2Vec/blob/master/img/bangla2vec.png" width="450" height="300" />
</p>

Bangla2Vec is an open source project for modelling the Bengali Language. The models released here can be used for a variety of tasks like [classification](https://github.com/soham96/Bengali_news_classifier) and translation. Furthermore, all the data and models are opensourced so you can train your own model or use the pretrained models for your own tasks.

## Releases

- Trained a skipgram model on a news dataset: [Training Script](news_vector_training.ipynb) | [Results](test_word2vec.ipynb) | [Model](https://drive.google.com/file/d/1X08NlbfZncP-h-aWHeDpL1OS39QxkcpP/view?usp=sharing)
- Trained a skipgram model on wikipedia dataset: [Training Script](wikipedia_embeddings.ipynb) | [Results](wikipedia_embeddings.ipynb) | [Model](https://drive.google.com/file/d/1EzKo9jcF1Q-8qBQotJj_z2CdAJXepPtO/view?usp=sharing)
- Scripts to scrape data from Bengali news websites: [Github Repo](https://github.com/soham96/bengali_news_crawler)

## Data

Data was scraped from multiple online Bengali news websites.

Data was also collected from a Wikipedia dump.

You can view the data in the [data](data) folder.

## Examples

- [Classification](https://github.com/soham96/bengali_news_crawler): Using the trained Bangal2vec models, a news classifier was built. This classifier can classify news into 5 categories based on the news headlines. The best model achieved a testing f1 score of 0.76 after training on just 40k news headlines.

## Similar Projects

This project is a sister project of other projects working on IndicNLP. They include:
- [Malayalam](https://github.com/adamshamsudeen/Vaaku2Vec)
- [Tamil](https://github.com/vanangamudi/tamil-news-classification/tree/master/anikattu)

To get resources to start working on IndicNLP or to learn more about it, you can see our [Awesome List](https://github.com/vanangamudi/awesome-resources-for-indic-nlp) of resources
