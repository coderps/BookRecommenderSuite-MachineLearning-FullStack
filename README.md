# BookRecommenderSuite-MachineLearning-FullStack

This is a Book Recommendation Suite that recommends a book based on the comments/reviews given by the other users, not number of stars, but textual understanding decides the "likability" of a particular book and then matching with the user's liking.

## Installation

```bash
pip install nltk
pip install django==1.10.5
```

For setting up the *settings.py* file, see this [page](https://docs.djangoproject.com/en/1.10/topics/settings/).

For the full list of settings and their values, see this [page](https://docs.djangoproject.com/en/1.10/ref/settings/)

## Some simple things you can do with NLTK

```bash
>>> import nltk
>>> sentence = """At eight o'clock on Thursday morning
... Arthur didn't feel very good."""
>>> tokens = nltk.word_tokenize(sentence)
>>> tokens
['At', 'eight', "o'clock", 'on', 'Thursday', 'morning',
'Arthur', 'did', "n't", 'feel', 'very', 'good', '.']
>>> tagged = nltk.pos_tag(tokens)
>>> tagged[0:6]
[('At', 'IN'), ('eight', 'CD'), ("o'clock", 'JJ'), ('on', 'IN'),
('Thursday', 'NNP'), ('morning', 'NN')]
```

For more information, see this [page](https://www.nltk.org/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## More Information
This project was made as a part of my Bachelor Thesis, in a group of three.
