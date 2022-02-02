# Sentiment Analysis

Classification of books reviews, the first step is a binary classification(positive or negative), the second step is multiclass classification, contain four grades (1,2,4,5)

![1_L7ylwBqCQ8oBQ_TFgmbTPQ](https://user-images.githubusercontent.com/71607449/152205955-feb757f3-5bcc-4607-be4d-60fb4ef56b17.jpg)


## Data

Amazon provide a complete information of score of different productos, there are two database, the first contain a binary classification and the second a multiclass classification. [link data](https://www.cs.jhu.edu/~mdredze/datasets/sentiment/)



## Usage Data

The format of the data is tar, in Python is possible decompress, so:

```
import tarfile

file = tarfile.open('processed_acl.tar.gz')
file.extractall('./data_reviews')
file.close()
```

## My Page
[diego51alejo](https://diego51alejo.github.io/diego51alejo/)
