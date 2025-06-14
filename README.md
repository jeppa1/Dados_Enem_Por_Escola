# Dados_Enem_Por_Escola

# ENEM School Data Analysis Project 📊

This project focuses on the **structuring and exploratory analysis of Brazilian high school performance data from the ENEM (Exame Nacional do Ensino Médio) between 2005 and 2015. The dataset was restructured following technical coding standards to allow for statistical and visual analysis.

## 🔍 Key Features:
- **Data Structuring:** Raw data from INEP was restructured into a standardized format with variables renamed as Q1, Q2, ..., Q24.
- **Metadata Documentation:** A metadata worksheet was created to describe each variable, its type, and its operational coding.
- **Statistical Descriptive Analysis:** Mean, median, quartiles, standard deviation, and missing values were analyzed for quantitative variables like `Q18` (average score), `Q22` (approval rate), `Q23` (rejection rate), and `Q24` (dropout rate).
- **Exploratory Data Visualization:** Histograms, boxplots, and stacked bar charts were generated to explore patterns across school characteristics such as administrative dependency (`Q8`), school size (`Q10`), and location (`Q9`).

## 🧾 Variables:
Each variable was renamed according to the following code:
- `Q1`: Year (`NU_ANO`)
- `Q2`: School UF Code (`CO_UF_ESCOLA`)
- `Q3`: School UF Initial (`SG_UF_ESCOLA`)
- `Q8`: Administrative Dependency Type (1=Federal, 2=State, 3=Municipal, 4=Private)
- `Q9`: Location (1=Urban, 2=Rural)
- `Q10`: School Size (1=1–30 students, 2=31–60, 3=61–90, 4=>90 students)
- `Q18`: Average Total Score
- `Q22`: Approval Rate (%)
- `Q23`: Rejection Rate (%)
- `Q24`: Dropout Rate (%)

## 📊 Results:
- **Average total scores** show differences by management type, with private schools performing better on average.
- **Approval and dropout rates** also vary significantly across regions and school types.
- **School size vs. location** indicates that urban schools are more likely to be large institutions.

## 🛠️ Tools Used:
- Google Sheets (data structuring and documentation)
- Python (Pandas, GSpread, Matplotlib, Seaborn)
- Google Colab

This project follows best practices in data structuring, descriptive statistics, and data visualization, aligning with academic content on descriptive statistics, categorical variables, and data quality assurance.
"""

print(descricao_github)
