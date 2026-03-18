### 👨‍💻 Python Backend Engineer
Специализируюсь на разработке отказоустойчивых бэкенд-систем и микросервисной архитектуре. Погружен во внутреннее устройство Python (AsyncIO, GIL, Memory Management), проектирование БД и алгоритмическую оптимизацию.

* 🚀 **Текущий фокус:** Проектирование высоконагруженных систем, паттерны идемпотентности и финтех-решения.
* 🏆 **Хакатоны:** Призер хакатонов (Т1 - 5 место, Радиохак 2.0 - 4 место).
* 🎓 **Образование:** ИРИТ-РТФ УрФУ, Программная инженерия.

---

### 🛠 Стек и Технологии
| Категория | Инструменты |
| --- | --- |
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) (Изучаю для перехода) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![AsyncIO](https://img.shields.io/badge/-AsyncIO-white?style=flat-square&logo=python&logoColor=3776AB) ![Pytest](https://img.shields.io/badge/-Pytest-0E7FBF?style=flat-square&logo=pytest&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Alembic](https://img.shields.io/badge/-Alembic-white?style=flat-square&logo=python&logoColor=red) |

---

### 📂 Основные проекты

#### 💎 [Payment Distribution Service](https://github.com/whxtelyy/payment-distribution-service)
**Самый технически сложный проект.** Система мультивалютных переводов с фокусом на консистентность данных.
* **Backend:** Реализовал строгую идемпотентность транзакций и обработку Race Conditions.
* **Performance:** Внедрил кэширование курсов валют в Redis и фоновую обработку задач через Taskiq.
* **Infrastructure:** Контейнеризация (Docker Compose), автоматические миграции (Alembic) и ротируемое логирование.
* **Reliability:** 100% покрытие критических сценариев (переводы, ошибки конвертации) тестами Pytest.

#### 📊 [Log Analyzer](https://github.com/whxtelyy/log_analyzer)
**Сервис централизованного сбора и анализа системных логов в реальном времени.**
* **Security:** Интегрировал аутентификацию на базе JWT и ролевую модель доступа для администрирования.
* **Data:** Спроектировал систему сложной фильтрации и агрегации статистики по логам.
* **Maintenance:** Реализовал Retention Policy для автоматической очистки устаревших записей в БД.

#### 🏆 Решения с хакатонов (Команда XOREK)
* **[Terraform LogViewer](https://github.com/kub1ce/Terraform-LogViewer_XOREK)** (Хакатон Т1) - Парсинг и визуализация логов инфраструктуры Terraform.
* **[Task Aggregator](https://github.com/kub1ce/task-aggregator-XOREK)** (Радиохак 2.0) - Единое окно уведомлений для корпоративных сервисов (Jira, Trello, TG).

---

### 📫 Связь
[<img src="https://img.shields.io/badge/-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" height="30">](https://t.me/whxtelyy) 
