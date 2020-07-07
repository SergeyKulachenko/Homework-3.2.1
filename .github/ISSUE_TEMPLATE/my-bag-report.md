---
name: My Bag report
about: Описание проблемы (Бага)
title: ''
labels: bug
assignees: ''

---

### Описание
При введении  номера карты Diners Club - International в код Credit Card Number Validator получаем Result is FAIL
Источник номеров карт [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)
### Шаги по воспроизведению

1. Открываем код Credit Card Number Validator 
2. Вводим валидный номер  карты Diners Club - International (например - 36310457907419)
3. Запускаем

### Ожидаемый результат
Result is OK
### Фактический результат
Result is FAIL
### Программное окружение
Windows 7, 64bit
Java version "11.0.7" 2020-04-14
