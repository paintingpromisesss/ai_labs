# ai_labs

Пять лабораторных работ по машинному обучению. В каждой исследованы классификация и регрессия: библиотечный бейзлайн, проверка гипотез на кросс-валидации, улучшенная конфигурация и реализация алгоритма с нуля в двух конфигурациях.

| Работа | Ноутбук |
| --- | --- |
| 1. Метод ближайших соседей | [lab-1.ipynb](https://github.com/paintingpromisesss/ai_labs/blob/lab-1/lab-1.ipynb) |
| 2. Логистическая и линейная регрессии | [lab-2.ipynb](https://github.com/paintingpromisesss/ai_labs/blob/lab-2/lab-2.ipynb) |
| 3. Решающее дерево | [lab-3.ipynb](https://github.com/paintingpromisesss/ai_labs/blob/lab-3/lab-3.ipynb) |
| 4. Случайный лес | [lab-4.ipynb](https://github.com/paintingpromisesss/ai_labs/blob/lab-4/lab-4.ipynb) |
| 5. Градиентный бустинг | [lab-5.ipynb](https://github.com/paintingpromisesss/ai_labs/blob/lab-5/lab-5.ipynb) |
| Сравнение всех работ | [comparison.ipynb](comparison.ipynb) |

## Датасеты

- Классификация — [Optical Recognition of Handwritten Digits, выборка sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html).
- Регрессия — [Diabetes, Efron и соавт.](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html).

Данные поставляются вместе со scikit-learn. Разбиение 80/20 фиксировано для всех работ, подбор настроек проводится на обучающей части. JSON-файлы в `results/` содержат метрики, из которых строится итоговое сравнение.

## Запуск

Python 3.11 или новее. Из корня нужной ветки:

```sh
python -m pip install -r requirements.txt
python -m jupyter lab
```

Откройте ноутбук и выполните ячейки сверху вниз. Ноутбуки уже содержат результаты выполнения. Итоговый ноутбук и входные JSON-файлы находятся в `main`.
