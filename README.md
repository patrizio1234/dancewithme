# Ignore Peevski

Този проект съдържа разширения за няколко от по-популярните уеб браузъри, показващи предупредителен екран, когато отваряте сайтове, свързани пряко или косвено с групата на Делян Пеевски и КТБ.

Може да следите за новини около това разширение и тази инициатива в [ignorepeevski.tumblr.com](http://ignorepeevski.tumblr.com/).

## Инсталация

### Google Chrome

Инсталирайте приложението от [Chrome Web Store](https://chrome.google.com/webstore/detail/%D0%B4%D0%B0%D0%BD%D1%81withme/lmcpmmnecclemnhobkplkgpjjddgnkej?hl=bg&gl=001).

### Opera Next

Инсталирайте от [сайта с добавки на Opera](https://addons.opera.com/en/extensions/details/danswithme/?display=bg)

### Firefox

Инсталирайте от [сайта за разширения на Mozilla](https://addons.mozilla.org/en-US/firefox/addon/danswithme/)

## Добавяне на нови домейни

Ако смятате, че разширението трявба да включва още домейни, редактирайте файла `common/blocked_domains.js`, добавете домейн името в списъка и изпълнете `./build`. След това, направете pull request, като в описанието се обосновете защо смятате, че този домейн трябва да бъде блокиран.

## Допринасяне с други промени 

Ако искате да допринесете по друг начин за развитието на това разширение:

* Fork-нете репозиторията
* Клонирайте вашето копие в някоя папка на компютъра си
* Изпълнете `./build`

### Google Chrome

* Отворете [chrome://extensions](chrome://extensions)
* Включете "Developer mode"
* Изберете "Load unpacked extension..." и посочете папката, в която сте клонирали репозиторията, подпапка `chrome/`
* Презаредете таба с [chrome://extensions](chrome://extensions) (`Cmd` + `R` или `F5`) и промените ви ще бъдат засечени
* Следете за грешки в нормалната конзола на браузъра

Документацията за [разработка на разширения за Google Chrome се намира тук](https://developer.chrome.com/extensions/getstarted.html).


### Mozilla Firefox

* От Firefox менюто, изберете `Tools / Add-ons`
* Изберете "Install Add-on From File..." и посочете файла `firefox/dancewithme.xpi`
* Рестартирайте браузъра

## Други браузъри

Ако искате да направим такова за други браузъри, отворете едно issue и ще дискутираме въпроса там.

## Лиценз

Правата за използването на разширението се определят от MIT лиценза. Копие от него можете да откриете във файла с име `LICENSE`.

## Защо съществува това разширение?

Медиите, притежавани от Делян Пеевски, са известни със своята некачествена журналистика. Материалите в тях могат да бъдат:

- Необективни
- Съдържащи непроверени или неверни факти
- Без втора гледна точка
- Силно манипулативни

Горното е непълен списък.

Импресия по импресия - медийна империя!

![#ignorepeevski](http://24.media.tumblr.com/243dfc6696cf71013636c403ee1473f2/tumblr_mon26lM2W71swvzfoo1_r1_1280.jpg)
