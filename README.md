<div align="center">

# RiderGuild Beta

**Мобильное сообщество для райдеров / A mobile community for riders**

![Android](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)
![Beta](https://img.shields.io/badge/status-Public%20Beta-orange)
![Languages](https://img.shields.io/badge/docs-RU%20%7C%20EN-blue)

### [⬇️ Скачать последнюю APK / Download latest APK](https://github.com/riderguild/RiderGuild-Beta/releases/download/v1.8.0-beta.12/RiderGuild-1.8.0-beta.12-build42-release.apk)

**[Русский](#русский) · [English](#english)**

</div>

> **Public testing hub.** Здесь публикуются материалы для тестеров RiderGuild. Исходный код, серверные конфигурации и внутренние данные разработки здесь не размещаются.  
> **Public testing hub.** This repository contains materials for RiderGuild testers. Source code, server configuration, and internal development data are not published here.

---

## Статус / Status

| | |
|---|---|
| **Текущая версия / Current version** | `1.8.0-beta.12` |
| **Build** | `42` |
| **Платформа / Platform** | Android |
| **APK** | Доступен в Releases / Available in Releases |
| **Стадия / Stage** | Public Beta / Pre-release |

### Быстрые ссылки / Quick links

[**Скачать APK / Download APK**](https://github.com/riderguild/RiderGuild-Beta/releases/download/v1.8.0-beta.12/RiderGuild-1.8.0-beta.12-build42-release.apk) · [**Сообщить об ошибке / Report a bug**](https://github.com/riderguild/RiderGuild-Beta/issues/new?template=bug_report.yml) · [**Предложить улучшение / Suggest a feature**](https://github.com/riderguild/RiderGuild-Beta/issues/new?template=feature_request.yml) · [**Обсуждения / Discussions**](https://github.com/riderguild/RiderGuild-Beta/discussions) · [**Что тестировать / Testing Guide**](TESTING.md) · [**Changelog**](CHANGELOG.md) · [**FAQ**](FAQ.md) · [**Поддержка / Support**](SUPPORT.md) · [**Приватность / Privacy**](PRIVACY.md) · [**Security**](SECURITY.md)

---

# Русский

## Что такое RiderGuild

**RiderGuild** — мобильное приложение для мотоциклистов и мотосообществ. Текущая beta-линия проверяет ключевые пользовательские сценарии: карту и геолокацию, клубы и сообщества, клубные места, маршруты, события, SOS и Live Location, уведомления и профиль пользователя.

## Текущая beta

**RiderGuild 1.8.0-beta.12 — build 42**

RiderGuild находится в активной разработке. Beta-сборки могут содержать ошибки, незавершённые функции и изменения интерфейса.

## Установка Android beta

APK публикуется в разделе **Releases** этого репозитория.

1. Откройте **Releases**.
2. Выберите последнюю beta-версию.
3. В блоке **Assets** скачайте APK.
4. Если Android запросит разрешение, разрешите установку приложений из используемого источника.
5. Установите APK поверх предыдущей beta или как новую установку.

Текущая публичная сборка: **1.8.0-beta.12 — build 42**.

## Что особенно важно тестировать

- определение текущего местоположения и работу карты;
- клубы, сообщества и клубные места;
- создание и просмотр маршрутов и событий;
- SOS и Live Location в безопасных тестовых условиях;
- push-уведомления и переходы из них;
- свой и чужие профили;
- корректность разрешений и видимости пользовательских данных;
- интерфейс на разных размерах экранов Android.

Полный чек-лист: **[TESTING.md](TESTING.md)**.

## Нашли ошибку?

Откройте **[форму Bug report](https://github.com/riderguild/RiderGuild-Beta/issues/new?template=bug_report.yml)**. Перед созданием отчёта проверьте, не сообщал ли уже кто-то о той же проблеме.

Хороший отчёт содержит версию и build, модель телефона, версию Android, точные шаги воспроизведения, ожидаемый результат, фактический результат и при необходимости безопасный скриншот или запись экрана.

**Не публикуйте** номера телефонов, реальные текущие координаты, токены, пароли, приватные переписки и другие чувствительные данные.

Подробнее: **[BUG_REPORT.md](BUG_REPORT.md)**. Общие вопросы и идеи можно обсуждать в **[Discussions](https://github.com/riderguild/RiderGuild-Beta/discussions)**.

## Документы

| Документ | Для чего |
|---|---|
| [TESTING.md](TESTING.md) | Чек-лист beta-тестирования |
| [CHANGELOG.md](CHANGELOG.md) | История публичных beta-изменений |
| [BUG_REPORT.md](BUG_REPORT.md) | Как правильно оформить ошибку |
| [FAQ.md](FAQ.md) | Частые вопросы тестеров |
| [SUPPORT.md](SUPPORT.md) | Куда обращаться и что приложить |
| [PRIVACY.md](PRIVACY.md) | Правила приватности при тестировании |
| [SECURITY.md](SECURITY.md) | Как сообщать о проблемах безопасности |

Для оперативного общения используется сообщество **RiderGuild | Beta Testers**. Подтверждённые воспроизводимые ошибки лучше фиксировать в GitHub Issues, чтобы они не терялись.

---

# English

## What is RiderGuild

**RiderGuild** is a mobile app for motorcycle riders and riding communities. The current beta line focuses on core user flows: map and geolocation, clubs and communities, club locations, routes, events, SOS and Live Location, notifications, and user profiles.

## Current beta

**RiderGuild 1.8.0-beta.12 — build 42**

RiderGuild is under active development. Beta builds may contain bugs, unfinished features, and interface changes.

## Installing the Android beta

The APK is published in the repository **Releases** section.

1. Open **Releases**.
2. Select the latest beta version.
3. Download the APK from **Assets**.
4. If Android asks, allow installation from the source you are using.
5. Install the APK over the previous beta or as a fresh installation.

Current public build: **1.8.0-beta.12 — build 42**.

## What is especially useful to test

- current-location detection and map behavior;
- clubs, communities, and club locations;
- creating and viewing routes and events;
- SOS and Live Location in safe test conditions;
- push notifications and navigation from notifications;
- your own profile and other riders' profiles;
- permission handling and user-data visibility;
- interface behavior across different Android screen sizes.

Full checklist: **[TESTING.md](TESTING.md)**.

## Found a bug?

Open the **[Bug report form](https://github.com/riderguild/RiderGuild-Beta/issues/new?template=bug_report.yml)**. Before opening a new report, check whether the same issue has already been reported.

A useful report includes the app version and build, phone model, Android version, exact reproduction steps, expected behavior, actual behavior, and—when helpful—a safe screenshot or screen recording.

**Do not publish** phone numbers, precise live coordinates, tokens, passwords, private conversations, or other sensitive information.

See **[BUG_REPORT.md](BUG_REPORT.md)** for details. General questions and ideas belong in **[Discussions](https://github.com/riderguild/RiderGuild-Beta/discussions)**.

## Documents

| Document | Purpose |
|---|---|
| [TESTING.md](TESTING.md) | Beta testing checklist |
| [CHANGELOG.md](CHANGELOG.md) | Public beta change history |
| [BUG_REPORT.md](BUG_REPORT.md) | How to submit a useful bug report |
| [FAQ.md](FAQ.md) | Frequently asked tester questions |
| [SUPPORT.md](SUPPORT.md) | Where to ask for help and what to include |
| [PRIVACY.md](PRIVACY.md) | Privacy rules for public testing |
| [SECURITY.md](SECURITY.md) | How to report security-related issues |

The **RiderGuild | Beta Testers** community is used for day-to-day communication. Confirmed reproducible bugs should preferably be recorded in GitHub Issues so they are not lost.

---

<div align="center">

**RiderGuild — built for riders, tested by riders.**

</div>
