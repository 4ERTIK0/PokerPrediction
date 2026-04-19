# PokerPrediction
Модель машинного обучения для классификации покерных комбинаций на основе набора карт.
________________________________________
📌 Описание
Цель проекта — предсказать тип покерной руки (например, пара, флеш, стрит и т.д.) на основе 5 карт.
Каждая карта представлена двумя признаками:
•	Suit (масть)
•	Rank (значение)
Итого:
•	10 входных признаков (5 карт × 2)
•	1 целевая переменная — тип комбинации
________________________________________
📂 Структура проекта
003_Poker_Hand_Prediction/
│
├── 003_Poker_Hand_Prediction.ipynb   # Основной ноутбук

├── data/

│   ├── poker_hand_test.data          # Тестовый датасет

│   ├── poker_hand_train_true.data    # Обучающий датасет (raw)

│   ├── poker_hand_train_true.csv     # Обучающий датасет (CSV)

│   └── test                          # Дополнительные данные
________________________________________
⚙️ Технологии
•	Python 3
•	Pandas
•	Matplotlib
•	Jupyter Notebook
________________________________________
🚀 Pipeline проекта
•	Загрузка данных
•	Предобработка
•	Переименование признаков
•	Анализ распределения классов
•	Разделение на X / y
•	(Опционально) обучение модели
•	Оценка результатов


📌 Description
The goal of this project is to predict the type of a poker hand (e.g., pair, flush, straight) based on 5 given cards.
Each card is represented by two features:
•	Suit
•	Rank
In total:
•	10 input features (5 cards × 2)
•	1 target variable — hand type
________________________________________
📂 Project Structure
003_Poker_Hand_Prediction/
│
├── 003_Poker_Hand_Prediction.ipynb   # Main notebook

├── data/

│   ├── poker_hand_test.data          # Test dataset

│   ├── poker_hand_train_true.data    # Training dataset (raw)

│   ├── poker_hand_train_true.csv     # Training dataset (CSV)

│   └── test                          # Additional data
________________________________________
⚙️ Technologies
•	Python 3
•	Pandas
•	Matplotlib
•	Jupyter Notebook
________________________________________
🚀 Project Pipeline
•	Data loading
•	Data preprocessing
•	Feature renaming
•	Exploratory data analysis (EDA)
•	Splitting into features (X) and target (y)
•	(Optional) model training
•	Model evaluation

