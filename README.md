# Макеты страниц рмк62.рф

Общая страница: `index.html`, список макетов строится из `makety.json`.

## Как добавить макет

1. Положить HTML в `makety/ГГГГ-ММ/<латинское-имя>.html` (в `<head>` добавить `<meta name="robots" content="noindex, nofollow">`).
2. Добавить запись в `makety.json`: `title`, `file`, `date` (ГГГГ-ММ-ДД), `status` («на согласовании» / «согласовано»), `url` (будущий адрес на сайте, можно пусто), `description`.
3. `git add` этих файлов, `git commit`, `git push` — GitHub Pages обновится за 1–2 минуты.

Исходники макетов лежат в Obsidian: `Work/Рязанская Молочка (РМК)/<месяц>/`.
