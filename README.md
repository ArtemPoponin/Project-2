# Отчёт о тестировании Money Transfer

## Краткое описание

05/04/2021 - 05/04/2021 было проведено компонентное тестирование (разовая проверка заданных значений) приложения Money Transfer.

На тестирование затрачено: 1.5 часа

В результате тестирования выявлены следующие дефекты:
* Дефект №1 https://github.com/ArtemPoponin/Project-2/issues/1#issue-850326248

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
- Открываем файл Code из GitHub репозитория https://github.com/ArtemPoponin/Project-2.git 
- Копируем содержимое файла Code
- Вставляем ранее скопированный код в файл Main.java и сохраняем его
- Вставляем текущий баланс счёта клиента: 2_000_000_000 (два миллиарда рублей) в 3 строчку кода (данные уже должны быть внесены до вас, проверьте, что значения верные)
- Вставляем сумму перевода: 500_000_000 (пятьсот миллионов рублей) в 4 строчку кода (данные уже должны быть внесены до вас, проверьте, что значения верные)
- Наводим курсор мыши на зеленую стрелку Run в первой сторке в верхней левой части открытого файла Main.java в IntelliJ IDEA Community Edition
- Из выпадающего списка выбираем Run'Main.main()'
- Обратите внимание на результат запуска программы в нижней части IntelliJ IDEA Community Edition (Если обработка данных прошла успешно, появится обновленная сумма средств на балансе счёта клиента - 2_500_000_000)
-  Ожидаемый результат: После успешного запуска программы, выводится обновленная сумма средств на балансе счёта клиента - 2_500_000_000.
