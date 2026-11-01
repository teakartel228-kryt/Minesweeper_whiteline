# MINESWEEPER: WHITELINE

Сапёр с градусником, парированиями, модификаторами и кучей пасхалок. Одна HTML-страница, без сборки и зависимостей.
Работает в браузере и на телефоне (есть Android-обёртка).

*English: a Minesweeper with a heat meter, parries, modifiers, a map editor and many easter eggs. Single `index.html`, no build step, works in any modern browser and on mobile.*

## Запуск

Просто откройте `index.html` в браузере. Или:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

После включения GitHub Pages (Settings → Pages → Source: GitHub Actions) игра будет доступна по ссылке вида
`https://<user>.github.io/<repo>/`.

## Возможности

- Режимы сложности и своё поле (ширина, высота, число мин), сид и таймер
- Градусник (нагрев и остывание от действий), парирования
- Модификаторы и челленджи, режим дуэли, раунды с выбором способностей
- Редактор своей карты
- Темы, скины, Material You, своя палитра, настройка управления
- Музыка, звуки, мягкие игрушки, статистика
- Встроенная консоль и скрытые пасхалки (ищите сами)
- Опциональный модуль Game Boy: запускает **ваш собственный** ROM-файл

## Game Boy и ROM

Проект **не содержит и не распространяет** ROM-файлов. Эмулятор [WasmBoy](https://github.com/torch2424/wasmboy)
подгружается с CDN только при открытии модуля, и запускает только тот файл, который вы загрузите сами.
Для этого модуля нужен интернет.

## Android

Приложение — обёртка на Flutter вокруг этого же `index.html`. Подробности: [docs/ANDROID.md](docs/ANDROID.md).
Готовые APK лучше выкладывать в раздел Releases.

## Участие

Смотрите [CONTRIBUTING.md](CONTRIBUTING.md). Pull request'ы приветствуются.

## Лицензия

GPL-3.0-or-later, см. [LICENSE](LICENSE). Сторонние компоненты: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
