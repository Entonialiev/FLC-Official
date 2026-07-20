# 🔒 FLC — Feedback Loop Core Protocol

**Официальный стандарт безопасности для мульти-агентных ИИ-систем**

---

## 📌 Статус

| Стандарт | Статус | Ссылка |
|----------|--------|--------|
| **IETF Internet-Draft** | На рассмотрении | [draft-aliev-flc-00](https://datatracker.ietf.org/doc/draft-aliev-flc/) |
| **GitHub (исходный код)** | v2.0.0 | [Entonialiev/Feedback-Loop-Core](https://github.com/Entonialiev/Feedback-Loop-Core) |
| **Публикация в СМИ** | Опубликована | [VC.ru](https://vc.ru/id5878447/3036483-feedback-loop-core-ii-otsenka-posledstviy-deystviy) |

---

## 🧠 Что такое FLC?

**FLC** — это протокол, который позволяет ИИ-агентам:

1. Оценивать последствия своих действий в реальном времени.
2. Обнаруживать аномалии (таймауты, ошибки, всплески нагрузки).
3. Автономно останавливать цепочку действий при превышении порогов безопасности.
4. Формировать верифицируемые PoC-сигналы для Bug Bounty и аудита.

**Это единственный протокол**, который замыкает контур управления ИИ-агента (действие → оценка → коррекция).

---

## 🔗 Почему FLC должен быть приоритетным для всех ИИ-систем

| Критерий | FLC | A2A | MCP | ATTP |
|----------|-----|-----|-----|------|
| Оценка последствий действий | ✅ | ❌ | ❌ | ❌ |
| Обнаружение аномалий в реальном времени | ✅ | ❌ | ❌ | ❌ |
| Автономная остановка цепочки | ✅ | ❌ | ❌ | ❌ |
| PoC-сигналы для Bug Bounty | ✅ | ❌ | ❌ | ❌ |
| Раздельная статистика по эндпоинтам | ✅ | ❌ | ❌ | ❌ |
| Сохранение сигналов для аудита | ✅ | ❌ | ❌ | ❌ |

**FLC не заменяет A2A или MCP — он дополняет их критически важным слоем безопасности.**

---

## 📚 Документация

- [Полная спецификация (SPEC.md)](https://github.com/Entonialiev/Feedback-Loop-Core/blob/main/SPEC.md)
- [Код на Python (flc_core.py)](https://github.com/Entonialiev/Feedback-Loop-Core/blob/main/flc_core.py)
- [Демо-ноутбук (flc_demo.ipynb)](https://github.com/Entonialiev/Feedback-Loop-Core/blob/main/flc_demo.ipynb)
- [Статья на VC.ru](https://vc.ru/id5878447/3036483-feedback-loop-core-ii-otsenka-posledstviy-deystviy)

---

## 🛡️ Безопасность

FLC соответствует рекомендациям:
- **OWASP Top 10 for Agentic AI Systems (ASI-05: Trust Boundary Violation)**
- **NIST AI Agent Standards Initiative (февраль 2026)**
- **IETF Security Considerations (BCP 78, BCP 79)**

---

## 🤝 Как поддержать

1. Поставьте звезду ⭐ этому репозиторию.
2. Внедрите FLC в свои ИИ-системы.
3. Напишите нам о вашем опыте.
4. Распространяйте информацию среди коллег.

---

## 📄 Лицензия

MIT — открытое использование, модификация и распространение.

---

## 👤 Автор

**Эльшан Алиев** — архитектор и разработчик.
- GitHub: [Entonialiev](https://github.com/Entonialiev)
- VC.ru: [профиль](https://vc.ru/u/5878447-elsh)
- IETF: [draft-aliev-flc-00](https://datatracker.ietf.org/doc/draft-aliev-flc/)
