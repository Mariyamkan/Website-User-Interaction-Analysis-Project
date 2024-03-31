# Website User Interaction Study
## Introduction

In this project, we will analyze website page data to identify potential issues that may affect the user experience and website performance. We will consider various parameters and metrics to form an understanding of the website's current state.

## Data Description

The data is a table where each row represents information about a user's interaction with the website.

- EventName - event name;
- DeviceIDHash - unique user identifier;
- EventTimestamp - event time;
- ExpId - experiment number: 246 and 247 are control groups, and 248 is the experimental group.

EventName represents the events or actions that users perform on the website or mobile application. In the context of website or application data analysis, these events have the following meanings:

- MainScreenAppear - User opens the main screen.
- PaymentScreenSuccessful - User successfully makes a payment.
- CartScreenAppear - User views the shopping cart.
- OffersScreenAppear - User sees offers or promotions.
- Tutorial - User views the tutorial.

## Conclusion

Based on the project's objective of identifying potential website issues, we analyzed data from two control groups (ExpId 246 and 247) and excluded the experimental group (ExpId 248). The analysis aimed to determine whether any deviations or inconsistencies in user behavior could signal potential website problems.

During the data analysis, we detected 413 duplicate events. This may indicate some technical issues or anomalies in the process of registering user interaction events on the website. However, despite this number of duplicates, we did not find any significant deviations in key metrics or user behavior, indicating no major problems with the website's functionality. It is recommended to further investigate the nature and causes of the duplicates in the future to ensure data correctness and reliability for future analytical tasks.

One important aspect we focused on during the analysis was user conversion at different stages of the sales funnel.

Approximately 80.53% of users who viewed the cart page (CartScreenAppear) successfully completed the purchase on the payment page (PaymentScreenSuccessful). This conversion rate is a key performance indicator for the website, as it allows us to assess how successfully users complete the entire purchase process after adding items to their cart. Thus, our analysis confirmed that the website has a high conversion rate at the checkout stage, which is a positive indicator of its effectiveness.


# Исследование пользовательского взаимодействия с веб-сайтом
## Введение

В этом проекте мы проведем анализ данных по страницам веб-сайта с целью выявления возможных проблем, которые могут влиять на пользовательский опыт и эффективность веб-сайта. Для анализа мы рассмотрим различные параметры и метрики, чтобы сформировать представление о текущем состоянии сайта.
## Описание данных

Данные представляют собой таблицу, где каждая строка представляет собой информацию о взаимодействии пользователя с веб-сайтом. 
- EventName — название события;
- DeviceIDHash — уникальный идентификатор пользователя;
- EventTimestamp — время события;
- ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

EventName представляет собой события или действия, которые пользователи выполняют на веб-сайте или в мобильном приложении. В контексте анализа данных о веб-сайте или приложении, эти события имеют следующее значение:

- MainScreenAppear - Пользователь открывает главный экран.
- PaymentScreenSuccessful - Пользователь успешно совершает платеж.
- CartScreenAppear - Пользователь просматривает корзину с товарами.
- OffersScreenAppear - Пользователь видит предложения или акции.
- Tutorial - Пользователь просматривает обучающее руководство.
  
## Вывод

Исходя из поставленной задачи проекта, которая заключалась в выявлении потенциальных проблем на веб-сайте, мы провели анализ данных двух контрольных групп (ExpId 246 и 247) и исключили из рассмотрения экспериментальную группу (ExpId 248). Целью анализа было определить, существуют ли какие-либо отклонения или несоответствия в поведении пользователей, которые могли бы сигнализировать о возможных проблемах на сайте.

В процессе анализа данных было выявлено наличие 413 дубликатов. Это может свидетельствовать о некоторых технических проблемах или аномалиях в процессе регистрации событий пользовательского взаимодействия на сайте. Однако, несмотря на это количество дубликатов, мы не обнаружили существенных отклонений в ключевых метриках или поведении пользователей, что указывает на отсутствие серьезных проблем с функциональностью сайта. В дальнейшем рекомендуется более детально изучить характер и причины возникновения дубликатов, чтобы гарантировать корректность и достоверность данных для будущих аналитических задач.

Одним из важных аспектов, на который мы обратили внимание в ходе анализа, была конверсия пользователей на различных этапах воронки продаж. 

Примерно 80.53% пользователей, которые просмотрели страницу корзины (CartScreenAppear), успешно завершили покупку на странице оплаты (PaymentScreenSuccessful). Этот показатель конверсии является важным показателем эффективности сайта, поскольку он позволяет нам оценить, насколько успешно пользователи проходят через весь процесс покупки после того, как добавили товары в корзину. Таким образом, наш анализ подтвердил, что веб-сайт имеет высокую конверсию на этапе завершения покупки, что является положительным показателем его эффективности.
