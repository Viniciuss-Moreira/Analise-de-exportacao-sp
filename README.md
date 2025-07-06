[🇧🇷 Ver em Português](./README.pt-br.md)
---

# Export-Analysis-SP
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Pandas](https://img.shields.io/badge/Pandas-333333?style=flat&logo=pandas)](https://pandas.pydata.org)
---
**Colab link:** [**➡️ Colab notebook link**](https://colab.research.google.com/drive/1KfUo9tfXb2trnxrNUjuyHKOnOI3fyW_b?usp=sharing)
---
This notebook is part of the integrative project at Fatec, which consists of developing a web application to dynamically visualize export data from all municipalities in the state of São Paulo.

![App Demo](./img/demo.gif)
---
## 📖 Notebook Description

This notebook scrapes data from public files provided by the federal government (.csv) using the Pandas library, processes and formats this data, and then displays it in dynamic charts using the Numpy and Matplotlib libraries. The fictitious client can filter export data by year, municipality, value per Kilo or FOB, view the top 5 exporting municipalities in the state, and even compare municipalities with each other.

---

## 🛠️ Notebook Workflow and Features
1. **Data Processing:** The data extracted from the .csv files is formatted into tables that will later be used to generate interactive charts.
2. **Chart Creation:** The formatted dataframe is transformed into clickable charts to allow filtering by specific topics, turning raw data into valuable insights.

---

## 🚀 Tech Stack

**Data Science:** Python, Numpy, Matplotlib, Pandas
---
## 🔮 Future Implementations

**Relational Database:** Addition of a database to store the data and enable SQL-based queries.

---
**Automation Scripts:** Python scripts to automate the inclusion of new information published on the government website into the interactive chart.
