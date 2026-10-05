# cetera-labs/library

Сторонние JS-библиотеки старого back-office [Fastsite CMS](https://github.com/cetera-labs/fastsite-cms) 3.x.
Пакет ставится composer-зависимостью CMS в `vendor/cetera-labs/library`; при сборке сайта (`build.xml` CMS)
нужные файлы склеиваются в `www/cms/js/vendor.js` и `www/cms/css/global.css`.

Раньше пакет скачивался архивом `https://cms.cetera.ru/lib.zip` и описывался в `composer.json` каждого сайта
блоком `repositories` с версией `13`. Версия `13.0.0` этого репозитория побайтно совпадает с тем архивом.

Новые версии не планируются: старый back-office в Fastsite CMS 4.0 заменяется новой админкой.

## Состав и лицензии

| Каталог | Библиотека | Версия | Лицензия |
|---|---|---|---|
| `extjs4/` | Ext JS (Sencha) | 4.2 | GPL-3.0 |
| `ace/` | Ace editor | — | BSD-3-Clause |
| `beautify/` | js-beautify | — | MIT |
| `cropper/` | Cropper.js | 1.0.0 | MIT |
| `minify/` | html-minifier | 2.1.3 | MIT |
| `youtube/` | Youtube Embed Plugin для CKEditor | 1.0.7 | GPL / LGPL / MPL |
| `pclzip.lib.php` | PclZip | 2.x | LGPL |

`library.php` оставлен для совместимости с архивом и в CMS не используется.
