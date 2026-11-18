# Требования (User Stories) – `gora-birthday-bot` (Build 1.0)

Функциональные требования к Telegram-боту «Жора» декомпозированы в формате **User Stories** с критериями приёмки, исключительными случаями и логикой работы фоновых задач и базы данных.

---

## 📋 Реестр User Stories по модулям в Jira

> **Доступ:** Задачи открыты в режиме чтения (`Viewer`). Внутри каждой карточки доступны подробные описания сценариев и требования к валидации ввода.

| Модуль                                  | Название User Story                                                                              |                                                                        Ссылка в Jira                                                                        |
|:----------------------------------------|:-------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|
| **Добавление дней рождения**            | Создание новой записи (имя, дата, заметка) с проверкой форматов                                  |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-1?atlOrigin=eyJpIjoiOWVhMGQxNjNhYTAxNGIwM2JhOTJhOGVlZTdjZmM5YjIiLCJwIjoiaiJ9)         |
| **Просмотр списка дней рождения**       | Запрос списка сохранённых дат, сгруппированных по месяцам                                        |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-2?atlOrigin=eyJpIjoiZTQwODkwYjNjOTNmNGU1NTg4Y2JhYmE0NzNlOGYwNjIiLCJwIjoiaiJ9)         |
| **Управление записями**                 | Редактирование (имя, дата, комментарий) и удаление записи по ID                                  |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-3?atlOrigin=eyJpIjoiNjRkODhhOWUzNTgwNDIwZGFmNDc3ZGYzZTI1ZDk2MWMiLCJwIjoiaiJ9)         |
| **Настройки пользователя**              | Настройка локального часового пояса и временных слотов уведомлений                               |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-4?atlOrigin=eyJpIjoiMjNmMmEzYWI4MGM4NGRjMDhhYzJjMzBjOGM2NzI2ZGUiLCJwIjoiaiJ9)         |
| **Ближайшие дни рождения и статистика** | Вывод именинников на ближайшие 30 дней и общая статистика                                        |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-5?atlOrigin=eyJpIjoiMjkzODYzMWMxMzdjNGJkOTljYmM3NWI3OWUwZDU3MGMiLCJwIjoiaiJ9)         |
| **Напоминания**                         | Фоновый планировщик рассылки (за 7 дней, 3, 2, 1 день и в день праздника)                        |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-6?atlOrigin=eyJpIjoiZWMyY2Y0NjUzNjEyNGQxZTg1ODQ4ZWJjZjhlZmE1MmYiLCJwIjoiaiJ9)         |
| **Сохранность данных и восстановление** | Сохранение записей пользователей и их восстановление в случае перезапуска сервера                |        [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-7?atlOrigin=eyJpIjoiZjY3YzA0ZjY3NDhiNGIxNjg5OGMwZWZiZWI0MGU1MmEiLCJwIjoiaiJ9)         |
| **Поиск**                               | Поиск дней рождения                |         [Открыть в Jira](https://artamkindima.atlassian.net/browse/GBB-9?atlOrigin=eyJpIjoiNDZjZThkNTM2MWNjNGMyYzgxZjRkNDk4NTZhYTAzZDIiLCJwIjoiaiJ9)         |

---

## 🔗 Дополнительно
- **Общий фильтр всех требований в проекте:** [Смотреть список в Jira](https://artamkindima.atlassian.net/jira/software/projects/GBB/list?jql=project+%3D+GBB+ORDER+BY+cf%5B10019%5D+ASC&atlOrigin=eyJpIjoiODNjODU0ZDNkNDhhNDcyZWE2N2Y1YzYyNTc5ZTBlMGMiLCJwIjoiaiJ9)
- **Покрытие требований тест-кейсами:** см. матрицу трассируемости и артефакты в [Тест-плане](../01_Test_Plan/) и [Итоговом отчёте](../04_Test_Summary_Report/).