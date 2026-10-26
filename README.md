# go.fest-sun.ru – мини-лендинги в мессенджерах

Короткие адреса для ссылок из бота и мини-приложения Telegram. Здесь только тонкие страницы:
блоки, данные и стили – в репозитории fest-sun-blocks (скрипт `https://xenaja.github.io/fest-sun-blocks/fs.js`),
поэтому весь контент правится там, а не здесь.

| Адрес | Что это | Копия страницы |
|---|---|---|
| https://go.fest-sun.ru/newyear/?ref=КОД | Новогодняя Мистерия | fest-sun-blocks/m/newyear/ |
| https://go.fest-sun.ru/es/?ref=КОД | Энергия Солнца | fest-sun-blocks/m/energiya-solntsa/ |
| https://go.fest-sun.ru/es/fe/ | Энергия Солнца – версия для партнёров | fest-sun-blocks/m/energiya-solntsa/fe/ |
| https://go.fest-sun.ru/newyear/fe/ | Мистерия – версия для партнёров | fest-sun-blocks/m/partner/ |
| https://go.fest-sun.ru/partner/ | Материалы для партнёров (из бота) | fest-sun-blocks/m/partner/ |

Корень и несуществующие адреса уводят на fest-sun.ru.

Почему отдельный репозиторий: если подключить поддомен к fest-sun-blocks, GitHub начнёт перенаправлять
старые адреса xenaja.github.io/fest-sun-blocks/… без CORS-заголовков – и блоки на fest-sun.ru и
soundmystery.ru перестанут загружаться.

DNS: REG.RU, зона fest-sun.ru – CNAME `go` → `xenaja.github.io.`
