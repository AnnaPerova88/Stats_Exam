# Stats_Exam

# Решение задач по математике и статистике с использованием Python

Этот репозиторий содержит решения задач по математике, статистике и оптимизации, с использованием Python. Каждое решение включает подробные шаги, комментарии и выводы.

## Задание 4: Реализация алгоритма Наивного Байеса для классификации

**Описание задачи**:
- Даны данные о людях с наличием или отсутствием заболевания. Признаки включают:
  - **Age** — возрастная группа.
  - **Test** — результат теста на заболевание (позитивный или негативный).
  - **Status** — целевая переменная, указывающая на наличие или отсутствие заболевания (Infected или Not Infected).

**Цель**: Реализовать алгоритм Наивного Байеса для классификации, используя Python, и оценить качество полученного результата.

**Шаги решения**:
1. Преобразование категориальных признаков (Test, Age_Group, Status) в числовой формат.
2. Разделение данных на обучающую и тестовую выборки.
3. Реализация и обучение классификатора Наивного Байеса.
4. Оценка точности модели на тестовых данных.

**Решение**:
- Используется алгоритм Наивного Байеса для классификации.
- Точность модели была оценена с использованием метода разделения на обучающую и тестовую выборки, с расчетом метрики точности.

**Результаты**:
- **Точность модели**: модель Наивного Байеса продемонстрировала точность 66.67% на тестовой выборке.

---

## Используемые библиотеки

- `pandas` — для работы с данными.
- `scikit-learn` — для реализации алгоритма Наивного Байеса и оценки точности модели.

---

## Задание 5: Оптимизация функции методом Ньютона

**Описание задачи**:
- Дана функция:
  \[
  f(x) = x^4 + 3x^3 - 12x^2 + 7x - 2
  \]
- Необходимо найти экстремум функции методом Ньютона с начальной точкой \( x = 10 \) и точностью \( 0.0001 \).

**Решение**:
- Используется метод Ньютона для нахождения экстремума функции. Итерации продолжаются, пока разница между новым и старым значением \( x \) не станет меньше заданной точности.

**Результаты**:
- Итоговое значение \( x \), на котором функция достигает экстремума.
- Количество итераций до достижения заданной точности.

---

## Задание 6: Вероятность, математическое ожидание и дисперсия

**Описание задачи**:
- Дано распределение вероятностей для случайной величины, которая описывает количество полученных спам-писем за один день.
  
  Вероятности для количества писем:
  | Количество писем | Вероятность |
  |------------------|-------------|
  | 0                | 0.1         |
  | 1                | 0.3         |
  | 2                | 0.1         |
  | 3                | 0.25        |
  | 4                | 0.05        |
  | 5                | 0.1         |
  
**Задания**:
1. Найти вероятность получения 7 спам-писем.
2. Найти математическое ожидание для количества полученных писем.
3. Найти дисперсию для количества полученных писем.

**Решение**:
- Используем распределение вероятностей для расчета математического ожидания и дисперсии.

**Результаты**:
- Вероятность получения 7 спам-писем: 0.
- Математическое ожидание: 1.95.
- Дисперсия: 2.06725.

---

## Задание 7: Количество звонков в колл-центр

**Описание задачи**:
- В течение 8 часов рабочего дня в колл-центр поступает в среднем 16 звонков. Нужно найти вероятность того, что за 1 час поступит от 2 до 4 звонков.

**Решение**:
- Для решения задачи используется закон распределения Пуассона с параметром \( \lambda = 2 \) для одного часа. 

**Результаты**:
- Вероятность того, что за 1 час поступит от 2 до 4 звонков: 0.541 (округлено до 3 знаков).
