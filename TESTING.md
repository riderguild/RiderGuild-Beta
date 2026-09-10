# RiderGuild Beta — Testing Guide / Руководство по тестированию

## Русский

Этот список помогает тестерам последовательно проходить основные сценарии RiderGuild.

### Карта и геолокация

- определяется ли текущее местоположение;
- корректно ли двигается карта;
- отображаются ли клубы и места;
- открываются ли карточки объектов;
- не перекрывают ли элементы интерфейса системные панели телефона.

### Клубы и сообщества

- создание и просмотр клуба;
- вступление и выход;
- корректность ролей и прав;
- отображение клубного дома и клубной символики;
- отсутствие дубликатов сущностей.

### Маршруты и события

- построение маршрута;
- отображение маршрута на карте;
- создание и просмотр событий;
- корректность дат, времени и мест.

### SOS и Live Location

Тестируйте этот раздел только в безопасных условиях.

- отправка SOS;
- принятие SOS помощником;
- обновление взаимного местоположения;
- работа при сворачивании приложения;
- корректное завершение SOS-сессии;
- корректное отображение доступной контактной информации.

Не используйте публичный Issue для публикации реальных текущих координат или личных телефонов.

### Уведомления

- запрос разрешения Android;
- получение push-уведомлений;
- счётчик непрочитанных;
- переход из уведомления в нужный экран.

### Профиль

- просмотр своего профиля;
- изменение доступных данных;
- просмотр чужого профиля;
- отсутствие данных, которые пользователь не разрешал показывать.

### Что особенно полезно в отчёте

Для воспроизводимой ошибки укажите точную последовательность действий. Например: «Карта → открыть клуб → открыть клубный дом → нажать Назад → приложение закрылось».

Чем точнее сценарий, тем быстрее можно воспроизвести и исправить проблему.

---

## English

This checklist helps testers go through the main RiderGuild scenarios consistently.

### Map and geolocation

- current location is detected correctly;
- the map moves and behaves correctly;
- clubs and places are displayed;
- object cards open correctly;
- interface elements do not overlap Android system bars.

### Clubs and communities

- club creation and viewing;
- joining and leaving;
- correct roles and permissions;
- correct display of the clubhouse and club identity;
- no duplicate entities are created.

### Routes and events

- route building;
- route display on the map;
- event creation and viewing;
- correct dates, times, and locations.

### SOS and Live Location

Test this section only in safe conditions.

- sending an SOS;
- accepting an SOS as a helper;
- mutual location updates;
- operation while the app is in the background;
- correct termination of the SOS session;
- correct display of permitted contact information.

Do not use a public Issue to publish real-time coordinates or personal phone numbers.

### Notifications

- Android permission request;
- push notification delivery;
- unread counter;
- opening the correct screen from a notification.

### Profile

- viewing your own profile;
- editing available profile data;
- viewing another user's profile;
- no data is shown unless the user has allowed it to be shared.

### What makes a bug report useful

For reproducible bugs, provide the exact sequence of actions. Example: “Map → open club → open clubhouse → press Back → app closes.”

The more precise the scenario, the faster the issue can be reproduced and fixed.