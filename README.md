# Faycal Zouine

Marketing data scientist. I figure out what things actually caused.

I'm usually the one in the meeting asking "compared to what?" A campaign ran and sales went up. Great. Would they have gone up anyway? That second question is my job.

8 years of it. Media mix models at Adobe and Popeyes. Geo tests on the agency side. Causal models for CRM. And the ML systems that run on top.

[Medium](https://medium.com/@faycal.zouine.usa) · [LinkedIn](https://www.linkedin.com/in/faycal-zouine/) · [Kaggle](https://www.kaggle.com/zfayfay) · faycal.zouine.usa@gmail.com

## Netflix Tech Blog, rebuilt

Netflix publishes how they measure things. I rebuild it on public data, then try to break it.

The trick: I simulate on real MovieLens tastes. So I know the right answer, and I can check if the method finds it.

- **Artwork personalization.** Netflix fixed cold-start with two ideas. Each one alone did nothing. Together: +3% to +20% on new titles. [Code](https://github.com/ZFayFay/netflix-maps-replication) · [Post](https://medium.com/@faycal.zouine.usa/i-rebuilt-netflixs-artwork-personalization-system-on-movielens-here-s-what-actually-matters-d0540b7c43eb)
- **Billboard bandit.** The metric picks the winner. And Netflix's offline test reads 14% too high on the wrong kind of logs. [Code](https://github.com/ZFayFay/netflix-bandits-replication) · [Post](https://medium.com/@faycal.zouine.usa/i-rebuilt-netflixs-billboard-bandit-the-metric-picked-the-winner-686296a3b72f)
- **What recommendations are worth.** The dashboard says 7.5×. The truth is 3.1×. The error bars missed it too. [Code](https://github.com/ZFayFay/netflix-rec-impact-replication) · [Post](https://medium.com/@faycal.zouine.usa/your-dashboard-says-recommendations-multiply-viewing-by-7-5-the-truth-is-3-1-a7b68e8334c3)

Same lesson three times. The easy number is usually wrong. The useful part is saying by how much.

## Big Tech measurement, rebuilt

Same idea, harder rules. Before running anything I write down what should happen and how I'll judge it, and commit it. Then I report what passed and what didn't.

- **Google GeoX (geo experiments).** On ten years of real Iowa sales, the estimates were right but the error bars were too narrow. [Code](https://github.com/ZFayFay/geox-replication)
- **Spotify on Bayesian A/B tests.** Their math held up, even on a skewed real metric. Novelty effects are where early stopping goes wrong. [Code](https://github.com/ZFayFay/spotify-bayes-replication)
- **Airbnb interleaving.** "50x faster" failed my test. The speedup depends on how similar the two rankers are. [Code](https://github.com/ZFayFay/airbnb-interleaving-replication)
- **Meta semantic IDs.** On new items, a plain content embedding beat them. [Code](https://github.com/ZFayFay/meta-semantic-ids-replication)

## At work

- Built Adobe Acrobat's media mix model from scratch. It ran in NA, EMEA, Japan, APAC and the UK.
- Built a Bayesian media mix model for Popeyes with Google Meridian, by DMA. Its plan guided second-half local media spend.
- Measured CRM impact with double ML and survival models.
- Built a store-level demand forecast (LightGBM), an offer bandit, and customer segments.
- Put an AI chatbot on Snowflake so the loyalty team could ask the data questions without me.

Python, SQL, scikit-learn, LightGBM, PyTorch, Meridian, Snowflake, Databricks, Streamlit.

## Other things here

- [Experimentation platform](https://github.com/ZFayFay/streamlit-experimentation-platform). An A/B test app: frequentist, Bayesian, CUPED. [Try it](https://app-experimentation-platform-p4mcqhkrtw5q3f72yr2wrw.streamlit.app/).
- [Kaggle notebooks](https://github.com/ZFayFay/kaggle-notebooks). How coding agents should search a repo. Whether synthetic data helps.
- [Movie recommenders, old to new](https://github.com/ZFayFay/Are-You-Coming-to-the-Tree-The-Evolution-of-Movie-Recommendation-Systems). Popularity baselines to collaborative filtering.
- [An LSTM that writes like Washington Irving](https://github.com/ZFayFay/Sequence-models-and-literature). From 2020, before ChatGPT made this boring.

Miami. Open to senior data science and measurement roles.
