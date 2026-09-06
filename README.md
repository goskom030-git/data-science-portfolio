# Data Science & Machine Learning Portfolio

Репозиторий содержит прикладные проекты по направлениям **Data Science, Machine Learning, MLOps и Аналитика данных**.

Портфолио включает **12 практических кейсов**: кредитный и поведенческий скоринг, MLOps-пайплайны, когортный анализ и retention, A/B-тестирование, временные ряды, регрессионный анализ и компьютерное зрение.

---

## Флагманский проект (ML & MLOps Service)

> **[StayAI SmartScore: Production ML Service](https://github.com/goskom030-git/stayai-ml-service)**  
> Микросервис скоринга объявлений аренды жилья: **Apache Airflow DAG**, интеграция с **PostgreSQL** и **S3 Object Storage**, модель **LightGBM** (Optuna tuning, SHAP), автоматическая предобработка и батч-инференс.

---

## Реестр проектов

| № | Направление / Задача | Проект | Ключевой стек | Метрики | Ссылка |
|:---:|:---|:---|:---|:---:|:---:|
| **01** | **Fintech / Scoring** | Поведенческий скоринг клиентов банка (90+ default) | CatBoost, Optuna, Scikit-learn, Time Split | **ROC-AUC: 0.77**<br>F1: 0.65 | [Открыть кейс](projects/01_credit_and_behavioral_scoring/) |
| **02** | **Hospitality / ML** | Прогнозирование риска отмены бронирований отелей | LightGBM, CatBoost, PostgreSQL, merge_asof | **ROC-AUC: 0.84**<br>F1: 0.76 | [Открыть кейс](projects/02_hotel_booking_cancellation_risk/) |
| **03** | **Logistics / E-com** | Выявление рисков задержки курьерской доставки | CatBoost, Scikit-learn, Feature Engineering | **ROC-AUC: 0.81**<br>F1: 0.71 | [Открыть кейс](projects/03_delivery_delay_risk/) |
| **04** | **Auto / Valuation** | Оценка рыночной стоимости автомобилей (Regression) | LightGBM, CatBoost, Optuna, Pandas | **RMSE: 1540 €**<br>R²: 0.89 | [Открыть кейс](projects/04_car_price_estimation/) |
| **05** | **AdTech / Marketing** | Прогнозирование вероятности клика (CTR Prediction) | LightGBM, CalibratedClassifierCV, Imbalance | **PR-AUC: 0.68**<br>ROC-AUC: 0.83 | [Открыть кейс](projects/05_ctr_prediction/) |
| **06** | **Subscription / Churn** | Прогнозирование оттока клиентов сервиса подписки | CatBoost, Scikit-learn, Optuna, Joblib | **PR-AUC: 0.73**<br>F1: 0.61 | [Открыть кейс](projects/06_customer_churn_prediction/) |
| **07** | **A/B Testing & Stats** | Дизайн, проведение и анализ A/B-эксперимента | SciPy, Statsmodels, Bootstrap, Sample Size | **p-value < 0.05**<br>+4.2% Lift | [Открыть кейс](projects/07_ab_testing_and_experimentation/) |
| **08** | **Analytics / Stats** | Статистический анализ и проверка гипотез кикшеринга | SciPy (ttest, norm.cdf/ppf), Matplotlib | **Stat Tests**<br>Quantile CDF/PPF | [Открыть кейс](projects/08_business_hypothesis_testing/) |
| **09** | **Product / Retention** | Исследование поведения и удержания пользователей (Афиша) | SQL, PostgreSQL, Cohort Analysis, $\phi_K$ | **Retention Analysis**<br>User Profiling | [Открыть кейс](projects/12_user_behavior_and_retention_analysis/) |
| **10** | **Computer Vision / ML** | Определение демографии и возраста пользователей | PyTorch / Sklearn, SVC (rbf kernel), Joblib | **F1-Score: 0.70**<br>(Baseline: 0.09) | [Открыть кейс](projects/09_computer_vision_age_prediction/) |
| **11** | **Mobility / Demand** | Прогнозирование спроса на городской велопрокат | kNN, DecisionTree, Weather Features | **MAE: 4.87**<br>R²: 0.91 | [Открыть кейс](projects/10_bike_rental_demand_forecasting/) |
| **12** | **Morphometrics** | Высокоточная регрессия биометрических параметров | Ridge, Lasso, SGDRegressor (MAE vs MSE) | **MAE: 3.63 kg**<br>R²: 0.983 | [Открыть кейс](projects/11_sea_turtle_weight_regression/) |

---

## Технологический стек

* **Языки и библиотеки анализа:** Python, SQL, PostgreSQL, Pandas, NumPy, SciPy, Statsmodels, Phik
* **Machine Learning & Deep Learning:** LightGBM, CatBoost, Scikit-learn, Optuna, PyTorch, SHAP
* **Data Engineering & MLOps:** Apache Airflow, PostgreSQL, S3 (Object Storage), Joblib, Docker
* **Визуализация:** Matplotlib, Seaborn, Plotly

---

## Контакты
* **GitHub:** [@goskom030-git](https://github.com/goskom030-git)