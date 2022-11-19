# Видеоплеер

Это учебный видеоплеер созданный для изучения верстки.
## Запуск:

Для просмотра работы видеоплеера нажмите [демо видеоплеера](https://maksanikeev.github.io/video_pleer/)

### Выбор видео:

Если вы хотите выбрать другое видео для просмотра, то зайдите в файл `index.html`
и в самом низу `src:` вставьте ссылку на другое видео

```
  <script type="text/javascript">
    createPlayer({
      elementId: 'player',
      src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
  });
  </script>
```
## Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).