<h1 align="center">👋 Привет, я Валерий</h1>

<p align="center">
  <b>Backend / Fullstack PHP-разработчик</b><br>
  <i>Проектирование высоконагруженных систем на Laravel, Symfony и современном стеке</i>
</p>

<p align="center">
  <a href="https://valsy.ru">Блог</a> &nbsp;|&nbsp;
  <a href="https://t.me/valsysp">Telegram</a> &nbsp;|&nbsp;
  <a href="https://github.com/Valsym">GitHub</a>
</p>

---

### Обо мне

- 7+ лет коммерческой разработки на PHP/Laravel, общий IT-опыт — 20+ лет
- Проектирую высоконагруженные системы (до 1600+ RPS)
- Мигрирую легаси (Yii2 → Laravel), рефакторинг, работа с чужим кодом
- Разрабатываю CRM-системы с нуля — от идеи до продакшена
- Пишу тесты (PHPUnit, покрытие до 76%), провожу code review
- Использую AI-инструменты (Copilot, SourceCraft) в ежедневной разработке
- Веду технический блог ([valsy.ru](https://valsy.ru)) — статьи по Laravel, SQL, оптимизации
- Москва, Россия

---

### Коммерческий опыт

| Область | Что делал |
|---------|-----------|
| **Архитектура** | Проектировал масштабируемые системы, микросервисы, модульные монолиты |
| **Highload** | Оптимизация производительности: до 1622 RPS, снижение нагрузки на БД на 40–60% |
| **Миграции** | Переводил легаси-проекты (Yii2 → Laravel), рефакторинг, работа с чужим кодом |
| **Интеграции** | API (REST, GraphQL), платёжные системы, OAuth, Telegram, Avito, XML |
| **Очереди** | RabbitMQ, Horizon, Kafka (CDC-пайплайн PostgreSQL → Kafka → ClickHouse) |
| **DevOps** | Docker, Kubernetes (k3d, HPA), CI/CD (GitHub Actions), Linux |
| **Мониторинг** | Prometheus + Grafana, ELK / Kibana |
| **Тестирование** | PHPUnit (покрытие до 76%), PHPStan, code review |

---

### Личные проекты и эксперименты

#### Коммерческие и инфраструктурные

- **[CRM (Public Demo)](https://github.com/Valsym/mycrm-showcase)** — демо-версия профессиональной CRM-системы на Laravel.  
  *(полная версия — приватный репозиторий)*

- **[High-Load Laravel](https://github.com/Valsym/high-load)** — оптимизация и оркестрация:
  - 48× рост RPS (33 → 1622) на VPS за счёт Laravel Octane, OPcache, оптимизации запросов
  - CDC Pipeline: PostgreSQL → Kafka → ClickHouse через Debezium
  - ClickHouse: TTL + Materialized Views
  - Prometheus + Grafana мониторинг (RPS, latency, память PHP)
  - ELK (Elasticsearch, Logstash, Kibana) — сбор и анализ логов Laravel
  - Горизонтальное масштабирование: локальный Docker-кластер (3 реплики, Nginx-балансировщик)
  - Kubernetes (k3d) с HPA для автомасштабирования
  - Отказоустойчивость: репликация PostgreSQL + Redis Sentinel (3 узла)
  - AI-автоматизация: Laravel Boost (MCP) + SourceCraft

- **[Конкурентный анализ](https://github.com/Valsym/CPT)** — система для сбора и анализа цен конкурентов на Avito.  
  *(начальная версия — [analytics](https://github.com/Valsym/analytics))*

#### Интеграции и паттерны

- **[RabbitMQ Patterns](https://github.com/Valsym/rabbitmq-patterns)** — реализация паттернов на Laravel:
  - Work Queue, Fanout, Topic, RPC
  - DLX (Dead Letter Exchange)
  - Retry + Idempotency
  - Idempotent RPC

- **[Transaction Demo](https://github.com/Valsym/transaction-demo)** — демонстрация работы с транзакциями:
  - Атомарность операций (commit/rollback)
  - Пессимистичные блокировки (lockForUpdate)
  - Savepoint (вложенные транзакции)
  - Оптимистичные блокировки

#### Fullstack (Laravel + Frontend)

- **[Laravel + React (my-shop)](https://github.com/Valsym/my-shop)** — интернет-магазин с:
  - OpenSearch для полнотекстового поиска
  - Laravel Reverb + Echo для WebSocket (real-time)
  - Redis для масштабирования

- **[Laravel + Vue (vue-first)](https://github.com/Valsym/vue-first)** (приватный) — CRUD с Pinia, Vitest (16 тестов), пагинация, поиск, фильтрация

- **[Symfony + Vue](https://github.com/Valsym/Symfony-Vue)** (приватный) — полный CRUD для товаров, REST API, валидация, Pinia, Vitest

- **[Filament Clean](https://github.com/Valsym/filament-clean)** — админ-панель на Laravel 12 + Filament 5:
  - Управление продуктами, категориями, пользователями
  - Роли и права доступа (политики)
  - Мультиязычный контент

#### Вспомогательные

- **[DevOps Scripts](https://github.com/Valsym/devops-scripts)** — скрипты для администрирования:
  - Мониторинг дискового пространства (с уведомлениями в Telegram)
  - Ротация логов
  - Бэкап БД

#### Pet-проекты (исторические)

- **[What to Watch](https://github.com/Valsym/what-to-watch)** — REST API на Laravel для поиска фильмов с рейтингами и комментариями
- **[My Blog](https://github.com/Valsym/my-blog)** — технический блог на Laravel
- **[Parser Autoposter](https://github.com/Valsym/parser-autoposter)** (2016) — парсер для горнолыжных курортов (WP)
- **[Railway](https://github.com/Valsym/railway)** (2014) — сайт с расписанием ЖД-перевозок (WP, 40k+ страниц)

---

### Технический стек

#### Backend
PHP 8.4, Laravel 10-13, Symfony (практика), Yii2, Docker, Kubernetes, REST API, WebSocket/Reverb, RabbitMQ, Kafka (CDC), Horizon, Octane

#### Базы данных
PostgreSQL, MySQL, ClickHouse (TTL, MV), Redis, OpenSearch/Elasticsearch

#### DevOps и мониторинг
Linux, CI/CD (GitHub Actions), Prometheus + Grafana, ELK/Kibana, Nginx

#### Frontend
HTML, CSS/SCSS, JavaScript/jQuery, React/Redux (интеграция), Vue.js

#### Инструменты
Git, PHPUnit, PHPStan, AI-инструменты (Copilot, SourceCraft)

---

### GitHub Stats

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Valsym&theme=default)

---

> Открыт к предложениям о сотрудничестве. Ищу долгосрочный проект в продуктовой компании, где востребованы навыки архитектора и оптимизатора.
