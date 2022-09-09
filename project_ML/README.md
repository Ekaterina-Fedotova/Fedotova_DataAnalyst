# Проект Прогнозирование оттока клиентов фитнес центра
-----------
### Описание данных

Данные клиента за предыдущий до проверки факта оттока месяц
* `gender` — пол;
* `Near_Location` — проживание или работа в районе, где находится фитнес-центр;
* `Partner` — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента);
* `Promo_friends` — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
* `Phone` — наличие контактного телефона;
* `Age` — возраст;
* `Lifetime` — время с момента первого обращения в фитнес-центр (в месяцах).

Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента
* `Сontract_period` — длительность текущего действующего абонемента (месяц, 6 месяцев, год);
* `Month_to_end_contract` — срок до окончания текущего действующего абонемента (в месяцах);
* `Group_visits` — факт посещения групповых занятий;
* `Avg_class_frequency_total` — средняя частота посещений в неделю за все время с начала действия абонемента;
* `Avg_class_frequency_current_month` — средняя частота посещений в неделю за предыдущий месяц;
* `Avg_additional_charges_total` — суммарная выручка от других услуг фитнес-центра: кафе, спорттовары, косметический и массажный салон.
* `Churn` — факт оттока в текущем месяце.
------------
### Задачи

Сеть фитнес-центров «Культурист-датасаентист» хочет спрогнозировать отток клиенов и разработать план по удержанию их. 
Необходимо спроектировать модель, которая будет придсказывать вероятность оттока каждого клиента. 
Выделить признаки, наиболее сильно влияющие на отток. Сформировать группы клиентов, и повысить качество работы с ними.

-----------
### Библиотеки для выполнения проекта

Pandas, Seaborn, Itertools, Sklearn.preprocessing, Sklearn.model_selection, Sklearn.linear_model,  
Sklearn.ensemble, Sklearn.cluster, Scipy.cluster.hierarchy, Sklearn.metrics, Matplotlib.pyplot