# I can has frontend skillz: fat FAQ

Платиновая шапка платинового треда.

## Содержание:

1. [Интро](#Интро)
2. [Верстка](#Верстка)
3. [JavaScript](#javascript)
4. [Основы](#Основы)
5. [Продолжение](#Продолжение)
6. [Advanced](#advanced)
7. [Дополнительно](#Дополнительно)

## Интро

 Этот FAQ посвящен вкату во фронтенд-разработку. Данное вступление было составлено со слов уже опытных скриптовоенов для неуверенных в себе инфантилов. Прежде, чем задать очередной глупый вопрос — прочитай.

Первое. Фронтенд в 2017+ — это не:

*  Верстка
*  Клепание лендингов
*  Фриланс на дядю Ваню за два доширака
*  Колупание в вордпрессе, жумле и проприетарных конструкторах сайтов

Если вы умеете верстать и натягивать свои горячие бутстрапы на влажный вордпресс, при этом получаете копейки, а HR-ы почему-то не названивают вам по 20 раз на дню — не стоит экстраполировать свой неудачный опыт на всю отрасль в целом. Фактически, вы ничего не умеете.

Вакансии на чистых верстальщиков периодически мелькают в ДС и ДС2, как правило это или позиция "джуна на вырост", или "нужен человек-мультитул PHP|JQ|Верстка|Заправка принтеров". В мусохрансках вакансии на верстал — нонсенс, хотя в треде иногда отчитываются аноны, которые таки СМОГЛИ устроиться верстальщиком. Но расчитывать на это не стоит.

Итак, в 2017 фронтенд-разработчик — это продвинутый формошлеп, который, в основном, копается в JS. Это не значит, что изучать верстку не обязательно — даже если на работе верстать не будете, на собеседовании обязательно спросят какую-нибудь фигню.

Что нужно знать на позицию фронтенд-разработчика начально-среднего уровня:
  * HTML + CSS
  * JS с ES6-синтаксисом
  * Фреймворк_нейм. Лучший выбор для новичка по прежнему React. Еще есть Vue, но работы сильно меньше, и знаний в процессе изучения получите сильно меньше. Если генетика одарила вас железобетонной силой воли — можно потыкать Angular 5(ха).

Попутно изучается работа с эмулятором терминала ("пресвятая консолечка"), git, инструменты сборки (как минимум webpack, желательно пощупать gulp), npm|yarn.

Все теоретические навыки обязательно подкрепляются практикой. Это может быть калькулятор, крестики-нолики, сверстанный статик-сайтец или даже полноценная приложуха на фреймворке.

### Ответы на вопросы для самых маленьких

> Можно ли вкатиться в `age` лет?

[Можно](https://ru.hexlet.io/blog/posts/learn-to-program-at-30)

> Можно ли вкатиться без знаний программирования, матана, функционирования гипертекст протоколов и т.д.?

Можно.

> Можно ли вкатиться без высшего образования или с дипломом заборостроительного ВУЗа?

Можно.

> __Ни верю!!11 Мой друг Вася в 25 уже тимлид, а я в свои 23 только вкатываться начну...__

В любой цивилизованной стране 25 лет - это начало самостоятельной жизни, но забитые СНГ-омежки продолжают думать, что к 25 надо уже родить 3 детей, взять ипотеку и построить карьеру, после чего сдохнуть, ведь биологическая программа выполнена, родина-мать не забудет, а дети продолжат заданную линию поведения.

Короче, если у тебя возникают вопросы касательно вышки, времени, возраста - не вкатывайся. В мире много чего интересного, можешь стать верхолазом-монтажником, например. Вкатываться во фронтенд исключительно ради денег - плохая идея.

> Есть ли работа?

Да. В обозримые `n` лет была, есть и будет. В России это чуть ли не единственный рынок на котором сейчас растут зарплаты.

> Мой друг Ваня-копирайтер сказал, что кризис, работу вайти не найти, джуниоров не берут и вообще лучше выпилиться. Это правда?

И да, и нет. На рынке катастрофическая нехватка *грамотных* специалистов. Конторы разной степени говнистости готовы судиться за любого миддла, появление где-нибудь на hh открытого резюме сениора вызывает жуткий резонанс, начинается охота, интриги, драмы, эйчары прыгают из окон. В тоже время рынок перенасыщен дебилами-выпускниками гикбрейнс-гоайти и прочих итвднов, которые ничего не умеют, а на работу хотят, бегают, размахивают своими сертификатами курсов. Ну вы понели, да?

_TL;DR_: если вы осилите нечто большее, чем прикручивание плагинов и верстку на бутстрапе, сможете показать, что вы владеете актуальным стеком технологий — работа сама вас найдет даже без реального опыта.

> Кто-то уже приходил к успеху/расскажите кулстори/кто-то уже работает/кто-то съехал от мамки

Да, и не один а двое, азазаза.

Ладно. Да приходили, и да, вряд-ли кто-то тут получает удовольствие от повторения одних и тех же слов в тысячный раз. Пожалуйста, избавь нас от этой головной боли.

> Сколько времени займет обучение?

Много. В среднем, путь с нуля до уровня более-менее шарящего реактодебила/вьюдераста потребуется около года.

> Могу ли учить верстку/JS после работы по 2 часа?

Можете, но это вряд ли будет эффективно.

> Слышал что для устройства на работу нужно портфолио

Мы тоже такое слышали, но обычно под "портфолио" понимают профиль на гитхабе и ссылочки на завершенные/активные проекты (если позволяет NDA|заказчик). В принципе, если не лень — можно даже простенький сайтецкий о себе забацать.

> Почему фронтенд вообще существует? Есть же CMS/конструкторы-сайтов.

Жизнь сложнее конструктора.

## Верстка

### Основы

#### Что нужно знать:
  * HTML:
    *  Структура документа
    *  Разметка
    *  Тэги
    *  Атрибуты
  * CSS:
    *  Основные селекторы (без фанатизма)
    *  Основные свойства (отступы, размеры, цвет, шрифты и прочее)
    *  Наследование свойств, каскад, вложенность
    *  Основы сетки: блочная модель, флоаты, инлайн-блоки
    *  Свойства position
  * Все вместе:
    *  Типовая разметка текста
    *  Картиночки, ссылочки
    *  Таблички, списочки
    *  Формы, инпуты, лэйблы

#### Итого

Умение сверстать простенькую статику, без новомодных фич, без семантики, модульности, бэмов, шмэмов, респонсивности и прочего. На все про все около месяца.

#### Где учить, что читать?

  *  Старт: интерактивные курсы хтмл академии: https://htmlacademy.ru/program бесплатных вполне хватит, но можно и оплатить подписку (лучше не надо). Можно спросить в треде скриншоты теории продвинутых интерактивов: их регулярно трут отовсюду, кроме меги, поэтому приходится перезаливать.
  *  http://htmlbook.ru/
  *  https://webref.ru/
  *  Базовый интенсив все той же академии (брать на торрентах)

Не стоит увлекаться просмотром сотен тысяч курсов, вебинаров, туториалов и прочему. Как правило хтмл академии + хтмлбука более, чем достаточно для усвоения азов верстки.

#### Очень подробный верстка-гайдлайн

Стоит как минимум бегло просмотреть и прикинуть, что к чему: http://webmasters.teamdev.com/

---

### Верстка advanced

#### Что нужно знать:
  * HTML5:
    *  "Новые" тэги
    *  "Новые" атрибуты
    *  Формы и инпуты
    *  SVG
    *  Семантика
  * CSS:
    *  Продвинутые селекторы (опять же без фанатизма, но знать полезно)
    *  Градиенты, трансформации, анимации, переходы и прочие приколюхи
    *  Флексы, гриды
    *  Респонсив ("адаптивность")  
    *  Любой CSS фреймворк (bootstrap / foundation)
    *  SVG
  * О дивный новый мир:
    *  Автоматизация (галп, нпм / йарн + скрипты)
    *  Организация структуры проекта
    *  Препроцессоры (любой на выбор)
    *  Какой-нибудь template engine (pug, как один из самых популярных)
    *  Работа в терминале (да, анон, удаляй свой github desktop, вот прямо сейчас)
  * Не помешает:
    * Умение самостоятельно размечать и реализовывать динамические штуки (слайдер, например)
    * Примерное понимание как работает js || jq

На все про все: еще месяц-два-три в худшем случае.

#### Итого получаем:

Готовую личинку верстальщика, которая сможет заверстать статику любой сложности по данному макету. Теоретически можно работать за дошираки, см интро.

#### Где учить, что читать?

  *  Продолжаем: интерактивные курсы хтмл академии https://htmlacademy.ru/program читаем про флексы, препроцессоры и т.п. Материалы платных интерактивов можно спросить в тредике
  *  http://htmlbook.ru/
  *  https://webref.ru/
  *  [Продвинутый интенсив академии-2016](http://nnmclub.to/forum/viewtopic.php?t=1032872()
  *  Верстка по БЭМ на примерах: http://habrahabr.ru/post/203440/
  *  http://ru.bem.info/ - документация БЭМ от Яндекса
  *  http://getbootstrap.com/ - Бутстрап. Полезная штука, кто бы что ни говорил.   
  *  http://habrahabr.ru/post/114256/ - чеклист верстки. Несколько устарел, но, в целом, актуален.
  *  http://habrahabr.ru/hub/webdev/ - тематический хаб, иногда проскальзывают полезные публикации.
  *  Документация препроцессоров: http://sass-lang.com/ http://lesscss.org/ http://stylus-lang.com/

__Дополнительные ресурсы, которые могут быть полезными на данном этапе:__

  *  http://tympanus.net/codrops/ - еженедельная подборка новостей
  *  http://www.smashingmagazine.com/ - многое отсюда так или иначе переведено на русский, ресурс полезный для развития
  *  http://css-tricks.com/ - много готовых шаблонов для решения часто встречающихся задач  
  *  http://codepen.io/ - ресурс с кучей интересных примеров кода
  *  http://www.html5rocks.com/en/ - туториалы от гугла
  *  http://frontender.info - неплохой ресурс, но редко обновляется
  *  http://www.sitepoint.com/html-css/, https://medium.com/tag/css, http://css-live.ru/ выборка статей по теме.  
  *  http://nicothin.pro/page/console-windows
  *  http://nicothin.pro/page/kak-komfortno-rabotat-s-github-v-konsoli-windows
  *  Материалы интенсивов академии: https://github.com/tsergeytovarov/htmlacademy-basic-additional-material
  *  Материалы от teamtreehouse, любезно слитые аноном (англ): https://mega.nz/#!PgRiXJLK!Ske0xNBPaC9Rm_3mV9c5Zoz6rD5Yna-V7pI-yzJOB_A

> __А книги, книги то будут? Хочу книжку!__

Книги надо выбирать индивидуально. Если по HTML/CSS, то желательно, чтобы книга была не старше 2012 года, ну или хотя бы переиздана. Читай все что интересно. В любом случае это будет полезно.

* http://frontendbookshelf.ru/ - список полезных книг. Большинство актуальны, можно выбрать по языку, технологии и конкретному уровню знаний. Первооочередную литературу желательно брать оттуда.
* http://scanlibs.com/ что-то типа хранилища айти книг. Скачать книги можно бесплатно. Там есть дохуя всего. Если в свободном доступе не найдете, попробуйте поискать там.

#### Что верстать?
  *  Макеты для верстки, тоже от академии. Все из их рассылки, поэтому лучше бы тебе на нее подписаться. https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
  *  Вполне годные макеты можно найти здесь: http://freebiesbug.com/psd-freebies/
  *  Moose - http://yadi.sk/d/g74XxFDUPyrob  - корпоративный сайт
  *  Hotel - http://yadi.sk/d/5VEeZriDPyroK  - туристический сайт
  *  Seabird - http://yadi.sk/d/XVt_w-TrPyrp4  - корпоративный сайт
  *  Appmo - https://yadi.sk/d/Ofaah1ZsTNrLf  - лендинг приложения
  *  Cleanwhite - https://yadi.sk/d/b05MLaKITNrLy  - корпоративный сайт
  *  Shoes - https://yadi.sk/d/Cp7qki0yTNrM4  - интернет-магазин обуви.
  *  Крупный пак с псдшками для практики - https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
  *  http://dbfreebies.co/templates  http://freebiesbug.com/psd-freebies/website-template/ - cайты с макетами.
  *  http://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/  как работают браузеры.

#### В чем работать?

В чем угодно. Универсальный выбор - Atom | VSCode, в них можно будет полноценно продолжать работать при переходе на жс+фреймворки. Для тех, у кого дрова вместо рабочей станции подойдет Sublime. А вообще даже NP++ подойдет.

#### Что делать дальше?
Сверстать пару макетов для закрепления и переходить к JS. Не помешает сразу зацепить гит, основные команды в терминале, поколупать какую-нибудь бубунту на виртуалке. Само собой использование галпа / вебпака, отсутствие боязни терминала, понимание того, как браузер рендерит страничку, как лучше подключать шрифты/стили/скрипты и т.п.

#### Гайд от анона по гитхабу:

>http://randomfederation.github.io/

**[⬆ К оглавлению](#Содержание)**

---

## JavaScript

Мир верстки был довольно дружелюбным и понятным. Мир JS — это особый мир особого программирования, где любая задача может иметь десятки решений, где существуют сотни и тысячи инструментов, библиотек и подводных камней. Добро пожаловать в ад.

![alt text](http://i.imgur.com/lKnOgq7.png "Welcome to hell")

Шутка. На самом деле, все довольно хорошо, и есть устоявшийся мейнстримовый набор:
* Версия языка — ES6+
* Инструмент для сборки — Webpack
* Фреймворк — React + Redux | Vue + Vues | Angular5 для любителей экстремальных видов самоудовлетворения

### Основы

Лучший учебник на JavaScript на русском языке — [Кантор](http://learn.javascript.ru/) . Ультраплатиновая ультрагоднота. Особое внимание следует уделить первой части, которая рассказывает непосредственно про язык, посколько DOM, события и другие API браузера про которые рассказано во второй части, абстрагируются фреймворком. [Английская версия](https://learn.javascript.info) поддерживается автором в более актуальном состоянии, рекомендуется читать ее.

Нужно выполнять все задания. Это сложно, вы будете много ошибаться, это нормально. Что-то не получается? Не вычисляются фибоначчи? Рекурсия не рекурсирует? Отвлекитесь, отдохните, перечитайте теорию, попробуйте снова. Составьте алгоритм псевдокодом или вовсе своими словами.

Кантора можно разнообразить видосами и другими сайтами. Одна и та же вещь, объясненная много раз разными словами, становится понятнее:
* [Codecademy](https://www.codecademy.com/ru/learn/javascript) — бесплатный интерактивный курс.
* [Treehouse](https://teamtreehouse.com) и [Codeschool](https://www.codeschool.com) — тоже интерактивные курсы, платные.
* Канал [LearnCode.academy](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw) — Очень годный канал (англ). Смотреть ES5 и ES6.

Основной справочник по JS — [Mozilla Developer Network](http://developer.mozilla.org/en/docs/Web/JavaScript). Хотите почитать про промисы — пишите в гугле `promises mdn`.

---

## Продолжение

Мы научились находить простые числа, пора переходить к чему-то более серьезному. Прототипы, основы функционального программирования, DOM, углубиться в ES6.

*  Продолжаем читать Кантора: заканчиваем первую часть, читаем DOM, события. Материалы касательно работы с графикой можно опустить.
*  Канал [Sorax](https://www.youtube.com/user/ArtSorax) очень клевый канал по "олдскульной ванилле" (ES5, прототипы и прочие прелести жизни). Алярм: может закипеть мозг, объясняет очень быстро и четко, никаких вам "переменная это коробочка с данными"
*  Канал [Code Dojo](https://www.youtube.com/channel/UCY10FZglXJ8RL3xB04VpykQ) Тоже очень дельные видео, в основном по ЕС6+. Есть немного реакта, редакса и ангуляра - это лучше опустить (пока)
*  [Coursera](https://www.coursera.org/) Неплохой ресурс, но почти все платно
*  [Codeschool](http://codeschool.com/) Аналогично
*  [JS the Right Way](http://jstherightway.org/) Невообразимо объемный гайд: книги и статьи для изучения, описание фреймворков, стайлгайды и т.п. Рекомендуем ознакомиться
*  [/r/ javascript](https://www.reddit.com/r/javascript/) Реддит, для любителей

> __А... книжки?__

Само собой. Ниже представлены только материалы со свободным лицензированием (бесплатные), их более, чем достаточно. Раздел давно не обновлялся, потому что книги мало кто читает и ссылочки на новье никто не присылает, а создатели сего фака следать не успевают. Так что смотрите сами, нужно оно вам или нет. И да, почти все на английском, увы и ах.

### ES5:

*  [Выразительный JavaScript](http://eloquentjavascript.net/) - годнота, есть перевод и на русский, можно ограничиться только этой книгой
*  [Speaking JavaScript](http://speakingjs.com/es5/)
*  [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262/index.html)
*  [JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)

### ES6:

*  [Exploring ES6](http://exploringjs.com/es2016-es2017/index.html/)
*  [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/)

### Функциональный / асинхронный JS:

*  [Guide to functional programming](https://drboolean.gitbooks.io/mostly-adequate-guide/)
*  [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) Воистину легендарная книга

### Фреймворки / библиотеки:

*  [Ng-book](https://dmitriy-kiryushin.gitbooks.io/ng-book-2-ru/content/) полная книжка по Ангулару (устарело)
*  [React для начинающих](https://maxfarseer.gitbooks.io/react-course-ru/content/) краткий туториал (код из примеров устарел и может не работать без доработки напильником, однако основные принципе верны, прочитать можно)
*  [React Redux](https://maxfarseer.gitbooks.io/redux-course-ru/content/) такой же туториал по редаксу

> Что уметь?

Писать рабочий, хорошо структурированный, модульный код ОБЯЗАТЕЛЬНО на ES6 (для этого придется потрогать вебпак + бабель). Для практики стоит придумать задачу - неважно, насколько шаблонной / скучной / избитой она будет. Легендарный тудулист вполне подойдет для оттачивания навыков: здесь вам и события, и работа с ДОМ, и обработка форм, можно прикрутить хранилище данных (localStorage, firebase) или даже "полноценный" бэкенд. К тому же, кода вполне достаточно для того, чтобы, например, написать приложение, используя MVC.

> Мой друг Самуил-Реактовец сказал, что прототипы не нужны. Можно их пропустить, уж очень они мудреные? Есть же ES6!

Нельзя. Во-первых, это один из самых часто встречающихся вопросов на собеседовании. Во-вторых, это основа основ JS, прототипы были, есть, будут и никуда не денутся, никакие ES6 классы и готовые либы этого не изменят. Понять прототипы === понять, как работает все, что на них завязано. А на них завязано вообще все. Ну, почти.

Все теоретические навыки обязательно подкрепляются практикой. Решайте задачки Кантора, каты на [CodeWars](https://www.codewars.com/?language=javascript). Попробуйте написать что-нибудь несложное, пусть код будет похож на императивную простыню: главное, чтобы работало.

---

## Advanced

### Промышленное программирование

Пришло время преодолеть разрыв между легкими и приятными учебными заданиями и суровой практикой с которой вам предстоит столкнуться на работе.

#### Выбор фреймворка

Первое и единственное решение, которое нужно принять: на какой фреймворк садиться. На текущий момент (2017) на выбор 2 с половиной стула:
##### Первый стул - [React](https://facebook.github.io/react/)

Традиционный выбор редакции 2015-2016-2017(? время покажет)(upd: на конец 2017 года Реакт по прежнему универсальный выбор). Строго говоря сам по себе Реакт - это view layer library, под фреймворком понимают комбайн типовида react + router + redux.
Ньюфажикам его советуют по многим причинам:
  *  JS центричность. Копаясь в Реакте вы невольно углубляетесь в понимание JS
  *  Относительно высокий, но "плоский" порог входа: придется изучить все, что так или иначе пригодится после (включая вебпак)
  *  Много вакансий
  *  Куча обучающих материалов
  *  Прекрасное коммьюнити

Реакт уже перерос пубертатный период, его постоянно допиливают, 20 апреля обещают запуск файбера (upd: таки запустили с полугодовым опозданием), в общем, сейчас у Реакта все хорошо, а будет еще лучше.

##### Второй стул -[Angular 5](https://angular.io/)

Трудное дитя гугла, поимело провальный старт, из-за чего его считают плохим, негодным. В него умудрились впихнуть невпихуемое (например всю библиотеку RXJS полностью).
Фичи:
  *  Высокий порог входа
  *  Все искаропки, в том числе свой cli, своя система сборки, централизованный стартер-кит и много чего
  *  Коммьюнити из суровых энтерпрайзеров, которые видели некоторое shit и которых ничем не испугать

Ангулар перешел на SemVer, текущая версия 5 (?). На него постепенно переводятся крупные энтерпрайз проекты, любители ковыряться в легаси будут рады.

##### Половинка стула - [Vue 2](https://vuejs.org/)   

Раздел про Вью переписывался раз 10, но каждый раз получалась куча субъективного бреда, поэтому вкратце. Главный плюс, он же и минус - предельная простота. Первую рабочую приложуху на Вью можно написать за два дня, не имея вообще никаких познаний в JS. Следующий момент - Вью выстрелил уже более полугода назад, а работы все нет. Но вообще штука неплохая, если делать нечего - можно поколупать, благо Вью понять даже проще, чем предсказать результаты выборов в России.
UPD: появились вакансии, где требуется опыт работы с Вью, но их мало и только в крупных городах.

> Но Реакт не фреймворк, мне так на курсах гикбрейнса сказали!

Есть строгий критерий, определяющий грань между фреймворком и кастомым кодом/библиотекой. Для тех, кому впадлу [читать](https://habrahabr.ru/post/116232/) - Реакт вполне себе фреймворк. Свои недовольства можете отправлять в спортлото.

---

Это были стулья, а теперь __табуретки__:

  *  Angular первый — устарел морально, физически. Вакансии по-прежнему есть, в основном - поддержка дымящегося легаси. Учить просто так смысла нет.
  *  [Backbone](http://backbonejs.org/) - good night, sweet prince. Можно поколупать, чтобы прикинуться олдэфагом. Но не нужно, вас все равно раскусят.
  *  [Inferno](https://infernojs.org/) - good night, sweet prince. Кговавый Фэйсбук купил разработчика, теперь он сидит в подвале без паспорт и пилит Реакт (тру стори);
  *  [Preact](https://preactjs.com/) - если видите в описании очередного фреймворка фразу 'this is fast lightwieght fork of React' - сразу закрывайте вкладку.  
  *  [Aurelia](http://aurelia.io/) - заявлено, что это самый мощный, гибкий и современный (прямая цитата) JS фреймворк в мире, которым никто не пользуется. Ну вы поняли.
  *  [Mithril](http://mithril.js.org/) - позиционируется как супер-пупер альтернатива этим вашим реактам, ангуларам и вью. Но никем не используется. Такие дела.
  *  [Polymer](https://www.polymer-project.org/1.0/) - долгострой гугла, пишется конкурирующей с ангуларом командой. Ходят слухи, что выйдет вместе с релизом нативных веб компонентов. А может и не выйдет.
  *  [Ember](http://emberjs.com/) - говорят, все, что придумали, уже давно было в Эмбере. Может так и есть, но эмбер даже на переписанном движке уж очень тормозной. Изредка мелькает в вакансиях (ищут спеца с опытом от 3 лет чисто на эмбере, что как бы намекает)
  *  [ExtJS](https://www.sencha.com/products/extjs/) - энтерпрайз монстр, который продается за 9к долларов и вертится где-то на задворках древних корпоративных ЦРМ и нигде больше не встречается.

Вышеперечисленные штуки указаны сугубо в ознакомительных целях.

---  

Лучшие ресурсы для начала обучения - официальная документация. Что у Реакта, что у Ангулара, что у Вью она очень подробная и "человеческая". Ну и куда же без вспомогательных видосиков? Вот самые годные (по мнению многих анонов):

*  Уже упомянутый канал [LearnCode.academy](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw) - здесь лучший туториал по реакту, совместно с документацией этого долго быть достаточно для освоения на хорошем уровне.
*  Канал [Mindspace](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w) Годнота от парня с забавным акцентом, есть и Реакт, и А2, и немного Vue JS
*  [Egghead](https://egghead.io/courses) прекрасный ресурс, где есть все. Много бесплатного, в том числе подробнейший скринкаст по редаксу от создателя редакса

Хорошая отправная точка для изучения фреймворков и других продвинутых тем — [Egghead](https://egghead.io). Но даже он способен дать только самую базу. Документация, случайные статьи на Медиуме и твиттеры разработчиков станут вашими новыми друзьями. И, конечно, эксперименты и практика. Кривая обучения в этом месте резко становится очень крутой и преодолеть ее с первого раза получается не у всех. Не отчаивайтесь, отдыхайте и пробуйте еще.

Пишите пет-проеты. Они станут основой вашего портфолио при устройсте на работу. Попутно разбирайтесь с остальными вещами.

#### Сборка

Если вы собирайтесь разбивать JS-код на несколько файлов и нормально использовать `import/export`, то вас настигнет вопрос сборки приложения. Сейчас для этого принято использовать [Webpack](https://webpack.js.org) — очень гибкий и мощный, но сложный в настройке инструмент, который интерпретирует все файлы как JS-модули. [Скринкаст Кантора](https://www.youtube.com/playlist?list=PLDyvV36pndZHfBThhg4Z0822EEG9VGenn) поможет вам разобраться с базовой конфигурацией.

#### Расширение JS / Полезные инструменты

Если вы уже состояфшийся фронт и вам кажется, что развиваться больше некуда - вынуждены вас разочаровать.

*  [TypeScript](https://www.typescriptlang.org/) - пожалуй, самый популярный и полезный яп, расширяющий возможности ванильного JS. Очень рекомендуем попробовать. Будем откровенны - если вы читаете этот раздел, то TS вы уже ДОЛЖНЫ знать, так что давайте, бегом-бегом читать документацию, благо она у ТС шикарная.
*  [ClojureScript](https://clojurescript.org/) - кложура, которая транспайлится в ЖС. Один из автором, будучи воннаби лисподебилом, дичайше котирует и кложуру, но сам на ней, конечно же, не пишет, потому что не любит jvm. В вакансия мелькает сравнительно часто.
*  [elm](http://elm-lang.org/) - автор лично порывался написать на нем рабочий хеллоуворлд, но руки не дошли. Функциональщина с приятным ароматом хаскеля и замечательным синтаксисам, от которого у неофитов выпадают глаза. До поры до времени активно форсился, но потом утратил позиции в связи с новым хайп-продуктом от господа бога нашего и пророка Фейсбука (о чем ниже). `Личная имхуечка - стоит внимания, если хочется чего-то для себя и нечего делать`
*  [ReasonML](https://reasonml.github.io/) - окамль с человеческим лицом от фейсбука. Как, вы не знаете, что такое окамль? Быстро гуглить! Ребята из фейсбука довольно давно и успешно используют окамль для внутренних нужд (к примеру - Flow написан полностью на Окамле), и видимо решили, что коммьюнити нуждается в новой парадигме, а жс с его ошибками проектирования должен отправиться на свалку. Энивей, ReasonML - это окамль, строгий, старый, никому (почти) не известный и слегка чудаковатый язык, несомненным плюсом которого является отсутствие нелепостей, присущих JS, и оче быстрый рантайм (плюс-минус равный идеально вылизанному коду на плюсах). Вопрос о перспективах и популярности Ризона остается открытым, учить ради денег пока не стоит. [Полезная ссылочка для инетерсующихся](http://2ality.com/2017/11/about-reasonml.html)
*  [Dart](https://www.dartlang.org/) - авантюра гугла по созданию полноценной альтернативы JS со своим интерпретатором и андефайнедами. Попросили упомянуть - упомянули, вот. Есть такая штука, да, наверное, даже клевая (а может и нет). Больше сказать о нем нечего, в вакансиях почти не встречается, реального продакшн кода на нем лично составители FAQ и их знакомые не имели.
*  [CoffeeScript](http://coffeescript.org/) - морально и физически устарел, все хорошее, что в нем было, перекочевало в ES6+. Иногда встречается в дремучих проектах, написанных на рубя с шаблонами. Учить не нужно, да и нечего там учить.
*  [Flow](https://flow.org/en/docs/getting-started/) - костыль от фейсбука, призванный исправить фатальный недостаток (тм) жаваскрипта - слегка шизанутую утиную типизацию. Штука хорошая, но, к сожалению, проигрывает тайпскрипту в стабильности и готовности к продакшну (у автора полностью сломался конфиг при обновлении flow с 0.59 до 0.61). А еще у флоу ужасная, кошмарная, отвратительная докумнтация. Но попробовать стоит, займет всего пару дней.

TL;DR: берите TypeScript, не прогадаете. Все остальное (кроме кофе) можно потрогать на досуге, опять же - не прогадаете. Кофе не нужно, пейте чай. Шутка. Нет, правда, кофескрипт не нужен.

Не забываем про линтинг [ESLint](http://eslint.org) который избавит от совсем уж тупых ошибок/опечаток и приучит к написанию красивого кода.

Навыки работы с консолью и гитом подразумеваются для любого разработчика по умолчанию, об этом часто даже не пишут в вакансии.

### Устройство на работу

Причесываем гитхаб, маскируем коммиты уровня "ффыарфрырыффф". Составляем адекватное резюме, рассылаем его по всему хедхантеру, небо и Аллаха в копию. Впрочем, если в резюме видны зачатки мысли (и вы в ДС), то HR скоро вас сами найдут и обрушат лавину звонков и писем.

Основная часть собеседования это рассказ о себе и своих проектах. Заранее подумайте что сказать. Если есть ноутбук, то приходите с ним и показывайте проекты вживую.

#### Платиновые вопросы на собеседованиях

Большая часть из них разобрана здесь: [Вопросы кандидату на должность front-end разработчика](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Russian)

Решения тестовых задач в функциональном стиле — очки х2: `спорный момент`. Инсайд: из-за наплыва "адептов функциональщины" и "детей ES6" могут потребовать написать "чистое решение" на ES5. Передаем привет всем, кто опустил / не понял прототипы.

**[⬆ К оглавлению](#Содержание)**

---

## Дополнительно

### Английский
> Нужен ли английский и как его выучить? Я и так уже по самую макушку завален материалами!

Нужен. Большая часть самых клевых материалов - на английском, большая часть влиятельных / шарящих людей в коммьюнити - не из СНГ и общаются на английском или своем родном (передаю привет одному голландцу). Плюс это нехилый бонус к трудоустройству.

Ниже будет подборка ответов / материалов по англйискому от анонов, за что им спасибо.

> Как учить?

Практикой и погружением:


*  Приложения на смартфон Duolingo и Memrise. Первый бесплатен, второй платен, но бесплатной версии более чем достаточно. У Duolingo есть и [веб-версия](https://www.duolingo.com/)
*  Чтение англоязычного интернета. Даже банальной Википедии будет достаточно. Еще можно читать газеты и издания мирового уровня типа:
  *  [vox](http://vox.com)
  *  [economist](http://www.economist.com/)
  *  [NYT](http://www.nytimes.com/)
  *  [BBC](http://www.bbc.com/)
  *  [spectrum](http://spectrum.ieee.org/)
  *  [combinator](https://news.ycombinator.com/)
*  Фильмы на английском с сабами
*  Игры на английском с сабами
*  Интерфейс во всех приложениях на английском


Для грамматики подойдет курс от Полиглот 16 уроков. Еще стоит отметить простой переводчик по клику для хрома LinguaLeo. Другое полезное расширение - Grammarly, смотрит за правильностью того как ты пишешь на английском и высвечивает ошибки, неправильную грамматику, подсказывает правильный порядок слов и так далее. А ещё он может показывать значение слова по клику, с полноценной выдачей о значении этого слова.

Читать поначалу можно словарём - Chrome, Google Dictionary дополнение. Кликанье на все непонятные слова во время чтения/раздумья над смыслом статьи должно стать привычкой.

Обычно сначала трудно но через пару недель чувствуешь результат, потом уже стабильное улучшение.

### Прочие мелочи
> Правда ли, что JS был придуман за 10 дней? Мой друг Вася-Джавист сказал, что это ущербный недоязык, хах.

Первая спецификация действительно была разработана и утверждена в кратчайшие сроки, и предназначалась для решения примитивнейших задач (оживить картинку, подсветить кнопочки). С тех пор прошло очень много времени, от первой спецификации осталась только общая концепция да парочка досадных багов, которые нельзя пофиксить из-за обратной совместимости (typeof Null, ага).

> Нужен ли матан?

Скажем так: лишним не будет, но и без него frontend разработчик не чувствует себя ущербным. Полезными будут знания дискретной математики, теории чисел и графов, а также основы теории алгоритмов (впрочем, это уже CS). Все это вполне изучается самостоятельно в свободное время. Для практики в этом деле лучше использовать Python: он более строгий, лаконичный и понятный. Хотя и на ES6 получаются очень даже красивые решения всяких олимпиадных задачек.

> Хочу фрилансить!

Фрилансить версталой - гиблое дело. Да и вообще фрилансить без опыта работы - гиблое дело. Да и вообще фрилансить в 2017 - гиблое дело. Адская конкуренция, кривые ТЗ, неадекватные заказчики, баны на апворках и прочие прелести ждут. Но никто не мешает попробовать.

> У вас тут все неправильно написано и вообще

FAQ полностью открыт для доработок и редактирования, присылайте свои pr или пишите в тредике, например. Обоснованные правки будут внесены.

> А где старая паста?

Вот же: http://pastebin.com/ytWW0UfU

> Нет-нет, где __та самая__ старая паста?

Здесь: http://pastebin.com/tvvwC7uz

**[⬆ К оглавлению](#Содержание)**
