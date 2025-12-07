# datasets
Repo to host datasets for personal projects so I can use raw github urls

## Datasets

### fake_news.csv
**Source**: Kaggle  
**Rows**: 20,800  
**Columns**: 
- `id`: Unique identifier for each news article
- `title`: Article headline
- `author`: Author name
- `text`: Full article text content
- `label`: Binary classification (0 = fake, 1 = real)

**Label Distribution**:
- Real news (label=1): 10,413 articles (50.1%)
- Fake news (label=0): 10,387 articles (49.9%)

**Description**: A balanced dataset of news articles labeled as either real (1) or fake (0).

### fake_tweets.csv
**Rows**: 6,420  
**Columns**:
- `id`: Unique identifier for each tweet
- `tweet`: Tweet text content
- `label`: Classification label ("real" or "fake")

**Label Distribution**:
- Real tweets: 3,360 tweets (52.3%)
- Fake tweets: 3,060 tweets (47.7%)

**Description**: A dataset of tweets related to COVID-19, labeled as either real or fake. 