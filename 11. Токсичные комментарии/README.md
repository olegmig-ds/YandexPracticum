
#  Поиск токсичных комментариев.
## Цель 
Построить модель бинарной классификации текстовых комментариев на позитивные и негативные. Модель должна стать инструментом детекции токсичных комментариев для их последующей модерации.
## Описание проекта
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 
## Описание данных
* Данные находятся в файле `toxic_comments.csv`. Скачать датасет. 
* Столбец `text` в нём содержит текст комментария, а `toxic` — целевой признак.
