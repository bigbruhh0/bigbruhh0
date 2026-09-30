# Артур Сафин

**AI Engineer · Backend-разработка · автоматизация процессов**

Более 5 лет занимаюсь backend-разработкой и автоматизацией бизнес-процессов. Работаю с Python/FastAPI и PHP/Symfony, проектирую API и интеграции, разбираю ручные workflow и превращаю их в сервисы и внутренние инструменты. В AI-проектах работаю с LLM-интеграциями, RAG, агентными сценариями, политиками выполнения действий и оценкой качества.

Рассматриваю позиции AI Engineer, Backend Engineer и Automation Engineer.

## Основной опыт

### Автоматизация e-commerce и складских операций — закрытый проект

Спроектировал внутреннюю систему печати этикеток и автоматизации обработки заказов: backend, desktop-клиент, взаимодействие по WebSocket, интеграции с CRM и генерация PDF. Также автоматизировал повторяющиеся операции менеджеров и поддерживал Symfony backend и интеграции с 1С.

По моим оценкам, время подготовки этикетки сократилось с 5 минут примерно до 15 секунд; автоматизировано до 90% повторяющихся действий, экономия времени команды составляла до 7 часов в неделю. Код проекта закрыт (private).

**Python · aiohttp · PyQt · WebSocket · RetailCRM API · PHP/Symfony · REST/JWT · MySQL/PostgreSQL · Docker · ReportLab · PIL**

### AI-платформа поддержки e-commerce — закрытый проект

Разрабатывал платформу поддержки с постоянными диалогами, маршрутизацией к специалистам и подключаемыми LLM-провайдерами. Проект включает RAG-базу знаний, поиск с источниками, контролируемые вызовы инструментов, policy/permissions layer, интеграции с CRM, audit trail, regression evals и мониторинг качества.

Исходный код закрыт (private); публичной ссылки нет.

**Python · FastAPI · React · DeepSeek/OpenAI-compatible API · RAG · embeddings · PostgreSQL/pgvector · Docker Compose**

### Realtime-мессенджер — личный закрытый проект

Разрабатываю мессенджер: REST backend, WebSocket/realtime-функции, чаты, вложения и уведомления. В проекте есть backend и web/desktop/mobile-клиенты с общими контрактами.

Проект ведётся в команде. Исходный код закрыт (private); [сайт проекта](https://min-chat.online).

**Python · FastAPI · PostgreSQL · Redis · MinIO/S3 · OpenAPI · WebSocket · TypeScript/React · WebRTC/LiveKit · Docker**

### Платформа удалённой разработки с Codex CLI — личный закрытый проект

Разрабатываю self-hosted VPS-инструмент для изолированной работы с Git-репозиториями и Codex CLI: управление рабочими копиями, запуск agent sessions, привязка агентов к логам и обратной связи для немедленной реакции, подтверждение действий через API/UI. Проект ведётся в команде.

Проект находится на стадии MVP; репозиторий закрытый (private).

**TypeScript · Fastify · React · Vite · PostgreSQL · WebSocket · Docker Compose · Codex CLI**

### Game Dev Loop — личный закрытый проект

Разрабатываю локальную админ-панель для итеративной разработки игровых проектов с Codex и OpenCode. Оркестратор распределяет задачи между ролями планировщика, разработчика, ассистента и документатора; ведёт планы задач и спецификации функций, запускает работу в отдельных Git-ветках, выполняет командные и MCP-проверки, сохраняет историю запусков и их логи. Предусмотрены ревью результата и ручное подтверждение перед слиянием изменений.

Исходный код приватный.

**TypeScript · Node.js · React · Vite · Express · SQLite · Codex app-server · OpenCode · MCP**

### PHP Backend Engineer — распределённая Symfony-система, закрытый коммерческий код

Работаю над backend-сервисами на PHP/Symfony: REST API и бизнес-логикой, интеграциями и асинхронным взаимодействием между сервисами. Участвую в проектировании OpenAPI-контрактов, поддержке legacy и production-разборе; спроектировал и запустил отдельный микросервис. Есть опыт разработки в большой команде с трекером задач и регулярными встречами. Примеры рабочего кода недоступны: система закрыта.

**PHP · Symfony · PostgreSQL · Doctrine ORM · RabbitMQ · Docker · OpenAPI · CI/CD**

## Публичные проекты: учебные работы и тестовые задания

Эти репозитории показывают отдельные реализации и прототипы; они не заменяют основной коммерческий и продуктовый опыт выше.

- [Анализ PDF-изометрий](https://github.com/bigbruhh0/test_work_blueprints_ai) — прототип извлечения геометрии и размерных кандидатов, диагностические PDF и экспорт JSON/Excel. Расчёт полной длины трубопровода остаётся экспериментальным.
- [Расчёт покупки на Symfony](https://github.com/bigbruhh0/symfony-purchase-example) — купоны, налоговый расчёт, транзакция и адаптеры платёжных провайдеров.
- [Telegram Bot Manager](https://github.com/bigbruhh0/telegram-bot-manager) — веб-панель управления ботами, подписчиками, webhook и очередью рассылок.
- [Сервис коротких ссылок](https://github.com/bigbruhh0/test_laravel_short_links) — кабинет, ссылки и статистика переходов пользователей.
- [Расписание курьеров на Symfony](https://github.com/bigbruhh0/php-symfony-schedule-manager) и [на чистом PHP](https://github.com/bigbruhh0/php-vanilla-schedule-manager) — планирование поездок и проверка пересечений расписания.
- [FastAPI game API](https://github.com/bigbruhh0/FastApi-game-api) — API карточной игры, коллекции, игровые боксы и платёжный callback.
- [Блог на чистом PHP](https://github.com/bigbruhh0/test-work-clean-php-blog) — MVC-подобная структура, свои router/repository и шаблоны Smarty.
- [Laravel CRUD](https://github.com/bigbruhh0/Laravel-crud) — REST API для списка задач.

## Технологии

- **Backend:** Python, FastAPI, aiohttp, PHP, Symfony, Laravel, REST, WebSocket
- **AI:** LLM API, RAG, embeddings, tool calling, agent workflows, evals, audit logging
- **Данные и инфраструктура:** PostgreSQL, MySQL, SQLite, Redis, RabbitMQ, MinIO/S3, Docker, Linux, Nginx, CI/CD
- **Интеграции и клиенты:** CRM API, 1С, React, TypeScript, PyQt, WebRTC, LiveKit

## Образование

- [УГНТУ](https://ugntu.ru/) — 2 курса, направление «Управление в технических системах».
- [Международный институт экономики и права (МИЭП)](https://miep.ru/) — 5 курсов, «Менеджер проектов».

В описании закрытых проектов не привожу ссылки на приватный код. Для публичных учебных проектов ссылки оставлены.
