# Лазарева и Ко — прототип сайта

## Что внутри
- `index.html` — сам сайт (один файл)
- `tiles/` — 12 картинок для анимации куба на обложке (должны лежать рядом с index.html, не переименовывать)

## Как выложить на GitHub

1. Зайти на github.com → **New repository**.
2. Имя, например: `lazareva-i-ko-site`. Оставить **Public** (иначе GitHub Pages не заработает на бесплатном тарифе). **Create repository**.
3. На странице пустого репозитория — ссылка **uploading an existing file** (или кнопка **Add file → Upload files**).
4. Перетащить в окно загрузки:
   - файл `index.html`
   - всю папку `tiles` целиком (GitHub сам разложит файлы по пути `tiles/...`)
5. Внизу — **Commit changes**.

## Как получить ссылку на сайт (GitHub Pages)

1. В репозитории: **Settings → Pages** (в левом меню).
2. **Source** → выбрать **Deploy from a branch**.
3. **Branch** → выбрать `main`, папку `/ (root)` → **Save**.
4. Через 1–2 минуты вверху появится ссылка вида:
   `https://<твой-логин>.github.io/lazareva-i-ko-site/`

Это и есть постоянная ссылка на сайт — можно присылать кому угодно.
