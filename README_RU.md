# KESA Messenger — сайт загрузки

Статическая страница для GitHub Pages. Она не требует Node.js или сервера.

## Кнопки скачивания

Страница ожидает, что в GitHub Releases последнего релиза репозитория
`KilluaClicker/KesaMessenger` будут приложены файлы с точными именами:

- `KESA-Messenger.apk`
- `KESA-Messenger-Setup.exe`

Ссылки на кнопках уже настроены на эти имена. Если у тебя файлы называются иначе,
измени ссылки в `index.html` или переименуй файлы перед загрузкой в Release.

## Как опубликовать через GitHub Pages

1. Скопируй `index.html` и `style.css` в корень репозитория `KesaMessenger`.
2. Сделай commit и push в ветку `main`.
3. На GitHub открой **Settings → Pages**.
4. В разделе **Build and deployment** выбери **Deploy from a branch**.
5. Выбери ветку `main` и папку `/(root)`, затем нажми **Save**.
6. Через минуту сайт появится по адресу `https://killuaclicker.github.io/KesaMessenger/`.

## Как добавить установщики

1. Открой вкладку **Releases** репозитория.
2. Нажми **Create a new release**.
3. Укажи тег, например `v1.0.0`.
4. Прикрепи APK и EXE, назвав их ровно как указано выше.
5. Опубликуй релиз (**Publish release**).

Важно: файлы из GitHub Actions **Artifacts** обычно являются ZIP-архивами и могут истекать;
для постоянных публичных ссылок загружай готовые файлы в **GitHub Releases**.
