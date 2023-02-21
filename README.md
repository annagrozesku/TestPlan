# План тестирования "Тестирование возможности записаться на обучение профессии "Тестировщик ПО""

## 1.Перечень автоматизируемых сценариев

### Сценарии нафигации к форме записи

* Переход к форме заявки через кнопку "Записаться" на странице профессии для зарегестрированного пользователя
	1.открыть страницу https://netology.ru/
	2.войти в личный кабинет пользователя
	3.перейти на страницу профессии
	4.кликнуть на кнопку "Записаться" на станице профессии

* Переход к форме заявки через кнопку "Записаться" на странице профессии для незарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии;
  3.кликнуть на кнопку "Записаться" на станице профессии.

* Переход к форме заявки через кнопку "Записаться" в хедере страницы профессии для зарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.войти в личный кабинет пользователя;
  3.перейти на страницу профессии;
  4.проскроллить страницу вниз пока не появится выкатывающийся хедер;
  5.кликнуть на кнопку "Записаться" в хедере страницы профессии.

* Переход к форме заявки через кнопку "Записаться" в хедере страницы профессии для незарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии;
  3.проскроллить страницу вниз пока не появится выкатывающийся хедер;
  4.кликнуть на кнопку "Записаться" в хедере страницы профессии.

* Переход к странице профессии через меню "Каталог курсов" на главной странице для зарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.войти в личный кабинет пользователя;
  3.кликнуть на "Каталог курсов" в хедере страницы;
  4.выбрать "все курсы"/ "программирование";
  5.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через меню "Каталог курсов" на главной странице для незарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.кликнуть на "Каталог курсов" в хедере страницы;
  3.выбрать "все курсы"/ "программирование";
  4.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через кнопку "Программирование" на главной странице для зарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.войти в личный кабинет пользователя;
  3.кликнуть на "Программирование" на главной странице;
  4.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через кнопку "Программирование" на главной странице для незарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.кликнуть на "Программирование" на главной странице;
  3.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через кнопку "355 курсов всех направлений" на главной странице для зарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.войти в личный кабинет пользователя;
  3.проскроллить страницу вниз до кнопки "355 курсов всех направлений"
  4.кликнуть на "355 курсов всех направлений" на главной странице;
  5.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через кнопку "355 курсов всех направлений" на главной странице для незарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.проскроллить страницу вниз до кнопки "355 курсов всех направлений"
  3.кликнуть на "355 курсов всех направлений" на главной странице;
  4.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через кнопку "Выбрать курс" на главной странице для зарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.войти в личный кабинет пользователя;
  3.проскроллить страницу вниз до кнопки "Выбрать курс"
  4.кликнуть на "Выбрать курс" на главной странице;
  5.кликнуть на "Тестировщик ПО".

* Переход к странице профессии через кнопку "Выбрать курс" на главной странице для незарегестрированного пользователя
  1.открыть страницу https://netology.ru/;
  2.проскроллить страницу вниз до кнопки "Выбрать курс"
  3.кликнуть на "Выбрать курс" на главной странице;
  4.кликнуть на "Тестировщик ПО".

### Сценарии заполнения и отправки формы

* Отправка формы записи
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Ваша заявка успешно отправлена!"

* Отправка формы записи с невалидным именем (латиница)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" данные на латинице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (арабский)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" данные на арабском;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (символы)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" любые символы за исключением дефиса;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (цифры)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" цифры;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (ведущий пробел)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" данные на кириллице с ведущим пробелом;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (замыкающий пробел)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" данные на кириллице с замыкающим пробелом;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (пробел)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" пробел;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать больше одной буквы"

* Отправка формы записи с невалидным именем (несколько пробелов)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" пробелы в диапазоне от 2 до 64;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" валидный номер;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным номером телефона (нули)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" +7 (000)-000-00-00;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (девятки)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" +7 (999)-999-99-99;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (буквы)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" буквы;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (символы)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" символы;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (9 цифр)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" данные, содержащие 9 цифр;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (11 цифр)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" валидный Email;
  6.ввести в поле "Номер телефона" данные, содержащие 11 цифр;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Невозможно ввести более 10 символов
 
* Отправка формы записи с невалидным адресом электронной почты (без точек в домене)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email без точек в доменной части;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на 

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в начале имени аккаунта)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email  с точкой в начале имени аккауната;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в конце имени аккаунта)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email  с точкой в конце имени аккауната;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в начале доменной части)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email с точкой в начале доменной части;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в конце доменной части)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email с точкой в конце доменной части;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (кириллица)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email на кириллице;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (без @)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email без символа @;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (пробел в имени аккауна)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email с пробелом в имени аккаунта;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (пробел в доменной части)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email с пробелом в доменной части;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (без доменной части)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email без доменной части;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (без имени аккаунта)
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.ввести в поле "Имя" валидное имя на кириллице;
  5.ввести в поле "Email" Email без имени аккаунта;
  6.ввести в поле "Номер телефона" валидный номер телефона;
  7.кликнуть на "Записаться".

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с пустыми полями 
  1.открыть страницу https://netology.ru/;
  2.перейти на страницу профессии любым способом;
  3.перейти к форме записи любым способом;
  4.кликнуть на "Записаться".

*Ожидаемый результат:* Кнопка отправить неактивна

## 2.Перечень используемых инструментов

- JUnit5 (использование библиотек для процессов автоматизации тестирования)
- Gradle (для автоматизации сборки проекта)
- Selenide (для UI-тестов, например, для тестирования переходов по страницам к форме записи)
- Docker (контейнеризация приложений, для тестирования отправки форм, запуск приложения в изолированной среде)
- Git (система контроля версий, хранение кода)
- Bash (интерпретатор командной строки, для использования git)
- Allure (сборка отчетов после прохождения тестов)
- Apache Jmeter (исследование нагрузки на сайт)

## 3.Перечень необходимых разрешений, данных и доступов

- Доступ к БД зарегестрированных пользователей, либо подготовленные тестовые данные
- SUT
- Разрешение на проведение тестирования

## 4.Перечень и описание возможных рисков при автоматизации

1. Большие затраты денег и времени при долгой автоматизации
2. Пропуск возможных багов в функционале, который не заложен в тестах
3. Обновление контента страницы, который ведет к тому, что тесты начинают устаревать 

## 5.Перечень необходимых специалистов для автоматизации

1. Разработчик (написание unit-тестов, установка test-id в код)
2. Тестировщик автоматизатор

## 6.Интервальная оценка с учетом рисков в часах

15-20 часов

