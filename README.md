# ai-sales-insight-llm-
stores excel file, process raw and never push sensitive real data
ai-sales-insight-llm/
│
├── data/
│   ├── raw/
│   │   └── sales_data.xlsx
│   ├── processed/
│   │   └── cleaned_sales.csv
│   └── sample/
│       └── sample_input.xlsx
│
├── notebooks/
│   └── eda.ipynb
│
├── src/
│   ├── __init__.py
│   │
│   ├── config.py
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── model.py
│   ├── llm_integration.py
│   ├── prompt_templates.py
│   ├── utils.py
│   │
│   └── pipeline.py
│
├── api/
│   ├── main.py
│   └── schemas.py
│
├── tests/
│   ├── test_preprocessing.py
│   └── test_pipeline.py
│
├── app/
│   └── streamlit_app.py
│
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── setup.py


