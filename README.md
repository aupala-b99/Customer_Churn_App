# 📊 Customer Churn Analysis App (Streamlit + Snowflake)

This project is a web-based interactive analytics dashboard built using **Streamlit** and powered by **Snowflake** data. It enables managers to explore customer churn based on various filters such as contract type and senior citizen status.

---

## 🧰 Tech Stack

- **Frontend & UI:** Streamlit
- **Data Source:** Snowflake table (`churn`)
- **Data Access:** Snowpark for Python
- **Visualization:** Seaborn & Matplotlib
- **Language:** Python

---
## 🚀 How to Run the App in Snowflake
1. **Login to Snowflake Snowsight**
2. Go to `Worksheets` → `+ Streamlit App`
3. Import Required Libraries

import streamlit as st
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from snowflake.snowpark.context import get_active_session

5. 


---
## 🖥 Features

- Interactive sidebar to filter by:
  - Contract Type
  - Senior Citizen Status
- Dynamic churn distribution visualization
- Live view of filtered customer data
- Built-in directly into Snowflake using Snowsight

---


