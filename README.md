# Kitchen Storage Docs

Документация по хранению продуктов, собранная как полноценный docs-сайт на `MkDocs Material`.

## Локальный запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

После запуска сайт будет доступен на `http://127.0.0.1:8000`.

## Сборка

```bash
source .venv/bin/activate
mkdocs build
```

Готовый статический сайт появится в папке `site/`.

## Публикация на GitHub Pages

В репозиторий уже добавлен workflow: [`.github/workflows/docs.yml`](/Users/alfa/Documents/Кухня/.github/workflows/docs.yml).

Что останется сделать:

1. Создать репозиторий на GitHub.
2. Подключить `origin`.
3. Запушить ветку `main`.
4. В настройках репозитория открыть `Settings -> Pages` и выбрать `GitHub Actions`.

После этого документация будет публиковаться автоматически при пуше в `main`.
