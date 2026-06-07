# Офлайн-архив справочной документации Яндекс Бизнеса

Проект представляет собой офлайн-архив справочной документации Яндекс Бизнеса
(https://yandex.ru/support/business-priority/ru/), сохранённый в виде markdown-файлов.

Каждая страница fetched через webfetch, сохраняется в файл с восстановленным
содержимым (таблицы, списки, примеры кода, описания полей).

## Дерево папок и файлов

```
yandex-business/
├── AGENTS.md                  — этот файл: описание проекта, дерево, соглашения
├── 1. О Яндекс Бизнесе/
│   ├── 0. О Яндекс Бизнесе.md — https://yandex.ru/support/business-priority/ru/
│   ├── 1. Где появится компания.md — .../ru/general/displaying
│   ├── 3. Подтвердить компанию.md — .../ru/moderation/moderation-address
│   ├── 4. Откуда мы берем данные.md — .../ru/add-company/change-info
│   └── 1. Требования к размещению/
│       ├── 0. Требования к размещению.md — .../ru/add-company/info-terms
│       ├── 1. Название.md — .../ru/add-company/rules-name
│       ├── 2. Адрес.md — .../ru/add-company/rules-address
│       ├── 3. Сайты и социальные сети.md — .../ru/add-company/rules-site
│       └── 4. Вид деятельности.md — .../ru/add-company/rules-rubric
├── 2. Добавить компанию в Яндекс/
│   ├── 1. Быстрый старт.md — .../ru/add-company/add-org
│   ├── 2. Подтверждение прав на компанию.md — .../ru/manage/verify
│   ├── 3. Знак Информация подтверждена владельцем.md — .../ru/manage/verified-owner
│   └── 4. Роли пользователей.md — .../ru/manage/accesses
├── 3. Заполнить информацию о компании/
    ├── 0. Заполнить информацию о компании.md — .../ru/manage/edit
    ├── 2. Логотип, фотографии и видеоролики.md — .../ru/manage/photos
    ├── 4. Публикации.md — .../ru/manage/publications
    ├── 5. Истории.md — .../ru/manage/stories
    ├── 6. События.md — .../ru/manage/events
    ├── 7. Акции.md — .../ru/manage/promotion
    ├── 8. Доставка.md — .../ru/manage/delivery
    ├── 9. Промоматериалы.md — .../ru/manage/promo
    ├── 10. Подключить заявки от пользователей.md — .../ru/manage/form
    ├── 12. Удаление компании.md — .../ru/manage/delete
    ├── 13. История изменений.md — .../ru/manage/changes
    ├── 14. Вопросы и ответы.md — .../ru/manage/faq
    ├── 1. Данные/
    │   ├── 0. Данные компании.md — .../ru/manage/data
    │   ├── 1. Название и короткое название.md — .../ru/manage/name
    │   ├── 2. Адрес и местоположение.md — .../ru/manage/address
    │   ├── 3. Статус.md — .../ru/manage/status
    │   ├── 4. Вид деятельности.md — .../ru/manage/type
    │   ├── 5. Время работы и праздничные дни.md — .../ru/manage/work-time
    │   ├── 6. Контактные данные.md — .../ru/manage/contacts
    │   ├── 7. Телефоны.md — .../ru/manage/phones
    │   └── 8. Особенности и реквизиты.md — .../ru/manage/other
    ├── 3. Товары и услуги/
    │   ├── 1. Прайс-лист компании.md — .../ru/manage/price-list
    │   └── 2. Прайс-лист партнера.md — .../ru/manage/partners-price-list
    └── 11. Онлайн‑запись в профиле/
        ├── 0. Онлайн‑запись в профиле компании.md — .../ru/manage/booking
        └── 1. Подключение к API онлайн‑записи.md — .../ru/manage/booking-api-partners
├── 4. Сети/
│   ├── 0. Сетевые организации.md — .../ru/branches/several-branches
│   ├── 1. Создать сеть.md — .../ru/branches/create-branches
│   ├── 4. Закрыть филиал сети.md — .../ru/branches/branches-exit
│   ├── 2. Информация о сети/
│   │   ├── 2. Логотип.md — .../ru/branches/logo
│   │   ├── 3. Прайс-лист сети.md — .../ru/branches/price
│   │   ├── 4. Обновления.md — .../ru/branches/updates
│   │   └── 1. Данные/
│   │       ├── 0. Как обновлять данные о филиалах.md — .../ru/branches/basic
│   │       ├── 1. Обновление данных вручную.md — .../ru/branches/branches-manual
│   │       ├── 2. Обновление данных через XML-файл.md — .../ru/branches/branches-xml
│   │       └── 3. Обновление данных через CSV-файл.md — .../ru/branches/branches-csv
│   └── 3. Реклама для сетей/
│       └── 1. Подключение подменных номеров для сетей.md — .../ru/branches/spoofed-num
├── 5. Отзывы и рейтинг/
│   ├── 1. Управление отзывами.md — .../ru/manage/reviews
│   ├── 2. Рейтинг компании.md — .../ru/manage/rating
│   ├── 3. Награда Хорошее место.md — .../ru/manage/stiker
│   └── 4. Награда «Особенно Хорошее место».md — .../ru/manage/stiker-good-place
├── 6. Реклама и продвижение/
│   ├── 0. Реклама и продвижение.md — .../ru/advertising
│   ├── 3. Брендированное приоритетное размещение.md — .../ru/brand
│   ├── 4. Виртуальная сеть.md — .../ru/virtual-network
│   ├── 5. Размещение в профиле другой компании.md — .../ru/adv-in-cards
│   ├── 6. Правила размещения рекламно-информационных материалов.md — .../ru/moderation/moderation
│   ├── 7. Как отредактировать кампанию.md — .../ru/manage-order
│   ├── 8. Оплатить кампанию.md — .../ru/payment/invoicing
│   ├── 9. Подмена номера.md — .../ru/spoofed-phone-number
│   ├── 1. Рекламная подписка/
│   │   ├── 0. Рекламная подписка.md — .../ru/order
│   │   ├── 1. Как мы покажем вас в Поиске и на сайтах.md — .../ru/adv-yan
│   │   ├── 2. Настроить цели в Яндекс Метрике.md — .../ru/tags
│   │   ├── 3. Рекламные материалы/
│   │   │   ├── 0. Рекламные материалы.md — .../ru/adv-materials
│   │   │   ├── 1. Новый интерфейс.md — .../ru/adv-materials-new
│   │   │   └── 2. Старый интерфейс.md — .../ru/adv-materials-old
│   │   ├── 4. Интеграция с Ozon.md — .../ru/ozon-api
│   │   └── 5. Автоматическое добавление товаров и услуг/
│   │       ├── 0. Автоматическое добавление товаров и услуг.md — .../ru/auto-prod-add
│   │       ├── 1. С сайта компании.md — .../ru/auto-prod-add-site
│   │       ├── 2. С маркетплейсов.md — .../ru/auto-prod-add-marketplace
│   │       ├── 3. ВКонтакте.md — .../ru/auto-prod-add-vk
│   │       ├── 4. Telegram.md — .../ru/auto-prod-add-tg
│   │       ├── 5. Через YML‑фид.md — .../ru/auto-prod-add-yml-fid
│   │       ├── 6. Из Вебмастера.md — .../ru/auto-prod-add-webmaster
│   │       └── 7. Частые вопросы.md — .../ru/auto-prod-add-faq
│   └── 2. Приоритетное размещение/
│       ├── 0. Приоритетное размещение.md — .../ru/benefits
│       ├── 1. Информационные материалы.md — .../ru/benefits-materials
│       └── 2. Управление и настройка.md — .../ru/benefits-materials-old
├── 7. Статистика/
│   ├── 1. Конкуренты.md — .../ru/manage/competitors
│   ├── 2. По рекламной кампании.md — .../ru/manage/ad-statistics
│   ├── 3. Общая статистика.md — .../ru/manage/general-statistics
│   └── 4. Как вас находят.md — .../ru/manage/statistics
├── 8. Создать сайт для компании.md — .../ru/create-site
├── 9. Особенности для онлайн‑компаний.md — .../ru/online-company
├── 10. Агентствам/
│   ├── 0. Агентствам.md — .../ru/agency/
│   ├── 1. Правила работы.md — .../ru/agency/rules
│   ├── 2. Роли пользователей.md — .../ru/agency/access
│   └── 3. Запустить рекламу для субклиента.md — .../ru/agency/manage
└── 13. Глоссарий.md — .../ru/general/glossary
```

## Соглашения

### Формат каждого markdown-файла

```
# <Title страницы>

> Source: <URL>

<текст страницы>
```

### Папки и файлы

- Папки и файлы именуются по схеме `NN. Название раздела/` / `NN. Название страницы.md`,
  где `NN` — порядковый номер (две цифры).
- Внутри каждой папки нумерация сквозная.

### Ссылки

- Внутренние относительные ссылки (`ru/...`) преобразуются в абсолютные
  (`https://yandex.ru/support/business-priority/ru/...`).
- Внешние ссылки остаются как есть.

### Обновление дерева

Дерево папок и файлов в этом разделе обновляется после каждого сохранённого файла.
