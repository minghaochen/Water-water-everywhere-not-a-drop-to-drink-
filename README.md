# Simple 5 fold Catboost - 0.06216

## About the competition

Considering that one of the most effective ways to stop the spread of COVID-19 and other pathogens is proper hand hygiene, these numbers are alarming. This simple behavior of handwashing not only protects us from contracting the disease but also stops transmission to other people.

But did you know that 2.2 billion people globally do not have access to safe water at home? And a further 1.37 billion people globally lack handwashing facilities at home? Almost two billion people around the world rely on health care facilities that do not have basic water services.

The world’s water resources are under increasing threat from the impacts of climate change, population growth, and pollution. As the global population grows, a persistent challenge is how to access enough water to meet humanity’s needs while also preserving the integrity of aquatic ecosystems. The Pacific Institute works on water resource issues around the globe, collaborating with stakeholders to ensure communities and nature have the water they need to thrive now and in the future.

This makes water cleanliness and understanding water sanitation is a must in both rural as well as urban areas. To do that, estimation of the quality of water we consume on a day-to-day basis could be the very first step towards water sanitation.

In this competition, your aim is to train a machine learning model based on the water quality data provided to you in the training file and further predict the quality estimation `result` for the test dataset.

## About the data set

The dataset provided in the `train.csv` consists of the following features:

- `id`: The unique ID for each row.
- `categoryA` - `categoryF`: 6 category columns with suffix A to F.
- `featureA` - `featureI`: 9 feature columns with suffix A to I.
- `compositionA` - `compositionJ`: 10 composition columns with suffix A to J.
- `unit`: The unit of measurement for the result values.
- `result`: The measure for water quality (target variable).