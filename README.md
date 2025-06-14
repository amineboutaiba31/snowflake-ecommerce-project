# snowflake-ecommerce-project
Complete end-to-end e-commerce analytics project using Snowflake, Snowpark Python and Power BI based on the Brazilian Olist dataset.


# 📦 Snowflake E-commerce Data Pipeline & Dashboard (Brazilian Olist Dataset)

Projet complet d’analyse e-commerce avec **Snowflake, Snowpark Python, Machine Learning** et **Power BI**.

---

## 🎯 Objectif

Analyser les ventes en ligne d’un e-commerce brésilien, prévoir les performances des produits, visualiser les tendances, et prendre des décisions basées sur les données grâce à une architecture cloud moderne.

---

## 🛠️ Technologies utilisées

- **Snowflake** – Data warehouse cloud
- **Snowpark (Python)** – Nettoyage, transformation, ML
- **Kaggle Dataset** – [Brazilian E-commerce Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Power BI** – Dashboards interactifs
- **GitHub** – Collaboration & versionnage

---

## 📁 Structure du projet

```plaintext
snowflake-ecommerce-project/
│
├── sql_scripts/
│   ├── create_warehouse.sql
│   ├── create_database_schema.sql
│   ├── create_tables.sql
│   ├── stage_and_copy.sql
│   └── create_views.sql
│
├── snowpark_python/
│   ├── clean_data.py
│   ├── predict_sales.py
│   └── requirements.txt
│
├── dashboards/
│   ├── dashboard_meilleurs_produits.pbix
│   ├── ventes_par_regions.pbix
│   └── screenshots/
│       ├── dashboard1.png
│       └── dashboard2.png
│
├── .gitignore
└── README.md
