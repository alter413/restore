# Restore

Простой статический лендинг, готовый к публикации через Cloudflare Pages.

## Запуск через Cloudflare Pages

1. Открой Cloudflare Dashboard → **Workers & Pages** → **Create application** → **Pages**.
2. Выбери **Connect to Git** и репозиторий `alter413/restore`.
3. Production branch: `main`.
4. Framework preset: **None**.
5. Build command оставь пустым, Build output directory: `/`.
6. Нажми **Save and Deploy**.

Сайт состоит из обычных HTML и CSS-файлов, поэтому сборка не требуется.