# План тестирования "Тестирование возможности записаться на обучение профессии "Тестировщик ПО""
## 1.Перечень автоматизируемых сценариев

### Сценарии нафигации к форме записи

* Переход к форме заявки через кнопку "Записаться" на странице профессии для зарегестрированного пользователя<br>
	1.открыть страницу https://netology.ru/;<br>
	2.войти в личный кабинет пользователя;<br>
	3.перейти на страницу профессии;<br>
	4.кликнуть на кнопку "Записаться" на станице профессии.<br>

* Переход к форме заявки через кнопку "Записаться" на странице профессии для незарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии;<br>
  3.кликнуть на кнопку "Записаться" на станице профессии.<br>

* Переход к форме заявки через кнопку "Записаться" в хедере страницы профессии для зарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.войти в личный кабинет пользователя;<br>
  3.перейти на страницу профессии;<br>
  4.проскроллить страницу вниз пока не появится выкатывающийся хедер;<br>
  5.кликнуть на кнопку "Записаться" в хедере страницы профессии.<br>

* Переход к форме заявки через кнопку "Записаться" в хедере страницы профессии для незарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии;<br>
  3.проскроллить страницу вниз пока не появится выкатывающийся хедер;<br>
  4.кликнуть на кнопку "Записаться" в хедере страницы профессии.<br>

* Переход к странице профессии через меню "Каталог курсов" на главной странице для зарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.войти в личный кабинет пользователя;<br>
  3.кликнуть на "Каталог курсов" в хедере страницы;<br>
  4.выбрать "все курсы"/ "программирование";<br>
  5.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через меню "Каталог курсов" на главной странице для незарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.кликнуть на "Каталог курсов" в хедере страницы;<br>
  3.выбрать "все курсы"/ "программирование";<br>
  4.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через кнопку "Программирование" на главной странице для зарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.войти в личный кабинет пользователя;<br>
  3.кликнуть на "Программирование" на главной странице;<br>
  4.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через кнопку "Программирование" на главной странице для незарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.кликнуть на "Программирование" на главной странице;<br>
  3.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через кнопку "355 курсов всех направлений" на главной странице для зарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.войти в личный кабинет пользователя;<br>
  3.проскроллить страницу вниз до кнопки "355 курсов всех направлений"<br>
  4.кликнуть на "355 курсов всех направлений" на главной странице;<br>
  5.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через кнопку "355 курсов всех направлений" на главной странице для незарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.проскроллить страницу вниз до кнопки "355 курсов всех направлений"<br>
  3.кликнуть на "355 курсов всех направлений" на главной странице;
  4.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через кнопку "Выбрать курс" на главной странице для зарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.войти в личный кабинет пользователя;<br>
  3.проскроллить страницу вниз до кнопки "Выбрать курс";<br>
  4.кликнуть на "Выбрать курс" на главной странице;<br>
  5.кликнуть на "Тестировщик ПО".<br>

* Переход к странице профессии через кнопку "Выбрать курс" на главной странице для незарегестрированного пользователя<br>
  1.открыть страницу https://netology.ru/;<br>
  2.проскроллить страницу вниз до кнопки "Выбрать курс"<br>
  3.кликнуть на "Выбрать курс" на главной странице;
  4.кликнуть на "Тестировщик ПО".<br>

### Сценарии заполнения и отправки формы

* Отправка формы записи<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Ваша заявка успешно отправлена!"

* Отправка формы записи с невалидным именем (латиница)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" данные на латинице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (арабский)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" данные на арабском;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (символы)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" любые символы за исключением дефиса;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (цифры)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" цифры;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (ведущий пробел)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" данные на кириллице с ведущим пробелом;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (замыкающий пробел)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" данные на кириллице с замыкающим пробелом;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным именем (пробел)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" пробел;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать больше одной буквы"

* Отправка формы записи с невалидным именем (несколько пробелов)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" пробелы в диапазоне от 2 до 64;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" валидный номер;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Значение поля должно содержать только русские буквы и дефис"

* Отправка формы записи с невалидным номером телефона (нули)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" +7 (000)-000-00-00;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (девятки)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" +7 (999)-999-99-99;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (буквы)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" буквы;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (символы)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" символы;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (9 цифр)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" данные, содержащие 9 цифр;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Телефон указан неверно"

* Отправка формы записи с невалидным номером телефона (11 цифр)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" валидный Email;<br>
  6.ввести в поле "Номер телефона" данные, содержащие 11 цифр;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Невозможно ввести более 10 символов
 
* Отправка формы записи с невалидным адресом электронной почты (без точек в домене)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email без точек в доменной части;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в начале имени аккаунта)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email  с точкой в начале имени аккауната;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в конце имени аккаунта)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email  с точкой в конце имени аккауната;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в начале доменной части)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email с точкой в начале доменной части;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (точка в конце доменной части)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email с точкой в конце доменной части;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (кириллица)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email на кириллице;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (без @)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email без символа @;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (пробел в имени аккаунта)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email с пробелом в имени аккаунта;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (пробел в доменной части)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email с пробелом в доменной части;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (без доменной части)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email без доменной части;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с невалидным адресом электронной почты (без имени аккаунта)<br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.ввести в поле "Имя" валидное имя на кириллице;<br>
  5.ввести в поле "Email" Email без имени аккаунта;<br>
  6.ввести в поле "Номер телефона" валидный номер телефона;<br>
  7.кликнуть на "Записаться".<br>

*Ожидаемый результат:* Вывод сообщения "Указан неверный Email"

* Отправка формы записи с пустыми полями <br>
  1.открыть страницу https://netology.ru/;<br>
  2.перейти на страницу профессии любым способом;<br>
  3.перейти к форме записи любым способом;<br>
  4.кликнуть на "Записаться".<br>

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

