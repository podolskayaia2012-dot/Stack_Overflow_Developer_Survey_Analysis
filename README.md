# Stack Overflow Developer Survey Analysis
Exploratory Data Analysis (EDA) of Stack Overflow Survey. Data cleaning, descriptive statistics, and aggregation using Python and Pandas.
# Дослідження глобального IT-ринку та екосистеми Python за даними Stack Overflow 🚀

## 📌 Опис проєкту
Цей проєкт присвячений комплексному розвідувальному аналізу даних (EDA) світової IT-індустрії на основі мікроданих щорічного опитування **Stack Overflow Developer Survey**. 

Головна мета дослідження — перетворити масштабний масив неструктурованих відповідей розробників на конкретні бізнес-інсайти щодо популярності технологій, трендів віддаленої роботи та ключових факторів, які впливають на рівень фінансової компенсації спеціалістів.

## 🛠 Інструменти та технології
* **Мова програмування:** Python
* **Основні бібліотеки:** Pandas (обробка, фільтрація, агрегація даних)
* **Середовище розробки:** Jupyter Notebook 

## 📊 Які завдання були виконані в ході аналізу:
1. **Валідація та очищення даних:** Оцінено загальний обсяг вибірки та повноту відповідей респондентів. Реалізовано очищення даних від пропущених значень (NaN).
2. **Статистичний аналіз досвіду:** Розраховано міри центральної тенденції (середнє, медіана, мода) для оцінки реального комерційного досвіду розробників.
3. **Аналіз зайнятості:** Ідентифіковано та підраховано частку спеціалістів, які працюють у форматі Remote (віддалено).
4. **Дослідження технологічного стеку:** За допомогою векторизованих методів обробки тексту обчислено реальний відсоток популярності мови Python (враховуючи множинні відповіді в анкетах) та проаналізовано її поширення серед різних вікових категорій.
5. **Аналіз освітніх трендів:** Визначено частку розробників, які обрали онлайн-курси як основний або додатковий шлях навчання.
6. **Географічний та індустріальний аналіз доходів:** Виконано групування даних (groupby) за країнами для розрахунку середньої та медіанної зарплати Python-фахівців. Виділено топ-індустрії з найвищим рівнем доходу для віддалених працівників у 75-му перцентилі.

## 🏆 Ключові результати проєкту
* **Обробка Big Data:** Опрацьовано та очищено масштабний масив даних обсягом у десятки тисяч анкет, успішно вирішено проблему пропущених значень та множинних відповідей у текстових полях без втрати продуктивності коду завдяки векторизації в Pandas замість циклів.
* **Аналітичні інсайти:** Виявлено ключові закономірності IT-ринку, визначено медіанну зарплатну вилку Python-розробників у розрізі різних країн та сформовано портрет високооплачуваного віддаленого працівника.
* **Автоматизація:** Створено готовий аналітичний скрипт, який автоматизує розрахунок метрик центральної тенденції та профілювання респондентів для майбутніх щорічних опитувань.

## 📁 Структура репозиторію
* `notebook.ipynb` — Jupyter-ноутбук із покроковим кодом аналізу та коментарями.
* `README.md` — опис проєкту (цей файл).
* `data/` — [Stack Overflow Developer Survey 2025 Data](https://github.com/StackExchange/Survey/tree/main/packages/archive/2025)



# Global IT Market & Python Ecosystem Investigation via Stack Overflow Data 🚀

## 📌 Project Description
This project is dedicated to a comprehensive Exploratory Data Analysis (EDA) of the global IT industry based on microdata from the annual **Stack Overflow Developer Survey**. 

The main goal of the research is to transform a large-scale array of unstructured developer responses into concrete business insights regarding technology popularity, remote work trends, and key factors that influence the level of financial compensation for specialists.

## 🛠 Tools & Technologies
* **Programming Language:** Python
* **Key Libraries:** Pandas (data processing, filtering, aggregation)
* **Development Environment:** Jupyter Notebook 

## 📊 Tasks Completed During the Analysis:
1. **Data Validation & Cleaning:** Evaluated the total sample size and completeness of respondents' answers. Implemented data cleaning from missing values (NaN).
2. **Statistical Experience Analysis:** Calculated measures of central tendency (mean, median, mode) to assess the real commercial experience of developers.
3. **Employment Analysis:** Identified and counted the share of specialists working in a Remote format.
4. **Tech Stack Research:** Calculated the actual popularity percentage of the Python language using vectorized text processing methods (taking into account multiple answers in questionnaires) and analyzed its distribution across different age categories.
5. **Educational Trends Analysis:** Determined the share of developers who chose online courses as a primary or additional learning path.
6. **Geographical & Industry Income Analysis:** Performed data grouping (groupby) by country to calculate the mean and median salary of Python specialists. Highlighted the top industries with the highest income level for remote workers in the 75th percentile.

## 🏆 Key Project Results
* **Big Data Processing:** Processed and cleaned a large-scale data array containing tens of thousands of questionnaires, successfully resolving the issue of missing values and multiple answers in text fields without losing code performance due to vectorization in Pandas instead of loops.
* **Analytical Insights:** Uncovered key patterns of the IT market, determined the median salary range of Python developers across different countries, and formed a profile of a high-earning remote worker.
* **Automation:** Created a ready-made analytical script that automates the calculation of central tendency metrics and profiling of respondents for future annual surveys.

## 📁 Repository Structure
* `notebook.ipynb` — Jupyter Notebook with step-by-step analysis code and comments.
* `README.md` — project description (this file).
* `data/` — [Stack Overflow Developer Survey 2025 Data](https://github.com/StackExchange/Survey/tree/main/packages/archive/2025)
