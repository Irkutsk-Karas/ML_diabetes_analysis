# Diabetes Risk Prediction with Random Forest

Этот проект представляет собой модель машинного обучения для предсказания риска возникновения диабета, построенную с помощью алгоритма Random Forest.

## Описание

Проект использует набор данных о диабете для обучения модели классификации, которая предсказывает вероятность развития диабета у пациентов на основе медицинских показателей.

## Функциональность

- Загрузка и предобработка данных
- Обучение модели Random Forest Classifier
- Оценка точности модели
- Визуализация деревьев решений
- Построение матрицы ошибок (confusion matrix)
- Анализ важности признаков

## Установка и запуск

1. Клонируйте репозиторий:
```bash
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
```

2. Установите необходимые зависимости:
```bash
pip install -r requirements.txt
```

3. Запустите скрипт:
```bash
python diabetes_prediction.py
```

## Требования

- Python 3.7+
- pandas
- scikit-learn
- matplotlib
- seaborn

Файл `requirements.txt` должен содержать:
```
pandas>=1.3.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
```

## Структура проекта

```
diabetes-prediction/
│
├── diabetes_prediction.py    # Основной скрипт
├── diabetes.csv              # Набор данных (должен быть добавлен вручную)
├── requirements.txt          # Зависимости
└── README.md                 # Этот файл
```

## Набор данных

Проект использует файл `diabetes.csv`, который должен содержать следующие признаки:
- Pregnancies: количество беременностей
- Glucose: уровень глюкозы
- BloodPressure: артериальное давление
- SkinThickness: толщина кожи
- Insulin: уровень инсулина
- BMI: индекс массы тела
- DiabetesPedigreeFunction: функция наследственности диабета
- Age: возраст
- Outcome: наличие диабета (0 - нет, 1 - есть)

## Результаты

Модель выводит:
- Accuracy score (точность предсказаний)
- Визуализацию первых 5 деревьев решений
- Матрицу ошибок
- График важности признаков

Ссылка на проект: [https://github.com/your-username/diabetes-prediction](https://github.com/your-username/diabetes-prediction)
