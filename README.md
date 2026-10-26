### Эдуард Сарваров — AI-инженер

14 лет серверного кода, последний год — ИИ в рабочем продукте. Отвечаю за продукт целиком:
схема данных, API, интерфейс, инфраструктура, выкладка. Код веду через ИИ-агентов
(Claude Code) — и по каждой строке объясню решение.
TypeScript, Go, Python, PHP · Yandex Cloud, YDB, PostgreSQL · LLM, RAG, MCP, evals.

- **[GamePulse](https://sourcecraft.dev/youredik/gamepulse)** — живой сервис с LLM: детерминированные проверки поверх ответа модели, стенд сравнения моделей, выкладка с дымовой пробой и автооткатом. [Демо](https://d5di947mrfv71qo6acud.fovt0b64.apigw.yandexcloud.net/)
- Принятые PR в репозитории Яндекса: **[langchain-ydb #33](https://github.com/ydb-platform/langchain-ydb/pull/33)** (векторные хранилища) и **[mcp-memory-ydb #1](https://github.com/ydb-platform/mcp-memory-ydb/pull/1)** (долгая память для ИИ-агентов)
- **[async-integration-platform](https://github.com/youredik/async-integration-platform)** — двусторонняя интеграция: outbox, подписанные вебхуки, идемпотентность при одновременных запросах
- **[notification-service](https://github.com/youredik/notification-service)** — очереди с приоритетами, повторы при сбое, защита от двойной отправки
- **[posiflora-telegram-mvp](https://github.com/youredik/posiflora-telegram-mvp)** — интеграция для магазинов: Telegram-уведомления, идемпотентность, запуск одной командой

Сочи, время московское · Telegram [@sochi_privet](https://t.me/sochi_privet)
