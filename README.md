# Homework 7: Time Series & JSONB in PostgreSQL

Домашнє завдання з курсу Relational Databases. Робота з часовими рядами, JSONB та індексами PostgreSQL для підготовки ML-ознак.

## Dataset

**NYC Yellow Taxi Trip Records**
- Джерело: [NYC TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- Файл: `yellow_tripdata_2024-03.parquet`
- Дані про поїздки таксі за березень 2024 року.

**Synthetic Event Log**
- 50 000 синтетичних подій.
- 5 типів подій із різною структурою JSONB.

## Technologies

- Python, Pandas, SQLAlchemy
- PostgreSQL (pgserver)
- Google Colab

## How to Run

1. Відкрити `Lata_goit_rdb_hw_07.ipynb` у Google Colab.
2. Обрати **Runtime → Restart session and run all**.
3. Notebook автоматично встановлює залежності, запускає PostgreSQL, завантажує дані та виконує SQL-запити.

## Project Structure

```text
├── Lata_goit_rdb_hw_07.ipynb
└── README.md
```

## Contents

- Time-series feature engineering: lag, rolling, expanding.
- JSONB event-log та JSONPath.
- GIN і B-tree індекси.
- Порівняння JSONB та normalized tables.
- EXPLAIN ANALYZE та Reflection.
