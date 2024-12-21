# Студент группы М8О-408Б-21 Стенин Константин Алексеевич

В этом репозитории лежат выполненные лабораторные работы 1-5 по курсу "Методы, средства и технологии мультимедиа"

# Условие

**1. Выбор начальных условий**

a. Выбор набора данных для задачи классификации  
   Уникальный для каждого студента.  
   Обоснование: реальная практическая задача.  

b. Выбор набора данных для задачи регрессии  
   Уникальный для каждого студента.  
   Обоснование: реальная практическая задача.  

c. Выбор метрик качества и обоснование их выбора  

**2. Создание бейзлайна и оценка качества**

a. Обучение моделей из sklearn для классификации и регрессии на выбранных наборах данных  

b. Оценка качества моделей по выбранным метрикам на выбранных наборах данных  

**3. Улучшение бейзлайна**

a. Формулирование гипотез  
   - Препроцессинг данных  
   - Визуализация данных  
   - Формирование новых признаков  
   - Подбор гиперпараметров на кросс-валидации  

b. Проверка гипотез  

c. Формирование улучшенного бейзлайна по результатам проверки гипотез  

d. Обучение моделей с улучшенным бейзлайном для классификации и регрессии  

e. Оценка качества моделей с улучшенным бейзлайном по выбранным метрикам  

f. Сравнение результатов моделей с улучшенным бейзлайном с результатами из пункта 2  

g. Сделать выводы  

**4. Имплементация алгоритма машинного обучения**

a. Самостоятельная имплементация алгоритмов машинного обучения для классификации и регрессии  

b. Обучение имплементированных моделей на выбранных наборах данных  

c. Оценка качества имплементированных моделей по выбранным метрикам  

d. Сравнение результатов имплементированных моделей с результатами из пункта 2  

e. Добавление техник из улучшенного бейзлайна (пункт 3)  

f. Обучение моделей для классификации и регрессии с учетом улучшений  

g. Оценка качества моделей с улучшенным бейзлайном  

h. Сравнение результатов моделей с результатами из пункта 3  

i. Сделать выводы  


# Подведение итогов

В следующей таблице в ячейках, относящихся к классифкации я буду отображать **accuracy**; в ячейках, относящихся к регрессии я буду отображать **RMSE**

*Метрика качества на тестовом наборе данных*
<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация (F1)</td>
        <td>0.8738</td>
        <td>0.9143</td>
        <td>0.9057</td>
    </tr>
    <tr>
        <td>регрессия (R2)</td>
        <td>0.8018</td>
        <td>0.8018</td>
        <td>0.7992</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация (F1)</td>
        <td>0.9020</td>
        <td>0.8952</td>
        <td>0.8727</td>
    </tr>
    <tr>
        <td>регрессия (R2)</td>
        <td>0.7822</td>
        <td>0.8264</td>
        <td>0.7914</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация (F1)</td>
        <td>0.9000</td>
        <td>0.9109</td>
        <td>0.8247</td>
    </tr>
    <tr>
        <td>регрессия (R2)</td>
        <td>0.8903</td>
        <td>0.7744</td>
        <td>0.6980</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация (F1)</td>
        <td>0.9020</td>
        <td>0.9412</td>
        <td>0.9232</td>
    </tr>
    <tr>
        <td>регрессия (R2)</td>
        <td>0.8714</td>
        <td>0.8966</td>
        <td>0.8804</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация (F1)</td>
        <td>0.9020</td>
        <td>0.9412</td>
        <td>0.4399</td>
    </tr>
    <tr>
        <td>регрессия (R2)</td>
        <td>0.8578</td>
        <td>0.8724</td>
        <td>0.8030</td>
    </tr>
</table>