# Требования к проекту
## 1. Введение
### 1.1. Назначение 
Jobs - это фриланс биржа, предоставляющая возможности  разместить заказ или найти работу любому желающему
### 1.2. Аналоги
* [КАБАНЧИК](https://kabanchik.by/) - онлайн сервис заказа услуг в by сегменте
* [Хабр Фриланс](https://freelance.habr.com) - фриланс биржа IT услуг от блога [habr](https://habr.com)
* [Weblancer](https://www.weblancer.net/) - крупная биржа удаленной работы

## 2. Требования пользователя
### 2.1. Программные интерфейсы 
* Язык программирования - **JavaScript**
* Среда разработки - **Visual Studio Code**
* Serverless реализация - [Firebase](https://firebase.google.com)
### 2.2. Интерфейс пользователя
Дизайн приложения: [figma](https://www.figma.com/file/89L3Ofzkax2IihlALaUm0I/jobs?node-id=0%3A1)
* Экран входа в приложение
* Экран при первом входе
* Экран "Заказы" роли "Исполнитель"
* Экран "Заказы" роли "Заказчик"
* Экран оповещений
* Экран профиля
### 2.3. Характеристики пользователей 
Целевая аудитория - заказчики, нуждающиеся в исполнителях для своих задач, и исполнители, готовые выполнять эти задачи

## 3. Системные требования
### 3.1. Функциональные требования
* Вход в приложение по номеру мобильного телефона
* Пароль отправляется чере SMS
* Лента всех доступных заказов для роли "Исполнитель"
* Возможность создание своего заказа для роли "Заказчик"
* Список своих заказов для роли "Заказчик"
* Отправка заявок на заказы пользователями с ролью "Исполнитель"
* Возможность смены роли для одного аккаунта одним нажатием в личном кабинете
* Редактирование и отображение информации о пользователях
### 3.2 Нефункциональные требования
#### 3.2.1. Атрибуты качества
* Приложение должно адаптироваться для разных разрешений экрана
* Обмен данными должен выполняться по защищенному протоколу
* Поддержка браузеров, занимающих более 2% рынка