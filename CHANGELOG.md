# RiderGuild Beta — Changelog / История изменений

## Русский

### 1.8.0-beta.13 — build 43

Стабилизационная beta-сборка для публичного тестирования.

Основные изменения:

- production backend обновлён и выровнен с текущим мобильным клиентом;
- исправлено восстановление активной SOS-сессии после возврата назад, повторного открытия SOS и возврата в приложение;
- пока существует активный SOS, новая SOS-форма не открывается и второй активный SOS не создаётся;
- выбранный помощник получает актуальное состояние и live tracking без обязательного открытия push-уведомления;
- отправитель и выбранный помощник корректно видят друг друга на SOS-карте;
- SOS origin, «Вы» и второй участник используют единый географический anchor, подписи больше не смещают маркеры при масштабировании и вращении карты;
- исправлен нижний SafeArea экрана поездки: кнопка «Маршрут» и остальные действия остаются выше системной навигационной панели Android;
- улучшена адаптация статистики поездки и длинных заголовков действий на небольших экранах;
- повторно проверены права создателя клуба, доступ участников, Club Chat и запуск поездки на production backend.

Функция объединённой ленты «Все поездки» в эту стабилизационную сборку не включена и запланирована отдельным этапом.

APK опубликован как **Pre-release** в GitHub Releases.

### 1.8.0-beta.12 — build 42

Первая публично распространяемая APK-сборка RiderGuild через GitHub Releases.

Основные направления текущей beta-линии:

- карта и геолокация;
- клубы, сообщества и клубные места;
- поездки, маршруты и события;
- профиль и гараж;
- SOS и Live Location;
- уведомления;
- исправления интерфейса и стабильности;
- подключение к production API RiderGuild.

APK опубликован как **Pre-release** в GitHub Releases.

### 1.8.0-beta.11 — build 40

Предыдущая beta-сборка для тестирования.

Основные направления beta-линии:

- улучшения профиля пользователя;
- развитие SOS и Live Location;
- работа с клубами, клубными домами и местами;
- улучшения маршрутов и карты;
- уведомления и сценарии взаимодействия между участниками;
- исправления интерфейса и стабильности.

Подробные внутренние технические изменения в этом публичном репозитории не публикуются.

### Предыдущие beta-сборки

Ранее использовалась серия 1.8.0-beta.x. Для тестирования всегда ориентируйтесь на последнюю сборку, опубликованную в Releases.

---

## English

### 1.8.0-beta.13 — build 43

Stabilization beta release for public testing.

Main changes:

- the production backend was updated and aligned with the current mobile client;
- active SOS recovery now works after navigating back, reopening SOS, and returning to the app;
- while an active SOS exists, the app does not open a new SOS form or create a second active request;
- the selected helper receives the current state and starts live tracking without requiring the push notification to be opened;
- the sender and selected helper can see each other correctly on the SOS map;
- SOS origin, “You”, and counterpart markers now use the same geographic anchor, so labels no longer shift marker positions during zoom or map rotation;
- Ride Detail bottom SafeArea is fixed so Route and other actions stay above Android system navigation;
- ride statistics and long action titles adapt better on small screens;
- club creator permissions, member access, Club Chat, and Ride Start availability were rechecked against the production backend.

The combined “All rides” feed is not included in this stabilization build and is planned for a separate follow-up.

The APK is published as a **Pre-release** in GitHub Releases.

### 1.8.0-beta.12 — build 42

First publicly distributed RiderGuild APK through GitHub Releases.

Main focus areas of the current beta line:

- map and geolocation;
- clubs, communities, and club locations;
- rides, routes, and events;
- profile and garage;
- SOS and Live Location;
- notifications;
- interface and stability fixes;
- connection to the RiderGuild production API.

The APK is published as a **Pre-release** in GitHub Releases.

### 1.8.0-beta.11 — build 40

Previous beta build for testing.

Main focus areas of the beta line:

- user profile improvements;
- continued development of SOS and Live Location;
- clubs, clubhouses, and places;
- route and map improvements;
- notifications and member interaction flows;
- interface and stability fixes.

Detailed internal technical changes are not published in this public repository.

### Previous beta builds

Earlier builds used the 1.8.0-beta.x series. For testing, always use the latest build published in Releases.
