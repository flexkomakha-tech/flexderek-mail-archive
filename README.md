# Почтовый веб-архив flexderek.com

Автономный веб-интерфейс для просмотра и поиска по архиву писем из резервной копии сайта.

## Характеристики:
- **Всего писем:** 2 105
- **Фильтрация:** все письма более 2 МБ исключены (в текущем архиве все письма < 60 КБ)
- **Основной ящик:** `wzkqkutl@flexderek.com` (DirectAdmin System / Server Mail)
- **Алиасы и пересылка:** `info@flexderek.com` -> `flexkomakha@gmail.com`
- **Категории:**
  - 📥 Входящие (Inbox) — 2 103 письма
  - 🚫 Спам (Spam) — 2 письма
  - ⚠️ Ошибки доставки (Mailer-Daemon) — 2 098 писем
  - 🛡️ Уведомления безопасности / Wordfence
  - 💬 Личная переписка и служебные уведомления

## Запуск локально:
Открыть файл `index.html` в любом современном браузере:
`file:///C:/Users/FlexDerek/.gemini/antigravity/scratch/mail_archive_web/index.html`

## Развертывание:
- **Cloudflare Pages:** Подключите данный приватный репозиторий `flexkomakha-tech/flexderek-mail-archive` в панели Cloudflare Pages (Build command: пусто, Output directory: `/`).
- **GitHub Pages:** Доступно при публичном статусе репозитория или на тарифе GitHub Pro.
