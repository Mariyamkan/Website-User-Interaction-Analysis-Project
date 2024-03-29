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
## Резюмирование
<h3> Проделанная работа </h3>
<h4> В ходе выполнения задания были совершены следующие действия: </h4>
    - Загрузили нужные библиотеки и данные <br>   
    - Проверили данные на полноту, на точность данных и на дубликаты <br>
    - Убрали дубликаты и лишние данные в виде экспериментальных логов и туториал логов <br>
    - Отразили воронку продаж
    
<h4> Найденная проблема: </h4>
Было обнаружено 413 дубликатов в данных, что означает выстроенная логика/система логирования имеет изъяны и периодически совершает лишние записи.

<h3> Дополнительная работа </h3>
Выстроили воронку продаж. В целом было совершено 157468 действий по сайту (убрали экспериментальные и туториал логи). Проанализированные данные воронки продаж представляют следующую картину:

- Главный экран появления (MainScreenAppear): В этом этапе присутствовало 77,991 действие.

- Просмотр предложений (OffersScreenAppear): После главного экрана предложений, 30,254 пользователей приступили к просмотру предложений.

- Добавление товаров в корзину (CartScreenAppear): Зафиксировано 27,389 действий по добавлению товаров в корзину.

- Успешная страница оплаты (PaymentScreenSuccessful): Отмечено 22,071 успешных оплат.

Примерно 80.53% пользователей, которые посмотрели страницу корзины, успешно завершили покупку. Этот показатель отражает конверсию на этом этапе воронки продаж.
    
