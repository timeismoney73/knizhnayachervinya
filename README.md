# Книжная червиня

Авторский книжный блог на Jekyll. Публикации хранятся в `_posts`: обычные заметки автоматически попадают в общую ленту и архив, а записи с `category: meetings` дополнительно появляются в разделе книжного клуба.

## Локальный запуск

```bash
bundle install
bundle exec jekyll serve
```

Сайт откроется по адресу `http://127.0.0.1:4000`.

Статическая сборка создаётся в `_site`. Файлы из `_sites` используются только упаковкой для OpenAI Sites и не влияют на Jekyll или GitHub Pages.

## Как добавить публикацию

Создайте файл `_posts/ГГГГ-ММ-ДД-slug.md` с полями `title`, `description`, `date_label`, `category` и `source_url`. Допустимые категории: `reviews`, `lists`, `essays`, `meetings`.

Для встречи дополнительно заполните `status`, `event_day`, `event_month`, `event_time`, `event_format`, `book_title`, `book_author`, `price`, `moderator` и, для будущей встречи, `registration_url`.

Исходные публикации: [Telegram-канал @knizhnayachervinya](https://t.me/knizhnayachervinya).
