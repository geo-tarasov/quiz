# Тест с вариантами ответа для американской компании
## Задача
Сверстать и сделать активным тест из 15 вопросов по прототипу в фигме. Кроме теста, нужно было сверстать шкалы прогресса и передавать результаты тестирования на страницу с результатами. 

## Решение
Изначально дизайн-макета не было и при создании теста я ориентировался на другой тест для примера https://rocketfueluniversity.com/quiz/crystallizer-quiz-hs-norandom-privateapp.php

После создания дизайна появилось еще одно требование - после прохождения теста, перед страницей результатов нужно собирать email и другие данные, которые понадобятся для рассылок.

Компания использует свой конструктор сайтов с блочной структурой, поэтому я адаптировал код и сделал квиз отдельным блоком, а форму для данных пользователя взял стандартную. Видимостью блоков управлял с помощью JS-скрипта: когда квиз был пройден, блок с квизом скрывался, а блок с формой становился активным. При этом, в форму были добавлены скрытые поля, которые сохраняли результаты теста в карточке клиента.
