<div align="center">

# Hi, I'm Vinicius Valiati 👋

### Analytics Engineer @ Indicium | Data Science

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F80ED&center=true&vCenter=true&width=500&lines=Analytics+Engineer+%40+Indicium;Supply+Chain+Data;Data+Science+%26+Machine+Learning" alt="Analytics Engineer @ Indicium, Supply Chain Data, Data Science and Machine Learning" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusvaliati)

</div>

I build data pipelines and models that turn operational data into decisions. My day job is analytics engineering for supply chain; on the side I work on machine learning projects, from recommender systems to classification models, and I like shipping them as apps people can actually open.

```text
┌──────────────────────────────────────────────────────────────────────────────┐
│ ● ● ●                                                                        │
├──────────────────────────────────────────────────────────────────────────────┤
│ vinicius@dev ~                                                               │
│──────────────────────────────────────────────────────────────────────────────│
│ OS .............. Windows 11 / WSL2                                          │
│ Role ............ Analytics Engineer @ Indicium                              │
│ Focus ........... Supply Chain Analytics                                     │
│                                                                              │
│ Education                                                                    │
│ B.A. ............ Business Administration                                    │
│ Postgraduate .... Data Science & Big Data (UFPR)                             │
│ MBA ............. Advanced Analytics                                         │
│ In progress ..... B.Sc. Computer Science (FIAP)                              │
│                                                                              │
│ Stack                                                                        │
│ Data ............ SQL, dbt, BigQuery, Airflow                                │
│ BI .............. Power BI, Tableau, Looker                                  │
│ Languages ....... Python, SQL, R                                             │
│ ML .............. scikit-learn, XGBoost, Streamlit                           │
│ Cloud/Infra ..... Google Cloud, Docker, Git                                  │
│                                                                              │
│ Contact                                                                      │
│ LinkedIn ........ linkedin.com/in/viniciusvaliati                            │
└──────────────────────────────────────────────────────────────────────────────┘
```

## Featured projects

### [Supply Chain Analytics Pipeline](https://github.com/vinivaliati/supply-chain-analytics)

An end-to-end data pipeline simulating a distribution company's supply chain. It generates its own synthetic data with realistic business rules, orchestrates with Airflow and transforms with dbt (staging → marts, tests, data contracts, SCD2 snapshots, incremental models), with a MetricFlow semantic layer and a Streamlit dashboard on top.

- Covers four business areas: OTIF, stockouts, inventory accuracy and transit performance
- Everything runs on Docker, with CI on GitHub Actions

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

### [Anime Recommendation with Collaborative Filtering](https://github.com/vinivaliati/A-Collaborative-Filtering-Model-Applied-to-Anime-Recommendation)

A recommender for **new** users with no rating history (the cold start problem), rebuilt from my final project for the Data Science & Big Data specialization at UFPR. K-means groups anime into 20 clusters and turns the most popular title of each into a "persona"; the user picks up to three, and user-based collaborative filtering recommends what the most similar users liked.

- 38.0% Hit Rate with Cosine distance, about twice the 18.3% of recommending the 10 most popular anime
- Compares Cosine, Manhattan and Euclidean distances on Hit Rate and Serendipity
- Ships with a Streamlit app that runs right after cloning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### [EV ChargeOps](https://github.com/vinivaliati/computer_science_fiap_challenge_2026)

A management platform for electric vehicle charging in condominiums and corporate buildings, built by a team of five for the GoodWe × FIAP Enterprise Challenge 2026. Each charging session becomes structured data in a star schema that feeds an automated billing engine (pay per use, subscription and shared condominium plans) and AI models that support the operator.

- Integrates public data from Open Charge Map, IBGE and RENAVAM
- [AI dashboard](https://vinivaliati-computer-science-fiap-challe-appdashboard-ia-hqsiet.streamlit.app/) · [User app](https://vinivaliati-computer-science-fiap-c-appdashboard-usuario-anjojx.streamlit.app/) · [Manager panel (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiYWQwZTlmOWUtOGM3NC00ZTUxLTg1ZjAtZmRkYzM2NWZkNDE2IiwidCI6IjExZGJiZmUyLTg5YjgtNDU0OS1iZTEwLWNlYzM2NGU1OTU1MSIsImMiOjR9)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### [Employee Attrition Prediction](https://github.com/vinivaliati/Project-IBM-attrition)

A model that estimates the probability of an employee leaving the company, using the IBM HR Analytics dataset. Includes a full EDA and a comparison of classification algorithms; Logistic Regression was chosen as the final model for its balance between performance and interpretability for the business.

- [Live Streamlit app](https://project-ibm-attrition-vinicius-valiati.streamlit.app)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

<div align="center">

More on my [repositories page](https://github.com/vinivaliati?tab=repositories) · Let's talk on [LinkedIn](https://www.linkedin.com/in/viniciusvaliati)

</div>
