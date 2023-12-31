# PROJECT-4. Classification of bank clients
ОСНОВНЫЕ ЗАДАЧИ:
- Исследовать данные, вычислить метрики и создать визуализации.
- Выявить характерные черты для потенциальных клиентов, чтобы чётко очертить целевую аудиторию и увеличить прибыль банка.
- Повысить качество прогноза.

## Оглавление  
[1. Первичная обработка данных](.README.md#Описание-проекта)  
[2. Разведывательный анализ данных (EDA)](.README.md#Какой-кейс-решаем)  
[3. Отбор и преобразование признаков](.README.md#Краткая-информация-о-данных)  
[4. Решение задачи классификации: логистическая регрессия и решающие деревья](.README.md#Этапы-работы-над-проектом)  
[5. Решение задачи классификации](.README.md#Результат)    
[6. Выводы](.README.md#Выводы)   
## *Данные о клиентах банка:*  

- age (возраст);
- job (сфера занятости);
- marital (семейное положение);
- education (уровень образования);
- default (имеется ли просроченный кредит);
- housing (имеется ли кредит на жильё);
- loan (имеется ли кредит на личные нужды);
- balance (баланс).
  
## *Данные, связанные с последним контактом в контексте текущей маркетинговой кампании:*

- contact (тип контакта с клиентом);
- month (месяц, в котором был последний контакт);
- day (день, в который был последний контакт);
- duration (продолжительность контакта в секундах).
## *Прочие признаки:*

- campaign (количество контактов с этим клиентом в течение текущей кампании);
- pdays (количество пропущенных дней с момента последней маркетинговой кампании до контакта в текущей кампании);
- previous (количество контактов до текущей кампании)
- poutcome (результат прошлой маркетинговой кампании).
- *deposit* - целевая переменная, которая определяет, согласится ли клиент открыть депозит в банке.

Проект будет состоять из пяти частей:

### 1 Первичная обработка данных

В рамках этой части вам предстоит обработать пропуски и выбросы в данных. Это необходимо для дальнейшей работы с ними.

### 2 Разведывательный анализ данных (EDA)

Вам необходимо будет исследовать данные, нащупать первые закономерности и выдвинуть гипотезы.

### 3 Отбор и преобразование признаков

На этом этапе вы перекодируете и преобразуете данные таким образом, чтобы их можно было использовать при решении задачи классификации. Если на первом этапе вы лишь избавите данные от ненужных артефактов, то на этом шаге совершите действия, более важные для подготовки данных к задаче классификации, уже понимая их структуру.

### 4 Решение задачи классификации: логистическая регрессия и решающие деревья

На данном этапе вы построите свою первую прогностическую модель и оцените её качество. Вы научитесь подбирать оптимальные параметры модели для того, чтобы получить наилучший результат для конкретного алгоритма.

### 5 Решение задачи классификации: ансамбли моделей и построение прогноза

На заключительном этапе вы сможете доработать своё предсказание с использованием более сложных алгоритмов и оценить, с помощью какой модели возможно сделать более качественные прогнозы.
