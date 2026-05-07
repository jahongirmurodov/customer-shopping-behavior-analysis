# Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using Python, PostgreSQL, SQL, and Power BI.

The goal of the project is to identify customer purchasing patterns, product preferences, subscription behavior, and business opportunities through data analysis and visualization.

---

## 📊 Project Overview

The analysis is based on transactional retail data containing approximately 3,900 purchases across multiple product categories.

The project includes:
- Data cleaning and preprocessing in Python
- Business analysis using SQL and PostgreSQL
- Interactive dashboard creation in Power BI
- Business recommendations based on analytical findings

---

## 🗂 Dataset Information

### Dataset Characteristics
- Rows: ~3,900
- Columns: 18

### Main Features
- Customer demographics
- Purchase information
- Product categories
- Discounts and promotions
- Customer reviews
- Shipping methods
- Subscription status

### Data Quality
- Missing values detected in `review_rating`
- Missing values handled using median imputation by category

---

## ⚙️ Data Processing (Python)

Data preprocessing and EDA were performed using Python.

### Main Steps
- Data loading with Pandas
- Exploratory analysis (`info`, `describe`)
- Missing value handling
- Column renaming (snake_case standardization)
- Feature engineering
- Data consistency checks

### Feature Engineering
Created:
- `age_group`
- `purchase_frequency_days`

---

## 🗄 Database & SQL Analysis

The cleaned dataset was loaded into PostgreSQL for analytical queries.

### Business Analysis Performed
- Revenue analysis by gender
- High-spending discount users
- Top-rated products
- Shipping type comparison
- Subscriber vs non-subscriber analysis
- Discount-dependent products
- Customer segmentation
- Top products by category
- Repeat buyer behavior
- Revenue by age group

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize:
- Revenue trends
- Customer segments
- Product performance
- Subscription behavior
- Purchase distribution
- Shipping insights

---

## 🎯 Business Recommendations

Based on the analysis:
- Improve customer loyalty programs
- Increase subscription engagement
- Optimize discount strategies
- Focus marketing on high-value customer groups
- Promote top-rated products

---

## 🛠 Technologies Used

- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

## 📌 Notes

This project demonstrates a full analytics workflow:
- Data Cleaning
- Exploratory Data Analysis
- SQL Business Analytics
- Dashboard Visualization
- Business Decision Support


---------------------------------------------------------------

# Анализ покупательского поведения клиентов

Данный проект посвящён анализу покупательского поведения с использованием Python, PostgreSQL, SQL и Power BI.

Цель проекта — выявить закономерности покупок, предпочтения клиентов и бизнес-инсайты на основе транзакционных данных.

---

## 📊 Обзор проекта

Проект основан на анализе около 3900 покупок из различных товарных категорий.

В проект входят:
- Очистка и подготовка данных в Python
- Бизнес-анализ с использованием SQL
- Визуализация данных в Power BI
- Формирование бизнес-рекомендаций

---

## 🗂 Информация о датасете

### Характеристики
- Строк: ~3900
- Колонок: 18

### Основные признаки
- Демография клиентов
- Информация о покупках
- Категории товаров
- Скидки и промокоды
- Отзывы
- Типы доставки
- Подписка клиентов

### Качество данных
- Были обнаружены пропуски в `review_rating`
- Пропуски обработаны через median imputation по категориям

---

## ⚙️ Обработка данных (Python)

EDA и preprocessing выполнены в Python.

### Основные этапы
- Загрузка данных через Pandas
- Исследование структуры данных
- Обработка пропущенных значений
- Стандартизация названий колонок
- Feature Engineering
- Проверка консистентности данных

### Созданные признаки
- `age_group`
- `purchase_frequency_days`

---

## 🗄 SQL и PostgreSQL

Подготовленные данные были загружены в PostgreSQL для выполнения бизнес-аналитики.

### Выполненный анализ
- Выручка по полу
- Клиенты с высокими расходами и скидками
- Топ товаров по рейтингу
- Анализ типов доставки
- Сравнение подписчиков и обычных клиентов
- Товары, зависящие от скидок
- Сегментация клиентов
- Топ товаров по категориям
- Поведение repeat buyers
- Выручка по возрастным группам

---

## 📈 Dashboard в Power BI

Создан интерактивный дашборд для визуализации:
- Выручки
- Поведения клиентов
- Эффективности товаров
- Подписок
- Покупательских паттернов
- Типов доставки

---

## 🎯 Бизнес-рекомендации

По итогам анализа предложены:
- Улучшение loyalty-программ
- Развитие подписок
- Оптимизация скидочной политики
- Таргетинг высокодоходных клиентов
- Продвижение лучших товаров

---

## 🛠 Используемые технологии

- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

## 📌 Примечание

Проект демонстрирует полный аналитический pipeline:
- Очистка данных
- EDA
- SQL аналитика
- BI визуализация
- Поддержка бизнес-решений



