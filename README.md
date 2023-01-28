# Drug-Review-sentiment-analysis

### Data Set Information:

The dataset provides patient reviews on specific drugs along with related conditions and a 10 star patient rating reflecting overall patient satisfaction. The data was obtained by crawling online pharmaceutical review sites. The intention was to study

- sentiment analysis of drug experience over multiple facets, i.e. sentiments learned on specific aspects such as effectiveness and side effects,
- the transferability of models among domains, i.e. conditions, and
- the transferability of models among different data sources (see 'Drug Review Dataset (Druglib.com)').

The data is split into a train (75%) a test (25%) partition (see publication) and stored in two .tsv (tab-separated-values) files, respectively.

### Attribute Information:

- 1. drugName (categorical): name of drug
- 2. condition (categorical): name of condition
- 3. review (text): patient review
- 4. rating (numerical): 10 star patient rating
- 5. date (date): date of review entry
- 6. usefulCount (numerical): number of users who found review useful

### Data Source
[Click here](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29)

### Data Visualization

![Ratings Distribution](https://user-images.githubusercontent.com/104658866/215289360-b0b5534e-0ced-41a0-8799-d3427818b445.png)
![Reviews Impact](https://user-images.githubusercontent.com/104658866/215289393-784e240d-5a92-4832-bfdb-892ef5cb0e68.png)
![Most Reviewed Drugs](https://user-images.githubusercontent.com/104658866/215289398-55686c50-f1d8-42bb-b18b-1672519bca53.png)
![Most Repeated Conditions](https://user-images.githubusercontent.com/104658866/215289400-33e558d2-603e-43ce-adf7-11d7506cc308.png)
![Top20 The number of drugs per condition](https://user-images.githubusercontent.com/104658866/215289405-f3026efc-e5bf-4806-9564-85afbb3cbba7.png)
![Most Reviewed Drugs](https://user-images.githubusercontent.com/104658866/215289410-c662e74e-d1a4-4c4a-bcd6-78b88cc2f77b.png)
![Synchronization of the number of reviews over time](https://user-images.githubusercontent.com/104658866/215289417-f849b796-0fbf-47ee-9671-9fa0700796d9.png)
![Positive WordCloud](https://user-images.githubusercontent.com/104658866/215289424-eba8a1c2-bdb7-4100-8244-ec8ee64318ef.png)
![Negative WordCloud](https://user-images.githubusercontent.com/104658866/215289428-ad659b1e-f35b-461d-b3df-e41f9f7fc61e.png)
![Average usefulCount vs Rating - Average Review Length vs Rating](https://user-images.githubusercontent.com/104658866/215289433-bcdc45ff-f9bd-4616-8e49-c5861effdf33.png)

