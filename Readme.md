# Верстка макета в рамках Летней кухни (Picom)
[Ссылка на макет (Figma)](https://www.figma.com/file/p9rwUVzI4rMotCcOOhreFg/Test)

## Структура проекта

```shell
smile/
├── css/                 # стили
├── fonts/               # шрифты
├── images/              # изображения
├── js/                  # js
├── .editorconfig        # конфиг для редакторов
└── [...]                # other...
```

## Динамическая перезагрузка браузера

    - Убедиться что установлен (node -v) [node.js](https://nodejs.org/en/)
    - Устанавливаем [browsersync](https://browsersync.io/)
    - Запускаем: browser-sync start --server --files "css/.css,js/.js,html/.html"
