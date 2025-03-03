# Анализ продаж игр для интернет-магазина «Стримчик»

## Описание проекта

В рамках этого проекта проведён анализ исторических данных о продажах компьютерных игр для интернет-магазина «Стримчик». Задача заключалась в выявлении закономерностей, определяющих успешность игр, для более эффективного планирования рекламных кампаний и прогнозирования продаж на 2017 год. Проект включает исследовательский анализ данных, создание визуализаций, проверку гипотез и составление портретов пользователей в разных регионах.

Данные предоставлены до 2016 года и включают информацию о продажах игр в разных регионах, их жанрах, платформе, а также оценках критиков и пользователей.

## Структура проекта

Проект состоит из нескольких шагов, каждый из которых выполняет конкретную задачу:

1. **Подготовка данных**: очистка и трансформация данных, замена типов данных, обработка пропусков.
2. **Исследовательский анализ данных**: анализ динамики продаж, выбор платформ, построение распределений.
3. **Проверка гипотез**: тестирование гипотез с использованием статистических методов.
4. **Составление портретов пользователей**: определение популярных платформ и жанров в разных регионах.
5. **Выводы**: создание выводов и рекомендаций для планирования рекламных кампаний.

## Данные

Данные о продажах игр до 2016 года содержат следующие столбцы:

- **Name** — название игры
- **Platform** — платформа (например, Xbox, PlayStation)
- **Year_of_Release** — год выпуска
- **Genre** — жанр игры
- **NA_sales** — продажи в Северной Америке (миллионы копий)
- **EU_sales** — продажи в Европе (миллионы копий)
- **JP_sales** — продажи в Японии (миллионы копий)
- **Other_sales** — продажи в других странах (миллионы копий)
- **Critic_Score** — оценка критиков (максимум 100)
- **User_Score** — оценка пользователей (максимум 10)
- **Rating** — рейтинг ESRB (возрастной рейтинг игры)

## Стек технологий

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Jupyter Notebook** для выполнения кода и документации

## Шаги выполнения

### 1. Открытие и изучение данных
На этом шаге загружаются и анализируются данные. Проводится первичный осмотр структуры датасета, изучаются пропуски и типы данных.

### 2. Подготовка данных
Включает очистку данных, преобразование столбцов (например, изменение названий столбцов в нижний регистр), обработку пропусков и изменение типов данных.

### 3. Исследовательский анализ
Анализируются тенденции продаж по годам, платформам и жанрам. Строятся графики, чтобы понять, как меняются предпочтения пользователей.

### 4. Составление портретов пользователей
Проводится сегментация пользователей по регионам (Северная Америка, Европа, Япония) и анализируются предпочтения по платформам, жанрам и рейтингу ESRB.

### 5. Проверка гипотез
Проверяются статистические гипотезы с использованием тестов, таких как t-test или ANOVA, чтобы понять, существуют ли значимые различия между оценками разных платформ и жанров.

### 6. Выводы
Основные выводы из анализа, рекомендации для планирования рекламных кампаний и прогнозирования успешности игр в 2017 году.


