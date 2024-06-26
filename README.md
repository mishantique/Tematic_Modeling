
# Тематическое Моделирование с Использованием NLP

## Описание

Данный блокнот Jupyter (`Tematic_modeling.ipynb`) представляет собой реализацию проекта по тематическому моделированию текстовых данных. Проект включает в себя различные этапы работы с текстом, начиная от предобработки данных и заканчивая обучением моделей машинного обучения для классификации текста и анализа тематик.

## Цели проекта

- Исследовать набор данных на русском языке.
- Применить методы предобработки текста для подготовки данных к анализу.
- Использовать различные подходы векторизации текста: TF-IDF, Bag of Words, Word2Vec.
- Обучить модель для классификации текстов по тематикам.
- Проанализировать полученные тематики и классификацию текстов.

## Структура проекта

1. **Предобработка данных**: очистка текста, лемматизация, удаление стоп-слов.
2. **Векторизация текста**: применение TF-IDF, Bag of Words и Word2Vec для преобразования текстов в числовые векторы.
3. **Классификация текстов**: обучение модели логистической регрессии на основе векторизованных данных.
4. **Анализ результатов**: интерпретация тематик и оценка качества модели с помощью метрик классификации.

## Инструкции по использованию

Для работы с проектом необходимо иметь установленными следующие библиотеки Python: `numpy`, `pandas`, `matplotlib`, `sklearn`, `gensim`, `nltk`.

1. Откройте блокнот `Tematic_modeling.ipynb` в среде, поддерживающей выполнение Jupyter блокнотов (например, JupyterLab, Google Colab).
2. Подгрузите данные для анализа
3. Выполните ячейки по порядку, следуя инструкциям в комментариях.
4. Для адаптации проекта под свои задачи, модифицируйте параметры предобработки данных, выбор методов векторизации и настройки моделей.


