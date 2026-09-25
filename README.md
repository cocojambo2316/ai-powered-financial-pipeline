# DataPipeline

Базовый проект для разработки и запуска data pipeline.

## Требования

- Python 3.11+
- Docker Desktop с Docker Compose

## Установка

1. Создайте виртуальное окружение:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

2. Установите зависимости:

   ```powershell
   pip install -r requirements.txt
   ```

3. Запустите локальную базу данных:

   ```powershell
   docker compose up -d
   ```

Переменные окружения храните в `.env`. Файл `.env.example` используйте как шаблон, если он добавлен в проект.

## Остановка

```powershell
docker compose down
```

Для удаления данных локальной базы используйте `docker compose down -v`.