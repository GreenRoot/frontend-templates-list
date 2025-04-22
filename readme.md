Ниже отчёт-сравнение по запрошенным шаблонам. Метрики оценивались по 7 критериям (поддержка TanStack Query, UI‑библиотека, модуль авторизации, @hey-api/openapi‑ts, таблицы/формы/валидация, размер сообщества, FSD‑архитектура). Оценка по 10‑балльной шкале.

| Шаблон                                                                                                                   | Звёзды | Последний релиз             | TanStack Query | UI‑библиотека            | Auth | openapi‑ts | Таблицы/Формы/Валид. | Комьюнити | FSD | Оценка |
| ------------------------------------------------------------------------------------------------------------------------ | ------ | --------------------------- | -------------- | ------------------------ | ---- | ---------- | -------------------- | --------- | --- | ------ |
| <a href="https://github.com/marmelab/react-admin" target="_blank">React Admin</a>                                        | 25.7 k | 5.7.3 (18 апр. 2025)        | ✅             | Material UI              | ✅   | ❌         | ✅                   | ✅        | ❌  | 7.1    |
| <a href="https://github.com/ant-design/ant-design-pro" target="_blank">Ant Design Pro</a>                                | 37 k   | 6.0.0‑beta.1 (27 июн. 2022) | ❌             | Ant Design               | ✅   | ❌         | ✅                   | ✅        | ❌  | 5.7    |
| <a href="https://github.com/horizon-ui/horizon-ui-chakra" target="_blank">Horizon UI Chakra</a>                          | 2.7 k  | 3.0.0 (13 янв. 2025)        | ❌             | Chakra UI                | ✅   | ❌         | ✅                   | ❌        | ❌  | 4.3    |
| <a href="https://www.creative-tim.com/product/soft-ui-dashboard-react" target="_blank">React Soft Dashboard (NodeJS)</a> | 207    | 2.0.10 (2 дек. 2022)        | ❌             | Material UI              | ✅   | ❌         | ✅                   | ❌        | ❌  | 4.3    |
| <a href="https://github.com/codedthemes/datta-able-bootstrap-dashboard" target="_blank">Datta Able Free</a>              | 87     | 3.0.0 (26 июн. 2024)        | ❌             | Bootstrap 5/Reactstrap   | ✅   | ❌         | ✅                   | ❌        | ❌  | 4.3    |
| <a href="https://github.com/codedthemes/berry-free-react-admin-template" target="_blank">Berry Free</a>                  | 2 000  | 4.0.1 (26 мар. 2025)        | ❌             | Material UI V6           | ❌   | ❌         | ✅                   | ❌        | ❌  | 2.9    |
| <a href="https://github.com/codedthemes/mantis-free-react-admin-template" target="_blank">Mantis Free</a>                | 845    | 1.4.1 (28 фев. 2025)        | ❌             | Material UI + Ant Design | ❌   | ❌         | ✅                   | ❌        | ❌  | 2.9    |

---

## 1. React Admin

**GitHub: <a href="https://github.com/marmelab/react-admin" target="_blank">marmelab/react-admin</a> (25.7 k ★)**
**Последний релиз:** v5.7.3 18 апр. 2025

### Метрики

- **TanStack Query:** есть (`react-query`)
- **UI‑библиотека:** Material UI
- **Авт./рег./сброс:** встроен контроллер аутентификации
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** `Datagrid`, `SimpleForm`, `react-hook-form`
- **Комьюнити:** ⭐ 25.7 k, 611 контриб
- **FSD:** нет

### Плюсы

- Полнофункциональный бэкенд‑агностик фреймворк
- Богатый набор компонентов (CRUD, формы, таблицы, валидация)
- Их поддерживает большое сообщество
- Отличная документация и DevTools

### Минусы

- Сложнее кастомизировать под не‑Material UI
- Нет генерации OpenAPI клиента

---

## 2. Ant Design Pro

**GitHub: <a href="https://github.com/ant-design/ant-design-pro" target="_blank">ant-design/ant-design-pro</a> (37 k ★)**
**Последний релиз:** v6.0.0‑beta.1 27 июн. 2022

### Метрики

- **TanStack Query:** нет
- **UI‑библиотека:** Ant Design
- **Авт./рег./сброс:** есть блок `Account` (login/register)
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** Standard Table, Basic/Step/Advanced Form
- **Комьюнити:** ⭐ 37 k, 2 517 коммитов
- **FSD:** нет

### Плюсы

- Широкий набор enterprise‑шаблонов (Dashboard, List, Profile и т.д.)
- Глубокая интеграция с i18n, mock, CI через Umi
- Большое комьюнити и зрелый UX

### Минусы

- Релизы давно не выходили
- Кривая обучения Umi

---

## 3. Horizon UI Chakra

**GitHub: <a href="https://github.com/horizon-ui/horizon-ui-chakra" target="_blank">horizon-ui/horizon-ui-chakra</a> (2.7 k ★)**
**Последний релиз:** v3.0.0 13 янв. 2025

### Метрики

- **TanStack Query:** нет
- **UI‑библиотека:** Chakra UI
- **Авт./рег./сброс:** готовые страницы авторизации
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** содержит UI‑блоки, но нет встроенной валидации
- **Комьюнити:** ⭐ 2.7 k
- **FSD:** нет

### Плюсы

- Модульный и современный дизайн
- Хорошая документация и Discord-комьюнити

### Минусы

- Отсутствуют механизмы фетчинга данных (напр. React Query)
- Нет встроенной валидации форм

---

## 4. React Soft Dashboard (NodeJS)

**GitHub: <a href="https://github.com/app-generator/react-soft-dashboard-nodejs" target="_blank">app-generator/react-soft-dashboard-nodejs</a> (207 ★)**
**Последний релиз:** v2.0.10 2 дек. 2022

### Метрики

- **TanStack Query:** нет
- **UI‑библиотека:** Material UI
- **Авт./рег./сброс:** JWT + OAuth (GitHub)
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** базовые формы и таблички
- **Комьюнити:** ⭐ 207
- **FSD:** нет

### Плюсы

- Готовый бэкенд (Node.js/Express с JWT)
- OAuth‑флоу и Postman коллекция

### Минусы

- Малое сообщество, нет обновлений с 2022
- Отсутствует унифицированный фетчинг и валидация

---

## 5. Datta Able Free

**GitHub: <a href="https://github.com/codedthemes/datta-able-bootstrap-dashboard" target="_blank">codedthemes/datta-able-bootstrap-dashboard</a> (87 ★)**
**Последний релиз:** v3.0.0 26 июн. 2024

### Метрики

- **TanStack Query:** нет
- **UI‑библиотека:** Reactstrap/Bootstrap 5
- **Авт./рег./сброс:** есть страницы аутентификации
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** компоненты форм и таблиц
- **Комьюнити:** ⭐ 87 citeturn0search3
- **FSD:** нет

### Плюсы

- Лёгкий Bootstrap‑шаблон
- Аутентификация из коробки

### Минусы

- Практически нет комьюнити
- Нет современных фетчинг/валидаций

---

## 6. Berry Free

**GitHub: <a href="https://github.com/codedthemes/berry-free-react-admin-template" target="_blank">codedthemes/berry-free-react-admin-template</a> (2 000 ★)**
**Последний релиз:** v4.0.1 26 мар. 2025

### Метрики

- **TanStack Query:** нет
- **UI‑библиотека:** Material UI V6
- **Авт./рег./сброс:** только в Pro‑версии
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** есть базовые страницы и компоненты
- **Комьюнити:** ⭐ 2 000
- **FSD:** нет

### Плюсы

- Быстрый старт на Vite + MUI
- Адаптивный и отзывчивый дизайн

### Минусы

- Отсутствует auth в бесплатной версии
- Нет встроенной валидации

---

## 7. Mantis Free

**GitHub: <a href="https://github.com/codedthemes/mantis-free-react-admin-template" target="_blank">codedthemes/mantis-free-react-admin-template</a> (845 ★)**
**Последний релиз:** v1.4.1 28 фев. 2025

### Метрики

- **TanStack Query:** нет
- **UI‑библиотека:** Material UI + Ant Design
- **Авт./рег./сброс:** только Pro‑версия
- **openapi‑ts:** нет
- **Таблицы/формы/валидация:** есть базовые компоненты
- **Комьюнити:** ⭐ 845
- **FSD:** нет

### Плюсы

- Гибрид MUI + Ant Design
- SWR для фетчинга (усовершенствованная кеш‑логика)

### Минусы

- Нет auth в бесплатной версии
- Малообновляемый
