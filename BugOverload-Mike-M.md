# Домашнее задание №3 по курсу "Обеспечение качества ПО" проекта VK Образование
## Команда: **BugOverload**
 
## Содержание

1. [Деплой](#деплой)
2. [Страница фильма](#задание)
3. [Ручное тестирование](#ручное-тестирование)

## Задание
Сделать чек-листы для будущих автотестов на проект 2-го семестра

## Деплой
[MovieGate](https://movie-gate.online/)

## Страница авторизации/регистрации
### Примеры доступны по ссылке:
[Страница авторизации](https://movie-gate.online/login/)
[Страница регистрации](https://movie-gate.online/signup/)

## Кейсы
Данные тестового пользователя
Почта: Qwe123@a.a
Пароль: Qwe123@a.a

## Страница регистрации

1. При нажатии на кнопку с текстом "Регистрация" должен произойти переход на страницу [https://movie-gate.online/signup/](https://movie-gate.online/signup/)
2. При нажатии на кнопку с текстом "Войти" должен произойти переход на страницу [https://movie-gate.online/login/](https://movie-gate.online/login/)
3. При вводе имени меньше 4 символов, не происходит регистрация
4. При вводе неправильного адреса электронной почты, не происходит регистрация
5. При вводе пароля, состоящего из одних маленьких букв, не происходит регистрация
6. При вводе валидных данных, происходит регистрация

## Страница авторизации
1. При вводе невалидного пароля, не происходит авторизация
2. При вводе невалидного логина, не происходит авторизация
3. При вводе валидных данных, происходит авторизации

## Страница профиля
### Примеры доступны по ссылке:
[Результат поиска](https://movie-gate.online/profile/)
0. Предварительно необходима авторизация для всех тестов
Данные тестового пользователя
Почта: Qwe123@a.a
Пароль: Qwe123@a.a
 
1. При нажатии на иконку карандаша ![image](https://github.com/Mike5535/homework-3-spring-2023/assets/84146116/f25bbade-15dd-4c85-b244-42b6fc230fa1)
 появляется инпуты для редактирования профиля
2. В профиле есть поля с основной информацией об аккаунте
3. Количество оценок - неотрицательное число или "нет оценок"
4. Количество коллекций - неотрицательное число
5. Количество рецензий - неотрицательное число или "нет рецензий"
6. Можно сменить имя пользователя

