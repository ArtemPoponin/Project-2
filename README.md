# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

05/04/2021 - 05/04/2021 было проведено компонентное тестирование (санитарное тестирование) приложения Credit Card Number Validator.

На тестирование затрачено: 1.5 часа

В результате тестирования выявлены следующие дефекты:
* Дефекты не выявлены, все тест-кейсы пройдены успешно, фактический результат целиком и польностью совпадает с ожидаемым результатом.

## Описание процесса тестирования:

В процессе тестирования использовались следующие артефакты:
* тест план №1*

В качестве тестовых данных использовались данные:
* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)
* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
* переменная для хранения итогового значения - тип int

Тестирование производилось в следующем окружении:
* ПК Lenovo Y750 (intel core i7); Windows 10.
* Java 11.0.10.9

# *Приложения*:
 ## Тест план №1:
- Открываем IntelliJ IDEA Community Edition
- Создаем новый проект
- Выбираем в новом проекте папку src
- Создаем файл Main.java
- Копируем из GitHub репозитория https://github.com/netology-code/javaqa-homeworks.git из блока 1, п. 1.1, задание №1 исходный код
- Вставляем ранее скопированный код в файл Main.java и сохраняем его
- Открываем сайт https://fakepersongenerator.com
- Создаем рандомного пользователя
- Копируем номер его карты из сторки с названием Credit Card Number
- Вставляем номер карты в четвертую строчку кода внутри двойных ковычек (String number = "НОМЕР КАРТЫ")
- Наводим курсор мыши на зеленую стрелку Run в первой сторке в верхней левой части открытого файла Main.java в IntelliJ IDEA Community Edition
- Из выпадающего списка выбираем Run'Main.main()'
- Обратите внимание на результат запуска программы в нижней части IntelliJ IDEA Community Edition (Если обработка данных прошла успешно, появится сообщение "Result is OK", а если нет, то "Result is FAIL"
-  Ожидаемый результат: После успешного запуска программы, появляется сообщение "Result is OK".
