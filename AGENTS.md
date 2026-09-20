# Репозиторий лендинга АРКА

Продакшен — **статика в корне**. Остальное не трогать при деплое.

## Корень (сайт)

| Файл | Назначение |
|---|---|
| `index.html` | Единственная страница. Правь её. |
| `arka-landing.html` | Редирект на `index.html` (старая ссылка) |
| `assets/` | Фото, `favicon.svg` |
| `favicon.svg` | Иконка с корня домена |
| `robots.txt` | Google, Яндекс + Allow для GPTBot, Claude, Perplexity и др. |
| `sitemap.xml` | После домена: абсолютный URL |
| `llms.txt` / `llms-full.txt` | GEO для ИИ |
| `site.webmanifest` | PWA-мета |

## `legacy/`

Jay Vibe / TanStack / Vite. Локально не собирается. **В git можно не пускать** или оставить как архив. На хостинг не копировать.

## Git

Коммитить корень без `legacy/node_modules`. После домена: абсолютные URL в sitemap, llms, canonical, og:image.
