# Hi, I'm Faycal 👋

### Marketing data scientist & ML engineer. I measure what actually works.

8+ years answering one question for marketing and product teams: *what did this cause?* Media mix models, experiments, causal models and the ML systems around them, at Adobe, Restaurant Brands International and global media agencies.

[![Medium](https://img.shields.io/badge/Medium-writing-black?logo=medium)](https://medium.com/@faycal.zouine.usa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?logo=linkedin)](https://www.linkedin.com/in/faycal-zouine/)
[![Kaggle](https://img.shields.io/badge/Kaggle-zfayfay-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/zfayfay)
[![Email](https://img.shields.io/badge/Email-faycal.zouine.usa%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:faycal.zouine.usa@gmail.com)

---

## 🎬 Netflix Tech Blog, rebuilt

I take Netflix research posts, rebuild them on public data, then push them further than the original. Each one is a runnable notebook plus a write-up. Simulations are built on real MovieLens tastes, so I know the true answer and can grade the method.

| Project | Netflix's idea | What I found | |
|---|---|---|---|
| [**Artwork personalization (MAPS)**](https://github.com/ZFayFay/netflix-maps-replication) | CLIP image embeddings fix cold-start for artwork ranking | Content embeddings or one shared model alone did nothing. Only the two together won: **+3% to +20%** on new titles. Raw CLIP cosines needed centering first. | [Post](https://medium.com/@faycal.zouine.usa/i-rebuilt-netflixs-artwork-personalization-system-on-movielens-here-s-what-actually-matters-d0540b7c43eb) |
| [**Billboard bandit**](https://github.com/ZFayFay/netflix-bandits-replication) | ε-greedy bandit, greedy vs incrementality policies | The metric picks the winner: incrementality gets **+28% incremental plays**. Replay overstates by 14% on non-uniform logs; doubly robust doesn't. | [Post](https://medium.com/@faycal.zouine.usa/i-rebuilt-netflixs-billboard-bandit-the-metric-picked-the-winner-686296a3b72f) |
| [**Value of recommendations**](https://github.com/ZFayFay/netflix-rec-impact-replication) | Choice model to measure what recommendations cause | The dashboard says **7.5×**, the truth is **3.1×**, the model gets 3.4×. Its bootstrap intervals still missed the truth. | [Post](https://medium.com/@faycal.zouine.usa/your-dashboard-says-recommendations-multiply-viewing-by-7-5-the-truth-is-3-1-a7b68e8334c3) |

---

## 🧪 More work

| Project | What it is |
|---|---|
| [**Experimentation platform**](https://github.com/ZFayFay/streamlit-experimentation-platform) | A/B test analysis app: frequentist, Bayesian, CUPED and heterogeneous effects. [Live demo →](https://app-experimentation-platform-p4mcqhkrtw5q3f72yr2wrw.streamlit.app/) |
| [**Kaggle notebooks**](https://github.com/ZFayFay/kaggle-notebooks) | [How coding agents should search a repo](https://www.kaggle.com/code/zfayfay/where-is-the-bug-file-finding-methods-compared) · [Does synthetic data help? Drift and signal checks](https://www.kaggle.com/code/zfayfay/s6e11-synthetic-vs-original-does-it-help) |
| [**Evolution of movie recommenders**](https://github.com/ZFayFay/Are-You-Coming-to-the-Tree-The-Evolution-of-Movie-Recommendation-Systems) | From popularity baselines to collaborative filtering, on movie ratings |
| [**Sequence models & literature**](https://github.com/ZFayFay/Sequence-models-and-literature) | A 2020, pre-ChatGPT LSTM that writes in the style of Washington Irving's *Tales of the Alhambra* |

---

## 💼 What I do at work

- **Media mix modeling.** Built Adobe Acrobat's MMM from zero, run globally (NA, EMEA, Japan, APAC, UK). Built a Bayesian MMM at DMA level with Google Meridian for Popeyes, whose optimizer guided second-half local media spend.
- **Causal measurement.** Double ML and survival models to measure CRM impact. Geo lift tests on the agency side.
- **ML in production.** Store-level demand forecasting with LightGBM, a multi-armed bandit for offers, and customer segmentation.
- **Making it usable.** Dashboards and an AI chatbot on Snowflake Cortex so teams can query loyalty data themselves. Results presented to VPs, directors and the CMO.

**Stack:** Python · SQL · scikit-learn · LightGBM · PyTorch · Google Meridian · Snowflake · Databricks · Streamlit

---

<sub>📍 Miami · Open to senior data science and measurement roles · MBA (ESG Business School) · M.Sc. Management Engineering Statistics · MIT xPRO & Stanford ML certificates</sub>
