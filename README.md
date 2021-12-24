# Software-testing-theory
QA_Bible
# Manual part 1
<br>
<h1>----- Введение (F.A.Q.) -----</h1>

<h2>Хочу войти в айти (в разработку) через тестирование, хороший план?</h2>
Это имело смысл (и то спорно) несколько лет назад, но после эпидемии и агрессивной рекламы работы в IT со стороны обучающих компаний появились тысячи выпускников курсов по тестированию, так что этого "легкого пути вкатиться в айтишечку" уже нет и не будет. Конкурс на одно место на удаленку может доходить до нескольких сотен человек. Конечно, в разработке тоже конкуренции поприбавилось, но если вы нацелены стать программистом, то никакие вхождения через другие специальности не имеют ни малейшего смысла - тестирование и разработка - разные профессии и опыт работы джуниор тестировщиком вам практически ничем не пригодится, вы лишь потратите время на подготовку к собеседованиям (а требования теперь весьма высокие), а потом еще на обучение непосредственно той специальности, куда хотели изначально, т.к. опыт по сути не релевантен и спрашивать будут с нуля.

Доп. материал:
<a href="https://www.youtube.com/watch?v=qiCjqqtWP7I&t=31s">Мифы о тестировании #2 / О чем не говорят на курсах по тестированию / Правда о работе в IT</a>
<h2>Хочу зарабатывать много денег, мне сюда?</h2>
Первые зарплаты будут мизерными (особенно учитывая конкурс на места), а подняться выше по карьерной лестнице без искреннего интереса и запала не получится, тестирование - слишком обширная область знаний. Без внутренней мотивации к ежедневному самообучению не получится зарабатывать больше чем в любой другой профессии на старте. Так что сферу деятельности стоит менять только если вы всю жизнь чувствовали, что занимаетесь не тем, а тут прям вот екнуло и хочется взахлеб осваивать именно тестирование. Но даже в этих случаях нужно понимать, что далеко не всем компаниям требуются профессиональные тестировщики, разработчикам в этом смысле найти применение своим навыкам куда проще. Именно по этой причине существует отток уже проработавших какое-то время в тестировании специалистов в другие направления: менеджмент, чистая автоматизация, разработка. Фактически они просто не смогли найти дальнейшие пути развития своих навыков. Соответственно и зарплаты здесь в среднем ниже, чем на многих специальностях в IT. 
Статистика зарплат: <a href="https://career.habr.com/salaries">Россия</a>, <a href="https://jobs.dou.ua/salaries/">Украина</a>, <a href="https://salaries.dev.by/">Беларусь</a>
<h2>Хочу работать удаленно джуном, это возможно?</h2>
К сожалению, шансы устроиться на удаленку специалисту без опыта довольно низкие - высокая конкуренция, к тому же компании охотнее берут начинающих в офис (так эффективнее обучать). Поэтому попробовать, конечно, стоит, но рассчитывать на это особо не нужно. Да и начинающему действительно продуктивнее находиться в офисе вместе со всей командой, в гуще событий.
<h2>Что реально должен знать junior? А что спросят на собеседовании?</h2>
Вот пара ссылок на карты знаний для тестировщиков, но можете на просторах найти и другие.
<a href="https://github.com/anas-qa/Quality-Assurance-Road-Map">https://github.com/anas-qa/Quality-Assurance-Road-Map</a> <a href="https://www.mindmeister.com/ru/1324282825/junior-qa?fullscreen=1">https://www.mindmeister.com/ru/1324282825/junior-qa?fullscreen=1</a> <a href="https://www.mindmeister.com/ru/1558647509?t=973hdS2AKb">https://www.mindmeister.com/ru/1558647509?t=973hdS2AKb</a>
Некоторые компании подробно расписывают на своих порталах ожидания от каждой стадии развития сотрудника, тоже не проблема найти, по этой же теме много видео на Youtube (<a href="https://www.youtube.com/watch?v=l9ezImoh5ac&feature=emb_logo&ab_channel=LearnQA%3A%D0%9E%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D1%89%D0%B8%D0%BA%D0%BE%D0%B2">раз</a>, <a href="https://www.youtube.com/watch?v=wDHZsoZIxcY&ab_channel=LearnQA%3A%D0%9E%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D1%89%D0%B8%D0%BA%D0%BE%D0%B2">два</a>, <a href="https://www.youtube.com/watch?v=tzOhRHVX6ko&ab_channel=QAQC">три</a>, <a href="https://www.youtube.com/watch?v=5DGuDT98EC0&ab_channel=AzatZakuanov">четыре</a>, …). Еще один ориентир – просто открыть и почитать вакансии в своем городе, что в среднем у вас требуется от новичка.
Если же попытаться выделить самые частые вопросы на собеседованиях, то получится примерно следующее:
<ul>
<li>Что такое тестирование?
</li>
<li>Зачем оно нужно?
</li>
<li>QA/QC/Тестирование - разница?
</li>
<li>Что такое качество ПО?
</li>
<li>Верификация и валидация?
</li>
<li>Severity priority?
</li>
<li>Виды, типы, уровни тестирования?
</li>
<li>Виды документации? Тест-план, тест-кейс, чек-лист?
</li>
<li>Что такое баг? Его жизненный цикл?
</li>
<li>Техники тест-дизайна?
</li>
<li>SDLC, STLC; Методологии разработки ПО?
</li>
<li>Мобильное тестирование: его особенности (и в частности жизненный цикл Android и iOS приложения)?
</li>
<li>Клиент-серверная архитектура?
</li>
<li>API?
</li>
<li>Базовое знание сетей: HTTP(S), его методы, коды ответов, Query-параметры, REST/SOAP, JSON/XML
</li>
<li>Базы данных: что такое SQL, СУБД, основные команды (особенно любят джойны).
</li>
<li>Инструменты: Chrome DevTools, Postman, Charles/Fiddler, GIT, TMS
</li>
<li>Практика: тестирование форм или какого либо сайта, приложения  (в частности  составление тест-кейсов и баг-репортов), придумать хороший summary для репорта, определение severity/priority; SQL запросы; что-нибудь на "подумать".
</li>
</ul>

В случае gamedev могут еще спросить про последнее во что играл, что понравилось/не понравилось и т.п.

Помимо вышеперечисленного нужно помнить об английском языке и его важности в работе. Конечно, есть небольшое количество компаний, которые не станут уделять этому внимания, но если в вакансии указан необходимый уровень владения языком, то будьте готовы к тому, что как минимум попросят ответить на какой-нибудь простенький житейский или из списка HR-вопросов на английском. В отдельных случаях, где явно указана необходимость разговорного уровня, все собеседование вполне может пройти на английском.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/funcorp/blog/426759/">Образ современного тестировщика. Что нужно знать и уметь</a>
</li>
<li><a href="https://habr.com/ru/company/funcorp/blog/491188/">Что должен знать тестировщик бэкенда</a>
</li>
<li><a href="https://www.youtube.com/watch?v=Yd0Z-35GbK4&feature=youtu.be&ab_channel=%D0%9B%D1%91%D1%88%D0%B0%D0%9C%D0%B0%D1%80%D1%88%D0%B0%D0%BB">Тестировщик ПО / что делает QA Engineer / интервью с Artsiom Rusau QA</a>
</li>
<li><a href="http://mymonday.by/qa-market-research-august-2019">Исследование рынка труда в QA</a>
</li>
<li><a href="https://ru.hexlet.io/blog/posts/gid-po-professii-testirovschik-chem-zanimaetsya-skolko-zarabatyvaet-chto-nado-znat-i-gde-uchitsya">Гид по профессии тестировщик: чем занимается специалист в сфере QA, сколько зарабатывает, что надо знать и где учиться</a>
</li>
<li><a href="https://habr.com/ru/company/otus/blog/530290/">Качественное тестирование ПО</a>
</li>
</ul>
<h2>С чего начать обучение?</h2>
Начать нужно с ознакомления с тестированием и я считаю, что лучший выбор для этого - книга Романа Савина "Тестирование дот ком". После ознакомления я бы посоветовал выбрать по отзывам в коммьюнити хороший базовый онлайн-курс и пройти его, либо по возможности пойти на офлайн-курсы местной компании с возможностью последующего трудоустройства - это вообще лучший вариант. Если нет желания или возможности, то после Савина стоит начать с книги Святослава Куликова "Тестирование программного обеспечения. Базовый курс" и далее уже имея общее представление и понимая азы равномерно восполнять пробелы, подготавливаясь к собеседованиям.
Тестирование – самая широкая область в IT. Т.к. теория хоть и не сильно сложная, но ее настолько много, что невозможно изучить все, нужно пытаться как можно быстрее найти применение своим навыкам. Начать стоит с классики типа тестирования форм, тренировочных сайтов с дефектами специально для тестировщиков и т.п. Не стоит забывать и о софт скилах и базовой грамотности. Бич многих современных тестировщиков даже высокого уровня – безграмотность, поэтому смолоду тренируйтесь в составлении тестовых артефактов.
По мере роста компетенций как можно раньше стоит начать проходить собеседования и пытаться устроиться на любую стажировку, вообще любой вариант, где вы сможете применять знания и указать этот опыт в резюме, т.к. без опыта сейчас найти работу очень трудно. Если нет никаких оффлайн вариантов, как было у меня, можете регистрироваться на краудтестинговых платформах (но зачастую это гиблое дело + многие работодатели игнорируют такой опыт), искать в тг-каналах возможности протестировать какие-то проекты за бесплатно (иногда там ищут волонтеров за опыт) либо придумать такой тестовый проект себе самому - взяться тестировать любимый( или какой-либо популярный) сервис, но делать это близко к тому, будто это ваша реальная работа. То есть чтобы было что потом рассказать и показать результаты (тест-кейсы, баг-репорты и т.п.). Именно поэтому эффективнее обучаться когда есть опытный наставник, который дает приближенные к реальным задания и дает обратную связь по выполненной работе.
Когда вы устроитесь на свою первую работу, спустя некоторые время сможете начать готовиться к дальнейшему развитию и выбору направления, ведь никто не заставляет всю жизнь быть ручным тестировщиком. Вы можете сосредоточиться на mobile/web/desktop платформе, профессионально развиваться в менеджеры или автоматизацию, готовиться к узкой специализации — безопасности или performance и т. д., а также сфокусироваться на подготовке по перспективным направлениям:
<ul>
<li>ML&AI в QA
</li>
<li>QAOps
</li>
<li>Тестирование IoT
</li>
<li>Тестирование больших данных
</li>
</ul>
Помимо прочего, специалисту, планирующему развиваться профессионально, желательно как можно раньше начать сначала посещать релевантные митапы и конференции, а когда-нибудь и начать выступать в роли докладчика. Также не лишними будут различные сертификации (хотя бы тот же ISTQB разных уровней). 

Дополнительные ссылки:
<a href="https://habr.com/ru/company/jugru/blog/541334/">Тестирование в эпоху ИИ</a>
<a href="https://sarahelson81.medium.com/12-important-software-testing-trends-for-2021-you-need-to-know-b23e8f7d6cb7">12 Important Software Testing Trends for 2021 You Need to Know</a>
<a href="https://dou.ua/lenta/columns/how-to-learn/">Как учиться, чтобы научиться</a>

<h2>Какие есть полезные ресурсы кроме этого?</h2>

Telegram:
Must have! Каналы это: знакомство с коммьюнити, живое общение, уникальный опыт тысяч коллег; богатая история сообщений, где поиском по истории сообщений можно найти все что угодно; в шапке каждого канала закреплено сообщение со своим набором полезностей. Кроме того, некоторые каналы специализируются на мониторинге нового полезного материала с основных порталов, так что можно даже не погружаться с головой в хабр, доу, медиум и т.п., вам отберут все самое полезное. В конце концов, в этих каналах публикуются анонсы грядущих онлайн-мероприятий, чтобы ничего не упустить.
<ul>
<li>Всем новичкам сюда! Тренировочные собеседования, интересные обсуждения https://t.me/qa_interviews
</li>
<li>Огромный чат, ориентированный на джуниоров https://t.me/qajuniors
</li>
<li>Огромный чат, ориентированный на уже работающих в сфере тестирования <a href="https://t.me/qa_ru">https://t.me/qa_ru</a>
</li>
<li>Чат по геймдеву https://t.me/qa_gamedev
</li>
<li>Обсуждение курсов, отзывы о них https://t.me/qa_courses
</li>
<li>Тут можно размещать свое резюме <a href="https://t.me/qa_resumes">https://t.me/qa_resumes</a>
</li>
<li>Тут отзывы о компаниях https://t.me/qa_bad_company
</li>
<li>Обсуждение финансов https://t.me/qa_fin
</li>
<li>Публикация книг <a href="https://t.me/booksqa">https://t.me/booksqa</a>
</li>
<li>Авторский бложик https://t.me/shooandendlessagony
</li>
<li>Репосты новых статей и полезных ссылок с разных сайтов: 
</li>
<ul>
<li><a href="https://t.me/qa_wiki">https://t.me/qa_wiki</a>
</li>
<li><a href="https://t.me/serious_tester">https://t.me/serious_tester</a>
</li>
<li><a href="https://t.me/qa_pro">https://t.me/qa_pro</a>
</li>
<li><a href="https://t.me/qa_chillout">https://t.me/qa_chillout</a>
</li>
<li><a href="https://t.me/yetanotherqa">https://t.me/yetanotherqa</a>
</li>
</ul>
</ul>

Youtube-каналы:
<ul>
<li>Вадим Ксендзов (тренировочные собеседования!) https://www.youtube.com/channel/UC6hNNlCXv1ZgdGpziNf83RA
</li>
<li>Mikhail Portnov: <a href="https://www.youtube.com/channel/UCDbzkNMBNZJBKP4C-9qGw4Q">https://www.youtube.com/channel/UCDbzkNMBNZJBKP4C-9qGw4Q</a>
</li>
<li>Podlodka Podcast <a href="https://www.youtube.com/channel/UCOei1E1Vqq10S913OEqTWGw">https://www.youtube.com/channel/UCOei1E1Vqq10S913OEqTWGw</a>
</li>
<li>QA START UP: <a href="https://www.youtube.com/channel/UCAlCZby7zJHzyhOmS8issDQ">https://www.youtube.com/channel/UCAlCZby7zJHzyhOmS8issDQ</a>
</li>
<li>Компания DINS: <a href="https://www.youtube.com/channel/UCmJYB3hvbF3AlVh9HFeXX3A">https://www.youtube.com/channel/UCmJYB3hvbF3AlVh9HFeXX3A</a>
</li>
<li>Artsiom Rusau QA Life <a href="https://www.youtube.com/c/ArtsiomRusauQALife">https://www.youtube.com/c/ArtsiomRusauQALife</a>
</li>
<li>Леша Маршал <a href="https://www.youtube.com/channel/UCTVciJQp8eYwKLLQIl-iSJw">https://www.youtube.com/channel/UCTVciJQp8eYwKLLQIl-iSJw</a>
</li>
<li>Тестирование: <a href="https://www.youtube.com/channel/UC9VeXtf7fcCJUfmZ_cyweXA">https://www.youtube.com/channel/UC9VeXtf7fcCJUfmZ_cyweXA</a>
</li>
<li>Fest Group: <a href="https://www.youtube.com/channel/UClTnsvgTiW2YcfP1tcI2oKA">https://www.youtube.com/channel/UClTnsvgTiW2YcfP1tcI2oKA</a>
</li>
<li>QAGuild: <a href="https://www.youtube.com/channel/UCHtyBZ2XbtsRmNiAxh48RGg">https://www.youtube.com/channel/UCHtyBZ2XbtsRmNiAxh48RGg</a>
</li>
</ul>

Web:
<ul>
<li><a href="https://blog.noveogroup.ru/2020/01/testovye-ploschadki-dlya-trenirovok/">Большой список тестовых площадок для тренировок</a>
</li>
<li>https://cantunsee.space/
</li>
<li>https://software-testing.ru/ (+форум)
</li>
<li>http://www.mobileappstesting.com/
</li>
<li><a href="https://www.guru99.com/">https://www.guru99.com</a>
</li>
<li><a href="https://www.softwaretestingmaterial.com/">https://www.softwaretestingmaterial.com/</a>
</li>
<li><a href="https://www.ministryoftesting.com/">https://www.ministryoftesting.com/</a>
</li>
<li><a href="http://www.testingeducation.org/BBST/foundations/">http://www.testingeducation.org/BBST/foundations/</a>
</li>
<li>https://www.learnqa.ru/ 
</li>
</ul>

Книги:
Очень хвалят вот эту подборку <a href="http://okiseleva.blogspot.com/2014/02/blog-post_6.html?m=1">http://okiseleva.blogspot.com/2014/02/blog-post_6.html?m=1</a>
<br>
Подборка книг по ИБ <a href="https://habr.com/ru/company/mailru/blog/282700/">https://habr.com/ru/company/mailru/blog/282700/</a>
<br>
<a href="https://drive.google.com/file/d/173NvdE4dnKxxbo0mdoPwcDMcdjCWaUTM/view">Перевод книги Ли Копланда "A Practitioner's Guide to Software Test Design"</a>

Еще встречал вот такой список:
<ul>
<li>Роман Савин «Тестирование Дот Ком, или Пособие по жестокому обращению с багами в интернет-стартапах» (можно сказать худ.лит, «для чайников»)
</li>
<li>Святослав Куликов «Тестирование программного обеспечения. Базовый курс.»
</li>
<li>Арбон Джейсон, Каролло Джефф, Уиттакер Джеймс «Как тестируют в Google»
</li>
<li>Борис Бейзер «Тестирование черного ящика. Технологии функционального тестирования программного обеспечения и систем»
</li>
<li>Рекс Блэк «Ключевые процессы тестирования»
</li>
<li>Гленфорд Майерс, Том Баджетт, Кори Сандлер «Искусство тестирования программ.»
</li>
<li><a href="https://www.amazon.com/s/ref=dp_byline_sr_book_1?ie=UTF8&field-author=Microsoft+Corporation&text=Microsoft+Corporation&sort=relevancerank&search-alias=books">Microsoft Corporation</a> - Performance testing Guidance for Web Applications
</li>
</ul>

Мобильные приложения:
<ul>
<li><a href="https://play.google.com/store/apps/details?id=com.strimqa.android.app.strimqa&hl=ru&gl=US">StrimQa — ваш карьерный навигатор! </a>
</li>
</ul>
Другие сборники материала и ответов на вопросы:
<ul>
<li><a href="https://drive.google.com/file/d/1x9oeWuPiVqytNYTKunJgLLarq4IBdeTY/view?usp=sharing">https://drive.google.com/file/d/1x9oeWuPiVqytNYTKunJgLLarq4IBdeTY/view?usp=sharing</a>
</li>
<li><a href="https://www.istqb.org/downloads/category/2-foundation-level-documents.html">https://www.istqb.org/downloads/category/2-foundation-level-documents.html</a>
</li>
<li><a href="https://github.com/ultragreatester/how-to-qa">https://github.com/ultragreatester/how-to-qa</a>
</li>
<li><a href="https://habr.com/ru/post/257529/">https://habr.com/ru/post/257529/</a>
</li>
<li><a href="https://docs.google.com/file/d/18yJqziwhxz5khP1mtrme1mNJW95mwrgc/edit?filetype=msword">https://docs.google.com/file/d/18yJqziwhxz5khP1mtrme1mNJW95mwrgc/edit?filetype=msword</a>
</li>
</ul>

Словари терминов (в т.ч. элементов интерфейса):
<ul>
<li><a href="https://habr.com/ru/company/wrike/blog/475558/">Словарик айтишника или Что? Где? Куда? Часть 1</a>
</li>
<li><a href="https://habr.com/ru/company/jugru/blog/538698/">IT-словарик для не-айтишников</a>
</li>
<li><a href="https://docs.google.com/spreadsheets/d/1LgytNrl7ep9wlr3A_3u0NitQsrZzKhEQwC-OTQfbLAM/edit?usp=sharing">https://docs.google.com/spreadsheets/d/1LgytNrl7ep9wlr3A_3u0NitQsrZzKhEQwC-OTQfbLAM/edit?usp=sharing</a>
</li>
<li><a href="https://docs.google.com/spreadsheets/d/1r5Ek83V4IHkOsW52DyVT8iJepR20oZu_Jy5vAkq7SrI/edit?usp=sharing">https://docs.google.com/spreadsheets/d/1r5Ek83V4IHkOsW52DyVT8iJepR20oZu_Jy5vAkq7SrI/edit?usp=sharing</a>
</li>
<li><a href="https://borodaboroda.com/blog/elementy-interfejsa-sajta/">Элементы интерфейса сайта</a>
</li>
<li><a href="https://habr.com/ru/company/youla/blog/540768/">UI-элементы и жесты в мобильных приложениях</a>
</li>
<li><a href="https://vk.com/@zapiskisedogotestera-slovar-testirovschika">Словарь тестировщика</a>
</li>
</ul>

Чек-листы и идеи для тестов:
<ul>
<li><a href="https://habr.com/ru/post/524784/">Где брать идеи для тестов (подборка полезных ссылок)</a>
</li>
<li><a href="https://habr.com/ru/post/537510/">37 источников тест-идей</a>
</li>
<li><a href="https://checkvist.com/checklists/476089">Checklists Base :)</a>
</li>
<li><a href="https://habr.com/ru/post/534190/">Чек-лист тестирования мобильных приложений</a>
</li>
<li><a href="https://habr.com/ru/company/funcorp/blog/525538/">Дополняем чек-лист тестирования при обновлении иконки и сплеша в мобильных приложениях</a>
</li>
<li><a href="https://software-testing.ru/images/stories/library/checklist-mobile-app-testen.pdf">Чеклист для тестирования мобильных приложений </a>
</li>
<li><a href="https://habr.com/ru/post/525192/">Чек-лист для тестирования числового поля</a>
</li>
<li><a href="https://habr.com/ru/post/542422/">Чек-лист тестирования WEB приложений</a>
</li>
<li><a href="http://www.mobileappstesting.com/2012/07/05/testing-checklist-for-mobile-applications/">Testing checklist for mobile applications</a>
</li>
<li><a href="https://ontestpad.com/library/200/ios-app-testing-template">iOS App Testing Template</a>
</li>
<li><a href="https://www.flickr.com/photos/softwaretestingclub/7159412943/sizes/o/in/photostream/">Getting started with mobile testing</a>
</li>
<li><a href="http://apps.testinsane.com/mindmaps/Mobile-Testing-In-a-Nutshell">Mobile testing in a nutshell</a>
</li>
<li><a href="https://www.koreyhinton.com/blog/ios/am-i-really-done-testing.html">Am I Really Done Testing?</a>
</li>
<li><a href="http://www.testingdiaries.com/mobile-testing-checklist/">Mobile Testing Checklist</a>
</li>
<li><a href="https://www.appqualityalliance.org/files/AQuA_testing_criteria_for_Android_v1.3_oct_2_2012.pdf">Testing Criteria for Android Applications</a>
</li>
<li><a href="https://i.imgur.com/DDWnzbS.png">A mnemonic for mobile app testing</a>
</li>
<li><a href="http://www.kohl.ca/articles/ISLICEDUPFUN.pdf">Test Mobile Applications with I SLICED UP FUN!</a>
</li>
<li><a href="https://testingideas.wordpress.com/2014/08/17/mobile-app-test-coverage-model-long-fun-cup/">Mobile App Test Coverage Model : LONG FUN CUP</a>
</li>
<li><a href="https://hsto.org/getpro/habr/upload_files/079/663/f2f/079663f2fc528456afb1367b4096d266.png">Тестирование новой фичи</a>
</li>
</ul>
<h2>Основные инструменты тестировщика?</h2>
<ul>
<li>Мультитул: DevTools;
</li>
<li>Снифферы: Charles Proxy, Fiddler;
</li>
<li>Тестирование API: Postman, SoapUI;
</li>
<li>Тестирование производительности: JMeter;
</li>
<li>Тестирование безопасности: Kali linux,  Santoku Linux + drozer, OWASP ZAP, …;
</li>
<li>Тестирование UI/UX: Figma, Zeplin, любой mindmap-like продукт;
</li>
<li>Фермы устройств для тестирования мобильных приложений: BrowserStack, Xamarin, AWS;
</li>
<li><a href="https://szadorozhnyi.medium.com/%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-android-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B9-%D1%87%D0%B0%D1%81%D1%82%D1%8C-1-87a6d6a9e817">Инструменты тестирования Android приложений</a>
</li>
<li>Системы контроля версий: GIT;
</li>
<li>Взаимодействие с базами данных: язык SQL, системы СУБД;
</li>
<li>Системы CI/CD: Jenkins/TeamCity;
</li>
<li>Прочее: мессенджеры, баг-трекинговые системы и TMS, генераторы тестовых данных и т.п.
</li>
</ul>

DevTools:
В каждый современный браузер встроены инструменты разработчика — они позволяют быстро отловить и исправить ошибки в разметке или в коде. С их помощью можно узнать, как построилось DOM-дерево, какие теги и атрибуты есть на странице, почему не подгрузились шрифты и многое другое:
<ul>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#2">Проверка ответа сервера</a>
</li>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#3">Проверка мобильной адаптивности</a>
</li>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#4">Проверка мобильной выдачи</a>
</li>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#5">Региональная поисковая выдача</a>
</li>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#6">Изменение дизайна</a>
</li>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#7">Анализ протокола безопасности</a>
</li>
<li><a href="https://siteclinic.ru/blog/seo-instrumenty/seo-chrome-devtools/#8">Анализ скорости загрузки страницы</a>
</li>
</ul>
<a href="https://habr.com/ru/company/ruvds/blog/486692/">Средства консоли Chrome, которыми вы, возможно, никогда не пользовались</a>
<br>
Postman:
Постман представляет собой мультитул для тестирования API. В нем можно создавать коллекции запросов, проектировать дизайн API и создавать для него моки (заглушки-имитации ответов реального сервера), настраивать мониторинг (периодическая отправка запросов с журналированием), для запросов возможно написание тестов на JS, есть собственный Runner и т.д. Однако постман сложно назвать подходящим инструментом для серьезной автоматизации ввиду сложности поддержки тестов, но при этом он хорошо подойдет в простых случаях или как инструмент поддержки а анализа: проверка работоспособности endpoint, дебаг тестов, простая передача информации о дефектах (можно сохранить запрос в curl, ответ в json и т.п.). Postman также может работать без графического интерфейса (newman).
<ul>
<li>Аналог: <a href="https://hoppscotch.io/">https://hoppscotch.io/</a>
</li>
<li><a href="https://www.youtube.com/watch?v=55l6XIEK9l0&ab_channel=QASTARTUP-ITTrainingCenter">Курс Тестирование ПО. Занятие 30. POSTMAN. Ручное тестирование API | QA START UP</a>
</li>
<li><a href="https://robertgorter.medium.com/api-testing-using-postman-87cf1c40b82c">API testing using Postman</a>
</li>
</ul>

Proxy (снифферы трафика):
Charles — инструмент для мониторинга HTTP/HTTPS трафика. Программа работает как прокси-сервер между приложением и сервером этого приложения. Charles записывает и сохраняет все запросы, которые проходят через него и позволяет их редактировать.
<ul>
<li><a href="https://habr.com/ru/company/redmadrobot/blog/269109/">Charles: незаменимый тул в арсенале QA-инженера</a>
</li>
<li><a href="https://www.youtube.com/watch?v=74v5lpOug8c&feature=youtu.be&ab_channel=BogdanOvsiyuk">Breakpoints charles proxy Подмена данных</a> 
</li>
<li><a href="https://habr.com/ru/company/youla/blog/527648/">Как приручить Charles Proxy?</a>
</li>
<li><a href="https://www.apriorit.com/dev-blog/591-proxies-for-application-testing">Using Web Debugging Proxies for Application Testing</a>
</li>
<li><a href="https://telegra.ph/Perehvat-SSL-trafika-s-Android-prilozheniya-01-26">Перехват SSL трафика с Android-приложения</a>
</li>
<li><a href="https://trykov.ru/certificate-and-public-key-pinning/">Certificate and Public Key Pinning</a>
</li>
</ul>

Тестирование безопасности:
<ul>
<li><a href="https://habr.com/ru/company/tomhunter/blog/456892/">Чем искать уязвимости веб-приложений: сравниваем восемь популярных сканеров</a>
</li>
<li><a href="https://itfb.com.ua/instrumenty-testirovaniya-bezopasnosti/">20 мощных инструментов тестирования на проникновение в 2019 году</a>
</li>
<li><a href="https://itsecforu.ru/2019/08/06/%F0%9F%92%A3-10-%D0%BB%D1%83%D1%87%D1%88%D0%B8%D1%85-%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2-%D1%81%D0%BA%D0%B0%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F/">10 лучших инструментов сканирования уязвимостей для тестирования на проникновение – 2020</a>
</li>
<li><a href="https://habr.com/ru/company/alexhost/blog/530110/">Пентест веб сайта с помощью Owasp Zap</a>
</li>
<li><a href="https://habr.com/ru/company/alexhost/blog/535396/">Проверяем безопасность приложений с помощью Drozer</a>
</li>
</ul>

GIT:
Git - это консольная утилита, для отслеживания и ведения истории изменения файлов, в вашем проекте. Чаще всего его используют для кода, но можно и для других файлов. Например, для картинок - полезно для дизайнеров.
С помощью Git-a вы можете откатить свой проект до более старой версии, сравнивать, анализировать или сливать свои изменения в репозиторий.
Репозиторием называют хранилище вашего кода и историю его изменений. Git работает локально и все ваши репозитории хранятся в определенных папках на жестком диске.
Так же ваши репозитории можно хранить и в интернете. Обычно для этого используют три сервиса: <a href="https://github.com/">GitHub</a>, <a href="https://bitbucket.org/">Bitbucket</a>, <a href="https://gitlab.com/">GitLab</a>
Знать команды нужно для:
"1. Если надо что-то сделать с гитом по SSH.
2. Если надо сравнить диффы огромных файлов. Vimdiff вытянет, многие тулы сдохнут или будут сильно тормозить.
3. Тулы часто тупят и работают неправильно.
4. Хорошие тулы платные)"  (с) @anton_smolianin
<br>
В любом случае, даже нажимая кнопки, требуется понимать, как это работает под капотом хотя бы на элементарном уровне.

<a href="https://t.me/qa_pro/480">Все что нужно для работы с GIT</a>
<ul>
<li><a href="https://habr.com/ru/post/541258/">Git для новичков (часть 1)</a>
</li>
<li><a href="https://habr.com/ru/company/oleg-bunin/blog/468177/">Git изнутри и на практике</a>
</li>
<li><a href="https://habr.com/ru/company/skillbox/blog/534972/">Git, я хочу все отменить! Команды исправления допущенных ошибок</a>
</li>
</ul>

SQL:
<a href="https://t.me/qa_pro/490">Все что нужно для работы с SQL</a>:
<ul>
<li>Официальные сайты
</li>
<ul>
<li><a href="https://www.sqlite.org/index.html">SQLite</a>
</li>
<li><a href="https://www.mysql.com/">MySQL</a>
</li>
<li><a href="https://www.postgresql.org/">PostgreSQL</a>
</li>
</ul>
<li>GUI клиенты
</li>
<ul>
<li><a href="https://www.mysql.com/products/workbench/">MySQL Workbench</a>
</li>
<li><a href="https://www.heidisql.com/">HeidiSQL</a>
</li>
<li><a href="https://www.navicat.com/en/products/navicat-for-mysql">Navicat for MySQL</a>
</li>
<li><a href="https://www.devart.com/dbforge/mysql/studio/">dbForge Studio for MySQL</a>
</li>
</ul>
<li> Основы SQL 
</li>
<ul>
<li><a href="https://www.amazon.com/Learning-SQL-Generate-Manipulate-Retrieve/dp/1492057614/ref=sr_1_1?dchild=1&keywords=sQL&qid=1613292997&s=books&sr=1-1">Алан Бьюли "Изучаем SQL"</a>
</li>
<li><a href="https://www.amazon.com/Head-First-SQL-Brain-Learners/dp/0596526849/ref=sr_1_10?dchild=1&keywords=sQL&qid=1613292997&s=books&sr=1-10">Линн Бейли "Изучаем SQL"</a>
</li>
<li><a href="https://www.w3schools.com/sql/sql_intro.asp">W3C Introduction to SQL</a>
</li>
<li><a href="https://www.guru99.com/sql.html">guru99 | SQL Tutorial for Beginners: Learn SQL in 7 Days</a>
</li>
</ul>
<li>Продвинутый уровень
</li>
<ul>
<li><a href="https://www.amazon.com/SQL-Cookbook-Query-Solutions-Techniques/dp/1492077445/ref=sr_1_2?dchild=1&keywords=sQL&qid=1613292997&s=books&sr=1-2">Энтони Молинаро "SQL. Сборник рецептов"</a>
</li>
<li><a href="https://www.amazon.com/SQL-Bible-Alex-Kriegel/dp/0470229063/ref=sr_1_1?dchild=1&keywords=sQL+bible&qid=1613293063&s=books&sr=1-1">Алекс Кригель "SQL. Библия пользователя"</a>
</li>
<li><a href="https://www.amazon.com/SQL-Complete-Reference-James-Groff-dp-0071592555/dp/0071592555/ref=mt_other?_encoding=UTF8">Джеймс Грофф, Пол Вайнберг, Эндрю Оппель "SQL Полное руководство. Третье издание." </a>
</li>
</ul>
<li>Практика
</li>
<ul>
<li><a href="https://sql-academy.org/ru">SQLAcademy | Онлайн тренажер с упражнениями по SQL</a>
</li>
<li><a href="https://sqlbolt.com/">SQLBolt | Introduction to SQL</a> 
</li>
<li><a href="https://www.w3schools.com/sql/trysql.asp?filename=trysql_op_in">W3C | The Try-SQL Editor</a>
</li>
<li><a href="https://www.hackerrank.com/domains/sql">HackerRack SQL</a>
</li>
<li><a href="https://www.sql-ex.ru/?Lang=0">Упражнения по SQL</a>
</li>
<li><a href="https://www.learnqa.ru/sql_test">Тест на знание SQL</a>
</li>
<li><a href="https://www.db-fiddle.com/">https://www.db-fiddle.com/</a>
</li>
</ul>
<li>Shit happens
</li>
<ul>
<li><a href="http://www.sqltutorial.org/wp-content/uploads/2016/04/SQL-cheat-sheet.pdf">SQL Cheat Sheet</a>
</li>
<li><a href="https://tproger.ru/translations/sql-recap/">Основные команды SQL, которые должен знать каждый программист</a> 
</li>
<li><a href="https://tproger.ru/articles/sql-interview-questions/">27 распространенных вопросов по SQL с собеседований и ответы на них </a>
</li>
</ul>
</ul>

Mind maps:
<ul>
<li><a href="https://presium.pro/blog/software_for_maindmapping">12 программ и сервисов для создания майндкарт</a>
</li>
<li><a href="http://okiseleva.blogspot.com/2020/01/mind-map.html">Как нарисовать карту приложения (mind map)</a>
</li>
<li><a href="https://habr.com/ru/company/badoo/blog/418353/">Mind map вместо тест-кейса, или Как визуализация позволяет тестировать приложение быстрее</a>
</li>
<li><a href="https://habr.com/ru/post/539756/">Mind Map в помощь тестировщику</a>
</li>
<li><a href="https://habr.com/ru/post/515990/">Mind Map в тестировании — или легкий способ тестировать сложные приложения</a>
</li>
</ul>

TMS:
<a href="https://habr.com/ru/post/522474/">Топ-12 лучших систем управления тестированием 2020</a>

<h2>Как вообще происходит процесс найма?</h2>
Все зависит от компании и в меньшей степени от уровня позиции. В среднем это выглядит так:
<ol>
<li>Отклик на вакансию;
</li>
<li>*Опционально: выполнение тестового задания, п.2 и п.3 могут меняться местами;
</li>
<li>Скрининг по телефону (небольшая беседа с HR);
</li>
<li>Полноценное собеседование с HR;
</li>
<li>Техническое собеседование, п.4 и п.5 иногда делают за раз;
</li>
<li>*Опционально: собеседование с боссом;
</li>
</ol>
<h2>Качества, которыми нужно обладать тестировщику?</h2>
<ul>
<li>Развитые софт-скиллы (например, уметь в коммуникацию, не перебивать собеседника и т.п.);
</li>
<li>Общая грамотность;
</li>
<li>Умение обучаться;
</li>
<li>Пытливый ум и желание выяснить первопричину проблемы;
</li>
<li>Устойчивость к рутине;
</li>
</ul>

Доп. материал: 
<a href="https://telegra.ph/Mif-ob-obraze-myshleniya-v-testirovanii-02-10">Миф об образе мышления в тестировании</a>
<h2>Как составить резюме?</h2>
Кратко о базовых рекомендациях.
Резюме стажера или джуниора – ровно 1 страница (имеется в виду вариант в файле, а не на площадках). Помимо PDF желательно иметь вордовскую копию на google-диске. Язык резюме – русский, если нацелены на компании из РФ с клиентами из РФ. В остальных случаях – английский. Лучший вариант оформления шапки:
<img src="https://lh3.googleusercontent.com/IxmsFBh0Fdl1QXs9nyvBCCmYHFHONqHO_iVQvfHg_ychWksh2QAJoEib1q-oM5GIfbT_nWXHNiMdEXJLpRHXVe-pl55D12BZWQKAk-UAfqX7Ytw76crI4_EV0s9C2c0zvsBaePp8">
Просто нормальное фото, ФИО, на какую позицию претендуете, опционально локация и дата рождения, актуальные контакты.
После чего идет раздел с опытом работы (любые практические навыки), где максимально кратко и емко описывается чем конкретно вы занимались. Это самая важная часть резюме. Общее правило - использовать глаголы совершенного вида (сделал то, там-то; а делал, участвовал - ничего о вас не говорит), а еще лучше в формате «зона ответственности + достижения»
Следом – образование и затем ключевые навыки. Не забудьте упомянуть знание иностранных языков. Сориентироваться поможет, например, бесплатный тест EFSET с сертификатом. Никогда не используйте банальные ключевые навыки «ответственный, целеустремленный, …». Только конкретика. Помните, что HR часто ищут по ключевым словам, а вы не должны раздувать ваше резюме всяким мусором. Технологии, инструменты – хороший выбор. Но будьте готовы, что вас по ним детально будут спрашивать в первую очередь.
Раздел «О себе» можно включить, если есть что важного и интересного написать, опять же, коротко и если есть чем выделиться. 
При отклике на вакансию встает вопрос о сопроводительном письме и мне понравилось это мнение:
[Переслано от Vincent Jozeph Mousekewitz] (@V_J_Mousekewitz)
"Рассматривайте свое резюме как коммерческое предложение, а сопроводительное письмо -- как быстрый и понятный ответ на вопрос "почему я должен рассмотреть детальнее именно Ваше предложение". 
Сопроводительные письма почти всегда читают. Другой вопрос, что они почти всегда написаны плохо, сухо и "не цепляют", что автоматически идет в минус. Если не хотите/не можете/не готовы в эпистолярный жанр -- не пишите. Переформатируйте резюме, чтобы за 30 секунд чтения было понятно, какую боль Вы готовы снять заказчику(работодателю) и какими квалификациями для этого обладаете. 
Сопроводительные -- тоже, в каком-то смысле "инструмент". Не надо их писать "чтобы было", такое отношение видно сразу и не играет на руку кандидату.
Однако, если есть "что сказать" -- не держите в себе. Увидели вакансию, считаете себя идеальным кандидатом и готовы аргументировать -- вперед."

Вообще на тему составления резюме в IT есть миллион статей (<a href="https://hurma.work/rf/blog/idealnoe-rezyume-kandidata-mif-ili-realnost-2/">пример</a>) и видео на youtube, да и не стоит исключать фактор личных пристрастий нанимателя, так что следует просто ознакомиться с базовыми рекомендациями, при желании скинуть итоговый вариант на оценку в коммьюнити и заняться более насущными вопросами.
Насчет самих откликов, тут на мой взгляд уместна аналогия с холодными звонками, т.е. не нужно на начальном этапе выбирать место работы так, будто собираетесь в ней состариться. Вообще слать резюме стоит не только откликаясь на вакансии. Есть мнение, что когда компания уже выкинула вакансию на работные сайты, это уже тупик (т.к. не нашли кандидата по своим каналам). Шлите на почты компаний, HR-ов, расширяйте сеть контактов в linkedin и т.п.. Слышал, что активные джуны рассылали по несколько сотен писем в неделю. Стоит ли говорить, что они быстро нашли свою первую работу?

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/470684/">Что писать в резюме, если нет опыта работы</a>
</li>
<li><a href="https://habr.com/ru/post/542952/">Инхаус, фриланс, аутсорс компания: куда приземлиться тестировщику, чтобы не разлюбить профессию и расти как на дрожжах</a>
</li>
</ul>
<h2>Как проходить собеседование?</h2>
Прежде всего, конечно, на него не нужно опаздывать. Стоит прийти немного заранее, оглядеться, привыкнуть к атмосфере и настроиться на нужный лад.
Главное, что нужно сказать о собеседованиях – на них надо ходить. Регулярно. Это отдельный навык, который утрачивается если не практиковать. Не стоит бояться и относиться к ним как к экзамену, вы и сами это поймете на практике. В знаниях это скорее это как калибровка, нахождение ориентира где вы сейчас находитесь и в какую сторону корректировать курс. Прошли – проанализировали – подкачались – повторяете, пока не будет достигнут приемлемый результат. Некоторые советуют даже после устройства на работу периодически ходить на собеседования, чтобы держать этот навык в тонусе и ориентироваться в своей ценности на рынке. 
Если вы ищете первую работу, начать ходить на собеседования нужно как можно раньше еще и потому, что никто не задумывается, как долго в реальности может занять процесс поиска работы. Сначала нужно будет выбить себе возможность пройти интервью. Цифры примерно такие: 10 откликов на подходящие вакансии или 100 рассылкой = 1 собес. 10 не заваленных собесов = 1 оффер. Принятие решения компанией может занимать пару недель. В некоторых компаниях этапов может быть штук до 6. Средне-оптимистичный сценарий предполагает от 2-3 месяцев с нуля до начала работы, но это в случае наличия вокруг выбора и хорошей подготовки у кандидата (а на этот счет тоже многие заблуждаются). В не идеальном случае процесс займет от полугода.
Основное, что хочется сказать про само собеседование:
Узнай о компании, в которую идешь проходить собеседование.
Не скромничай и не занижай свои навыки. Ты, возможно, 50-й кандидат на этой неделе и еще 100 будет после тебя. Если будешь мяться – про тебя забудут, как только ты закроешь за собой дверь. Здоровая гипербола и немного красок еще никому не мешали. Но никогда не переходи в ложь.
Потренируйтесь в самопрезентации, записывая себя на видео и пересматривая. Обычно первое, что вас спросят – «расскажите о себе». Основная задача HR – проверить адекватность кандидата, в некоторых случаях еще соответствие определенному заказу из целевой команды (от возраста до хобби, все что угодно). Помните, что собеседуют в компанию в первую очередь человека, а уже потом специалиста. Кто-то сравнивает собеседование со свиданием, где за час вы должны понять, подходите ли вы друг другу. Вопросы на этом этапе в основном стандартные, ответы на них лучше расписать заранее, но не заучивать. Заученный ответ обычно выглядит нелепо, а вот сформулировать свои мысли заранее и понять себя бывает полезно.
Хороший базовый рассказ о себе определит дальнейший ход собеседования, HR будет копать вглубь от заинтересовавших фактов. Кстати, не на все вопросы вы будете знать ответ и это нормально. Одна из задач рекрутера проверить, как вы себя ведете и как отвечаете, когда не знаете ответ. Или вас попробуют заставить сомневаться в заведомо правильном ответе (в этот момент вы вспомните передачу "кто хочет стать миллионером"). Умение грамотно отстаивать свою точку зрения очень важно для тестировщика. 
Еще хороший совет - всё, что вы скажете, может и будет использовано против вас. В том смысле, что не говорите лишнего или того, в чем плаваете, иначе очень быстро закопаетесь в новых вопросах.
В конце (хотя бывает и в начале) спрашивает собеседуемый! Помните, что это обоюдный процесс? Они выбирают себе кандидата, но и вы выбираете себе компанию. Немного информации для борьбы со стеснением: для компании найм сотрудника очень затратная затея. В крупных компаниях даже есть бонусы сотрудникам за удачную рекомендацию знакомого в размере тысяч 100 и это в контексте затрат на обычный процесс найма просто копейки. Обе стороны заинтересованы закрыть торги прямо здесь и сейчас, так что не бойтесь задавать вопросы и будьте полноценной второй стороной в этих переговорах.
По поводу спросить – вот безжалостный копипаст (есть мнение, что если все это начнет спрашивать начинающий специалист, то на это покрутят у виска. Просто умело и ненавязчиво вплетайте самое важное для вас в беседу и все будет ок):
<ul>
<li>Официальное ли оформление, тип. Белая ли заработная плата? Предусмотрены ли премии?
</li>
<li>Есть ли KPI, что в них входит?
</li>
<li>Какой график работы, как происходят отработки?
</li>
<li>Как часто бывают переработки и оплачиваются ли они?
</li>
<li>Время начала рабочего дня и отношение к опозданиям?
</li>
<li>Схема карьерного роста, матрица компетенций, период и порядок пересмотра з.п.?
</li>
<li>Приветствуется ли инициатива и если нет, насколько она наказуема?
</li>
<li>Есть ли командировки, какие направления и как часто?
</li>
<li>Что входит в социальный пакет и когда он предоставляется?
</li>
<li>Если работа удаленная или частично удаленная — какая техника предоставляется?
</li>
<li>Как организовано рабочее место, что в него входит? Опенспейс или кабинет?
</li>
<li>Есть ли наставничество или менторство в первое время работы в компании?
</li>
<li>Практикуется ли компенсация обучения, заинтересован ли работодатель в сертификации, участии сотрудника в митапах, конференциях и т.п.?
</li>
<li>Как осуществляется контроль за сотрудниками: есть ли тайм-трекеры, камеры и т. д.?
</li>
<li>Наличие спортзала, столовой, душа?
</li>
<li>Наличие библиотеки с актуальной литературой?
</li>
</ul>

Если на собеседовании несколько иерархически подчиненных человек (HR и директор, начальник отдела и директор или топ-менеджер), обратите внимание на модель их общения, на то, слаженно ли они работают, есть ли контакт или же только благоговейное молчание. Команду видно издалека.
<ul>
<li>Как отнеслись к вашему резюме: оно одно из многих и вы здесь «на потоке» или оно лежит одно, и вы в фокусе.
</li>
<li>Как распределено время на собеседование и часто ли отвлекаются его участники, вовремя ли начато общение или вам пришлось ждать больше 15 минут.
</li>
<li>Как вам представили руководителя — с регалиями или нет, по имени-отчеству или имени, формально или неформально. 
</li>
<li>Как отнеслись к ходу решения вами заданий — как к экзамену или как к деловому обсуждению задачи. Это говорит о вашем уровне в глазах собеседующего.
</li>
</ul>

Собеседование на английском языке практическое такое же*, просто из-за языкового барьера могут возникать трудности. Практикуйтесь! И помните, что вашему собеседнику может быть так же трудно, как и вам.
*- при собеседовании в другую страну следует учитывать культурные особенности (да и законодательство), потому что некоторые ценности и взгляды могут совершенно не очевидным образом быть разными и при этом иметь решающее значение. Здесь нужно целенаправленно читать статьи о найме или релокации в интересующую страну, там упоминаются эти нюансы и особенности.
Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/477354/">Вопросы для собеседования — от кандидата к работодателю</a>
</li>
<li><a href="https://habr.com/ru/post/470227/">Как собеседовать работодателя?</a>
</li>
<li><a href="https://habr.com/ru/post/513524/">О чем поговорить на собеседовании с выпускником онлайн-курсов по тестированию</a>
</li>
<li><a href="https://habr.com/ru/company/headzio/blog/529384/">Как QA найти «ту самую» компанию и стать тимлидом</a>
</li>
<li><a href="https://habr.com/ru/company/gms/blog/527916/">Собеседование для QA: резюме, вопросы на интервью, переговоры о зарплате + полезные ссылки</a>
</li>
<li><a href="https://habr.com/ru/company/mailru/blog/522326/">Сценарий идеального технического собеседования</a>
</li>
<li><a href="https://habr.com/ru/post/431514/">Собеседование для собеседующих</a>
</li>
<li><a href="https://github.com/kix/reverse-interview/blob/master/README.md">Обратное собеседование</a>
</li>
<li><a href="https://www.linkedin.com/pulse/%D1%87%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82-%D0%B4%D0%BB%D1%8F-%D0%BF%D0%BE%D0%B4%D0%B3%D0%BE%D1%82%D0%BE%D0%B2%D0%BA%D0%B8-%D0%BA-%D1%81%D0%BE%D0%B1%D0%B5%D1%81%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8E-%D0%BD%D0%B0-%D0%B0%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%BE%D0%BC-mashtalyar/">Чек-лист для подготовки к собеседованию на английском</a> (linkedin, в РФ нужен VPN/proxy)
</li>
</ul>
<h2>Ошибки в работе у начинающих тестировщиков?</h2>
<ul>
<li>Во всем видят дефекты. Как избежать:
</li>
<ul>
<li>Внимательно анализировать требования
</li>
<li>Владеть информацией о том, как должен работать продукт
</li>
<li>Если сомневаешься, что это дефект – спроси БА или ответственного
</li>
<li>Несколько раз перепроверь прежде чем регистрировать дефект
</li>
</ul>
<li>Пытаются сразу все сломать. Как избежать:
</li>
<ul>
<li>Начинать тестирование только с положительных тестов
</li>
<li>Акцентировать внимание на том, что в приоритете для заказчика
</li>
<li>Не проверять редкие сценарии в первую очередь
</li>
</ul>
<li>Боятся задавать вопросы. Как избежать:
</li>
<ul>
<li>Начать понимать, что коммуникация это важная и неотъемлемая часть работы
</li>
</ul>
<li>Не интересуются, кто и за что отвечает, как устроены процессы. Как избежать:
</li>
<ul>
<li>Узнать у ПМ об областях ответственности каждого члена команды
</li>
<li>Узнать у ПМ о всех процессах на проекте
</li>
</ul>
<li>Паникуют при малейшей трудности. Как избежать:
</li>
<ul>
<li>Без паники, п. 3 и 4 помогут разобраться
</li>
</ul>
<li>Пытаются применить сразу все, что изучили. Как избежать:
</li>
<ul>
<li>Помнить, что у каждого вида тестирования своя цель
</li>
<li>Бюджет всегда ограничен, расставлять приоритеты
</li>
</ul>
<li>Задают один и тот же вопрос несколько раз
</li>
<li>Дёргают разработчиков по каждой мелочи (прерывают состояние потока, контекст. Разработка требует держать огромное количество абстракций в голове во время работы над задачей. Это очень легко сбить элементарным вопросом, который находится в первой строчке поисковой выдачи)
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://red-foks.medium.com/%D0%BA%D0%B0%D0%BA-%D0%B2%D1%8B%D0%B6%D0%B8%D1%82%D1%8C-%D0%BD%D0%B0-%D0%BD%D0%BE%D0%B2%D0%BE%D0%B9-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B5-%D0%B8%D0%BB%D0%B8-%D0%BE%D0%BD%D0%B1%D0%BE%D1%80%D0%B4%D0%B8%D0%BD%D0%B3-%D1%81%D0%BD%D0%B8%D0%B7%D1%83-8e95c7c4ac0c">Как выжить на новой работе или онбординг снизу</a>
</li>
<li><a href="https://telegra.ph/SHest-test-person-s-kotorymi-ne-stoit-imet-dela-01-02">Шесть тест-персон, с которыми не стоит иметь дела</a>
</li>
<li><a href="https://ru.hexlet.io/blog/posts/shest-podskazok-novichku-v-testirovanii">Лучше не знать и спросить, чем притворяться, что знаешь, или Шесть подсказок новичку в тестировании</a>
</li>
<li><a href="https://abilmazhinova.medium.com/%D0%BC%D0%BE%D0%B8-3-%D0%BE%D1%88%D0%B8%D0%B1%D0%BA%D0%B8-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D0%B5-%D1%8F-%D1%81%D0%BE%D0%B2%D0%B5%D1%80%D1%88%D0%B0%D0%BB%D0%B0-%D0%BA%D0%B0%D0%BA-junior-qa-engineer-10290234e949">Мои 3 ошибки, которые я совершала как junior QA engineer</a>
</li>
</ul>
<h2>Я – единственный тестировщик на проекте. Что делать?</h2>

<img src="https://lh3.googleusercontent.com/YAepXPiV4qhlJogC3O2wL6e39cwsXb4EmTJT-Wg6esjKnh-ImTO4gwtiFIis9EQBonDnMBd3-TmeNvulahKrJIWma63Z38NFoXg0P2p13XtPUTR0RoXxrnitP1i-BjCv2-cLnBo0">
Начинать знакомство с проектом лучше с интервью. Станьте журналистом. Что из себя представляет структура организации, а именно кто над кем стоит и кто за что отвечает? Где больше всего багов, каким видят тестирование сейчас и какие ожидания в будущем? Оцените зрелость процессов по CMM и TMM, зрелость проекта (новый/старый-зрелый/старые-зрелые где будут глобальные изменения) и команды, определите методологию разработки. Проведите вводную лекцию команде: что такое QA, как оно может помочь, с какими проблемами обращаться и зачем вообще оно надо. Далее в зависимости от всего этого ищем и смотрим соответствующий вебинар/статью и т.п., в крайнем случае можно поинтересоваться у коллег в тематических сообществах, например, в tg. Вообще создавать отдел тестирования обычно нанимают QA Lead, а если вы джун, то либо работодатель не понимает что делает, ожидая от джуниора построения процессов, о которых он в лучшем случае где-то читал, либо от вас хотят чего-то вполне конкретного и проводить целое расследование не придется - наверняка все объяснят еще на собеседовании. В нормальной ситуации вы проведете исследовательское тестирование, составите набор кейсов, задокументируете все текущие баги и в дальнейшем будете заниматься тестированием новых сборок, проверкой исправления найденных дефектов и проведением регрессии. 

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/439128/">Как организовать работу QA. Один практически примененный способ</a>
</li>
<li><a href="https://habr.com/ru/post/467109/">Как QA организовать автоматизацию тестирования на проекте. Один практически примененный способ</a>
</li>
<li><a href="https://habr.com/ru/post/471576/">Как QA выстроить эффективное взаимодействие с разработчиками. Один возможный путь</a>
</li>
<li><a href="https://www.youtube.com/watch?v=RAC1bjWzIVk&ab_channel=FestGroup">Никогда такого не было и вот опять: Построение отдела тестирования - Андрей Мясников. QA Fest 2018</a>
</li>
<li><a href="https://www.youtube.com/watch?v=54JtRR4GbPQ&ab_channel=FestGroup">Процесс: как наладить, а не нагадить - Андрей Мясников. QA Fest 2015</a>
</li>
<li><a href="https://www.youtube.com/watch?v=4KT_ouolMQs&ab_channel=KatyaKravchenkoUSLife">Как проходит организация тестирования и составление тест планов (в зависимости от проекта)</a>
</li>
<li><a href="https://www.youtube.com/watch?v=UW8sTq8SuFQ&feature=emb_logo&ab_channel=LuxoftTrainingCenter">Концепция построения процесса тестирования в Agile-проектах: 3+1</a>
</li>
<li><a href="https://www.youtube.com/watch?v=POYyrqpbr94&feature=emb_logo&ab_channel=VladislavOrlikov">Построение процессов тестирования на новом проекте</a>
</li>
<li><a href="https://www.youtube.com/watch?v=qiCjqqtWP7I&t=790s">Мифы о тестировании #2 / О чем не говорят на курсах по тестированию / Правда о работе в IT</a>
</li>
<li> <a href="https://dou.ua/lenta/columns/value-driven-testing/">Что нужно знать о Value Driven Testing. Анализируем ценность и экономическую целесообразность тестирования</a>
</li>
</ul>


<h1>----- HR-часть -----</h1>
<h2>Вопросы с реальных собеседований с этапа HR </h2>
Часть из них зададут в любом случае. Список, разумеется, не полный:
<ul>
<li>Расскажи о себе (все что хочешь, что нам нужно знать о тебе)
</li>
<li>Есть ли релевантный опыт?
</li>
<li>Какие курсы проходил и вообще, что изучал?
</li>
<li>Что не устраивало на прошлом месте работы (если было), особенно если решил сменить сферу?
</li>
<li>Почему выбрал именно тестирование?
</li>
<li>Чем заинтересовала именно наша компания?
</li>
<li>Как часто бываешь на собеседованиях?
</li>
<li>Уровень английского? (вопрос могут задать на английском, многие теряются в этот момент)
</li>
<li>(Если требуется и уровень хороший) расскажите на английском: как доехали до собеседования/о себе (только не как в обществе анонимных алкоголиков) /почему считаешь, что можешь стать тестировщиком/ как прошел вчерашний день/о своих хобби/ и т.п.
</li>
<li>Как в целом смотришь на мир, как решаешь возникающие проблемы?
</li>
<li>3 твоих сильных и 3 слабых стороны?
</li>
<li>Как отдыхаешь? Как проводишь свободное время?
</li>
<li>Какие хобби?
</li>
<li>Что последнее прочитал техническое? Не техническое?
</li>
<li>Если бы мог вернуться в начало осознанной жизни, выбрал бы иной карьерный путь?
</li>
<li>3 примера, что тебе положительного дал предыдущий опыт работы (если есть)
</li>
<li>3 плюса и 3 минуса в сфере тестирования лично для тебя
</li>
<li>Как видишь развитие в этой сфере, кем видишь себя через год, три?
</li>
<li>Какая-то одна вещь или ситуация, которой ты гордишься
</li>
<li>Представим, что остальных кандидатов много и они опытнее (обычно так и есть), может у тебя есть какие-то преимущества перед ними? Почему ты думаешь, что лучше других кандидатов?
</li>
<li>Зарплатные ожидания сейчас, после испытательного срока, через год?
</li>
<li>Есть ли какие-то факторы, с которыми ты согласишься на меньшие деньги?
</li>
<li>С чем точно не готов мириться в отношении компании или руководителя?
</li>
<li>Ожидания от работы?
</li>
<li>Отношение к переработкам?
</li>
<li>Представь, что ты работаешь уже полгода. Опиши свой рабочий день.
</li>
<li>Что если при выполнении задачи понимаешь, что не укладываешься в сроки?
</li>
</ul>
<h1>----- Теоретическая часть -----</h1>

<h1>Общие понятия</h1>
<h2>Что означает тестирование ПО?</h2>
Тестирование (testing) программного обеспечения  - с технической точки зрения заключается в выполнении приложения (Application Under Testing (AUT) или Implementation Under Testing (IUT)) на некотором множестве исходных данных и сверке получаемых результатов с заранее известными (эталонными) с целью установить соответствие различных свойств и характеристик приложения заказанным свойствам. Как одна из основных фаз процесса разработки программного продукта (Дизайн приложения - Разработка кода - Тестирование ), тестирование характеризуется достаточно большим вкладом в суммарную трудоемкость разработки продукта. Широко известна оценка распределения трудоемкости между фазами создания программного продукта: 40%-20%-40%, из чего следует, что наибольший эффект в снижении трудоемкости может быть получен прежде всего на фазах Design и Testing. В более широком смысле, тестирование ПО - это техника контроля качества программного продукта, включающая в себя проектирование тестов, выполнение тестирования и анализ полученных результатов.
<h2>Почему требуется тестирование ПО?</h2>
<ul>
<li>Процесс тестирования гарантирует, что ПО будет работать в соответствии с ожиданиями клиентов и на имеющемся у них оборудовании.
</li>
<li>Это уменьшает циклы кодирования, выявляя проблемы на начальном этапе разработки. Обнаружение проблем на более ранних этапах SDLC обеспечивает правильное использование ресурсов и предотвращает повышение стоимости.
</li>
<li>Команда тестирования привносит взгляд клиента в процесс и находит варианты использования, о которых разработчик может не подумать.
</li>
<li>Любой сбой, дефект или ошибка, обнаруженные клиентом в готовом продукте, нарушают доверие к компании.
</li>
</ul>
<h2>Что означает обеспечение качества (Quality Assurance - QA) при тестировании ПО?</h2>
Это совокупность мероприятий, охватывающих все технологические этапы разработки, выпуска и эксплуатации ПО и информационных систем, предпринимаемых на разных стадиях жизненного цикла ПО, для обеспечения требуемого уровня качества выпускаемого продукта.
Доп. материал: <a href="https://habr.com/ru/company/badoo/blog/496452/">QA — специалист по пожарной безопасности вашего проекта</a>
<h2>Что означает контроль качества (Quality Control - QC) при тестировании ПО?</h2>
Это подмножество QA, совокупность действий, проводимых над продуктом в процессе разработки, для получения информации о его актуальном состоянии и соответствии ожидаемым результатам.
<h2>Что означает качество ПО? (Software Quality)</h2>
Качеству очень сложно дать неформальное определение, оно заключается в соответствии требованиям (conformance to requirements) и пригодности к использованию (fitness for use). Качество программного продукта характеризуется набором свойств, определяющих, насколько продукт "хорош" с точки зрения заинтересованных сторон, таких как заказчик продукта, спонсор, конечный пользователь, разработчики и тестировщики продукта, инженеры поддержки, сотрудники отделов маркетинга, обучения и продаж. Каждый из участников может иметь различное представление о продукте и о том, насколько он хорош или плох, то есть о том, насколько высоко качество продукта. То есть, основная последовательность действий при выборе и оценке критериев качества программного продукта включает:
<ul>
<li>Определение всех лиц, так или иначе заинтересованных в исполнении и результатах данного проекта.
</li>
<li>Определение критериев, формирующих представление о качестве для каждого из участников.
</li>
<li>Приоритезацию критериев, с учетом важности конкретного участника для компании, выполняющей проект, и важности каждого из критериев для данного участника.
</li>
<li>Определение набора критериев, которые будут отслежены и выполнены в рамках проекта, исходя из приоритетов и возможностей проектной команды. Постановка целей по каждому из критериев.
</li>
<li>Определение способов и механизмов достижения каждого критерия.
</li>
<li>Определение стратегии тестирования исходя из набора критериев, попадающих под ответственность группы тестирования, выбранных приоритетов и целей.
</li>
</ul>
Доп. материал:
<ul>
<li><a href="https://analytics.infozone.pro/software-quality/">https://analytics.infozone.pro/software-quality/</a>
</li>
<li><a href="https://www.intuit.ru/studies/courses/48/48/lecture/1440?page=1">https://www.intuit.ru/studies/courses/48/48/lecture/1440?page=1</a>
</li>
<li><a href="https://habr.com/ru/company/otus/blog/471080/">Кто несет ответственность за качество тестирования приложения? 10 причин попадания ошибки в продакшен</a>
</li>
<li><a href="https://habr.com/ru/company/otus/blog/537554/">На ком лежит ответственность за качество программного обеспечения?</a>
</li>
<li><a href="https://www.softwaretestinghelp.com/coq-cost-of-quality-tutorial/">What Is Cost Of Quality (COQ): Cost Of Good And Poor Quality</a>
</li>
</ul>
<h2>Объясните отличия в QA, QC и тестировании</h2>
<img src="https://lh6.googleusercontent.com/iuHyNeCGiFo1LRWXSdLStodw1wvg1cJwGEOYpUi8fThHJbIfXsAOMBRx-FaTFbGQJYO23io_U_X5uftxxggNDj5rkl17JVC0-nPk-8PtIBbUoRFx3cuFBgWq7lcoJYBbglENXJ2A">

<h2>Разница между верификацией и валидацией? (Verification и Validation)</h2>
<ul>
<li>Верификация — это процесс включающий в себя проверку Plans, Requirement Specifications, Design Specifications, Code, Test Cases, Check-Lists, etc.
</li>
<li>Верификация всегда проходит без запуска кода.
</li>
<li>Верификация использует методы — reviews, walkthroughs, inspections, etc.
</li>
<li>Верификация отвечает на вопрос "Делаем ли мы продукт правильно?"
</li>
<li>Верификация поможет определить, является ли программное обеспечение высокого качества, но оно не гарантирует, что система полезна. Проверка связана с тем, что система хорошо спроектирована и безошибочна.
</li>
<li>Верификация происходит до Validation.
</li>
</ul>
Она содержит все активности которые позволяют достигнуть высокого качества программного обеспечения:
<ol>
<li>Inspection in software engineering, refers to peer review of any work product by trained individuals who look for defects using a well defined process. (Fagan inspection)
</li>
<li>Walkthroughs In software engineering, a walkthrough or walk-through is a form of software peer review «in which a designer or programmer leads members of the development team and other interested parties go through a software product, and the participants ask questions and make comments about possible errors, violation of development standards, and other problems».
</li>
<li>Reviews In software development, peer review is a type of software review in which a work product (document, code, or other) is examined by its author and one or more colleagues, in order to evaluate its technical content and quality.
</li>
</ol>
Валидация (validation) – это процесс оценки конечного продукта, необходимо проверить, соответствует ли программное обеспечение ожиданиям и требованиям клиента. Это динамический механизм проверки и тестирования фактического продукта.
<ul>
<li>Валидация всегда включает в себя запуск кода программы.
</li>
<li>Валидация использует методы, такие как тестирование Black Box, тестирование White Box и нефункциональное тестирование.
</li>
<li>Валидация отвечает на вопрос "Делаем ли мы правильный продукт?"
</li>
<li>Валидация проверяет, соответствует ли программное обеспечение требованиям и ожиданиям клиента.
</li>
<li>Валидация может найти ошибки, которые процесс Verification не может поймать.
</li>
<li>Валидация происходит после Verification.
</li>
</ul>
На практике, отличия верификации и валидации имеют большое значение: заказчика интересует в большей степени валидация (удовлетворение собственных требований); исполнителя, в свою очередь, волнует не только соблюдение всех норм качества (верификация) при реализации продукта, а и соответствие всех особенностей продукта желаниям заказчика.

<table>
<tr>
<td>Верификация
</td><td>Валидация
</td></tr>
<tr>
<td>По факту отвечает на вопрос, правильно ли создается и тестируется ПО и все ли требования учитываются при этом.
</td><td>Отвечает на вопрос, создается ли продукт правильно с точки зрения ожиданий клиента.
</td></tr>
<tr>
<td>В процессе верификации убеждаемся в том, что весь созданный функционал приложения работает корректно и логически верно.
</td><td>При процессе валидации убеждаемся в том, что продукт полностью соответствует поведению, которое от него ожидается и то, что клиент знает о наличии подобного функционала.
</td></tr>
<tr>
<td>В структуру верификации входят такие компоненты, как сверка завалидированным требованиям, технической документации и корректное выполнения программного кода на любом этапе создания и тестирования ПО.
</td><td>Валидация, по своей сути, в большей степени включает в себя общую оценку ПО и может основываться исключительно на субъективном мнении касательно правильности работы приложения или его компонентов.
</td></tr>
</table>

Источник: <a href="https://qalight.ua/ru/baza-znaniy/verifikatsiya-i-validatsiya/">Верификация и валидация</a>
Доп. материал:
<ul>
<li><a href="https://software-testing.ru/forum/index.php?/topic/979-verification-validation-chto-eto-takoe/">Большое обсуждение: Verification & Validation - что это такое?</a>
</li>
<li><a href="https://testmatick.com/ru/validatsiya-i-verifikatsiya-ponyatiya-shodstva-i-otlichiya/">Чем отличается валидация от верификации</a>
</li>
</ul>
<h2>Принципы тестирования?</h2>
<ul>
<li>Тестирование демонстрирует наличие дефектов
</li>
<li>Исчерпывающее тестирование недостижимо
</li>
<li>Раннее тестирование
</li>
<li>Скопление/кластеризация дефектов
</li>
<li>Парадокс пестицида
</li>
<li>Тестирование зависит от контекста
</li>
<li>Заблуждение об отсутствии ошибок
</li>
<li>Garbage in, garbage out (GIGO)
</li>
</ul>

Принцип 1. Тестирование показывает наличие дефектов
Тестирование может показать, что дефекты присутствуют, но не может доказать, что дефектов нет.
Сколько бы успешных тестов вы не провели, вы не можете утверждать, что нет таких тестов, которые не нашли бы ошибку. Но если мы нашли хотя бы один дефект, мы уже можем утверждать, что в данном ПО присутствуют дефекты.

Принцип 2. Исчерпывающее тестирование невозможно
Вместо попыток «протестировать все» нам нужен некий подход к тестированию (стратегия), который обеспечит правильный объем тестирования для данного проекта, данных заказчиков (и других заинтересованных лиц) и данного продукта. При определении, какой объем тестирования достаточен, необходимо учитывать уровень риска, включая технические риски и риски, связанные с бизнесом, и такие ограничения проекта как время и бюджет. Оценка и управление рисками – одна из наиболее важных активностей в любом проекте. 

Принцип 3. Раннее тестирование
Тестовые активности должны начинаться как можно раньше в цикле разработки и быть сфокусированы на определенных целях.
Этот принцип связан с понятием «цена дефекта» (cost of defect). Цена дефекта существенно растет на протяжении жизненного цикла разработки ПО. Чем раньше обнаружен дефект, тем быстрее, проще и дешевле его исправить. Дефект, найденный в требованиях, обходится дешевле всего. 
Еще одно важное преимущество раннего тестирования – экономия времени. Тестовые активности могут начинаться еще до того, как написана первая строчка кода. По мере того, как готовятся требования и спецификации, тестировщики могут приступать к разработке и ревью тест-кейсов. И когда появится первая тестовая версия, можно будет сразу приступать к выполнению тестов.

Принцип 4. Скопление дефектов
Небольшое количество модулей содержит большинство дефектов, обнаруженных на этапе предрелизного тестирования, или же демонстрируют наибольшее количество отказов на этапе эксплуатации.
Многие тестировщики наблюдали такой эффект – дефекты «кучкуются». Это может происходить потому, что определенная область кода особенно сложна и запутана, или потому, что внесение изменений производит «эффект домино». Это знание часто используется для оценки рисков при планировании тестов – тестировщики фокусируются на известных «проблемных зонах». Также полезно проводить анализ первопричин (root cause analysis), чтобы предотвратить повторное появление дефектов, обнаружить причины возникновения скоплений дефектов и спрогнозировать потенциальные скопления дефектов в будущем.

Принцип 5. Парадокс пестицида
Если повторять те же тесты снова и снова, в какой-то момент этот набор тестов перестанет выявлять новые дефекты. Повторное применение тех же тестов и тех же методик приводит к тому, что в продукте остаются именно те дефекты, против которых эти тесты и эти методики неэффективны.
Чтобы преодолеть «парадокс пестицидов», необходимо регулярно пересматривать существующие тест-кейсы и создавать новые, разнообразные тесты, которые будут выполняться на различных частях системы.
 
Принцип 6. Тестирование зависит от контекста
Тестирование выполняется по-разному, в зависимости от контекста. Например, тестирование систем, критических с точки зрения безопасности, проводится иначе, чем тестирование сайта интернет-магазина.
Этот принцип тесно связан с понятием риска. Что такое риск? Риск – это потенциальная проблема. У риска есть вероятность (likelihood) – она всегда выше 0 и ниже 100% – и есть влияние (impact) – те негативные последствия, которых мы опасаемся. Анализируя риски, мы всегда взвешиваем эти два аспекта: вероятность и влияние.
То же можно сказать и о мире ПО: разные системы связаны с различными уровнями риска, влияние того или иного дефекта также сильно варьируется. Одни проблемы довольно тривиальны, другие могут дорого обойтись и привести к большим потерям денег, времени, деловой репутации, а в некоторых случаях даже привести к травмам и смерти.
Уровень риска влияет на выбор методологий, техник и типов тестирования. <img src="https://lh6.googleusercontent.com/4UYXQ5DHdtgibdzNodKMrNo3CemS1449MPJVgUx9b9KgEJ7y3YDc-VFzZcE1zXn9azLrVtY8IfXLdP6UYh_tYuzpn3pGT6N5SbkVd_x0MPSuRqKUs9ugI-NxJiyCa5_TF_AT7t_-">

Принцип 7. Заблуждение об отсутствии ошибок
Нахождение и исправление дефектов бесполезно, если построенная система неудобна для использования и не соответствует нуждам и ожиданиям пользователей.
Заказчики ПО – люди и организации, которые покупают и используют его, чтобы выполнять свои повседневные задачи – на самом деле совершенно не интересуются дефектами и их количеством, кроме тех случаев, когда они непосредственно сталкиваются с нестабильностью продукта. Им также неинтересно, насколько ПО соответствует формальным требованиям, которые были задокументированы. Пользователи ПО более заинтересованы в том, чтобы оно помогало им эффективно выполнять задачи. ПО должно отвечать их потребностям, и именно с этой точки зрения они его оценивают.
Даже если вы выполнили все тесты и ошибок не обнаружили, это еще не гарантия того, что ПО будет соответствовать нуждам и ожиданиям пользователей.
Иначе говоря, верификация != валидация.

* Принцип 8. GIGO.
В компьютерной науке «garbage in – garbage out» (GIGO) — это концепция, в которой ошибочные или бессмысленные входные данные создают бессмысленный вывод или «мусор», т.е. при неверных входящих данных будут получены неверные результаты, даже если сам по себе алгоритм правилен. В тестировании такие случаи иногда создают намеренно, но я добавил этот принцип в общий список для того, чтобы подчеркнуть важность подготовки качественных тестовых данных, положительные они или отрицательные.

Доп. материал: <a href="https://theqalead.com/topics/zero-defect-software/">The Cold Hard Truth About Zero-Defect Software</a>
<h2>Критерии выбора тестов?</h2>
Требования к идеальному критерию тестирования:
<ul>
<li>Критерий должен быть достаточным, т.е. показывать, когда некоторое конечное множество тестов достаточно для тестирования данной программы.
</li>
<li>Критерий должен быть полным, т.е. в случае ошибки должен существовать тест из множества тестов, удовлетворяющих критерию, который раскрывает ошибку.
</li>
<li>Критерий должен быть надежным, т.е. любые два множества тестов, удовлетворяющих ему, одновременно должны раскрывать или не раскрывать ошибки программы.
</li>
<li>Критерий должен быть легко проверяемым, например вычисляемым на тестах.
</li>
</ul>
Для нетривиальных классов программ в общем случае не существует полного и надежного критерия, зависящего от программ или спецификаций. Поэтому мы стремимся к идеальному общему критерию через реальные частные. Классы критериев:
<ul>
<li>Структурные критерии используют информацию о структуре программы (критерии так называемого "белого ящика").
</li>
<li>Функциональные критерии формулируются в описании требований к программному изделию ( критерии так называемого "черного ящика" ).
</li>
<li>Критерии стохастического тестирования формулируются в терминах проверки наличия заданных свойств у тестируемого приложения, средствами проверки некоторой статистической гипотезы.
</li>
<li>Мутационные критерии ориентированы на проверку свойств программного изделия на основе подхода Монте-Карло.
</li>
</ul>
Структурные критерии используют модель программы в виде "белого ящика", что предполагает знание исходного текста программы или спецификации программы в виде потокового графа управления. Структурная информация понятна и доступна разработчикам подсистем и модулей приложения, поэтому данный класс критериев часто используется на этапах модульного и интеграционного тестирования (Unit testing, Integration testing). Структурные критерии базируются на основных элементах УГП (Управляющий граф программы), операторах, ветвях и путях.
<ul>
<li>Условие критерия тестирования команд (критерий С0) - набор тестов в совокупности должен обеспечить прохождение каждой команды не менее одного раза. Это слабый критерий, он, как правило, используется в больших программных системах, где другие критерии применить невозможно.
</li>
<li>Условие критерия тестирования ветвей (критерий С1) - набор тестов в совокупности должен обеспечить прохождение каждой ветви не менее одного раза. Это достаточно сильный и при этом экономичный критерий, поскольку множество ветвей в тестируемом приложении конечно и не так уж велико. Данный критерий часто используется в системах автоматизации тестирования.
</li>
<li>Условие критерия тестирования путей (критерий С2) - набор тестов в совокупности должен обеспечить прохождение каждого пути не менее 1 раза. Если программа содержит цикл (в особенности с неявно заданным числом итераций), то число итераций ограничивается константой (часто - 2, или числом классов выходных путей).
</li>
</ul>
Структурные критерии не проверяют соответствие спецификации, если оно не отражено в структуре программы. Поэтому при успешном тестировании программы по критерию C2 мы можем не заметить ошибку, связанную с невыполнением некоторых условий спецификации требований.
Функциональный критерий - важнейший для программной индустрии критерий тестирования. Он обеспечивает, прежде всего, контроль степени выполнения требований заказчика в программном продукте. Поскольку требования формулируются к продукту в целом, они отражают взаимодействие тестируемого приложения с окружением. При функциональном тестировании преимущественно используется модель "черного ящика". Проблема функционального тестирования - это, прежде всего, трудоемкость; дело в том, что документы, фиксирующие требования к программному изделию (Software requirement specification, Functional specification и т.п.), как правило, достаточно объемны, тем не менее, соответствующая проверка должна быть всеобъемлющей. Ниже приведены частные виды функциональных критериев:
<ul>
<li>Тестирование пунктов спецификации - набор тестов в совокупности должен обеспечить проверку каждого тестируемого пункта не менее одного раза. Спецификация требований может содержать сотни и тысячи пунктов требований к программному продукту и каждое из этих требований при тестировании должно быть проверено в соответствии с критерием не менее чем одним тестом.
</li>
<li>Тестирование классов входных данных - набор тестов в совокупности должен обеспечить проверку представителя каждого класса входных данных не менее одного раза. При создании тестов классы входных данных сопоставляются с режимами использования тестируемого компонента или подсистемы приложения, что заметно сокращает варианты перебора, учитываемые при разработке тестовых наборов. Следует заметить, что перебирая в соответствии с критерием величины входных переменных (например, различные файлы - источники входных данных), мы вынуждены применять мощные тестовые наборы. Действительно, наряду с ограничениями на величины входных данных, существуют ограничения на величины входных данных во всевозможных комбинациях, в том числе проверка реакций системы на появление ошибок в значениях или структурах входных данных. Учет этого многообразия - процесс трудоемкий, что создает сложности для применения критерия.
</li>
<li>Тестирование правил - набор тестов в совокупности должен обеспечить проверку каждого правила, если входные и выходные значения описываются набором правил некоторой грамматики. Следует заметить, что грамматика должна быть достаточно простой, чтобы трудоемкость разработки соответствующего набора тестов была реальной (вписывалась в сроки и штат специалистов, выделенных для реализации фазы тестирования).
</li>
<li>Тестирование классов выходных данных - набор тестов в совокупности должен обеспечить проверку представителя каждого выходного класса, при условии, что выходные результаты заранее расклассифицированы, причем отдельные классы результатов учитывают, в том числе, ограничения на ресурсы или на время (time out). При создании тестов классы выходных данных сопоставляются с режимами использования тестируемого компонента или подсистемы, что заметно сокращает варианты перебора, учитываемые при разработке тестовых наборов.
</li>
<li>Тестирование функций - набор тестов в совокупности должен обеспечить проверку каждого действия, реализуемого тестируемым модулем, не менее одного раза. Очень популярный на практике критерий, который, однако, не обеспечивает покрытия части функциональности тестируемого компонента, связанной со структурными и поведенческими свойствами, описание которых не сосредоточено в отдельных функциях (т.е. описание рассредоточено по компоненту). Критерий тестирования функций объединяет отчасти особенности структурных и функциональных критериев. Он базируется на модели "полупрозрачного ящика", где явно указаны не только входы и выходы тестируемого компонента, но также состав и структура используемых методов (функций, процедур) и классов.
</li>
<li>Комбинированные критерии для программ и спецификаций - набор тестов в совокупности должен обеспечить проверку всех комбинаций непротиворечивых условий программ и спецификаций не менее одного раза. При этом все комбинации непротиворечивых условий надо подтвердить, а условия противоречий следует обнаружить и ликвидировать.
</li>
</ul>

Стохастическое тестирование применяется при тестировании сложных программных комплексов - когда набор детерминированных тестов (X,Y) имеет громадную мощность.
Мутационный критерий (класс IV). Постулируется, что профессиональные программисты пишут сразу почти правильные программы, отличающиеся от правильных мелкими ошибками или описками типа - перестановка местами максимальных значений индексов в описании массивов, ошибки в знаках арифметических операций, занижение или завышение границы цикла на 1 и т.п. Предлагается подход, позволяющий на основе мелких ошибок оценить общее число ошибок, оставшихся в программе. Подход базируется на следующих понятиях: Мутации - мелкие ошибки в программе. Мутанты - программы, отличающиеся друг от друга мутациями . Метод мутационного тестирования - в разрабатываемую программу P вносят мутации, т.е. искусственно создают программы-мутанты P1, P2... Затем программа P и ее мутанты тестируются на одном и том же наборе тестов (X,Y). Если на наборе (X,Y) подтверждается правильность программы P и, кроме того, выявляются все внесенные в программы-мутанты ошибки, то набор тестов (X,Y) соответствует мутационному критерию, а тестируемая программа объявляется правильной. Если некоторые мутанты не выявили всех мутаций, то надо расширять набор тестов (X,Y) и продолжать тестирование.

Подробнее и с примерами в источнике: <a href="https://www.intuit.ru/studies/courses/48/48/lecture/1428?page=1">https://www.intuit.ru/studies/courses/48/48/lecture/1428?page=1</a>
Доп. материал: <a href="https://www.youtube.com/watch?v=qkUCzvP-5mg&t=20547s">https://www.youtube.com/watch?v=qkUCzvP-5mg&t=20547s</a>
<h2>Что такое импакт анализ (анализ влияния, Impact Analysis)?</h2>
Impact Analysis (импакт анализ) - это исследование, которое позволяет указать затронутые места (affected areas) в проекте при разработке новой или изменении старой функциональности, а также определить, насколько значительно они были затронуты.
Затронутые области требуют большего внимания во время проведения регрессионного тестирования.
Импакт анализ может быть полезным в следующих случаях:
<ul>
<li>есть изменения в требованиях;
</li>
<li>получен запрос на внесение изменений в продукт;
</li>
<li>ожидается внедрение нового модуля или функциональности в существующий продукт;
</li>
<li>каждый раз, когда есть изменения в существующих модулях или функциональностях продукта.
</li>
</ul>
Как мы знаем, в настоящее время продукты становятся все более большими и комплексными, а компоненты все чаще зависят друг от друга. Изменение строчки кода в таком проекте может "сломать" абсолютно все.
Информация о взаимосвязи и взаимном влиянии изменений могут помочь QA:
<ul>
<li>сфокусироваться на тестировании функциональности, где изменения были представлены;
</li>
<li>принять во внимание части проекта, которые были затронуты изменениями и, возможно, пострадали;
</li>
<li>не тратить время на тестирование тех частей проекта, которые не были затронуты изменениями.
</li>
</ul>

Источник:<a href="https://habr.com/ru/post/539208/"> Impact Analysis: 6 шагов, которые облегчат тестирование изменений</a>
<h2>Что подразумевается под тестовым покрытием? (Test Coverage)</h2>
Тестовое Покрытие - это одна из метрик оценки качества тестирования, представляющая из себя плотность покрытия тестами требований либо исполняемого кода. Сложность современного ПО и инфраструктуры сделало невыполнимой задачу проведения тестирования со 100% тестовым покрытием. Поэтому для разработки набора тестов, обеспечивающего более-менее высокий уровень покрытия можно использовать специальные инструменты либо техники тест дизайна.
Существуют следующие подходы к оценке и измерению тестового покрытия:
<ul>
<li><a href="http://www.protesting.ru/testing/testcoverage.html#requirements">Покрытие требований (Requirements Coverage)</a> - оценка покрытия тестами функциональных и нефункциональных требований к продукту путем построения матриц трассировки (traceability matrix).
</li>
<li><a href="http://www.protesting.ru/testing/testcoverage.html#code">Покрытие кода (Code Coverage)</a> - оценка покрытия исполняемого кода тестами, путем отслеживания непроверенных в процессе тестирования частей ПО.
</li>
<li><a href="http://www.protesting.ru/testing/testcoverage.html#flow">Тестовое покрытие на базе анализа потока управления</a> - это одна из техник тестирования белого ящика, основанная на определении путей выполнения кода программного модуля и создания выполняемых тест кейсов для покрытия этих путей. 
</li>
</ul>
Различия:
Метод покрытия требований сосредоточен на проверке соответствия набора проводимых тестов требованиям к продукту, в то время как анализ покрытия кода - на полноте проверки тестами разработанной части продукта (исходного кода), а анализ потока управления - на прохождении путей в графе или модели выполнения тестируемых функций (Control Flow Graph).
Ограничения:
<ul>
<li>Метод оценки покрытия кода не выявит нереализованные требования, так как работает не с конечным продуктом, а с существующим исходным кодом.
</li>
</ul>
<ul>
<li>Метод покрытия требований может оставить непроверенными некоторые участки кода, потому что не учитывает конечную реализацию.
</li>
</ul>

Альтернативное мнение:
Покрытие кода — совершенно бесполезная метрика. Не существует «правильного» показателя. Это вопрос-ловушка. У вас может быть проект со 100% покрытием кода, в котором по-прежнему остаются баги и проблемы. В реальности нужно следить за другими метриками — хорошо известными показателям CTM (Codepipes testing Metrics).
<img src="https://lh5.googleusercontent.com/ycWdGw8XfGW_7xun6DdJ2HLdCP5FaAIht4em7L99M4Pu58zUki4bgk6V0o4VjnGCxPcxyZFsXKep5rwyJP-KVQa9daBeK0XdCUgOkSUvBsPJyLOTxnYOHunUBfvIOrgMuUeH7f61">

PDWT (процент разработчиков, пишущих тесты) — вероятно, самый важный показатель. Нет смысла говорить об антипаттернах тестирования ПО, если у вас вообще нет тестов. Все разработчики в команде должны писать тесты. Любую новую функцию можно объявлять сделанной только если она сопровождается одним или несколькими тестами.

PBCNT (процент багов, приводящих к созданию новых тестов). Каждый баг в продакшне — отличный повод для написания нового теста, проверяющего соответствующее исправление. Любой баг должен появиться в продакшне не более одного раза. Если ваш проект страдает от появления повторных багов даже после их первоначального «исправления», то команда действительно выиграет от использования этой метрики.

PTVB (процент тестов, которые проверяют поведение, а не реализацию). Тесно связанные тесты пожирают массу времени при рефакторинге основного кода.

PTD (процент детерминированных тестов от общего числа). Тесты должны завершаться ошибкой только в том случае, если что-то не так с бизнес-кодом. Если тесты периодически ломаются без видимой причины — это огромная проблема.

Если после прочтения о метриках вы по-прежнему настаиваете на установке жесткого показателя для покрытия кода, я дам вам число 20%. Это число должно использоваться как эмпирическое правило, основанное на законе Парето. 20% вашего кода вызывает 80% ваших ошибок

Доп. материал:
<a href="https://intuit.ru/studies/courses/48/48/lecture/1430">Лекция 4: Оценка оттестированности проекта: метрики и методика интегральной оценки</a>
<h2>Что такое модель зрелости тестирования (TMM - Test Maturity Model)?</h2>
Существует определение Maturity Models, то есть модели зрелости различных процессов в организации, состоящая из 5 уровней. Нас же в рамках этого материала интересует один конкретный подвид моделей MM - модель зрелости тестирования, которая тоже состоит из 5 уровней. TMM в свою очередь основан на модели зрелости возможностей (CMM — Capability Maturity Model). Модель зрелости ПО (CMM или SW-CMM) — это модель для оценки зрелости программных процессов в организации. В ней также перечислены некоторые стандартные практики, которые увеличивают зрелость этих процессов. TMM это подробная модель для улучшения процесса тестирования. Она может быть дополнена любой моделью улучшения процесса или может использоваться как одиночная модель.
Модель ТММ имеет два основных компонента:
<ul>
<li>Набор из 5 уровней, которые определяют возможности тестирования (testing capability)
</li>
<li>Модель оценки (An Assessment Model)
</li>
</ul>
Пять уровней TMM помогают организации определить зрелость своего процесса и определить следующие шаги по улучшению, которые необходимы для достижения более высокого уровня зрелости тестирования. Приведенный далее текст является переводом, но есть и русскоязычные на эту тему. Однако материал везде несколько отличается, поэтому представляю несколько точек зрения: 
<a href="https://devsday.ru/blog/details/5427">https://devsday.ru/blog/details/5427</a> <a href="https://www.software-testing.ru/library/around-testing/processes/3092-test-maturity-model">https://www.software-testing.ru/library/around-testing/processes/3092-test-maturity-model</a> <a href="https://habr.com/ru/company/otus/blog/479368/">https://habr.com/ru/company/otus/blog/479368/</a>
<ul>
<li>Уровень 1. Начальный. ПО должно успешно работать.
</li>
<ul>
<li>На этом уровне области процессов не определены.
</li>
<li>Цель тестирования — убедиться, что ПО работает нормально.
</li>
<li>На этом уровне не хватает ресурсов, инструментов и обученного персонала.
</li>
<li>Нет проверки качества перед поставкой ПО.
</li>
</ul>
<li>Уровень 2. Определенный. Разработка целей и политик тестирования и отладки.
</li>
<ul>
<li>Этот уровень отличает тестирование от отладки, и они считаются различными действиями.
</li>
<li>Этап тестирования наступает после кодирования.
</li>
<li>Основная цель тестирования — показать, что ПО соответствует спецификации.
</li>
<li>Основные методы и методики тестирования.
</li>
</ul>
<li>Уровень 3: Комплексный. Интеграция тестирования в жизненный цикл ПО.
</li>
<ul>
<li>Тестирование интегрируется в весь жизненный цикл.
</li>
<li>На основании требований определяются цели испытаний.
</li>
<li>Структура тестирования существует.
</li>
<li>Тестирование на уровне профессиональной деятельности.
</li>
</ul>
<li>Уровень 4: Управление и измерение. Создание программы тестовых измерений.
</li>
<ul>
<li>Тестирование — это измеренный и количественный процесс.
</li>
<li>Проверка на всех этапах разработки признается как тестирование.
</li>
<li>Для повторного использования и регрессионного тестирования есть Test case и они записаны в базу тестов.
</li>
<li>Дефекты регистрируются и получают уровни серьезности.
</li>
</ul>
<li>Уровень 5: Оптимизированный. Оптимизация процесса тестирования.
</li>
<ul>
<li>Тестирование управляется и определено.
</li>
<li>Эффективность и стоимость тестирования можно отслеживать.
</li>
<li>Тестирование может постоянно настраиваться и улучшаться.
</li>
<li>Практика контроля качества и предотвращения дефектов.
</li>
<li>Практикуется процесс повторного использования (Reuse).
</li>
<li>Метрики, связанные с тестированием, также имеют средства поддержки.
</li>
<li>Инструменты обеспечивают поддержку разработки тестовых наборов и сбора дефектов.
</li>
</ul>
</ul>

Доп. материал:<a href="https://medium.com/@grifer163/7-%D0%BF%D0%BE%D0%B4%D1%85%D0%BE%D0%B4%D0%BE%D0%B2-%D0%BA-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8E-a78fc69da167"> 7 подходов к тестированию</a>
<h2>Что такое тестирование со сдвигом влево? (Shift left testing) </h2>
В попытке перенести тестирование на более ранний этап жизненного цикла разработки при одновременном улучшении показателей качества, задачи смещаются влево в схеме жизненного цикла разработки ПО. По возможности, тестирование должно проводиться с самого начала фазы проектирования, чтобы построить соответствующую стратегию тестирования. Проще говоря, это подход к тестированию программного обеспечения и тестированию системы, при котором тестирование выполняется на более раннем этапе жизненного цикла. Ключевые преимущества:
<ul>
<li>Сокращение затрат 
</li>
<li>Более высокое качество
</li>
<li>Повышение эффективности 
</li>
<li>Конкурентные преимущества
</li>
</ul>

Доп. материал:
<a href="https://habr.com/ru/post/543318/">Экономим ресурсы и успеваем в срок: зачем подключать QA-инженера в начале работы над фичей</a>
<h2>Что такое независимое тестирование? (Independent testing)</h2>
Можете ли вы доверять вердикту судьи, который является частью внутреннего круга людей, которых он должен судить? Чтобы этот процесс был справедливым, лица, принимающие решения, должны быть беспристрастными. Теперь, когда вы активно участвуете в разработке какого-либо продукта или программного обеспечения, тестировать его с нейтральным мышлением это легче сказать, чем сделать. Как разработчик, вы бы хотели отгружать продукт в кратчайшие сроки и считать его безупречным и в конечном итоге упустите из виду некоторые ошибки. Чтобы избежать такой ситуации, иногда следует нанять независимую организацию по тестированию, которая тщательно проверит ваш продукт на наличие сбоев, готовя его к развертыванию. 
Тестирование по уровням независимости:
<ul>
<li>Программист тестирует свой код 
</li>
<li>Тестирование проводится другим программистом в организации
</li>
<li>Внутренняя команда тестирования 
</li>
<li>Независимая организация тестирования
</li>
</ul>

<ul>
<li>Когда программист проверяет свой код: Вы бы никогда не попросили шеф-повара быть его собственным критиком. И даже если вы это сделаете, вам будет трудно поверить всему, что он говорит. Смысл - создатель никогда не может быть хорошим критиком своей собственной работы. Программист знает свой код от и до. Их цель - создать продукт и отправить его в кратчайшие сроки. Вместо того, чтобы искать ошибки со всех возможных точек зрения, они будут искушены найти способы обойти найденные ошибки. Писатель Гленфорд Майерс в своей книге «Искусство тестирования программного обеспечения» перечислил разницу в мышлении разработчика и тестировщика. Он сказал, что разработчик думает как строитель, сосредоточенный на строительстве, в то время как тестировщик ищет недостатки, которые приведут к разрушению здания, если не будут решены. 
</li>
<li>Тестирование проводится другим программистом в организации: Компромисс - это найти кого-то в организации. Это может быть какой-то другой программист, который участвует в некоторых других проектах. Это дает определенный уровень независимости. Но проблема возникает из-за того же reporting manager. Менеджер может попросить программиста пропустить некоторые тесты, когда есть ограничения по времени. Это приведет к неполному тестированию продукта. Кроме того, если попросить других разработчиков провести тестирование, это приведет к развертыванию различных ресурсов в одном проекте. Это будет вредно для всей работы организации. 
</li>
<li>Внутренняя команда тестирования: Наличие другой внутренней команды - это хорошее решение. Но поскольку они будут в организации, на них будут влиять ограничительные сроки. Кроме того, это будет дорого поддерживать внутреннюю команду. Это приведет к большим бюджетным и ресурсным ограничениям для команды. Команда может иметь доступ к ограниченным инструментам и программному обеспечению, таким образом, не отвечая требованиям всех проектов. Среда тестирования также будет варьироваться в зависимости от количества пользователей и числа выполненных интеграций. Затем тестирование будет проводиться в спешном порядке, что приведет к упущению некоторых ошибок, которые могут появиться после выпуска продукта. Решение, которое позаботится обо всех этих недостатках, - «Независимое тестирование». 
</li>
<li>Почему независимое тестирование? Независимые тестирующие организации изучат все аспекты вашей продукции. Они работают с мышлением поиска недостатков и ошибок. Они не будут использовать ярлыки в процессе тестирования. И поскольку они не были частью процесса разработки, они будут проводить тесты на нейтральной основе, чтобы прежние интересы не мешали процессу тестирования. Мысль о поиске максимальных «точек останова» пойдет на пользу вашему продукту. Почти все сторонние тестирующие организации предоставят вам подробные отчеты об ошибках и предложат корректирующие меры. 
</li>
</ul>
<h2>В чем разница между превентивным и реактивным подходами в тестировании? (Preventative and Reactive approaches)</h2>
<ul>
<li>Превентивный (профилактический) подход: он также известен как Verification Process. Этот подход заключается в предотвращении дефектов. При таком подходе тесты разрабатываются на ранних этапах SDLC, то есть до того, как программное обеспечение было создано. Он подпадает под анализ качества (QA). 
</li>
<li>Реактивный подход: он также известен как Validation Process. Этот подход заключается в выявлении дефектов. При таком подходе тесты предназначены для выполнения после того, как программное обеспечение было произведено. Здесь мы пытаемся найти недостатки. Подпадает под контроль качества (QC).
</li>
</ul>
<h2>Перечислите типичные возможные обязанности инженера по обеспечению качества? </h2>
<ul>
<li>Команда QA отвечает за мониторинг всего процесса разработки. 
</li>
<li>Они несут ответственность за отслеживание результатов каждого этапа SDLC и корректировку их в соответствии с ожиданиями. 
</li>
<li>Они несут ответственность за чтение и понимание необходимых документов. 
</li>
<li>Анализируют требования к тестированию, а также разрабатывают и выполняют тесты. 
</li>
<li>Разрабатывают Test case и расставляют приоритеты в тестировании. 
</li>
<li>Записывают проблемы и инциденты в соответствии с задачами проекта и планами управления инцидентами. 
</li>
<li>Работают с командой приложения и/или клиентом для решения любых проблем, возникающих в процессе тестирования. 
</li>
<li>Проводят регрессионное тестирование каждый раз, когда в код вносятся изменения для исправления дефектов. 
</li>
<li>Должны взаимодействовать с клиентами, чтобы лучше понять требования продукта. 
</li>
<li>Принимают участие в прохождении процедур тестирования.
</li>
</ul>
<h2>Что такое аудит качества? </h2>
Аудит качества - это процесс систематической и независимой проверки программного продукта или процесса для оценки соответствия спецификациям, стандартам, соглашениям и другим соответствующим критериям.
<h2>Почему тестирование делится на отдельные этапы? </h2>
<ul>
<li>Каждый этап испытаний имеет свое назначение 
</li>
<li>Проще управлять поэтапно 
</li>
<li>Мы можем запустить разные тесты в разных средах 
</li>
<li>Производительность и качество тестирования улучшаются с помощью поэтапного тестирования
</li>
</ul>
<h2>Почему невозможно полностью протестировать ПО? </h2>
<ul>
<li>Спецификации ПО могут быть субъективными и приводить к различным интерпретациям. 
</li>
<li>ПО может потребоваться слишком много входов, слишком много выходов и слишком много комбинаций путей для тестирования.
</li>
</ul>
<h2>Как вы тестируете продукт, если требования еще не зафиксированы? </h2>
Если спецификация требований недоступна для продукта, тогда план тестирования может быть создан на основе предположений, сделанных относительно продукта. Но мы должны хорошо документировать все предположения в плане тестирования. 
<h2>Как вы узнаете, было ли создано достаточно тестов для тестирования продукта? </h2>
Прежде всего, мы проверим, охватывает ли каждое требование хотя бы один Test case. Если да, то можно сказать, что тестовых примеров достаточно для тестирования продукта. 
<h2>Как вы понимаете инспекцию? </h2>
Это процесс проверки на уровне группы и улучшения качества документации по продукту. Он фокусируется на следующих двух аспектах: 
<ul>
<li>Улучшение документа продукта 
</li>
<li>Улучшение процесса (как производства документов, так и проверки)
</li>
</ul>
<h2>Какие есть роли/должности в команде?</h2>
<img src="https://lh5.googleusercontent.com/A8vFU_BDXkSdJG3KlSWFvoGcMbwLr1vifKjhwDYYPYyYTOjN8-Cu_EoulIhTHNMzW_0PikTDGgO2FZmNtCJie1rNpjX6z8QHNLcCxJcspISrep5hc0gA1lgBRRF-6VZ_1leCXD3S">
Project manager
Это человек, который берет входящие от заказчика требования (несформулированные хотелки), уточняет все и нормальным языком передает разработчикам, следит за рисками, прогрессом и доводит до финала. На нем вся коммуникация с заказчиком, согласования и т. д. 
Product Owner
Может выполнять немного разные роли в разных компаниях. Человек, который является хранителем информации о продукте. Его роль быть decision maker, он отвечает со стороны бизнеса за приложение, с него будет спрашивать заказчик. Противоположные роли с ПМ, как адвокат с обвинителем. ПМ со стороны команды, пытается извертеться на плюшки, а PO со стороны заказчика выбивает все по максимуму для себя. 
Knowledge manager
Управление знаниями - это о том, как распоряжаться всеми имеющимися в компании знаниями, чтобы позволять всем сотрудникам максимально быстро находить ответы на вопросы, принимать решения, избегать ошибок, придумывать что-то новое, управлять проектами, подбирать и развивать сотрудников. А значит, нужно выстраивать коммуникации между подразделениями, учить их разговаривать друг с другом. Вопросы менеджера по знаниям ведущим специалистам имеют высший приоритет, поэтому тот всегда держит руку на пульсе. Полученные знания после доставки не теряются, а превращаются в обучающие документы, которые изучают все сотрудники.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/538128/">Product Owner vs Product Manager или Product Owner/Product Manager</a>
</li>
<li><a href="https://habr.com/ru/company/habr_career/blog/535032/">Продакт-менеджмент как профессия: востребованность, зарплата и другие нюансы</a>
</li>
<li><a href="https://habr.com/ru/post/535418/">Кто такой продакт-менеджер? Или не все PM’ы — проджект-менеджеры</a>
</li>
<li><a href="https://habr.com/ru/company/plarium/blog/541814/">Knowledge management: как перестать изобретать велосипеды</a>
</li>
<li><a href="https://habr.com/ru/company/exness/blog/505470/">Заметки knowledge manager'a. Как работает управление знаниями в Exness</a>
</li>
<li><a href="https://habr.com/ru/company/ivi/blog/535448/">Профессия СТО</a>
</li>
<li><a href="https://habr.com/ru/company/netologyru/blog/501690/">Кто такой DevOps-инженер, что он делает, сколько зарабатывает и как им стать</a>
</li>
<li><a href="https://habr.com/ru/company/skillfactory/blog/509344/">Гайд по DevOps для начинающих</a>
</li>
</ul>
<h2>Опишите жизненный цикл продукта по этапам - какие участники на каждом этапе, какие у них роли? Какие артефакты на каждом этапе?</h2>
Хотелось бы уточнить, что описанные этапы не являются эталонными и от компании к компании процессы могут радикально отличаться. В данном случае представлены некие «сферические процессы в вакууме» для какого-то начального понимания. Параллельно описывается SDLC и STLC.
<ul>
<li>Анализ. Участники: Product owner, BA(бизнес-аналитик), QA. Артефакты: спецификация требований к ПО (Software Requirement Specification, SRS).
</li>
</ul>
Во время этого этапа BA выясняет у PO все пожелания к продукту и документирует это в процессе обсуждения требований. Необходимо убедиться в том, что все участники правильно поняли поставленные задачи и то, как именно каждое требование будет реализовано на практике. Таким образом, этот этап предполагает сбор требований к разрабатываемому ПО, их систематизацию, документирование, анализ, а также выявление и разрешение противоречий. В компаниях, где налажены процессы обеспечения качества, уже на этом этапе включается в работу QA, т.к. бывают и дефекты требований.
<ul>
<li>Проектирование. Участники: Product owner, разработчики, системные архитекторы, QA. Артефакты: дизайн-спецификация (Design Specification Document, DSD), Тест-план, тест-сценарии, тест-кейсы; вариативно: тестовая стратегия.
</li>
</ul>
На стадии проектирования (называемой также стадией дизайна и архитектуры) программисты и системные архитекторы, руководствуясь требованиями, разрабатывают высокоуровневый дизайн системы. Разнообразные технические вопросы, возникающие в процессе проектирования, обсуждаются со всеми заинтересованными сторонами. Определяются технологии, которые будут использоваться в проекте, загрузка команды, ограничения, временные рамки и бюджет. В соответствии с уточненными требованиями выбираются наиболее подходящие проектные решения. Утвержденный дизайн системы определяет перечень разрабатываемых программных компонентов, взаимодействие с третьими сторонами, функциональные характеристики программы, используемые базы данных и многое другое. QA/test analyst проектируют процесс тестирования в тест плане, руководствуясь также (если есть) политикой и стратегией тестирования. Тестировщики начинают писать сценарии и по ним кейсы для тестирования.
<ul>
<li>Разработка. Участники: разработчики. Артефакты: -.
</li>
</ul>
Системные администраторы настраивают программное окружение, frontend программисты разрабатывают пользовательский интерфейс программы и логику ее взаимодействия с сервером.
Кроме того, программисты пишут Unit-тесты для проверки правильности работы кода каждого компонента системы, проводят ревью написанного кода, создают билды и разворачивают готовое ПО в программной среде. Этот цикл повторяется до тех пор, пока все требования не будут реализованы.
<ul>
<li>Тестирование. Участники: QA. Артефакты: дефект-репорты, сводный отчет о тестировании. 
</li>
</ul>
Тестовый администратор (если есть) настраивает тестовые среды/стенды для проведения тестирования. Тестировщики занимаются поиском дефектов в программном обеспечении и сравнивают описанное в требованиях поведение системы с реальным. В фазе тестирования обнаруживаются пропущенные при разработке баги. При обнаружении дефекта, тестировщик составляет отчет об ошибке, который передается разработчикам. Последние его исправляют, после чего тестирование повторяется – но на этот раз для того, чтобы убедиться, что проблема была исправлена, и само исправление не стало причиной появления новых дефектов в продукте. По итогам проведенного процесса тестирования составляется итоговый отчет.
<ul>
<li>Внедрение и сопровождение. Участники: команда технической поддержки. Артефакты: замечания, запросы на исправление/улучшение.
</li>
</ul>
Когда программа протестирована и в ней больше не осталось серьезных дефектов, приходит время релиза и передачи ее конечным пользователям. После выпуска новой версии программы в работу включается отдел технической поддержки. Его сотрудники обеспечивают обратную связь с пользователями, их консультирование и поддержку. В случае обнаружения пользователями тех или иных пост-релизных багов, информация о них передается в виде отчетов об ошибках команде разработки, которая, в зависимости от серьезности проблемы, либо немедленно выпускает исправление (т.н. hot-fix), либо откладывает его до следующей версии программы. Кроме того, команда технической поддержки помогает собирать и систематизировать различные метрики – показатели работы программы в реальных условиях и т.п.
<h2>Кто такой SDET? </h2>
SDET (Software Development Engineer in Test) инженер по разработке ПО в тестировании - это ИТ-специалист, который может одинаково эффективно работать в сфере разработки и тестирования, и он / она принимает участие в полном процессе разработки ПО. В отличие от Quality Analyst (QA), которым желательны базовые знания в программировании, но нет необходимости писать код, SDET это делает на постоянной основе, совмещая в себе и тестировщика и разработчика.
<table>
<tr>
<td>SDET
</td><td>Manual Tester
</td></tr>
<tr>
<td>Знает всю систему от начала до конца
</td><td>Ограниченные знания о системе
</td></tr>
<tr>
<td>SDET участвует в каждом этапе процесса разработки ПО, как Проектирование, разработка и тестирование.
</td><td>QA участвует только в жизненном цикле тестирования процесса разработки ПО.
</td></tr>
<tr>
<td>Высококвалифицированный специалист со знаниями как в разработке, так и в тестировании
</td><td>Тестировщик ПО участвует только в подготовке и выполнении Test case
</td></tr>
<tr>
<td>SDET может участвовать в разработке средств автоматизации тестирования
</td><td>Не ожидается разработка средств автоматизации тестирования.
</td></tr>
<tr>
<td>SDET должны выполнять такие обязанности, как тестирование производительности, автоматическое создание тестовых данных и т. д. 
</td><td>Только задачи по ручному тестированию
</td></tr>
<tr>
<td>Знает требования и гайдлайны для продуктов
</td><td>От QA таких знаний не ожидается.
</td></tr>
</table>

<h2>Что такое тестирование как сервис? (TaaS – testing as a Service)</h2>
ТЕСТИРОВАНИЕ КАК СЕРВИС (TaaS) - это модель аутсорсинга, при которой деятельность по тестированию передается третьей стороне. Здесь тестирование проводится сторонними подрядчиками, а не сотрудниками организации. TaaS используется, когда Компании не хватает навыков или ресурсов для внутреннего тестирования или чтобы получить свежий взгляд со стороны. Чаще всего на аутсорс отдают тестирование функциональности, производительности и безопасности.
<h2>Что подразумевается под тестовой средой? (Test Environment/Test Bed)</h2>
Вообще существует несколько сред:
<ul>
<li>Среда разработки (Development Env) – в ней разработчики пишут код, проводят отладку, исправляют ошибки, выполняют Unit-тестирование. За эту среду отвечают также разработчики.
</li>
<li>Среда тестирования (Test Env) – в этой среде работают тестировщики. Тут тестируются новые билды. Здесь тестировщики проверяют функционал, проводят регрессионные проверки, воспроизводят ошибки. Эта среда появляется во время начала динамического тестирования;
</li>
<li>Интеграционная среда (Integration Env) – иногда реализована в рамках среды тестирования, а иногда в рамках превью среды. В этой среде собрана необходимая для end-to-end тестирования схема взаимодействующих друг с другом модулей, систем, продуктов. Собственно, необходима она для интеграционного тестирования. Поддержка среды – также, как и в случае со средой тестирования
</li>
<li>Превью среда (Preview, Preprod Env) – в идеале, это среда идентичная или максимально приближенная к продуктивной: те же данные, то же аппаратно-программное окружение, та же производительность. Она используется, чтобы сделать финальную проверку ПО в условиях максимально приближенным к «боевым». Здесь тестировщики проводят заключительное end-to-end тестирование функционала, бизнес и/или пользователи проводят UAT, а команды поддержки L3 и L2 выполняют DryRun (пробную установку релиза). Как правило за эту среду отвечает группа L3 поддержки.
</li>
<li>Продакшн среда (Production Env) – среда, в которой работают пользователи. С этой средой работает команда L2 поддержки устанавливая поставки ПО или патчи с исправлениями, выполняя настройки, отвечая за работоспособность всех систем. Инциденты и проблемы требующие исправления ПО передаются в работу команде на L3

</li>
</ul>
В общем случае среда тестирования - это настройка программного и аппаратного обеспечения для тестирования. 
Испытательный стенд (Test Bed) – более глобальная сущность и включает в себя operating system, configuration management for the products, hardware, network topology и т. д.  Настраиваются в соответствии с требованиями тестируемого приложения. В некоторых случаях испытательный стенд может представлять собой комбинацию тестовой среды и тестовых данных, которые он использует. 
Настройка правильной среды тестирования гарантирует успех тестирования ПО. Любые недостатки в этом процессе могут привести к дополнительным затратам и времени для клиента. Следующие люди участвуют в настройке тестовой среды: Системные администраторы, Разработчики, Тестировщики.

Доп. материал:
<ul>
<li><a href="https://coderlessons.com/tutorials/kachestvo-programmnogo-obespecheniia/ruchnoe-testirovanie/testovaia-sreda-2#:~:text=%D0%A1%D1%80%D0%B5%D0%B4%D0%B0%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%E2%80%94%20%D1%8D%D1%82%D0%BE%20%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE,%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%B4%D0%BB%D1%8F%20%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D1%85%20%D1%81%D0%BB%D1%83%D1%87%D0%B0%D0%B5%D0%B2.&text=%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0%20%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D1%81%D1%80%D0%B5%D0%B4%D1%8B%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%B3%D0%B0%D1%80%D0%B0%D0%BD%D1%82%D0%B8%D1%80%D1%83%D0%B5%D1%82%20%D1%83%D1%81%D0%BF%D0%B5%D1%85%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D1%8F.">Тестовая среда</a>
</li>
<li><a href="https://coderlessons.com/tutorials/kachestvo-programmnogo-obespecheniia/uznaite-stlc/stlc-nastroika-testovoi-sredy">STLC — настройка тестовой среды</a>
</li>
</ul>
<h2>Что подразумевается под тестовыми данными?</h2>
Тестовые данные - это набор входных значений, необходимых для выполнения Test case. тестировщики определяют данные в соответствии с требованиями. Они могут сделать это вручную или использовать инструменты генерации. 
<h2>Основные фазы тестирования?</h2>
<ul>
<li>Pre-Alpha: - ПО является прототипом. Пользовательский интерфейс завершен. Но не все функции завершены. На данном этапе ПО не публикуется. 
</li>
<li>Alpha: является ранней версией программного продукта. Цель - вовлечь клиента в процесс разработки. Хороший Альфа-тест должен иметь четко определенный план тестирования с комплексными тестовыми примерами. Это дает лучшее представление о надежности программного обеспечения на ранних стадиях. В некоторых случаях тестирование может быть передано на аутсорс. 
</li>
<li>Beta: ПО стабильно и выпускается для ограниченной пользовательской базы. Цель состоит в том, чтобы получить отзывы клиентов о продукте и внести соответствующие изменения в ПО. 
</li>
<li>Release Candidate (RC): основываясь на отзывах Beta Test, вы вносите изменения в ПО и хотите проверить исправления ошибок. На этом этапе вы не хотите вносить радикальные изменения в функциональность, а просто проверяете наличие ошибок. RC также выпущен для общественности 
</li>
<li>Release: Все работает, ПО выпущено для общественности. 
</li>
</ul>
<h2>Подробнее про бета-тестирование? </h2>
Бета-тестирование происходит на конечных пользователях. Это нужно для обеспечения обратной связи. 
Существуют различные типы бета-тестов в тестировании ПО, и они заключаются в следующем: 
<ul>
<li>Традиционное бета-тестирование: продукт распространяется на целевой рынок, и соответствующие данные собираются по всем аспектам. Эти данные могут быть использованы для улучшения продукта. 
</li>
<li>Публичное бета-тестирование: продукт публикуется во внешнем мире через онлайн-каналы, и данные могут быть получены от любого пользователя. На основе обратной связи могут быть сделаны улучшения продукта. 
</li>
<li>Техническое бета-тестирование: продукт передается во внутреннюю группу организации и собирает отзывы / данные от сотрудников организации. 
</li>
<li>Целевая бета-версия: продукт выпущен на рынок для сбора отзывов об особенностях программы. 
</li>
<li>Бета-версия после выпуска. Продукт выпущен на рынок, и данные собираются для внесения улучшений в будущем выпуске продукта.
</li>
</ul>
<h2>Что означает пилотное тестирование? (Pilot)</h2>
PILOT testing определяется как тип тестирования программного обеспечения, который проверяет компонент системы или всю систему в режиме реального времени. Целью пилотного теста является оценка осуществимости, времени, стоимости, риска и эффективности исследовательского проекта. Это тестирование проводится точно между UAT и Production. В пилотном тестировании выбранная группа конечных пользователей пробует тестируемую систему и предоставляет обратную связь до полного развертывания системы. Другими словами, это означает проведение генеральной репетиции для последующего теста на удобство использования. Пилотное тестирование помогает в раннем обнаружении ошибок в Системе.
Пилотное тестирование связано с установкой системы на площадке заказчика (или в среде, моделируемой пользователем) для тестирования на предмет постоянного и регулярного использования. Выявленные недостатки затем отправляются команде разработчиков в виде отчетов об ошибках, и эти ошибки исправляются в следующей сборке системы. Во время этого процесса иногда приемочное тестирование также включается как часть тестирования на совместимость. Это происходит, когда система разрабатывается для замены старой. 
<h2>В чем отличие build от release?</h2>
Билд это номер, даваемый ПО при передаче от разработчиков тестировщикам. Релиз — это номер, даваемый ПО при передаче конечному пользователю.
<h2>Что такое бизнес – логика (domain)?</h2>
Бизнес – логика (domain) это то, что конкретная программа по задумке должна сделать. Например, в складской программе проверка на возможность отправить товар (вдруг его нет в наличии). Это правила, которые должны соблюдаться в данной конкретной программе, определенные бизнес-клиентом. Слои приложения – слой пользовательского интерфейса, слой бизнес логики, слой сохранения данных.










<h1>----- Виды тестирования -----</h1>
<h2>Какие существуют основные виды тестирования ПО? </h2>
<ul>
<li>Функциональные виды («Что?» - проверяет весь функционал продукта):
</li>
<ul>
<li>Функциональное тестирование (Functional testing)
</li>
<li>Тестирование взаимодействия (Interoperability testing)
</li>
</ul>
<li>Нефункциональное («Как?»):
</li>
<ul>
<li>Производительности (Performance)
</li>
<ul>
<li>Тестирование емкости/способностей (Capacity testing)
</li>
<li>Стрессовое (Stress testing)
</li>
<li>Нагрузочное (Load testing)
</li>
<li>Объемное тестирование (Volume testing)
</li>
<li>Выносливости (Soak/Endurance testing)
</li>
<li>Стабильности/надежности (Stability / Reliability testing)
</li>
<li>Шиповое (Spike)
</li>
<li>Отказоустойчивости (Stability testing)
</li>
<li>Масштабируемости (Scalability test)
</li>
</ul>
<li>Отказ и восстановление (Failover and Recovery testing)
</li>
<li>Удобство пользования (Usability testing)
</li>
<li>Тестирование установки (Installation testing)
</li>
<li>Тестирование безопасности (Security and Access Control testing)
</li>
<li>Конфигурационное (Configuration testing)
</li>
</ul>
<li>Связанное с изменениями:
</li>
<ul>
<li>Регрессионное (Regression testing)
</li>
<li>Санитарное (Sanity testing)
</li>
<li>Дымовое (Smoke testing)
</li>
<li>Тестирование сборки (Build Verification testing)
</li>
</ul>
</ul>
В разных источниках предлагается разный взгляд:

<img src="https://lh5.googleusercontent.com/wKytfmj7ee7u7zgaRb-B1nfJwO-oTu_Q8Yidnf6df0BTZldvdGF-PqfaV4TgZp3sXnD60A3W4RzBniexE5SmESozeXHZJkT67_M_4kgt4WYxLsgiQqxEIwFCsA4UpfaJm-URQv7w">
<img src="https://lh4.googleusercontent.com/d6u6n4M8HenGww1y10nZZpQP22k-BrYomMm6WiZuY0jQhZxUubtRN1tXvFPyCJqp2RuZCDtjtuCf-GyXPzakS8g8IZXcAGRTr7jir3tp5UTXkZLAD_2139wAf3MbGJoMUDD2hACk">
<img src="https://lh3.googleusercontent.com/1MO0Dp2MwPU_ZOD46tlGIPKnGlrmvWog4E-cpVt5jm3jzEYkFx9IYYh9ONWaSVInu7M-JMVXd_H0mlqt87UkQ3s9HDgdHWD-yMEn6hCujYnOcPt5gnwuHVGuREr2ScAw9N2wds-e">

<h2>Типы тестирования? (White/Black/Grey Box)</h2>
Самым высоким уровнем в иерархии подходов к тестированию будет понятие типа, которое может охватывать сразу несколько смежных техник тестирования. То есть, одному типу тестирования может соответствовать несколько его видов. Отличаются они знанием внутреннего устройства объекта тестирования.
<h2>Что означает тестирование черного ящика?</h2>
Summary: Мы не знаем, как устроена внутри тестируемая система.
Тестирование методом «черного ящика», также известное как тестирование, основанное на спецификации или тестирование поведения – техника тестирования, основанная на работе исключительно с внешними интерфейсами тестируемой системы.
– тестирование, как функциональное, так и нефункциональное, не предполагающее знания внутреннего устройства компонента или системы.
– тест-дизайн, основанный на технике черного ящика – процедура написания или выбора тест-кейсов на основе анализа функциональной или нефункциональной спецификации компонента или системы без знания ее внутреннего устройства.
Почему именно «черный ящик»? Тестируемая программа для тестировщика – как черный непрозрачный ящик, содержания которого он не видит. Целью этой техники является поиск ошибок в таких категориях:
– неправильно реализованные или недостающие функции;
– ошибки интерфейса;
– ошибки в структурах данных или организации доступа к внешним базам данных;
– ошибки поведения или недостаточная производительности системы;
Таким образом, мы не имеем представления о структуре и внутреннем устройстве системы. Нужно концентрироваться на том, ЧТО программа делает, а не на том, КАК она это делает.
Пример:
Тестировщик проводит тестирование веб-сайта, не зная особенностей его реализации, используя только предусмотренные разработчиком поля ввода и кнопки. Источник ожидаемого результата – спецификация.
Поскольку это тип тестирования, по определению он может включать другие его виды. Тестирование черного ящика может быть как функциональным, так и нефункциональным. Функциональное тестирование предполагает проверку работы функций системы, а нефункциональное – соответственно, общие характеристики нашей программы.
Техника черного ящика применима на всех уровнях тестирования (от модульного до приемочного), для которых существует спецификация. Например, при осуществлении системного или интеграционного тестирования, требования или функциональная спецификация будут основой для написания тест-кейсов.
Техники тест-дизайна, основанные на использования черного ящика, включают:
– классы эквивалентности;
– анализ граничных значений;
– таблицы решений;
– диаграммы изменения состояния;
– тестирование всех пар.
Преимущества:
– тестирование производится с позиции конечного пользователя и может помочь обнаружить неточности и противоречия в спецификации;
– тестировщику нет необходимости знать языки программирования и углубляться в особенности реализации программы;
– тестирование может производиться специалистами, независимыми от отдела разработки, что помогает избежать предвзятого отношения;
– можно начинать писать тест-кейсы, как только готова спецификация.
Недостатки:
– тестируется только очень ограниченное количество путей выполнения программы;
– без четкой спецификации (а это скорее реальность на многих проектах) достаточно трудно составить эффективные тест-кейсы;
– некоторые тесты могут оказаться избыточными, если они уже были проведены разработчиком на уровне модульного тестирования;
Противоположностью техники черного ящика является тестирование методом белого ящика, речь о котором пойдет ниже.
<h2>Что означает тестирование белого ящика?</h2>
Тестирование методом белого ящика (также: прозрачного, открытого, стеклянного ящика; основанное на коде или структурное тестирование) – метод тестирования ПО, который предполагает, что внутренняя структура/устройство/реализация системы известны тестировщику. Мы выбираем входные значения, основываясь на знании кода, который будет их обрабатывать. Точно так же мы знаем, каким должен быть результат этой обработки. Знание всех особенностей тестируемой программы и ее реализации – обязательны для этой техники. Тестирование белого ящика – углубление во внутреннее устройство системы, за пределы ее внешних интерфейсов.
Техника белого ящика применима на разных уровнях тестирования – от модульного до системного, но главным образом применяется именно для реализации модульного тестирования компонента его автором.
Преимущества:
– тестирование может производиться на ранних этапах: нет необходимости ждать создания пользовательского интерфейса;
– можно провести более тщательное тестирование, с покрытием большого количества путей выполнения программы.
Недостатки:
– для выполнения тестирования белого ящика необходимо большое количество специальных знаний
Основным методом тестирования Белого ящика является анализ покрытия кода. Анализ покрытия кода устраняет пробелы в наборе тестовых примеров. Он определяет области программы, которые не покрываются набором Test case. После выявления пробелов вы создаете контрольные примеры для проверки непроверенных частей кода, тем самым повышая качество программного продукта.
<ul>
<li>Охват операторов: - Этот метод требует, чтобы каждое возможное утверждение в коде было проверено хотя бы один раз в процессе тестирования разработки ПО.
</li>
<li>Покрытие ветвления - этот метод проверяет все возможные пути (если-еще и другие условные циклы) программного приложения.
</li>
</ul>
Помимо вышесказанного, существует множество типов покрытия, таких как покрытие условий, покрытие нескольких условий, покрытие пути, покрытие функций и т. д. Каждый метод имеет свои достоинства и пытается протестировать (охватить) все части программного кода. Используя покрытие Statement и Branch, вы обычно достигаете 80-90% покрытия кода, что является достаточным.
<h2>Что означает тестирование серого ящика? (Grey box)</h2>
Тестирование методом серого ящика – метод тестирования ПО, который предполагает комбинацию White Box и Black Box подходов. То есть, внутреннее устройство программы нам известно лишь частично. Предполагается, например, доступ к внутренней структуре и алгоритмам работы ПО для написания максимально эффективных тест-кейсов, но само тестирование проводится с помощью техники черного ящика, то есть, с позиции пользователя. Либо нам не доступна внутренняя реализация функций, но мы знаем на уровень ниже, чем пользователи – интерфейсы/эндпоинты и т.п.
Техника серого ящика применима на разных уровнях тестирования – от модульного до системного, но главным образом применяется на интеграционном уровне для проверки взаимодействия разных модулей программы.
Пример тестирования «серого ящика»: при тестировании веб-сайтов на битые ссылки, если тестировщик сталкивается с какой-либо проблемой с этими ссылками, он может сразу же внести изменения в HTML-код и проверить в реальном времени.
Методы:
<ul>
<li>Матричное тестирование: этот метод тестирования включает в себя определение всех переменных, которые существуют в их программах. 
</li>
<li>Регрессионное тестирование: чтобы проверить, повлияло ли изменение в предыдущей версии другие аспекты программы в новой версии. 
</li>
<li>Тестирование ортогональных массивов или OAT: обеспечивает максимальное покрытие кода с минимальным количеством тестов. 
</li>
<li>Pattern testing: это тестирование выполняется на данных истории предыдущих дефектов системы. В отличие от тестирования черного ящика, в тестировании серого ящика копаются в коде и определяют причину сбоя.
</li>
</ul>
<h2>Основные отличия White/grey/black box?</h2>
<img src="https://lh3.googleusercontent.com/zLG0Og9z_pcH-Idqhj7-uH6TwRb0fMhaICI-Q5ITCmwDUpIq59SURBm0A4oeF6LRdubXzgIB270UsdoLnZSSv9QnHU2h5ohHWljsyaEVLaDPOiPUemtso56lkV7gewnYVpy2_5j5">
<h2>Что такое пирамида / уровни тестирования? (Testing Levels)</h2>
«Пирамида тестов» — метафора, которая означает группировку тестов программного обеспечения по разным уровням детализации. Она также дает представление, какое количество тестов должно быть в каждой из этих групп. 
<img src="https://lh6.googleusercontent.com/5AXlFPyJejfB3ItXS0NeMSKHTa_ty2lmavi4C_8B2Q2f5lovFxiRoWe32kdt7dIdeffo8qCoFsxXV-vnIemrOELuOeKidwk4ZdeLeOdSdBSQl77_amcF9dkZDo7QCwm1QXqHNMY8">
… В тесте более высокого уровня вы не тестируете всю условную логику и пограничные случаи, которые уже покрыты юнит-тестами более низкого уровня. Убедитесь, что тест высокого уровня фокусируется только на том, что не покрыто тестами более низкого уровня.
Правило трех А(AAA) (arrange, act, assert) или триада «дано, когда, тогда» — хорошая мнемоника, чтобы поддерживать хорошую структуру тестов. 

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/358950/">Пирамида тестов на практике</a>
</li>
<li><a href="https://habr.com/ru/post/358178/">Антипаттерны тестирования ПО</a>
</li>
<li><a href="https://telegra.ph/Unit-API-i-GUI-testy--chem-otlichayutsya-02-11">Unit, API и GUI тесты — чем отличаются</a>
</li>
<li><a href="https://dou.ua/lenta/columns/test-cases-dev-qa-analyst/">Почему тестировать должны не только QA. Распределяем тест-кейсы между Dev, Analyst и QA</a>
</li>
<li><a href="https://martinfowler.com/articles/practical-test-pyramid.html">The Practical Test Pyramid</a>
</li>
<li><a href="https://martinfowler.com/bliki/TestPyramid.html">Test Pyramid</a>
</li>
</ul>
<h2>Что такое деструктивное/разрушающее/негативное тестирование? (DT - Destructive testing)</h2>
ОТРИЦАТЕЛЬНОЕ ТЕСТИРОВАНИЕ - тип тестирования ПО для поиска точек отказа в программном обеспечении, который проверяет систему на обработку исключительных ситуаций (срабатывание валидаторов на некорректные данные), а также проверяет, что вызываемая приложением функция не выполняется при срабатывании валидатора. Неожиданные условия могут быть чем угодно, от неправильного типа данных до хакерской атаки. Целью отрицательного тестирования является предотвращение сбоя приложений из-за некорректных входных данных. Просто проводя положительное тестирование, мы можем только убедиться, что наша система работает в нормальных условиях. Мы должны убедиться, что наша система может справиться с непредвиденными условиями, чтобы обеспечить 100% безошибочную систему.
Типичные примеры: ввести неправильно составленный e-mail и номер телефона, загрузить файл не предусмотренного расширения или размера. 
Для деструктивного тестирования существует множество способов его тестирования: 
<ul>
<li>Метод анализа точек отказа: это пошаговое прохождение системы, проводящее оценку того, что может пойти не так в разных точках. Для этой стратегии может быть использована помощь BA (Business Analyst). 
</li>
<li>Экспертная проверка тестировщика: проанализируйте или дайте на ревью ваши Test вашему коллеге-тестировщику, который менее знаком с системой/функцией 
</li>
<li>Бизнес-анализ тестовых случаев. Конечные пользователи или эксперты могут подумать о многих допустимых сценариях, которые иногда тестировщики могут не учитывать или упустить, так как все их внимание будет сосредоточено на тестировании требований. 
</li>
<li>Проведите предварительное тестирование с использованием контрольных таблиц (run sheets). Исследовательское тестирование с использованием контрольных таблиц поможет определить, что было проверено, повторить тесты и позволит вам контролировать охват тестами. 
</li>
<li>Используйте другой источник: вы можете попросить кого-нибудь сломать программный продукт и проанализировать различные сценарии.
</li>
</ul>

Доп. материал:
<a href="https://testmatick.com/ru/top-10-negativnyh-test-kejsov-ispolzuemyh-vo-vremya-testirovaniya-po/">Топ 10 негативных кейсов</a>
<h2>Что такое недеструктивное/неразрушающее/позитивное тестирование? (NDT – Non Destructive testing)</h2>
НЕДЕСТРУКТИВНОЕ ТЕСТИРОВАНИЕ - это тип тестирования программного обеспечения, который включает в себя правильное взаимодействие с программным обеспечением. Другими словами, неразрушающее тестирование (NDT) также можно назвать позитивным тестированием или тестированием «счастливого пути». Это дает ожидаемые результаты и доказывает, что программное обеспечение ведет себя так, как ожидалось. Пример: - Ввод правильных данных в модуль входа в систему и проверка, принимает ли он учетные данные и переходит на следующую страницу
<h2>Что подразумевается под компонентным/модульным/юнит тестированием? (Component/Module/Unit testing)</h2>
С этими терминами происходит путаница и даже глоссарий ISTQB не проясняет ситуацию. Обычно эти термины используют как синонимы, а конкретика варьируется от компании к компании. Но если копнуть и попробовать разобраться, получается примерно следующее:
Модульное тестирование (юнит-тестирование). Модульные тесты используются для тестирования какого-либо одного логически выделенного и изолированного элемента системы (отдельные методы класса или простая функция, subprograms, subroutines, классы или процедуры) в коде. Очевидно, что это тестирование методом белого ящика и чаще всего оно проводится самими разработчиками. Целью тестирования модуля является не демонстрация правильного функционирования модуля, а демонстрация наличия ошибки в модуле, а также в определении степени готовности системы к переходу на следующий уровень разработки и тестирования. На уровне модульного тестирования проще всего обнаружить дефекты, связанные с алгоритмическими ошибками и ошибками кодирования алгоритмов, типа работы с условиями и счетчиками циклов, а также с использованием локальных переменных и ресурсов. Ошибки, связанные с неверной трактовкой данных, некорректной реализацией интерфейсов, совместимостью, производительностью и т.п. обычно пропускаются на уровне модульного тестирования и выявляются на более поздних стадиях тестирования. Изоляция тестируемого блока достигается с помощью заглушек (stubs), манекенов (dummies) и макетов (mockups). Являясь по способу исполнения структурным тестированием или тестированием "белого ящика", модульное тестирование характеризуется степенью, в которой тесты выполняют или покрывают логику программы (исходный текст). Тесты, связанные со структурным тестированием, строятся по следующим принципам:
<ul>
<li>На основе анализа потока управления. В этом случае элементы, которые должны быть покрыты при прохождении тестов, определяются на основе структурных критериев тестирования С0, С1,С2. К ним относятся вершины, дуги, пути управляющего графа программы (УГП), условия, комбинации условий и т. п.
</li>
<li>На основе анализа потока данных, когда элементы, которые должны быть покрыты, определяются при помощи потока данных, т. е. информационного графа программы.
</li>
</ul>
Тестирование на основе потока управления. Особенности использования структурных критериев тестирования С0,С1,С2 были рассмотрены ранее. К ним следует добавить критерий покрытия условий, заключающийся в покрытии всех логических (булевских) условий в программе. Критерии покрытия решений (ветвей - С1) и условий не заменяют друг друга, поэтому на практике используется комбинированный критерий покрытия условий/решений, совмещающий требования по покрытию и решений, и условий.
К популярным критериям относятся критерий покрытия функций программы, согласно которому каждая функция программы должна быть вызвана хотя бы один раз, и критерий покрытия вызовов, согласно которому каждый вызов каждой функции в программе должен быть осуществлен хотя бы один раз. Критерий покрытия вызовов известен также как критерий покрытия пар вызовов (call pair coverage).
Тестирование на основе потока данных. Этот вид тестирования направлен на выявление ссылок на неинициализированные переменные и избыточные присваивания (аномалий потока данных ). Предложенная там стратегия требовала тестирования всех взаимосвязей, включающих в себя ссылку (использование) и определение переменной, на которую указывает ссылка (т. е. требуется покрытие дуг информационного графа программы). Недостаток стратегии в том, что она не включает критерий С1, и не гарантирует покрытия решений.
Стратегия требуемых пар также тестирует упомянутые взаимосвязи. Использование переменной в предикате дублируется в соответствии с числом выходов решения, и каждая из таких требуемых взаимосвязей должна быть протестирована. К популярным критериям принадлежит критерий СР, заключающийся в покрытии всех таких пар дуг v и w, что из дуги v достижима дуга w, поскольку именно на дуге может произойти потеря значения переменной, которая в дальнейшем уже не должна использоваться. Для "покрытия" еще одного популярного критерия Cdu достаточно тестировать пары (вершина, дуга), поскольку определение переменной происходит в вершине УГП, а ее использование - на дугах, исходящих из решений, или в вычислительных вершинах.
Методы проектирования тестовых путей для достижения заданной степени тестированности в структурном тестировании. Процесс построения набора тестов при структурном тестировании принято делить на три фазы:
<ul>
<li>Конструирование УГП.
</li>
<li>Выбор тестовых путей.
</li>
<li>Генерация тестов, соответствующих тестовым путям.
</li>
</ul>
Первая фаза соответствует статическому анализу программы, задача которого состоит в получении графа программы и зависящего от него и от критерия тестирования множества элементов, которые необходимо покрыть тестами. На третьей фазе по известным путям тестирования осуществляется поиск подходящих тестов, реализующих прохождение этих путей. Вторая фаза обеспечивает выбор тестовых путей. Выделяют три подхода к построению тестовых путей:
<ul>
<li>Статические методы.
</li>
<li>Динамические методы.
</li>
<li>Методы реализуемых путей.
</li>
</ul>
Статические методы. Самое простое и легко реализуемое решение - построение каждого пути посредством постепенного его удлинения за счет добавления дуг, пока не будет достигнута выходная вершина управляющего графа программы. Эта идея может быть усилена в так называемых адаптивных методах, которые каждый раз добавляют только один тестовый путь (входной тест), используя предыдущие пути (тесты) как руководство для выбора последующих путей в соответствии с некоторой стратегией. Чаще всего адаптивные стратегии применяются по отношению к критерию С1. Основной недостаток статических методов заключается в том, что не учитывается возможная нереализуемость построенных путей тестирования.
Динамические методы. Такие методы предполагают построение полной системы тестов, удовлетворяющих заданному критерию, путем одновременного решения задачи построения покрывающего множества путей и тестовых данных. При этом можно автоматически учитывать реализуемость или нереализуемость ранее рассмотренных путей или их частей. Основной идеей динамических методов является подсоединение к начальным реализуемым отрезкам путей дальнейших их частей так, чтобы: 1) не терять при этом реализуемости вновь полученных путей; 2) покрыть требуемые элементы структуры программы.
Методы реализуемых путей. Данная методика заключается в выделении из множества путей подмножества всех реализуемых путей. После чего покрывающее множество путей строится из полученного подмножества реализуемых путей.
Достоинство статических методов состоит в сравнительно небольшом количестве необходимых ресурсов, как при использовании, так и при разработке. Однако их реализация может содержать непредсказуемый процент брака (нереализуемых путей). Кроме того, в этих системах переход от покрывающего множества путей к полной системе тестов пользователь должен осуществить вручную, а эта работа достаточно трудоемкая. Динамические методы требуют значительно больших ресурсов как при разработке, так и при эксплуатации, однако увеличение затрат происходит, в основном, за счет разработки и эксплуатации аппарата определения реализуемости пути (символический интерпретатор, решатель неравенств). Достоинство этих методов заключается в том, что их продукция имеет некоторый качественный уровень - реализуемость путей. Методы реализуемых путей дают самый лучший результат.
Компонентное тестирование — тип тестирования ПО, при котором тестирование выполняется для каждого отдельного компонента отдельно, без интеграции с другими компонентами. Его также называют модульным тестированием (Module testing), если рассматривать его с точки зрения архитектуры. Как правило, любое программное обеспечение в целом состоит из нескольких компонентов. Тестирование на уровне компонентов (Component Level testing) имеет дело с тестированием этих компонентов индивидуально. Это один из самых частых типов тестирования черного ящика, который проводится командой QA. Для каждого из этих компонентов будет определен сценарий тестирования, который затем будет приведен к Test case высокого уровня -> детальным Test case низкого уровня с предварительными условиями.
Исходя из глубины уровней тестирования, компонентное тестирование можно классифицировать как:
<ul>
<li>Тестирование компонентов в малом (CTIS — Component testing In Small). Тестирование компонентов может проводиться с или без изоляции остальных компонентов в тестируемом программном обеспечении или приложении. Если это выполняется с изоляцией другого компонента, то это называется CTIS. Пример: веб-сайт, на котором есть 5 разных веб-страниц, тестирование каждой веб-страницы отдельно и с изоляцией других компонентов.
</li>
</ul>
<ul>
<li>Тестирование компонентов в целом (CTIL — Component testing In Large). Тестирование компонентов, выполненное без изоляции других компонентов в тестируемом программном обеспечении или приложении, называется CTIL. Давайте рассмотрим пример, чтобы понять это лучше. Предположим, что есть приложение, состоящее из трех компонентов, таких как Компонент A, Компонент B и Компонент C. Разработчик разработал компонент B и хочет его протестировать. Но для того, чтобы полностью протестировать компонент B, некоторые его функции зависят от компонента A, а некоторые — от компонента C. Функциональный поток: A -> B -> C, что означает, что существует зависимость от B как от A, так и от C, заглушка - вызываемая функция, а драйвер - вызывающая функция. Но компонент A и компонент C еще не разработаны. В этом случае, чтобы полностью протестировать компонент B, мы можем заменить компонент A и компонент C заглушкой и драйверами по мере необходимости. Таким образом, в основном, компоненты A & C заменяются заглушками и драйверами, которые действуют как фиктивные объекты до тех пор, пока они фактически не будут разработаны.
</li>
</ul>

<table>
<tr>
<td>Unit testing
</td><td>Component testing
</td></tr>
<tr>
<td>Тестирование отдельных программ, модулей, функций для демонстрации того, что программа выполняется согласно спецификации
</td><td>Тестирование каждого объекта или частей программного обеспечения отдельно с или без изоляции других объектов
</td></tr>
<tr>
<td>Проверка в(на) соответствии с design documents
</td><td>Проверка в(на) соответствии с test requirements, use case
</td></tr>
<tr>
<td>Пишутся и выполняются(обычно) разработчиками
</td><td>Тестировщиками
</td></tr>
<tr>
<td>Выполняется первым
</td><td>Выполняется после Unit
</td></tr>
</table>

Другой источник:
Разница между компонентным и модульным тестированием: По-существу эти уровни тестирования представляют одно и тоже, разница лишь в том, что в компонентном тестировании в качестве параметров функций используют реальные объекты и драйверы, а в модульном тестировании - конкретные значения.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/skyeng/blog/521324/">Я сомневался в юнит-тестах, но…</a>
</li>
<li><a href="https://habr.com/ru/company/qiwi/blog/510608/">Юнит-тесты переоценены</a>
</li>
</ul>
<h2>Что подразумевается под интеграционным тестированием? (Integration testing)</h2>
Интеграционное тестирование предназначено для проверки насколько хорошо два или более модулей ПО взаимодействуют друг с другом, а также взаимодействия с различными частями системы (операционной системой, оборудованием либо связи между различными системами). С технологической точки зрения интеграционное тестирование является количественным развитием модульного, поскольку так же, как и модульное тестирование, оперирует интерфейсами модулей и подсистем и требует создания тестового окружения, включая заглушки ( Stub ) на месте отсутствующих модулей. Основная разница между модульным и интеграционным тестированием состоит в целях, то есть в типах обнаруживаемых дефектов, которые, в свою очередь, определяют стратегию выбора входных данных и методов анализа. В частности, на уровне интеграционного тестирования часто применяются методы, связанные с покрытием интерфейсов, например, вызовов функций или методов, или анализ использования интерфейсных объектов, таких как глобальные ресурсы, средства коммуникаций, предоставляемых операционной системой. Больше: <a href="https://www.intuit.ru/studies/courses/48/48/lecture/1432?page=1">https://www.intuit.ru/studies/courses/48/48/lecture/1432?page=1</a>
Уровни интеграционного тестирования:
<ul>
<li>Компонентный интеграционный уровень (Component Integration testing): Проверяется взаимодействие между компонентами системы после проведения компонентного тестирования.
</li>
<li>Системный интеграционный уровень (System Integration testing): Проверяется взаимодействие между разными системами после проведения системного тестирования.
</li>
</ul>
Подходы к интеграционному тестированию:
<ul>
<li>Подход Большого взрыва:
</li>
<li>Инкрементальный подход:
</li>
<ul>
<li>Нисходящий подход
</li>
<li>Подход снизу-вверх
</li>
<li>Сэндвич-подход
</li>
</ul>
</ul>
Некоторые утверждают, что всех участников (например, вызываемые классы) тестируемого субъекта следует заменить на имитации (mocks) или заглушки (stubs), чтобы создать идеальную изоляцию, избежать побочных эффектов и сложной настройки теста. Другие утверждают, что на имитации и заглушки следует заменять только участников, которые замедляют тест или проявляют сильные побочные эффекты (например, классы с доступом к БД или сетевыми вызовами). Иногда эти два вида юнит-тестов называют одинокими (solitary) в случае тотального применения имитаций и заглушек или общительными (sociable) в случае реальных коммуникаций с другими участниками.
Информация должна приходить в течение нескольких секунд или нескольких минут с быстрых тестов на ранних этапах конвейера. И наоборот, более длительные тесты — обычно с более широкой областью — размещаются на более поздних этапах, чтобы не тормозить фидбек от быстрых тестов. Как видите, этапы конвейера развертывания определяются не типами тестов, а их скоростью и областью действия. Поэтому очень разумно может быть разместить некоторые из самых узких и быстрых интеграционных тестов на ту же стадию, что и юнит-тесты — просто потому что они дают более быструю обратную связь
Доп. материал:
<ul>
<li><a href="https://tproger.ru/articles/integracionnye-testy-v-mikroservisah/">Интеграционные тесты в микросервисах</a>
</li>
<li><a href="https://intuit.ru/studies/courses/48/48/lecture/1434">Лекция 6: Интеграционное тестирование и его особенности для объектно-ориентированного программирования</a>
</li>
</ul>
<h2>Разница между Unit testing и Integration testing?</h2>
Именно здесь больше всего споров о названиях. «Область» интеграционных тестов также весьма противоречива, особенно по характеру доступа к приложению (тестирование в черном или белом ящике; разрешены mock-объекты или нет). На практике получается так: если тест…
<ul>
<li>использует базу данных,
</li>
<li>использует сеть для вызова другого компонента/приложения,
</li>
<li>использует внешнюю систему (например, очередь или почтовый сервер),
</li>
<li>читает/записывает файлы или выполняет другие операции ввода-вывода,
</li>
<li>полагается не на исходный код, а на бинарник приложения,
</li>
</ul>
… то это интеграционный, а не модульный тест

<img src="https://lh3.googleusercontent.com/rfOAqBWrJ5y_D6_tgcJGp9M-lEIlWxeAn3zWxYMDaXkL-6T-CBgymdtHlZ0HKuucvZyejFqKUHcO_a0HKenap6WnPkl4KBj5Mz4RWkMAKWEfGRluxPIXbMPcUJ9qC9tQunT55rTV">
Подведем итог: хотя теоретически можно использовать только интеграционные тесты, на практике
<ul>
<li>Юнит-тесты легче поддерживать.
</li>
<li>Юнит-тесты легко воспроизводят пограничные случаи и редкие ситуации.
</li>
<li>Юнит-тесты выполняются гораздо быстрее интеграционных тестов.
</li>
<li>Сбойные юнит-тесты легче исправить, чем интеграционные.
</li>
</ul>
Если у вас есть только интеграционные тесты, то вы впустую тратите и время разработки, и деньги компании. Нужны как модульные, так и интеграционные тесты одновременно. Они не взаимоисключающие.
<h2>Что такое системное интеграционное тестирование? (SIT - System Integration testing)</h2>
Это тип тестирования программного обеспечения, проводимого в интегрированной аппаратной и программной среде для проверки поведения всей системы. Это тестирование, проведенное на полной интегрированной системе для оценки соответствия системы ее установленным требованиям. SIT выполняется для проверки взаимодействия между модулями программной системы. Оно занимается проверкой требований к программному обеспечению высокого и низкого уровня, указанных в Software Requirements Specification/Data and the Software Design Document. Он также проверяет сосуществование программной системы с другими и тестирует интерфейс между модулями программного приложения. В этом типе тестирования модули сначала тестируются индивидуально, а затем объединяются в систему. Например, программные и / или аппаратные компоненты объединяются и тестируются постепенно, пока не будет интегрирована вся система.
<h2>Что подразумевается под инкрементальным подходом? (Incremental Approach)</h2>
При таком подходе тестирование выполняется путем объединения двух или более логически связанных модулей. Затем другие связанные модули поэтапно добавляются и тестируются для правильного функционирования. Процесс продолжается до тех пор, пока все модули не будут соединены и успешно протестированы. Осуществляется двумя разными методами: Снизу-вверх и сверху-вниз.
<h2>Что подразумевается под подходом снизу-вверх? (Bottom-Up Approach)</h2>
В восходящей стратегии каждый модуль на более низких уровнях последовательно тестируется с более высокоуровневыми модулями, пока не будут протестированы все модули. Требуется помощь драйверов для тестирования. Данный подход считается полезным, если все или практически все модули, разрабатываемого уровня, готовы. Также данный подход помогает определить по результатам тестирования уровень готовности приложения.
Преимущества: Локализация ошибок проще. Не тратится время на ожидание разработки всех модулей, в отличие от подхода Большого взрыва 
Недостатки: Критические модули (на верхнем уровне архитектуры ПО), которые контролируют поток приложения, тестируются последними и могут быть подвержены дефектам. Ранний прототип невозможен.
<img src="https://lh5.googleusercontent.com/3OXvBS-5b6ClVPNOksMO1nO9IuG5l4IKpcFcTfVFAJkb0ABby7wsdZu_8YflWOaFT0WGud9rXRkTZrBO8wzz7put0eWDqSpLkDu1Gb-VghigbKFfrIbiN5RMm55YKiZB-BG-6k2Y">
<h2>Что подразумевается под подходом сверху-вниз? (Top-Down Approach)</h2>
Вначале тестируются все высокоуровневые модули, и постепенно один за другим добавляются низкоуровневые. Все модули более низкого уровня симулируются заглушками с аналогичной функциональностью, затем по мере готовности они заменяются реальными активными компонентами.
Преимущества: Локализация неисправностей проще. Возможность получить ранний прототип. Основные недостатки дизайна могут быть найдены и исправлены в первую очередь. Недостатки: Нужно много заглушек. Модули на более низком уровне тестируются недостаточно.
<img src="https://lh6.googleusercontent.com/aqen2464jdbgFFAsX0OdNWGyfQyLGfE5BPoDwYCCX0GMSGZrZyCwT5hkw7CLsvGItmPtYpC0pzL4f2IBfg1hivyYTGFH6KIGQzJkzU6DLU8tv3gmz9syYNb1D1RFncXtc4qNZ-X7">
<h2>Что подразумевается под гибридным/сэндвич-подходом? (Sandwich Approach)</h2>
Представляет собой комбинацию подходов сверху вниз и снизу-вверх. Здесь верхние модули тестируются с нижними модулями, а нижние модули интегрируются с верхними модулями и тестируются. Эта стратегия использует и заглушки и драйверы.
<img src="https://lh3.googleusercontent.com/9SvWxP9sbOEcigN9CBYsXwTnLlbGOhhbd_SqazHOgRmtOwoYPiExZtubi2qgFmcxOuSDU6OKnc6RBYdm5_FL8cHfpLJ1iaq7Tr4UAdrOfFCydpQ-0K_vAsQhgyzXo-7kNfnxCmO8">
<h2>Что подразумевается под подходом Большого взрыва?  (Big Bang Approach)</h2>
Все или практически все разработанные модули собираются вместе в виде законченной системы или ее основной части, и затем проводится интеграционное тестирование. Такой подход очень хорош для сохранения времени. Однако если Test case и их результаты записаны не верно, то сам процесс интеграции сильно осложнится, что станет преградой для команды тестирования при достижении основной цели интеграционного тестирования
<h2>В чем разница между тест-драйвером и тест-заглушкой? (Test Driver and Test Stub)</h2>
Тестовый драйвер - это фрагмент кода, который вызывает тестируемый программный компонент. Это полезно при тестировании по принципу «снизу-вверх». Тестовая заглушка - это фиктивная программа, которая интегрируется с приложением для полной функциональности. Они актуальны для тестирования, в котором используется нисходящий подход. Давайте возьмем пример. 
1. Допустим, есть сценарий для проверки интерфейса между модулями A и B. Мы разработали только модуль-A. Затем мы можем проверить модуль-A, если у нас есть реальный модуль-B или фиктивный модуль для него. В этом случае мы называем модуль-B тестовой заглушкой. 
2. Теперь модуль B не может отправлять или получать данные напрямую из модуля A. В таком сценарии мы перемещаем данные из одного модуля в другой, используя некоторые внешние функции, называемые Test Driver.
Заглушки и драйверы не реализуют всю логику программного модуля, а только моделируют обмен данными с вызывающим модулем. Заглушка: вызывается тестируемым модулем. Драйвер: вызывает модуль для тестирования.
<h2>Что подразумевается под системным тестированием? </h2>
Системное тестирование качественно отличается от интеграционного и модульного уровней. Системное тестирование рассматривает тестируемую систему в целом и оперирует на уровне пользовательских интерфейсов, в отличие от последних фаз интеграционного тестирования, которое оперирует на уровне интерфейсов модулей. Различны и цели этих уровней тестирования. На уровне системы часто сложно и малоэффективно анализировать прохождение тестовых траекторий внутри программы или отслеживать правильность работы конкретных функций. Основная задача системного тестирования - в выявлении дефектов, связанных с работой системы в целом, таких как неверное использование ресурсов системы, непредусмотренные комбинации данных пользовательского уровня, несовместимость с окружением, непредусмотренные сценарии использования, отсутствующая или неверная функциональность, неудобство в применении и тому подобное.
Системное тестирование производится над проектом в целом с помощью метода "черного ящика". Структура программы не имеет никакого значения, для проверки доступны только входы и выходы, видимые пользователю.
Категории тестов системного тестирования:
<ul>
<li>Полнота решения функциональных задач.
</li>
<li>Стрессовое тестирование - на предельных объемах нагрузки входного потока.
</li>
<li>Корректность использования ресурсов (утечка памяти, возврат ресурсов).
</li>
<li>Оценка производительности.
</li>
<li>Эффективность защиты от искажения данных и некорректных действий.
</li>
<li>Проверка инсталляции и конфигурации на разных платформах.
</li>
<li>Корректность документации
</li>
</ul>
Для минимизации рисков, связанных с особенностями поведения системы в той или иной среде, во время тестирования рекомендуется использовать окружение максимально приближенное к тому, на которое будет установлен продукт после выдачи. Системное тестирование относят к черному ящику.
Можно выделить два подхода к системному тестированию:
<ul>
<li>на базе требований (requirements based): Для каждого требования пишутся <a href="http://www.protesting.ru/testing/testcase.html">Test case</a>, проверяющие выполнение данного требования.
</li>
<li>на базе случаев использования (use case based): На основе представления о способах использования продукта создаются случаи использования системы (Use Cases). По конкретному случаю использования можно определить один или более сценариев. На проверку каждого сценария пишутся <a href="http://www.protesting.ru/testing/testcase.html">Test case</a>, которые должны быть протестированы.
</li>
</ul>
Доп. материал:
<a href="https://intuit.ru/studies/courses/48/48/lecture/1436">Лекция 7: Разновидности тестирования: системное и регрессионное тестирование</a>

<h2>Можем ли мы провести системное тестирование на любом этапе? </h2>
Нет. Системное тестирование следует начинать, только если все модули написаны и работают правильно. Тем не менее, это должно произойти до UAT (пользовательского приемочного тестирования).
<h2>Что такое функциональное тестирование?</h2>
Функциональное тестирование рассматривает заранее указанное поведение и основывается на анализе спецификаций функциональности компонента или системы в целом.
Функциональные тесты основываются на функциях, выполняемых системой, и могут проводиться на всех уровнях тестирования (компонентном, интеграционном, системном, приемочном). Как правило, эти функции описываются в требованиях, функциональных спецификациях или в виде случаев использования системы (use cases).
Тестирование в перспективе «требования» использует спецификацию функциональных требований к системе как основу для дизайна Test case. В этом случае необходимо сделать список того, что будет тестироваться, а что нет, приоритезировать требования на основе рисков (если это не сделано в документе с требованиями), а на основе этого приоритезировать тестовые сценарии. Это позволит сфокусироваться и не упустить при тестировании наиболее важный функционал.
Тестирование в перспективе «бизнес-процессы» использует знание этих самых бизнес-процессов, которые описывают сценарии ежедневного использования системы. В этой перспективе тестовые сценарии (test scripts), как правило, основываются на случаях использования системы (use cases).
Преимущества функционального тестирования:
<ul>
<li>имитирует фактическое использование системы;
</li>
</ul>
Недостатки функционального тестирования:
<ul>
<li>возможность упущения логических ошибок в программном обеспечении;
</li>
<li>вероятность избыточного тестирования.
</li>
</ul>
<h2>Что такое тестирование совместимости/взаимодействия? (Compatibility/Interoperability testing)</h2>
Тестирование взаимодействия - функциональное тестирование, проверяющее способность приложения/устройства взаимодействовать с одним и более компонентами/системами/устройствами и включающее в себя тестирование совместимости (compatibility testing) и интеграционное тестирование (integration testing). 
ПО с хорошими характеристиками взаимодействия может быть легко интегрировано с другими системами, не требуя каких-либо серьезных модификаций. В этом случае, количество изменений и время, требуемое на их выполнение, могут быть использованы для измерения возможности взаимодействия. Например, тестирование совместимости проводится между смартфонами и планшетами для проверки передачи данных через Bluetooth.
Существуют разные уровни тестирования совместимости:
<ul>
<li>Аппаратное обеспечение: проверяет совместимость программного обеспечения с различными аппаратными конфигурациями. 
</li>
<li>Операционные системы: Он проверяет ваше программное обеспечение на совместимость с различными операционными системами, такими как Windows, Unix*, Mac OS и т. д. 
</li>
<li>Программное обеспечение: проверяет ваше разработанное программное обеспечение на совместимость с другим программным обеспечением. Например, приложение MS Word должно быть совместимо с другими программами, такими как MS Outlook, MS Excel, VBA и т. д. 
</li>
<li>Сеть: оценка производительности системы в сети с различными параметрами, такими как пропускная способность, скорость работы, емкость. 
</li>
<li>Браузер: проверяет совместимость вашего сайта с различными браузерами, такими как Firefox, Google Chrome, Internet Explorer и т. д. 
</li>
<li>Устройства: проверяет совместимость вашего программного обеспечения с различными устройствами, такими как устройства USB-порта, принтеры и сканеры, другие мультимедийные устройства и Bluetooth. 
</li>
<li>Mobile: проверка совместимости вашего программного обеспечения с мобильными платформами, такими как Android, iOS и т. д. 
</li>
<li>Версии программного обеспечения. Он проверяет совместимость вашего программного приложения с различными версиями программного обеспечения. Например, проверка вашего Microsoft Word на совместимость с Windows 7, Windows 7 SP1, Windows 7 SP2, Windows 7 SP3.
</li>
</ul>
Существует два типа проверки версий:
<ul>
<li>Тестирование обратной совместимости предназначено для проверки поведения разработанного аппаратного / программного обеспечения с использованием более старых версий аппаратного / программного обеспечения. 
</li>
<li>Тестирование прямой совместимости заключается в проверке поведения разработанного аппаратного / программного обеспечения с использованием более новых версий аппаратного / программного обеспечения.
</li>
</ul>
Пример тестирования взаимодействия: 
<ul>
<li>Подключите (connect) два или более устройств от разных производителей 
</li>
<li>Проверьте связь между устройствами 
</li>
<li>Проверьте, может ли устройство отправлять / получать пакеты или фреймы друг от друга 
</li>
<li>Проверьте, правильно ли обрабатываются данные на уровне сети и объектов 
</li>
<li>Проверьте, правильно ли работают реализованные алгоритмы 
</li>
<li>Результат в порядке: проверьте следующий результат. Результат не в порядке: используйте инструменты мониторинга, чтобы обнаружить источник ошибки 
</li>
<li>Отчет о результатах в тестовом отчете.
</li>
</ul>
<h2>Что такое тестирование на соответствие? (Conformance/Compilance testing)</h2>
CONFORMANCE testing - это тип тестирования программного обеспечения, который удостоверяет, что система программного обеспечения соответствует стандартам и правилам, определенным IEEE, W3C или ETSI. Цель проверки соответствия состоит в том, чтобы определить, в какой степени отдельная реализация конкретного стандарта соответствует индивидуальным требованиям этого стандарта. Включает в себя: 
<ul>
<li>Производительность
</li>
<li>Функции 
</li>
<li>Прочность (Robustness)
</li>
<li>Совместимость (Interoperability) 
</li>
<li>Поведение системы
</li>
</ul>
Тестирование соответствия может быть логическим или физическим, и оно включает в себя следующие типы тестирования: 
<ul>
<li>Тестирование на соответствие (Compliance testing)
</li>
<li>Нагрузочное тестирование (<a href="https://www.guru99.com/load-testing-tutorial.html">Load testing</a>)
</li>
<li>Стресс тестирование (<a href="https://www.guru99.com/stress-testing-tutorial.html">Stress testing</a>)
</li>
<li>Объемное тестирование (Volume testing)
</li>
</ul>

<table>
<tr>
<td>Conformance testing
</td><td>Compliance testing
</td></tr>
<tr>
<td>Conformance является формальным и точным способом тестирования стандартов
</td><td>Compliance является неформальным и менее точным способом тестирования стандартов
</td></tr>
<tr>
<td>Сертификация Conformance применима только к операционной системе, имеющей официальный Certification Authority
</td><td>Операционная система, которая обеспечивает единый API (Portable Operating System Interface), считается совместимой
</td></tr>
<tr>
<td>Conformance testing используется для тестирования системы, которая обеспечивает полную поддержку данных стандартов
</td><td>Compliance testing используется для тестирования системы, обеспечивающей поддержку некоторых из указанных стандартов
</td></tr>
</table>
Тестирование соответствия также называется Type testing, который является формальным способом тестирования.
<h2>Что такое нефункциональное тестирование?</h2>
НЕФУНКЦИОНАЛЬНОЕ тестирование определяется как тип тестирования ПО для проверки нефункциональных аспектов ПО. Оно предназначено для проверки готовности системы по нефункциональным параметрам, которые никогда не учитываются при функциональном тестировании.
<ul>
<li>Нефункциональное тестирование должно повысить удобство использования, эффективность, ремонтопригодность и portability продукта. 
</li>
<li>Помогает снизить производственный риск и затраты, связанные с нефункциональными аспектами продукта. 
</li>
</ul>
Позволяет:
<ul>
<li>оптимизировать способ установки, настройки, выполнения, управления и мониторинга продукта. 
</li>
<li>Собирать и производить измерения и метрики для внутренних исследований и разработок. 
</li>
<li>Улучшать и расширять знания о поведении продукта и используемых технологиях.
</li>
</ul>

Основные нефункциональные типы тестирования:
<ul>
<li>Производительности (Performance)
</li>
<ul>
<li>Стрессовое (Stress testing)
</li>
<li>Тестирование емкости/способностей (Capacity testing)
</li>
<li>Нагрузочное (Load testing)
</li>
<li>Объемное тестирование (Volume testing)
</li>
<li>Выносливости/стабильности/надежности (Soak/Endurance/Stability/Reliability testing)
</li>
<li>Шиповое (Spike)
</li>
<li>Масштабируемости (Scalability Test)
</li>
</ul>
<li>Тестирование времени отклика (Response Time testing)
</li>
<li>Тестирование на отказоустойчивость (Failover testing)
</li>
<li>Тестирование совместимости (Compatibility testing)
</li>
<li>Тестирование на удобство пользования (Usability testing)
</li>
<li>Тестирование на поддерживаемость/ремонтопригодность (Maintainability testing)
</li>
<li>Тестирование безопасности (Security testing)
</li>
<li>Тестирование аварийного восстановления (Disaster Recovery testing)
</li>
<li>Тестирование на соответствие (Compliance testing)
</li>
<li>Тестирование переносимости (Portability testing)
</li>
<li>Тестирование эффективности (Efficiency testing)
</li>
<li>Базовое тестирование (Baseline testing)
</li>
<li>Тестирование документации (Documentation testing)
</li>
<li>Тестирование восстановления (Recovery testing)
</li>
<li>Интернационализация (Globalization/Internationalization testing)
</li>
<li>Тестирование локализации (Localization testing)
</li>
</ul>
<h2>Основные понятия в тестировании производительности?</h2>
<ul>
<li>Время задержки (Latency) - временной интервал между запросом и ответом. Например, у вашего сервиса время задержки составляет 100ms, что означает, что такому сервису потребуется 100 миллисекунд на обработку запроса и генерирование ответа. Как правило, чем ниже время задержки, тем лучше клиентский опыт.
</li>
<li>Время ответа (Response time) - время, необходимое для ответа на запрос 
</li>
<li>Пропускная способность (Throughput) - фактическое количество запросов (или пользователей), которое может обработать система за определенное время. В то время как время задержки говорит вам только о времени, метрика пропускной способности информирует об объеме данных, полученных и обработанных в момент времени. Важно не отделять показатели времени задержки от пропускной способности, т.к. высокий показатель времени задержки часто прямо связан с увеличением показателей метрики пропускной способности. Пропускная способность обычно измеряется в rps – (кол-во) запросов в секунду (requests per second).
</li>
<li>Ширина пропускания канала (Bandwidth) - максимальное число запросов (или пользователей), которое может обработать система. В отличие от пропускной способности ширина пропускания канала измеряет максимальный объем, который может обработать приложение.
</li>
<li>Транзакции в секунду. Пользовательские транзакции – это последовательность действий пользователя в интерфейсе. Сравнивая реальное время прохождения транзакции с ожидаемой (или количество транзакций в секунду), вы сможете сделать вывод о том, насколько успешной системой было пройдено нагрузочное тестирование.
</li>
<li>Процент ошибок рассчитывается как отношение невалидных ответов к валидным за промежуток времени.
</li>
<li>Про Average, медианы, перцентили и т.п. углубляться в рамках этой статьи не буду, есть в гугле.
</li>
</ul>
<h2>Тестирование производительности клиентской части и серверной, в чем разница?</h2>
Оценка скорости работы клиентской и серверной частей веб-приложения осуществляется двумя разными видами тестирования: для Frontend применяется тестирование клиентской части, или Client-Side testing, а для Back-end – тестирование серверной части.
Основная цель тестирования клиентской части состоит в измерении времени, необходимого браузеру, для загрузки HTML-страницы. Наиболее важными показателями здесь являются количество загружаемых данных, их объем, а также количество выполненных запросов.
Собрать данную статистику можно как с использованием встроенных инструментов браузера (DevTools), так и с помощью специализированных инструментов и онлайн-сервисов, которые позволяют замерить необходимые показатели с учетом интересующего региона.
Помимо общего веса страницы, инструменты предоставляют детализированную информацию по каждому из компонентов. Изучив параметры запросов, можно обнаружить ряд проблем, приводящих к ухудшению скорости отображения страницы. К примеру, подгружается слишком большая картинка и Javascript, или отправляется значительное количество запросов.
Другая необходимая проверка направлена на анализ заголовков кэширования, поскольку корректность его выполнения при повторном посещении страницы позволяет повысить скорость загрузки страницы до 80%.
Тестирование серверной части направлено на анализ выполнения запросов и получения соответствующего ответа от Back-end.
Цели данного вида тестирования:
<ul>
<li>Измерить время отклика самых важных бизнес-транзакций;
</li>
<li>Определить предельный уровень допустимой нагрузки;
</li>
<li>Выявить «узкие» места в производительности системы;
</li>
<li>Составить рекомендации по улучшению производительности;
</li>
<li>Найти возможные дефекты, проявляющиеся только при одновременной работе большого количества пользователей.
</li>
</ul>

<h2>В общем виде что такое тестирование производительности?</h2>
Это класс тестирования ПО, который фокусируется на производительности системы при определенной нагрузке. Он не ищет напрямую ошибки или дефекты. Он производит аналитику на основе эталонных тестов и предоставляет разработчику всю диагностическую информацию, необходимую для выявления проблем производительности и узких мест. При этом происходит:
<ul>
<li>измерение времени выполнения выбранных операций при определенных интенсивностях выполнения этих операций
</li>
<li>определение количества пользователей, одновременно работающих с приложением
</li>
<li>определение границ приемлемой производительности при увеличении нагрузки (при увеличении интенсивности выполнения этих операций)
</li>
<li>исследование производительности на высоких, предельных, стрессовых нагрузках
</li>
</ul>

Важно понимать, что все подвиды тестирования производительности это, грубо говоря, одно и то же, просто в зависимости от конкретного подвида выбираются разные параметры (показатели нагрузки/пользователей, длительности и т.п.) и собираются соответствующие метрики. Точкой отсчета принято брать результаты Capacity testing. 
В реальном мире проводят только часть из перечисленных подвидов в соответствии с бюджетом и приоритетами данного ПО, а параметры тестов и метрики могут корректироваться в разных ситуациях.

<img src="https://lh6.googleusercontent.com/XNuV1_4ya69jlZ7lkW-Dovc1xycy-zvrcGAKyoQxni7AITleD6eO4lsHsIp2PVA-CzpHCFrCX0MX9vBZRMHroN9i1YfDD70rIL0VdNq2593APZqVDkF-cVpLSByaOXR8XXTFuvgB">
Небольшая заметка. Несмотря на необходимость понимания многих математических и статистических концепций, многие тестировщики и менеджеры либо не имеют достаточных знаний в области математики и статистики, либо не пользуются ими. Это приводит к значительным искажениям и неверной интерпретации результатов тестирования производительности. Поэтому хороший специалист должен обладать и смежными знаниями.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/tinkoff/blog/514314/">Анализ результатов нагрузочного тестирования</a>
</li>
<li><a href="https://habr.com/ru/company/vdsina/blog/536304/">Нагрузочное тестирование выполнять сложно, а инструменты далеки от совершенства. Почему?</a>
</li>
<li><a href="https://tproger.ru/articles/nagruzochnoe-testirovanie-osobennosti-professii/">Нагрузочное тестирование: особенности профессии</a>
</li>
</ul>

<h2>Что такое тестирование емкости/способностей? (Capacity)</h2>
Capacity — базовый тест, который обычно выполняется первым. Все последующие тесты на среднее время ответа, регенерацию системы, утилизацию ресурсов нужно выполнять с оглядкой на результаты Capacity. Емкость системы измеряется в rps (requests per second). Используемый подход: ступенчато повышаем нагрузку до момента, когда время ответа начнет расти экспоненциально. Экспоненциальный рост времени ответа, как правило, связан с полной утилизацией одного из ресурсов, из-за которого запросы вместо моментальной обработки выстраиваются друг за другом и ждут своей очереди на обработку. 
<img src="https://lh5.googleusercontent.com/NFbeBOzq9h_517Zw0uK569eq3k0kWY2BBiORQVKKTa1Gqi0EuS3KeYNQ2Y5NfI7fpFJexd1CaC4SeDhXDz4Be9oS_ryYROMbNHoJ-CKOFinOHxeNH4r6Oh50lgxHyYDxxUgarqGw">
Capacity point – точка, где перестает расти Throughput, но увеличивается Response Time, то есть система перестает справляться с запросами.
Исходя из этого тестирования выбираются значения для stress, load и soak/endurance тестов. Для stress берется значение близкое к capacity point, но немного меньше. Для load количество пользователей из зоны деградации. 
Важно, ваша цель, не получить кол-во rps, при котором все взрывается, а понять, какой именно ресурс станет узким местом, при повышении нагрузки. Поэтому, если обстреливаемый вами сервер не покрыт мониторингом — можете даже не начинать тест. Общий подход к сбору телеметрии — чем больше метрик собирается, тем лучше.
В некоторых случаях Capacity называют так же Scalability (масштабируемость), но в целом это не равнозначные понятия.
<h2>Что означает тестирование масштабируемости? (Scalability)</h2>
Профиль нагрузки тот же, что и при нагрузочном тестировании. Что получаем в результате? Ответы на следующие вопросы:
<ul>
<li>Увеличится ли производительность приложения, если добавить дополнительные аппаратные ресурсы?
</li>
<li>Увеличится ли производительность пропорционально количеству добавленных аппаратных средств?
</li>
</ul>
Разница между тестированием емкости/способностей и тестированием масштабируемости? (Capacity vs Scalability)
Тестирование масштабируемости - это тестирование программного приложения для измерения его способности увеличивать или уменьшать масштаб с точки зрения любых его нефункциональных возможностей. Тестирование производительности, масштабируемости и надежности обычно группируется аналитиками качества ПО. 
Тестирование емкости измеряет, сколько пользователей может обработать приложение. Это подмножество тестирования масштабируемости, в котором при тестировании масштабируемости вы получите меру емкости приложения. Тестирование масштабируемости измеряет, насколько хорошо приложение справляется с растущим числом пользователей. Если вы тестируете масштабируемость до тех пор, пока приложение не выйдет из строя, у вас будет мера того, сколько пользователей (емкость) может обработать приложение.
<h2>Расскажите о стрессовом тестировании? (Stress testing)</h2>
Стрессовое тестирование выполняется самым первым, если нет отдельного Capacity тестирования, хотя по факту это все равно будет Capacity, т.к. нагрузка берется «с потолка». Позволяет проверить насколько приложение и система в целом работоспособны в условиях высокой нагрузки. Нагрузка на систему будет возрастать непрерывно до тех пор, пока не будет достигнут один из критериев его остановки. Пример: стресс-тест банковской системы был остановлен при превышении отметки в 1500 пользователей, когда высокая загруженность процессора (более 80%) привела к увеличению среднего времени отклика в пять раз и массовому появлению ошибок HTTP(S).
<img src="https://lh3.googleusercontent.com/aIJG3A1Mujx5ChXCbyeoY7SBwy06KdJSOjREYmcbiBXJdUdBDMxypKzoxodqx3l4JU7ouVi2zLrmZw8OSOHy_QxwxuYZc2qh65G2VOhuqVSrponf-MQNWmAFGwacN8luIGCaoRmc">
<h2>Расскажите о нагрузочном тестировании? (Load)</h2>
Нагрузочное тестирование - это тестирование, имитирующее работу определенного количества бизнес пользователей на каком-либо общем (разделяемом ими) ресурсе. Этот тип тестирования производительности выполняется для диагностики поведения системы при увеличении рабочей нагрузки.
Нагрузка на систему обычно подается на протяжении 1-2 часов (в некоторых источниках: 4-8 часов, хотя это уже больше endurance), количество пользователей для нагрузочного теста берется из зоны деградации (в некоторых источниках: определяется в количестве 80% от результата максимальной производительности). В это время собираются метрики производительности: количество запросов в секунду, транзакций в секунду, время отклика от сервера, процент ошибок в ответах, утилизация аппаратных ресурсов и т. д. 
<img src="https://lh3.googleusercontent.com/KQDgZCIEO4LqnoxMqJNaTZ3F7_bxgN7oKJfQzY_uw7FUdT8ssHCirc5E1J9l6L9lF_PXaVQIg6J1M1YsQiLv7MTAaccr3w2WmB3_0BSxo454ossgqrPGDAErf2eal5Pt0IUycExM">

<h2>Что такое объемное тестирование? (Volume testing)</h2>
Объемное тестирование предназначено для прогнозирования того, может ли система / приложение обрабатывать большой объем данных. Это тестирование сосредоточено на наполнении базы данных продукта в реальных сценариях использования.
Пример 1: отправка через POST-запросы очень большого количества данных. 
Пример 2: как изменится производительность приложения спустя X лет, если аудитория приложения вырастет в Y раз?
<h2>Тестирование выносливости/стабильности/надежности (Soak/Endurance/Stability/Reliability testing)</h2>
Задачей тестирования стабильности является проверка работоспособности приложения при длительном (многочасовом) тестировании со средним уровнем нагрузки. Время выполнения операций может играть в данном виде тестирования второстепенную роль. При этом на первое место выходит проверка на утечки памяти, время отклика, правильность подключения и закрытия подключения к модулям (например, БД) и т.п. в течение длительного времени, чтобы гарантировать, что после длительного периода время отклика системы останется таким же или лучше, чем на начало теста. Этот тип тестирования выполняется в самом конце (а где-то по ночам). Так же он помогает управлять будущими нагрузками, ведь нам необходимо понять, сколько дополнительных ресурсов (таких как ЦП, емкость диска, использование памяти или пропускная способность сети) необходимы для поддержки использования в будущем.
<h2>Что такое спайк/шиповое тестирование? (Spike)</h2>
Этот вид тестирования предназначен для определения поведения системы при внезапном увеличении нагрузки (большого количества пользователей) на систему. Например, дни распродаж в интернет-магазине.
<h2>Что такое тестирование устойчивости? (Resilence)</h2>
Проверка устойчивости проводится для того, чтобы убедиться, что система способна вернуться в исходное состояние после кратковременного напряжения. Например, если в интернет-магазине действует скидка на определенные товары на короткое время, скажем, один час в день.

Доп.материал:
<a href="https://github.com/Netflix/chaosmonkey">Chaos Monkey</a>
<h2>Что такое тестирование времени отклика? (Response time testing)</h2>
Время ответа относится ко времени, которое требуется одному системному узлу для ответа на запрос другого. Среднее время ответа - это среднее время, затрачиваемое на каждый запрос в оба конца. Пиковое время отклика помогает нам определить, какие компоненты потенциально проблематичны. Коэффициент ошибок - это математический расчет, который отображает процент проблемных запросов. Три критических значения времени отклика: 0,1 секунды, 1,0 секунды и 10 секунд.
<h2>Что такое Ramp тестирование? </h2>
Это метод тестирования, который предлагает ступенчато поднимать нагрузку до тех пор, пока система не выйдет из строя. 
<h2>Что такое тестирование хранилища? (Storage testing)</h2>
Тестирование хранилища определяется как тип тестирования программного обеспечения, который проверяет, сохраняет ли тестируемое приложение соответствующие данные в соответствующих каталогах и достаточно ли у него места для предотвращения неожиданного завершения из-за недостатка дискового пространства. Это также называется тестированием производительности хранилища (Storage Performance testing).
Зачем оно нужно? 
<ul>
<li>Медленное хранилище означает медленное время отклика, длительные запросы и более низкую availability приложений. 
</li>
<li>Медленное хранилище - это накладные расходы на обслуживание серверной инфраструктуры. 
</li>
<li>Также помогает найти практическое ограничение хранилища перед деплоем. 
</li>
<li>Помогает понять, как система будет реагировать при замене или обновлении аппаратного обеспечения.
</li>
</ul>
Типы:
<ul>
<li>Application testing: Тестирование приложений с примерами запросов в production like environment
</li>
<ul>
<li>Сравните время ответа OLTP 
</li>
<li>Сравните время выполнения batch 
</li>
<li>Сравните rates непрерывной потоковой передачи
</li>
</ul>
<li>Application Simulation: Проведите тестирование с использованием стандартного программного обеспечения, аналогичного целевому приложению 
</li>
<ul>
<li>Протестировать на пиковые значения IOPS для баз данных 
</li>
<li>Тест пика для data streaming environments 
</li>
<li>Проверка задержек хранилища для обмена сообщениями или других однопоточных приложений
</li>
</ul>
<li>Benchmarking: Провести тестирование с использованием стандартного программного обеспечения. 
</li>
<ul>
<li>Проверка на повреждение данных.
</li>
</ul>
</ul>
<h2>Что такое тестирование на отказ и восстановление? (Failover and Recovery testing)</h2>
Тестирование на отказ и восстановление (Failover and Recovery testing) проверяет тестируемый продукт с точки зрения способности противостоять и успешно восстанавливаться после возможных сбоев, возникших в связи с ошибками ПО, отказами оборудования или проблемами связи/сети. Целью данного вида тестирования является проверка систем восстановления (или дублирующих основной функционал систем), которые, в случае возникновения сбоев, обеспечат сохранность и целостность данных тестируемого продукта.
Тестирование на отказ и восстановление очень важно для систем, работающих по принципу "24x7". Если Вы создаете продукт, который будет работать, например, в интернете, то без проведения данного вида тестирования Вам просто не обойтись. Т.к. каждая минута простоя или потеря данных в случае отказа оборудования, может стоить вам денег, потери клиентов и репутации на рынке.
Методика подобного тестирования заключается в симулировании различных условий сбоя и последующем изучении, и оценке реакции защитных систем. В процессе подобных проверок выясняется, была ли достигнута требуемая степень восстановления системы после возникновения сбоя.
Для наглядности рассмотрим некоторые варианты подобного тестирования и общие методы их проведения. Объектом тестирования в большинстве случаев являются весьма вероятные эксплуатационные проблемы, такие как:
<ul>
<li>Отказ электричества на компьютере-сервере
</li>
<li>Отказ электричества на компьютере-клиенте
</li>
<li>Незавершенные циклы обработки данных (прерывание работы фильтров данных, прерывание синхронизации).
</li>
<li>Объявление или внесение в массивы данных невозможных или ошибочных элементов.
</li>
<li>Отказ носителей данных.
</li>
</ul>
Стоит заметить, что тестирование на отказ и восстановление – это весьма продукт-специфичное тестирование. Разработка тестовых сценариев должна производиться с учетом всех особенностей тестируемой системы. Принимая во внимание довольно жесткие методы воздействия, стоит также оценить целесообразность проведения данного вида тестирования для конкретного программного продукта.
<h2>Что вы знаете о Тестировании удобства пользования? (Usability testing)</h2>
Тестирование удобства пользования - это метод тестирования, направленный на установление степени удобства использования, обучаемости, понятности и привлекательности для пользователей разрабатываемого продукта в контексте заданных условий.
Тестирование удобства пользования дает оценку уровня удобства использования приложения по следующим пунктам:
<ul>
<li>производительность, эффективность (efficiency) - сколько времени и шагов понадобится пользователю для завершения основных задач приложения, например, размещение новости, регистрации, покупка и т. д. ? (меньше - лучше)
</li>
<li>правильность (accuracy) - сколько ошибок сделал пользователь во время работы с приложением? (меньше - лучше)
</li>
<li>активизация в памяти (recall) – как много пользователь помнит о работе приложения после приостановки работы с ним на длительный период времени? (повторное выполнение операций после перерыва должно проходить быстрее чем у нового пользователя)
</li>
<li>эмоциональная реакция (emotional response) – как пользователь себя чувствует после завершения задачи - растерян, испытал стресс? Порекомендует ли пользователь систему своим друзьям? (положительная реакция - лучше)
</li>
</ul>
Проверка удобства использования может проводиться как по отношению к готовому продукту, посредством тестирования черного ящика (black box testing), так и к интерфейсам приложения (API), используемым при разработке - тестирование белого ящика (white box testing). В этом случае проверяется удобство использования внутренних объектов, классов, методов и переменных, а также рассматривается удобство изменения, расширения системы и интеграции ее с другими модулями или системами. Использование удобных интерфейсов (API) может улучшить качество, увеличить скорость написания и поддержки разрабатываемого кода, и как следствие улучшить качество продукта в целом.
Отсюда становится очевидно, что тестирование удобства пользования может производиться на разных уровнях разработки ПО: модульном, интеграционном, системном и приемочном.


Доп. материал:
<a href="https://vc.ru/marketing/200995-vkusnyy-i-zdorovyy-gayd-po-yuzabiliti-testirovaniyam">Вкусный и здоровый гайд по юзабилити-тестированиям</a>
<h2>Отличия тестирование на удобство пользования и тестирования доступности? (Usability Vs. Accessibility testing)</h2>
USABILITY testing показывает, насколько проста в использовании и удобна система программного обеспечения. Здесь небольшой набор целевых конечных пользователей «использует» программную систему для выявления дефектов юзабилити. Основное внимание в этом тестировании уделяется простоте использования приложения пользователем, гибкости в управлении средствами управления и способности системы выполнять свои задачи. Это также называется тестированием пользовательского опыта (UX – "Ю-Экс", user experience). Это тестирование рекомендуется на начальном этапе разработки SDLC, что позволяет лучше понять ожидания пользователей. Исследования (Virzi, 1992 и Neilsen Landauer, 1993) показывают, что 5 пользователей достаточно для выявления 80% проблем с юзабилити, хотя некоторые исследователи предлагают другие цифры.
Тестирование доступности (accessibility testing) - это подмножество юзабилити-тестирования. Его цель - убедиться в том, что наш продукт удобен в использовании для людей с различными видами инвалидности или особенностей восприятия. Это могут быть проблемы со зрением, слухом или ограничения в подвижности рук. 
Ваш продукт должен правильно работать с соответствующим ПО. Примеры такого программного обеспечения:
<ul>
<li>Speech Recognition Software - ПО преобразует произнесенное слово в текст, который служит вводом для компьютера. 
</li>
<li>Программа для чтения с экрана - используется для озвучивания текста, отображаемого на экране 
</li>
<li>Программное обеспечение для увеличения экрана - используется для увеличения масштаба элементов и облегчения чтения для пользователей с нарушениями зрения. 
</li>
<li>Специальная клавиатура, облегчающая ввод для пользователей, у которых проблемы с двигательными функциями.
</li>
</ul>
Еще один из примеров - люди с цветовой слепотой (дальтонизмом). Эта особенность довольно широко распространена. Различными видами цветовой слепоты страдают около 8 % мужчин и 0,4 % женщин - не так уж мало!
Цвет не должен быть единственным способом передачи информации. Если вы используете цвет для того, чтобы, допустим, отобразить статус, эту информацию стоит продублировать еще каким-то образом - геометрическими фигурами, иконками или текстовым комментарием. 
Хорошая контрастность. Хорошая контрастность обеспечивает нормальную видимость элементов управления и текста даже для людей, не различающих те или иные оттенки.
Есть отличный инструмент для тестирования веб-сайтов на предмет доступности для людей с различными формами цветовой слепоты: Color Blind Web Page Filter.
 <img src="https://lh3.googleusercontent.com/yq2LgYAT7WG6k1-uARt38HzPsKtfIFZCL2YaSwdVI-50X6uXChgPjaiiQFsARtf06z4aPVGlaATms2MH_WSPNvn2yafEGQ3G8_lEoPFXzliwCNU9S37fqsUbrEyG5p6CrdyYEsdY">
Если вы хотите сократить количество тестов, можно ограничиться только тремя фильтрами: дейтеранопия, протанопия и тританопия. Это наиболее выраженные формы цветовой слепоты (не считая крайне редкого черно-белого зрения). Остальные люди с особенностями цветовосприятия видят больше оттенков, и если ваш UI достаточно хорошо виден с этими тремя фильтрами, то и для остальных будет отображаться корректно.
Пример чек-листа:
<ul>
<li>Предоставляет ли приложение клавиатурные эквиваленты для всех действий мышью и окон? 
</li>
<li>Предоставляются ли инструкции как часть пользовательской документации или руководства? Легко ли понять и использовать приложение, используя документацию? 
</li>
<li>Упорядочены ли вкладки логически для обеспечения плавной навигации? 
</li>
<li>Предусмотрены ли сочетания клавиш для меню? 
</li>
<li>Поддерживает ли приложение все операционные системы? 
</li>
<li>Четко ли указано время отклика каждого экрана или страницы, чтобы конечные пользователи знали, как долго ждать? 
</li>
<li>Все ли надписи правильно написаны? 
</li>
<li>Являются ли цвета подходящим для всех пользователей? 
</li>
<li>Правильно ли используются изображения или значки, чтобы их было легко понять конечным пользователям? 
</li>
<li>Есть ли звуковые оповещения? 
</li>
<li>Может ли пользователь настроить аудио или видео элементы управления? 
</li>
<li>Может ли пользователь переопределить шрифты по умолчанию для печати и отображения текста? 
</li>
<li>Может ли пользователь настроить или отключить мигание, вращение или перемещение элементов? 
</li>
<li>Убедитесь, что цветовое кодирование никогда не используется в качестве единственного средства передачи информации или указания на действие 
</li>
<li>Видна ли подсветка с инвертированными цветами? 
</li>
<li>Тестирование цвета в приложении путем изменения контрастности 
</li>
<li>Правильно ли слышат люди с ограниченными возможностями все имеющее отношение к аудио и видео?
</li>
<li>Протестируйте все мультимедийные страницы без мультимедиа-оборудования. 
</li>
<li>Предоставляется ли обучение пользователям с ограниченными возможностями, что позволит им ознакомиться с программным обеспечением или приложением?
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/redmadrobot/blog/504110/">QA и его роль в создании ресурсов для людей с ограниченными возможностями</a>
</li>
<li><a href="https://habr.com/ru/company/edison/blog/474472/">Чеклист по UX из 30 пунктов для мобильных приложений</a>
</li>
<li><a href="https://cdn2.hubspot.net/hubfs/5358007/WCAG_2.1_Checklist.pdf">Web Content Accessibility Guidelines</a>
</li>
</ul>
<h2>Что такое тестирование интерфейса?</h2>
Это тип интеграционного теста, который проверяет, правильно ли установлена ​​связь между двумя различными программными системами или их частями (модулями). Соединение, которое объединяет два компонента, называется интерфейсом. Этот интерфейс в компьютерном мире может быть чем угодно, как API, так и веб-сервисами и т. д.  Тестирование этих подключаемых сервисов или интерфейса называется Тестированием интерфейса.
Тестирование интерфейса включает в себя тестирование двух основных сегментов: 
<ul>
<li>Интерфейс веб-сервера и сервера приложений 
</li>
<li>Интерфейс сервера приложений и базы данных
</li>
</ul>
<h2>Что такое тестирование рабочего процесса/воркфлоу? (Workflow testing)</h2>
Это тип тестирования программного обеспечения, который проверяет, что каждый software workflow точно отражает данный бизнес-процесс. Workflow - это серия задач для получения желаемого результата, которая обычно включает несколько этапов или шагов. Для любого бизнес-процесса тестирование этих последовательных шагов определяется как «WorkFlow testing».
Например, убедитесь, что система может быть установлена ​​на платформе пользователя и работает правильно. Тестирование рабочего процесса проводится поэтапно. Вот как вы будете выполнять Workflow testing:
<ul>
<li>Начальная фаза (Inception phase): эта фаза включает начальное планирование испытаний и тестирование прототипа 
</li>
<li>Фаза разработки (Elaboration phase): Эта фаза включает базовую архитектуру тестирования 
</li>
<li>Фаза строительства (Construction phase): эта фаза включает в себя значительные испытания в каждой сборке 
</li>
<li>Фаза перехода (Transition phase): Эта фаза включает в себя регрессионные тесты и повторные тесты исправлений
</li>
</ul>
Тестирование workflow выполняется:
<ul>
<li>Test engineer: планирует цели теста и график. Определяет Test case и процедуры. Оценивает результаты теста.
</li>
<li>Component engineer: Разработка тестовых компонентов. Автоматизирует некоторые тестовые процедуры.
</li>
<li>Integration Tester: Выполнение интеграционных тестов и выявление дефектов 
</li>
<li>System Testers: Выполнение системных тестов и отчеты о дефектах
</li>
</ul>
<h2>Что вы знаете о пользовательском приемочном тестировании? (UAT – User Acceptance testing)</h2>
Пользовательское приемочное тестирование (UAT) - это тип тестирования, выполняемый конечным пользователем или клиентом для проверки / принятия ПО перед его перемещением в production. UAT выполняется на заключительном этапе тестирования после выполнения функциональных, интеграционных и системных испытаний. Основной целью UAT является проверка end-to-end business flow. Он не фокусируется на косметических ошибках, орфографических ошибках или тестировании системы. Приемочное тестирование пользователя выполняется в отдельной среде тестирования с настройкой данных, аналогичных производственным. Это своего рода тестирование черного ящика, в котором будут участвовать два или более конечных пользователя. Этапы:
<ul>
<li>Анализ бизнес-требований 
</li>
<li>Создать плана тестирования UAT 
</li>
<li>Определить Test Scenario 
</li>
<li>Создать Test case UAT 
</li>
<li>Подготовить Test Data (Production like Data) 
</li>
<li>Запустить Test case
</li>
<li>Записать результаты
</li>
<li>Подтвердить бизнес-цели
</li>
</ul>
<h2>Что такое эксплуатационное приемочное тестирование? (OAT - Operational Acceptance testing)</h2>
ИСПЫТАНИЕ НА ЭКСПЛУАТАЦИЮ (OAT) - это тип тестирования программного обеспечения, который оценивает операционную готовность программного приложения до его выпуска в производство. Целью эксплуатационного тестирования является обеспечение бесперебойной работы системы в ее стандартной операционной среде (SOE - standard operating environment). Это также называется Оперативное тестирование (Operational testing). Эксплуатационное приемочное тестирование обеспечивает соответствие системы и компонентов в стандартной операционной среде приложения (SOE). Типы OAT:
<ul>
<li>Installation testing
</li>
<li>Load & Performance Test Operation
</li>
<li>Backup and Restore testing
</li>
<li><a href="https://www.guru99.com/what-is-security-testing.html">Security testing</a>
</li>
<li>Code Analysis
</li>
<li>Fail over testing
</li>
<li>Recovery testing
</li>
<li>End-to-End<a href="https://www.guru99.com/test-environment-software-testing.html"> Test Environment </a>Operational testing
</li>
<li>Operational Documentation Review
</li>
</ul>
Примеры Test case:
<ul>
<li>Резервные копии, сделанные на одном сайте, могут быть развернуты на тот же сайт 
</li>
<li>Резервные копии, сделанные на одном сайте, можно развернуть на другом сайте. 
</li>
<li>Внедрение любых новых функций в живую производственную среду не должно отрицательно влиять на целостность текущих производственных услуг. 
</li>
<li>Процесс внедрения может быть воспроизведен с использованием действующей документации 
</li>
<li>Каждый компонент может быть отключен и успешно запущен в согласованные сроки. 
</li>
<li>Для оповещений - все критические оповещения должны идти в TEC и ссылаться на документ правильного разрешения. 
</li>
<li>Оповещения созданы и выдаются при превышении согласованных пороговых значений 
</li>
<li>Любая документация по восстановлению, созданная или измененная, включая сервисные диаграммы, действительна 
</li>
<li>Это должно быть передано в соответствующие области поддержки. 
</li>
<li>Любой компонент, на который влияет сбой, должен показывать рекомендуемый порядок перезапуска, время завершения и т. д. 
</li>
</ul>
<h2>Расскажите об инсталляционном тестировании?</h2>
Тестирование инсталляции (установки) направленно на проверку успешной инсталляции и настройки, а также обновления или удаления ПО, как десктопного, так и мобильного.
Тестирование инсталляции в большинстве своем не входит в Веб-тестирование, являясь специализированным тестированием установки приложений на различные операционные системы.
Следующие проверки должны быть выполнены для этапов:
Установка. 
<ul>
<li>Установка должна начаться при клике по кнопке, подтверждающей данное действие
</li>
<li>Установки во всех поддерживаемых окружениях и на всех поддерживаемых платформах
</li>
<li>Установки в неподдерживаемых окружениях, а также в нужных окружениях с некорректными настройками
</li>
<li>Права, которые требует инсталляция (чаще всего они должны быть админскими), проверить установить приложение как гость
</li>
<li>Установки в clean state (при отсутствии любых возможных связанных файлов и предыдущих версий)
</li>
<li>Подсчитывается ли при установке количество свободного места на диске и выдается ли предупреждение если места недостаточно
</li>
<li>Установки загруженного ранее приложения, а также прямая установка с использованием сети/беспроводного соединения
</li>
<li>Восстановится ли процесс установки при внезапном его прерывании (отключение устройства, отказ сети, отключение беспроводного соединения)
</li>
<li>Установка приложения, его запуск, удаление приложения должны возвращать систему в исходное состояние
</li>
<li>Распознается ли наличие в системе приложений/программ, необходимых для корректной работы устанавливаемого приложения
</li>
<li>Повторный запуск установки приложения при уже текущем должен выдавать корректное сообщение, двойная установка должна быть исключена
</li>
<li>Процесс установки может быть настраиваемый/дефолтный. Убедиться, что оба корректно работают
</li>
<li>Наличие кнопки, которая предложит сохранить приложение в определенную папку, а также указывает дефолтное местоположение ("C:/programs/.")
</li>
<li>Правильно ли установлены, сохранены ли в корректных папках файлы приложения
</li>
<li>Наличие созданных ярлыков, корректно ли они расположены
</li>
<li>После установки в системной вкладке " Программы и компоненты" должны быть доступны: название приложения, иконка, имя издателя, размер приложения, дата установки и номер версии
</li>
<li>Настройки переменных сред PATH
</li>
<li>Убедиться, что лицензионный ключ сохраняется в Windows Registry library
</li>
<li>Поддерживает ли приложение функции ‘UnInstall’, ‘Modify’, ‘ReInstall’ и корректно ли они работают
</li>
<li>Работа приложения с уже существующими DLL-файлами, с DLL-файлами приложений, которые необходимы для корректной работы устанавливаемого приложения
</li>
<li>Наличие информации/сообщение о том, когда истекает срок действия установленной пробной версии приложения
</li>
</ul>
Обновление:
<ul>
<li>Поддерживает ли приложение функцию обновления/автообновления
</li>
<li>При попытке установить ранее установленную версию приложения система должна ее распознать и выдать корректное сообщение
</li>
<li>Сохраняются ли пользовательские настройки при попытке загрузить новую версию/обновить старую версию
</li>
<li>При попытке обновить версию должны быть доступны функции удалить приложение и восстановить приложение
</li>
<li>Стандартные проверки как при первичной установке приложения
</li>
<li>Убедиться, что номер версии приложения сменился новым
</li>
<li>Запустить приложение и убедиться, что оно работает корректно
</li>
</ul>
Откат до предыдущей версии:
<ul>
<li>Попробовать установить старую версию на более новую
</li>
<li>Наличие корректного сообщения при попытке отката
</li>
<li>Убедиться, что приложение работает корректно
</li>
</ul>
Удаление приложения:
<ul>
<li>Не остается ли в системе никаких папок/файлов/ярлыков/ключей реестра после полного удаления приложения
</li>
<li>Корректно ли работает система после установки и последующего удаления приложения
</li>
</ul>
<h2>Что вы знаете о тестировании безопасности? (Security and Access Control testing)</h2>
Это тип тестирования ПО, который выявляет уязвимости, угрозы и риски. Целью тестов безопасности является выявление всех возможных лазеек и слабых мест в ПО, которые могут привести к потере информации, доходов, репутации компании, сотрудников или клиентов. Общая стратегия безопасности основывается на трех основных принципах:
<ul>
<li>Конфиденциальность - сокрытие определенных ресурсов или информации
</li>
<li>Целостность – ресурс может быть изменен только в соответствии с полномочиями пользователя
</li>
<li>Доступность - ресурсы должны быть доступны только авторизованному пользователю, внутреннему объекту или устройству
</li>
</ul>
Тестирование безопасности обычно выполняет отдельный специалист по безопасности. В ходе тестирования безопасности испытатель играет роль взломщика. Ему разрешено все:
<ul>
<li>попытки узнать пароль с помощью внешних средств;
</li>
<li>атака системы с помощью специальных утилит, анализирующих защиты;
</li>
<li>подавление, ошеломление системы (в надежде, что она откажется обслуживать других клиентов);
</li>
<li>целенаправленное введение ошибок в надежде проникнуть в систему в ходе восстановления;
</li>
<li>просмотр несекретных данных в надежде найти ключ для входа в систему.
</li>
</ul>
При неограниченном времени и ресурсах хорошее тестирование безопасности взломает любую систему. Задача проектировщика системы — сделать цену проникновения более высокой, чем цена получаемой в результате информации.
Типы тестирования безопасности:
<ul>
<li>Сканирование уязвимостей/оценка защищенности (Vulnerability Scanning) выполняется с помощью автоматизированного ПО для сканирования системы на наличие известных сигнатур уязвимостей. 
</li>
<li>Сканирование безопасности (Security Scanning) включает в себя выявление слабых сторон сети и системы, а затем предоставляет решения для снижения этих рисков. Это сканирование может быть выполнено как ручным, так и автоматизированным.
</li>
<li>Тестирование на проникновение (Penetration testing) - этот тип тестирования имитирует атаку злоумышленника. Это тестирование включает анализ конкретной системы для проверки потенциальных уязвимостей при попытке внешнего взлома. 
</li>
<li>Оценка рисков (Risk Assessment) тестирование включает анализ рисков безопасности, наблюдаемых в организации. Риски классифицируются как Низкие, Средние и Высокие. Это тестирование рекомендует меры по снижению риска. 
</li>
<li>Аудит безопасности (Security Auditing) - внутренняя проверка приложений и операционных систем на наличие уязвимостей. Аудит также может быть выполнен путем построчной проверки кода 
</li>
<li>Этический взлом (Ethical hacking) - совершается с целью выявления проблем безопасности в системе. Это делается White Hat хакерами - это специалисты по безопасности, которые использует свои навыки законным способом для помощи в выявлении дефектов системы, в отличии от Black Hat (преступников) или Gray Hat (что-то между).
</li>
<li>Оценка состояния (Posture Assessment) объединяет сканирование безопасности, этический взлом и оценки рисков, чтобы показать общее состояние безопасности организации.
</li>
</ul>

<table>
<tr>
<td>SDLC фаза
</td><td>Security Processes
</td></tr>
<tr>
<td>Requirements
</td><td>Анализ безопасности для требований и проверка случаев злоупотребления / неправильного использования
</td></tr>
<tr>
<td>Design
</td><td>Анализ рисков безопасности для проектирования. Разработка плана тестирования с учетом тестирования безопасности
</td></tr>
<tr>
<td>Coding and Unit testing
</td><td>Статическое и динамическое тестирование безопасности и тестирование белого ящика 
</td></tr>
<tr>
<td>Integration testing
</td><td>Тестирование черного ящика
</td></tr>
<tr>
<td>System testing
</td><td>Тестирование черного ящика и сканирование уязвимостей
</td></tr>
<tr>
<td>Implementation
</td><td>Тестирование на проникновение, сканирование уязвимостей
</td></tr>
<tr>
<td>Support
</td><td>Анализ воздействия патчей
</td></tr>
</table>

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/ruvds/blog/537456/">Топ-10 уязвимостей мобильных приложений и способы их устранения</a>
</li>
<li><a href="https://habr.com/ru/post/526878/">Безопасность веб-приложений: от уязвимостей до мониторинга</a>
</li>
<li><a href="https://habr.com/ru/company/group-ib/blog/535092/">Социотехническое тестирование: какое лучше выбрать в 2021 году?</a>
</li>
<li><a href="https://www.youtube.com/playlist?list=PLrCZzMib1e9owORdnWTvZIkSCqRFFbHGA">Анализ безопасности веб-проектов</a>
</li>
<li><a href="https://www.youtube.com/playlist?list=PLrCZzMib1e9qiiSWgZ6pI5HiQzFc4hhdo">Безопасность интернет-приложений</a>
</li>
<li><a href="https://habr.com/ru/company/varonis/blog/524308/">Red Teaming — комплексная имитация атак. Методология и инструменты</a>
</li>
<li><a href="https://www.youtube.com/channel/UCGfxztXUoBeGNVv6UTpUQHw/videos">cHack</a>
</li>
<li><a href="https://owasp.org/www-project-top-ten/">OWASP Top Ten</a>
</li>
<li><a href="https://santoku-linux.com/">Santoku Linux</a> 
</li>
<li><a href="https://www.kali.org/">Kali Linux</a>
</li>
<li><a href="https://github.com/FSecureLABS/drozer">https://github.com/FSecureLABS/drozer</a>
</li>
<li><a href="https://habr.com/ru/post/542190/">SQL-инъекции' union select null,null,null --</a>
</li>
<li><a href="https://www.software-testing.ru/library/testing/security/3398-ross-site-scripting">Что такое XSS-уязвимость и как тестировщику не пропустить ее</a>
</li>
</ul>
<h2>Что означает оценка уязвимости/защищенности? (Vulnerability Assessment)</h2>
Это процесс оценки рисков безопасности в программной системе с целью уменьшения вероятности угрозы. Уязвимость - это любые ошибки или слабости в процедурах безопасности системы, разработке, реализации или любом внутреннем контроле, которые могут привести к нарушению политики безопасности системы. Целью оценки уязвимости является снижение возможности несанкционированного доступа для злоумышленников (хакеров). Анализ проникновения зависит от двух механизмов, а именно от оценки уязвимости и тестирования на проникновение (VAPT - Vulnerability Assessment and Penetration testing).
Методы:
<ul>
<li>Активное тестирование 
</li>
<ul>
<li>Inactive testing, тестировщик вводит новые test data и анализирует результаты. 
</li>
<li>В процессе тестирования тестировщики создают интеллектуальную модель процесса, и она будет расти и дальше во время взаимодействия с тестируемым программным обеспечением. 
</li>
<li>Выполняя тест, тестировщик будет активно вовлекаться в процесс обнаружения новых Test case и новых идей. Вот почему это называется Active testing. 
</li>
</ul>
<li>Пассивное тестирование 
</li>
<ul>
<li>Пассивное тестирование - отслеживание результатов запуска тестируемого программного обеспечения без введения новых Test case или data. 
</li>
</ul>
<li>Тестирование сети 
</li>
<ul>
<li>Тестирование сети - это процесс измерения и записи текущего состояния работы сети за определенный период времени. 
</li>
<li>Тестирование в основном проводится для прогнозирования работы сети под нагрузкой или для выявления проблем, создаваемых новыми сервисами. 
</li>
<li>Нам нужно проверить следующие характеристики сети: 
</li>
<ul>
<li>Уровни утилизации 
</li>
<li>Количество пользователей 
</li>
<li>Использование приложения 
</li>
</ul>
</ul>
<li>Распределенное Тестирование 
</li>
<ul>
<li>Распределенные тесты применяются для тестирования распределенных приложений, то есть приложений, работающих с несколькими клиентами одновременно. По сути, тестирование распределенного приложения означает тестирование его клиентской и серверной частей по отдельности, но с помощью метода распределенного тестирования мы можем протестировать их все вместе. 
</li>
<li>Части теста будут взаимодействовать друг с другом во время теста. Это делает их синхронизированными соответствующим образом. Синхронизация является одним из наиболее важных моментов в распределенном тестировании.
</li>
</ul>
</ul>
<h2>Расскажите подробнее о тестировании на проникновение? (Penetration testing)</h2>
PENETRATION testing - это тип тестирования безопасности, который выявляет уязвимости, угрозы, риски в программном приложении, сети или веб-приложении, которые может использовать злоумышленник. Тестирование на проникновение показывает реальную картину существующей угрозы в системе безопасности и определяет уязвимости организации к ручным атакам. Проведение пентеста на регулярной основе позволит определить технические ресурсы, инфраструктуру, физические и кадровый арсенал содержащие в себе слабые аспекты, которые требуют развития и усовершенствования. Данный вид тестирования выполняется как вручную, так и автоматически и может быть как Black Box, так и Grey и White. Ввиду необходимости наличия специфических знаний и опыта для выполнения этого вида тестирования привлекается отдельный специалист – пентестер. Примеры кейсов тестирования на проникновение:
<ul>
<li>Тест на проникновение в сеть:
</li>
<ul>
<li>выявлении уязвимостей сетевого и системного уровня;
</li>
<li>определение неправильных конфигураций и настроек;
</li>
<li>выявление уязвимости беспроводной сети;
</li>
<li>мошеннические услуги;
</li>
<li>отсутствие <a href="http://withsecurity.ru/kak-pridumat-nadezhnyj-parol-i-zapomnit-ego">надежных паролей</a> и наличие слабых протоколов.
</li>
</ul>
<li><a href="http://withsecurity.ru/pentest-mobilnyh-prilozheniy-na-chto-obratit-vnimanie">Тест на проникновение приложений</a>:
</li>
<ul>
<li>выявление недостатков прикладного уровня;
</li>
<li>подделка запросов;
</li>
<li>применение злонамеренных скриптов;
</li>
<li>нарушение работы управления сеансами;
</li>
<li>и т.п.
</li>
</ul>
<li>Тест на физическое проникновение:
</li>
<ul>
<li>взлом физических барьеров;
</li>
<li>проверка и взлом замков;
</li>
<li>нарушения работы и обход датчиков;
</li>
<li>вывод из строя камер видеонаблюдения;
</li>
<li>и т. д. 
</li>
</ul>
</ul>

<h2>Отличия Vulnerability Assessment от Penetration testing?</h2>
Оба этих вида отличаются друг от друга по силе и задачам, которые они выполняют. Однако для составления исчерпывающего отчета по тестированию уязвимостей рекомендуется сочетание обеих процедур.

<table>
<tr>
<td> 
</td><td>Vulnerability Assessment
</td><td>Penetration testing
</td></tr>
<tr>
<td>Working
</td><td>Нахождений уязвимостей
</td><td>Выявление и использование уязвимостей
</td></tr>
<tr>
<td>Mechanism
</td><td>Обнаружение и сканирование
</td><td>Симуляция
</td></tr>
<tr>
<td>Focus
</td><td>Ширина
</td><td>Глубина
</td></tr>
<tr>
<td>Coverage of Completeness
</td><td>Высокое покрытие
</td><td>Низкое
</td></tr>
<tr>
<td>Cost
</td><td>Низкая стоимость
</td><td>Высокая
</td></tr>
<tr>
<td>Performed By
</td><td>Внутренний персонал
</td><td>Атакующий или пентестер
</td></tr>
<tr>
<td>How often to Run
</td><td>После каждой сборки
</td><td>Реже, зависит от политики безопасности компании и продукта
</td></tr>
<tr>
<td>Result
</td><td>Предоставит частичную информацию об уязвимостях
</td><td>Предоставит полную информацию об уязвимостях
</td></tr>
<tr>
<td>
</td><td>
</td><td>
</td></tr>
</table>
<h2>Что такое Fuzz тестирование?</h2>
FUZZ testing (fuzzing) – это метод тестирования ПО методом черного ящика, один из типов тестирования безопасности, который вводит недействительные или случайные данные, называемые FUZZ, в систему программного обеспечения для обнаружения ошибок кодирования и лазеек в безопасности. Данные вводятся с использованием автоматических или полуавтоматических методов тестирования, после чего система отслеживается на предмет различных исключений, таких как сбой системы или сбой встроенного кода и т. д.  
Обычно fuzzing обнаруживает наиболее серьезные ошибки или дефекты безопасности. Это очень экономически эффективный метод тестирования. Fuzzing - один из самых распространенных методов хакеров, используемых для обнаружения уязвимости системы (сюда относятся популярные SQL- или скриптовые инъекции). Примеры фаззеров:
<ul>
<li>Mutation-Based Fuzzers: изменяет существующие образцы данных для создания новых test data. Это очень простой и понятный подход, он начинается с действительных образцов и постоянно корректирует каждый байт или файл.
</li>
<li>Generation-Based Fuzzers: определяет новые данные на основе ввода модели. Он начинает генерировать ввод с нуля на основе спецификации.
</li>
<li>PROTOCOL-BASED-fuzzer: самый успешный фаззер - это детальное знание тестируемого формата протокола. Понимание зависит от спецификации. Это включает в себя запись массива спецификации в инструмент, а затем с помощью метода генерации тестов на основе модели проходится спецификация и добавляется неравномерность в содержимое данных, последовательность и т. д.  Это также известно как синтаксическое тестирование, грамматическое тестирование, тестирование надежности, и т. д.  Fuzzer может генерировать Test case из существующего или использовать допустимые или недействительные входные данные.
</li>
</ul>

Типы ошибок, обнаруживаемых Fuzz testing:
<ul>
<li>Сбои ассертов и утечки памяти (Assertion failures and memory leaks). Эта методология широко используется для больших приложений, где ошибки влияют на безопасность памяти, что является серьезной уязвимостью. 
</li>
<li>Некорректный ввод (Invalid input). Фаззеры используются для генерирования неверного ввода, который используется для тестирования процедур обработки ошибок, и это важно для программного обеспечения, которое не контролирует его ввод. Простой фаззинг может быть способом автоматизации отрицательного тестирования. 
</li>
<li>Исправление ошибок (Correctness bugs). Fuzzing также может использоваться для обнаружения некоторых типов ошибок «правильности». Например, поврежденная база данных, плохие результаты поиска и т. д. 
</li>
</ul>


Доп. материал:
<a href="https://habr.com/ru/company/tensor/blog/527304/">Фаззинг тестирование веб-интерфейса. Расшифровка доклада</a>
<h2>Можно ли отнести тестирование безопасности или нагрузочное тестирование к функциональным видам тестирования?</h2>
Данные виды во многих источниках относят к нефункциональным видам тестирования, но если это является основной функцией приложения, то можно отнести и к функциональным. 

Мнение:
"<..> Есть функциональное требование: 
"Пользователь должен иметь возможность перевести деньги со своей карты на другую карту по номеру". 
Это функциональное требование (ну, на самом деле это целая тонна требований, но обобщим их до одной user story). 
Оно отвечает на вопрос "какие операции должен уметь выполнять сервис". 
К этой функциональности может предъявляться еще куча требований - по безопасности, по скорости, по отказоустойчивости, и т.д.  Они описывают то, как система должна работать, а не что она должна уметь. 
Нефункциональные требования могут быть критичными, могут блокировать выпуск той или иной функциональности. Но это все еще свойство фичи, а не какая-то самостоятельная ее функция. 
В то же время, есть, например, функциональные требования безопасности, типа "автоматически блокировать транзакции обладающие характеристиками А, Б, В".  © @azshoo
Это снова нас возвращает к тому, что система должна обладать какими-то функциями."
<h2>Что вы знаете о конфигурационном тестировании? (Configuration testing)</h2>
Конфигурационное тестирование (Configuration testing) — специальный вид тестирования, направленный на проверку работы ПО при различных аппаратных и программных конфигурациях системы (заявленных платформах, поддерживаемых драйверах, при различных конфигурациях компьютеров и т. д. )
В зависимости от типа проекта конфигурационное тестирование может иметь разные цели:
<ul>
<li>Проект по профилированию работы системы
Цель Тестирования: определить оптимальную конфигурацию оборудования, обеспечивающую требуемые характеристики производительности и времени реакции тестируемой системы.
</li>
<li>Проект по миграции системы с одной платформы на другую
Цель Тестирования: Проверить объект тестирования на совместимость с объявленным в спецификации оборудованием, операционными системами и программными продуктами третьих фирм.
</li>
</ul>
Для клиент-серверных приложений конфигурационное тестирование можно условно разделить на два уровня (для некоторых типов приложений может быть актуален только один):
<ul>
<li>Серверный
</li>
<li>Клиентский
</li>
</ul>
На первом (серверном) уровне, тестируется взаимодействие выпускаемого ПО с окружением, в которое оно будет установлено:
<ul>
<li>Аппаратные средства (тип и количество процессоров, объем памяти, характеристики сети / сетевых адаптеров и т. д.)
</li>
<li>Программные средства (ОС, драйвера и библиотеки, стороннее ПО, влияющее на работу приложения и т. д.)
</li>
</ul>
Основной упор здесь делается на тестирование с целью определения оптимальной конфигурации оборудования, удовлетворяющего требуемым характеристикам качества (эффективность, портативность, удобство сопровождения, надежность).
На следующем (клиентском) уровне, ПО тестируется с позиции его конечного пользователя и конфигурации его рабочей станции. На этом этапе будут протестированы следующие характеристики: удобство использования, функциональность. Для этого необходимо будет провести ряд тестов с различными конфигурациями рабочих станций:
<ul>
<li>Тип, версия и битность операционной системы (подобный вид тестирования называется кроссплатформенное тестирование)
</li>
<li>Тип и версия Web браузера, в случае если тестируется Web приложение (подобный вид тестирования называется кросс-браузерное тестирование)
</li>
<li>Тип и модель видеоадаптера (при тестировании игр это очень важно)
</li>
<li>Работа приложения при различных разрешениях экрана
</li>
<li>Версии драйверов, библиотек и т. д.  (для JAVA приложений версия JAVA машины очень важна, тоже можно сказать и для .NET приложений касательно версии .NET библиотеки)
</li>
</ul>
и т. д. 
Перед началом проведения конфигурационного тестирования рекомендуется:
<ul>
<li>создавать матрицу покрытия (матрица покрытия - это таблица, в которую заносят все возможные конфигурации),
</li>
<li>проводить приоритезацию конфигураций (на практике, скорее всего, все желаемые конфигурации проверить не получится),
</li>
<li>шаг за шагом, в соответствии с расставленными приоритетами, проверять каждую конфигурацию.
</li>
</ul>
Уже на начальном этапе становится очевидно, что чем больше требований к работе приложения при различных конфигурациях рабочих станций, тем больше тестов нам необходимо будет провести. В связи с этим, рекомендуем, по возможности, автоматизировать этот процесс, так как именно при конфигурационном тестировании автоматизация реально помогает сэкономить время и ресурсы. Конечно же автоматизированное тестирование не является панацеей, но в данном случае оно окажется очень эффективным помощником.
В итоге: конфигурационным называется тестирование совместимости выпускаемого продукта (ПО) с различным аппаратным и программным средствами.
Основные цели - определение оптимальной конфигурации и проверка совместимости приложения с требуемым окружением (оборудованием, ОС и т. д.). Автоматизация конфигурационного тестирования позволяет избежать лишних расходов
Примечание: в ISTQB вообще не говорится о таком виде тестирования как конфигурационное. Согласно глоссарию, данный вид тестирования рассматривается там как тестирование портируемости:
configuration testing: See portability testing.
portability testing: The process of testing to determine the portability of a software product.
<h2>Что подразумевается под проверкой на дым / дымовым тестированием? (Smoke testing)</h2>
Смоук тестирование рассматривается как короткий цикл тестов, выполняемый для каждой новой сборки для подтверждения того, что ПО стартует и выполняет основные функции без критических и блокирующих дефектов. В случае отсутствия таковых дефектов дымовое тестирование объявляется пройденным, и команда QA может начинать дальнейшее тестирование полного цикла, в противном случае, сборка объявляется дефектной, что делает дальнейшее тестирование пустой тратой времени и ресурсов. Сборка возвращается на доработку и исправление.
Аналогами дымового тестирования являются Build Verification testing и Acceptance testing, выполняемые на функциональном уровне командой тестирования, по результатам которых делается вывод о том, принимается или нет установленная версия ПО в тестирование, эксплуатацию или на поставку заказчику.
Если мы говорим про сайт интернет-магазина, то сценарий будет примерно следующим:
<ul>
<li>Сайт открывается
</li>
<li>Можно выбрать случайный товар и добавить его в корзину
</li>
<li>Можно оформить и оплатить заказ
</li>
</ul>
Если мы говорим про мобильное приложение, например, messenger, то:
<ul>
<li>Приложение устанавливается и запускается
</li>
<li>Можно авторизоваться
</li>
<li>Можно написать сообщение случайном контакту
</li>
</ul>

Синонимом в некоторых источниках указан breath testing.
Небольшая шпаргалка по степени важности:
<ul>
<li>smoke - самое важное
</li>
<li>critical path -  повседневное
</li>
<li>extended - все
</li>
</ul>

В русском языке термин ошибочно переводят как проверка дыма, корректнее уж говорить "на дым". <a href="https://ru.wikipedia.org/wiki/Smoke_test">История термина:</a> Первое свое применение этот термин получил у печников, которые, собрав печь, закрывали все заглушки, затапливали ее и смотрели, чтобы дым шел только из положенных мест.
Повторное «рождение» термина произошло в радиоэлектронике. Первое включение нового радиоэлектронного устройства, пришедшего из производства, совершается на очень короткое время (меньше секунды). Затем инженер руками ощупывает все микросхемы на предмет перегрева. Сильно нагревшаяся за эту секунду микросхема может свидетельствовать о грубой ошибке в схеме. Если первое включение не выявило перегрева, то прибор включается снова на большее время. Проверка повторяется. И так далее несколько раз. Выражение «smoke-test» используется инженерами в шуточном смысле, так как появления дыма, а значит и порчи частей устройства, стараются избежать.

Доп. материал:
<a href="https://testing-companies.com/qa-outsourcing-smoke-testing-critical-path-testing-extended-testing/">QA Outsourcing: Smoke Testing, Critical Path Testing, Extended Testing</a>
<h2>Что такое тестирование встряхиванием? (Shake out testing)</h2>
Стандартного определения ISO для теста на встряхивание для ПО не существует. Говорят, что это синоним к Smoke тестированию.
<h2>Что подразумевается под санитарным тестированием? (Sanity testing)</h2>
Для начала стоит сказать, что санитарным оно в русскоязычной среде назвалось по совершенно непонятным причинам, но гуглится только так. На самом же деле корректно говорить тестирование на вменяемость или разумность.
Санитарное тестирование - это узконаправленное тестирование достаточное для доказательства того, что конкретная функция работает согласно заявленным в спецификации требованиям. Является подмножеством регрессионного тестирования. Используется для определения работоспособности определенной части приложения после изменений, произведенных в ней или окружающей среде. Обычно выполняется вручную.

Доп. материалы:
<a href="https://www.merriam-webster.com/dictionary/sanity">Definition of sanity</a>
<a href="http://tryqa.com/what-is-sanity-testing/">What is Sanity testing? Advantages, disadvantages & differences</a>
<h2>Отличие санитарного тестирования от дымового? (Sanity vs Smoke testing)</h2>
Эти виды тестирования имеют "вектора движения", направления в разные стороны. В отличии от дымового (Smoke testing), санитарное тестирование (Sanity testing) направлено вглубь проверяемой функции, в то время как дымовое направлено вширь, для покрытия тестами как можно большего функционала в кратчайшие сроки.

Доп. материал:
<a href="https://habr.com/ru/post/358142/">В чем разница Smoke, Sanity, Regression, Re-test и как их различать?</a>
<h2>Что вы знаете про регрессионное тестирование? (Regression testing)</h2>
При корректировках программы необходимо гарантировать сохранение качества. Для этого используется регрессионное тестирование - дорогостоящая, но необходимая деятельность в рамках этапа сопровождения, направленная на перепроверку корректности измененной программы. В соответствии со стандартным определением, регрессионное тестирование - это выборочное тестирование, позволяющее убедиться, что изменения не вызвали нежелательных побочных эффектов, или что измененная система по-прежнему соответствует требованиям.
Главной задачей этапа сопровождения является реализация систематического процесса обработки изменений в коде. После каждой модификации программы необходимо удостовериться, что на функциональность программы не оказал влияния модифицированный код. Если такое влияние обнаружено, говорят о регрессионном дефекте. Для регрессионного тестирования функциональных возможностей, изменение которых не планировалось, используются ранее разработанные тесты. Одна из целей регрессионного тестирования состоит в том, чтобы, в соответствии с используемым критерием покрытия кода (например, критерием покрытия потока операторов или потока данных), гарантировать тот же уровень покрытия, что и при полном повторном тестировании программы. Для этого необходимо запускать тесты, относящиеся к измененным областям кода или функциональным возможностям.
Другая цель регрессионного тестирования состоит в том, чтобы удостовериться, что программа функционирует в соответствии со своей спецификацией, и что изменения не привели к внесению новых ошибок в ранее протестированный код. Эта цель всегда может быть достигнута повторным выполнением всех тестов регрессионного набора, но более перспективно отсеивать тесты, на которых выходные данные модифицированной и старой программы не могут различаться. Важной задачей регрессионного тестирования является также уменьшение стоимости и сокращение времени выполнения тестов.
Можно заключить, что регрессионное тестирование выполняется чтобы минимизировать регрессионные риски. То есть, риски того, что при очередном изменении продукт перестанет выполнять свои функции. С регрессионным тестированием плотно связана другая активность - импакт анализ (или иначе, анализ влияния изменений). Обычно под импакт анализом имеют в виду одно из следующих:
<ol>
<li>Попытку оценить регрессионные риски еще на этапе планирования изменений (этим определением, по моему опыту, чаще пользуются менеджеры и разработчики);
</li>
<li>Попытку определить объем регрессионного тестирования с учетом изменений, которые уже произошли (это определение чаще используют сами тестировщики). У Пола Джеррарда есть серия статей, где более детально раскрывается понятие импакт анализа, причем не только с позиции тестировщика.
Очевидно, что от эффективности импакт анализа зависит эффективность регрессионного тестирования. Но не всегда тщательно проведенный импакт анализ позволяет сократить затраты на последующее тестирование.
</li>
</ol>
Обоснование корректности метода отбора тестов. Перечислим некоторые особенности реализации регрессионного тестирования:
<ul>
<li>Некоторые участки кода программы не получают управление при выполнении некоторых тестов.
</li>
<li>Если участок кода реализует требование, но измененный фрагмент кода не получает управления при выполнении теста, то он и не может воздействовать на значения выходных данных программы при выполнении данного теста.
</li>
<li>Даже если участок кода, реализующий требование, получает управление при выполнении теста, это далеко не всегда отражается на выходных данных программы при выполнении данного теста. Действительно, если изменяется первый блок программы, например, путем добавления инициализации переменной, все пути в программе также изменяются, и, как следствие, требуют повторного тестирования. Однако может так случиться, что только на небольшом подмножестве путей действительно используется эта инициализированная переменная.
</li>
<li>Не каждый тест, проверяющий код, находящийся на одном пути с измененным кодом, обязательно покрывает этот измененный код.
</li>
<li>Код, находящийся на одном пути с измененным кодом, может не воздействовать на значения выходных данных измененных модулей программы.
</li>
<li>Не всегда каждый оператор программы воздействует на каждый элемент ее выходных данных.
</li>
</ul>
Предположим, что изменения в программе ограничиваются одним оператором. Если при выполнении какого-либо теста на исходной программе этот оператор никогда не получает управление, можно с уверенностью сказать, что он не получит управление и в ходе выполнения теста на новой программе, а результаты тестирования новой и старой программ будут совпадать. Следовательно, нет необходимости выполнять этот тест на новой программе. Указанный метод легко можно обобщить для случая нескольких изменений: если тест не задействует ни одного измененного оператора, и его входные данные не изменились, код, выполняемый им в измененной программе, будет в точности таким же, как в первоначальной версии. Такой тест не выявляет различий между двумя версиями системы; следовательно, нет необходимости прогонять его повторно. Если тест не затрагивает ни одного оператора вывода, поведение которого зависит от измененных операторов, это означает, что, несмотря на изменения в программе, все операторы, которые получают управление при выполнении этого теста, не изменят вывод системы по отношению к предыдущей версии. Таким образом, нет необходимости повторно прогонять и тесты такого рода.
Следовательно, необходимо ориентироваться на выбор только тех тестов, которые покрывают измененный код, воздействующий, в свою очередь, на вывод программы. Такой подход гарантирует, что будут выбраны только тесты, обнаруживающие изменения, и метод будет, как говорят, точным.
Классификация тестов при отборе.
Создание наборов регрессионных тестов рекомендуется начинать с множества исходных тестов. При заданном критерии регрессионного тестирования все исходные тесты подразделяются на четыре подмножества:
<ul>
<li>Множество тестов, пригодных для повторного использования. Это тесты, которые уже запускались и пригодны к использованию, но затрагивают только покрываемые элементы программы, не претерпевшие изменений. При повторном выполнении выходные данные таких тестов совпадут с выходными данными, полученными на исходной программе. Следовательно, такие тесты не требуют перезапуска.
</li>
<li>Множество тестов, требующих повторного запуска. К ним относятся тесты, которые уже запускались, но требуют перезапуска, поскольку затрагивают, по крайней мере, один измененный покрываемый элемент, подлежащий повторному тестированию. При повторном выполнении такие тесты могут давать результат, отличный от результата, показанного на исходной программе. Множество тестов, требующих повторного запуска, обеспечивает хорошее покрытие структурных элементов даже при наличии новых функциональных возможностей.
</li>
<li>Множество устаревших тестов. Это тесты, более не применимые к измененной программе и непригодные для дальнейшего тестирования, поскольку они затрагивают только покрываемые элементы, которые были удалены при изменении программы. Их можно удалить из набора регрессионных тестов.
</li>
<li>Новые тесты, которые еще не запускались и могут быть использованы для тестирования.
</li>
</ul>
Сразу после создания тест вводится в структуру базы данных как новый. После исполнения новый тест переходит в категорию тестов, пригодных для повторного использования либо устаревших. Если выполнение теста способствовало увеличению текущей степени покрытия кода, тест помечается как пригодный для повторного использования. В противном случае он помечается как устаревший и отбрасывается. Существующие тесты, повторно запущенные после внесения изменения в код, также классифицируются заново как пригодные для повторного использования или устаревшие в зависимости от тестовых траекторий и используемого критерия тестирования.
<img src="https://lh6.googleusercontent.com/nqirFfSu2IyEeva_AnCfbr2UeS0JlOarIep7zkQJB2U2jtFiill8K5miqrYj1IJy9IfN5KmkDwQ5yD7X92-8KyWQc_fZelMfjA8rGAY7VJ9JP4osmPLogehSOq79k5KVwJISwut0">
Классификация тестов по отношению к изменениям в коде требует анализа последствий изменений. Тесты, активирующие код, затронутый изменениями, могут требовать повторного запуска или оказаться устаревшими. Чтобы тест был включен в класс тестов, требующих повторного запуска, он должен быть затронут изменениями в коде, а также должен способствовать увеличению степени покрытия измененного кода по используемому критерию. Затронутым элементом теста может быть траектория, выходные значения, или и то, и другое. Чтобы тест был включен в класс тестов, пригодных для повторного использования, он должен вносить вклад в увеличение степени покрытия кода и не требовать повторного запуска.
Степень покрытия кода определяется для тестов, пригодных для повторного использования, поскольку к этому классу относятся тесты, не требующие повторного запуска и способствующие увеличению степени покрытия до желаемой величины. Если имеется компонент программы, не задействованный пригодными для повторного использования тестами, то вместо них выбираются и выполняются с целью увеличения степени покрытия тесты, требующие повторного запуска. После запуска такой тест становится пригодным для повторного использования или устаревшим. Если тестов, требующих повторного запуска, больше не осталось, а необходимая степень покрытия кода еще не достигнута, порождаются дополнительные тесты и тестирование повторяется.
Окончательный набор тестов собирается из тестов, пригодных для повторного использования, тестов, требующих повторного запуска, и новых тестов. Наконец, устаревшие и избыточные тесты удаляются из набора тестов, поскольку избыточные тесты не проверяют новые функциональные возможности и не увеличивают покрытие.

Дополнительный материал.
<ul>
<li><a href="https://www.intuit.ru/studies/courses/48/48/lecture/1446?page=1">Регрессионное тестирование: разновидности метода отбора тестов</a>
</li>
<li><a href="https://www.intuit.ru/studies/courses/48/48/lecture/1448">Регрессионное тестирование: методики, не связанные с отбором тестов и методики порождения тестов</a>
</li>
<li><a href="https://www.intuit.ru/studies/courses/48/48/lecture/1450">Регрессионное тестирование: алгоритм и программная система поддержки</a>
</li>
</ul>
<h2>Типы регрессии по Канеру?</h2>
Сэм Канер описал 3 основных типа регрессионного тестирования:
<ul>
<li>Регрессия багов (Bug regression) — попытка доказать, что исправленная ошибка на самом деле не исправлена
</li>
<li>Регрессия старых багов (Old bugs regression) — попытка доказать, что недавнее изменение кода или данных сломало исправление старых ошибок, т.е. старые баги стали снова воспроизводиться.
</li>
<li>Регрессия побочного эффекта (Side effect regression) — попытка доказать, что недавнее изменение кода или данных сломало другие части разрабатываемого приложения
</li>
</ul>

<h2>Объясните, что такое тестирование N+1?</h2>
Вариант регрессионного тестирования представлен как N+1. В этом методе тестирование выполняется в несколько циклов, в которых ошибки, обнаруженные в тестовом цикле «N», устраняются и повторно тестируются в тестовом цикле N + 1. Цикл повторяется, пока не будет найдено ни одной ошибки.
<h2>Что означает подтверждающее тестирование? (confirmation/re-testing)</h2>
Повторное тестирование - это тип тестирования, выполняемый для проверки того, что конкретный дефект устранен после исправления кода.
<h2>В чем разница между повторным и регрессионным тестированием?</h2>
<ul>
<li>Регрессионное тестирование проводится для подтверждения того, что недавнее изменение программы или кода не оказало неблагоприятного воздействия на существующие функции. Повторное тестирование проводится для подтверждения того, что тест-кейсы, которые не прошли, проходят после устранения дефектов. 
</li>
<li>Цель регрессионного тестирования подтвердить, что новые изменения кода не должны иметь побочных эффектов для существующих функций. Повторное тестирование проводится на основе исправлений дефектов. 
</li>
<li>Проверка дефектов не является частью регрессионного тестирования. Проверка дефекта является частью повторного тестирования 
</li>
<li>В зависимости от проекта и наличия ресурсов, регрессионное тестирование может проводиться параллельно с повторным тестированием. Приоритет повторного тестирования выше, чем регрессионное тестирование, поэтому оно проводится перед регрессионным тестированием. 
</li>
<li>Вы можете сделать автоматизацию для регрессионного тестирования, ручное тестирование может быть дорогим и трудоемким. 
</li>
<li>Регрессионное тестирование называется общим (generic) тестированием. Повторное тестирование - это плановое (planned) тестирование.
</li>
<li>Регрессионное тестирование проводится для пройденных Test case. Повторное тестирование проводится только для неудачных тестов. 
</li>
<li>Регрессионное тестирование проверяет наличие неожиданных побочных эффектов. Повторное тестирование гарантирует, что первоначальная ошибка была исправлена.
</li>
<li>Регрессионное тестирование проводится только тогда, когда есть какие-либо изменения или изменения становятся обязательными в существующем проекте. Повторное тестирование выполняет дефект с теми же данными и той же средой с разными входными данными с новой сборкой (build). 
</li>
<li>Test case для регрессионного тестирования могут быть получены из функциональной спецификации, user tutorials and manuals, а также defect reports в отношении исправленных проблем. Test case для повторного тестирования не могут быть получены до начала тестирования.
</li>
</ul>

<h2>Что вы знаете о тестировании сборки? (Build Verification Test)</h2>
Тестирование, направленное на определение соответствия, выпущенной версии, критериям качества для начала тестирования. По своим целям является аналогом Дымового Тестирования, направленного на приемку новой версии в дальнейшее тестирование или эксплуатацию. Вглубь оно может проникать дальше, в зависимости от требований к качеству выпущенной версии.
<h2>Что такое тестирование потоков? (Thread testing) </h2>
Тестирование потоков определяется как тип тестирования программного обеспечения, который проверяет основные функциональные возможности конкретной задачи (потока). Обычно проводится на ранней стадии фазы интеграционного тестирования. Тестирование на основе потоков является одной из дополнительных стратегий, принятых в ходе тестирования системной интеграции. Поэтому его, вероятно, следует более правильно назвать «тестом взаимодействия потоков» (thread interaction test).
Тестирование на основе потоков подразделяется на две категории:
<ul>
<li>Однопоточное тестирование включает одну транзакцию приложения за раз 
</li>
<li>Многопоточное тестирование включает одновременно несколько активных транзакций
</li>
</ul>
Как производить:
<ul>
<li>Тестирование на основе потоков является обобщенной формой тестирования на основе сеансов (session-based testing), в котором сеансы являются формой потока, но поток не обязательно является сеансом. 
</li>
<li>Для тестирования потока, поток или программа (небольшая функциональность) интегрируются и тестируются постепенно как подсистема, а затем выполняются для всей системы. 
</li>
<li>На самом низком уровне оно предоставляет интеграторам лучшее представление о том, что тестировать. 
</li>
<li>Вместо непосредственного тестирования программных компонентов требуется, чтобы интеграторы сосредоточились на тестировании логических путей выполнения в контексте всей системы.
</li>
</ul>
<h2>Что такое тестирование документации? (Documentation testing)</h2>
Плохая документация может повлиять на качество продукта. Хорошая документация по продукту играет решающую роль в конечном продукте. Тестирование артефактов, разработанных до, во время и после тестирования продукта, называется тестированием документации. Это нефункциональный тип тестирования программного обеспечения. Мы знаем, что дефекты, обнаруженные на этапе тестирования, более дорогостоящие, чем если бы они были обнаружены на этапе требований. Стоимость исправления ошибки увеличивается тем больше, чем позже вы найдете ее. Таким образом, тестирование документации может начаться с самого начала процесса разработки программного обеспечения, чтобы сэкономить большую сумму денег. Некоторые часто проверяемые артефакты:
<ul>
<li>Requirement documents
</li>
<li>Test Plan
</li>
<li>Test case
</li>
<li>Traceability Matrix (RTM)
</li>
</ul>
<h2>Какие вы знаете уровни тестирования данных?</h2>
Тесты группируются в зависимости от того, где они добавлены в SDLC, или от уровня детализации, который они содержат. В целом, существует четыре уровня или слоя тестирования: модульное тестирование, интеграционное тестирование, системное тестирование и приемочное тестирование. Целью уровней тестирования является систематизация тестирования программного обеспечения и простота выявления всех возможных Test case на определенном уровне. 
Здесь работает хорошая аналогия с пирамидой тестирования. Это распределение по количеству тестов на разных уровнях приложения.
<ul>
<li>Unit-слой — это когда тестируется один модуль программы, чаще всего это одна функция или метод. Таких тестов должно быть больше всего. Unit-тест для данных — это когда мы определяем требования для каждой ячейки. Нет смысла тестировать дальше, если у нас есть ошибки на уровне ячеек. Если, например, в фамилии содержатся цифры, то какой смысл проверять что-то дальше? Возможно, там должны быть буквы, похожие на эти цифры. И тогда нам нужно все исправлять и проверять следующий уровень, чтобы у нас все было в единственном числе и не было дубликатов, если так сказано в требованиях.
</li>
<li>Integration-слой — это когда несколько кусков программы тестируются вместе. Слой API для данных — это когда мы говорим о всей таблице. Допустим, у нас могут быть дубликаты, но не больше ста штук. Если у нас город-миллионник, то на одной улице не может жить миллион человек. Поэтому если мы сделаем выборку по улице, то количество адресов должно быть десять тысяч или тысяча — это надо определить. А если у нас миллион, то с данными что-то не так.
</li>
<li>System-слой — это когда вся программа тестируется полностью. В случае с данными этот слой означает, что тестируется вся система. Здесь включается статистика. Например, мы говорим, что у нас не может быть больше 30% мужчин, рожденных после 1985 года. Или мы говорим, что 80% данных должны быть одного типа.
</li>
<li>Приемочное тестирование - это тест, проводимый для определения того, удовлетворяются ли требования спецификации или контракта в соответствии с его поставкой. Приемочное тестирование в основном выполняется пользователем или заказчиком. Тем не менее, другие акционеры могут быть вовлечены в этот процесс.
</li>
</ul>
<h2>Что такое подкожный тест? (Subcutaneous test)</h2>
Тест, который выполняется не для конечного пользовательского интерфейса, а для интерфейса, расположенного чуть ниже поверхности (пример - API).


Доп. материал:
<a href="https://martinfowler.com/bliki/SubcutaneousTest.html">Subcutaneous Test</a>
<h2>Расскажите о локализации, глобализации и интернационализации? (Localization/ globalization/internationalization testing)</h2>
Глобализированное ПО - это ПО, функционирующее одинаково независимо от географической, культурной и национальной среды. Тестирование глобализации концентрируется на выявлении потенциальных проблем в дизайне продукта, которые могут испортить глобализацию. Например, разработчик должен заложить в CSS основу для вертикального текста, если в будущем планируется локализовать продукт на язык с вертикальным письмом или обработку почтовых индексов для разных стран (где-то цифры, где-то цифры с буквами и т.п.). Оно гарантирует, что код может обрабатывать желаемую международную поддержку без нарушения какой-либо функциональности. А также, что не будет никакой потери данных и проблем с отображением. 

Тестирование глобализации, в свою очередь, можно разделить на два подвида:
<ul>
<li>Тестирование интернационализации (118N);
</li>
<li>Тестирование локализации (L10N);
</li>
</ul>

(Цифра означает количество пропущенных букв, типа как k8s - kubernetes)

Интернализация ПО – это особый процесс, при котором веб-софт создается таким образом, чтобы оно было равноудаленным от какой-либо культуры и (или) специфики определенного географического региона.
Например, одна из задач по интернационализации ПО– корректное редактирование логики всех подключенных параметров форматирования (формат даты, времени, цифровое и валютное форматирование).
Также, тестировщики во время проверки на соответствие ПО требованиям 118N тестируют работу продукта на равномерность работы в разных регионах и культурах мира.
Основной задачей тестирования интернациональности является проверка того, может ли программный код работать со всей международной поддержкой без нарушения функциональности, что может привести к потере данных или проблемам целостности информации.
В основном, фокус тестирования интернациональности направлен на:
<ul>
<li>Тестирование языковой совместимости. Проводятся проверки того, может ли веб-продукт корректно работать в определенной языковой среде;
</li>
<li>Проверка функциональности: полное выполнение регрессионных тестов в разнообразных языковых средах (корректное отображение специфической информации – даты, времени и валюты);
</li>
<li>Тестирование на корректность отображения графического интерфейса;
</li>
<li>Проверка удобства пользования: тестирование простоты использования ПО на различных операционных системах, разнообразных устройствах и прочее.
</li>
</ul>

Локализация ПО – деятельность по модификации ПО в соответствии с определенными региональными настройками (языком, географической территорией, кодировкой и прочим), которая должна бесперебойно работать.
В данный вид проверки входит необходимость выполнения работ по переводу всего контента программного обеспечения для конечного пользователя. Во время перевода должны учитываться иконки, информационная графика, справочные материалы, техническая документация и иные культурные особенности регионов, где в будущем будет доступно это программное обеспечение.

На что обратить внимание:
<ul>
<li>Длина переведенных слов
</li>
<li>Параметры шрифта пользовательского интерфейса
</li>
<li>Ввод текста в разных локализациях
</li>
<li>RTL-языки (справа-налево) или вертикальных
</li>
<li>Перевод сокращений или аббревиатур
</li>
<li>Мета-теги (проблемы с SEO или отображением имени вкладки (title, description, keywords))
</li>
<li>Соответствие мер исчисления, валюты, postal code и т.п.
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/alconost/blog/521330/">Локализационное тестирование: зачем оно нужно приложению или сайту?</a>
</li>
<li><a href="https://habr.com/ru/company/otus/blog/523112/">Почему интернационализация и локализация имеют значение</a>
</li>
<li><a href="https://habr.com/ru/post/532836/">Гайд по тестированию локализации и интернационализации, а также большой и полезный checklist</a>
</li>
<li><a href="https://lokalise.com/">Accelerate localization from code to delivery</a>
</li>
</ul>
<h2>Что такое исследовательское тестирование? (Exploratory testing)</h2>
Исследовательское Тестирование — одновременно является и техникой, и видом тестирования. Такое тестирование подразумевает под собой одновременно изучение проекта, функционала, проектирование тест кейсов в уме и тут же их исполнение, не записывая и не создавая тестовую документацию.
Такой вид тестирования обычно не предусматривается в тест плане и тест кейсы выполняются и модифицируются динамически. Эффективность такого тестирования напрямую зависит от опыта тестировщика ранее имевшим дело с этим приложением, платформой, знанием мест скопления возможных багов и рисками которые относятся к конкретному продукту.
Цель данного тестирования — это углубление в познании продукта, приложения и нахождения «на лету» возможных багов. Также такое тестирование помогает в дальнейшем проектировании тест кейсов для покрытия функционала данного приложения. Исследовательское тестирование широко используется в Agile-моделях.
 <img src="https://lh4.googleusercontent.com/YPaEupYJfq4gLD7JmQK6QxjN1efOTzdbyjHMi5sKMNKQPrM_ViRnvydi1uYQjpTb4_rEHrOuq-98Y8juAwGsSq3Wz0q0A6xwqOliBYWgodNQdtPcG0_9NMEeRJ4S_WYHDRj1Acr-">
Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/535094/">Исследовательское тестирование: пустая трата времени или мощный инструмент?</a>
</li>
<li><a href="https://www.satisfice.com/rapid-testing-methodology">Rapid Software Testing Methodology</a>
</li>
<li><a href="https://www.satisfice.com/exploratory-testing">Exploratory Testing</a>
</li>
<li><a href="http://www.testingeducation.org/BBST/exploratory/">Exploratory Testing</a>
</li>
<li><a href="http://www.testingeducation.org/BBST/exploratory/BBSTExploring.pdf">Exploratory Testing</a>
</li>
<li><a href="https://silo.tips/download/exploratory-testing-dynamics">Exploratory Testing Dynamics</a>
</li>
<li><a href="https://www.kaner.com/pdfs/QAIExploring.pdf">A Tutorial in Exploratory Testing</a>
</li>
<li><a href="https://medium.com/@cristina.mtys/tips-for-your-next-exploratory-testing-session-22b4421b9620">Plan your next exploratory testing session</a>
</li>
</ul>
<h2>Что вы знаете о турах Виттакера в исследовательском тестировании?</h2>
Чтобы систематизировать исследовательское тестирование можно использовать идею туров. Туры – это идеи и инструкции по исследованию программного продукта, объединенные определенной общей темой или целью. Туры, как правило, ограничены по времени – длительность тестовой сессии не должна превышать 4 часа. Идею туров развивали в своих работах Канер, Бах, Хендриксон, Болтон, Кохл и другие. Джеймс Виттакер (James A. Whittaker), хоть и не придумал саму идею туров, но предложил свой подход к исследовательскому тестированию с использованием туров и в своей книге "Exploratory Software Testing" в доступной форме озвучил идею туров и описал сами туры.
Тур – это своего рода план тестирования, он отражает основные цели и задачи, на которых будет сконцентрировано внимание тестировщика во время сессии исследовательского тестирования. При этом Виттакер использует метафору, что тестировщик – это турист, а тестируемое приложение – это город. Обычно у туриста (тестировщика) мало времени, поэтому он выполняет конкретную задачу в рамках выбранного тура, ни на что другое не отвлекаясь. Город (ПО) разбит на районы: деловой центр, исторический район, район развлечений, туристический район, район отелей, неблагополучный район.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/328990/">Туры в исследовательском тестировании. Личный перевод из книги Д. Виттакера «Исследовательское тестирование ПО»</a>
</li>
<li><a href="https://www.software-testing.ru/library/testing/testing-for-beginners/2965-exploratory-software-testing">Переводы туров для исследовательского тестирования</a>
</li>
<li><a href="https://www.software-testing.by/blog/exploratory-testing-exploratory-tours/">Исследовательское тестирование и исследовательские туры Виттакера</a>
</li>
</ul>
<h2>Что такое Свободное или Интуитивное тестирование? (Adhoc) </h2>
Часто его путают с другим видом тестирования «Exploratory testing» – «Исследовательское тестирование».
Свободное тестирование (ad-hoc testing) – это вид тестирования, который выполняется без подготовки к тестированию продукта, без определения ожидаемых результатов, проектирования тестовых сценариев. Это неформальное, импровизационное тестирование. Оно не требует никакой документации, планирования, процессов, которых следует придерживаться при выполнении тестирования. Такой способ тестирования в большинстве случаев дает большее количество заведенных отчетов об ошибке.  Это обусловлено тем, что тестировщик на первых шагах приступает к тестированию основной функциональной части продукта и выполняет как позитивные, так и негативные варианты возможных сценариев.
Чаще всего такое тестирование выполняется, когда владелец продукта не обладает конкретными целями, проектной документацией и ранее поставленными задачами. При этом тестировщик полагается на свое общее представление о продукте, сравнение с похожими продуктами, собственный опыт. Однако при тестировании ad-hoc имеет смысл владеть общей информацией о продукте, особенно если проект очень сложный и большой. Поэтому нужно хорошее представление о целях проекта, его назначении и основных функциях, и возможностях. А дальше уже можно приступать к ad-hoc тестированию.
Виды свободного тестирования (ad-hoc testing):
<ul>
<li>Buddy testing – процесс, когда 2 человека, как правило разработчик и тестировщик, работают параллельно и находят дефекты в одном и том же модуле тестируемого продукта. Такой вид тестирования помогает тестировщику выполнять необходимые проверки, а разработчику исправлять множество дефектов на ранних этапах.
</li>
<li>Pair testing – процесс, когда 2 тестировщика проверяют один модуль и помогают друг другу. К примеру, один может искать дефекты, а второй их документировать. Таким образом, у одного тестировщика будет функция, скажем так, обнаружителя, у другого – описателя.
</li>
<li>Monkey testing – произвольное тестирование продукта с целью как можно быстрее, используя различные вариации входных данных, нарушить работу программы или вызвать ее остановку (простыми словами – сломать).
</li>
</ul>

Различия между Buddy testing и Pair testing:
<ul>
<li>Buddy testing (Совместное тестирование) – это сочетание модульного тестирования и системного тестирования между разработчиком и тестировщиком.
</li>
<li>Pair testing (Парное тестирование) – выполняется только тестировщиками с разным уровнем знаний и опыта (такое сочетание поможет поделиться взглядами и идеями).
</li>
</ul>

Основные преимущества ad-hoc testing:
<ul>
<li>нет необходимости тратить время на подготовку документации;
</li>
<li>самые важные дефекты зачастую обнаруживаются на ранних этапах;
</li>
<li>часто применяется, когда берут нового сотрудника. С помощью этого метода, человек усваивает за 3 дня то, что, разбираясь тестовыми случаями, разбирал бы неделю – это называется форсированное обучение новых сотрудников;
</li>
<li>возможность найти трудновоспроизводимые и трудноуловимые дефекты, которые невозможно было бы найти, используя стандартные сценарии проверок.
</li>
</ul>

Если нам нужно провести ad-hoc тестирование интернет-магазина, то этот краткий список может помочь с тем, что нужно проверить:
<ul>
<li>все возможности сайта доступны без регистрации;
</li>
<li>корректность отображения анимаций и картинок;
</li>
<li>все возможности сайта доступны после регистрации;
</li>
<li>процесс регистрации;
</li>
<li>процесс добавления/удаления из корзины;
</li>
<li>процесс оплаты покупок;
</li>
<li>удобство в пользовании для новичков, простота, подсказки, помощь.
</li>
</ul>
<h2>Что вы знаете о мутационном тестировании? (Mutation testing)</h2>
Mutation testing - это тип тестирования программного обеспечения, в котором мы мутируем (меняем) определенные выражения в исходном коде и проверяем, способны ли Test case найти ошибки. Это тип тестирования белого ящика, который в основном используется для модульного тестирования. Изменения в мутантной программе сохраняются крайне небольшими, поэтому это не влияет на общую цель программы. Цель Mutation testing - оценить качество Test case, которые должны быть достаточно надежными, чтобы не выполнять мутантный код. Этот метод также называется стратегией тестирования на основе ошибок, так как он включает в себя создание ошибки в программе. 
<ul>
<li>Шаг 1: Ошибки вводятся в исходный код программы путем создания множества версий, называемых мутантами. Каждый мутант должен содержать одну ошибку, и цель состоит в том, чтобы заставить версию мутанта потерпеть неудачу, что демонстрирует эффективность Test case. 
</li>
<li>Шаг 2: Test case применяются к исходной программе, а также к программе мутанта. 
</li>
<li>Шаг 3: Сравните результаты оригинальной и мутантной программы. 
</li>
<li>Шаг 4: Если исходная программа и программы-мутанты генерируют разные выходные данные, то этот мутант уничтожается by the Test case. Следовательно, Test case достаточно хорош, чтобы обнаружить изменение между оригинальной и мутантной программой. 
</li>
<li>Шаг 5: Если исходная программа и программа-мутант генерируют одинаковые выходные данные, мутант остается в живых. В таких случаях необходимо создать более эффективные Test case, которые убивают всех мутантов.
</li>
</ul>
Что изменить в программе мутантов? Есть несколько методов, которые могут быть использованы для создания мутантных программ: 
<ul>
<li>Операторы замены операндов (Operand replacement operators) – например, в условии if (x> y) поменять местами значения x и y
</li>
<li>Операторы модификации выражений (Expression Modification Operators) – например, в условии if (х == у) Мы можем заменить == на >=
</li>
<li>Операторы модификации операторов (Statement modification Operators) – например, удалить часть else в конструкции if-else или удалить целиком конструкцию if-else, чтобы проверить, как ведет себя программа
</li>
</ul>
Оценка мутации = (убитые мутанты / общее количество мутантов) * 100

Автоматизированные инструменты для разных ЯП: mutmut, Humbug и Infection и т.п. 

Доп. материал:
<a href="https://habr.com/ru/post/334394/">Мутационное тестирование</a>
<h2>Что означает механизм тестирования по ключевым словам? (Keyword Driven testing Framework)</h2>
Это скриптовая техника, которая использует файлы данных, которые содержат ключевые слова, связанные с тестируемым ПО. Эти ключевые слова описывают набор действий, необходимых для выполнения определенного шага. Тест на основе ключевых слов состоит из ключевых слов высокого и низкого уровня, включая аргументы ключевых слов, которые составлены для описания действия Test case. Это также называется тестированием на основе таблиц (table-driven testing) или тестированием на основе action word (action word based testing). В тестировании по ключевым словам вы сначала идентифицируете набор ключевых слов, а затем связываете действие (или функцию), связанную с этими ключевыми словами. Здесь каждое действие тестирования, такое как открытие или закрытие браузера, щелчок мыши, нажатия клавиш и т. д., описывается ключевым словом, таким как openbrowser, click, Typtext и т. д.  Тестирование на основе ключевых слов обычно выполняется с помощью автоматического тестирования. 
<h2>Что вы знаете о тестировании интерфейса прикладного программирования (API - Application Programming Interface)? </h2>
Каждый день используя любимые мобильные приложения и веб-ресурсы вы незаметно взаимодействуете с API, скрытым под интерфейсом пользователя.
API действует как интерфейс между двумя программными приложениями и позволяет им связываться друг с другом на оговоренных правилах и не залезая в реализацию предоставляемых функций. Простой пример: вы можете встроить на свою главную страницу сайта маленький виджет прогноза погоды, который будет отправлять определенный правилами запрос к API некоего сервиса погоды и получать определенный правилами ответ, содержащий посылку с данными.
Еще более простой пример: примите официанта в качестве API ресторана. В ресторане вы даете заказ на основе блюд, определенных в меню. Официант принимает ваш заказ и на этом ваше участие заканчивается и вам не интересно, что там произойдет дальше. От официанта вы ожидаете только итог – вам приносят заказанное блюдо. 
Можете попробовать взаимодействие с API сами: отправляете GET запрос на <a href="https://reqres.in/api/users">https://reqres.in/api/users</a>, и получаете в ответ список пользователей. Это очень удобно, когда вы хотите предоставить интерфейс взаимодействия со своим сервисом сторонним лицам. Например, у google, instagram, vk и, в общем-то, всех популярных продуктов есть открытая часть API. То есть у вас есть документ с перечнем того, что и как можно спросить и что вам на это придет в ответ. Взаимодействовать с API можно и с веб-страницы, и с помощью специальных инструментов и напрямую из кода. Помимо этого, API еще чаще используется для внутренних нужд как архитектурное решение для связи между сервисами или вообще представлять собой не веб-взаимодействие, а решение внутри кода одного продукта (таким образом, гипотетически API может быть и у десктопного приложения и практически где угодно).
Тестирование API - это тип тестирования который включает в себя тестирование API напрямую, а также в рамках интеграционного тестирования, чтобы проверить, соответствует ли API ожиданиям с точки зрения функциональности, надежности, производительности и безопасности приложения. В тестировании API наш основной упор будет сделан на уровне бизнес-логики архитектуры программного обеспечения. 

<img src="https://lh6.googleusercontent.com/l1nV69iecqE78_9FkGox0wJnnRWBa5EYtH-brZxsAF-BYCzTucY09YCocUZnDTYCse-XcAIajcpS0oHanhJCKAIAy2n2MBMNTKNMFcjFjXoP6TPA2PIdS0-fbhu1EhNdZwkcQmp9">
Мнение:
"Тестирование API - не какой-то отдельный вид или тип тестирования, это просто еще один способ взаимодействия с системой. В случае с UI у вас есть, условно, страница набором полей, которые вы заполняете, отправляете и ждете реакции от системы. В случае с API у вас есть эндпоинт и набор параметров.  Посылаете запрос -> получаете ответ -> валидируете ответ. Часть из этих тестов будет негативными, часть перейдет в "контрактное" тестирование, часть уйдет в тестирование валидации. Вся остальная логика тестирования - про приоритеты, техники тест-дизайна и прочее остается неизменным. 

С чего начать. 
<ol>
<li>Почитать про инструменты, что это такое и как оно работает. 
</li>
<li>Потренироваться на любом открытом API посылать/получать/обрабатывать запросы любым удобным вам способом - хоть с помощью python (разобраться можно за 2-3 вечера неспешного изучения с нуля), хоть с помощью GUI инструментов, хоть с помощью CURL. 
</li>
<li>Получить список функциональности API:
</li>
<ol>
<li> - Кто является "клиентом" для этого АПИ (использует его ваше приложение/фронтенд или вы его отдаете во вне). 
</li>
<li>- Какие функции доступны через API. 
</li>
</ol>
<li>Для списка функциональности выше составить список функциональных тест-кейсов, начиная с того, что представляет большую бизнес значимость. 
</li>
<li>Для того же списка функциональности получить все нужные данные: 
</li>
<ol>
<li>- Эндпоинты (если они есть в вашем случае). 
</li>
<li>- Схему авторизации. 
</li>
<li>- Документацию (если есть) или описание работы. 
</li>
</ol>
<li>Дополнить список функциональных проверок из п.3 более подробными тестами про схему взаимодействия, авторизацию, тестирование контракта, валидацию значений и пр. 
</li>
<li>Начать писать запросы следуя списку тест-кейсов из п.3 и 4 с помощью инструмента, который выбрали в п.1"
</li>
</ol>
© @azshoo

Типы тестирования API:
<ul>
<li>Unit testing: Для проверки функциональности отдельной операции
</li>
<li>Functional testing: Чтобы проверить функциональность более широких сценариев с помощью блока результатов unit-тестирования, протестированных вместе
</li>
<li>Load testing: Чтобы проверить функциональность и производительность под нагрузкой
</li>
<li>Runtime/Error Detection: Мониторинг приложения для выявления проблем, таких как исключения и утечки ресурсов
</li>
<li>Security testing: Чтобы гарантировать, что реализация API защищена от внешних угроз 
</li>
<li>UI testing: Это выполняется как часть end-to-end integration тестов, чтобы убедиться, что каждый аспект пользовательского интерфейса функционирует должным образом. 
</li>
<li>Interoperability and WS Compliance testing: Совместимость и WS Compliance testing - это тип тестирования, который применяется к SOAP API. Функциональная совместимость между API-интерфейсами SOAP проверяется путем обеспечения соответствия профилям функциональной совместимости веб-служб. Соответствие WS- * проверено, чтобы гарантировать, что стандарты, такие как WS-Addressing, WS-Discovery, WS-Federation, WS-Policy, WS-Security и WS-Trust, должным образом реализованы и используются
</li>
<li>Penetration testing: Чтобы найти уязвимости при атаках злоумышленников
</li>
<li>Fuzz testing: Для проверки API путем принудительного ввода в систему некорректных данных для попытки принудительного сбоя
</li>
</ul>
Примеры для тестирования API: 
<ul>
<li>Возвращаемое значение на основе входных условий: его относительно легко проверить, поскольку входные данные могут быть определены и результаты могут быть проверены. 
</li>
<li>Ничего не возвращает: при отсутствии возвращаемого значения проверяется поведение API в системе. 
</li>
<li>Вызов другого API / события / прерывания: если выход API инициирует какое-либо событие или прерывание, то эти события и прерывания listeners следует отслеживать 
</li>
<li>Обновление структуры данных: Обновление структуры данных будет иметь определенный эффект или влияние на систему, и это должно быть проверено 
</li>
<li>Изменение определенных ресурсов: если вызов API изменяет некоторые ресурсы, его следует проверить путем доступа к соответствующим ресурсам.
</li>
</ul>
Доп. материал:
<ul>
<li><a href="https://www.youtube.com/watch?v=7D7AMmgxt_I&t=1540s&ab_channel=QASTARTUP-ITTrainingCenter">Курс Тестирование ПО. Занятие 29. Тестирование API | QA START UP</a>
</li>
<li><a href="https://dou.ua/lenta/columns/api-testing-stages/">От шока до принятия: пять стадий тестирования API</a>
</li>
<li><a href="https://software-testing.ru/library/testing/testing-automation/3382-api-testing">Тестирование API</a>
</li>
<li><a href="https://habr.com/ru/company/jugru/blog/525298/">Swagger/OpenAPI Specification как основа для ваших приемочных тестов</a>
</li>
<li><a href="https://habr.com/ru/company/nix/blog/534156/">История одного сервера и тестировщика Васи</a>
</li>
<li><a href="https://www.howtogeek.com/343877/what-is-an-api/">What Is an API?</a>
</li>
<li><a href="https://www.youtube.com/watch?v=kUPWQMalWNk&feature=youtu.be&ab_channel=ArtsiomRusauQALife">Тестирование API простыми словами за 8 минут / Тестировщик API</a>
</li>
</ul>
<h2>Как протестировать API без документации/черным ящиком?</h2>
Если Вам по какой-то причине предстоит проделать эту неблагодарную работу, определитесь, насколько все плохо и какая у Вас есть информация об объекте тестирования.

Известно ли какие порты для Вас открыты? Знаете ли Вы нужные endpoints?
Если дело совсем плохо - просканируйте порты, например, с помощью netcat. Открытые порты сохраните в файл.
Эта операция займет довольно много времени. Можете почитать советы по работе с Nmap и Netcat. 
Если Вам известен нужный порт и соответствующий endopoint - переберите все возможные HTTP методы. Начните с наиболее очевидных POST, PUT, GET. Для ускорения процесса напишите скрипт, например, на Python.

В худшем случае, когда ни порт ни endpoints неизвестны Вам, скорее всего придется перебирать все открытые порты и генерировать endpoints, которые подходят по смыслу.

Разработчики обычно не особо заморачиваются и закладывают минимально-необходимую информацию. Так что включите воображение и попробуйте придумать endpoints опираясь на бизнес логику и принятые в Вашей компании стандарты.

Если ни endpoints ни бизнес логика Вам неизвестны, то у меня есть подозрение, что Вы тестируете API с не самыми хорошими намерениями.

<h2>Тестирование клиентской части и серверной, в чем разница? (Frontend testing Vs. Backend testing?)</h2>
<img src="https://lh3.googleusercontent.com/pxJmlG2P53pOIW6wYUhc2eNaOkyhVok_Y_rnOBsMzIApYQqv0kho32UilY66FTRJISRr7TP-8w92l5xAqgWcWpA163OcpTL1uCm4mKRY1nD6JfZDjPKQw2fC-lbTwQLJKGg8m8fU">
Frontend testing - это тип тестирования, который проверяет уровень представления 3-уровневой архитектуры. С точки зрения непрофессионала, вы проверяете GUI - все, что видно на экране, на стороне клиента. Для веб-приложения интерфейсное тестирование будет включать проверку функциональных возможностей, таких как формы, графики, меню, отчеты и т. д., а также связанный Javascript. Frontend testing - это термин, охватывающий различные стратегии тестирования, включая оценку производительности фронтенда, которая является хорошей практикой перед тестированием приложения с высокими пользовательскими нагрузками. Тестировщик должен хорошо понимать бизнес-требования для выполнения этого типа тестирования. Ранее оптимизация производительности означала оптимизацию на стороне сервера. Это было связано с тем, что большинство веб-сайтов были в основном статичными, а большая часть обработки выполнялась на стороне сервера. Однако сегодня веб-приложения становятся более динамичными и в результате код на стороне клиента нередко становится причиной низкой производительности. 
Тестирование клиентской части невозможно в некоторых случаях: бэкенд разрабатывают быстрее, чем фронтенд; очевидно, если клиентская часть отсутствует в принципе ( самодостаточное приложение, терминальная команда).
Backend testing - это тип тестирования, который проверяет уровень приложений и базы данных 3-уровневой архитектуры. В сложном программном приложении, таком как ERP, внутреннее тестирование повлечет за собой проверку бизнес-логики на уровне приложений. Для более простых приложений бэкэнд-тестирование проверяет серверную часть или базу данных. Это означает, что данные, введенные в интерфейс, будут проверены в базе данных. Базы данных проверяются на наличие свойств ACID, операций CRUD, их схемы, соответствия бизнес-правилам. Базы данных также проверяются на безопасность и производительность. Производится проверка целостности данных, Проверка достоверности данных, Тестирование функций, процедур и триггеров. При внутреннем тестировании нет необходимости использовать графический интерфейс. Вы можете напрямую передавать данные с помощью браузера с параметрами, необходимыми для функции, чтобы получить ответ в некотором формате по умолчанию. Например, XML или JSON. Вы также подключаетесь к базе данных напрямую и проверяете данные с помощью SQL-запросов.

Доп. материал:<a href="https://habr.com/ru/company/funcorp/blog/518248/"> </a>
<ul>
<li><a href="https://habr.com/ru/post/510458/">Как найти границы на клиенте и сервере</a>
</li>
<li><a href="https://habr.com/ru/company/funcorp/blog/518248/">Как Иван ошибку в бэкенде локализовывал</a>
</li>
<li><a href="https://www.youtube.com/watch?v=XSeoWpSlcig&feature=youtu.be&ab_channel=PodlodkaPodcast">Круглый стол "Почему не стоит тестировать бэкенд руками"</a>
</li>
</ul>
<h2>Что подразумевают под эталонным тестированием? (Baseline testing)</h2>
Это подход к тестированию, в котором за точку отсчета берется базовая линия - это показатель конкретного ориентира, который служит основой для нового тестирования. В базовом тестировании тесты собирают и сохраняют все результаты, полученные в исходном коде, и сравнивают с эталонным базовым уровнем. Этот базовый уровень относится к последним принятым результатам испытаний. Если в исходном коде есть новые изменения, то для повторного выполнения тестов необходимо сформировать текущий базовый уровень. Если последние результаты будут приняты, то текущая базовая линия станет эталонной. По большей части Baseline testing относят к тестированию производительности.
<h2>В чем разница между Baseline и Benchmark testing?</h2>
<ul>
<li>Baseline предназначено для оценки производительности приложения. Benchmark сравнивает производительность приложения с отраслевым стандартом. 
</li>
<li>Baseline тестирование использует данные, собранные для повышения производительности. Benchmark возвращает информацию о целевом приложении по сравнению с другими приложениями.
</li>
<li>Baseline тестирование сравнивает текущую производительность с предыдущей производительностью приложения, тогда как Benchmark сравнивает производительность нашего приложения с производительностью конкурентов.
</li>
</ul>
<h2>Что такое параллельное/многопользовательское тестирование? (Concurrency/Multi-user testing)</h2>
Параллельное тестирование определяется как метод тестирования для обнаружения дефектов в приложении, когда в систему вошли несколько пользователей. Другими словами, отслеживание эффекта, когда несколько пользователей выполняют одно и то же действие одновременно. Параллельное тестирование также называется многопользовательским тестированием. Тестирование параллельной программы является более сложной задачей, чем тестирование последовательной программы, из-за недетерминированности и проблем синхронизации. Зачем оно нужно:
<ul>
<li>Определяет влияние одновременного доступа к одним и тем же записям базы данных, модулям или коду приложения. 
</li>
<li>Определяет и измеряет уровень взаимоблокировки, блокировки и использования однопоточного кода и ограничения доступа к общим ресурсам
</li>
</ul>
<h2>Как вы думаете, что такое тестирование на переносимость? </h2>
Тестирование переносимости — это тип тестирования программного обеспечения, который проводится для определения степени легкости или сложности, с которой программное приложение может быть эффективно и эффективно перенесено с одного аппаратного обеспечения, программного обеспечения или среды на другое.
Результаты тестирования переносимости представляют собой измерения того, насколько легко программный компонент или приложение будут интегрированы в среду, и затем эти результаты будут сравниваться с нефункциональным требованием переносимости программной системы. Измерение основано на сравнении стоимости адаптации программного обеспечения к новой среде и стоимости реконструкции.
Атрибуты тестирования переносимости:
<ul>
<li>Адаптивность: Адаптируемость определяется как способность программного приложения адаптироваться к конкретной среде без каких-либо усилий. Общие стандарты связи между несколькими системами помогают повысить адаптивность системы в целом.
</li>
<li>Installability: Устанавливаемость определяется как способность программного приложения быть установленным в желаемой среде без использования дополнительных ресурсов. Устанавливаемость выполняется на программном обеспечении, которое должно быть установлено в целевой среде.
</li>
<li>Заменяемость: Возможность замены определяется как способность программного приложения заменять другое программное обеспечение в конкретной среде. Приложение, которое заменяет предыдущее приложение, должно давать одинаковые результаты во всех целевых средах.
</li>
<li>Сосуществование: Сосуществование определяется как способность программного приложения работать с другим программным приложением в системе, не мешая друг другу и совместно используя один и тот же ресурс. Специально это тестирование используется в больших системах, которые включают в себя несколько подсистем.
</li>
</ul>
<h2>Что такое тестирование графического интерфейса/визуальное тестирование? (GUI - Graphical User Interface testing)</h2>
Существует два типа интерфейсов для компьютерного приложения. Интерфейс командной строки, где вы вводите текст, и компьютер отвечает на эту команду и GUI - графический интерфейс пользователя, где вы взаимодействуете с компьютером, используя графическое представление, а не текст. 
Цель тестирования графического интерфейса пользователя (GUI) - проверить функциональность интерфейса пользователя.
Примеры:
<ul>
<li>Тестирование размера, положения, ширины, высоты элементов. 
</li>
<li>Тестирование сообщений об ошибках, которые отображаются. 
</li>
<li>Тестирование разных разделов экрана. 
</li>
<li>Проверка шрифта, читаемый ли он или нет. 
</li>
<li>Тестирование экрана в разных разрешениях с помощью увеличения и уменьшения масштаба, например, 640 x 480, 600x800 и т. д. 
</li>
<li>Проверка выравнивания текстов и других элементов, таких как значки, кнопки и т. д. , находятся на своем месте или нет. 
</li>
<li>Тестирование цветов шрифтов. 
</li>
<li>Проверка цветов сообщений об ошибках, предупреждающих сообщений. 
</li>
<li>Проверка, имеет ли изображение хорошую четкость или нет. 
</li>
<li>Тестирование выравнивания изображений. 
</li>
<li>Проверка орфографии. 
</li>
<li>Пользователь не должен разочаровываться при использовании системного интерфейса. 
</li>
<li>Тестирование, является ли интерфейс привлекательным или нет. 
</li>
<li>Тестирование полос прокрутки в соответствии с размером страницы, если таковые имеются. 
</li>
<li>Тестирование отключенных полей, если таковые имеются. 
</li>
<li>Тестирование размера изображений. 
</li>
<li>Проверка заголовков, правильно ли они выровнены или нет. 
</li>
<li>Тестирование цвета гиперссылки.
</li>
</ul>

Визуальное тестирование проверяет корректность отображения пользователю web-сайта, мобильного или десктопного приложения, дизайн-системы, PDF-файла или отдельного изображения на наличие расхождений с спецификацией дизайна (рендеринг страниц, шрифтов, изображений и т. д.). Раньше выполнялось вручную, т.к., например, в случае веб-сайта классическое автоматизированное тестирование было бесполезно – большинство инструментов сверялись с DOM и не видели те ошибки, что человек мог увидеть вживую. Сейчас визуальное тестирование выполняется автоматизированными инструментами создания скриншотов и сверки их с эталоном. Там все еще очень много нюансов, но это уже не относится к статье о ручном тестировании.

Доп. материал:
<a href="https://habr.com/ru/company/oleg-bunin/blog/499638/">Эффективное тестирование верстки</a>
<h2>Что такое A/B тестирование?</h2>
A / B-тестирование также называется сплит-тестированием (split). При тестировании AB мы создаем и анализируем два варианта приложения, чтобы найти, какой вариант работает лучше с точки зрения пользовательского опыта, потенциальных клиентов, конверсий или любой другой цели, а затем в конечном итоге сохранить наиболее эффективный вариант. 
Давайте попробуем понять это на примере. Предположим, у нас есть интернет магазин и каталог отображается определенным образом. В какой-то момент (новые маркетинговые исследования/пожелания клиента и т. д.) решено изменить дизайн выдачи товаров в каталоге. Независимо от того, сколько проведено анализа, выпуск нового пользовательского интерфейса будет большим изменением и может иметь неприятные последствия. 
В этом случае мы можем использовать A / B-тестирование. Мы создадим интерфейс нового варианта и выпустим его для некоторого процента пользователей. Например - мы можем распределить пользователей в соотношении 50:50 или 80:20 между двумя вариантами - A и B. После этого в течение определенного периода времени мы будем наблюдать эффективность обоих вариантов. Таким образом, тестирование A/B помогает принять решение о выборе лучшего варианта.

Доп. материал:
<a href="https://habr.com/ru/company/skyeng/blog/518164/">Ошибки в дизайне A/B тестов, которые я думала, что никогда не совершу</a>
<h2>Что означает сквозное тестирование? (E2E - End–to–End)</h2>
Сквозное тестирование - это стратегия тестирования для выполнения тестов, которые охватывают все возможные потоки приложения от его начала до конца; проверяет программную систему вместе с ее интеграцией с внешними интерфейсами. Целью сквозного тестирования является создание полного производственного сценария, выявление программных зависимостей и утверждение, что между различными программными модулями и подсистемами передается правильный ввод. Сквозное тестирование обычно выполняется после функционального и системного тестирования. Оно использует реальные данные, такие как данные и тестовая среда, для имитации настроек в реальном времени. Сквозное тестирование также называется цепным тестированием (Chain testing).
Для чего оно нужно? Современные программные системы являются сложными и взаимосвязаны с несколькими подсистемами. Подсистема может отличаться от текущей системы или может принадлежать другой организации. Если какая-либо из подсистем выйдет из строя, вся система программного обеспечения может рухнуть. Это серьезный риск, и его можно избежать путем сквозного тестирования. 
<h2>В чем разница между E2E и системным тестированием?</h2>

<table>
<tr>
<td>End to End testing
</td><td>System testing
</td></tr>
<tr>
<td>Проверяет программную систему, а также взаимосвязанные подсистемы
</td><td>Проверяет только программную систему в соответствии со спецификациями требований.
</td></tr>
<tr>
<td>Проверяет весь E2E flow
</td><td>Проверяет функциональные возможности и функции системы.
</td></tr>
<tr>
<td>Все интерфейсы, бэкэнд-системы 
</td><td>Функциональное и нефункциональное тестирование 
</td></tr>
<tr>
<td>Выполняется после завершения System testing
</td><td>Выполняется после завершения Integration testing
</td></tr>
<tr>
<td>Сквозное тестирование включает проверку внешних интерфейсов, которые могут быть сложными для автоматизации. Следовательно, ручное тестирование является предпочтительным.
</td><td>Как ручное, так и автоматическое могут быть выполнены для тестирования системы
</td></tr>
</table>

<h2>Что такое параллельное тестирование? (Parallel testing)</h2>
Это тип тестирования ПО, который одновременно проверяет несколько приложений или подкомпонентов одного приложения, чтобы сократить время выполнения теста. При параллельном тестировании тестировщик запускает две разные версии программного обеспечения одновременно с одним и тем же вводом. Цель состоит в том, чтобы выяснить, ведут ли себя прежняя система и новая система одинаково или по-разному. Это гарантирует, что новая система достаточно способна для эффективной работы программного обеспечения.

 <img src="https://lh4.googleusercontent.com/nbGIawh-G-P2Ti_z4JFNHAeNjZe4akr_3d72SCmwiSiyMaGgj2AieL2r6spV4LQ2T2RGeHApth9s8PCqCYN1gOhICv7KylLgP2zVlwnm5m5xZLrOb2xLpxyd1hdWPHUxbpg71ihD">
Пример: когда какая-либо организация переходит от старой системы к новой, legacy является важной частью. Передача этих данных является сложным процессом. При тестировании программного обеспечения проверка совместимости вновь разработанной системы со старой системой осуществляется посредством «параллельного тестирования».
<table>
<tr>
<td>Это Parallel testing
</td><td>Это НЕ Parallel testing
</td></tr>
<tr>
<td><ul>
<li>Тестирование обновленного приложения по сравнению с предыдущим приложением. 
</li>
<li>Запуск старого сценария с новым программным обеспечением с зарезервированными условиями ввода. 
</li>
<li>Цель состоит в том, чтобы узнать, соответствует ли результат предыдущей системе. 
</li>
<li>Должен иметь знания о старой и недавно разработанной системе
</li>
</ul>
</td><td><ul>
<li>Тестирование только одного ПО 
</li>
<li>Кросс-браузерное или кроссплатформенное тестирование. 
</li>
<li>Цель состоит в том, чтобы выяснить проблему проектирования. 
</li>
<li>Знать разницу не обязательно.
</li>
</ul>
</td></tr>
</table>
<h1>----- Тест дизайн -----</h1>
<h2>Тест дизайн? (Test Design)</h2>
Этап процесса тестирования ПО, на котором проектируются и создаются Test case (тест кейсы), в соответствии с определенными ранее критериями качества и целями тестирования. План работы над тест дизайном:
<ul>
<li>анализ имеющихся проектных артефактов: документация (спецификации, требования, планы), модели, исполняемый код и т. д. 
</li>
<li>написание спецификации по тест дизайну (<a href="http://www.protesting.ru/documentation/sqe_test_design_specification_template.zip">Test Design Specification</a>)
</li>
<li>проектирование и создание <a href="http://www.protesting.ru/testing/testcase.html">Test case</a>
</li>
</ul>
Роли, ответственные за тест дизайн:
<ul>
<li>Тест аналитик - определяет "ЧТО тестировать?"
</li>
<li>Тест дизайнер - определяет "КАК тестировать?"
</li>
</ul>
Попросту говоря, задача тест аналитиков и дизайнеров сводится к тому, чтобы используя различные стратегии и техники тест дизайна, создать набор Test case, обеспечивающий оптимальное тестовое покрытие тестируемого приложения. Однако, на большинстве проектов эти роли не выделяется, а доверяется обычным тестировщикам, что не всегда положительно сказывается на качестве тестов, тестировании и, как из этого следует, на качестве ПО (конечного продукта).
<h2>Перечислите известные техники тест-дизайна?</h2>
<ul>
<li>Cтатические (Static):
</li>
<ul>
<li>Review:
</li>
<ul>
<li>Неформальное ревью (Informal review)
</li>
<li>Прохождение (Walkthrough)
</li>
<li>Техническое ревью (Technical Review)
</li>
<li>Инспекция (Inspection)
</li>
</ul>
<li>Статический анализ (Static Analysis):
</li>
<ul>
<li>Поток данных (Data Flow) 
</li>
<li>Поток управления (Control Flow)
</li>
<li>Путь (Path)
</li>
<li>Стандарты (Standards)
</li>
</ul>
</ul>
<li>Динамические (Dynamic):
</li>
<ul>
<li>Белый ящик (White-box)
</li>
<ul>
<li>Выражение (Statement)
</li>
<li>Решение (Decision)
</li>
<li>Ветвь (Branch)
</li>
<li>Условие (Condition)
</li>
<li>Конечный автомат (FSM)
</li>
</ul>
<li>Основанные на опыте (Experience-based):
</li>
<ul>
<li>Предугадывание ошибки (Error Guessing - EG)
</li>
<li>Исследовательское тестирование (Exploratory testing)
</li>
<li>Ad-hoc testing
</li>
</ul>
<li>Черный ящик (Black-box):
</li>
<ul>
<li>Эквивалентное Разделение (Equivalence Partitioning - EP)
</li>
<li>Анализ Граничных Значений (Boundary Value Analysis - BVA)
</li>
<li>Комбинаторные техники (<a href="https://sysgears.com/articles/test-design-techniques-overview/#combinatorial">Combinatorial Test Techniques</a>)
</li>
<li>Переходы между состояниями (State transition)
</li>
<li>Случаи использования (Use case testing)
</li>
</ul>
</ul>
</ul>

Альтернативный источник:
<ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#black-box">Specification-Based Testing Techniques (or Black Box techniques):</a>
</li>
<ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#equivalence-classes">Equivalence Partitioning</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#boundary-values">Boundary Value Analysis</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#combinatorial">Combinatorial Test Techniques:</a>
</li>
<ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#all-combinations">All Combinations</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#pairwise">Pairwise Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#each-choice">Each Choice Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#base-choice">Base Choice Testing</a>
</li>
</ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#decision-table">Decision Table Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#classification-tree">Classification Tree Method</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#state-transition">State Transition Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#cause-effect">Cause-Effect Graphing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#scenario">Scenario Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#random">Random Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#syntax">Syntax Testing</a>
</li>
</ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#white-box">Structure-Based Testing Techniques (or White Box techniques):</a>
</li>
<ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#statement">Statement Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#decision">Decision Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#conditions">Condition Testing:</a>
</li>
<ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#branch-condition">Branch Condition Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#branch-condition-combination">Branch Condition Combination Testing</a>
</li>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#mcdc">Modified Condition Decision Coverage (MCDC) Testing</a>
</li>
</ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#data-flow">Data Flow Testing</a>
</li>
</ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#experience">Experience-Based Testing Techniques:</a>
</li>
<ul>
<li><a href="https://sysgears.com/articles/test-design-techniques-overview/#error-guessing">Error Guessing</a>
</li>
</ul>
</ul>

Все методы тестирования на основе спецификаций (черного ящика) могут быть удобно описаны и систематизированы с помощью следующей таблицы:

<table>
<tr>
<td>Группа
</td><td>Техника
</td><td>Когда используется
</td></tr>
<tr>
<td>Элементарные методы: 
- сфокусированы на анализе входных / выходных параметров - могут быть объединены для обеспечения лучшего покрытия - обычно не используют и не зависят от других приемов
</td><td>Equivalence Partitioning
</td><td>Входные и выходные параметры имеют большое количество возможных значений
</td></tr>
<tr>
<td>Boundary Value Analysis
</td><td>Значения параметров имеют явные (например, четко определенные в документации) границы и диапазоны или неявные (например, известные технические ограничения) границы
</td></tr>
<tr>
<td>Комбинаторные стратегии: 
- объединить возможные значения нескольких входных / выходных параметров - можно использовать элементарные приемы, чтобы уменьшить количество возможных значений
</td><td>All Combinations
</td><td>Количество возможных комбинаций входов достаточно мало, или каждая отдельная комбинация входов приводит к определенному выходу
</td></tr>
<tr>
<td>Pairwise Testing
</td><td>Количество входных комбинаций чрезвычайно велико и должно быть сведено к приемлемому набору cases
</td></tr>
<tr>
<td>Each Choice Testing
</td><td>У вас есть функциональность, при которой конкретное значение параметра чаще вызывает ошибку чем комбинация значений
</td></tr>
<tr>
<td>Base Choice Testing
</td><td>Вы можете выделить набор значений параметров, которые имеют наибольшую вероятность использования
</td></tr>
<tr>
<td>Продвинутые техники: - помочь проанализировать Систему с точки зрения бизнес-логики, иерархических отношений, сценариев и т. д. - анализ основан на данных, организованных в виде таблиц, диаграмм и шаблонов - может полагаться на элементарные и комбинаторные методы для разработки Test case
</td><td>Decision Table Testing
</td><td>Существует набор комбинаций параметров и их выводов, описываемых бизнес-правилами или другими правилами.
</td></tr>
<tr>
<td>Classification Tree Method
</td><td>У вас есть иерархически структурированные данные, или данные могут быть представлены в виде иерархического дерева
</td></tr>
<tr>
<td>State Transition Testing
</td><td>В функциональности есть очевидные состояния, у которых переходы регулируются правилами (например, потоками)
</td></tr>
<tr>
<td>Cause-Effect Graphing
</td><td>Причины (входы) и следствия (выходы) связаны большим количеством сложных логических зависимостей
</td></tr>
<tr>
<td>Scenario Testing
</td><td>Есть четкие сценарии в функционале
</td></tr>
<tr>
<td>Другие
</td><td>Random Testing
</td><td>Вы должны подражать непредсказуемости реальных входных данных, или функциональность имеет несистематические дефекты
</td></tr>
<tr>
<td>Syntax Testing
</td><td>Функциональность имеет сложный синтаксический формат для ввода (например, коды, сложные имена электронной почты и т. д.)
</td></tr>
</table>

Методы тестирования на основе структуры (Structure-Based Testing Techniques): также известны как методика тестирования White Box, это означает, что мы знакомы с кодом, который собираемся тестировать. Чтобы понять эти методы, мы должны определить, что такое покрытие в контексте разработки теста. Вот хорошее определение из Книги ISTQB: Тестирование покрытия определенным образом измеряет количество тестов, выполненных набором тестов (полученных другим способом, например, с использованием методов, основанных на спецификациях). Везде, где мы можем посчитать вещи и сказать, была ли каждая из этих вещей проверена каким-либо тестом, мы можем измерить охват. Основная мера покрытия:

              Number of coverage items exercised
 Coverage = -------------------------------------- x 100%
                Total number of coverage items

где «coverage item» - это то, что мы смогли подсчитать и посмотреть, выполнил ли тест этот элемент или использовал его.
Для методов, основанных на спецификациях, это могут быть случаи использования, разделы эквивалентности, граничные значения, состояния из диаграммы перехода состояний, процент бизнес-правил из таблицы решений и т. д. Для методов, основанных на структуре, элементы покрытия представлены структурные элементы кода. В принципе, оценка покрытия означает, что мы должны решить, какие структурные элементы мы будем использовать (например, заявления или решения). Затем найдите общее количество этих элементов в коде. Введите дополнительные операторы (например, ведение журнала) рядом с каждым структурным элементом, чтобы выяснить, использовался ли этот элемент во время выполнения Test case. И, наконец, измерьте охват, выполнив тесты и используя формулу, упомянутую выше. Но, как правило, вы не должны думать обо всех этих шагах, потому что есть много автоматизированных инструментов для измерения покрытия. Методы структурного тестирования обычно подразумевают, что вы должны измерить покрытие для существующих наборов тестов (включая наборы черного ящика), а затем разработать дополнительные Test case белого ящика, основанные на элементах структурного кода, для достижения максимально возможного покрытия.

Доп. материал:
<ul>
<li><a href="https://egor-romanov.medium.com/%D1%82%D0%B5%D1%81%D1%82-%D0%B4%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%BE%D0%BC-interface-model-state-7fa89c43934d">Тест дизайн методом Interface — Model — State</a>
</li>
<li><a href="http://kaner.com/pdfs/swparadigm.pdf">Paradigms Paradigms of Black Box Software Software Testing Testing</a>
</li>
<li><a href="http://www.testingeducation.org/BBST/testdesign/">Test Design: A Survey of Black Box Software Testing Techniques</a>
</li>
</ul>
<h2>Что такое статическое тестирование, когда оно начинается и что оно охватывает?</h2>
При статическом тестировании код не выполняется. Вы вручную проверяете код, документы требований и проектные документы на наличие ошибок. Отсюда и название «статичный». Основная цель этого тестирования - повысить качество программных продуктов путем выявления ошибок на ранних этапах цикла разработки. Это тестирование также называется Non-execution техникой или verification. Проверки могут также производиться автоматически (например, используя линтеры).
В статическом тестировании проверяются следующее: 
<ul>
<li>Unit Test cases
</li>
<li>Business Requirements Document (BRD)
</li>
<li>Use Cases
</li>
<li>System/Functional Requirements
</li>
<li>Prototype
</li>
<li>Prototype Specification Document
</li>
<li>DB Fields Dictionary Spreadsheet
</li>
<li>Test Data
</li>
<li>Traceability Matrix Document
</li>
<li>User Manual/Training Guides/Documentation
</li>
<li>Test Plan Strategy Document/Test cases
</li>
<li>Automation/Performance Test Scripts
</li>
</ul>
<h2>Что такое динамическое тестирование, когда оно начинается и что оно охватывает?</h2>
При динамическом тестировании выполняется код. Оно проверяет функциональное поведение ПО, использование памяти / процессора и общую производительность системы. Основная цель этого тестирования - подтвердить, что программный продукт работает в соответствии с требованиями бизнеса. Это тестирование также называется Execution technique или validation. Динамическое тестирование выполняется на всех уровнях тестирования, и это может быть либо тестирование черного, либо белого ящика.
Виды динамического тестирования: Модульное тестирование. Интеграционное тестирование: Системное тестирование. Кроме того, нефункциональное тестирование, такое как производительность, тестирование безопасности.
На примере: Предположим, мы тестируем страницу входа в систему, где у нас есть два поля с именем «Имя пользователя» и «Пароль», а имя пользователя ограничено буквенно-цифровым форматом. Когда пользователь вводит имя пользователя «VA610», система принимает это. Но когда пользователь вводит «VA610 @ 123», тогда приложение выдает сообщение об ошибке. Этот результат показывает, что код действует динамически на основе пользовательского ввода. 
<h2>Какие виды Review вы знаете?</h2>
<ul>
<li>Неофициальные reviews: это один из видов рецензирования, который не сопровождается каким-либо процессом поиска ошибок в документе. При использовании этого метода вы просто просматриваете документ и оставляете неофициальные комментарии к нему. 
</li>
<li>Технические reviews: команда, состоящая из ваших коллег, изучает технические характеристики программного продукта и проверяет, подходят ли он для проекта. Они пытаются найти любые несоответствия в спецификациях и стандартах. Этот обзор концентрируется главным образом на технической документации, связанной с программным обеспечением, такой как: Стратегия тестирования, План тестирования и спецификации требований. 
</li>
<li>Пошаговое руководство. Автор рабочего продукта объясняет продукт своей команде. Участники могут задавать вопросы, если таковые имеются. Встреча проводится автором. 
</li>
<li>Инспекция: Основная цель - найти дефекты, а встречу проводит обученный модератор. Этот обзор является формальным типом обзора, где следует строгий процесс поиска дефектов. У рецензентов есть контрольный список для проверки рабочих продуктов. Они фиксируют дефект и информируют участников об устранении этих ошибок. 
</li>
<li>Code Walk Through: Это неформальный анализ исходного кода программы для выявления дефектов и проверки методов кодирования.
</li>
</ul>
<h2>Что вы знаете о Data Flow testing?</h2>
Тестирование потока данных - это еще один набор методов / стратегий белого ящика, который связан с анализом потока управления, но с точки зрения жизненного цикла переменной. Переменные определяются, используются и уничтожаются, когда в них больше нет необходимости. Аномалии в этом процессе, такие как использование переменной без ее определения или после ее уничтожения, могут привести к ошибке. Существуют условные обозначения, которые могут помочь в описании последовательных во времени пар в жизненном цикле переменной: 
<ul>
<li>~ - переменная еще не существует или предыдущий этап был последним 
</li>
<li>d - определено, создано, инициализировано 
</li>
<li>k - не определено, убито 
</li>
<li>u - используется (c - использование вычислений; p - использование предикатов) 
</li>
</ul>
Таким образом, ~ d, du, kd, ud, uk, uu, k ~, u ~ являются вполне допустимыми комбинациями, когда ~ u, ~ k, dd, dk, kk, ku, d ~ являются аномалиями, потенциальными или явными ошибками. В настоящее время практически все они эффективно обнаруживаются компиляторами или, по крайней мере, IDE, и нам редко требуется выполнять статический анализ для обнаружения этих аномалий. То же самое относится и к динамическому анализу, который сфокусирован на исследовании / выполнении du пар - современные языки программирования снижают вероятность возникновения проблем, связанных с du. Так что в настоящее время такая проверка в основном не стоит усилий.
<h2>Что вы знаете о Control Flow testing?</h2>
Тестирование потоков управления (Control Flow Testing) - это одна из двух техник тестирования белого ящика, основанная на определении путей выполнения кода программного модуля и создания выполняемых тест кейсов для покрытия этих путей.
Фундаментом для тестирования потоков управления является построение графов потоков управления (Control Flow Graph), основными блоками которых являются:
<ul>
<li>блок процесса - одна точка входа и одна точка выхода
</li>
<li>точка альтернативы - одна точка входа, две и более точки выхода
</li>
<li>точка соединения - две и более точек входа, одна точка выхода
</li>
</ul>
При тестировании потока управления определяются различные уровни покрытия тестами. Под «покрытием» мы подразумеваем процент кода, который был протестирован, по сравнению с тем, который есть для тестирования. В тестировании потока управления мы определяем покрытие на нескольких различных уровнях. (Обратите внимание, что эти уровни охвата представлены не по порядку. Это связано с тем, что в некоторых случаях проще определить более высокий уровень охвата, а затем определить более низкий уровень охвата с точки зрения более высокого.):

<table>
<tr>
<td>Уровень
</td><td>Название
</td><td>Краткое описание
</td></tr>
<tr>
<td>Уровень 0
</td><td>--
</td><td>"Тестируй все что протестируешь, пользователи протестируют остальное" На английском языке это звучит намного элегантнее: "Test whatever you test, users will test the rest"
</td></tr>
<tr>
<td>Уровень 1
</td><td>Покрытие операторов
</td><td>Каждый оператор должен быть выполнен как минимум один раз.
</td></tr>
<tr>
<td>Уровень 2
</td><td>Покрытие альтернатив / Покрытие ветвей
</td><td>Каждый узел с ветвлением (альтернатива) выполнен как минимум один раз.
</td></tr>
<tr>
<td>Уровень 3
</td><td>Покрытие условий
</td><td>Каждое условие, имеющее TRUE и FALSE на выходе, выполнено как минимум один раз.
</td></tr>
<tr>
<td>Уровень 4
</td><td>Покрытие условий альтернатив
</td><td>Тестовые случаи создаются для каждого условия и альтернативы
</td></tr>
<tr>
<td>Уровень 5
</td><td>Покрытие множественных условий
</td><td>Достигается покрытие альтернатив, условий и условий альтернатив (Уровни 2, 3 и 4)
</td></tr>
<tr>
<td>Уровень 6
</td><td>"Покрытие бесконечного числа путей"
</td><td>Если, в случае зацикливания, количество путей становится бесконечным, допускается существенное их сокращение, ограничивая количество циклов выполнения, для уменьшения числа тестовых случаев.
</td></tr>
<tr>
<td>Уровень 7
</td><td>Покрытие путей
</td><td>Все пути должны быть проверены
</td></tr>
</table>

Подробный разбор с примерами доступен в источнике:
flylib.com/books/en/2.156.1/control_flow_testing.html
<h2>Что такое Loop coverage?</h2>
Loop testing определяется как тип тестирования программного обеспечения методом белого ящика, который полностью фокусируется на валидности конструкций цикла. Это одна из частей тестирования структуры управления (Control Structure testing): тестирование пути, проверка данных, тестирование условий (path testing, data validation testing, condition testing). 
Этот показатель сообщает, выполняли ли вы каждое тело цикла ноль раз, ровно один раз и более одного раза (последовательно). Для циклов do-while покрытие цикла сообщает, выполняли ли вы тело ровно один раз и более одного раза. Ценным аспектом этой метрики является определение того, выполняются ли циклы while и for более одного раза, т.к. эта информация не сообщается другими метриками. 
<img src="https://lh6.googleusercontent.com/jrZUePNsJu_L0YEInoPlwq9bcWqP1V0mDQSAx97y90qg4VMSRT8fzXwDYswLgZULSpr64kNlXPHlrd0h1fqYbPK8Ao3aAQ3fUIsDDRQ9teyp2OaOBy-IVkGEGMAj4EGDVaVKPUyj">
<h2>Что такое Race coverage?</h2>
Этот показатель показывает, выполняет ли несколько потоков один и тот же код одновременно. Это помогает обнаружить сбой при синхронизации доступа к ресурсам. Это полезно для тестирования многопоточных программ, например, в операционной системе.
<h2>Тестирование пути и тестирование базового пути? (Path testing & Basis Path testing)</h2>
Path testing - это метод структурного тестирования, который включает использование исходного кода программы для нахождения каждого возможного исполняемого пути. Это помогает определить все ошибки, лежащие в части кода. Здесь Test case выполняются таким образом, что каждый путь проходится по крайней мере один раз. Все возможные control paths, включая все loop paths. Test case подготавливаются на основе логической сложности. При таком типе тестирования каждый оператор в программе гарантированно выполняется как минимум один раз. Flow Graph, Cyclomatic Complexity и Graph Metrics используются для достижения basis path.
Любая программа включает в себя несколько точек входа и выхода. Тестирование каждого из этих пунктов является сложным и трудоемким. Для сокращения избыточных тестов и достижения максимального охвата тестов используется Basis Path testing. Basis Path testing такое же, но оно основано на методе White Box testing и определяет Test case на основе потоков или логического пути, которые могут быть пройдены через программу. В программной инженерии Basis Path testing включает в себя выполнение всех возможных блоков в программе и достижение максимального охвата пути с наименьшим количеством Test case. Это гибрид branch testing и path testing. Цель Basis Path testing состоит в том, что оно определяет количество независимых путей, таким образом, число необходимых Test case может быть определено явно (максимизирует охват каждого тестового случая).
Тесты критического пути (Critical path tests) запускаются для проверки функциональности, используемой обычными пользователями во время их повседневной деятельности. Многие пользователи обычно используют определенный набор функций приложения, который необходимо проверить, как только фаза smoke будет успешно завершена. Здесь метрический предел немного ниже, чем при smoke, и он соответствует 70-80-90% в зависимости от цели проекта при ста процентах у smoke. Чаще всего на практике, на данном уровне тестирования проверяется основная масса требований к продукту. Пример: выбор шрифта, возможность набора текста, вставки картинок и т. д. 

<img src="https://lh3.googleusercontent.com/ajhl7AreCw6oZrj4sOzSc0Yi3745bDWS_hrtMoMWtfb4CBx_cw6nsKPPKu6-miB1QRam6pfq1SrZ72g73lZf6FHfZmbr7jChLZ2Ls5uYeKbulEBJcuBuyH77Kifk4NmOWoT2nSQD">

<h2>Что вы знаете о Statement coverage?</h2>
Охват операторов - это метод проектирования теста белого ящика, который включает в себя выполнение всех исполняемых операторов (if, for и switch) в исходном коде как минимум один раз. Он используется для вычисления и измерения количества операторов в исходном коде, которые могут быть выполнены с учетом требований. Другими словами, тестировщик будет концентрироваться на внутренней работе исходного кода, касающегося control flow graphs или flow charts. Как правило, в любом программном обеспечении, если мы посмотрим на исходный код, будет множество элементов, таких как операторы, функции, циклы, обработчики исключений и т. д. В зависимости от входных данных программы некоторые части кода могут не выполняться. Цель покрытия Statement - охватить все возможные пути, строки и операторы в коде. Тестируются операторы потока управления, такие как. 
Покрытие операторов позволяет найти: 
<ul>
<li>Неиспользованные выражения (Unused Statements) 
</li>
<li>Мертвый код (Dead Code)
</li>
<li>Неиспользуемые ветви (Unused Branches) 
</li>
<li>Недостающие операторы (Missing Statements)
</li>
</ul>

<img src="https://lh3.googleusercontent.com/jdaV-ql5_cSd63nzi3alwtbXVJzCz3Lh0ROOws3y5tBG8XNmYGv2qBl8jJgcGcv5zlIEJAFlW7yFQqPj6PASJ2zAKl-V_pd90xuocQtV-ighRiXTbdjTbeZrWFMXgo8-ZbGNeGpz">
<h2>Что вы знаете о Decision coverage?</h2>
«Решение» - это программная точка, в которой control flow имеет два или более альтернативных маршрута. control flow- это последовательность событий (paths) при выполнении через компонент или систему. Таким образом, если быть точным, «решение» - это узел потока управления (например, оператор if, оператор цикла или оператор case), который имеет две или более ссылок на отдельные ветви выполнения. 100% покрытие решений означает, что все возможные результаты решения были выполнены по крайней мере один раз. Для утверждений if это правда или ложь. 
Иногда этот метод называют Branch testing.
<h2>Что вы знаете о Branch coverage?</h2>
В покрытии ветвей проверяется каждый результат из модуля кода. Например, если результаты являются бинарными, вам необходимо протестировать как истинные, так и ложные результаты. Это помогает вам гарантировать, что каждая возможная ветвь из каждого условия решения выполняется по крайней мере один раз. Используя метод покрытия Branch, вы также можете измерить долю независимых сегментов кода. Это также поможет вам узнать, какие разделы кода не имеют ветвей.

Если тесты имеют полный branch coverage, то мы можем сказать, что они также имеют полный statement coverage, но не наоборот. Причина заключается в том, что в branch coverage, кроме выполнения всех statements, мы также должны проверить, выполняют ли тесты все ветви, что можно интерпретировать как охват всех ребер в control flow branch.

<img src="https://lh5.googleusercontent.com/oFvBmLitKzTlWNP3sQSXYRvoVMIH9rT4J3OEEi9CrH5igqcSX2e5TUyhbiRzCD5-bAh4HLL2NPvcyAx2zPOy-fKDZQ_GA2dqjYhnn17T4iJkvwDp-0cdOZXlD-c8dsIDBSwbQdE4">
<h2>Что вы знаете о Condition coverage?</h2>
Покрытие условий (Condition/Toggle Coverage) - рассматриваются только выражения с логическими операндами, например, AND, OR, XOR. Условное покрытие обеспечивает лучшую чувствительность к control flow, чем decision coverage. Condition Coverage не дает гарантии о полном decision coverage.
Multiple Condition Coverage: Множественное покрытие условий сообщает, встречается ли каждая возможная комбинация условий. Test Case, необходимые для полного охвата решения несколькими условиями, приведены в таблице истинности логического оператора для решения. Как и в случае покрытия условий, покрытие нескольких условий не включает покрытие решений.
<h2>Что вы знаете о FSM coverage?</h2>
Покрытие FSM (FSM Coverage) - Покрытие конечного автомата, безусловно, является наиболее сложным методом покрытия кода. В этом методе покрытия вам нужно посмотреть, как много было переходов/посещений определенных по времени состояний (time-specific states). Оно также проверяет, сколько последовательностей включено в конечный автомат.
<h2>Что такое Function coverage?</h2>
Этот показатель показывает, вызывали ли вы каждую функцию или процедуру. Во время предварительного тестирования полезно обеспечить хотя бы некоторое покрытие во всех областях программного обеспечения. Широкое неглубокое тестирование быстро обнаруживает серьезные недостатки в наборе тестов.
<h2>Что такое Call coverage?</h2>
Этот показатель показывает, выполняли ли вы каждый вызов функции. Гипотеза состоит в том, что ошибки обычно возникают в интерфейсах между модулями. Также известен как покрытие пары вызовов (call pair coverage).
<h2>Что означает LCSAJ coverage?</h2>
LCSAJ (linear code sequence and jump) «линейная последовательность кода и переход». Эта вариация path coverage учитывает только подпути, которые могут быть легко представлены в исходном коде программы, не требуя flow graph. LCSAJ - это последовательность строк исходного кода, выполняемых последовательно. Эта «линейная» последовательность может содержать decisions, пока control flow фактически продолжается от одной строки к следующей во время выполнения. Подпути создаются путем объединения LCSAJ. Исследователи ссылаются на коэффициент покрытия путей длиной n LCSAJ как на коэффициент эффективности теста (TER) n + 2.
Его основное применение при динамическом анализе программного обеспечения, чтобы помочь ответить на вопрос «Сколько тестирования достаточно?». Динамический анализ программного обеспечения используются для измерения качества и эффективности тестовых данных программного обеспечения, где количественное определение выполняются в терминах структурных единиц кода при тестировании. В более узком смысле, LCSAJ является хорошо определенным линейным участком коды программы. При использовании в этом смысле, LCSAJ также называют JJ-путь, стоя для скачка к скачку-пути. 100% LCSAJ означает 100% Statement Coverage, 100% Branch Coverage, 100% procedure или Function call Coverage, 100% Multiple condition Coverage.
<h2>Сравнение некоторых метрик</h2>
Вы можете сравнить «относительные силы»? (relative strengths), когда более сильная метрика включает более слабую метрику. 
<ul>
<li>Decision coverage включает в statement coverage, поскольку выполнение каждой ветви должно приводить к выполнению каждого statement. Эта связь сохраняется только тогда, когда control flows непрерывно до конца всех основных блоков. Например, функция C / C ++ может никогда не вернуться для завершения вызывающего базового блока, потому что она использует throw, abort, семейство exec, exit или longjmp. 
</li>
<li>Path coverage включает в себя Decision coverage. 
</li>
<li>Predicate coverage включает в себя Path coverage и multiple condition coverage, а также большинство других метрик. 
</li>
</ul>
Показатели покрытия нельзя сравнивать количественно.
<h2>Что такое Equivalence Partitioning?</h2>
Хорошо известная техника и одна из самых используемых. Часто вы можете найти такое объяснение: Например, у вас есть диапазон допустимых значений от 1 до 10, поэтому вам просто нужно проверить одно значение из диапазона - «5» и одно вне диапазона - «0». Это очень простое и понятное объяснение, но оно может дать узкий взгляд на эту технику. Что если у нас нет диапазона чисел? Концепция разделения эквивалентности возникла из математики и понимания того, что такое класс эквивалентности и отношение эквивалентности, что может быть трудно быстро понять без математического бекграунда. Но для целей тестирования, я думаю, это можно упростить, определив его следующим образом: эквивалентное разделение - это подмножество элементов из определенного набора, которые обрабатываются Системой (тестируются) одинаково. Таким образом, вам не нужно выполнять тесты для каждого элемента подмножества, и достаточно одной проверки, чтобы охватить все подмножество. Следовательно, методика может быть описана как разделение всего набора данных ввода / вывода на такие разделы. И если у вас есть, например, набор данных, содержащий около 100 элементов, которые можно разделить на 5 разделов, вы можете уменьшить количество кейсов до 5. Хитрость заключается в том, чтобы увидеть и идентифицировать разделы. Их можно найти в наборах без номеров (например, листья деревьев, разделенные по цвету - желтый, зеленый и т. д.), или даже один элемент может быть классом эквивалентности (например, лифт обычно более полон на первом этаже, чем на других этажах). По мере того, как люди выходят из здания, поднимается лифт, поэтому первый этаж - это отдельный класс эквивалентности). Очень эффективная, экономящая время техника.
<h2>Что такое Boundary Value Analysis?</h2>
Анализ Граничных Значений (Boundary Value Analysis - BVA). Второй известный метод, который часто используется в паре с предыдущим. Идея этого метода заключается в проверке граничных значений для разделов эквивалентности, когда результат изменяется с действительного на недействительный (для этого раздела). Test case, основанные на этих значениях, чувствительны к ошибкам и имеют высокую вероятность обнаружения ошибок при использовании логических операторов (> вместо >=, < вместо >, || вместо && и т. l.).
Это описание немного неоднозначно. Для проверки границ мы должны проверять допустимые значения границ диапазона, плюс одно значение ниже и одно значение вне диапазона. Таким образом, для диапазона больше 1 и меньше или равного 10, это 1, 2 и 10, 11.
<h2>Что такое Error Guessing?</h2>
Предугадывание ошибки (Error Guessing - EG). Это когда тест аналитик использует свои знания системы и способность к интерпретации спецификации на предмет того, чтобы "предугадать" при каких входных условиях система может выдать ошибку. Например, спецификация говорит: "пользователь должен ввести код". Тест аналитик, будет думать: "Что, если я не введу код?", "Что, если я введу неправильный код? ", и так далее. Это и есть предугадывание ошибки.
<h2>Что такое Cause/Effect?</h2>
Причина / Следствие (Cause/Effect - CE). Это, как правило, ввод комбинаций условий (причин), для получения ответа от системы (Следствие), то есть Простая проверка базовых действий и их результата. Например, если нажать крестик в правом верхнем углу окна (причина), оно закроется (следствие). Или вы проверяете возможность добавлять клиента, используя определенную экранную форму. Для этого вам необходимо будет ввести несколько полей, таких как "Имя", "Адрес", "Номер Телефона" а затем, нажать кнопку "Добавить" - это "Причина". После нажатия кнопки "Добавить", система добавляет клиента в базу данных и показывает его номер на экране - это "Следствие".
Граф причинно-следственных связей похож на Decision Table и также использует идею объединения условий. И иногда они описываются как один метод. Но если между условиями существует много логических зависимостей, может быть проще их визуализировать на cause-effect graph. Здесь можно выделить три этапа: 
<ul>
<li>Определить условия и последствия 
</li>
<li>Нарисовать график со всеми логическими зависимостями и ограничениями 
</li>
<li>Преобразовать график в Decision Table, отслеживая каждую комбинацию причин, которые приводят к эффекту от эффекта (tracing each combination of causes that lead to an effect from the effect).
</li>
</ul>
<h2>Что такое Exhaustive testing?</h2>
Исчерпывающее тестирование (Exhaustive testing - ET) - это крайний случай. В пределах этой техники вы должны проверить все возможные комбинации входных значений, и в принципе, это должно найти все проблемы. На практике применение этого метода не представляется возможным, из-за огромного количества входных значений.
<h2>Какие вы знаете комбинаторные техники тест-дизайна?</h2>
Или, скорее, стоит рассматривать их как комбинаторные стратегии. Их основное назначение - создавать комбинации входных параметров на основе одного из приведенных ниже алгоритмов.
Все комбинации (All combinations): как видно из названия, этот алгоритм подразумевает генерацию всех возможных комбинаций. Это означает исчерпывающее тестирование и имеет смысл только при разумном количестве комбинаций. Например, 3 переменные с 3 значениями для каждой дают нам матрицу параметров 3х3 с 27 возможными комбинациями.
Попарное тестирование (Pairwise testing) — это техника формирования наборов тестовых данных. Сформулировать суть можно, например, вот так: формирование таких наборов данных, в которых каждое тестируемое значение каждого из проверяемых параметров хотя бы единожды сочетается с каждым тестируемым значением всех остальных проверяемых параметров. Смысл метода не в том, чтобы перебрать все возможные пары параметров, а в том, чтобы подобрать пары, обеспечивающие максимально эффективную проверку при минимальном количестве выполняемых тестов. С этой задачей помогают справиться математические методы, называемые ортогональными таблицами (OAT). Также существует ряд инструментов, которые помогают автоматизировать этот процесс.

Тестирование каждого выбора (Each choice testing): эта стратегия означает, что каждое значение каждого конкретного параметра должно использоваться как минимум один раз в тестовом наборе. Таким образом, полученное количество случаев будет равно количеству значений параметра с наибольшим диапазоном. Каждый выбор - это минимальная стратегия покрытия.

<table>
<tr>
<td>param1
</td><td>param2
</td><td>param3
</td></tr>
<tr>
<td>a
</td><td>1
</td><td>X
</td></tr>
<tr>
<td>b
</td><td>2
</td><td>Y
</td></tr>
<tr>
<td>c
</td><td>3
</td><td>
</td></tr>
<tr>
<td>
</td><td>4
</td><td>
</td></tr>
<tr>
<td>
</td><td>5
</td><td>
</td></tr>
<tr>
<td>Test Case
</td><td>param1
</td><td>param2
</td><td>param3
</td></tr>
<tr>
<td>1
</td><td>a
</td><td>1
</td><td>X
</td></tr>
<tr>
<td>2
</td><td>b
</td><td>2
</td><td>Y
</td></tr>
<tr>
<td>3
</td><td>c
</td><td>3
</td><td>X
</td></tr>
<tr>
<td>4
</td><td>a
</td><td>4
</td><td>Y
</td></tr>
<tr>
<td>5
</td><td>b
</td><td>5
</td><td>X
</td></tr>
</table>


Тестирование базового выбора (Base choice testing): для этой стратегии мы должны определить наши базовые значения для каждого параметра. Это могут быть самые распространенные, самые маленькие / самые большие, самые простые или значения по умолчанию. После того, как мы сделали наш базовый выбор, мы должны изменять значение каждого параметра по одному, сохраняя при этом значения других параметров фиксированными при базовом выборе. Пусть a, 2 и Y будут нашим базовым выбором. Тогда кейсы будут:

<table>
<tr>
<td>param1
</td><td>param2
</td><td>param3
</td></tr>
<tr>
<td>a
</td><td>1
</td><td>X
</td></tr>
<tr>
<td>b
</td><td>2
</td><td>Y
</td></tr>
<tr>
<td>c
</td><td>3
</td><td>Z
</td></tr>
</table>

<table>
<tr>
<td>Test Case
</td><td>param1
</td><td>param2
</td><td>param3
</td></tr>
<tr>
<td>1
</td><td>a
</td><td>2
</td><td>Y
</td></tr>
<tr>
<td>2
</td><td>b
</td><td>2
</td><td>Y
</td></tr>
<tr>
<td>3
</td><td>c
</td><td>2
</td><td>Y
</td></tr>
<tr>
<td>4
</td><td>a
</td><td>1
</td><td>Y
</td></tr>
<tr>
<td>5
</td><td>a
</td><td>3
</td><td>Y
</td></tr>
<tr>
<td>6
</td><td>a
</td><td>2
</td><td>X
</td></tr>
<tr>
<td>7
</td><td>a
</td><td>2
</td><td>Z
</td></tr>
</table>

Доп. материал:
<a href="https://habr.com/ru/company/tinkoff/blog/516132/">Меньше, чем пара. Еще один способ сокращения количества тестов</a>

<h2>Что такое тестирование ортогональных массивов? (OAT - Orthogonal Array testing)</h2>
Оно является техникой тестирования, которая использует ортогональные массивы для создания Test case. Это особенно полезно, когда тестируемая система имеет огромные входные данные. Например, когда необходимо проверить билет на поезд, необходимо проверить такие факторы, как - количество пассажиров, номер билета, номера мест и номера поездов. Один за другим проверка каждого фактора / ввода является громоздкой. Это более эффективно, когда инженер QA объединяет больше входных данных и проводит тестирование. В таких случаях мы можем использовать метод тестирования Orthogonal Array. Этот тип сопряжения или объединения входов и тестирования системы для экономии времени называется попарным тестированием (pairwise testing). Метод OATS используется для попарного тестирования. Сформулировать суть pairwise можно, например, вот так: формирование таких наборов данных, в которых каждое тестируемое значение каждого из проверяемых параметров хотя бы единожды сочетается с каждым тестируемым значением всех остальных проверяемых параметров.

В реальном мире у тестировщиков не будет свободного времени для выполнения всех возможных Test case, чтобы выявить дефекты, поскольку существуют другие процессы, такие как документация, предложения и обратная связь с заказчиком, которые необходимо учитывать на этапе тестирования. Следовательно, test managers хотели оптимизировать количество и качество Test case, чтобы обеспечить максимальное покрытие тестами с минимальными усилиями. Это усилие называется Test case Optimisation.
<ul>
<li>Систематический и статистический способ тестирования парных взаимодействий 
</li>
<li>Точки взаимодействия и интеграции являются основным источником дефектов. 
</li>
<li>Выполните четко определенные, краткие Test case, которые могут выявить большинство ошибок. 
</li>
<li>Ортогональный подход гарантирует попарное покрытие всех переменных.
</li>
</ul>
Формула для расчета ОАТ: 
<img src="https://lh3.googleusercontent.com/gD1NuYX818654itN9YgYgA3-mnuMyTC0qolFIb5LFibtj-nKqMjgMnyqs6shfj0DIIgvwsPpNt_wNY_gwHjKb4Bc3ouZ0T_WBnzoX9j9UVT7FO9jOLWsyO1Cq39qon5bTUE1Az2-">
Runs (N) - количество строк в массиве, что выражается в количестве тестовых случаев, которые будут сгенерированы. Factors (K) - Количество столбцов в массиве, что выражается в максимальном количестве переменных, которые могут быть обработаны. Levels (V) - максимальное количество значений, которые могут быть приняты для любого отдельного фактора. Один фактор имеет от 2 до 3 входов для тестирования. Это максимальное количество входов определяет уровни.
<h2>Что такое Domain analysis/testing?</h2>
Доменный анализ: Это тип функционального тестирования, направленный на разбиение диапазона возможных значений переменной (или переменных) на поддиапазоны (или домены), с последующим выбором одного или нескольких значений из каждого домена для тестирования, то есть на анализ показательных значений и взаимосвязи элементов. Основная цель Domain testing: предоставить стратегию по выбору минимального набора показательных тестов. Кроме того, оно проверяет, что система не должна принимать входные данные, условия и индексы за пределами указанного или действительного диапазона. Во многом доменное тестирование пересекается с известными нам техниками разбиения на классы эквивалентности и анализа граничных значений. Но доменное тестирование не ограничивается перечисленными техниками. Оно включает в себя как анализ зависимостей между переменными, так и поиск тех значений переменных, которые несут в себе большой риск (не только на границах).
<img src="https://lh4.googleusercontent.com/AK8Lzev0tHf3CY5qPl9RwTVyc6skY7OwPeOc3VNUbqhGOhGN0_Vox8gn6n_eznKucdjiq8lc8kKtIDAmqB4HbGCrka5Pze4hnstqy42vgJdmp8lH3jbZZfAetq9iMpkzXp4ZXI2W">


Доп. материал:
<ul>
<li><a href="https://bbst.courses/wp-content/uploads/2018/01/Kaner-Intro-to-Domain-Testing-2018.pdf">Introduction to Domain Testing</a>
</li>
<li><a href="https://www.developsense.com/articles/2006-10-MasterOfYourDomain.pdf">Master of Your Domain</a>
</li>
</ul>
<h2>Что такое Cyclomatic Complexity в тестировании ПО? </h2>
Это метрика ПО, используемая для измерения сложности программы. Это количественная мера независимых путей в исходном коде программы. Независимый путь определяется как путь, имеющий хотя бы одно ребро, которое ранее не проходило ни в одном другом пути. Цикломатическая сложность может быть рассчитана относительно функций, модулей, методов или классов в программе. Эта метрика основана на представлении программы как control flow. Поток управления изображает программу в виде графа, который состоит из вершин и ребер. На графе вершины представляют обработку задачи, а ребра представляют поток управления между вершинами.
Тестирование базового пути является одним из методов «белого ящика» и гарантирует выполнение хотя бы одного оператора во время тестирования. Он проверяет каждый линейно независимый путь в программе, что означает, что число тестовых примеров будет эквивалентно цикломатической сложности программы. <img src="https://lh3.googleusercontent.com/M36zomzoDi0nJxl7lwtoFrZQf1nHai5AP0pkauN8Yrsl5_b1T_BwM5YmxQxzs0Rg15BEqRFDNd38TQAhR49D_E5STDm90-VbbTzlLSrxEa7pG_9OsO4Rq4Kqpbk4J1JG6lrfhy0d">

V(G) = E - N + 2 где E – количество ребер, N –количество вершин
или
V(G) = P + 1 где P - Количество предикатных узлов (узел, содержащий условие)

<img src="https://lh3.googleusercontent.com/07MfQh-QsMF1wzGPUld6zCRjcclnmNlEpGiqINBMKEOaAeIoEUMaaDj1MSSEmcTzMS254HdiijyJZSWl_raGAijnd-4ASaufU5MiUqohZHLMMISUGy6UCcdU0FJWAeDbwO7Ty4B1">
Сложность 1-10 говорит о хорошо написанном коде, легкой тестируемости и экономичности. 10-20 и 20-30 говорят об усложненном коде и трудностях с тестированием такого кода вкупе с высокими затратами. Сложность больше 40 практически не поддается проверке и стоит очень дорого. Подсчитывается вручную в случае небольшого ПО или с помощью автоматизированного ПО для крупного.
Цикломатическая Сложность может оказаться очень полезной:
<ul>
<li>Помогает разработчикам и тестировщикам определять независимые пути выполнения 
</li>
<li>Разработчики могут быть уверены, что все пути были протестированы хотя бы раз 
</li>
<li>Помогает нам больше сосредоточиться на открытых (uncovered) путях 
</li>
<li>Улучшение покрытия кода 
</li>
<li>Оценка рисков 
</li>
<li>Использование этих метрик в начале цикла снижает риски
</li>
</ul>
<h2>Что такое State Transition testing?</h2>
Тестирование переходов между состояниями определяется как метод тестирования ПО, при котором изменения входных условий вызывают изменения состояния в тестируемом приложении (AUT). Это метод тестирования черного ящика, в котором тестировщик анализирует поведение тестируемого приложения для различных входных условий в последовательности. В этом методе тестировщик предоставляет как положительные, так и негативные входные значения теста и записывает поведение системы. Это модель, на которой основаны система и тесты. Любая система, в которой вы получаете разные выходные данные для одного и того же ввода, в зависимости от того, что произошло раньше, является системой конечных состояний. Техника тестирования переходов между состояниями полезна, когда вам нужно протестировать различные системные переходы. Этот подход лучше всего подходит там, где есть возможность рассматривать всю систему как конечный автомат
<ul>
<li>Состояние (state, представленное в виде круга на диаграмме) – это состояние приложения, в котором оно ожидает одно или более событий. Состояние помнит входные данные, полученные до этого, и показывает, как приложение будет реагировать на полученные события. События могут вызывать смену состояния и/или инициировать действия.
</li>
<li>Переход (transition, представлено в виде стрелки на диаграмме) – это преобразование одного состояния в другое, происходящее по событию.
</li>
<li>Событие (event, представленное ярлыком над стрелкой) – это что-то, что заставляет приложение поменять свое состояние. События могут поступать извне приложения, через интерфейс самого приложения. Само приложение также может генерировать события (например, событие «истек таймер»). Когда происходит событие, приложение может поменять (или не поменять) состояние и выполнить (или не выполнить) действие. События могут иметь параметры (например, событие «Оплата» может иметь параметры «Наличные деньги», «Чек», «Приходная карта» или «Кредитная карта»).
</li>
<li>Действие (action, представлено после «/» в ярлыке над переходом) инициируется сменой состояния («напечатать билет», «показать на экране» и др.). Обычно действия создают что-то, что является выходными/возвращаемыми данными системы. Действия возникают при переходах, сами по себе состояния пассивны.
</li>
<li>Точка входа обозначается черным кружком.
</li>
<li>Точка выхода показывается на диаграмме в виде мишени.
</li>
</ul>

 <img src="https://lh4.googleusercontent.com/phWpxnCHLiZETao25say3M3ZHuZVBuNwHpwxoF-gsIOxbC7vmTcUXBEGqOf8FUw54SUZblk1KdXwyiDjaNo9KuXgUhciHDld8tFHTIki6tEoa1UtFzlMxNVM-rZh03Eyou36AtnG">
Для наглядности возьмем классический пример покупки авиабилетов. Все начинается с точки входа. Мы (клиенты) предоставляем авиакомпании информацию для бронирования. Служащий авиакомпании является интерфейсом между нами и системой бронирования авиабилетов. Он использует предоставленную нами информацию для создания бронирования. После этого наше бронирование находится в состоянии «Создано». После создания бронирования система также запускает таймер. Если время таймера истекает, а забронированный билет еще не оплачен, то система автоматически снимает бронь.
Каждое действие, выполненное над билетом, и соответствующее состояние (отмена бронирования пользователем, оплата билета, получение билета на руки, и т. д.) отображаются в блок-схеме. На основании полученной схемы составляется набор тестов, в котором хотя бы раз проверяются все переходы.
Некоторым исследователям представляется более удобным свести весь процесс в таблицу состояний и переходов. Конечно, таблица не так наглядна, как схема, но зато она получается более полной и систематизированной, так как определяет все возможные State-Transition варианты, а не только валидные.

Еще пример с банкоматом. После того, как мы визуализировали все переходы, мы просто выполняем определенные пути из диаграммы в качестве Test case:
<img src="https://lh4.googleusercontent.com/2TD5SS9vTwd62HdQqjvlVqiYnN2-d1zaHww6eBBqoVjy7FkyJAI5lQ2b6O2jnYhumaCpnRRhRbXBzqImhnR_0zFyXSaQBSvH1xlT21qtReaM8POn6hzKypqyJLfvg7kdL5ApJxUV">
<h2>Что такое Scenario (use case) testing?</h2>
Use Case описывает сценарий взаимодействия двух и более участников (как правило – пользователя и системы). Пользователем может выступать как человек, так и другая система. Юзкейсы могут быть позитивными (Sunny day use case) – в приоритете, и негативными (Rainy day use case).
Целью этого тестирования является нахождение дефектов, которые трудно найти при тестировании частей/модулей отдельно. Но нужно понимать, что это не аналог приемочного тестирования (но может быть его частью) и оно не охватывает все возможные варианты путей.
Как правило, Test case представлен очень небольшим количеством действий и одним результатом. Сценарий, с другой стороны, представляет собой последовательность действий (с промежуточными результатами), которые приводят к достижению какой-то конкретной цели. Сценарии могут быть частью документации разработчика (scenario diagrams). Довольно часто они задокументированы в требованиях как «use cases» - сценарии, которые обычно описывают взаимодействие пользователя с Системой. Но часто эти сценарии не очень подробны. Кроме того, прежде чем использовать их для создания Test case, их необходимо подробно описать с помощью шаблона. Шаблоны могут варьироваться от проекта к проекту. Но среди таких обычных полей, как имя, цель, предварительные условия, актер (ы) и т. д., всегда есть основной успешный сценарий и так называемые расширения (плюс иногда подвариации). Расширения - это условия, которые влияют на основной сценарий успеха. А подвариации - это условия, которые не влияют на основной flow, но все же должны быть рассмотрены. После того, как шаблон заполнен данными, мы создаем конкретные Test case, используя методы эквивалентного разделения и граничных значений. Для минимального охвата нам нужен как минимум один тестовый сценарий для основного сценария успеха и как минимум один Test case для каждого расширения. Опять же, этот метод соответствует общей формуле «получите условия, которые меняют наш результат, и проверьте комбинации». Но способ получить это - проанализировать поведение Системы с помощью сценариев.
Пример: Рассмотрим сценарий, когда пользователь покупает товар с сайта онлайн-покупок. Пользователь сначала войдет в систему и начнет поиск. Пользователь выберет один или несколько товаров, отображаемых в результатах поиска, и добавит их в корзину. После всего этого он проверит. Так что это пример логически связанного ряда шагов, которые пользователь выполнит в системе для выполнения задачи. В этом тестировании проверяется поток транзакций во всей системе от конца до конца. Варианты использования - это, как правило, путь, который пользователи чаще всего используют для достижения конкретной задачи. Таким образом, это упрощает использование прецедентов при обнаружении дефектов, поскольку включает в себя путь, с которым пользователи чаще всего сталкиваются при первом использовании приложения.

Как создать хорошие сценарии (Сэм Канер):
<ol>
<li>Напишите истории жизни для объектов в системе.
</li>
<li>Перечислите возможных пользователей, проанализируйте их интересы и цели.
</li>
<li>Подумайте об отрицательных пользователях: как они хотят злоупотреблять вашей системой?
</li>
<li>Перечислите «системные события». Как система справляется с ними?
</li>
<li>Перечислите «особые события». Какие приспособления система делает для них?
</li>
<li>Перечислите преимущества и создайте сквозные задачи, чтобы проверить их.
</li>
<li>Интервью пользователей об известных проблемах и сбоях старой системы.
</li>
<li>Работайте вместе с пользователями, чтобы увидеть, как они работают и что они делают.
</li>
<li>Читайте о том, что должны делать подобные системы.
</li>
<li>Изучите жалобы на предшественника этой системы или ее конкурентов.
</li>
<li>Создать фиктивный бизнес. Относитесь к нему как к реальному и обрабатывайте его данные.
</li>
<li>Попробуйте преобразовать реальные данные из конкурирующего или предшествующего приложения.
</li>
</ol>
<h2>Что такое Decision Table testing?</h2>
Этот простой метод заключается в документировании бизнес-логики в таблице как наборов условий и действий. Например, если у вас есть набор переменных, которые трудно запомнить и управлять ими, таблица решений поможет упорядочить их, чтобы упростить идентификацию правильных случаев. 

Пример: если пользователь вводит правильное имя пользователя и пароль, он будет перенаправлен на домашнюю страницу. Если какой-либо из вводимых данных неправильный, появится сообщение об ошибке. 
<img src="https://lh5.googleusercontent.com/8t8si1_DAntjoadGKRGpIYaXc1q0BzajHy6ysedXazE18ETU-bs-ss6NLOU_JUEgTmrUguNhP0pW-qKZ70K6oHSE1Vq5NidyEcVhipjJT6yL6agmP7m8HyqvK_bmylfMcPwKfbcd">
<table>
<tr>
<td>Условие
</td><td>1
</td><td>2
</td><td>3
</td><td>4
</td></tr>
<tr>
<td>Имя пользователя (+/-)
</td><td>-
</td><td>+
</td><td>-
</td><td>+
</td></tr>
<tr>
<td>Пароль (+/-)
</td><td>-
</td><td>-
</td><td>+
</td><td>+
</td></tr>
<tr>
<td>Итог (E/H)
</td><td>E
</td><td>E
</td><td>E
</td><td>H
</td></tr>
</table>
Условные обозначения: «+» - правильное имя пользователя / пароль «-» - Неверное имя пользователя / пароль E - Сообщение об ошибке отображается H - отображается главный экран 
<ul>
<li>Случай 1 - имя пользователя и пароль были неверны. Пользователю показывается сообщение об ошибке.
</li>
<li> Случай 2 - Имя пользователя было правильным, но пароль был неправильным. Пользователю показывается сообщение об ошибке. 
</li>
<li>Случай 3 - Имя пользователя было неверным, но пароль был правильным. Пользователю показывается сообщение об ошибке. 
</li>
<li>Случай 4 - имя пользователя и пароль были правильными, и пользователь перешел на домашнюю страницу Преобразуя это в тестовый пример, мы можем создать 2 сценария: 
</li>
<ol>
<li>Введите правильное имя пользователя и правильный пароль и нажмите на кнопку входа, и ожидаемый результат будет пользователь должен перейти на домашнюю страницу 
</li>
<li>И один из сценария ниже: 
</li>
<ol>
<li>Введите неправильное имя пользователя и неправильный пароль и нажмите на кнопку входа, и ожидаемый результат будет, пользователь должен получить сообщение об ошибке 
</li>
<li>Введите правильное имя пользователя и неправильный пароль и нажмите на кнопку входа, и ожидаемый результат будет, пользователь должен получить сообщение об ошибке 
</li>
<li>Введите неправильное имя пользователя и правильный пароль и нажмите на кнопку входа, и ожидаемый результат будет, пользователь должен получить сообщение об ошибке
</li>
</ol>
</ol>
</ul>

<h2>Что такое Random testing?</h2>
Техника функционального тестирования (Black box), также известный как тестирование с произвольным вводом, это, вероятно, самый недооцененный метод, основная идея которого заключается в выборе случайных входных данных из возможных значений для определенной функциональности. Так что нет никакой системы в выборе входных данных. Этот метод также называется monkey testing, и если мы говорим о ручном тестировании, он может быть менее эффективным, чем другие методы черного ящика. Но если мы добавим автоматизацию, она станет мощным инструментом. Просто представьте, что Test case (с различными наборами входных данных) генерируются, выполняются и оцениваются автоматически в непрерывном цикле, что позволяет вам запускать тысячи и миллионы случаев в течение разумного времени. Создание «Случайного тестера» - довольно интересная тема, но также довольно сложная и требует более глубокого изучения. Здесь я опишу это только концептуально. 
В Monkey testing тестировщиком (иногда и разработчиком) считается «Обезьяна». Если обезьяна использует компьютер, она будет произвольно выполнять любую задачу в системе из своего понимания. Точно так же, как тестировщик будет применять случайные Test case в тестируемой системе, чтобы находить bugs/errors без предварительного определения тестового примера. В некоторых случаях Monkey testing также посвящен модульному тестированию или GUI-тестированию. Основная задача: попытаться сломать систему. 
Gorilla testing - это метод тестирования ПО, при котором модуль программы многократно тестируется, чтобы убедиться, что он работает правильно и в этом модуле нет ошибок. Модуль может быть проверен более ста раз одним и тем же способом. Gorilla testing также известен как «раздражающее тестирование».

<table>
<tr>
<td>Monkey testing
</td><td>Gorilla testing
</td></tr>
<tr>
<td>Тестирование выполняется случайным образом без каких-либо заранее определенных Test case
</td><td>Тоже
</td></tr>
<tr>
<td>Тестирование выполняется на всей системе может иметь несколько Test case
</td><td>Тестирование выполняется на нескольких отдельных модулях с небольшим количеством Test case.
</td></tr>
<tr>
<td>Целью Monkey testing является проверка на сбой системы
</td><td>Целью тестирования Gorilla является проверка правильности работы модуля.
</td></tr>
</table>


<table>
<tr>
<td>Monkey testing
</td><td>Ad-hoc testing
</td></tr>
<tr>
<td>Тестирование выполняется случайным образом без каких-либо заранее определенных Test case
</td><td>Тестирование выполняется без планирования и документации (контрольные примеры и SRS)
</td></tr>
<tr>
<td>В Monkey testing тестировщики могут не знать, что за ПО и для чего оно предназначено.
</td><td>В Ad-hoc testing тестировщик должен понять ПО перед выполнением тестирования
</td></tr>
<tr>
<td>Целью Monkey testing является проверка на сбой системы
</td><td>Целью специального тестирования является случайное разделение системы на части и проверка их функциональности.
</td></tr>
</table>
Типы Обезьян:
<ul>
<li>Тупая обезьяна: тестировщики не имеют представления о системе и ее функциональных возможностях, а также не имеют никаких гарантий относительно достоверности Test case. 
</li>
<li>Умная обезьяна: тестировщик имеет четкое представление о системе, ее назначении и функциональности. Тестировщик перемещается по системе и предоставляет действительные данные для выполнения тестирования. 
</li>
<li>Выдающаяся обезьяна: тестировщики выполняют тестирование в соответствии с поведением пользователя и могут указать некоторые вероятности возникновения ошибок.
</li>
</ul>
<h2>Что такое Syntax testing?</h2>
Синтаксическое тестирование - это метод проверки «черного ящика». Этот метод помогает при разработке Test case для входных форматов. Конечно, если наши правила синтаксиса звучат как «должны быть только цифры или буквы», нам не нужен этот метод. Но если у нас есть какой-то сложный формат (например, почтовый индекс, телефон, конкретный адрес электронной почты), это может быть удобно. Прежде всего, мы должны определить наш формат и описать его формально, используя форму Бэкуса-Наура (или расширенный BNF). Это очень важный момент, поэтому я бы посоветовал вам ознакомиться с BNF, прежде чем читать дальше. После того, как мы создали определение BNF для нашего формата, пришло время генерировать положительные и отрицательные кейсы: 
Для положительных случаев мы находим возможные варианты значений, допускаемые отдельными элементами определения BNF, а затем разрабатываем варианты, чтобы просто охватить эти варианты. 
Для случаев с недопустимым синтаксисом мы определяем и применяем возможные мутации (например, отсутствующий элемент, нежелательный дополнительный элемент, недопустимое значение для элемента и т. д.) к отдельным элементам определения BNF. Затем мы разрабатываем наши кейсы, применяя мутации, которые могут давать отличительные результаты (случаи, которые приводят к действительным комбинациям, исключаются).
<img src="https://lh4.googleusercontent.com/rFO5p5QbSo8mBKETsZ5cRbAzkuVwKkCOvvoS4koDBWXe0YFwLwnoF6KTiaL9m2EgOpNKCS02oQRFLOvVicH_3SVA49I0rtASYDl2haM1BvcNiDFl61xvMMIHVlReWVWATyI-X2R1">
<h2>Что вы знаете о Classification tree method?</h2>
Большинство ресурсов выделяют два основных шага для этой техники: 
<ul>
<li>Определение относящихся к тесту аспектов (аспектов, которые влияют на функциональность - так называемые классификации) и их соответствующих значений (называемых классами, это могут быть точные значения или классы эквивалентности). 
</li>
<li>Объединение разных классов из всех классификаций в Test case.
</li>
</ul>
Оба эти шага справедливы для большинства методов тестирования и могут быть перефразированы следующим образом: - определить параметры ввода / вывода, а затем объединить их, чтобы получить ваши кейсы. 
Теперь давайте добавим некоторые детали. Классификационное дерево - это графический метод, который помогает нам визуализировать относящиеся к тесту аспекты (аспекты, которые влияют на поведение тестового объекта во время теста) в форме иерархического дерева.
Как вырастить это дерево? Это похоже на интеллектуальные карты с небольшими отличиями, если это вам о чем-то говорит. У нас есть тестовый объект (целое приложение, определенная функция, абстрактная идея и т. д.) вверху как корень. Мы рисуем ответвления от корня как классификации (проверяем соответствующие аспекты, которые мы определили). Затем, используя распределение по эквивалентности и анализ граничных значений, мы определяем наши листья как классы из диапазона всех возможных значений для конкретной классификации. И если некоторые из классов могут быть классифицированы далее, мы рисуем под-ветку / классификацию с собственными листьями / классами. Когда наше дерево завершено, мы делаем проекции листьев на горизонтальной линии (Test case), используя одну из комбинаторных стратегий (все комбинации, каждый выбор и т. д.), и создаем все необходимые комбинации.
<img src="https://lh3.googleusercontent.com/HFPlp7_pJrF7S-mmqNcgMCPbUTkU8YgS3hpMcQrIaHdO-3phJSJxtbbaqHbXIdDRigrIx6Xqr-NRvK9VCb9MZcY5WnUJOR0s_zZQfHEQPI-Sq7-5uo5rkADcR1luaVFxc63Wpucu">
В приведенном выше примере использовалась комбинаторная стратегия «Каждый выбор». Наиболее очевидные преимущества здесь - это большая наглядность и ясность объема тестового объекта и идей Test case. Если у вас есть сложные, иерархически структурированные данные, и вы можете позволить себе тратить время на создание и поддержку дерева, этот метод будет чрезвычайно удобен. И для эффективного применения метода вы можете, например, рассмотреть возможность использования специального инструмента, такого как Classification Tree Editor.
<h2>Как мы узнаем, что код соответствует спецификациям? </h2>
Матрица прослеживаемости - это интуитивно понятный инструмент, который обеспечивает соответствие требований тестовым примерам. Когда выполнение всех Test case заканчивается успешно, это указывает на то, что код соответствует требованиям. 
<h2>Что включает в себя матрица отслеживания требований? (RTM - Requirement Traceability Matrix)</h2>
Матрица прослеживаемости - это документ, который связывает любые два базовых документа, которые требуют отношения «многие ко многим» для проверки полноты отношений. В случае тестирования это матрица покрытия функциональных требований тест-кейсами.
Есть даже такое понятие как Requirement based testing, которое имеет место быть, когда есть требования к продукту, на их основе составляются тест-сценарии и выполняется тестирование.
Зачем нужна эта матрица?
Например, для того чтобы:
- при разработке тестов четко ориентироваться какие из требований уже покрыты тестами, а какие еще нет;
- при выполнении тестирования ориентироваться какие из требований прошли все написанные для них тесты успешно, а какие - еще нет.
Матрица трассировки может служить одновременно в качестве матрицы покрытия. Наличие такой матрицы позволяет объективно оценить, какая часть продукта покрыта тестами, а какая нет. Это необходимое условие, чтобы оценить, какой объем работы мы уже выполнили и что еще осталось сделать - и по части создания, и по части выполнения тестов.
Еще одно преимущество traceability matrix – ее наглядность. Если она поддерживается в актуальном состоянии, то можно сразу увидеть "белые пятна" и сосредоточиться на них.
Traceability matrix также позволяет сравнивать тесты между собой по критерию количества требований, которые они покрывают. Одни тесты могут покрывать несколько требований, другие – только одно.
<h2>В чем разница между Test matrix и Traceability matrix?</h2>
Тестовая матрица: тестовая матрица используется для определения фактического качества, усилий, плана, ресурсов и времени, необходимых для охвата всех этапов тестирования программного обеспечения. 
Матрица прослеживаемости: сопоставление между Test case и требованиями.
<h2>Что такое анализ GAP? </h2>
Анализ пробелов выявляет любые отклонения между функциями, доступными для тестирования, и восприятием их клиентом. Матрица прослеживаемости - это инструмент тестирования, который тестировщики могут использовать для отслеживания пробелов. 
<h2>Что такое граф причинно-следственных связей? (Cause Effect Graph)</h2>
Это графическое представление входных данных и связанных с ними выходных эффектов, которые помогают в разработке Test case. 
<h2>В чем разница между предугадыванием ошибок и посевом? (Error guessing and error seeding)</h2>
Предугадывание -  методика разработки Test Suite, в которой тестировщики должны предполагать возможные дефекты и писать тестовые наборы для их представления. 
Seeding. Это процесс добавления известных ошибок в программу для отслеживания скорости обнаружения и удаления. Это также помогает оценить количество неисправностей, оставшихся в программе.
<h2>Стили тестов?</h2>
*источник утерян, аналогов не нашел
<ul>
<li>Output based verification (смотрим что возвращает)
</li>
<li>State based verification (смотрим состояние)
</li>
<li>Communication based verification (общение и зависимости)
</li>
</ul>
<h2>Техники тестирования требований?</h2>
<ul>
<li>Взаимный просмотр:
</li>
<ul>
<li>беглый просмотр — автор показывает свою работу коллегам, они в свою очередь дают свои рекомендации, высказывают свои вопросы и замечания;
</li>
<li>технический просмотр — выполняется группой специалистов;
</li>
<li>формальная инспекция — привлекается большое количество специалистов, представляет собой структурированный, систематизированный и документированный подход. Минус такого варианта — тратится много времени.
</li>
</ul>
<li>Вопросы — если возникают вопросы, то можно спрашивать у представителей заказчика, более опытных коллег.
</li>
<li>Тест-кейсы и чек-листы — хорошее требование должно быть проверяемым, чтобы это определить можно использовать чек-листы или полноценные тест-кейсы. Если можно быстро придумать несколько пунктов чек-листа — это уже хороший знак.  
</li>
<li>Исследование поведения системы — необходимо мысленно смоделировать процесс работы пользователя с системой, созданной по тестируемым требованиям, после этого определить неоднозначные варианты определения системы.
</li>
<li>Рисунки — графическое представление дает наглядное представление приложения, на рисунке проще увидеть, что какие-то элементы не стыкуются, где-то чего-то не хватает и т. д. 
</li>
<li>Прототипирование — сделав наброски пользовательского интерфейса, легко оценить применение тех или иных пользовательских решений
</li>
</ul>
<h2>Что такое эвристики?</h2>
Эвристики – это быстрые, недорогие способы решения проблемы или принятия решения. Эвристики подвержены ошибкам, то есть они могут как сработать, так и не сработать. Эвристики недостаточно абстрактны, они могут перекрываться и пересекаться друг с другом. Также эвристики зависят от контекста
Процесс тестирования на основе эвристик – это такая технология тестирования алгоритмов, приложений и программ, при использовании которой стратегия тестирования основывается на предыдущем опыте и данных о вероятности наступления различных событий.
<ul>
<li>Эвристика «Время вышло!» мы останавливаем тестирование, когда заканчивается выделенное на него время.
</li>
<li>Эвристика <a href="http://ru.wikipedia.org/wiki/%D0%9F%D0%B8%D0%BD%D1%8C%D1%8F%D1%82%D0%B0">пиньяты</a> (The Piñata Heuristic). Мы прекращаем ломать программу, когда начинают выпадать конфеты – мы останавливаем тестирование, когда видим первую достаточно серьезную проблему.
</li>
<li>Эвристика «мертвой лошади». В программе слишком много ошибок, так что продолжение тестирования не имеет смысла. Мы знаем, что все изменится настолько, что сведет на нет результаты текущего тестирования.
</li>
<li>Эвристика «Задание выполнено» останавливаем тестирование, когда найдены ответы на все поставленные вопросы.
</li>
<li>Эвристика «Отмена задания» Наш клиент сказал нам: «пожалуйста, прекратите тестирование». Это может произойти по причине перерасхода бюджета, или вследствие отмены проекта, и по любой другой причине. Какова бы ни была причина, нам поручили остановить тестирование. (На самом деле эвристика «Время вышло!» может быть частным случаем более общей «Отмены задания», в том случае, если предпочтительнее, чтобы не мы сами, а заказчик принял решение о том, что время вышло.)
</li>
<li>Эвристика «Я зашел в тупик!» По какой бы то ни было причине мы останавливаемся, поскольку обнаруживаем некое препятствие. У нас нет информации, которая нам требуется (например, многие люди заявляют, что не могут тестировать без достаточного количества спецификаций). Имеется блокирующая ошибка, и таким образом мы не можем перейти в ту область продукта, которую необходимо протестировать, у нас нет необходимого оборудования или инструментария, у команды нет квалификации, требуемой для выполнения некоторых специальных тестов.
</li>
<li>Эвристика «освежающей паузы» Вместо прекращения тестирования мы приостанавливаем его на некоторое время. Мы можем остановить тестирование и сделать перерыв, когда мы устали, когда нам стало скучно или пропало вдохновение. Мы можем сделать паузу на то, чтобы выполнить некоторые исследования, разработать планы, поразмыслить над тем, что мы делали в прошлом и понять, что делать дальше. Идея заключается в том, что нам требуется определенный перерыв, после которого мы сможем вернуться к продукту со свежим взглядом или свежими мыслями. Также есть и другой вид паузы: мы можем остановить тестирование какой-либо функции, поскольку в настоящий момент другая имеет более высокий приоритет.
</li>
<li>Эвристика «Отсутствие продвижения» Что бы мы ни делали, мы получаем тот же самый результат. Это может происходить в случае, когда программа падает определенным способом или перестает отвечать, но также мы можем не продвигаться, когда программа в основном ведет себя стабильно: "выглядит хорошо!"
</li>
<li>Эвристика Привычного завершения. Мы останавливаем тестирование тогда, когда мы обычно останавливаем тестирование. Имеется протокол, задающий определенное количество идей для тестирования, или тест-кейсов, или циклов тестирования, или как вариант – имеется определенный объем работ по тестированию, который мы выполняем и после этого останавливаемся. Agile-команды, например, часто применяют такой подход: «когда выполнены все приемочные тесты, мы знаем, что продукт готов к поставке. Отличие от эвристики «Время вышло!» в том, что временные ограничения могут изменяться более гибко, чем некоторые другие. 
</li>
<li>Больше нет интересных вопросов В этот момент мы решаем, что не осталось вопросов, ответы на которые были бы достаточно ценными, чтобы оправдать стоимость продолжения тестирования, и поэтому мы останавливаемся. Эта эвристика используется в основном как дополнение к другим эвристикам, помогая принять решение о том, есть ли какие-то вопросы или риски, которые отменяют действие этих эвристик (примеры таких вопросов я привожу после каждой эвристики). Кроме того, если одна эвристика советует нам прекратить тестирование, следует проверить, нет ли интересных вопросов или серьезных рисков в других областях, и если они есть, то мы скорее продолжим тестирование, чем остановимся.
</li>
<li>Эвристика уклонения/безразличия. Иногда людей не интересует дополнительная информация, либо они не хотят знать, что происходит в программе. Тестируемое приложение может быть первой версией, которую, как мы знаем, скоро заменят. Некоторые люди прекращают тестирование по причине лени, злого умысла или отсутствия мотивации. Иногда бизнес-критичность выпуска нового релиза настолько высока, что никакая мыслимая проблема не остановит выход программы, и поэтому никакие новые результаты тестирования не будут иметь значения.
</li>
</ul>
Дополнение: Кем Канер (Cem Kaner) предложил еще одну эвристику: «Отказ от выполнения задания» (Mission Rejected), в которой тестировщик сам отказывается от продолжения тестирования. Подробнее читайте здесь.
Процесс тестирования на основе эвристик – это такая технология тестирования алгоритмов, приложений и программ, при использовании которой стратегия тестирования основывается на предыдущем опыте и данных о вероятности наступления различных событий.

Мнемоника – это набор правил и приемов, которые помогают эффективно запоминать необходимые сведения (информацию).
Большинство экспертов с мировым именем в сфере тестирования настоятельно рекомендуют использовать проверенную схему SFDPOT, автором которой является Джеймс Бах. По их словам, это самый качественный и правильный инструмент для быстрой генерации тестовых идей и наработок.
Итак, что такое SFDPOT?
SFDPOT – Structures, Functions, Data, Platforms, Operations, Times:
<ul>
<li>Structures – архитектура приложения (продукта), которая проверяется по частям. На этом этапе создаются тестовые идеи и шаги, неразрывно связанные со структурой веб-продукта;
</li>
<li>Function – производительность приложения (продукта). Проверка того, что может выполнять приложение (продукт). На этом этапе проводится функциональное тестирование ПО;
</li>
<li>Data – взаимодействие с данными. Проверка приложения на взаимодействие с данными. QA специалисты должны определить по какой логике продукт взаимодействует с данными, как проходит их получение, тип обработки и виды информации;
</li>
<li>Platform – экосистема, платформа. Выполнение проверки того, как именно приложение (продукт) потенциально взаимодействует с платформой, на которой оно создано и запущенно. Тестировщик должен определить, на каких именно платформах и внутри каких систем необходимо провести процедуру ручного и автоматизированного тестирования;
</li>
<li>Operations – проверка созданных сценариев для разработанного приложения. На этом этапе перед тестировщиками постает задача по выяснению потенциального круга будущих пользователей, которые будут взаимодействовать с создаваемым продуктом;
</li>
<li>Time – период времени, проверка того, как продукт ведет себя в зависимости от наступления или завершения каких-либо временных промежутков.
</li>
</ul>

Что же касается CRUCSPIC STMP, то этот метод может рассматриваться как составная часть Operations внутри методики SFDPOT.
Если вкратце сказать о функциональности CRUCSPIC STMP, то можно отметить, что это своего рода атрибуты системы. Наработки CRUCSPIC STMP позволяют выделить основные объекты тестирования, его целей, а также построить карту эффективности взаимодействия между собой.

<img src="https://lh5.googleusercontent.com/cF5kpa8lvcZc7iPbcOBtyeb2f4VRsJEHErLQPMNNaiZmidqJi2Mjnmvb8LQN74fCZbW9KzzrLc0ffaIF_iRrk97dc6Nty3eIa3phvTawt9MlKLtM1-_qW-ugzg65BFUiYUIW0Oxs">

================================================================================================================================================================================

# Manual part 2
<br>
<h1>----- Тестовые артефакты и документация (Test Deliverables/TestWare/test artifacts) ----- </h1>
<h2>Виды тестовой документации?</h2>
Внешняя документация:
Замечание – короткая записка, комментарий о небольшой неточности в реализации продукта.
Дефект-репорт – описание выявленного случая несоответствия производимого продукта требованиям, к нему выдвигаемым – ошибки или ее проявления. Он обязательно должен содержать следующие элементы:
<ul>
<li>Идею Test case, вызвавшего ошибку.
</li>
<li>Описание исходного состояния системы для выполнения кейса.
</li>
<li>Шаги, необходимые для того, чтобы выявить ошибку или ее проявление.
</li>
<li>Ожидаемый результат, т. е. то, что должно было произойти в соответствии с требованиями.
</li>
<li>Фактический результат, т. е. то, что произошло на самом деле.
</li>
<li>Входные данные, которые использовались во время воспроизведения кейса.
</li>
<li>Прочую информацию, без которой повторить кейс не получится.
</li>
<li>Критичность и/или приоритет.
</li>
<li>Экранный снимок (скрин).
</li>
<li>Версию, сборку, ресурс и другие данные об окружении.
</li>
</ul>
Запрос на изменение (улучшение) – описание неявных/некритичных косвенных требований, которые не были учтены при планировании/реализации продукта, но несоблюдение, которых может вызвать неприятие у конечного потребителя. И пути/рекомендации по модификации продукта для соответствия им.
Сводный отчет об испытаниях (Test summary report) представляет собой документ высокого уровня, в котором обобщаются проведенные испытания и результаты испытаний.
Политика тестирования (Test policy) – Общая цель организации при выполнении тестовых заданий описана в документе «Политика тестирования». Он создается Lead’ами и Senior’ами в группе управления тестированием совместно с руководителями групп заинтересованных сторон. Иногда тестовая политика является частью более широкой политики качества, принятой организацией. В таких случаях политика качества разъяснит общую цель менеджмента в отношении качества. Политика тестирования — это краткий документ, обобщенный на высоком уровне, который содержит следующее:
<ul>
<li>преимущества тестирования, ценность для бизнеса, предоставляемую организации, которая оправдывает стоимость качества
</li>
<li>цели тестирования, такие как укрепление доверия, выявление дефектов и снижение рисков для качества
</li>
<li>методы измерения эффективности и результативности тестирования при выполнении целей теста
</li>
<li>способы для организации улучшить свои процессы тестирования
</li>
</ul>
Стратегия тестирования (Test strategy) — это подход к проведению тестирования (STLC). Это относительно небольшой статический документ, который предшествует плану тестирования. Прежде чем писать объемный и подробный план, стоит формализовать некоторые базовые подходы к тестированию и убедиться, что все заинтересованные лица понимают одинаково, что и как будет тестироваться. Вероятность пропустить какую-либо тестовую активность очень мала, если существует правильная стратегия тестирования. Это самый важный документ для любой команды QA. Написание эффективного Стратегического документа - это навык, который тестировщик развивает с опытом. Стратегия включает:
<ul>
<li>Роли и обязанности в команде тестирования
</li>
<li>Область тестирования
</li>
<li>Тестовые инструменты
</li>
<li>Тестовая среда
</li>
<li>График тестирования
</li>
<li>Сопутствующие риски
</li>
</ul>
Внутренняя документация:
<ul>
<li>Тест-план (Test plan, план тестирования) – документ, описывающий весь объем работ по тестированию, начиная с описания объекта, расписания, критериев начала и окончания тестирования, до необходимого в процессе работы оборудования, специальных знаний, а также оценки рисков с вариантами их разрешения. Ответственность за создание документа плана тестирования лежит на Test Lead или менеджере по тестированию. Содержание:
</li>
<ul>
<li>Что надо тестировать? — описание объекта тестирования: системы, приложения, оборудования
</li>
<li>Что будете тестировать? — список функций и описание тестируемой системы и ее компонент в отдельности
</li>
<li>Как будете тестировать? — стратегия тестирования, а именно: <a href="http://www.protesting.ru/testing/testtypes.html">виды тестирования</a> и их применение по отношению к объекту тестирования
</li>
<li>Когда будете тестировать? — последовательность проведения работ: подготовка (Test Preparation), тестирование (Testing), анализ результатов (Test Result Analisys) в разрезе запланированных фаз разработки
</li>
<li>Критерии начала тестирования:
</li>
<ul>
<li>готовность тестовой платформы (тестового стенда)
</li>
<li>законченность разработки требуемого функционала
</li>
<li>наличие всей необходимой документации
</li>
</ul>
<li>Критерии окончания тестирования:
</li>
<ul>
<li>результаты тестирования удовлетворяют критериям качества продукта:
</li>
<li><a href="http://www.protesting.ru/testing/bugpriority.html#openbugsreq">требования к количеству открытых багов</a> выполнены
</li>
<li>выдержка определенного периода без изменения исходного кода приложения Code Freeze (CF)
</li>
<li>выдержка определенного периода без открытия новых багов Zero Bug Bounce (ZBB)
</li>
</ul>
<li>Хорошие дополнения:
</li>
<ul>
<li>Окружение тестируемой системы (описание программно-аппаратных средств)
</li>
<li>Необходимое для тестирования оборудование и программные средства (тестовый стенд и его конфигурация, программы для автоматизированного тестирования и т. д.)
</li>
<li>Риски и пути их разрешения
</li>
</ul>
</ul>
<li>Тестовый сценарий (Test scenario) – последовательность действий над продуктом, которые связаны единым ограниченным бизнес-процессом использования, и сообразных им проверок корректности поведения продукта в ходе этих действий. Фактически при успешном прохождении всего тестового сценария мы можем сделать заключение о том, что продукт может выполнять ту или иную возложенную на него функцию.
</li>
<ul>
<li>Создание тестовых сценариев обеспечивает полное покрытие тестами
</li>
<li>Сценарии тестирования могут быть одобрены различными заинтересованными сторонами, такими как бизнес-аналитик, разработчики, клиенты, для обеспечения тщательного тестирования ПО. Это гарантирует, что ПО работает для наиболее распространенных юзкейсов (use cases – сценарии использования).
</li>
<li>Они служат быстрым инструментом для определения трудозатрат на тестирование и, соответственно, создают предложение для клиента или организуют рабочую силу.
</li>
<li>Они помогают определить наиболее важные end-to-end транзакции или реальное использование ПО.
</li>
<li>Для изучения end-to-end функционирования программы, тестовый сценарий имеет решающее значение.
</li>
</ul>
<li>Тестовый набор/комплект (Test Suite) — Некоторый набор формализованных Test case, объединенных между собой по общему логическому признаку.
</li>
<li>Test case (тест-кейс) – Это артефакт, описывающий совокупность шагов, конкретных условий и параметров, необходимых для проверки реализации тестируемой функции или ее части. Более строго — формализованное описание одной показательной проверки на соответствие требованиям прямым или косвенным. Обязательно должен содержать следующую информацию:
</li>
<ul>
<li>Идея проверки.
</li>
<li>Описание проверяемого требования или проверяемой части требования.
</li>
<li>Используемое для проверки тестовое окружение.
</li>
<li>Исходное состояние продукта перед началом проверки.
</li>
<li>Шаги для приведения продукта в состояние, подлежащее проверке.
</li>
<li>Входные данные для использования при воспроизведении шагов.
</li>
<li>Ожидаемый результат.
</li>
<li>Прочую информацию, необходимую для проведения проверки.
</li>
</ul>
<li>Чек-лист (лист проверок) – перечень формализованных Test case в упрощенном виде удобном для проведения проверок. Test case в чек-листе не должны быть зависимыми друг от друга. Обязательно должен содержать в себе информацию о: идеях проверок, наборах входных данных, ожидаемых результатах, булевую отметку о прохождении/непрохождении тестового случая, булевую отметку о совпадении/несовпадении фактического и ожидаемого результата по каждой проверке. Может также содержать шаги для проведения проверки, данные об особенностях окружения и прочую информацию необходимую для проведения проверок. Цель – обеспечить стабильность покрытия требований проверками необходимыми и достаточными для заключения о соответствии им продукта. Особенностью является то, что чек-листы компонуются теми Test case, которые показательны для определенного требования.
</li>
<li>Матрица покрытия требований (RTM — Requirements Traceability Matrix) - это документ, который связывает требования с тест-кейсами.
</li>
<li>Тестовые данные (Test Data) — это данные, которые нужны для выполнения Test case.
</li>
</ul>

Доп. материал: 
<ul>
<li><a href="https://habr.com/ru/post/542288/">Какая бывает документация</a>
</li>
<li><a href="https://dou.ua/lenta/articles/why-do-you-need-test-strategy/">Стратегия тестирования в условиях Scrum: зачем она нужна и как построить</a>
</li>
<li><a href="https://hsto.org/getpro/habr/upload_files/5be/94e/842/5be94e842c3417a918830cc9f5f1b785.png">Интеллект-карта при составлении тест-плана</a>
</li>
</ul>
<h2>Какие отличия у тест-кейса высокого и низкого уровня?</h2>
Высокоуровневый тест-кейс (high level test case или logical test case) — тест-кейс без конкретных входных данных и ожидаемых результатов. Как правило, ограничивается общими идеями и операциями, схож по своей сути с подробно описанным пунктом чек-листа. Достаточно часто встречается в интеграционном тестировании и системном тестировании, а также на уровне дымового тестирования. Может служить отправной точкой для проведения исследовательского тестирования или для создания низкоуровневых тест-кейсов. Низкоуровневый тест-кейс (low level test case) — тест-кейс с конкретными входными данными и ожидаемыми результатами. Представляет собой «полностью готовый к выполнению» тест-кейс и вообще является наиболее классическим видом тест-кейсов. Начинающих тестировщиков чаще всего учат писать именно такие тесты, т.к. прописать все данные подробно — намного проще, чем понять, какой информацией можно пренебречь, при этом не снизив ценность тест-кейса.
<h2>Отличия Test Suite от Test Scenario?</h2>
Test Suite - это серия логически связанных Test case, которые позволяют проверить один из вариантов сценария. Test Scenario - представляет собой некий пользовательский сценарий по тестированию некой функциональности. Что-то, что пользователь может захотеть сделать с вашей системой, и вы хотите это проверить. Сценарий может иметь один или несколько Test Suite.
<h2>Какие отличия у плана тестирования и стратегии тестирования?</h2>
<ul>
<li>План тестирования - это документ, в котором описываются объем, цель и значение задачи тестирования ПО, тогда как стратегия тестирования описывает, как необходимо проводить тестирование. 
</li>
<li>План тестирования используется на уровне проекта, тогда как стратегия тестирования используется на уровне организации. 
</li>
<li>План тестирования имеет первостепенную цель, состоящую в том, как тестировать, когда тестировать, и кто будет проверять, в то время как стратегия тестирования имеет первостепенную цель - какой техники придерживаться и что проверять. 
</li>
<li>План тестирования может быть изменен, тогда как стратегия тестирования не может быть изменена. 
</li>
<li>План тестирования выполняется тест менеджером (Test Manager), а стратегия тестирования - менеджером проекта (Project Manager).
</li>
</ul>
<h2>В чем разница между тест-кейсом и чек-листом?</h2>
Сила тест-кейса в том, что в нем все расписано очень детально, и с помощью тест-кейсов тестировать сможет даже человек, который ни разу не видел тестируемое им приложение. Но все это сложно обновлять или изменять.
Сила чек-листа в том, что он простой. Там нет глубокой детализации, это просто памятка. Но тестировать приложение по чек-листу сразу, без подготовки, не понимая, что подразумевается под «Зачарджить ордер на бэкофисе» (это где? это как? это что? это откуда и куда?) — практически невозможно.

Доп. материал: 
<ul>
<li><a href="https://gcoder.ru/12-harakteristik-vysokoehffektivnyh-testov/">12 характеристик высокоэффективных тестов</a>
</li>
<li><a href="https://telegra.ph/Ozhidaemyj-rezultat-02-11">Ожидаемый результат</a>
</li>
</ul>
<h2>Чем Test case отличается от сценария тестирования?</h2>
Test case - это артефакт тестирования для проверки определенного flow с определенными входными значениями, предварительными условиями тестирования, ожидаемым выходным сигналом и постусловиями, подготовленными для охвата определенного поведения. Тестовый сценарий может иметь одну или несколько ассоциаций с тестовым набором, что означает, что он может включать несколько тестовых наборов.
<h2>Виды тест планов?</h2>
Чаще всего на практике приходится сталкиваться со следующими видами тест планов:
<ul>
<li>Мастер Тест План (Master Plan or Master Test Plan)
</li>
<li>Тест План (Test Plan), назовем его детальный тест план
</li>
<li>План Приемочных Испытаний (Product Acceptance Plan) - документ, описывающий набор действий, связанных с <a href="http://www.protesting.ru/testing/levels/acceptance.html">приемочным тестированием</a> (стратегия, дата проведения, ответственные работники и т. д.) 
</li>
</ul>
Явное отличие Мастер Тест Плана от просто Тест Плана в том, что мастер тест план является более статичным в силу того, что содержит в себе высокоуровневую (High Level) информацию, которая не подвержена частому изменению в процессе тестирования и пересмотра требований. Сам же детальный тест план, который содержит более конкретную информацию по стратегии, видам тестировании, расписанию выполнения работ, является "живым" документом, который постоянно претерпевает изменения, отражающие реальное положение дел на проекте.
В повседневной жизни на проекте может быть один Мастер Тест План и несколько детальных тест планов, описывающих отдельные модули одного приложения.
Для увеличения ценности вашего тест плана рекомендуется проводить его периодическое рецензирование со стороны участников проектной группы:
<ul>
<li>Ведущий тестировщик
</li>
<li>Тест менеджер (менеджер по качеству)
</li>
<li>Руководитель разработки
</li>
<li>Менеджер Проекта
</li>
</ul>
Каждый из перечисленных участников проекта, перед утверждением, проведет рецензию и внесет свои комментарии и предложения, которые помогут сделать Ваш тест план более полным и качественным.

<img src="https://lh6.googleusercontent.com/XYF-R2z8X0ejUX0di71ynIaLcmFFvDukrJzFDC4YxjSfJbp6havQRyu4pXGI2nzwN0dJJbp53YgZnfoFtFmOHnK6quWumxTC2a-NVGkS116rnaH1oA7hDZqCyDU5cuC8JuQowODW">

Доп. материал:
<a href="https://dou.ua/lenta/columns/creating-quality-test-plan/">Тест-план не для галочки, или 8 вопросов к заказчику на старте проекта</a>
<h2>Что является основой для подготовки плана приемки? (PAP - Product Acceptance Plan)</h2>
Прежде всего, вам нужны данные из следующих областей, чтобы подготовиться к приемке. Они могут варьироваться от компании к компании и от проекта к проекту. 
<ul>
<li>Документ с требованиями: Этот документ определяет, что именно требуется в проекте с точки зрения клиента. 
</li>
<li>Вклад клиента: это могут быть обсуждения, неформальные чаты, письма электронной почты и т. д. 
</li>
<li>План проекта: план проекта от менеджера проекта (PM) также служит хорошим вкладом в завершение вашего приемочного теста.
</li>
</ul>
<h2>Что такое тест-анализ/основа/база тестирования и условия тестирования ? (Test Analysis/Test Basis/Test conditions)</h2>
База тестирования определяется как источник информации или документ, необходимый для написания кейсов, а также для анализа тестов. База тестирования должна быть четко определена и должным образом структурирована, чтобы можно было легко определить условия тестирования, из которых можно получить тестовые примеры. Типичная основа тестирования:
<ul>
<li>  Документ с требованиями
</li>
<li>  План тестирования
</li>
<li>  Репозиторий кодов
</li>
<li>  Бизнес-требования
</li>
</ul>

Т. е. Test conditions - тестируемый аспект в test basis - элемент или событие компонента или системы, которые могут быть проверены одним или несколькими кейсами: функция, транзакция, фича, атрибут качества или структурный элемент и т.п.

Доп. материал:
<ul>
<li><a href="https://istqb-glossary.page/test-basis/">ISTQB Glossary - Test Basis</a>
</li>
<li><a href="https://glossary.istqb.org/en/term/test-condition-3">ISTQB Glossary - Test Condition</a>
</li>
</ul>
<h2>Что такое документ бизнес-требований (BRD)?</h2>
BRD предоставляет полное бизнес-решение для проекта, включая документацию о потребностях и ожиданиях клиентов. BRD выполняет следующие задачи. 
<ul>
<li>Получить соглашение с заинтересованными сторонами. 
</li>
<li>Обеспечить ясность бизнес-требований. 
</li>
<li>Описывает решение, которое соответствует потребностям клиента / бизнеса. 
</li>
<li>Определяет входные данные для следующей фазы проекта.
</li>
</ul>
<h2>Что вы знаете о требованиях (уровни/виды и т. д.)?</h2>
Виды требований по уровню:
<ul>
<li>Бизнес-требования — определяют назначение ПО, описываются в документе о видении (vision) и границах проекта (scope).
</li>
<li>Пользовательские требования — определяют набор пользовательских задач, которые должна решать программа, а также способы (сценарии) их решения в системе. Пользовательские требования могут выражаться в виде фраз утверждений, в виде <a href="https://ru.wikipedia.org/wiki/%D0%A1%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B9_%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">сценариев использования</a> (<a href="https://ru.wikipedia.org/wiki/%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA">англ.</a> use case), <a href="https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%B8%D0%B5_%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B8%D0%B8">пользовательских историй</a> (<a href="https://ru.wikipedia.org/wiki/%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA">англ.</a> user stories), сценариев взаимодействия (scenario).
</li>
<li>Функциональный уровень (функции).
</li>
</ul>

Виды требований по характеру:
1. Функциональные требования - что система должна делать. К функциональным требованиям относят (из первого вытекает следующее):
<ul>
<li>Бизнес-требования. Что система должна делать с точки зрения бизнеса. Слово "бизнес" в данном контексте ближе к слову "заказчик".  Пример бизнес-требования: промо-сайт, привлекающий внимание определенной аудитории к определенной продукции компании. 
</li>
<li>Пользовательские требования – описывают цели/задачи пользователей системы, которые должны достигаться/выполняться пользователями при помощи создаваемой программной системы. Эти требования часто представляют в виде вариантов использования (Use Cases). Иначе говоря, пользовательские требования - это что может сделать пользователь: зарегистрироваться, посмотреть определенную информацию, пересчитать данные по определенному алгоритму и прочее.
</li>
<li>Функциональные требования – определяют функциональность (поведение) программной системы, которая должна быть создана разработчиками для предоставления возможности выполнения пользователями своих обязанностей в рамках бизнес-требований и в контексте пользовательских требований.  Другими словами, что будут делать разработчики, чтобы выполнить пользовательские требования. 
</li>
</ul>
В группу функциональных требований относят и системные требования. Эти характеристики могут описывать требования как к аппаратному обеспечению (тип и частота процессора, объем оперативной памяти, объем жесткого диска), так и к программному окружению (операционная система, наличие установленных системных компонентов и сервисов и т. п.). Обычно такие требования составляются производителем или автором ПО. Например, для игры это могут быть требования такого типа: видеокарта - объем памяти от 64 Мб, совместимость сDirectX 9.0b и новейшие драйвера.  Для сайта: ОС - Windows не ниже XP, браузеры IE не ниже 7.0 и так далее.
Почему важно указывать системные требования и утверждать их у заказчика? Если не указать, например, что важно обеспечить просмотр сайта в IE 6, то разработчики вполне могут выбрать такое архитектурное решение, которое не позволит корректно отображать сайт. Системные требования напрямую зависят от целевой аудитории проекта. 

2. Нефункциональные требования. Иначе говоря, как будет работать система и почему именно так. 
<ul>
<li>Бизнес-правила.  Они определяют почему система работать должна именно так, как написано. Это могут быть ссылки на законодательство, внутренние правила заказчика и прочие причины. Часто упускают этот раздел и получается, что некоторые системные решения выглядят нетипичным и совсем неочевидными. Например, многие табачные компании и компании, производящие алкоголь, требуют постоянного доказательства того, что промо-сайтами пользуются люди, достигшие определенного возраста. Это бизнес-правило (подтверждение возраста) возникает по требованию этических комитетов заказчика, хотя и несколько противоречит маркетинговым целям и требованиям по usability. 
</li>
<li>Внешние интерфейсы. Это не только интерфейсы пользователя, но и протоколы взаимодействия с другими системами. Например, часто сайты связаны с CRM системами. Особенности протокола взаимодействия «сайт-CRM» также относятся к нефункциональным требованиям. 
</li>
<li>Атрибуты качества. Атрибуты касаются вопросов прозрачности взаимодействия с другими системами, целостности, устойчивости и т.п. К таким характеристикам относятся:
</li>
<ul>
<li>легкость и простота использования (usability)
</li>
<li>производительность (performance)
</li>
<li>удобство эксплуатации и технического обслуживания (maintainability)
</li>
<li>надежность и устойчивость к сбоям (reliability)
</li>
<li>взаимодействия системы с внешним миром (interfaces)
</li>
<li>расширяемость (scalability)
</li>
<li>требования к пользовательским и программным интерфейсам (user and software interface).
</li>
</ul>
</ul>

Еще одна классификация:
<ul>
<li>Явные требования: все, что вы написали. Чаще всего встречаются в документах, переданных заинтересованными сторонами команде разработчиков. Они могут принимать форму сложной спецификации дизайна, набора критериев приема или описание каркаса ПО.
</li>
<li>Неявные требования - это второй тип. Это все то, что ожидают пользователи и что не было прописано в явных требованиях. Примеры включают производительность, удобство использования, доступность и безопасность.
Рассмотрим облачный продукт хранения, который позволяет хранить ваши файлы в Интернете. Продукт получает новое явное требование: пользователи должны иметь доступ к частному контенту других пользователей через URL, используя кнопку совместного доступа. 
</li>
<li>Скрытые требования: все, что будет приятным сюрпризом для клиента.
Скрытые требования представляют собой функции, которые пользователи не ожидают увидеть в используемом продукте, основываясь на своем предыдущем опыте, но при их наличии данное ПО будет выигрывать в сравнении с конкурентами.
</li>
</ul>

Источники требований:
<ul>
<li>Федеральное и муниципальное отраслевое законодательство (конституция, законы, распоряжения)
</li>
<li>Нормативное обеспечение организации (регламенты, положения, уставы, приказы)
</li>
<li>Текущая организация деятельности объекта автоматизации
</li>
<li>Модели деятельности (диаграммы бизнес-процессов)
</li>
<li>Представления и ожидания потребителей и пользователей системы
</li>
<li>Журналы использования существующих программно-аппаратных систем
</li>
<li>Конкурирующие программные продукты
</li>
</ul>

Методы выявления требований:
<ul>
<li>Интервью, опросы, анкетирование
</li>
<li>Мозговой штурм, семинар
</li>
<li>Наблюдение за производственной деятельностью, «фотографирование» рабочего дня
</li>
<li>Анализ нормативной документации
</li>
<li>Анализ моделей деятельности
</li>
<li>Анализ конкурентных продуктов
</li>
<li>Анализ статистики использования предыдущих версий системы
</li>
</ul>
Требования начала для производства ПО:
<ul>
<li>необходимое тестовое окружение,
</li>
<li>билд/ресурс/предмет тестирования,
</li>
<li>код, БД, прочие компоненты объекта тестирования «заморожены», т. е. не изменяются в период всей сессии тестирования,
</li>
<li>модификация требований (хотя бы прямых) «заморожена»,
</li>
<li>известно направление тестирования,
</li>
<li>известны сроки на сессию тестирования.
</li>
</ul>
Есть и другие условия, но они менее значимы и сильно зависят от конкретного процесса в компании.
<h2>Расскажите, какие есть требования к самим требованиям?</h2>
<ul>
<li>Понятность. Если требования понятны кому-то одному, но не понятны всем остальным участникам, или наоборот понятны всем кроме одного — свидетельство об ошибке в их составлении. Как понять, что требование понятно? 
</li>
<li>Реализуемость. Требования должны быть реализуемы в рамках заявленных платформ вообще, а также реализуемыми в заявленные сроки. Разработчик должен в первую очередь смотреть на этот атрибут при проведении ревью. 
</li>
<li>Обращайте внимание на очень большие и очень маленькие числа в требованиях. Реализовать отклик в 1 миллисекунду или закачку файлов в 100ГБ, наверное, можно, только зачем, и будет ли это соответствовать основным функциональным задачам сайта?
</li>
<li>Полнота. Зависит от назначения и формата требований. В общем случае требования должны полностью описывать то, что в них изначально подразумевается (не должно быть недосказанности или «и т. д. »)
</li>
<li>Непротиворечивость. Требования должны быть поняты однозначно. Это «тест на внимательность» для тестировщика. Хорошо, если противоречие содержится в двух требованиях, расположенных рядом. Но в длинных документах требования могут занимать несколько страниц, и требования на 15 странице могут противоречить требованиям со 2 страницы. Так же требования должны не противоречить законам физики, геометрии, математики и прочим обусловленными внешними законами и обстоятельствами
</li>
<li>Измеримость. Требования можно посчитать и измерить (нет - «большая база», «быстрый отклик»)
</li>
<li>Актуальность. Требования не устарели.
</li>
<li>Проверяемость. Реализованность требования может быть определена через один из четырех возможных методов: осмотр, демонстрация, тест или анализ.
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/543340/">Чек-лист тестирования требований</a>
</li>
<li><a href="https://drive.google.com/file/d/1MV7IPacZZ77W0YGs6d3UHhCt-8Drpe6r/view?usp=sharing">Пример требований</a>
</li>
<li>Так же хорошо раскрыта эта тема в книге Куликова
</li>
</ul>
<h1>----- Дефекты и ошибки -----</h1>
<h2>Что такое дефект? </h2>
Разница между ожидаемым и фактическим результатом.

Доп. материал:
<a href="https://telegra.ph/Bag-ili-ficha-Vot-v-chyom-vopros-12-25">Баг или фича? Вот в чем вопрос!</a>
<h2>Классы дефектов?</h2>
<ul>
<li>Функциональные
</li>
<ul>
<li>Дефекты требований
</li>
<li>Дефекты функций
</li>
<li>Функциональные дефекты самого процесса тестирования
</li>
</ul>
<li>Системные 
</li>
<ul>
<li>Внутренние взаимодействия (интерфейсы)
</li>
<li>Аппаратная часть
</li>
<li>ОС
</li>
<li>Архитектура ПО
</li>
</ul>
<li>Дефекты, связанные с процессом
</li>
<ul>
<li>Арифметика (например, нюансы с округлениями в коде)
</li>
<li>Инициализация
</li>
<li>Последовательность
</li>
<li>Статическая логика (например, валидация форм)
</li>
</ul>
<li>Дефекты, связанные с данными
</li>
<li>Дефекты, связанные со стандартами
</li>
<li>Дефекты пользовательского интерфейса (UI)
</li>
</ul>
<h2>Какие есть категории дефектов? </h2>
Существует три основных категории дефектов: 
<ul>
<li>Wrong: это указывает на несоответствие в требовании и реализации. Это подразумевает отклонение от данной спецификации. 
</li>
<li>Missing: конечный продукт не имеет функции, соответствующей требованию. Это отличается от спецификаций и означает, что вы неправильно задокументировали требование. 
</li>
<li>Extra: вы добавили функцию, которую клиент не запрашивал. Это снова отклонение от спецификации. И пользователям продукта может понравиться эта функция. Но это все еще дефект, потому что это не часть спецификаций.
</li>
</ul>
<h2>Error/Mistake/Defect/Bug/Failure/Fault?</h2>
В русском языке переводятся практически одинаково, но это разные термины. В некоторых источниках данные термины следуют за категориями, описанными выше.
<ul>
<li>Ошибка (Error) возникает из-за ошибки (Mistake) в написании кода разработчиком.
</li>
<li>Дефект (Defect) это скрытый недостаток в ПО, возникший из-за ошибки в написании кода.
</li>
<li>Когда дефект (Defect) обнаруживается тестировщиком, он называется багом (Bug).
</li>
<li>Если тестировщики упустили дефект и его нашел пользователь, то это сбой (Failure).
</li>
<li>Если программа в итоге не выполняет свою функцию, то это отказ (Fault).
</li>
</ul>
<h2>Каково содержание эффективного сообщения об ошибке? </h2>
<ul>
<li>Project
</li>
<li>Subject
</li>
<li>Description
</li>
<li>Summary
</li>
<li>Detected By (Name of the Software Tester)
</li>
<li>Assigned To (Name of the Developer of the feature)
</li>
<li>Test Lead (Name)
</li>
<li>Detected in Version
</li>
<li>Closed in Version
</li>
<li>Date Detected
</li>
<li>Expected Date of Closure
</li>
<li>Actual Date of Closure
</li>
<li>Priority (Medium, Low, High, or Urgent)
</li>
<li>Severity (Range => 1 to 5)
</li>
<li>Status.
</li>
<li>Bug ID
</li>
<li>Attachment
</li>
<li>Test case Failed (Total no. of Test cases which are failing for a Bug)
</li>
</ul>

Доп. материал:
<a href="https://habr.com/ru/company/devexpress/blog/456132/">О записи багов, или Найди кота</a>
<h2>Несколько ключевых моментов, которые следует учитывать при написании отчета об ошибке? </h2>
<ul>
<li>Воспроизведите ошибку 2-3 раза. 
</li>
<li>Используйте некоторые ключевые слова, связанные с вашей ошибкой, и выполните поиск в инструменте отслеживания дефектов. 
</li>
<li>Проверьте в аналогичных модулях.
</li>
<li>Сообщите о проблеме немедленно. 
</li>
<li>Напишите подробные шаги для воспроизведения ошибки. 
</li>
<li>Напишите хорошее summary дефекта. Следите за словами в процессе написания сообщения об ошибке, они не должны оскорблять людей. Никогда не используйте капс, объясняя проблему. 
</li>
<li>Желательно проиллюстрировать проблему с помощью правильных скриншотов. 
</li>
<li>Перед публикацией перепроверьте два или три раза ваш отчет об ошибке.
</li>
</ul>
<h2>Серьезность и Приоритет Дефекта (Severity & Priority)</h2>
Разные системы баг трекинга предлагают нам разные пути описания серьезности и приоритета баг репорта, неизменным остается лишь смысл, вкладываемый в эти поля. Все знают такой баг-трекер, как Atlassian JIRA. В нем, начиная с какой-то версии вместо одновременного использования полей Severity и Priority, оставили только Priority, которое собрало в себе свойства обоих полей. Но, все же, разделение этих понятий может быть очень важно, а точнее использование обоих полей Severity и Priority, так как смысл, вкладываемый в них, различный:
Серьезность - представляет серьезность / глубину ошибки в контексте работоспособности самого ПО. Приоритет - указывает на очередность выполнения задачи или устранения дефекта. Серьезность - Описывает точку зрения приложения. Приоритет - точку зрения бизнеса. Приоритет выставляет менеджер, разработчик берет таски исходя из приоритета.

пример:
я в ходе тестирования нашел дефект, довольно критичный для приложения на мой взгляд т.к. этот дефект закрывает доступ к 20% функционала. ставлю такому багу Severity "критикал". ПМ видит багрепорт, анализирует ситуацию (поджимающие сроки, этот функционал будет рефакториться или вообще выкидываться в следующей итерации и т.п.) и ставит приорити - "медиум" или ниже.
а девелопер при работе с баг- тасктреккером руководствуется исключительно приорити, т.к. приорити и существует для регулирования очередности выполнения тасков.

Градация Серьезности дефекта (Severity):
<ul>
<li>Блокирующий (S1 – Blocker) – тестирование значительной части функциональности вообще недоступно. Блокирующая ошибка, приводящая приложение в нерабочее состояние, в результате которого дальнейшая работа с тестируемой системой или ее ключевыми функциями становится невозможна.
</li>
<li>Критический (S2 – Critical) – Критическая ошибка, неправильно работающая ключевая бизнес логика, дыра в системе безопасности, проблема, приведшая к временному падению сервера или приводящая в нерабочее состояние некоторую часть системы, то есть не работает важная часть одной какой-либо функции либо не работает значительная часть, но имеется workaround (обходной путь/другие входные точки), позволяющий продолжить тестирование.
</li>
<li>Значительный (S3 – Major)– не работает важная часть одной какой-либо функции/бизнес-логики, но при выполнении специфических условий, либо есть workaround, позволяющий продолжить ее тестирование либо не работает не очень значительная часть какой-либо функции. Также относится к дефектам с высокими visibility – обычно не сильно влияющие на функциональность дефекты дизайна, которые, однако, сразу бросаются в глаза.
</li>
<li>Незначительный (S4 – Minor) – часто ошибки GUI, которые не влияют на функциональность, но портят юзабилити или внешний вид. Также незначительные функциональные дефекты, либо которые воспроизводятся на определенном устройстве.
</li>
<li>Тривиальный (S5 – Trivial) – почти всегда дефекты на GUI - опечатки в тексте, несоответствие шрифта и оттенка и т.п., либо плохо воспроизводимая ошибка, не касающаяся бизнес-логики, проблема сторонних библиотек или сервисов, проблема, не оказывающая никакого влияния на общее качество продукта.
</li>
</ul>

Серьезность ошибки может быть низкой, средней или высокой, в зависимости от контекста.
<ul>
<li>Дефект интерфейса пользователя - Низкая
</li>
<li>Пограничные дефекты - Средняя
</li>
<li>Обработка ошибок - Средняя 
</li>
<li>Дефекты расчета - Высокая
</li>
<li>Неверно истолкованные данные - Высокая 
</li>
<li>Аппаратные сбои - Высокий 
</li>
<li>Проблемы совместимости - Высокая 
</li>
<li>Дефекты потока управления - Высокая
</li>
<li>Условия нагрузки (утечки памяти при нагрузочном тестировании) – Высокая
</li>
</ul>

Градация Приоритета дефекта (Priority):
<ul>
<li>P1 Высокий (High)
Ошибка должна быть исправлена как можно быстрее, т.к. ее наличие является критичным для проекта.
</li>
<li>P2 Средний (Medium)
Ошибка должна быть исправлена, ее наличие не является критичным, но требует обязательного решения.
</li>
<li>P3 Низкий (Low)
Ошибка должна быть исправлена, но ее наличие не является критичным и не требует срочного решения.
</li>
</ul>
<h2>Может ли быть высокий severity и низкий priority? А наоборот?</h2>
Да, такое может быть при некоторых стечениях обстоятельств. 
<ul>
<li>Очень низкая серьезность с высоким приоритетом: ошибка логотипа для любого продающего веб-сайта или крупной компании может иметь низкую серьезность, поскольку она не повлияет на функциональность веб-сайта, но может иметь высокий приоритет, поскольку вы не хотите, чтобы дальнейшая продажа продолжалась с неправильным логотипом. Или, например, сайт-визитка, показывающий только основную краткую информацию об организации может содержать грамматические ошибки, которые в иных случаях были бы с минимальным приоритетом, но в данном приведут к репутационным потерям.
</li>
<li>Очень высокая серьезность с низким приоритетом: 
</li>
<ul>
<li>Workaround, скорое обновление/удаление функционала: для веб-сайта авиакомпании дефект функциональности бронирования может быть серьезным, но может иметь низкий приоритет, так как исправление уже может быть запланировано в следующем цикле и возможно бронирование по телефону. 
</li>
<li>Наоборот, обновление запланировано на потом: бухгалтерское ПО. Не работает функция генерации годового отчета. Только вот сейчас июль. И эту функцию до декабря трогать не будут. Поэтому, приоритет можно понизить. 
</li>
<li>Редкость проявления дефекта/сложность воспроизведения для юзеров: например, если нажать на кнопку 50 раз подряд, то приложение упадет с ошибкой и будет ее показывать при попытке запуска. Или такое происходит на одной редкой модели телефона
</li>
</ul>
</ul>

<h2>Жизненный цикл дефекта?</h2>
<img src="https://lh4.googleusercontent.com/7ANYnLe1IhmZIX7mx8eNnJAGwn4riqDZDiQgBPQADpYm23mySDfk_g4DMc-GlcH9QlplkGa8KjB8BYQFpPf8mdZZ2nujHwgc20rcB30sqT571yM_cVK0WA2RSgrhcK5v23uNpbhF">
Жизненный цикл дефекта - это представление различных состояний дефекта, в которых он пребывает от начального до конечного этапа своего существования. Он может варьироваться от компании к компании или даже настраиваться для некоторых проектов.
Допустим вы нашли баг и зарегистрировали его в баг трекинг системе. Согласно нашей блок-схеме он получит статус "Новый". Тестировщик, ответственный за валидацию новых баг репортов, или координатор проекта (в зависимости от распределения ролей в вашей команде) может перевести его в один из следующих статусов:
"Отклонен", если данный баг невалидный или повторный, или же его просто не смогли воспроизвести
"Отсрочен", если данный баг не нужно исправлять в данной итерации
"Открыт", если исправление бага необходимо
Рассмотрим теперь по порядку каждый из вариантов.
Отклонен. В этом случае вы можете либо поспорить о судьбе вашего багрепорта, изменив статус на "Переоткрыт" либо закрыть его - статус "Закрыт"
Отсрочен. Баг репорт в статусе "Отсрочен" можно перевести в статус "Открыт", когда потребуется исправление либо в статус "Закрыт", если уже не потребуется.
Открыт. Именно в таком состоянии разработчик получает баг репорт для исправления. Он может отклонить (дальнейшие действия смотрите в пункте 1) или исправить баг. Баг репорт в статусе "Исправлен" переводится на тестировщика для проверки. В случае если проблема все еще воспроизводится, выставляется статус "Переоткрыт" и баг репорт направляется назад на доработку к разработчику. Если же исправление было успешным, то баг репорт переводится в статус "Закрыт".
* * *
Хотим отметить, что данная схема сильно упрощена. Для большей наглядности и, возможно, удобства работы на проекте, вы можете добавить дополнительные статусы и переходы, тем более, что современные баг трекинговые системы позволяют это делать. Правда имейте в виду, что излишне запутанные схемы переходов и лишние статусы могут значительно усложнить жизнь.

Примечание 1: в некоторых системах баг трекинга, созданный баг репорт сразу получает статус "Открыт" без дополнительной валидации
Примечание 2: многие баг трекинговые системы позволяют переоткрывать закрытые баги, однако лично я против такой практики, поэтому и не описывал подобный переход в выше представленном жизненном цикле
Примечание 3: Рассмотренный выше жизненный цикл основан на том, что в команде есть кто-то, ответственный за назначение баг репортов. В случае, если такой роли на проекте нет, то баги назначаются разработчиками самостоятельно, и тогда во избежании путанницы, есть смысл ввести еще один промежуточный статус "В разработке" (In progress), показывающий, что данный баг репорт уже назначен и находится на стадии исправления. 
<h2>Что такое утечка дефектов и релиз бага? (Bug Leakage & Bug Release)</h2>
Релиз бага - это когда программное обеспечение или приложение передается группе тестирования, зная, что дефект присутствует в выпуске. При этом приоритет и серьезность ошибки низки, поскольку ошибка может быть удалена до окончательной передачи обслуживания. 
Утечка бага - когда баг обнаруживается конечными пользователями или заказчиком, а не обнаруживается группой тестирования во время тестирования программного обеспечения.
<h2>Что означает плотность дефектов при тестировании ПО? </h2>
Плотность дефектов - это количество дефектов, подтвержденных в программном обеспечении / модуле в течение определенного периода эксплуатации или разработки, деленное на размер ПО / модуля. Это позволяет решить, готова ли часть ПО к выпуску. Плотность дефектов рассчитывается на тысячу строк кода, и обозначается KLOC.
Однако не существует фиксированного стандарта для плотности ошибок, исследования показывают, что один дефект на тысячу строк кода обычно считается признаком хорошего качества проекта. 
<h2>Что означает процент обнаружения дефектов при тестировании ПО? </h2>
Процент обнаружения дефектов (DDP) - это тип метрики тестирования. Он показывает эффективность процесса тестирования путем измерения соотношения дефектов, обнаруженных до выпуска и сообщенных после выпуска клиентами. Например, скажем, QA зарегистрировало 70 дефектов во время цикла тестирования, а клиент сообщил еще 20 после выпуска. DDP составит 72,1% после расчета 70 / (70 + 20) = 72,1%. 
<h2>Что означает эффективность устранения дефектов при тестировании ПО? (DRP)</h2>
Эффективность устранения дефектов (DRP) - это тип метрики тестирования. Это показатель эффективности команды разработчиков для устранения проблем перед выпуском. Он измеряется как отношение зафиксированных дефектов к общему количеству обнаруженных проблем. Например, допустим, что во время цикла тестирования было обнаружено 75 дефектов, в то время как 62 из них были устранены командой разработчиков во время измерения. DRE достигнет 82,6% после расчета 62/75 = 82,6%.
<h2>Что означает эффективность Test case в тестировании ПО? (TCE)</h2>
Эффективность тестирования (TCE) - это тип метрики тестирования. Это четкий показатель эффективности выполнения Test case на этапе выполнения теста в выпуске. Это помогает в обеспечении и измерении качества Test case. Эффективность тестового набора (TCE) => (Количество обнаруженных дефектов / Количество выполненных Test case) * 100 
<h2>Возраст дефекта в тестировании ПО? </h2>
Возраст дефекта - это время, прошедшее между днем ​​обнаружения тестировщиком и днем, когда разработчик исправил его. 
<h2>Что такое принцип Парето в тестировании ПО? </h2>
В тестировании ПО принцип Парето говорит о том, что 80% всех ошибок приходится на 20% кода.
<h2>Каковы различные способы применения принципа Парето в тестировании ПО? </h2>
1. Расставьте дефекты по их причинам, а не по последствиям. Не клубите ошибки, которые дают тот же результат. Группируйте проблемы в зависимости от того, в каком модуле они возникают. 
2. Сотрудничайте с командой разработчиков, чтобы найти новые способы классификации проблем. Например, используйте ту же статическую библиотеку для компонентов, которые учитывают большинство ошибок. 
3. Больше энергии вкладывайте в поиск проблемных областей в исходном коде, а не в случайный поиск. 
4. Переупорядочьте Test case и выберите наиболее важные для начала. 
5. Обратите внимание на реакцию конечного пользователя и оцените зоны риска. 
<h2>В чем основное отличие отладки от тестирования? (Debugging Vs. Testing)</h2>
Тестирование заключается в обнаружении дефектов при использовании продукта, а отладка - в части кода, вызывающей сбой. Отладка изолирует проблемную область в коде, сделанном разработчиком, тогда как Тестирование идентифицирует ошибку в приложении и выполняется тестировщиком.
<h2>Почему в программном обеспечении есть ошибки? </h2>
<ul>
<li>Недопонимание. 
</li>
<li>Ошибки программирования. 
</li>
<li>Сжатые сроки.
</li>
<li>Изменение в требованиях. 
</li>
<li>Сложность ПО. 
</li>
</ul>
<h2>Что вы будете делать, если во время тестирования появится ошибка? </h2>
Когда обнаруживается ошибка, запустите больше тестов, чтобы убедиться, что проблема имеет четкое описание. Запустите еще несколько тестов, чтобы убедиться, что одна и та же проблема не существует с разными входами. Как только мы полностью уверены в ошибке, мы можем добавить подробности и сообщить о ней. 
<h2>Как вы справляетесь с невоспроизводимой ошибкой? </h2>
Следующие типы ошибок относятся к категории невоспроизводимых. 
<ul>
<li>Наблюдаемые дефекты из-за недостатка памяти 
</li>
<li>Проблемы, возникающие из-за адреса, указывающего на область памяти, которая не существует. 
</li>
<li>Состояние гонки - ошибка проектирования <a href="https://ru.wikipedia.org/wiki/%D0%9C%D0%BD%D0%BE%D0%B3%D0%BE%D0%BF%D0%BE%D1%82%D0%BE%D1%87%D0%BD%D0%BE%D1%81%D1%82%D1%8C">многопоточной</a> системы или приложения, при которой работа системы или приложения зависит от того, в каком порядке выполняются части кода
</li>
</ul>
Тестировщик может предпринять следующие действия для устранения невоспроизводимых ошибок. 
<ul>
<li>Выполните шаги теста, близкие к описанию ошибки. 
</li>
<li>Оцените тестовую среду. 
</li>
<li>Изучите и оцените результаты выполнения теста. 
</li>
<li>Держите ресурсы и временные ограничения под контролем.
</li>
</ul>
<h2>Если продукт находится в производстве и один из его модулей обновляется, то необходимо ли провести повторную проверку? </h2>
Повторная проверка относится только к исправленным дефектам. После обновления модуля желательно выполнить регрессионное тестирование и запустить интеграционные тесты и прочие тесты для всех других модулей. После, QA следует провести Системное тестирование. Все зависит от компании и бюджета, стратегии/политики тестирования или политики качества.
<h2>Что такое анализ рисков? </h2>
Анализ рисков - это метод выявления вещей, которые могут пойти не так в проекте разработки ПО. Они могут негативно повлиять на объем, качество, своевременность и стоимость проекта. Тем не менее, все участники проекта участвуют в минимизации риска. Но именно лидер гарантирует, что вся команда понимает индивидуальную роль в управлении риском.
Как выполнять анализ рисков во время тестирования ПО? Анализ рисков - это процесс выявления скрытых проблем, которые могут помешать успешной доставке приложения. Он также устанавливает приоритетность последовательности устранения выявленных рисков для целей тестирования. Ниже приведены некоторые из рисков, которые представляют интерес для обеспечения качества. 
<ul>
<li>Новое оборудование 
</li>
<li>Новые технологии 
</li>
<li>Новый инструмент автоматизации 
</li>
<li>Последовательность доставки кода 
</li>
<li>Наличие тестовых ресурсов для приложения 
</li>
</ul>
Мы выделяем их в три категории, которые заключаются в следующем. 
<ul>
<li>Высокая важность: влияние ошибки значительно на другие функциональные возможности приложения 
</li>
<li>Средний: это несколько терпимо, но не желательно. 
</li>
<li>Низкий: терпимо. Этот вид риска не влияет на бизнес компании.
</li>
</ul>
<h2>Что такое скрытый дефект? (Latent defect)</h2>
Этот дефект является существующим дефектом в системе, но он не вызывает никаких сбоев, поскольку точный набор условий еще никогда не выполнялся.
<h2>Что такое маскировка ошибок, объясните примером? </h2>
Когда наличие одного дефекта скрывает наличие другого дефекта в системе, это называется маскированием неисправностей. Пример: если «отрицательное значение» вызывает исключение необработанного системного исключения, разработчик предотвратит ввод отрицательных значений. Это решит проблему и скроет дефект обработки необработанных исключений. 
<h2>Категории/подходы к отладке? (Debugging approaches)</h2>
Отладка - этап, следующий после разработки и тестирования. Тестирование предназначено для поиска ошибок, а отладка - для поиска причины конкретной ошибки.
В целом мы можем разделить методы отладки на две основные категории:
<ul>
<li>Методы, которые анализируют производительность программы путем проверки основной памяти после сбоя программы (посмертная отладка - post-mortem debugging).
</li>
<li>Методы пошагового анализа программы путем ее запуска под отладчиком («динамическая отладка» или «отслеживание отладки» - "dynamic debugging" or "tracing debugging").
</li>
</ul>
Подробнее:
<ul>
<li>Метод грубой силы (Brute Force Method): это наиболее распространенный метод отладки, однако он является наименее экономичным. Во время этого подхода программа запускается с расставленными операторами print для печати промежуточных значений с надеждой, что ряд записанных значений может облегчить обнаружение оператора с ошибкой. 
</li>
<li>Возврат (Backtracking): это также довольно распространенный подход. Во время этого подхода, начиная с оператора, в котором был обнаружен симптом ошибки, исходный код извлекается в обратном порядке, пока не будет обнаружена ошибка. К сожалению, из-за того, что количество возможных обратных линий поставок будет увеличиваться, количество потенциальных обратных методов возрастет и должно стать невообразимо большим, что ограничивает использование этого подхода.
</li>
<li>Метод устранения причины (Cause Elimination Method): при таком подходе составляется список причин, которые предположительно могли способствовать появлению симптомов ошибки, и проводятся тесты для устранения каждой ошибки. Связанный метод идентификации ошибки из симптома ошибки - это анализ дерева ошибок пакета (fault tree analysis).
</li>
<li>Нарезка программы (Program Slicing): этот метод аналогичен поиску с возвратом. Здесь поиск сокращен срезами процесса. Слайс (нарезка) программы для конкретной переменной в конкретном операторе это набор строк, предшествующих этому оператору, которые будут влиять на значение этой переменной
</li>
<li>Анализ дерева отказов (FTA - Fault tree analysis) - это нисходящий дедуктивный анализ отказов, в котором нежелательное состояние системы анализируется с использованием булевой логики для объединения серии событий нижнего уровня
</li>
</ul>

<h2>Что такое Эффективность удаления дефектов? (DRE - Defect Removal Efficiency)</h2>
Этот показатель используется для измерения эффективности теста. Из этого показателя мы узнаем, сколько ошибок мы обнаружили в наборе Test case. Формула для расчета DRE имеет вид 
DRE = Количество ошибок во время тестирования / (количество ошибок во время тестирования + количество ошибок, обнаруженных пользователем)
<h2>Что такое сортировка дефектов? (Bug triage)</h2>
Это формальный процесс, позволяющий определить, какие ошибки являются важными, путем определения их приоритетов на основе их серьезности, частоты, риска и других важных параметров. Тестировщики назначают приоритет (высокий, средний, низкий) каждой ошибке на bug triage meeting и в зависимости от приоритета эти ошибки будут исправлены в соответствующем порядке. Делая это, мы экономим ресурсы организации.
<h1>----- SDLC и STLC -----</h1>
<h2>Что вы знаете о жизненном цикле разработки ПО? (SDLC - Software Development Lifecycle) </h2>
SDLC определяет все стандартные фазы, которые участвуют в процессе разработки ПО. Жизненный цикл SDLC - это процесс поэтапной разработки ПО, которому следуют в программных проектах. Каждый этап SDLC производит результаты, необходимые для следующего этапа жизненного цикла. Требования транслируются в дизайн. Код пишется в соответствии с дизайном. Тестирование должно проводиться на разработанном продукте в соответствии с требованиями. Развертывание должно быть сделано после завершения тестирования.

<img src="https://lh5.googleusercontent.com/cM54PLQZQBJ7qHLK55NAjzH-qbNYmxDoz7ImumqTl2pdiDDJdd6aCVwECTdUZDEYwwrMhxCRr_iKpS2EU2J5se6MxYWHL4O9JyWkauOIKJRYBEnSKXbkAvYdUuNOgljCX-hhWpMk">

<ul>
<li>Этап требований (Requirement Phase): Сбор и анализ требований является наиболее важной фазой в жизненном цикле разработки программного обеспечения. Бизнес-аналитик получает требование от Заказчика / Клиента в соответствии с бизнес-потребностями и документирует требования в Спецификации бизнес-требований (Business Requirement Specification, название документа зависит от Организации. Некоторые примеры: Спецификация требований клиента (CRS - Customer Requirement Specification), Бизнес-спецификация (BS - Business Specification), и т. д. ), и предоставляет то же самое для команды разработчиков. 
</li>
<li>Этап анализа (Analysis Phase): После сбора и анализа требований следующим шагом является определение и документирование требований к продукту и их утверждение заказчиком. Это делается с помощью документа Спецификация требований к программному обеспечению (SRS - Software Requirement Specification). SRS состоит из всех требований к продукту, которые должны быть спроектированы и разработаны в течение жизненного цикла проекта. Ключевыми людьми, вовлеченными в этот этап, являются Project Manager, Business Analyst и Senior члены команды. Результатом этого этапа является спецификация требований к программному обеспечению. 
</li>
<li>Этап проектирования (Design Phase): высокоуровневый дизайн (HLD - High-Level Design) – это про архитектуру программного продукта, который должен быть разработан, и выполняется архитекторами и старшими разработчиками. Низкоуровневый дизайн (LLD - Low-Level Design) - это делается старшими разработчиками. Он описывает, как должна работать каждая функция продукта и как должен работать каждый компонент. Здесь будет только дизайн, а не код. Результатом этого этапа является документ высокого уровня и документ низкого уровня, который служит входными данными для следующего этапа.
</li>
<li>Этап разработки (Development Phase): Разработчики всех уровней участвуют в этом этапе. На этом этапе мы начинаем создавать программное обеспечение и начинаем писать код для продукта. Результатом этого этапа является исходный код документа (SCD - Source Code Document) и разработанный продукт. 
</li>
<li>Этап тестирования (Testing Phase): Когда программное обеспечение готово, оно отправляется в отдел тестирования, где группа тестирования тщательно тестирует его на наличие различных дефектов. Они либо тестируют программное обеспечение вручную, либо используют инструменты автоматического тестирования, в зависимости от процесса, определенного в STLC (жизненный цикл тестирования программного обеспечения), и гарантируют, что каждый компонент программного обеспечения работает нормально. Как только QA удостоверится, что программное обеспечение не содержит серьезных ошибок, оно переходит к следующему этапу, который является реализацией. Результатом этого этапа является качество продукта и артефакты тестирования. 
</li>
<li>Этап развертывания и обслуживания (Deployment and Maintenance Phase): После успешного тестирования продукт доставляется / развертывается заказчику для использования. Развертывание выполняется Deployment/Implementation engineers. Однажды, когда клиенты начнут использовать разработанную систему, возникнут реальные проблемы, и время от времени их придется решать. Устранение проблем, обнаруженных заказчиком, происходит на этапе обслуживания. Техническое обслуживание должно выполняться в соответствии Соглашением об уровне обслуживания (SLA - Service Level Agreement)
</li>
</ul>
<h2>Что такое цикл/колесо Деминга? (Deming circle/cycle/wheel)</h2>
Цикл PDCA (Plan – Do – Check – Act) - это непрерывный (до получения конечного результата) итеративный четырехступенчатый метод управления, используемый в бизнесе для постоянного улучшения процессов. Это одна из ключевых концепций качества, и она также называется кругом/ циклом/ колесом Деминга.
<ul>
<li>Plan: Запланируйте изменения (либо для решения проблемы, либо для улучшения некоторых областей) и решите, какую цель достичь. Здесь мы определяем цель, стратегию и вспомогательные методы для достижения цели нашего плана. 
</li>
<li>Do: Разработать или пересмотреть бизнес-требования в соответствии с планом. Здесь мы реализуем план (с точки зрения реализации плана) и проверяем его эффективность 
</li>
<li>Check: Оцените результаты, чтобы убедиться, что мы достигнем целей, как планировалось. Здесь мы составляем контрольный список для записи того, что прошло хорошо, а что не сработало (извлеченные уроки) 
</li>
<li>Act: Если изменения не соответствуют запланированным, продолжайте цикл для достижения цели с другим планом. Здесь мы принимаем меры по факту того, что не работает, как планировалось. Задача состоит в том, чтобы продолжать пытаться улучшить процесс с другим планом. 
</li>
</ul>
<h2>Модели разработки ПО?</h2>
Waterfall (каскадная модель, или «водопад»). В этой модели разработка осуществляется поэтапно: каждая следующая стадия начинается только после того, как заканчивается предыдущая. Если все делать правильно, «водопад» будет наиболее быстрой и простой моделью. Применяется уже почти полвека, с 1970-х.
<img src="https://lh3.googleusercontent.com/lONz2RMSs0wt9X95FmOSw4QhTyej2MkSLt4oZro1imWty7R4xSOSL_biQ1YdidkSjCyH51hdkb6zVhO1O6O9A3zqpwyzmkB-zjZrlqBYYTbWiuDhlOJYvfNIup_ieYQW2gtUkDUD">
Преимущества «водопада»: Разработку просто контролировать. Заказчик всегда знает, чем сейчас заняты программисты, может управлять сроками и стоимостью. Стоимость проекта определяется на начальном этапе. Все шаги запланированы уже на этапе согласования договора, ПО пишется непрерывно «от и до».
Не нужно нанимать тестировщиков с серьезной технической подготовкой. Тестировщики смогут опираться на подробную техническую документацию.
Недостатки каскадной модели: Тестирование начинается на последних этапах разработки. Если в требованиях к продукту была допущена ошибка, то исправить ее будет стоить дорого. Тестировщики обнаружат ее, когда разработчик уже написал код, а технические писатели — документацию.
Заказчик видит готовый продукт в конце разработки и только тогда может дать обратную связь. Велика вероятность, что результат его не устроит. Разработчики пишут много технической документации, что задерживает работы. Чем обширнее документация у проекта, тем больше изменений нужно вносить и дольше их согласовывать.
«Водопад» подходит для разработки проектов в медицинской и космической отрасли, где уже сформирована обширная база документов (СНиПов и спецификаций), на основе которых можно написать требования к новому ПО. При работе с каскадной моделью основная задача — написать подробные требования к разработке. На этапе тестирования не должно выясниться, что в них есть ошибка, которая влияет на весь продукт.

V-образная модель (разработка через тестирование)
Это усовершенствованная каскадная модель, в которой заказчик с командой программистов одновременно составляют требования к системе и описывают, как будут тестировать ее на каждом этапе. История этой модели начинается в 1980-х.
<img src="https://lh6.googleusercontent.com/lsqdKdUL1zr1UDuV3NNYNxtMPNsZUuWSmpDBSvYV2jrOyrA6ySgKCh18ZYVSoF8DD7nB3eCsI5M1CasiG68XN0r-SbACixj7y9boKfBg6ettfdNbSNELhsHD8Qt7NNoQ7wsf0w96">
Преимущества V-образной модели: Количество ошибок в архитектуре ПО сводится к минимуму.
Недостатки V-образной модели: Если при разработке архитектуры была допущена ошибка, то вернуться и исправить ее будет стоить дорого, как и в «водопаде». 
V-модель подходит для проектов, в которых важна надежность и цена ошибки очень высока. Например, при разработке подушек безопасности для автомобилей или систем наблюдения за пациентами в клиниках. 

Incremental Model (инкрементная модель)
Это модель разработки по частям (increment в переводе с англ. — приращение) уходит корнями в 1930-е. Рассмотрим ее на примере создания социальной сети.
Заказчик решил, что хочет запустить соцсеть, и написал подробное техническое задание. Программисты предложили реализовать основные функции — страницу с личной информацией и чат. А затем протестировать на пользователях, «взлетит или нет».
Команда разработки показывает продукт заказчику и выпускает его на рынок. Если и заказчику, и пользователям социальная сеть нравится, работа над ней продолжается, но уже по частям.
Программисты параллельно создают функциональность для загрузки фотографий, обмена документами, прослушивания музыки и других действий, согласованных с заказчиком. Инкремент за инкрементом они совершенствуют продукт, приближаясь к описанному в техническом задании.
<img src="https://lh4.googleusercontent.com/IjgpTPtEnT8ecFUyRR6XNxEWEygnndB6_0-vzY3OilyoFthW2XybTO5NUTTbx1q19-lOpoyhrw-JqOrBbBnkT_Pxpc6TvpVuklH-B-A2qUyTdMlkmBZ1Q7bxWbKIYst8ER2DOgJ3">
Преимущества инкрементной модели
Не нужно вкладывать много денег на начальном этапе. Заказчик оплачивает создание основных функций, получает продукт, «выкатывает» его на рынок — и по итогам обратной связи решает, продолжать ли разработку. Можно быстро получить фидбэк от пользователей и оперативно обновить техническое задание. Так снижается риск создать продукт, который никому не нужен. Ошибка обходится дешевле. Если при разработке архитектуры была допущена ошибка, то исправить ее будет стоить не так дорого, как в «водопаде» или V-образной модели.
Недостатки инкрементной модели: Каждая команда программистов разрабатывает свою функциональность и может реализовать интерфейс продукта по-своему. Чтобы этого не произошло, важно на этапе обсуждения техзадания объяснить, каким он будет, чтобы у всех участников проекта сложилось единое понимание. 
Разработчики будут оттягивать доработку основной функциональности и «пилить мелочевку». Чтобы этого не случилось, менеджер проекта должен контролировать, чем занимается каждая команда. 
Инкрементная модель подходит для проектов, в которых точное техзадание прописано уже на старте, а продукт должен быстро выйти на рынок.

Iterative Model (итеративная модель)
Это модель, при которой заказчик не обязан понимать, какой продукт хочет получить в итоге, и может не прописывать сразу подробное техзадание.
<img src="https://lh6.googleusercontent.com/sJJev0RliRq5S5cRbGrB2_acnGEGeqn_rMqtsgyIscPNGCcaTIgAvYNdzh0rvHCPSOCFG2Um30TrkBw-K2oKNFzo-0GjqrSEmisAjbAhflWyEDifu8rLlNJbphg9X14v6-bjqP5U">
Рассмотрим на примере создания мессенджера, как эта модель работает.
Заказчик решил, что хочет создать мессенджер. Разработчики сделали приложение, в котором можно добавить друга и запустить чат на двоих.
Мессенджер «выкатили» в магазин приложений, пользователи начали его скачивать и активно использовать. Заказчик понял, что продукт пользуется популярностью, и решил его доработать.
Программисты добавили в мессенджер возможность просмотра видео, загрузки фотографий, записи аудиосообщений. Они постепенно улучшают функциональность приложения, адаптируют его к требованиям рынка.
Преимущества итеративной модели: Быстрый выпуск минимального продукта дает возможность оперативно получать обратную связь от заказчика и пользователей. А значит, фокусироваться на наиболее важных функциях ПО и улучшать их в соответствии с требованиями рынка и пожеланиями клиента. Постоянное тестирование пользователями позволяет быстро обнаруживать и устранять ошибки.
Недостатки итеративной модели: Использование на начальном этапе баз данных или серверов — первые сложно масштабировать, а вторые не выдерживают нагрузку. Возможно, придется переписывать большую часть приложения. Отсутствие фиксированного бюджета и сроков. Заказчик не знает, как выглядит конечная цель и когда закончится разработка.
Итеративная модель подходит для работы над большими проектами с неопределенными требованиями, либо для задач с инновационным подходом, когда заказчик не уверен в результате. 

Spiral Model (спиральная модель)
Используя эту модель, заказчик и команда разработчиков серьезно анализируют риски проекта и выполняют его итерациями. Последующая стадия основывается на предыдущей, а в конце каждого витка — цикла итераций — принимается решение на основе рисков, продолжать ли развивать проект.
<img src="https://lh6.googleusercontent.com/m2VLTkTLjbcJfunc25XdYuoWY0kFSVh0KGy0Qz1vk3cjmblEcxyJjSh65ZapnQlvfVMmlkWaGEoyI6KoW8izCXoAqcHz8wQZojUEUAaBsgd9339005eZ9KWa3JPPzrsqUhldUSK7">
Рассмотрим, как функционирует эта модель, на примере разработки системы «Умный дом». 
Заказчик решил, что хочет сделать такую систему, и заказал программистам реализовать управление чайником с телефона. Они начали действовать по модели «водопад»: выслушали идею, провели анализ предложений на рынке, обсудили с заказчиком архитектуру системы, решили, как будут ее реализовывать, разработали, протестировали и «выкатили» конечный продукт.
Заказчик оценил результат и риски: насколько нужна пользователям следующая версия продукта — уже с управлением телевизором. Рассчитал сроки, бюджет и заказал разработку. Программисты действовали по каскадной модели и представили заказчику более сложный продукт, разработанный на базе первого.
Заказчик подумал, что пора создать функциональность для управления холодильником с телефона. Но, анализируя риски, понял, что в холодильник сложно встроить Wi-Fi-модуль, да и производители не заинтересованы в сотрудничестве по этому вопросу. Следовательно, риски превышают потенциальную выгоду. На основе полученных данных заказчик решил прекратить разработку и совершенствовать имеющуюся функциональность, чтобы со временем понять, как развивать систему «Умный дом».
Спиральная модель похожа на инкрементную, но здесь гораздо больше времени уделяется оценке рисков. С каждым новым витком спирали процесс усложняется. Эта модель часто используется в исследовательских проектах и там, где высоки риски. 
Преимущества спиральной модели: Большое внимание уделяется проработке рисков.
Недостатки спиральной модели: Есть риск застрять на начальном этапе — бесконечно совершенствовать первую версию продукта и не продвинуться к следующим. Разработка длится долго и стоит дорого.

На основе итеративной модели была создана Agile — не модель и не методология, а скорее подход к разработке.

<h2>Что такое Agile? </h2>
В классической модели waterfall каждая стадия начиналась после предыдущей без возврата назад и только в самом конце начиналось тестирование. Можно ли обеспечить качество, когда уже все готово? В книге «Как тестируют в Google» говорится, что QA не отвечает единолично за качество продукта, за это отвечает вся команда и в первую очередь разработчики.
В результате post-development тестирования создавалась иллюзия качественного продукта, но это не обеспечение качества, а скорее QC. Еще одним следствием следования каскадной модели являлось то, что команда старалась реализовать сразу все требования и к этапу тестирования выяснялось, что требуется много доделок/переделок и в результате релиз откладывался. Помимо прочего, пока разработчики писали код, тестировщики бездействовали. Безусловно, что-то писалось по требованиям и интуитивно, но смысл понятен. Нередко из-за срыва срока релизов сокращался срок, отводимый на тестирование, что также неблагоприятно сказывалось на итоговом качестве продукта.
Далее вместе с прогрессом пошла эволюция процессов SDLC и пришло понимание необходимости встраивания процессов обеспечения качества в жизненный цикл разработки продукта. Таким образом появлялись новые модели разработки и однажды группой энтузиастов был придуман Agile-манифест — основной документ, содержащий описание ценностей и принципов гибкой разработки программного обеспечения (4 ценности, 12 принципов):
Ценности:
<ol>
<li>Люди и взаимодействие важнее процессов и инструментов.
</li>
<li>Работающий продукт важнее исчерпывающей документации.
</li>
<li>Сотрудничество с клиентом важнее согласования условий контракта.
</li>
<li>Готовность к изменениям важнее следования первоначальному плану.
</li>
</ol>
Основные принципы:
<ol>
<li>Наивысшим приоритетом является удовлетворение потребностей клиента, благодаря регулярной и ранней поставке ценного программного обеспечения.
</li>
<li>Изменение требований приветствуется, даже на поздних стадиях разработки.
</li>
<li>Работающий продукт следует выпускать как можно чаще, с периодичностью от пары недель до пары месяцев.
</li>
<li>На протяжении всего проекта разработчики и представители бизнеса должны ежедневно работать вместе.
</li>
<li>Над проектом должны работать мотивированные профессионалы. Чтобы работа была сделана, создайте условия, обеспечьте поддержку и полностью доверьтесь им.
</li>
<li>Непосредственное общение является наиболее практичным и эффективным способом обмена информацией как с самой командой, так и внутри команды.
</li>
<li>Работающий продукт — основной показатель прогресса.
</li>
<li>Инвесторы, разработчики и пользователи должны иметь возможность поддерживать постоянный ритм бесконечно.
</li>
<li>Постоянное внимание к техническому совершенству и качеству проектирования повышает гибкость проекта.
</li>
<li>Простота — искусство минимизации лишней работы — крайне необходима.
</li>
<li>Самые лучшие требования, архитектурные и технические решения рождаются у самоорганизующихся команд.
</li>
<li>Команда должна систематически анализировать возможные способы улучшения эффективности и соответственно корректировать стиль своей работы.
</li>
</ol>
<img src="https://lh6.googleusercontent.com/Bc9PBiZVMc5Cpzx0eQz3iMGznuQOip1BsM_ewqATjkfMr1yrAx6Nqqp4fRHeTHgbtmjYWSRr2vHLBLL5sAqBloTf_TX6JDlf0AQVQlm7HBk_bs5LcPufuRQSaZjxt2eMKJxW3bSP">
Agile включает в себя практики, подходы и методологии, которые помогают создавать продукт более эффективно:
<ul>
<li>экстремальное программирование (Extreme Programming, XP);
</li>
<li>бережливую разработку программного обеспечения (Lean);
</li>
<li>фреймворк для управления проектами Scrum;
</li>
<li>разработку, управляемую функциональностью (Feature-driven development, FDD);
</li>
<li>разработку через тестирование (Test-driven development, TDD);
</li>
<li>методологию «чистой комнаты» (Cleanroom Software Engineering);
</li>
<li>итеративно-инкрементальный метод разработки (OpenUP);
</li>
<li>методологию разработки Microsoft Solutions Framework (MSF);
</li>
<li>метод разработки динамических систем (Dynamic Systems Development Method, DSDM);
</li>
<li>метод управления разработкой Kanban.
</li>
</ul>
Не все перечисленное в списке — методологии. Например, Scrum чаще называют не методологией, а фреймворком. В чем разница? Фреймворк — это более сформированная методология со строгими правилами. В скраме все роли и процессы четко прописаны. Помимо Scrum, часто используют Kanban. Сегодня это одна из наиболее популярных методологий разработки ПО. Команда ведет работу с помощью виртуальной доски, которая разбита на этапы проекта. Каждый участник видит, какие задачи находятся в работе, какие — застряли на одном из этапов, а какие уже дошли до его столбца и требуют внимания.
В отличие от скрама, в канбане можно взять срочные задачи в разработку сразу, не дожидаясь начала следующего спринта. Канбан удобно использовать не только в работе, но и в личных целях — распределять собственные планы или задачи семьи на выходные, наглядно отслеживать прогресс.
<img src="https://lh3.googleusercontent.com/nIEyu_kp0wQhOqFRXPJOD2GnygkXN8DGVOFw7TfwqedFlwFEF_0S5v2SGwvsIXRS5IpNToadGI6LKrfR4b6X65JL9iel_1AOTD4RcRMzYDuStEGYO1eWVtIzIuypKC7LYVGg2-iF">
(Красный – waterfall, синий – разработка по гибкой методологии)
Впоследствии был разработан отдельный Манифест тестирования в Agile:
<ul>
<li>постоянное тестирование, а не только в конце разработки
</li>
<li>предотвращение багов более значимо, чем их поиск
</li>
<li>понимание тестируемого продукта выше проверки функционала
</li>
<li>построение лучшей системы в связке с командой выше поиска методов ее сломать
</li>
<li>вся команда отвечает за качество, а не только тестировщик
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/otus/blog/533400/">10 примеров эффективного общения для тестировщиков</a>
</li>
<li> <a href="https://dzone.com/articles/a-brief-guide-to-testing-in-devops">A Brief Guide to Testing in DevOps</a>
</li>
<li><a href="https://www.youtube.com/watch?v=dHGq4ago09k&ab_channel=ITVDN">Как выживать тестировщику в Agile среде</a>
</li>
<li><a href="https://habr.com/ru/company/arcadia/blog/542974/">Стратегия тестирования краткосрочного проекта</a>
</li>
</ul>
<h2>Что такое Scrum? </h2>
Scrum – наиболее популярный Agile-подход, для многих людей согласно статистике эти термины являются синонимами. В целом о Scrum:
<ul>
<li>итеративно-инкрементальная разработка. Слово «итеративная» означает, что разработка разбивается на равные по длительности промежутки времени — спринты. Один спринт занимает от одной до четырех недель. Слово «инкрементальная» подразумевает, что в результате итерации получается новый, потенциально рабочий продукт, решающий бизнес-проблему. Такой продукт называется инкрементом продукта;
</li>
<li>самоорганизующаяся команда, в которой нет проектного менеджера;
</li>
<li>в команде присутствует SCRUM-master;
</li>
<li>в команде есть человек со стороны заказчиков — product owner, или владелец продукта;
</li>
<li>весь период разработки разбит на промежутки времени — спринты. Длина спринта устанавливается в начале проекта и меняется только в том случае, если всплывают неучтенные детали, мешающие уложиться в заданные рамки;
</li>
<li>задачи (функциональные требования, баги, правки заказчика и т.п.) формируют пул работ — бэклог. Изначально в него входят только требования заказчика;
</li>
<li>в начале спринта (и в любом его месте, если это нужно) проводится Backlog Grooming — обработка задач из бэклога. В результате получается проработанный бэклог на 2-3 будущих спринта. Затем PO и SCRUM-команда формулирует цель спринта и ожидаемый результат, и команда составляет бэклог спринта;
</li>
<li>после планирования спринта его состав стараются не менять. Если добавление новых задач все же происходит, то из спринта исключаются старые и сопоставимые по ценности задачи. Если эти изменения привели к смене цели спринта, то спринт отменяется и планируется заново;
</li>
<li>ежедневные короткие SCRUM-митинги. Они дают понять, как движется процесс, а команда в курсе того, идут ли они к цели спринта или нет;
</li>
<li>в конце спринта выполненные задачи либо подтверждаются, либо отклоняются и возвращаются в бэклог;
</li>
<li>по результатам спринта команда получает инкремент продукта.
</li>
</ul>

Роли:
<table>
<tr>
<td>Product Owner
</td><td>Scrum Master
</td><td>Команда
</td></tr>
<tr>
<td>определяет особенности продукта.
</td><td>управляет командой и заботится о продуктивности команды
</td><td>команда обычно состоит из 5-9 человек.
</td></tr>
<tr>
<td>определяет дату релиза и соответствующие функции
</td><td>поддерживает block список и устраняет барьеры в разработке
</td><td>в нее входят разработчики, дизайнер, а иногда и тестировщики и т. д. 
</td></tr>
<tr>
<td>устанавливает приоритеты функций в соответствии с рыночной стоимостью и прибыльностью продукта.
</td><td>координирует все роли и функции
</td><td>команда организует и планирует свою работу самостоятельно
</td></tr>
<tr>
<td>несет ответственность за прибыльность продукта
</td><td>защищает команду от внешних помех
</td><td>имеет право делать все в рамках проекта для достижения цели спринта
</td></tr>
<tr>
<td>может принять или отклонить результат задания
</td><td>приглашает на ежедневные разборы, обзор спринта и встречи по планированию
</td><td>активно участвуют в ежедневных церемониях
</td></tr>
</table>

На практике в скрам-тестировании успешность спринта - это когда все задачи, которые были добавлены в Scrum, оказались в статусе Done. Хотя много зависит от определения, что такое Done в вашем проекте. Скрам по своей сути это просто таймбокс для работ и если не уложились в сроки – то это проблема планирования и на ретроспективе нужно разобраться почему это произошло и зафиксировать на будущее.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/464861/">Мини-справочник и руководство по Scrum</a>
</li>
<li><a href="https://habr.com/ru/post/526822/">Scrum-мем на злобу дня</a>
</li>
</ul>
<h2>Какие вообще особенности у тестирования в Scrum?</h2>
Классика типа Савина или Канера повествует скорее о традиционных моделях (именно поэтому там уделено столько внимания дизайну, документированию, видам тестирования и т.п., т.к. на все это там есть время) но в гибких все значительно отличается. В гибкой методологии времени на разработку тест-кейсов низкого уровня и прочей документации обычно не бывает, поэтому подготавливаются чек-листы. Наборы проверок могут определяться как по не формализованным требованиям, так и на основе рисков (risk based). Ну и тестирование на основе экспертизы – самый простой подход к тестированию, но в то же время и самый рискованный, потому что все тестирование завязывается на экспертизу специалиста, выполняющего тестирование. В некоторых случаях мы все же можем формализовать Стратегию тестирования (порядок тестирования и подход к выполнению работ по тестированию ПО) и Тест-план (в кратком содержании для спринта не менее 2-х недель, при меньших сроках спринта ведение не актуально). Требования к документации в аджайл: она должна служить потребностям команды, живая документация ценнее архивной.
<img src="https://lh4.googleusercontent.com/atfuXIjFH9MUSpcmV-CqoytNQNqHI4yNO9sEKU2Kzfu3zLRxpkUItHX8oIBhIm2UWV4wZ0zWkGdEccMlsEvPyJ4uhhaR7z2CIZijqoj8CNhebwRe5gJtkJKwrr2KGtJpUD7IUNHm">

3+1 принципа тестирования в аджайл: предотвращение, автоматизация (авто QA - функциональное, приемочное. Devs - юнит, интеграция), гибкость, здравый смысл.
В agile user stories пишет Product Owner или Business Analyst. Кодеры по ним кодят, а тестировщики по ним тестят. ПО или БА к каждой ЮС будут писать критерии приемки, а тестировщики на основании их будут писать кейсы. При планировании спринта тестировщик должен выбрать пользовательскую историю из журнала невыполненных работ, которую следует протестировать. Как тестировщик, он / она должен решить, сколько часов (оценка усилий) потребуется, чтобы завершить тестирование для каждой из выбранных пользовательских историй. Как тестировщик , он / она должен знать, каковы цели спринта. В качестве тестировщика, внести свой вклад в процесс расстановки приоритетов. Тестировщик отвечает за разработку сценариев автоматизации. Он планирует автоматизированное тестирование с помощью системы непрерывной интеграции (CI). Автоматизация получает важность из-за коротких сроков доставки.Выполнение нефункционального тестирования для утвержденных пользовательских историй. Тестировщик взаимодействует с клиентом и владельцем продукта, чтобы определить критерии приемки для приемочных испытаний. В конце спринта тестировщик также проводит приемочное тестирование (UAT) в некоторых случаях и подтверждает полноту тестирования для текущего спринта. Узнать больше можно по ссылкам в теме "Ты – единственный тестировщик на проекте. Что делать?".

Доп. материал: 
<ul>
<li><a href="https://habr.com/ru/company/livetyping/blog/307860/">Тестирование в рамках SCRUM. Тернии, грабли и успехи</a>
</li>
<li><a href="https://habr.com/ru/company/miro/blog/505282/">QA-процесс в Miro: отказ от водопада и ручного тестирования, передача ответственности за качество всей команде</a>
</li>
<li><a href="https://habr.com/ru/company/yandex_praktikum/blog/543262/">Тесты должна писать разработка (?)</a>
</li>
<li><a href="https://webmisha.medium.com/%D0%BA%D0%B0%D0%BA-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%81%D1%82%D0%B8-%D1%80%D0%B5%D1%82%D1%80%D0%BE%D1%81%D0%BF%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D1%83-93124778247">Как провести ретроспективу</a>
</li>
<li><a href="https://www.mindfulqa.com/qa-sprint-planning/">The Role of QA in Sprint Planning</a>
</li>
</ul>
<h2>В чем отличие Kanban от Scrum?</h2>
В отличие от Scrum, в команде канбан отсутствуют роли владельца продукта и модератора, а процесс разработки делится не на универсальные спринты, а на стадии выполнения задач («Планируется», «Разрабатывается», «Тестируется», «Завершено»). Жизненный цикл задачи отображается на канбан-доске, физической или электронной. Такая визуализация делает рабочий процесс открытым и понятным для всех участников, что особенно важно в Agile, когда у команды нет одного формального руководителя. 
Канбан, как и другие практики бережливого производства, пришедшие из Японии, направлен на достижение баланса и выравнивание нагрузки исполнителей. Эффективность работы оценивается по среднему времени жизни задачи, от начальной до конечной стадии. Если задача прошла весь путь быстро, то команда проекта работала продуктивно и слаженно. Иначе – необходимо решать проблему: искать, где и почему возникли задержки и чью работу надо оптимизировать
<h2>Что знаете о User stories в гибких подходах к разработке?</h2>
Пользовательские истории (англ. User Story) - способ описания требований к разрабатываемой системе, сформулированных как одно или несколько предложений на повседневном или деловом языке пользователя. Пользовательские истории – это один из самых быстрых способов документирования требований клиента (цель документирования состоит в том, чтобы оперативно и без затрат реагировать на возникающие изменения).
Главное действующее лицо User story – это некий персонаж, который будет совершать какие-либо действия с нашим тестируемым продуктом с учетом его потребностей. Персонаж сопровождается описанием проблем, которые он может (и хочет) решить с помощью нашего продукта. Потребность представляет собой тезис в 1-2 предложения. Для одного пользователя может быть разработано несколько (например, 4-6) User Story.
Для того, чтобы персонажи стали эффективными инструментами проектирования сайта, потребуется не только провести исследование, но и выявить закономерности в поведении пользователей. Как правило, принято создавать и детально прорабатывать одного основного (как показано на mind-map ниже) и несколько второстепенных персонажей.
<img src="https://lh5.googleusercontent.com/yyhND6_MLksLyHFL5uy53AAz-8q69x4zVbbumXmY04gp60Ay5E_Wy4R4RdNYwLsn75GKE0TqDISUgJ7AJwHs9_4rwTWUzSVYOo0WmDYylXyXeR9po_nJsE6cOyqYMfziM6cFzj12">
<h2>Что значит жизненный цикл тестирования ПО? (STLC – Software Testing Lifecycle)</h2>
STLC это модель тестирования, которая предлагает выполнять тестирование систематическим и запланированным способом.

Модель STLC устанавливает следующие этапы:
<ul>
<li>Инициация,
</li>
<li>Выявление и анализ требований прямых и косвенных
</li>
<li>Планирование испытаний 
</li>
<li>Генерация Test case,
</li>
<li>Отбор показательных Test case,
</li>
<li>Настройка среды 
</li>
<li>Проведение проверок,
</li>
<li>Фиксация результатов,
</li>
<li>Анализ результатов,
</li>
<li>Передача информации о соответствии проверенного продукта требованиям.
</li>
</ul>

<ol>
<li>Инициация – событие, которое извещает команду тестирования о необходимости сессии тестирования

</li>
<li>Выявление требований (RA) – пожалуй, один из главных шагов в процессе тестирования. Необходимо собрать всю доступную информацию о предмете тестирования, вариантах использования и т. п. Первый источник – техническая документация и юзер-стори – это прямые требования. Если некоторые спецификации не являются точными или имеют разногласия, то заинтересованные стороны, такие как бизнес-аналитик (BA), архитекторы, клиенты, дают ясность. Качество же косвенных требований во многом зависят от добросовестности, ответственности, квалификации тестировщика и всей команды проекта.
</li>
<li>Планирование тестирования (TP) - Как правило, на этом этапе старший QA определяет усилия и смету расходов по проекту, а также готовит и завершает план тестирования. На этом этапе также определяется стратегия тестирования. Команда тестирования выполняет следующие задачи на этапе TP:
</li>
<ol>
<li>Подготовка плана тестирования / стратегии для различных типов тестирования 
</li>
<li>Выбор тестовых инструментов
</li>
<li>Оценка усилий 
</li>
<li>Планирование ресурсов и определение ролей и обязанностей. 
</li>
<li>Требования к обучению
</li>
<li>Расписание, критерии начала и окончания
</li>
<li>Оценка рисков
</li>
</ol>
</ol>

<ol>
<li>Генерация Test case – выявление всех возможных случаев использования продукта, его характеристик и особенностей в процессе эксплуатации. Это значит: всех случаев, которые тестировщик может «придумать» на основе прямых и косвенных требований, известных ему. Этот этап требует высокой квалификации специалиста по тестированию. При выполнении этой задачи также необходимо подготовить входные данные, необходимые для тестирования. Как только план тестирования будет готов, он должен быть рассмотрен Senior или Lead. Один из документов, который должна подготовить группа, - это матрица отслеживания требований (RTM). Это общеотраслевой стандарт, обеспечивающий правильное сопоставление тест-кейсов с требованиями. 
</li>
<li>Отбор Test case – отбор наиболее показательных, значимых и воспроизводимых Test case. От этого этапа зависит, насколько тестирование будет полезным, эффективным и анализируемым. Количество косвенных требований стремится к бесконечности, и проверять их все подряд – полный абсурд, но подобные кейсы должны быть сгенерированы хотя бы в голове проверяющего. 
</li>
<li>Настройка тестовой среды в STLC - Среда тестирования определяет условия программного и аппаратного обеспечения, при которых тестируется рабочий продукт. Настройка тестовой среды является одним из важнейших аспектов процесса тестирования и может выполняться параллельно с этапом разработки тестового набора. Команда тестирования может быть не вовлечена в это действие, если клиент / команда разработчиков предоставляет среду тестирования, и в этом случае команда тестирования должна выполнить проверку готовности (тестирование дыма) данной среды. Какие задачи выполняются на этапе настройки среды тестирования STLC? 
</li>
<ol>
<li>Ознакомление с необходимой архитектурой, настройка среды и подготовка требований к оборудованию и ПО для среды тестирования. 
</li>
<li>Настройка тестовой среды и тестовых данных 
</li>
<li>Выполнение Smoke тестирования
</li>
</ol>
<li>Проведение проверок – тут все понятно. На этом этапе команда запускает тестовые наборы в соответствии с планом тестирования, определенным в предыдущих шагах, либо adhoc (интуитивно, свободный поиск, без документации). В любом случае это проводится согласно списку отобранных проверок. 
</li>
<li>Фиксация результатов – создание внутренней и внешней тестовой документации в формализованном виде или в виде записей и т. п. На данном этапе отчет о тестировании даже если и создается, то не считается законченным.
</li>
<li>Анализ результатов – вынесение решения о соответствии проверенного продукта требованиям. Формализация данного решения и его обоснование в виде отчета о тестировании. Сюда также входят процедуры по оценке покрытия требований проверками, тайм-шитинг и пр. Таким образом, проводится анализ не только результатов, но и самой сессии тестирования.
</li>
<li>Передача информации о соответствии продукта требованиям. Формально: передача внешней тестовой документации заинтересованным в ней сторонам, зачастую инициатору сессии тестирования. В общем случае: помимо документации предоставляется информация о рисках, которые были выявлены в продукте, требованиях, процессах, передаются рекомендации по отработке этих рисков и т. п. 
</li>
</ol>

<h2>Что вы знаете о техниках оценки теста? (Test Estimation)</h2>
Оценка теста - это управленческая деятельность, которая приблизительно показывает, сколько времени потребуется для выполнения Задачи. Оценка усилий для теста является одной из основных и важных задач в управлении тестированием (Test Management). Что оценивается?
<ul>
<li>Ресурсы необходимы для выполнения любых задач проекта. Это могут быть люди, оборудование, средства, финансирование или что-то еще, что может быть определено для завершения деятельности по проекту. Время - самый ценный ресурс в проекте. Каждый проект имеет срок доставки. 
</li>
<li>Человеческие навыки означают знания и опыт членов Команды. Они влияют на вашу оценку. Например, команде, члены которой имеют низкие навыки тестирования, потребуется больше времени для завершения проекта, чем команде, обладающей высокими навыками тестирования. 
</li>
<li>Стоимость - это бюджет проекта. Вообще говоря, это означает, сколько денег нужно, чтобы закончить проект.
</li>
</ul>
<h2>В чем разница между SDLC и STLC?</h2>
<img src="https://lh3.googleusercontent.com/Lm29YMFKHfNgGPh0ATcuHYAzv6f2EXWHTXTcmbXkg6QkmVLUtORWMssfAIHgYwg0-8eN6wQTuSMH5DTUhvxQvJjV5tq89oL6PXHqUJEtbbi5TujPWXY8Rf0voOHDp--9kQxYHpod">
SDLC определяет все стандартные фазы, которые участвуют в процессе разработки ПО, тогда как процесс STLC определяет различные действия для улучшения качества продукта. SDLC - это жизненный цикл разработки, тогда как STLC - это жизненный цикл тестирования. В SDLC команда разработчиков создает планы проектирования высокого и низкого уровня, в то время как в STLC аналитик тестов создает Систему, План тестирования интеграции. В SDLC разрабатывается реальный код, и фактическая работа выполняется в соответствии с проектной документацией, тогда как в STLC команда тестирования готовит среду тестирования и выполняет тестовые примеры. Жизненный цикл SDLC помогает команде завершить успешную разработку ПО, в то время как фазы STLC охватывают только тестирование ПО. 
<h2>Что такое быстрая разработка приложений? (RAD - Rapid Application Development) </h2>
Быстрой разработкой приложений формально является параллельное развитие функций и последующей интеграции. Компоненты/функции развиваются параллельно, как если бы они были мини-проекты, события, time-boxed, доставлены и собраны в работающий прототип. Это может очень быстро дать клиенту что-то увидеть и использовать, и обеспечить обратную связь по поводу доставки и их требований. Быстрое изменение и развитие продукта возможно с помощью этой методики, однако спецификация продукта должна быть разработана для продукта в какой-то момент, и проект должен быть размещен под более формальный контроль перед запуском в производство.
<h2>Что такое разработка через тестирование (TDD - Test Driven Development)?</h2>
В традиционном подходе сначала пишут код, который затем покрывают тестами; в этом подходе сначала разрабатываются тесты, которые в будущем должны быть пройдены кодом. Разработчик будет писать код, пока тесты не начнут проходить. Разработка через тестирование начинается с проектирования и разработки тестов для каждой небольшой функциональности приложения. Также очевидно, в TDD вы получаете 100% покрытия кода тестами.
Есть два уровня TDD:
<ul>
<li>Acceptance TDD (ATDD): вы пишете один приемочный тест. Этот тест удовлетворяет требованиям спецификации или удовлетворяет поведению системы. После этого пишете достаточно производственного / функционального кода, чтобы выполнить этот приемочный тест. Приемочный тест фокусируется на общем поведении системы. ATDD также был известен как BDD - Behavioral Driven Development. 
</li>
<li>Developer TDD: вы пишете один тест разработчика, то есть модульный тест, а затем просто достаточно производственного кода для выполнения этого теста. Модульное тестирование фокусируется на каждой небольшой функциональности системы. Это называется просто TDD. Основная цель ATDD и TDD - определить подробные, выполнимые требования для вашего решения точно в срок (JIT). JIT означает принятие во внимание только тех требований, которые необходимы в системе, что повышает эффективность.
</li>
</ul>
<img src="https://lh4.googleusercontent.com/yVEfLTll1WVSb7yoW9Ybkfoku8bM9_AI81QMJU8BEuNrU3WsLgLP6-k2xPL6tNQVNMhdONeQ5N2hepClSy96v18rNzCHAvFSl13zwi0j_8Ein5tU5NDQlmQjrbPTnPCYC-JUOQz-">

<h2>Что такое Value Driven Testing (тестирование на основе ценности)?</h2>
Чтобы понять, как обстоят дела с тестированием на проекте, нужно проанализировать его эффективность с точки зрения качества создаваемого продукта и процессов. Тут можно рассчитывать плотность дефектов, разрывы, утечки, эффективность тест-кейсов, RC, FDP, DDP, PTC, MTTD, TDE и десятки других метрик тестирования. Но, чтобы определить рентабельность такого тестирования, необходимо считать деньги. Деньги и их возрастающий поток — основная цель заказчика в большинстве случаев разработки ПО.
Чтобы правильно принимать управленческие решения, тест-менеджеру необходимо в полной мере ориентироваться в себестоимости активностей по тестированию, видеть зоны развития и пути оптимизации процессов. Заказчику также важно понимать, за что он платит и почему, где он теряет, а где зарабатывает. Один в поле не воин, и задача так называемого архитектора постараться заставить пчел реально осознать, сколько денег они приносят заказчику, сколько помогли сэкономить. Сэкономленные деньги не обязательно, но могут формировать фонд для потенциального увеличения оплаты труда тех же пчел.
Цена и ценность
Любое качество имеет свою цену: Cost of Quality = Cost of Poor Quality + Cost of Good Quality:
<img src="https://lh5.googleusercontent.com/fdOoF1G7I6Eh9LXtaLFfD_78mtUj3cVrJ9NvFjAPOcmbqSuqg5rXYCzI-Uydq6ElMqDKXRp906d7hygu5EH7xyyrNT9zfSGRvunVjtpYsmhQXTvpGHQGipfLC_M66zxwrmki29_H">
Общая стоимость тестирования достаточно велика, но стоит лишь оценить стоимость плохого тестирования, как она уже кажется вполне приемлемой. Уоррен Баффет как-то сказал, что цена — это то, что вы платите, а ценность — то, что получаете. И не всегда они совпадают. Качество еще не означает ценность. Попробуйте сегодня продать очень качественную печатную машинку либо убедить заказчика, что для него ценнее будет зарелизить фичу не послезавтра, а через год, ведь за это время вы еще лучше все протестите и качество будет выше. Не получится. Дорога ложка к обеду, и time to market никто не отменял.
Задача в том, чтобы достичь оптимального соотношение цена/качество для заказчика. Почему оптимального? Потому что по мере увеличения затрат на поиск дефектов и их устранения стоимость поломки будет снижаться до тех пор, пока не будет достигнута оптимальная точка, после которой дальнейшее увеличение активностей по тестированию станет экономически нецелесообразным.
<img src="https://lh4.googleusercontent.com/ID91h2-_EcHSAfsIf6i9y2lwI2M--dxRE1RWCBJmaRB9YTCkjPaDdYHMS3TRY46veEll3VsQDfUTE7z7rQBeLuvXCwYJQvVLZhTaIJ3lUpy8JOsnQXJYqfvsXCnXy8_wmwI1qixK">
Источник: <a href="https://dou.ua/lenta/columns/value-driven-testing/">Что нужно знать о Value Driven Testing. Анализируем ценность и экономическую целесообразность тестирования</a>
<h2>TDD в Agile Model Driven Development (AMDD)</h2>
TDD очень хорош в детальной спецификации и валидации. Он не может продумать более важные вопросы, такие как общий дизайн, использование системы или пользовательский интерфейс. AMDD решает проблемы гибкого масштабирования, которых нет в TDD. Таким образом, AMDD используется для больших проблем.
Жизненный цикл AMDD:
<ul>
<li>Iteration 0: Envisioning
</li>
<li>Initial requirements envisioning.
</li>
<li>Initial Architectural envisioning.
</li>
<li>Iteration modeling.
</li>
<li>Model storming.
</li>
<li>Test Driven Development (TDD).
</li>
<li>Reviews.
</li>
</ul>
TDD сокращает цикл обратной связи программирования, AMDD сокращает цикл обратной связи моделирования. TDD - детальная спецификация, AMDD работает для больших проблем. TDD способствует разработке качественного кода, AMDD способствует качественному общению с заинтересованными сторонами и разработчиками. TDD общается с программистами, AMDD общается с бизнес-аналитиками, заинтересованными сторонами и специалистами по данным. TDD не визуально ориентированный, AMDD визуально ориентированный. TDD имеет ограниченную область применения, AMDD имеет широкий охват. Это предполагает работу по достижению общего понимания. Оба поддерживают эволюционное развитие.
<h2>Тестирование на основе моделей (MDD - Model-driven Development)</h2>
Это метод тестирования черного ящика, при котором поведение тестируемого программного обеспечения во время выполнения проверяется на основе прогнозов, сделанных моделями. Модель - это описание поведения системы. Поведение может быть описано в виде наглядной схемы, Data Flow, Control Flow, Dependency Graphs, Decision Tables, State transition machines или mind map. Простой аналогией модели в тестировании является электрическая схема при разработке электроприбора. Этот подход к тестированию требуется, когда высока цена ошибки в большом продукте и нужно как можно раньше попытаться ее предотвратить.

Доп. материал:
<a href="https://habr.com/ru/company/jugru/blog/506048/">Тестирование на основе моделей</a>
<h2>Тестирование на основе данных (DDT - Data Driven testing)</h2>
DATA DRIVEN testing - это инфраструктура автоматизации тестирования, которая хранит тестовые данные в виде таблицы. Это позволяет инженерам по автоматизации иметь единый сценарий тестирования, который может выполнять тесты для всех тестовых данных в таблице. В этой структуре входные значения считываются из файлов данных и сохраняются в переменную в тестовых сценариях. Ddt (тестирование на основе данных) позволяет объединять как положительные, так и отрицательные Test case в один тест. В среде автоматизации тестирования на основе данных входные данные могут храниться в одном или нескольких источниках данных, таких как xls, XML, csv и базы данных.
Часто у нас есть несколько наборов данных, на которых мы должны запускать одни и те же тесты. Создание отдельного теста для каждого набора данных - длительный и трудоемкий процесс. Data Driven testing Framework решает эту проблему, отделяя данные от функциональных тестов. Один и тот же сценарий тестирования может выполняться для различных комбинаций входных данных теста и генерировать результаты теста. Например, мы хотим протестировать вход в систему с несколькими полями ввода с 1000 различными наборами данных. Чтобы проверить это, вы можете использовать следующие разные подходы: Подход 1) Создайте 1000 сценариев по одному для каждого набора данных и запускайте каждый тест отдельно по одному. Подход 2) Вручную измените значение в тестовом скрипте и запустите его несколько раз. Подход 3) Импортируйте данные из листа Excel. Извлеките данные теста из строк Excel по очереди и выполните скрипт. В приведенных трех сценариях первые два являются слишком трудоемкими. Таким образом, идеально следовать третьему подходу и это не что иное, как Data-Driven Framework.
<h2>Тестирование на основе риска (RBT - Risk Based Testing)</h2>
ТЕСТИРОВАНИЕ НА ОСНОВЕ РИСКА (RBT) - это тип тестирования, основанный на вероятности риска. Он включает в себя оценку риска на основе сложности, критичности бизнеса, частоты использования, видимых областей, областей, подверженных дефектам, и т. д.  Он включает определение приоритетов тестирования модулей и функций тестируемого приложения на основе влияния и вероятности отказов. 
Риск - это возникновение неопределенного события, которое положительно или отрицательно влияет на измеримые критерии успеха проекта. Это могут быть события, которые произошли в прошлом или текущие события, или что-то, что может произойти в будущем. Эти неопределенные события могут повлиять на стоимость, бизнес, технические и качественные цели проекта. Позитивные риски упоминаются как возможности и помощь в устойчивости бизнеса. Например, инвестирование в новый проект, изменение бизнес-процессов, разработка новых продуктов. Отрицательные риски называются угрозами, и для успеха проекта должны быть реализованы рекомендации по их минимизации или устранению. 
Примерный чеклист:
<ul>
<li>Важные функциональные возможности в проекте. 
</li>
<li>Видимая пользователю функциональность в проекте 
</li>
<li>Функциональность, оказывающая наибольшее влияние на безопасность 
</li>
<li>Функциональные возможности, которые оказывают наибольшее финансовое влияние на пользователей 
</li>
<li>Сложные области исходного кода и кодов, подверженных ошибкам 
</li>
<li>Функции, которые могут быть проверены в начале цикла разработки. 
</li>
<li>Особенности или функциональные возможности, которые были добавлены в дизайн продукта в последнюю минуту. 
</li>
<li>Критические факторы подобных / связанных предыдущих проектов, которые вызвали проблемы. 
</li>
<li>Основные факторы или проблемы аналогичных / связанных проектов, которые оказали огромное влияние на эксплуатационные расходы. 
</li>
<li>Плохие требования, которые приводят к плохим проектам и тестам, которые могут повлиять на цели и результаты проекта. 
</li>
<li>В худшем случае продукт может быть настолько дефектным, что его невозможно переработать, и его необходимо полностью утилизировать, что может нанести серьезный ущерб репутации компании. Определите, какие проблемы имеют решающее значение для целей продукта. 
</li>
<li>Ситуации или проблемы, которые могут привести к постоянным жалобам на обслуживание клиентов. Сквозные тесты могут легко сфокусироваться на нескольких функциональных возможностях системы. Оптимальный набор тестов, которые могут максимизировать покрытие риска 
</li>
<li>Какие тесты будут иметь лучшее соотношение риска и требуемого времени?
</li>
</ul>

<h2>Что вы знаете о потоковом тестировании? (BFT — Business Flow Testing)</h2>
BFT – это подход к тестированию, где вы смотрите на продукт не с точки зрения конкретных кейсов, а с точки зрения поведения системы в каждой ее точке.
Подход является объединением таких концепций, как Data Driven testing и Behaviour Driven testing, примененным к бизнес-моделям, хорошо описываемым графами движения данных.
Вы не тестируете отдельные тест-кейсы, а проверяете работоспособность системы, тест-кейсы получаются сами по себе.
Образно говоря, у вас есть:
<ul>
<li>Набор разнообразных входных бизнес данных
</li>
<li>Система, разбитая на важные для тестирования состояния бизнес-сущностей, которые надо проверить
</li>
<li>Правила перехода между состояниями
</li>
</ul>
У вас нет тест-кейсов. Тест-кейсы генерируются на основании входных данных сами.
Больше не надо спорить, как назвать тест-кейсы правильно. Название тест-кейса – это набор определяющих его входных данных и путь, по которым они пройдут. Название получается длинное, но полностью описывающее данный тест. И к тому же вы не тратите на него ни секунды — оно создается само.
<h2>В чем разница между coupling и cohesion? </h2>
Это термины из принципов разработки ПО:
<ul>
<li>Связанность, сопряжение (coupling)— способ и степень взаимозависимости между программными модулями; сила взаимосвязей между модулями; мера того, насколько взаимозависимы разные подпрограммы или модули. Сильная связанность (High coupling) рассматривается как серьезный недостаток, поскольку затрудняет понимание логики модулей, их модификацию, автономное тестирование, а также переиспользование по отдельности.
</li>
<li>Связность, или прочность (cohesion) — мера силы взаимосвязанности элементов внутри модуля; способ и степень, в которой задачи, выполняемые некоторым программным модулем, связаны друг с другом.Считается, что объект (подсистема) обладает высокой связностью (High cohesion), если его обязанности хорошо согласованы между собой и он не выполняет огромных объемов работы.
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://medium.com/german-gorelkin/low-coupling-high-cohesion-d36369fb1be9">Low Coupling и High Cohesion</a>
</li>
<li><a href="https://habr.com/ru/post/38323/">ООП для ООП: GRASP</a>
</li>
</ul>

<h1>----- Тестирование в разных сферах/областях (testing different domains) -----</h1>
<h2>Что такое веб-тестирование и как его производить? </h2>
ВЕБ-ТЕСТИРОВАНИЕ, или тестирование веб-сайта, проверяет ваше веб-приложение или веб-сайт на наличие потенциальных ошибок, прежде чем оно будет опубликовано и доступно для широкой публики. 

1. Функциональное тестирование: используется для проверки того, соответствует ли ваш продукт спецификациям, а также функциональным требованиям, которые вы наметили для него в документации по разработке. Включает в себя: 

<ul>
<li>Проверка, что все ссылки на ваших веб-страницах работают правильно и что нет битых ссылок. 
</li>
<ul>
<li>Исходящие ссылки
</li>
<li>Внутренние ссылки 
</li>
<li>Якорные ссылки (слово или словосочетание, на котором поставлена ссылка)
</li>
<li>MailTo Ссылки 
</li>
</ul>
<li>Текстовые формы работают как положено. 
</li>
<ul>
<li>Проверка скриптов в форме работает как положено. Например, если пользователь не заполняет обязательное поле в форме, отображается сообщение об ошибке. 
</li>
<li>Проверьте значения по умолчанию 
</li>
<li>После отправки данные в формах отправляются в базу данных или связываются с рабочим адресом электронной почты. 
</li>
<li>Формы оптимально отформатированы для лучшей читаемости 
</li>
</ul>
<li>Тестовые куки работают как положено. Файлы cookie - это небольшие файлы, используемые веб-сайтами для запоминания активных пользовательских сессий, поэтому вам не нужно входить в систему каждый раз, когда вы посещаете веб-сайт. Тестирование файлов cookie будет включать 
</li>
<ul>
<li>Тестовые файлы cookie (сеансы) удаляются либо после очистки кэша, либо по истечении срока их действия. Удалите файлы cookie (сеансы) и проверьте, запрашиваются ли учетные данные при следующем посещении сайта. 
</li>
<li>Протестируйте HTML и CSS, чтобы поисковые системы могли легко сканировать ваш сайт. Это будет включать 
</li>
<ul>
<li>Проверка на синтаксические ошибки 
</li>
<li>Удобочитаемые цветовые схемы 
</li>
<li>Стандартное соответствие. Убедитесь, что соблюдаются такие стандарты, как W3C, OASIS, IETF, ISO, ECMA или WS-I. 
</li>
</ul>
</ul>
<li>Тест бизнес-воркфлоу - это будет включать в себя 
</li>
<ul>
<li>Тестирование вашего end-to-end workflow / бизнес-сценариев
</li>
<li>Также проверьте отрицательные сценарии, чтобы при выполнении пользователем неожиданного шага в веб-приложении отображалось соответствующее сообщение об ошибке или справка.
</li>
</ul>
<li>Примеры функциональных тест-кейсов: 
</li>
<ul>
<li>Все обязательные поля должны быть валидированы. 
</li>
<li>Звездочка должна отображаться для всех обязательных полей. 
</li>
<li>Не должно отображаться сообщение об ошибке для дополнительных полей. 
</li>
<li>Проверьте, что високосные годы проверены правильно и не вызывают ошибок. 
</li>
<li>Числовые поля не должны принимать буквы и должно отображаться соответствующее сообщение об ошибке. 
</li>
<li>Проверьте наличие отрицательных чисел, если это разрешено для числовых полей. 
</li>
<li>Тестовое деление на ноль должно быть правильно обработано. 
</li>
<li>Проверьте максимальную длину каждого поля, чтобы убедиться, что данные не усекаются. 
</li>
<li>Тест всплывающего сообщения («Это поле ограничено 500 символами») должно отображаться, если данные достигают максимального размера поля. 
</li>
<li>Проверьте, должно ли отображаться подтверждающее сообщение для операций обновления и удаления. 
</li>
<li>Величины должны быть в подходящем формате.
</li>
<li>Проверьте все поля ввода на ввод специальных символов. 
</li>
<li>Проверьте функциональность тайм-аута.
</li>
<li>Проверьте функциональность сортировок. 
</li>
<li>Проверьте, что FAQ и Политика конфиденциальности четко определены и доступны для пользователей. 
</li>
<li>Проверьте, все ли работает и не перенаправляется ли пользователь на страницу ошибки. 
</li>
<li>Все загруженные документы открываются правильно. 
</li>
<li>Пользователь должен иметь возможность скачать загруженные файлы. 
</li>
<li>Проверьте функциональность электронной почты системы. Тестируемый скрипт корректно работает в разных браузерах (IE, Firefox, Chrome, Safari и Opera). 
</li>
<li>Проверьте, что произойдет, если пользователь удалит файлы cookie, находясь на сайте. 
</li>
<li>Проверьте, что произойдет, если пользователь удалит файлы cookie после посещения сайта. 
</li>
</ul>
</ul>

2. Юзабилити-тестирование стало важной частью любого веб-проекта. Его могут провести тестировщики или небольшая фокус-группа, похожая на целевую аудиторию веб-приложения. 
<ul>
<li>Навигация: 
</li>
<ul>
<li>Меню, кнопки или ссылки на разные страницы вашего сайта должны быть легко видны и согласованы на всех веб-страницах. 
</li>
</ul>
<li>Проверьте содержимое: 
</li>
<ul>
<li>Содержание должно быть разборчивым, без орфографических или грамматических ошибок. 
</li>
<li>Изображения, если они присутствуют, должны содержать «альтернативный» текст
</li>
</ul>
<li>Примеры тестов юзабилити:
</li>
<ul>
<li>Содержание веб-страницы должно быть правильным без каких-либо орфографических или грамматических ошибок 
</li>
<li>Все шрифты должны быть в соответствии с требованиями. 
</li>
<li>Весь текст должен быть правильно выровнен. 
</li>
<li>Все сообщения об ошибках должны быть правильными без каких-либо орфографических или грамматических ошибок, а сообщение об ошибке должно соответствовать метке поля. 
</li>
<li>Текст подсказки должен быть там для каждого поля. 
</li>
<li>Все поля должны быть правильно выровнены. 
</li>
<li>Должно быть достаточно места между метками полей, столбцами, строками и сообщениями об ошибках. 
</li>
<li>Все кнопки должны быть в стандартном формате и размере. 
</li>
<li>Домашняя ссылка должна быть на каждой странице. 
</li>
<li>Отключенные поля должны быть недоступны. 
</li>
<li>Проверьте наличие битых ссылок и изображений. 
</li>
<li>Сообщение о подтверждении должно отображаться для любого вида операции обновления и удаления. Проверить сайт на разных разрешениях (640 х 480, 600х800 и т. д. ) 
</li>
<li>Убедитесь, что вкладка должна работать правильно. 
</li>
<li>Полоса прокрутки должна появляться только при необходимости. 
</li>
<li>Если при отправке появляется сообщение об ошибке, информация, заполненная пользователем, должна быть там. 
</li>
<li>Название должно отображаться на каждой веб-странице 
</li>
<li>Все поля (текстовое поле, раскрывающийся список, переключатель и т. д. ) И кнопки должны быть доступны с помощью сочетаний клавиш, и пользователь должен иметь возможность выполнять все операции с помощью клавиатуры. 
</li>
<li>Проверьте, не усекаются ли выпадающие данные из-за размера поля. 
</li>
<li>Также проверьте, жестко ли закодированы или управляются данные через администратора.
</li>
</ul>
</ul>

3. Тестирование интерфейсов: Здесь тестируются три области: приложение, веб-сервер и сервер базы данных. 
<ul>
<li>Приложение: тестовые запросы правильно отправляются в базу данных и вывод на стороне клиента отображается правильно. Ошибки, если таковые имеются, должны быть обнаружены приложением и должны отображаться только администратору, а не конечному пользователю. 
</li>
</ul>
<ul>
<li>Веб-сервер: тестовый веб-сервер обрабатывает все запросы приложений без какого-либо отказа в обслуживании. 
</li>
<li>Сервер базы данных: убедитесь, что запросы, отправленные в базу данных, дают ожидаемые результаты. Проверьте реакцию системы, когда невозможно установить соединение между тремя уровнями (Приложение, Интернет и База данных) и соответствующее сообщение отображается конечному пользователю.
</li>
</ul>

4. Тестирование базы данных: База данных является одним из важнейших компонентов вашего веб-приложения, и необходимо тщательно провести тестирование. Тестирование будет включать в себя: 
<ul>
<li>Проверьте, отображаются ли какие-либо ошибки при выполнении запросов 
</li>
<li>Целостность данных поддерживается при создании, обновлении или удалении данных в базе данных. 
</li>
<li>Проверьте время ответа на запросы. 
</li>
<li>Тестовые данные, полученные из вашей базы данных, точно отображаются в вашем веб-приложении.
</li>
</ul>

<ul>
<li>Примеры тест-кейсов для тестирования базы данных: 
</li>
<ul>
<li>Проверьте имя базы данных: имя базы данных должно соответствовать спецификациям. 
</li>
<li>Проверьте таблицы, столбцы, типы столбцов и значения по умолчанию: все должно соответствовать спецификациям. 
</li>
<li>Проверьте, допускает ли столбец null значение или нет. 
</li>
<li>Проверьте первичный и внешний ключ каждой таблицы. 
</li>
<li>Проверьте хранимую процедуру: 
</li>
<li>Проверьте, установлена ​​ли сохраненная процедура или нет. 
</li>
<li>Проверьте имя хранимой процедуры 
</li>
<li>Проверьте имена параметров, типы и количество параметров. 
</li>
<li>Проверьте требуемые параметры. 
</li>
<li>Проверьте хранимую процедуру, удалив некоторые параметры 
</li>
<li>Проверьте, когда выход равен нулю, это должно повлиять на нулевые записи. 
</li>
<li>Проверьте хранимую процедуру, написав простые запросы SQL. 
</li>
<li>Проверьте, возвращает ли хранимая процедура значения 
</li>
<li>Проверьте хранимую процедуру с образцами входных данных. 
</li>
<li>Проверьте поведение каждого флага в таблице. 
</li>
<li>Убедитесь, что данные правильно сохраняются в базе данных после каждой отправки страницы. 
</li>
<li>Проверьте данные, если выполняются операции DML (Обновить, удалить и вставить). 
</li>
<li>Проверьте длину каждого поля: длина поля на Frontend и backend должна быть одинаковой. 
</li>
<li>Проверьте имена баз данных QA, UAT и production. Имена должны быть уникальными. 
</li>
<li>Проверьте зашифрованные данные в базе данных. 
</li>
<li>Проверьте размер базы данных. 
</li>
<li>Также проверьте время ответа каждого выполненного запроса. 
</li>
<li>Проверьте данные, отображаемые на Frontend, и убедитесь, что они совпадают с backend. 
</li>
<li>Проверьте достоверность данных, вставив неверные данные в базу данных. 
</li>
<li>Проверьте триггеры.
</li>
</ul>
</ul>

5. Тестирование на совместимость. Тесты на совместимость гарантируют, что ваше веб-приложение правильно отображается на разных устройствах. 
<ul>
<li>Вам нужно проверить, правильно ли отображается ваше веб-приложение в браузерах, работает ли JavaScript, AJAX и аутентификация нормально. Вы также можете проверить совместимость мобильного браузера. Рендеринг веб-элементов, таких как кнопки, текстовые поля и т. д. , изменяется с изменением в операционной системе. Убедитесь, что ваш сайт работает нормально для различных комбинаций операционных систем, таких как Windows, Linux, Mac и браузеров, таких как Firefox, Internet Explorer, Safari и т. д. 
</li>
<li>Примеры тестов на совместимость: 
</li>
<ul>
<li>Протестируйте сайт в разных браузерах (IE, Firefox, Chrome, Safari и Opera) и убедитесь, что сайт отображается правильно. 
</li>
<li>Используемая версия HTML совместима с соответствующими версиями браузера. 
</li>
<li>Проверьте правильность отображения изображений в разных браузерах. 
</li>
<li>Протестируйте шрифты, которые можно использовать в разных браузерах. 
</li>
<li>Протестируйте код Javascript в разных браузерах. 
</li>
<li>Проверьте анимированные GIF-файлы в разных браузерах.
</li>
</ul>
</ul>

6. Тестирование производительности: Это нужно, чтобы обеспечить работу вашего сайта при любых нагрузках. Деятельность по тестированию ПО будет включать, но не ограничиваться: 
<ul>
<li>Время отклика приложения сайта на разных скоростях соединения 
</li>
<li>Нагрузочное тестирование вашего веб-приложения, чтобы определить его поведение при нормальной и пиковой нагрузке. 
</li>
<li>Стресс-тест вашего веб-сайта, чтобы определить его точку остановки при превышении нормальных нагрузок в пиковое время. 
</li>
<li>Проверьте, происходит ли сбой из-за пиковой нагрузки, как сайт восстанавливается после такого события, убедитесь, что методы оптимизации, такие как сжатие gzip и кэш включены, чтобы сократить время загрузки
</li>
</ul>

7. Тестирование безопасности жизненно важно для сайта электронной коммерции, который хранит конфиденциальную информацию о клиентах, например, кредитные карты. Деятельность по тестированию будет включать: 
<ul>
<li>Проверка несанкционированного доступа к защищенным страницам
</li>
<li>Запрещенные файлы не должны быть загружаемыми без соответствующего доступа 
</li>
<li>Сессии автоматически прекращаются после длительного отсутствия активности пользователя 
</li>
<li>При использовании SSL-сертификатов веб-сайт должен перенаправить на зашифрованные SSL-страницы.
</li>
</ul>

<ul>
<li>Примеры тестовых сценариев для тестирования безопасности: 
</li>
<ul>
<li>Убедитесь, что веб-страница, содержащая важные данные, такие как пароль, номера кредитных карт, секретные ответы на секретный вопрос и т. д. , Должна быть отправлена ​​через HTTPS (SSL). 
</li>
<li>Убедитесь, что важная информация, такая как пароль, номера кредитных карт и т. д. , Должна отображаться в зашифрованном виде. 
</li>
<li>Правила проверки пароля применяются на всех страницах аутентификации, таких как Регистрация, забытый пароль, смена пароля. 
</li>
<li>Убедитесь, что, если пароль изменен, пользователь не должен иметь возможность войти со старым паролем. Убедитесь, что сообщения об ошибках не должны отображать важную информацию. 
</li>
<li>Убедитесь, что, если пользователь вышел из системы или сеанс пользователя истек, пользователь не должен перемещаться по сайту авторизованным.
</li>
<li>Проверьте доступ к защищенным и незащищенным веб-страницам напрямую без входа в систему. 
</li>
<li>Убедитесь, что опция «Просмотр исходного кода» отключена и не должна быть видна пользователю. Убедитесь, что учетная запись пользователя заблокирована, если пользователь вводит неправильный пароль несколько раз. 
</li>
<li>Убедитесь, что куки не должны хранить пароли. 
</li>
<li>Убедитесь, что, если какая-либо функция не работает, система не должна отображать информацию о приложении, сервере или базе данных. Вместо этого она должна отображать пользовательскую страницу ошибки. 
</li>
<li>Проверьте атаки SQL-инъекций. 
</li>
<li>Проверьте роли пользователей и их права. Например, запрашивающая сторона не должна иметь доступа к странице администратора. 
</li>
<li>Убедитесь, что важные операции записаны в файлы журналов, и эта информация должна быть отслеживаемой. 
</li>
<li>Убедитесь, что значения сеанса находятся в зашифрованном формате в адресной строке. 
</li>
<li>Убедитесь, что информация о файлах cookie хранится в зашифрованном формате. 
</li>
<li>Проверьте приложение на брутфорс-атаки
</li>
</ul>
</ul>

8. Тестирование толпы (Crowd Testing): Вы берете большое количество людей (толпу) для выполнения тестов, которые в противном случае были бы выполнены выбранной группой людей в компании. Краудсорсинговое тестирование представляет собой интересную и перспективную концепцию и помогает выявить многие незамеченные дефекты. Оно включает в себя практически все типы тестирования, применимые к вашему веб-приложению. 
<h2>Тестирование банковского ПО</h2>
Сектор BFSI (банковские, финансовые услуги и страхование) является крупнейшим потребителем ИТ-услуг. Банковские приложения напрямую связаны с конфиденциальными финансовыми данными. Обязательно, чтобы все операции, выполняемые банковским программным обеспечением, выполнялись без сбоев и ошибок. Банковское ПО выполняет различные функции, такие как перевод и внесение средств, запрос баланса, история транзакций, вывод средств и так далее. Тестирование банковского приложения гарантирует, что эти действия не только хорошо выполняются, но и остаются защищенными от хакеров. 
Важно отметить стандартные функции, ожидаемые от любого банковского приложения:
<ul>
<li>Оно должно поддерживать тысячи одновременных пользовательских сессий 
</li>
<li>Банковское приложение должно интегрироваться с другими многочисленными приложениями, такими как торговые счета, утилита оплаты счетов, кредитные карты и т. д. 
</li>
<li>Должно обрабатывать быстрые и безопасные транзакции 
</li>
<li>Оно должно включать в себя массивную систему хранения. 
</li>
<li>Для устранения проблем с клиентами у него должна быть высокая возможность аудита 
</li>
<li>Оно должен обрабатывать сложные бизнес-процессы 
</li>
<li>Нужно поддерживать пользователей на разных платформах (Mac, Linux, Unix, Windows) 
</li>
<li>Оно должно поддерживать пользователей из разных мест и на разных языках
</li>
<li>Поддерживать пользователей в различных платежных системах (VISA, AMEX, MasterCard) 
</li>
<li>Оно должно поддерживать несколько секторов обслуживания (кредиты, розничные банковские операции и т. д.) 
</li>
<li>Иметь механизм защиты от катастрофических сбоев
</li>
</ul>

<h2>Тестирование электронной коммерции (eCommerce)</h2>
Тестирование электронной коммерции помогает в предотвращении ошибок и повышает ценность продукта, обеспечивая соответствие требованиям клиента. Целями тестирования являются: 
<ul>
<li>Обеспечение надежности и качества ПО 
</li>
<li>Уверенность в системе
</li>
<li>Оптимальная производительность
</li>
</ul>
Настройка системы электронной коммерции является сложным процессом и зависит от множества рыночных переменных. Для поддержания целостности системы электронной коммерции тестирование становится обязательным. Что проверяется:
<ul>
<li>Совместимость браузера:
</li>
<ul>
<li>Поддержка для старых браузеров 
</li>
<li>Специальные браузерные расширения 
</li>
<li>Тестирование браузера должно охватывать основные платформы (Linux, Windows, Mac и т. д. ) 
</li>
</ul>
<li>Отображение страниц: 
</li>
<ul>
<li>Некорректное отображение страниц 
</li>
<li>Сообщения об ошибках во время выполнения 
</li>
<li>Плохое время загрузки страницы 
</li>
<li>Битые ссылки, зависимость от плагина, размер шрифта и т. д. 
</li>
</ul>
<li>Управление сессиями 
</li>
<ul>
<li>Истечение сессии 
</li>
<li>Хранение сессии 
</li>
</ul>
<li>Удобство и простота 
</li>
<ul>
<li>Неинтуитивный дизайн 
</li>
<li>Плохая навигация по сайту 
</li>
<li>Навигация по каталогам 
</li>
<li>Отсутствие помощи-поддержки 
</li>
</ul>
<li>Анализ содержимого 
</li>
<ul>
<li>Вводящий в заблуждение, оскорбительный или незаконный контент 
</li>
<li>Роялти-фри изображения и нарушение авторских прав 
</li>
<li>Функциональность персонализации 
</li>
<li>Доступность 24/7 
</li>
</ul>
<li>Доступность
</li>
<ul>
<li>Атаки отказа в обслуживании 
</li>
<li>Неприемлемые уровни недоступности 
</li>
</ul>
<li>Резервное копирование и восстановление 
</li>
<ul>
<li>Сбой или отказ восстановления 
</li>
<li>Ошибка резервного копирования 
</li>
<li>Отказоустойчивость 
</li>
</ul>
<li>Операции 
</li>
<ul>
<li>Целостность транзакции 
</li>
<li>Пропускная способность 
</li>
<li>Аудит
</li>
</ul>
<li>Обработка заказов на покупку и покупка 
</li>
<ul>
<li>Функциональность корзины 
</li>
<li>Обработка заказов 
</li>
<li>Процесс оплаты 
</li>
<li>Отслеживание заказа 
</li>
</ul>
<li>Интернационализация 
</li>
<ul>
<li>Языковая поддержка 
</li>
<li>Отображение языков
</li>
<li>Культурная чувствительность 
</li>
<li>Региональный учет 
</li>
</ul>
<li>Оперативные бизнес-процедуры 
</li>
<ul>
<li>Насколько хорошо справляется электронная процедура 
</li>
<li>Наблюдение за узкими местами 
</li>
</ul>
<li>Системная интеграция 
</li>
<ul>
<li>Формат интерфейса данных 
</li>
<li>Обновления 
</li>
<li>Величина нагрузки интерфейса 
</li>
<li>Интегрированная производительность 
</li>
</ul>
<li>Производительность 
</li>
<ul>
<li>Узкие места производительности 
</li>
<li>Обработка нагрузки 
</li>
<li>Анализ масштабируемости 
</li>
</ul>
<li>Логин и безопасность 
</li>
<ul>
<li>Возможность входа 
</li>
<li>Проникновение и контроль доступа 
</li>
<li>Небезопасная передача информации 
</li>
<li>Веб-атаки 
</li>
<li>Компьютерные вирусы 
</li>
<li>Цифровые подписи
</li>
</ul>
</ul>

Тестирование производительности - главный приоритет в электронной коммерции. Просто задержите около 250 миллисекунд времени загрузки страницы – и это заставляет вашего клиента идти к вашему конкуренту. Гигант розничной торговли Walmart пересмотрел скорость своего сайта и заметил увеличение на 2% коэффициента конверсии посетителей и доходов на 1%. Эффективность вашего сайта зависит от этих факторов:
<ul>
<li>Пропускная способность (Throughput):
</li>
<ul>
<li>Запросов в секунду 
</li>
<li>Транзакций в минуту
</li>
<li>Выполнений за клик 
</li>
</ul>
<li>Время отклика (Response Time): 
</li>
</ul>
<ul>
<li>Длительность задачи 
</li>
<li>Секунд на клик 
</li>
<li>Загрузка страницы 
</li>
<li>DNS Lookup 
</li>
<li>Продолжительность времени между кликом и просмотром страницы
</li>
</ul>

<h2>Тестирование платежного шлюза (Payment Gateway)</h2>
Платежный шлюз - это сервис приложений электронной коммерции, который принимает оплату кредитной картой для покупок в Интернете. Платежные шлюзы защищают данные кредитной карты, шифруя конфиденциальную информацию, такую ​​как номера кредитных карт, данные владельца счета и так далее. Эта информация безопасно передается между покупателем и продавцом, и наоборот. Современные платежные шлюзы также надежно подтверждают платежи с помощью дебетовых карт, электронных банковских переводов, банковских карт, бонусных баллов и т. д. 
Типы платежных систем:
<ul>
<li>Собственный местный платежный шлюз: Хостинговая система шлюзов платежей направляет клиента от сайта электронной коммерции к шлюзу во время процесса оплаты. Как только платеж будет выполнен, он вернет клиента на сайт электронной коммерции. Для такого типа оплаты вам не нужен идентификатор продавца, например, хостинговый платежный шлюз - PayPal, Noche и WorldPay. 
</li>
<li>Shared (встраиваемый у партнеров) платежный шлюз: В разделяемом платежном шлюзе при обработке платежа клиент направляется на страницу оплаты и остается на сайте электронной коммерции. Как только реквизиты платежа заполнены, процесс оплаты продолжается. Поскольку он не покидает сайт электронной коммерции во время обработки платежа, этот режим прост и, более предпочтителен, примером шлюза с общими платежами является eWay, Stripe.
</li>
</ul>

Тестирование для Платежного шлюза должно включать:
<ul>
<li>Функциональное тестирование: это тестирование базовой функциональности платежного шлюза. Оно предназначено для проверки того, ведет ли себя приложение ожидаемым образом при обработке заказов, расчетах, добавлении НДС в зависимости от страны и т. д. 
</li>
<li>Интеграция: Проверьте интеграцию с вашей кредитной картой. 
</li>
<li>Производительность. Определите различные показатели производительности, такие как максимально возможное количество пользователей, проходящих через шлюзы в течение определенного дня, и конвертирующих их в одновременных пользователей. 
</li>
<li>Безопасность: вам необходимо выполнить глубокую проверку безопасности для Платежного шлюза
</li>
</ul>

Примеры тест-кейсов для тестирования платежного шлюза:
<ul>
<li>В процессе оплаты попробуйте изменить язык платежного шлюза. 
</li>
<li>После успешной оплаты проверьте все необходимые компоненты
</li>
<li>Проверьте, что произойдет, если платежный шлюз перестанет отвечать во время оплаты 
</li>
<li>В процессе оплаты проверьте, что произойдет, если сессия заканчивается 
</li>
<li>В процессе оплаты проверьте, что происходит в бэкэнде 
</li>
<li>Проверьте, что произойдет, если процесс оплаты не удастся 
</li>
<li>Проверьте записи базы данных, хранят ли они данные кредитной карты или нет 
</li>
<li>В процессе оплаты проверяйте страницы ошибок и страницы безопасности 
</li>
<li>Проверьте при наличии блокировщика всплывающих окон 
</li>
<li>Между платежным шлюзом и страницами проверьте буферные страницы.
</li>
<li>Проверка успешной оплаты, код успеха отправляется в приложение и пользователю отображается страница подтверждения 
</li>
<li>Убедитесь, что транзакция обрабатывается немедленно или обработка передана вашему банку. 
</li>
<li>После успешной транзакции проверьте, возвращается ли платежный шлюз в ваше приложение. 
</li>
<li>Проверьте все форматы и сообщения при успешном процессе оплаты 
</li>
<li>Если у вас нет квитанции об авторизации от платежного шлюза, товар не должен быть отправлен 
</li>
<li>Сообщите владельцу о любой транзакции, обработанной по электронной почте. Шифровать содержимое почты.
</li>
<li>Проверьте формат суммы с форматом валюты 
</li>
<li>Проверьте, доступен ли каждый из вариантов оплаты 
</li>
<li>Проверьте, открывает ли каждый перечисленный способ оплаты соответствующий способ оплаты в соответствии со спецификацией. 
</li>
<li>Убедитесь, что в платежном шлюзе по умолчанию выбран нужный вариант дебетовой / кредитной карты.
</li>
<li>Проверьте опцию по умолчанию для дебетовых карт - показывает выпадающее меню выбора карты
</li>
</ul>
<h2>Тестирование систем розничной торговли (POS - Point Of Sale)</h2>
POS-тестирование определяется как тестирование приложения в точках продаж. ПО POS или Point Of Sale - это жизненно важное решение для предприятий розничной торговли, позволяющее легко совершать розничные транзакции из любого места. Вы, наверное, видели терминал торговой точки в своем любимом торговом центре. Система является более сложной, чем вы думаете, и тесно интегрирована с другими программными системами, такими как Склад, Инвентарь, Заказ на поставку, Цепочка поставок, Маркетинг, Планирование товаров и т. д.  Знание предметной области POS важно для тестирования.
Оценка POS-системы может быть разбита на два уровня: 
<ul>
<li>Уровень применения (Application Level)
</li>
<li>Уровень предприятия (Enterprise Level)
</li>
</ul>

<table>
<tr>
<td>Сценарий
</td><td>Кейсы
</td></tr>
<tr>
<td>Деятельность кассира
</td><td><ul>
<li>Проверьте правильность ввода товаров, приобретенных клиентом 
</li>
<li>Тестовые скидки применяются правильно 
</li>
<li>Убедитесь, что платежные карты магазина (value cards) могут быть использованы 
</li>
<li>Управление мелочью работает как положено 
</li>
<li>Проверьте соответствие итогов и закрытия 
</li>
<li>Убедитесь, что денежный ящик кассы работает правильно
</li>
<li>Проверьте, что система POS совместима с периферийными устройствами, такими как считыватель RFID, сканер штрих-кода и т. д. 
</li>
</ul>
</td></tr>
<tr>
<td>Обработка платежного шлюза
</td><td><ul>
<li>Проверка правильности CVV кредитных карт
</li>
<li>Тест на использование карт с обеих сторон
</li>
<li>Убедитесь, что данные карты правильно зашифрованы и расшифрованы
</li>
</ul>
</td></tr>
<tr>
<td>Продажи
</td><td><ul>
<li>Проверьте для обычного процесса продажи 
</li>
<li>Продажи могут быть обработаны дебетовой / кредитной картой 
</li>
<li>Проверить покупку по карте лояльности
</li>
<li>Проверка правильности отображаемой цены для покупаемых товаров 
</li>
<li>Тест для "0" или нулевой транзакции 
</li>
<li>Привязка UPC или штрих-кодов с поставщиками 
</li>
<li>Проверка платежных данных или данных о доставке в диспетчере платежей 
</li>
<li>Тест для reference транзакции 
</li>
<li>Проверьте формат печати сгенерированной квитанции 
</li>
<li>Убедитесь, что для утвержденных, удержанных или отклоненных транзакций создан правильный код
</li>
</ul>
</td></tr>
<tr>
<td>Сценарии возврата и обмена
</td><td><ul>
<li>Убедитесь, что внутренняя опись хорошо интегрирована с другими торговыми точками или цепочкой поставок 
</li>
<li>Чек на обмен или возврат товара наличными 
</li>
<li>Проверьте, работает ли система при обмене или возврате товара с помощью кредитной карты 
</li>
<li>Проверка системы обработки продажи с чеком или без чека 
</li>
<li>Убедитесь, что система должна позволять вводить штрих-код вручную, если сканер не работает 
</li>
<li>Убедитесь, что система отображает как текущую сумму, так и сумму скидки при обмене товара, если применимо
</li>
</ul>
</td></tr>
<tr>
<td>Производительность
</td><td><ul>
<li>Проверьте скорость или время, необходимое для получения ответа или отправки запроса 
</li>
<li>Проверьте, применяются ли правила транзакций (скидки / налоги и т. д.) 
</li>
<li>Убедитесь, что для утвержденных, удержанных или отклоненных транзакций создан правильный код
</li>
</ul>
</td></tr>
<tr>
<td>Негативные сценарии
</td><td><ul>
<li>Тестовая система с просроченными данными карты 
</li>
<li>Тест с неверным PIN-кодом для кредитной карты 
</li>
<li>Проверьте инвентарь, введя неправильный код товара 
</li>
<li>Проверьте, как система реагирует при вводе неверного номера счета 
</li>
<li>Тест на отрицательную транзакцию 
</li>
<li>Проверьте ответ системы при вводе недопустимой даты для рекламных предложений онлайн-товаров
</li>
</ul>
</td></tr>
<tr>
<td>Управление акциями и скидками
</td><td><ul>
<li>Проверка: система для различных скидок, таких как ветеранская скидка, сезонная скидка, скидка на покупку или перелет и т. д. 
</li>
<li>Проверка: система для различных рекламных предложений по отдельным позициям 
</li>
<li>Проверка: система оповещений, которая уведомляет об окончании или начале сезонных предложений 
</li>
<li>Проверьте, распечатывает ли квитанция точную скидку или предложения, которые используются 
</li>
<li>Проверка: система для определения неправильных предложений или скидок на товары онлайн 
</li>
<li>Протестируйте процесс управления заказами 
</li>
<li>Убедитесь, что данные продукта, полученные после сканирования штрих-кода, являются точными
</li>
</ul>
</td></tr>
<tr>
<td>Отслеживание данных клиента
</td><td><ul>
<li>Проверка ответа системы с неверным вводом данных клиента 
</li>
<li>Проверка: система для разрешения авторизованного доступа к конфиденциальным данным клиента 
</li>
<li>Протестируйте базу данных для записи истории покупок клиента (что он покупает, как часто он покупает и т. д. )
</li>
</ul>
</td></tr>
<tr>
<td>Безопасность и соответствие нормативным требованиям
</td><td><ul>
<li>Проверка системы POS на соответствие нормативным требованиям 
</li>
<li>Проверка: система оповещения -> security defenders
</li>
<li>Убедитесь, что вы можете аннулировать платеж перед отправкой 
</li>
<li>Тестируйте профили пользователей и уровни доступа в POS Software 
</li>
<li>Проверка согласованности базы данных 
</li>
<li>Проверьте конкретную информацию о каждой наличности, идентификатор купона, номер чека и т. д. 
</li>
</ul>
</td></tr>
<tr>
<td>Тестирование отчетности
</td><td><ul>
<li>Тестирование отчета по анализу трендов 
</li>
<li>Тестовая информация, связанная с транзакцией по кредитной карте, должна быть отражена в отчетах 
</li>
<li>Тест для отдельных, а также сводные отчеты истории покупок клиентов
</li>
<li>Тест для генерации онлайн отчетов
</li>
</ul>
</td></tr>
</table>

<h2>Тестирование в сфере страхования (Insurance)</h2>
Страховые компании в значительной степени полагаются на ПО для ведения своего бизнеса. Программные системы помогают им заниматься различными видами страховой деятельности, такими как разработка стандартных форм полисов, обработка процесса выставления счетов, управление данными клиента, оказание качественных услуг клиенту, координация между филиалами и так далее. Хотя это ПО разработано с учетом ожиданий заказчика, его надежность и согласованность должны быть проверены перед его фактическим внедрением. Тестирование ПО гарантирует качество страхового ПО, выявляя ошибки перед запуском. 
Страхование определяется как справедливая передача риска убытков от одного субъекта другому в обмен на платеж. Страховая компания, которая продает полис, называется СТРАХОВОЙ, а лицо или компания, которая использует полис, называется ЗАСТРАХОВАННЫЙ. Страховые полисы обычно делятся на две категории, и страховщик покупает эти полисы в соответствии с их требованиями и бюджетом. Тем не менее, есть другие виды страхования, которые подпадают под эти категории: 
<ul>
<li>Страхование по безработице (Unemployment insurance)
</li>
<li>Социальное обеспечение (Social Security)
</li>
<li>Компенсация рабочим (Workers Compensation)
</li>
</ul>
Есть много ветвей в страховой компании, которые требуют тестирования: 
<ul>
<li>Системы администрирования политики (Policy Administration Systems)
</li>
<li>Системы управления претензиями (Claim Management Systems)
</li>
<li>Системы управления распределением (Distribution Management Systems)
</li>
<li>Системы управления инвестициями (Investment Management Systems)
</li>
<li>Сторонние системы администрирования (Third party Administration Systems)
</li>
<li>Решения по управлению рисками (Risk Management Solutions)
</li>
<li>Регулирование и соответствие (Regulatory and Compliance)
</li>
<li>Актуарные системы (Оценка и ценообразование) (Actuarial Systems (Valuation & Pricing))
</li>
</ul>
Сектор страхования представляет собой сеть небольших подразделений, которая прямо или косвенно занимается обработкой требований. Для бесперебойного функционирования страховой компании необходимо, чтобы каждое из этих подразделений было тщательно проверено для достижения желаемого результата. Тестирование включает в себя: 
<ul>
<li>Колл-центр (Call Center): 
</li>
<ul>
<li>Интеграционное тестирование IVR (IVR <a href="https://www.guru99.com/integration-testing.html">Integration testing</a>)
</li>
<li>Маршрутизация и назначение вызовов (Call routing and assignment)
</li>
<li>Безопасность и доступ (Security and access)
</li>
<li>Рефлексивные вопросы (Reflexive Questions)
</li>
</ul>
<li>Политика обслуживания (Policy Serving):
</li>
<ul>
<li>Тестирование жизненного цикла политики (Policy life cycle testing)
</li>
<li>Изменения в финансовой и нефинансовой политике (Financial and Non-financial policy changes)
</li>
<li>Политика недействительности и восстановления (Policy lapse and Re-instatement)
</li>
<li>Оповещения о страховых выплатах (Premium due alerts)
</li>
<li>Оценка NPV/NAV (Valuation of NPV/NAV)
</li>
</ul>
<li>Претензии (Claims):
</li>
<ul>
<li>Сортировка и уступка требований (Claims triage and assignment)
</li>
<li>Тестирование жизненного цикла претензий (Testing claims life cycle)
</li>
<li>Учет требований / резервирование (Claims accounting/reserving)
</li>
<li>EDI / обмен сообщениями от третьих лиц (Third party EDI/messaging)
</li>
</ul>
<li>Прямой канал (Direct channel):
</li>
<ul>
<li>Мобильный доступ (Mobile access)
</li>
<li>Кросс-браузерность / кроссплатформенность (Cross browser/cross platform accessibility)
</li>
<li>Производительность приложения (Application performance)
</li>
<li>Удобство использования приложения (Usability of application)
</li>
</ul>
<li>Отчеты / BI (Reports/BI):
</li>
<ul>
<li>Соблюдение нормативных требований (Behaving to regulatory requirements)
</li>
<li>Генерация качественных данных для отчетности (Generate quality data for reporting)
</li>
<li>Создание массовых данных для сводных отчетов (Create bulk data for roll-up reports)
</li>
<li>Тестирование полей на основе формул в отчетах (Testing formula based fields in reports)
</li>
</ul>
<li>Андеррайтинг (Underwriting):
</li>
<ul>
<li>Качество андеррайтинга (Underwriting quality)
</li>
<li>Ручная и прямая обработка (Manual and Straight through processing)
</li>
<li>Сложные бизнес-правила (Complex business rules)
</li>
<li>Рейтинг эффективности (Rating efficiency)
</li>
<li>Управление требованиями (Vendor Interfacing) (Requirements Management)
</li>
</ul>
<li>Интеграция (Integration):
</li>
<ul>
<li>Интеграция данных (Data integration)
</li>
<li>Комплексная интеграция интерфейса (Complex interface integration)
</li>
<li>Форматы источника / назначения (Source/Destination formats)
</li>
<li>Производственный интерфейс (Production like interface)
</li>
<li>Эффективность пулла/пуша веб-сервиса (Web service pull/push efficiency)
</li>
</ul>
<li>Новый бизнес (New Business):
</li>
<ul>
<li>Проверить комбинации коэффициентов (Validate rates-factor combinations)
</li>
<li>Расписания и запуски заданий (Batch job schedules and runs)
</li>
<li>Ввод в эксплуатацию расчетов урегулирований (Commissioning calculations settlements)
</li>
<li>Быстрое и подробное назначение цен (Quick and detailed quote)
</li>
<li>Иллюстрация преимущества (Benefit illustration)
</li>
<li>Валидация суммарной выгоды (Benefit summary validation)
</li>
</ul>
</ul>
Образцы тестов для страховой заявки:
<ul>
<li>Проверка правил претензий (Validate claims rule)
</li>
<li>Убедитесь, что претензия может возникнуть на максимальный и минимальный платеж (Ensure that claim can occur to the maximum and minimum payment)
</li>
<li>Убедитесь, что данные передаются точно во все подсистемы, включая учетные записи и отчетность (Verify data is transferred accurately to all sub-systems including accounts and reporting)
</li>
<li>Убедитесь, что претензии могут быть обработаны по всем каналам, например, через Интернет, мобильный телефон, звонки и т. Д (Check that the claims can be processed via all channels example web, mobile, calls, etc)
</li>
<li>Тест на 100% покрытие и точность в расчетах, определяющих ставки премии (
Test for 100% coverage and accuracy in calculations determining premium rates)
</li>
<li>Убедитесь, что формула для расчета дивидендов и выплаченных значений дает правильное значение (Make sure formula for calculating dividend and paid up values gives correct value)
</li>
<li>Убедитесь, что значения выдачи рассчитываются в соответствии с требованиями политики (Verify surrender values are calculated as per the policy requirement)
</li>
<li>Проверьте фидуциарные детали и требования бухгалтерского учета (Verify fiduciary details and bookkeeping requirements)
</li>
<li>Тестирование сложных сценариев для отклонения политики провала и восстановления (Test complex scenarios for policy lapse and revivals)
</li>
<li>Испытайте различные условия для стоимости без конфискации (Test various conditions for non-forfeiture value)
</li>
<li>Тестовые сценарии для прекращения действия политики (Test scenarios for policy termination)
</li>
<li>Убедитесь, что учетная запись главной книги ведет себя так же, как и для сверки с дополнительной книгой (Verify general ledger account behave same as to reconcile with subsidiary ledger)
</li>
<li>Тестовый расчет чистого обязательства для оценки (Test calculation of net liability for valuation)
</li>
<li>Условия тестирования для длительного страхования (Test conditions for extended term insurance)
</li>
<li>Проверка политики для варианта без конфискации (Verify policy for a non-forfeiture option)
</li>
<li>Проверьте, что другой страховой продукт ведет себя как ожидалось (Check different insurance product term behaves as expected)
</li>
<li>Проверьте сумму выплаты согласно плану продукта (Verify premium value as per product plan)
</li>
<li>Тестирование автоматической системы обмена сообщениями для информирования клиентов о новых продуктах (Test automatic messaging system to inform customer about new products)
</li>
<li>Проверяйте все данные, введенные пользователями, по мере их прохождения через рабочий процесс, чтобы инициировать предупреждения, соответствие, уведомления и другие события рабочего процесса (Validate all the data entered by users as it progresses through the workflow to trigger warnings, compliance, notification and other workflow events)
</li>
<li>Убедитесь, что шаблон страхового документа поддерживает такой формат документа, как MS-Word (Verify insurance document template supports the document format like MS-Word)
</li>
<li>Тестовая система для автоматического выставления счета и отправки его клиенту по электронной почте (Test system for generating invoice automatically and send it to customer through e-mail)
</li>
</ul>
<h2>Тестирование в сфере телекоммуникаций (Telecom)</h2>
После перехода сектора телекоммуникаций на цифровые и компьютерные сети, телекоммуникационная отрасль повсеместно использует ПО. Сектор телекоммуникаций зависит от различных видов компонентов ПО, чтобы доставить множество услуг, таких как маршрутизация и коммутация, VoIP и широкополосный доступ, и т. д. Таким образом, тестирование ПО Telecom является неизбежным.
Для предоставления телекоммуникационных услуг требуется наличие IVR, колл-центров, выставление счетов и т. д.  и системы, которые включают в себя маршрутизаторы, коммутаторы, сотовые вышки и т. д. 

Примеры тест-кейсов:
<ul>
<li>Биллинговая Система: 
</li>
<ul>
<li>Телефонный номер клиента зарегистрирован на данного оператора связи 
</li>
<li>Продолжает ли номер работать 
</li>
<li>Введенный номер является валидным, а это 10-значный номер 
</li>
<li>Отображение неоплаченных счетов
</li>
<li>Проверьте, что все предыдущие аккаунты номера стерты
</li>
<li>Убедитесь, что система зафиксировала количество звонков точно 
</li>
<li>Проверьте, что тариф, выбранный клиентом, отображается в биллинговой системе 
</li>
<li>Общая суммы расходов является точной
</li>
</ul>
<li>Тестирование Приложения 
</li>
<ul>
<li>Протоколы, подача сигнала, полевые испытания для IoT 
</li>
<li>Функциональное тестирование для базового применения мобильных телефонов как звонок, SMS, перевод/удержание и т. д. 
</li>
<li>Тестирование различных приложений, таких как финансы, спорт и на основе определения местоположения, и т. д. ОСС-БСС тестирования
</li>
</ul>
<li>ОСС-БСС тестирования (OSS-BSS testing) 
</li>
<ul>
<li>Выставление счетов клиентам, партнерам, правопорядка и борьбы с мошенничеством, обеспечения доходов 
</li>
<li>Сетевое управление, посредничество, обеспечение, и т. д. 
</li>
<li>ЦОВ, CRM и ERP-систем, хранилищ данных и т. д. 
</li>
</ul>
<li>Тестирование соответствия
</li>
<ul>
<li>Совместимость электрических интерфейсов
</li>
<li>Соответствие протокола
</li>
<li>Соответствие транспортных слоев
</li>
</ul>
<li>Тестирование IVR
</li>
<ul>
<li>Интерактивные тестовые сценарии
</li>
<li>Распознавание голоса
</li>
<li>Голосовое меню и ветвление
</li>
<li>Ввод тонового сигнала DTMF
</li>
</ul>
</ul>
<h2>Тестирование протокола: L2 и L3 OSI</h2>
Когда компьютеры общаются друг с другом, существует общий набор правил и условий, которым должен следовать каждый компьютер. Другими словами, протоколы определяют, как данные передаются между вычислительными устройствами и по сетям.
PROTOCOL testing проверяет протоколы связи в областях коммутации, беспроводной связи, VoIP, маршрутизации и т. д.  Цель состоит в том, чтобы проверить структуру пакетов, которые отправляются по сети, с помощью инструментов тестирования протоколов.
Протоколы делятся на две категории: Routed и routing. Routed могут использоваться для отправки пользовательских данных из одной сети в другую. Он переносит пользовательский трафик, такой как электронная почта, веб-трафик, передача файлов и т. д.  Routed являются IP, IPX и AppleTalk. 
Routing это сетевые протоколы, которые определяют маршруты для маршрутизаторов. Они используется только между маршрутизаторами. Например, RIP, IGRP, EIGRP и т. д. 
Модель OSI имеет в общей сложности 7 уровней сетевого взаимодействия, в которых уровень 2 и уровень 3 очень важны. 
<ul>
<li>Уровень 2: это уровень канала передачи данных. Mac-адрес, Ethernet, Token Ring и Frame Relay являются примерами канального уровня. 
</li>
<li>Уровень 3: это сетевой уровень, который определяет наилучший доступный путь в сети для связи. IP-адрес является примером layer3. 
</li>
</ul>
Для тестирования протокола вам понадобится анализатор протокола и симулятор.
Анализатор протокола обеспечивает правильное декодирование наряду с анализом вызовов и сеансов. В то время как симулятор имитирует различные сущности сетевого элемента. 
Обычно тестирование протокола выполняется DUT (тестируемым устройством) для других устройств, таких как коммутаторы и маршрутизаторы, и для настройки протокола в нем. После этого проверяется структура пакетов, отправленных устройствами. Он проверяет масштабируемость, производительность, алгоритм протокола и т. д.  устройства с помощью таких инструментов, как lxNetworks, Scapy и Wireshark. 
Тестирование протокола включает тестирование функциональности, производительности, стека протоколов, функциональной совместимости и т. д.  Во время тестирования протокола, в основном, выполняется три проверки: 
<ul>
<li>Корректность: получаем ли мы пакет X как ожидали 
</li>
<li>Задержка: сколько времени занимает доставка пакета
</li>
<li>Пропускная способность: сколько пакетов мы можем отправить в секунду 
</li>
</ul>
Тестирование протокола может быть разделено на две категории. Стресс и тесты надежности и функциональные тесты. Стресс-тесты и тесты надежности охватывают нагрузочное тестирование, стресс-тестирование, тестирование производительности и т. д.  В то время как функциональное тестирование включает в себя негативное тестирование, тестирование на соответствие, тестирование на совместимость и т. д.  
Тестирование соответствия: протоколы, реализованные в продуктах, тестируются на соответствие, например, IEEE, RFC и т. д.  Тестирование совместимости: проверяется совместимость для разных поставщиков. Это тестирование проводится после тестирования соответствия на соответствующей платформе. Проверка функциональности сети: функциональность сетевых продуктов проверена на функциональность со ссылкой на проектную документацию. Например, функциями могут быть защита портов на коммутаторе, ACL на маршрутизаторе и т. д. 
Вот примеры Test case для роутеров: 
<ul>
<li>One VLAN on One Switch: Создайте две разные VLAN. Проверьте видимость между хостами в разных VLAN 
</li>
<li>Three Symmetric VLANs on One switch: Создайте три разных VLAN. Проверьте видимость между хостами 
</li>
<li>Spanning Tree: Root Path Cost Variation: Проверьте, как изменяется стоимость маршрута корневого пути после изменения топологии 
</li>
<li>Spanning Tree: Port Blocking: Проверьте, как протокол связующего дерева предотвращает образование циклов в сети, блокируя избыточные каналы, также при наличии VLAN 
</li>
<li>Spanning Tree: Port Blocking: Покажите, что каждый MSTI может иметь разные корневые мосты 
</li>
<li>Visibility between different STP Regions: с теми же VLAN проверить видимость между различными регионами STP 
</li>
<li>Telephone switch Performance: Создайте 1000 телефонных звонков и проверьте, нормально ли работает телефонный коммутатор или его производительность снижается 
</li>
<li>Negative test for device: Введите неверный ключ и проверьте пользователя на аутентификацию. 
</li>
<li>Line speed: Проверьте устройство, работающее на скорости 10 Гбит / с, используя всю доступную пропускную способность для обработки входящего трафика. 
</li>
<li>Protocol conversation rate: Отслеживайте диалог TCP между двумя устройствами и убедитесь, что каждое устройство работает правильно 
</li>
<li>Response time for session initiation: Измерьте время отклика устройства на запрос приглашения для инициации сеанса
</li>
</ul>
<h2>Тестирование интернета вещей (IoT - Internet of Things)</h2>
Интернет вещей - это сеть, состоящая из устройств в транспортных средствах, зданиях или любых других подключенных электронных устройств. Эта взаимосвязь облегчает сбор и обмен данными. 4 общих компонента системы IoT: 
<ul>
<li>Sensor
</li>
<li>Application
</li>
<li>Network
</li>
<li>Backend (Data Center)
</li>
</ul>
IOT - это соединение идентифицируемых встроенных устройств с существующей интернет-инфраструктурой. Проще говоря, мы можем сказать, что IOT - это эра «умных», связанных продуктов, которые обмениваются данными и передают большой объем данных и загружают их в облако.

<table>
<tr>
<td>IOT elements
Testing Types
</td><td>Sensor
</td><td>Application
</td><td>Network
</td><td>Backend (Data Center)
</td></tr>
<tr>
<td>Functional testing
</td><td>True
</td><td>True
</td><td>False
</td><td>False
</td></tr>
<tr>
<td>Usability testing
</td><td>True
</td><td>True
</td><td>False
</td><td>False
</td></tr>
<tr>
<td>Security testing
</td><td>True
</td><td>True
</td><td>True
</td><td>True
</td></tr>
<tr>
<td>Performance testing
</td><td>False
</td><td>True
</td><td>True
</td><td>True
</td></tr>
<tr>
<td>Compatibility testing
</td><td>True
</td><td>True
</td><td>False
</td><td>False
</td></tr>
<tr>
<td>Services testing
</td><td>False
</td><td>True
</td><td>True
</td><td>True
</td></tr>
<tr>
<td>Operational testing
</td><td>True
</td><td>True
</td><td>False
</td><td>False
</td></tr>
</table>

Категории тестов с примерами Test Conditions:
<ul>
<li>Проверка компонентов (Components Validation):
</li>
<ul>
<li>Аппаратное обеспечение устройства (Device Hardware)
</li>
<li>Встроенное программное обеспечение (Embedded Software)
</li>
<li>Облачная инфраструктура (Cloud infrastructure)
</li>
<li>Подключение к сети (Network Connectivity)
</li>
<li>Стороннее программное обеспечение (Third-party software)
</li>
<li>Тестирование датчиков (Sensor testing)
</li>
<li>Тестирование команд (Command testing)
</li>
<li>Тестирование формата данных (Data format testing)
</li>
<li>Испытание на прочность (Robustness testing)
</li>
<li>Тестирование безопасности (Safety testing)
</li>
</ul>
<li>Проверка функций (Function Validation):
</li>
<ul>
<li>Базовое тестирование устройства (Basic device testing)
</li>
<li>Тестирование между устройствами IOT (Testing between IOT devices)
</li>
<li>Обработка ошибок (Error Handling)
</li>
<li>Правильность расчета (Valid Calculation)
</li>
</ul>
<li>Проверка соответствия (Conditioning Validation):
</li>
<ul>
<li>Ручная (Manual Conditioning)
</li>
<li>Автоматическая (Automated Conditioning)
</li>
<li>Профили (Conditioning profiles)
</li>
</ul>
<li>Проверка производительности (Performance Validation):
</li>
<ul>
<li>Частота передачи данных (Data transmit Frequency)
</li>
<li>Обработка многократнах запросов (Multiple request handing)
</li>
<li>Синхронизация (Synchronization)
</li>
<li>Тестирование прерываний (Interrupt testing)
</li>
<li>Производительность устройства (Device performance)
</li>
<li>Проверка согласованности (Consistency validation)
</li>
</ul>
<li>Безопасность и проверка данных (Security and Data Validation):
</li>
<ul>
<li>Проверка пакетов данных (Validate data packets)
</li>
<li>Проверка на потерю или повреждение пакетов (Verify data loses or corrupt packets)
</li>
<li>Шифрование / дешифрование данных (Data encryption/decryption)
</li>
<li>Значения данных (Data values)
</li>
<li>Роли и ответственность пользователей и их модель использования (Users Roles and Responsibility & its Usage Pattern)
</li>
</ul>
<li>Проверка шлюза:
</li>
<ul>
<li>Тестирование облачного интерфейса (Cloud interface testing)
</li>
<li>Тестирование протокола от устройства к облаку (Device to cloud protocol testing)
</li>
<li>Тестирование задержек (Latency testing)
</li>
</ul>
<li>Проверка аналитики (Analytics Validation):
</li>
<ul>
<li>Проверка аналитики данных датчика (Sensor data analytics checking)
</li>
<li>Операционная аналитика системы IOT (IOT system operational analytics)
</li>
<li>Аналитика системного фильтра (System filter analytics)
</li>
<li>Проверка правил (Rules verification)
</li>
</ul>
<li>Проверка связи (Communication Validation):
</li>
<ul>
<li>Совместимость (Interoperability)
</li>
<li>M2M или от устройства к устройству (M2M or Device to Device)
</li>
<li>Тестирование трансляции (Broadcast testing)
</li>
<li>Тестирование прерываний (Interrupt testing)
</li>
<li>Протокол (Protocol)
</li>
</ul>
</ul>
<h2>Что такое облачное тестирование? (Cloud testing)</h2>
CLOUD testing - это тип тестирования программного обеспечения, который проверяет услуги облачных вычислений. Облачные вычисления - это интернет-платформа, предоставляющая различные компьютерные сервисы, такие как оборудование, программное обеспечение и другие компьютерные сервисы, удаленно. Существует три модели облачных вычислений:
<ul>
<li>SaaS- Software as a service
</li>
<li>PaaS- Platform as a service
</li>
<li>IaaS- Infrastructure as a service
</li>
</ul>
Все облачное тестирование разделено на четыре основные категории: 
<ul>
<li>Тестирование всего облака (Testing of the whole cloud). Облако рассматривается как единое целое и на основе его возможностей проводится тестирование. SaaS и облачные вендоры, а также конечные пользователи заинтересованы в проведении такого типа тестирования.
</li>
<li>Тестирование в пределах облака (Testing within a cloud). Проверяя каждую из его внутренних функций, проводится тестирование. Только поставщики облачных услуг могут выполнять этот тип тестирования. 
</li>
<li>Тестирование через облако (Testing across cloud). Тестирование проводится в облачных, частных, публичных и гибридных облаках различных типов. 
</li>
<li>SaaS-тестирование в облаке (SaaS testing in cloud): функциональное и нефункциональное тестирование проводится на основе требований приложений.
</li>
</ul>
Облачное тестирование фокусируется на основных компонентах, таких как: 
<ul>
<li>Приложение (Application): охватывает тестирование функций, сквозные бизнес-процессы (end-to-end business workflows), безопасность данных, совместимость с браузерами и т. д.  
</li>
<li>Сеть (Network): включает в себя тестирование различной пропускной способности сети, протоколов и успешную передачу данных через сети. 
</li>
<li>Инфраструктура (Infrastructure): включает в себя тестирование аварийного восстановления, резервное копирование, безопасное соединение и политики хранения. Инфраструктура должна быть проверена на соответствие нормативным требованиям.
</li>
</ul>
Другие типы тестирования в облаке включают:
<ul>
<li>Performance
</li>
<li>Availability
</li>
<li>Compliance
</li>
<li>Security
</li>
<li>Scalability
</li>
<li>Multi-tenancy
</li>
<li>Live upgrade testing
</li>
</ul>
Как выполнять облачное тестирование:
<ul>
<li>SaaS или облачное тестирование: Этот тип тестирования обычно выполняется поставщиками облачных или SaaS-приложений. Основной задачей является обеспечение качества предоставляемых сервисных функций, предлагаемых в облачной или SaaS-программе. Тестирование, выполняемое в этой среде, - это проверка интеграции, функциональности, безопасности, функциональности модулей, системных функций и регрессионного тестирования, а также оценка производительности и масштабируемости. 
</li>
<li>Онлайн тестирование приложений в облаке: Производители онлайн-приложений проводят это тестирование, которое проверяет производительность и функциональное тестирование облачных сервисов. Когда приложения связаны с legacy системами, проверяется качество связи между legacy системой и тестируемым приложением в облаке. 
</li>
<li>Тестирование облачных приложений над облаками: Для проверки качества облачного приложения в разных облаках выполняется этот тип тестирования.
</li>
</ul>
Примеры Test Scenario и несколько Test case для каждого из них:
<ul>
<li>Тестирование производительности (<a href="https://www.guru99.com/performance-testing.html">Performance testing</a>): 
</li>
<ul>
<li>Сбой из-за одного действия пользователя в облаке не должен влиять на других пользователей 
</li>
<li>Ручное или автоматическое масштабирование не должно вызывать сбоев 
</li>
<li>На всех типах устройств производительность приложения должна оставаться неизменной 
</li>
<li>Повторное бронирование на стороне поставщика не должно снижать производительность приложения 
</li>
</ul>
<li>Тестирование безопасности (Security testing): 
</li>
<ul>
<li>Только авторизованный клиент должен получать доступ к данным 
</li>
<li>Данные должны быть хорошо зашифрованы 
</li>
<li>Данные должны быть полностью удалены, если они не используются клиентом 
</li>
<li>Администрация поставщиков не должна получать доступ к данным клиентов. 
</li>
<li>Проверьте наличие различных настроек безопасности, таких как брандмауэр, VPN, антивирус и т. д.  
</li>
</ul>
<li>Функциональное тестирование (Functional testing): 
</li>
<ul>
<li>Валидный ввод должен давать ожидаемые результаты 
</li>
<li>Сервис должен должным образом интегрироваться с другими приложениями 
</li>
<li>Система должна отображать тип учетной записи клиента при успешном входе в облако 
</li>
<li>Когда клиент решил переключиться на другие службы, работающая служба должна автоматически закрыться 
</li>
</ul>
<li>Тестирование совместимости (Interoperability & Compatibility testing): 
</li>
<ul>
<li>Проверка требований совместимости тестируемой системы и приложения 
</li>
<li>Проверьте совместимость браузера в облачной среде 
</li>
<li>Определите дефект, который может возникнуть при подключении к облаку 
</li>
<li>Любые неполные данные в облаке не должны быть переданы 
</li>
<li>Убедитесь, что приложение работает на другой платформе облака 
</li>
<li>Протестируйте приложение в собственной среде, а затем разверните его в облачной среде. 
</li>
</ul>
<li>Тестирование сети (Network testing): 
</li>
<ul>
<li>Тестовый протокол, отвечающий за подключение к облаку 
</li>
<li>Проверка целостности данных при передаче данных 
</li>
<li>Проверьте правильность подключения к сети 
</li>
<li>Проверьте, отбрасываются ли пакеты брандмауэром с обеих сторон 
</li>
</ul>
<li>Нагрузка и стресс-тестирование (Load and Stress testing): 
</li>
<ul>
<li>Проверьте сервисы, когда несколько пользователей получают к ним доступ 
</li>
<li>Определите дефект, ответственный за сбой оборудования или среды 
</li>
<li>Проверьте, отказывает ли система при увеличении удельной нагрузки 
</li>
<li>Проверьте, как система изменяется со временем при определенной нагрузке
</li>
</ul>
</ul>
<h2>Что такое тестирование сервис-ориентированной архитектуры? (SOA - Service Oriented Architecture) </h2>
Это тестирование архитектурного стиля SOA, в котором компоненты приложения предназначены для сообщения по протоколам связи, обычно через сеть. SOA - это метод интеграции бизнес-приложений и процессов для удовлетворения потребностей бизнеса. В разработке программного обеспечения SOA обеспечивает гибкость бизнес-процессов. Изменения в процессе или приложении могут быть направлены на конкретный компонент, не затрагивая всю систему. Разработчики программного обеспечения в SOA либо разрабатывают, либо покупают куски программ под названием SERVICES. Что такое Service? 
<ul>
<li>Service могут быть функциональной единицей приложения или бизнес-процесса, которая может быть повторно использована или повторена любым другим приложением или процессом. (Например, Платежный шлюз - это сервис, который может быть повторно использован любым сайтом электронной коммерции. Каждый раз, когда необходимо сделать платеж, сайт электронной коммерции вызывает / запрашивает сервис Платежного шлюза. После оплаты через шлюз, ответ отправляется на сайт электронной коммерции) 
</li>
<li>Service просты в сборке и легко переконфигурируют компоненты. 
</li>
<li>Service можно сравнить со строительными блоками. Они могут построить любое необходимое приложение. Добавить и удалить их из приложения или бизнес-процесса очень просто. 
</li>
<li>Service больше определяются бизнес-функциями, которые они выполняют, а не кусками кода. 
</li>
</ul>
Пример: на домашней странице веб-сайта и в поисковой системе отображается ежедневный прогноз погоды. Вместо того, чтобы писать код для виджета прогноза погоды, у продавца можно купить Службу прогноза погоды и встроить ее в страницу.
Тестирование SOA должно быть сосредоточено на 3 уровнях:
<ul>
<li>Уровень сервисов (Services Layer): Этот уровень состоит из сервисов, полученных из бизнес-функций. Например - Рассмотрим оздоровительный сайт, который состоит из: Трекер веса, Отслеживание уровня сахара в крови и трекера артериального давления. Трекеры отображают соответствующие данные и дату их ввода. Уровень сервисов состоит из сервисов, которые получают соответствующие данные из базы данных – Сервис трекера веса, сервис отслеживания уровня сахара в крови, сервис отслеживания артериального давления и Сервис логина.
</li>
</ul>
<img src="https://lh6.googleusercontent.com/TRiqEMx8_mKtRv3ql8zI6HUbIMp2yLCPQPL9aba_3W7hToNLwrHsPIzYDU7r0PHgAoTCDGYf1lOFYvKlmyvRfh-8cnOktzuvs8ix9sSP9NLNZiemdK49ZdVSDkqrnWJI10YI0xzA">
<ul>
<li>Уровень процесса (Process Layer): Уровень процесса состоит из процессов, набора сервисов, которые являются частью единой функциональности. Процессы могут быть частью пользовательского интерфейса (например, поисковая система), частью инструмента ETL (для получения данных из базы данных). Основное внимание на этом уровне будет уделяться пользовательским интерфейсам и процессам. Пользовательский интерфейс весового трекера и его интеграция с базой данных является основным направлением. 
</li>
<li>Потребительский уровень (Consumer Layer): Этот уровень в основном состоит из пользовательских интерфейсов. Тестирование приложения SOA распределяется на три уровня: Уровень обслуживания, Уровень интерфейса, Уровень end-to-end. Подход сверху вниз используется для проектирования тестов. Подход снизу-вверх используется для выполнения теста.
</li>
</ul>

Методы тестирования SOA:
<ul>
<li>Data based testing на основе бизнес-сценариев:
</li>
<ul>
<li>Различные аспекты бизнеса, связанные с системой, должны быть проанализированы. 
</li>
<li>Сценарии должны быть разработаны на основе интеграции 
</li>
<ul>
<li>Различные веб-сервисы приложения 
</li>
<li>Веб-сервисы и приложения 
</li>
</ul>
<li>Настройка данных должна быть выполнена на основе вышеуказанных сценариев.
</li>
<li>Настройка данных должна быть выполнена так, чтобы охватить также сквозные сценарии
</li>
</ul>
<li>Заглушки (Stubs):
</li>
<ul>
<li>Будут созданы фиктивные интерфейсы для тестирования сервисов. 
</li>
<li>Через эти интерфейсы могут быть предоставлены различные входные данные, а выходные данные могут быть проверены. 
</li>
<li>Когда приложение использует интерфейс с внешней службой, которая не тестируется (сторонняя служба), во время тестирования интеграции можно создать заглушку.
</li>
</ul>
<li>Regression testing:
</li>
<ul>
<li>Регрессионное тестирование приложения должно проводиться при наличии нескольких релизов, чтобы обеспечить стабильность и доступность систем. 
</li>
<li>Будет создан комплексный набор регрессионных тестов, охватывающий сервисы, которые составляют важную часть приложения. 
</li>
<li>Этот набор тестов может быть повторно использован в нескольких релизах проекта.
</li>
</ul>
<li>Тестирование уровня сервиса (Service Level testing):
</li>
<ul>
<li>Тестирование уровня сервиса включает тестирование компонента на функциональность, безопасность, производительность и функциональную совместимость. Каждую услугу необходимо сначала протестировать независимо.
</li>
</ul>
<li>Functional testing:
</li>
<ul>
<li>Убедитесь, что служба отправляет правильный ответ на каждый запрос.
</li>
<li>Правильные ошибки получены для запросов с неверными данными. 
</li>
<li>Проверьте каждый запрос и ответ для каждой операции, которую служба должна выполнять во время выполнения. 
</li>
<li>Проверяйте сообщения об ошибках при возникновении ошибки на уровне сервера, клиента или сети. 
</li>
<li>Убедитесь, что полученные ответы имеют правильный формат. 
</li>
<li>Подтвердите, что данные, полученные в ответе, соответствуют запрашиваемым данным.
</li>
</ul>
<li>Security testing:
</li>
<ul>
<li>Отраслевой стандарт, определенный тестированием WS-Security, должен соблюдаться веб-службой. 
</li>
<li>Меры безопасности должны работать без нареканий. 
</li>
<li>Шифрование данных и Цифровые подписи на документах 
</li>
<li>Аутентификация и авторизация 
</li>
<li>SQL-инъекции, вредоносные программы, XSS, CSRF и другие уязвимости должны быть проверены на XML. Атаки отказа в обслуживании
</li>
</ul>
<li>Performance testing:
</li>
<ul>
<li>Производительность и функциональность сервиса необходимо тестировать при большой нагрузке. 
</li>
<li>Производительность службы необходимо сравнивать при работе индивидуально и в приложении, с которым она связана. 
</li>
<li>Нагрузочное тестирование сервиса: проверить время отклика, проверить наличие узких мест, проверить использование процессора и памяти, прогнозировать масштабируемость
</li>
</ul>
<li>Тестирование уровня интеграции (Integration level testing):
</li>
<ul>
<li>Интеграционное тестирование проводится с упором в основном на интерфейсы. 
</li>
<li>Этот этап охватывает все возможные бизнес-сценарии. 
</li>
<li>Нефункциональное тестирование приложения должно быть сделано еще раз на этом этапе. Security, compliance, and Performance testing обеспечивают доступность и стабильность системы во всех аспектах. 
</li>
<li>Коммуникационные и сетевые протоколы должны быть протестированы для проверки согласованности обмена данными между сервисами.
</li>
</ul>
<li>End to End testing:
</li>
<ul>
<li>Все сервисы работают должным образом после интеграции 
</li>
<li>Обработка исключений 
</li>
<li>Пользовательский интерфейс приложения 
</li>
<li>Правильный data flow через все компоненты 
</li>
<li>Бизнес-процесс
</li>
</ul>
</ul>
<h2>Что такое тестирование планирования ресурсов предприятия? (ERP - Enterprise Resource Planning)</h2>
Планирование ресурсов предприятия, также известное как ERP, представляет собой комплексное программное обеспечение, которое объединяет различные функции организации в единую систему. Программное обеспечение имеет общую базу данных, содержащую всю информацию, относящуюся к различным функциям или подразделениям организации. Система ERP помогает оптимизировать процессы и доступ к информации по всей организации 24 × 7.
Приложения ERP стали критически важными для бесперебойной работы предприятий. Поскольку они включают в себя множество модулей, функций и процессов, необходимость их проверки становится критической. Предприятия осознают необходимость использования модели SMAC (Social, Mobile, Analytics и Cloud) для ускорения роста. Однако капитальный ремонт основных процессов, администрируемых устаревшими приложениями ERP, также важен. Приложения ERP помогают предприятиям управлять различными функциями, отделами и процессами, включая генерируемые в них данные. Эти приложения помогают предприятиям работать как единое целое и в процессе генерировать такие результаты, как повышение производительности, повышение эффективности, сокращение отходов, повышение качества обслуживания клиентов и повышение рентабельности инвестиций. Ввиду важности приложений ERP для организаций, они должны быть протестированы и утверждены. Тестирование приложений ERP может обеспечить бесперебойную работу множества задач в организациях. Они могут включать в себя отслеживание инвентаризации и операций с клиентами, управление финансами и человеческими ресурсами, среди многих других.
Каждое программное обеспечение ERP поставляется с несколькими версиями и требует настройки в соответствии с конкретными бизнес-требованиями. Более того, поскольку каждый элемент приложения связан с каким-либо другим модулем, их обновление может быть сложной задачей. Например, для создания заказа на продажу потребуется доступ к модулю управления запасами. Если какой-либо из модулей не функционирует оптимально, это может повлиять на все приложение ERP. Это может оказать каскадное влияние на производительность компании, а также создать плохой опыт клиентов. Следовательно, тестирование приложений ERP должно обеспечить правильную реализацию программного обеспечения и предотвратить сбои. Тестирование программного обеспечения ERP, помимо проверки функциональности программного обеспечения, должно обеспечивать точное формирование отчетов и форм. Выявляя и устраняя ошибки на этапе тестирования, тестировщики могут избежать столкновения с проблемами после внедрения. Более того, это может привести к скорейшему внедрению программного обеспечения и обеспечить его бесперебойную работу. Службы тестирования приложений ERP проверяют бизнес-процессы, функции и регулирующие их правила. Они помогают снизить операционные риски в условиях ограниченности имеющихся ресурсов и времени.
Поскольку система ERP содержит огромные объемы данных, тестирование ручных процедур может потребовать много времени и средств. Автоматизированное тестирование может помочь проверить все функции и возможности при минимальных затратах времени и средств. Кроме того, поскольку несколько бизнес-подразделений организации могут иметь разные процессы или процедуры, автоматическое тестирование может проверять точность их результатов по конкретным параметрам. Кроме того, ERP-систему необходимо периодически обновлять с появлением новых технологий, таких как Cloud, Big Data и Mobility. Такие обновления помогают организации проверять транзакции в режиме реального времени, что невозможно вручную.
Системы ERP доступны в нескольких версиях, предназначенных для нескольких доменов, подразделений и клиентов, лучшие доступные инструменты: 
<ul>
<li>Microsoft Dynamics NAV - для малых и средних предприятий 
</li>
<li>SAP Insurance - Для страховых компаний 
</li>
<li>Microsoft Dynamics AX - для крупных предприятий 
</li>
<li>SAP Banking - Для банковского сектора
</li>
</ul>

Доп. материал:
<a href="https://dou.ua/forums/topic/31759/?from=fptech">Тестування CRM-систем на прикладі Salesforce</a>
<h2>Тестирование качества видеосвязи WebRTC-based сервиса видеоконференций</h2>
WebRTC (англ. real-time communications — коммуникации в реальном времени) — проект с открытым исходным кодом, предназначенный для организации передачи потоковых данных между браузерами или другими поддерживающими его приложениями по технологии точка-точка. Стандарт поддерживается в браузерах, поэтому низкий порог вхождения – не нужно писать клиент. Помимо браузеров известны такие гиганты в сфере видеоконференций, как: Skype, Google Meets/hangouts, Discord.
В чем выражается качество видеосвязи? В подавляющем большинстве случаев речь о:
<ul>
<li>Разрешение
</li>
<li>Количество кадров в секунду
</li>
</ul>

Как обычно пытаются тестировать? С помощью плохой сети. Например, отойти с планшетом подальше от wi-fi точки. Вообще плохая сеть подразумевает большой пинг, низкую пропускную способность канала, потерю пакетов. 
К сожалению, ручное тестирование видеосвязи (впрочем, как и аудио-) не даст достоверных и точных результатов. На следующем этапе команда приходит к идее писать автотесты (по большей части unit) и лишь некоторые доходят до написания бенчмарков. Возможно, в комментариях опытные коллеги поделятся своим опытом.
<h2>Что такое тестирование ETL?</h2>
ETL расшифровывается как Extract, Transform, Load. ETL - это процесс, объединяющий три этапа: извлечение, преобразование и загрузка данных из одного источника в другой. Проще говоря, операции ETL выполняются с данными, чтобы вытащить их из одной базы данных в другую. Процесс ETL часто используется в хранилищах данных.
<ul>
<li>Первым этапом процесса ETL является извлечение данных. На этом этапе данные извлекаются из исходной базы данных; может быть более одного источника данных. 
</li>
<li>На втором этапе, Преобразование данных, извлеченные данные преобразуются путем применения различных правил и функций, которые должны храниться в целевой базе данных в надлежащем формате. Данные извлекаются из разных источников, и вполне вероятно, что у них будет много проблем, например, одному и тому же объекту присваиваются разные имена или одно и то же имя присваивается разным объектам. 
</li>
<li>На последнем этапе загрузка данных, преобразованные и однородно отформатированные данные загружаются в базу данных назначения.
</li>
</ul>
ETL-тестирование - это тип тестирования, выполняемый для гарантии того, что данные, перенесенные из исходной в целевую базу данных, являются точными и соответствуют действующим правилам преобразования.

Пример: 
Давайте рассмотрим пример слияния двух компаний - компании A и компании B. После слияния их операции будут объединены, а их клиенты, сотрудники и другие данные будут храниться в единой централизованной базе данных. Предположим, что компания A использует базу данных Oracle для хранения всей информации, а компания B использует MySQL. Теперь для объединения своей информации обе компании могут использовать процесс ETL для переноса данных из своих отдельных баз данных в одну согласованную базу данных. В процессе ETL, поскольку две базы данных различны, данные обеих компаний будут в другом формате, будут использоваться разные соглашения об именах, будут использоваться разные структуры таблиц и так далее. Из-за этих различий компаниям необходимо удостовериться, что перед загрузкой данных в целевую базу данных она была должным образом очищена и может сформировать нужный формат. При тестировании ETL тестировщики должны убедиться, что данные обеих баз данных были преобразованы в формат целевой базы данных; необходимые функции преобразования были выполнены; в процессе не было потеряно никаких данных, и данные являются точными.

Типы тестирования ETL: 
<ul>
<li>Новое тестирование хранилища данных (New Data Warehouse Testing) - в этом типе тестирования ETL все делается с нуля. Информация для ввода данных собирается от клиента. Исходные и целевые базы данных заново создаются и проверяются с использованием инструментов ETL. 
</li>
<li>Миграционное тестирование (Migration Testing) - в этом типе тестирования ETL у клиента есть существующее хранилище рабочих данных; у клиента также есть существующий инструмент ETL. Процесс тестирования миграции требуется, когда данные загружаются из существующей базы данных в новую базу данных. Старая база данных называется устаревшей или исходной базой данных, а новая база данных называется целевой базой данных. 
</li>
<li>Запрос на изменение (Change Request) - в этом процессе данные выбираются из разных источников и загружаются в существующее хранилище, при этом не используются никакие новые базы данных. Помимо загрузки новых данных, клиенту может потребоваться изменить существующее бизнес-правило или добавить новое бизнес-правило. 
</li>
<li>Тестирование отчетов (Report Testing). После создания хранилища данных система позволяет пользователям создавать различные отчеты. Это тестирование проверяет макет, точность данных и ограничения доступа пользователей к отчетам.
</li>
</ul>
Доп. материал:
<a href="https://habr.com/ru/company/tinkoff/blog/543416/">«Как QA в управлении хранилища данных эволюционировал»</a>
<h1>----- Мобильное тестирование -----</h1>
<h2>Каковы особенности в тестировании мобильных приложений?</h2>
<ul>
<li>Высокая фрагментация устройств (где посмотреть: лучше аналитика с ваших пользователей, но есть и источники статистики по странам, версиям ОС и вендорам)
</li>
<li>Размеры дисплеев, разрешение и сам по себе тач-интерфейс (ландшафтная и портретная ориентация, все элементы должны быть такого размера, чтобы можно было однозначно по ним попасть; сценарии не должны вести на пустые экраны. Всегда нужно проверять несколько нажатий на одну и ту же кнопку, мультитач (если поддерживается, если нет то аппа не должна на него реагировать), нативные жесты.
</li>
<li>Постоянная обратная связь с пользователем (реакция кнопок на нажатие - у каждого элемента должно быть нажатое состояние, должны быть сообщения при загрузке контента/прогресс, сообщения об успешном исполнении сценария, звук/вибрация должны быть корректно синхронизированы по событию, сообщения при ошибке доступа к сети, наличие сообщений при попытке удалить важную информацию, наличие экрана/сообщения при окончании процесса/игры (экран Game over)).
</li>
<li>Ограничения ресурсов (энергопотребление, утечки памяти (особенно может проявляться на окнах, с большим количеством информации (длинные списки как пример), во время задач с длительным workflow (когда пользователь долго не выходит из приложения), при некорректно работающем кэшировании изображений), не хватает места для установки и работы, обновления, перенос на SD карту.
</li>
<li>Реакция на внешние прерывания (выключение или перезагрузка, входящий звонок или сообщение, обновления приложений, уведомления, разрядка, переход в энергосберегающий режим и режим ожидания, смена ориентации + в режиме ожидания, переход wi-fi -> 3G и обратно, включение и отключение функций необходимых устройству (геопозиции, блютус, режим полета), запрет на использование аппаратных ресурсов, функции с камерой, кейсы с потерей связи, зарядкой устройства, подключением отключением сд карты/симки/АКБ, подключение кабеля или гарнитуры, биометрические (напр для банковского приложения), платежи NFC или просто разные фичи, сворачивание приложения, принудительная остановка).
</li>
<li>Если приложение работает с какими-то форматами файлов, нужно проверять корректность работы с каждым из них
</li>
<li>Учитывать шторку и челку или вырез под фронталки
</li>
<li>Бэкап и восстановление из него
</li>
<li>Работа в режиме разделенного экрана
</li>
<li>Датчики, температура окружающей среды
</li>
<li>Тестирование смартфона начинается с тестирования самого устройства в заводском состоянии.
</li>
</ul>
<h2>В чем отличия тестирования мобильного приложения от десктопного?</h2>
<ul>
<li>В первую очередь это разные операционные системы и разная архитектура «железа», хотя сейчас прогресс нацелен на унификацию (например, такие гиганты, как Microsoft и Apple. У MS это планшеты-ноутбуки Surface на базе ARM и Windows 10, Apple в июне 2020 года заявила о переходе на ARM-архитектуру в компьютерах).
</li>
<li>Пока еще актуальное различие – аппаратные ресурсы. Мощность начинки и количество памяти. Хотя, опять же, в 2020 году этот пункт уже утрачивает актуальность. Мощности новых флагманских мобильных устройств сопоставимы с бюджетными ноутбуками на архитектуре x86/64, а начинка бюджетных и средних по цене мобильных аппаратов обеспечивает достаточный для большинства нужд уровень производительности.
</li>
<li>Самое очевидное различие в аппаратной части помимо мощности – наличие разнообразных датчиков и модулей связи в мобильном устройстве, а также нескольких камер, вибромотора, сканера отпечатков и т. д. 
</li>
<li>Наличие датчика ориентации уже предполагает тестирование в портретной и ландшафтной ориентациях. Добавьте к этому множество разрешений дисплея, их различные типы матриц со своими особенностями отображения и т.п.
</li>
<li>Помимо этого, в мобильном устройстве очень большое внимание уделяется обработке разнообразных прерываний (входящий звонок, уведомление, нажатие кнопки блокировки, выгрузка из ОЗУ и т. д. )
</li>
<li>Основная функция мобильных устройств – по-прежнему связь. Голосовая, но также и через мобильный интернет, что усложняет тестирование по сравнению с десктопами.
</li>
<li>Связь также в контексте взаимодействия с носимой электроникой (беспроводные наушники, фитнес-браслеты, смарт-часы, очки и т.п.), бесконтактной оплатой и т.п. 
</li>
<li>Прогресс в обновлениях ОС. В мобильных устройствах это происходит гораздо чаще и имеет большее значение в связи с большой конкуренцией.
</li>
<li>Различия в гайдлайнах для ОС.
</li>
<li>Десктопные приложения чаще всего загружаются с официального веб-сайта производителя. Мобильное приложения почти всегда загружается из соответствующего ОС магазина приложений.
</li>
<li>Ожидания. Т.к. приложения десктопных устройств созданы в основном для осуществления некой функциональной деятельности и являются рабочими инструментами, им может быть иногда простительно то, что в мобильном приложении приведет к немедленному удалению его пользователем и негативным отзывам. Любая мелкая проблема с интуитивностью, интерфейсом, локализацией, функциональностью, производительностью, расходом батареи может моментально отпугнуть пользователя и тот отдаст предпочтение конкурентам.
</li>
</ul>
<h2>В чем отличия тестирования мобильного приложения от web?</h2>
<ul>
<li>Большее количество вариантов и комбинаций ОС/железа и т.п. в мобильных устройствах (сюда же вытекающее следствие необходимости использования эмуляторов)
</li>
<li>Браузеры «стационарны», в то время как при тестировании мобильных приложений нужно учитывать ориентацию, прерывания, связь, наличие дополнительных модулей.
</li>
<li>С т.з. связи веб приложение фактически становится бесполезным при потере интернет-соединения (хотя в последнее время это иногда не совсем так), для нативного мобильного приложения ничего не изменится*.
</li>
<li>Аппаратные ограничения. Веб браузеру обычно доступно куда больше ресурсов.
</li>
<li>Публикация и распространение. Для того, чтобы люди начали пользоваться мобильным приложением, необходим аккаунт разработчика и пройденная модерация в магазине приложений.
</li>
</ul>
Из этих основных различий следуют и различия в тестировании – уровни, виды, типы и т. д. 

Мнение:
"Ваши усилия должны скорее быть направлены на выявление узких мест такие как ограничения на доступ к ресурсам выходящие с каждой новой версией мобильных операционных систем - шифрование хранилищ. Глубокая модернизация ядра (Что касается Android) устройств. Нюансы работы оффлайн воркеров для PWA. C  другой стороны в "Старших" операционных системах вы столкнетесь с взаимодействием с другими программными продуктами в рамках одной операционной системы - поскольку в них приложения не запускаются в своем собственном Sandbox но очень не слабо влияют друг на друга.  Самая яркая иллюстрация этого существование InstallShield в рамках WIndows  в течении уже многих лет." (с) @Havy_Man
<h2>Как работает Android, какая у него архитектура?</h2>

<img src="https://lh6.googleusercontent.com/R_51nz0zGZJDTvaeUMmYrUnrrUVMwMp3F8slDIDgQnKRKdS9mDWUJ253YVJrcs5YpSk9NBnNmWY77ljf-KMc1bpoOlpj07GCx9hS_Lsku1BebqAL0SF_Guwgfkvz_qi6xrWUsokE">

<img src="https://lh6.googleusercontent.com/dnrHv_dBu9lI6r9r0WXGXqi6OtChVUYjNyHM4vm50QTQxRQDvxnC28FdCR-xG3UT5UTWcrxa4Y7DdpHqKFLW_mq72GuImt0wEdA11ttNrqVSiJnxYz3uUDcq166OMJ5UXNl0QF0D">
Applications. Android поставляется с набором основных приложений, включающим календарь, карты, браузер, менеджер контактов и другие. Все перечисленные приложения написаны на Java.
Application Framework. Предоставляя открытую платформу разработки, Android дает разработчикам возможность создавать гибкие и инновационные приложения. Разработчики могут использовать аппаратные возможности устройства, получать информацию о местоположении, выполнять задачи в фоновом режиме, устанавливать оповещения и многое другое. Разработчики имеют полный доступ к тем же API, что используются в основных приложениях.
Архитектура приложений разработана с целью упрощения повторного использования компонентов; любое приложение может "публиковать" свои возможности и любое другое приложение может затем использовать эти возможности (с учетом ограничений безопасности). Этот же механизм позволяет заменять стандартные компоненты на пользовательские.
Libraries. Android включает в себя набор C/C++ библиотек, используемых различными компонентами системы. Эти возможности доступны разработчикам в контексте применения Android Application Framework. Некоторые основные библиотеки, перечислены ниже:
Mедиа библиотеки – эти библиотеки предоставляют поддержку воспроизведения и записи многих популярных аудио, видео форматов и форматов изображений, в том числе MPEG4, MP3, AAC, AMR, JPG, PNG и других;
Surface Manager – управляет доступом к подсистеме отображения 2D и 3D графических слоев;
LibWebCore – современный веб-движок, на котором построен браузер Android;
SGL – основной графический движок 2D;
3D библиотеки – реализованы на основе OpenGL; библиотеки используют либо аппаратное 3D-ускорение (при его наличии), либо включены программно;
FreeType – поддержка растровых и векторных шрифтов
SQLite – механизм базы данных, доступной для всех приложений.
Android Runtime. Android включает в себя набор основных библиотек, которые обеспечивают большинство функций, доступных в библиотеках Java. Каждое приложение Android работает в своем собственном процессе, со своим собственным экземпляром виртуальной машины Dalvik. Dalvik была написана так, что устройство может работать эффективно с несколькими виртуальными машинами одновременно.
Dalvik проектировалась специально под платформу Android. Виртуальная машина оптимизирована для низкого потребления памяти и работы на мобильном аппаратном обеспечении. Dalvik использует собственный байт-код. Android-приложения переводятся компилятором в специальный машинно-независимый низкоуровневый код. И именно Dalvik интерпретирует и выполняет такую программу при выполнении на платформе. Кроме того, с помощью специальной утилиты, входящей в состав Android SDK, Dalvik способна переводить байт-коды Java в коды собственного формата и также исполнять их в своей виртуальной среде.
Linux Kernel. Android основан на Linux версии 2.6 с основными системными службами – безопасность, управление памятью, управление процессами и модель драйверов. Разработчики Android модифицировали ядро Linux, добавив поддержку аппаратного обеспечения, используемого в мобильных устройствах и, чаще всего, недоступного на компьютерах.
Источник: <a href="https://intuit.ru/studies/courses/4462/988/lecture/14988">https://intuit.ru/studies/courses/4462/988/lecture/14988</a>
Доп. материал: <a href="https://www.slideshare.net/opersys/androids-hidl-treble-in-the-hal">Android's HIDL: Treble in the HAL</a>
<h2>Что такое тестирование прерываний (Interrupt Testing)? Причем тут Activity Lifecycle?</h2>
У приложения есть жизненный цикл со строго определенными в системе активностями. То есть при любом типе прерывания приложение должно вести себя корректно. Это важно проверять, так как это происходит буквально постоянно, а разработчики могут упустить такие кейсы в коде. Примеры можно посмотреть в разделе полезных ресурсов, там множество чек-листов и мнемоник.
<img src="https://lh6.googleusercontent.com/vwpxK5tEd5mpQinpZnEUlacDnlt37vk_SezNMD7bPX_0sTq-OnBRbqypCYgsUwpL5FIuwBfHg6RIOMidnr-pkhRwhpldt73wtloe-FEzv_TLSLKBtPm6LnwNso-1ZHImIjrMA8-O">
<h2>Как устроена iOS?</h2>
Все в курсе, что мобильные девайсы Apple работают под управлением iOS. Многие знают, что iOS представляет собой облегченную версию настольной Mac OS X. Некоторые догадываются, что в основе Mac OS X лежит POSIX-совместимая ОС Darwin, а те, кто всерьез интересуется IT, в курсе, что основа Darwin — это ядро XNU, появившееся на свет в результате слияния микроядра Mach и компонентов ядра FreeBSD. Однако все это голые факты, которые ничего не скажут нам о том, как же на самом деле работает iOS и в чем ее отличия от настольного собрата.
Условно начинку OS X / iOS можно разделить на три логических уровня: ядро XNU, слой совместимости со стандартом POSIX (плюс различные системные демоны/сервисы) и слой NeXTSTEP, реализующий графический стек, фреймворк и API приложений. Darwin включает в себя первые два слоя и распространяется свободно, но только в версии для OS X. iOS-вариант, портированный на архитектуру ARM и включающий в себя некоторые доработки, полностью закрыт и распространяется только в составе прошивок для айдевайсов (судя по всему, это защита от портирования iOS на другие устройства).
По своей сути Darwin — это «голая» UNIX-подобная ОС, которая включает в себя POSIX API, шелл, набор команд и сервисов, минимально необходимых для работы системы в консольном режиме и запуска UNIX-софта. В этом плане он похож на базовую систему FreeBSD или минимальную установку какого-нибудь Arch Linux, которые позволяют запустить консольный UNIX-софт, но не имеют ни графической оболочки, ни всего необходимого для запуска серьезных графических приложений из сред GNOME или KDE.
Ключевой компонент Darwin — гибридное ядро XNU, основанное, как уже было сказано выше, на ядре Mach и компонентах ядра FreeBSD, таких как планировщик процессов, сетевой стек и виртуальная файловая система (слой VFS). В отличие от Mach и FreeBSD, ядро OS X использует собственный API драйверов, названный I/O Kit и позволяющий писать драйверы на C++, используя объектно-ориентированный подход, сильно упрощающий разработку.
iOS использует несколько измененную версию XNU, однако в силу того, что ядро iOS закрыто, сказать, что именно изменила Apple, затруднительно. Известно только, что оно собрано с другими опциями компилятора и модифицированным менеджером памяти, который учитывает небольшие объемы оперативки в мобильных устройствах. Во всем остальном это все то же XNU, которое можно найти в виде зашифрованного кеша (ядро + все драйверы/модули) в каталоге /System/Library/Caches/com.apple.kernelcaches/kernelcache на самом устройстве.
Уровнем выше ядра в Darwin располагается слой UNIX/BSD, включающий в себя набор стандартных библиотек языка си (libc, libmatch, libpthread и так далее), а также инструменты командной строки, набор шеллов (bash, tcsh и ksh) и демонов, таких как launchd и стандартный SSH-сервер. Последний, кстати, можно активировать путем правки файла /System/Library/LaunchDaemons/ssh.plist. Если, конечно, джейлбрейкнуть девайс.
На этом открытая часть ОС под названием Darwin заканчивается, и начинается слой фреймворков, которые как раз и образуют то, что мы привыкли считать OS X / iOS.
<img src="https://lh6.googleusercontent.com/n2x5S4lS_u2Xedgh2E-WyyBRC_POLkwLHW1hIzU9-SmC516KObJUa8v-RoYfo6wI-Ap6yh7PDYZBDIM5TEi5nqWW_j9EAKnZuPY9zCDnJsovzRx4uFpI71Hu0q9r0jUUvRPRdEmU">
Darwin реализует лишь базовую часть Mac OS / iOS, которая отвечает только за низкоуровневые функции (драйверы, запуск/остановка системы, управление сетью, изоляция приложений и так далее). Та часть системы, которая видна пользователю и приложениям, в его состав не входит и реализована в так называемых фреймворках — наборах библиотек и сервисов, которые отвечают в том числе за формирование графического окружения и высокоуровневый API для сторонних и стоковых приложений
Как и во многих других ОС, API Mac OS и iOS разделен на публичный и приватный. Сторонним приложениям доступен исключительно публичный и сильно урезанный API, однако jailbreak-приложения могут использовать и приватный.
В стандартной поставке Mac OS и iOS можно найти десятки различных фреймворков, которые отвечают за доступ к самым разным функциям ОС — от реализации адресной книги (фреймворк AddressBook) до библиотеки OpenGL (GLKit). Набор базовых фреймворков для разработки графических приложений объединен в так называемый Cocoa API, своего рода метафреймворк, позволяющий получить доступ к основным возможностям ОС. В iOS он носит имя Cocoa Touch и отличается от настольной версии ориентацией на сенсорные дисплеи.
<...>
Источник: <a href="https://xakep.ru/2014/10/08/kau-ustroena-ios/">Как устроена iOS</a>
<h2>Жизненный цикл iOS-приложения?</h2>
В любой момент времени ваши приложение находятся в каком либо из перечисленных ниже состояний. Система меняет состояния вашего приложения в ответ на происходящие события. Например, когда пользователь нажимает кнопку Home, или поступает входящий вызов, или что либо еще — приложения в ответ на все это меняют свое состояние.
<table>
<tr>
<td>Not Running
</td><td>Приложение не запущено, либо запущенно но прервано системой.
</td></tr>
<tr>
<td>Inactive
</td><td>Приложение работает, но в настоящий момент ничего не делает (это может быть связано с выполнением другого кода). Приложение, как правило, остается в этом состоянии очень мало времени и переходит в другое состояние
</td></tr>
<tr>
<td>Active
</td><td>Нормальный обычный режим работы приложения на переднем плане.
</td></tr>
<tr>
<td>Background
</td><td>Приложение находится в фоне, но работает. Большинство приложений входят в это состояние на короткое время и позже приостанавливаются. Но если необходимо дополнительное время для работы в бекграунде, приложение может оставаться в этом состоянии
</td></tr>
<tr>
<td>Suspended
</td><td>Приложение работает в фоне, но не выполняет никакой код. Система перемещает приложение в это состояние автоматически и не предупреждает об этом. При условии малого количества памяти, система может не предупреждая закрыть приложения в этом состоянии для освобождения памяти.
</td></tr>
</table>
<img src="https://lh6.googleusercontent.com/d5ujO6BZ-ZJwfuH6-d4Bl1QkjljzIK66KSvMxVYhbJ3vzFEXzqdjc1DhEl1wE5cs33EI_0GtoNvcHK8DMmN4hqvEj5KVWj56MWWSA0hetY85nH4RPT0qSjV3F-5U70NeheA5jSzZ">
Приложение должно быть готово к завершению в любое время. Завершение — это нормальная часть жизненного цикла. Система обычно выключает приложения, для очищения памяти и подготовки к запуску других приложений, которые запущены пользователем, но система также может выключить приложения , которые некорректно или не отвечающим на события своевременно.
Suspended приложения не получают уведомления о завершении. Система убивает процесс и восстанавливает соответствующую память. Если приложение запущено в фоне и не отвечает, система вызовет applicationWillTerminate: чтобы приложение подготовилось к выключению. Система не вызывает метод когда устройство перезагружается.

Доп. материал:
<ul>
<li><a href="https://blog.justdev.org/preworking/preworking-4-ios-app-lifecicle/">PREWORKING 4: ЖИЗНЕННЫЙ ЦИКЛ IOS ПРИЛОЖЕНИЯ</a> (источник)
</li>
<li><a href="https://proswift.ru/ios-application-lifecycle-ili-zhiznennyj-cikl-ios-prilozheniya/">iOS Application Lifecycle, или жизненный цикл iOS приложения</a>
</li>
</ul>
<h2>Что вы знаете о симуляторах и эмуляторах?</h2>
Всегда идет спор о том, что тестирование мобильных приложений более экономично и быстрее на реальных устройствах. Но прежде чем разрушить этот миф, давайте взглянем на базовое определение эмуляторов, симуляторов и реальных устройств: 
<ul>
<li>Тестирование на реальном устройстве позволяет запускать мобильные приложения и проверять его функциональность. Тестирование реального устройства гарантирует, что ваше приложение будет работать без проблем на клиентских телефонах. 
</li>
<li>эмулятор пытается дублировать внутреннее устройство устройства, то есть представляет собой полную повторную реализацию конкретного устройства или платформы. Эмулятор действует точно так же, как и реальное устройство.
</li>
<li> симулятор пытается дублировать поведение устройства. Как правило, симулятор —  это имитация лишь отдельных свойств, возможностей или функций симулируемой системы, причем не в полном объеме, а только в том, в каком это необходимо в рамках тех задач, которые были поставлены перед симулятором. Вы как будто бы работаете в настоящей ОС, но при этом под капотом оно полностью или частично "фальшивое"
</li>
</ul>
Тестирование на симуляторах или эмуляторах имеет много преимуществ, так как они бесплатны, имеют высокую скорость выполнения, не имеют проблем при автоматическом тестировании, просты в отладке и просты в настройке. Но эмулятор / симулятор не всегда является лучшим решением для таких сценариев, как те, в которых команде тестирования необходимо проверять производительность приложения в течение более длительного периода времени. Реальные устройства стоят дороже по сравнению с эмулятором / симуляторами. Но, как следует из названия, результаты реальных устройств всегда более точны по сравнению с эмуляторами или симуляторами. Для тестирования мобильных приложений всегда требуется большое количество мобильных устройств, поскольку тестирование мобильных приложений - это все о комбинациях ПО и железа. Следовательно, в таких случаях эффективность может быть достигнута только с помощью реальных устройств.

Доп. материал:
<a href="https://andreyex.ru/informaciya/emulyator-i-simulyator-mobilnogo-ustrojstva-protiv-realnogo-ustrojstva/">Эмулятор и симулятор мобильного устройства против реального устройства</a>
<h2>Типы мобильных приложений?</h2>
<ul>
<li>Нативные приложения: Эти приложения называют нативными оттого, что они написаны на родном (с англ. native – родной) для определенной платформы языке программирования. Для Android этим языком является Kotlin/Java, тогда как для iOS – objective-С или Swift. Нативные приложения находятся на самом устройстве, доступ к ним можно получить, нажав на иконку. Они устанавливаются через магазин приложений (Play Market на Android, App Store на iOS и др.). Они разработаны специально для конкретной платформы и могут использовать все возможности устройства – камеру, GPS-датчик, акселерометр, компас, список контактов и все остальное. Также они могут распознавать стандартные жесты, предустановленные операционной системой или совершенно новые жесты, которые используются в конкретном приложении. В силу того, что нативные приложения оптимизированы под конкретную ОС, они органично вписываются в любой смартфон, отличаясь высокой скоростью работы и производительностью. Нативные приложения могут получить доступ к системе оповещений устройства, а также, в зависимости от предназначения нативного приложения, оно может всецело или частично обходиться без наличия интернет-соединения.
</li>
</ul>

<ul>
<li>Мобильные веб-приложения: На самом деле мобильные веб-приложения не являются приложениями как таковыми. Ведь дело в том, что веб-приложение, в сущности, представляет собой сайт, который адаптирован и оптимизирован под любой смартфон. И для того, чтобы воспользоваться им, достаточно иметь на устройстве браузер, знать его адрес и располагать интернет-соединением (благодаря ему происходит обновление информации в данном виде приложений). Запуская мобильные веб-приложения, пользователь выполняет все те действия, которые он выполняет при переходе на любой веб-сайт, а также получает возможность «установить» их на свой рабочий стол, создав закладку страницы веб-сайта. Веб-приложения отличаются кроссплатформенностью, то есть способны функционировать, независимо от платформы девайса. Козырем в их рукаве выступает и то, что они не используют его программное обеспечение. А по причине того, что являются мобильной версией сайта с расширенным интерактивом, веб-приложения не отбирают драгоценное место в памяти смартфона. Веб-приложения стали широко популярны в то время, когда начал развиваться HTML5 и люди осознали, что могут получить доступ к множеству функций нативных приложений, просто зайдя на веб-сайт через обычный браузер. На сегодняшний день сложно сказать, где именно располагается четкая граница между веб-приложениями и обычными веб-страницами, поскольку функционал HTML5 растет с каждым днем и все больше и больше сайтов его используют. В то же время камень в огород веб-приложений следует бросить за неспособность работать с ними без Интернета. Причем из этого выплывает и другой минус – их производительность, которая находится на среднем уровне, в сравнении с другими видами приложений. Более того, она зависит от возможностей интернет-соединения провайдера услуг. Также очевидно, что веб-приложения не могут получить доступ к функциям системы и самого устройства.
</li>
</ul>

<ul>
<li>Гибридные приложения представляют собой сочетание веб и нативных приложений: доступ к функционалу смартфона (API системы, пуш и т.п.), размещение в маркетах, простота обновления контента, кроссплатформенность веб-части. Фактически это можно объяснить как нативное приложение, в обертке которого загружается веб-приложение. Это может быть основным контентом или лишь одной из функций. Очевидно, без интернет-соединения соответствующая часть приложения потеряет работоспособность.
</li>
</ul>
<h2>Что основное проверить при тестировании мобильного приложения? </h2>
Проверяем в начале тестирования:
<ul>
<li>достаточно ли устройств для тестирования (по целевым рынкам) и готово ли покрытие
</li>
<li>согласованы все процедуры на проекте (понять что все готово, выстроили регламент цикл разработки, договорились кто когда вступает в работу, набрана команда)
</li>
<li>аппа соответствует гайдлайнам
</li>
<li>аппа работает в различных окружениях
</li>
<li>аппа должна корректно работать с внешними и внутренними запросами
</li>
<li>Проверка энергопотребления (как типичный юзер)
</li>
<li>Выбор тестов для автоматизации (когда уже написано достаточно ручных)
</li>
</ul>
Список кейсов под iPhone из утерянного источника, довольно неплохой:
<ul>
<li>Перепроверка функциональности, где ранее были обнаружены наиболее критические дефекты (регрессионное тестирование)
</li>
<li>Проверка функциональности на корректных данных (текущая дата, короткие имена и т.д.)
</li>
<li>Проверка на некорректных значениях (например: пустые поля, длинные имена, установка на телефоне даты в прошлом и т.д.)
</li>
<li>Проверка интерфейса приложения на соответствие требованиям Apple (Human interface guidelines for iPhone/iPad)
</li>
<li>Производительность приложения и скорость ответа интерфейса (используется iPhone 2g)
</li>
<li>Тесты на удобство пользования приложением (Usability tests)
</li>
<li>Тест на совместимость с другими приложениями/функциональностью iPhone (будильник/таймер/напоминания/входящий звонок/смс)
</li>
<li>Проверка настроек приложения и корректность их применения
</li>
<li>Поиск возможных мест «падения» приложения (crash) и причин их возникновения
</li>
<li>Корректность работы приложения при использовании wi-fi/gprs (включая обрывы связи/ее отсутствие)
</li>
<li>Проверка на корректность работы приложения с памятью iPhone (memory leaks)
</li>
<li>проверка того, что звук не пропадает при подключении наушников
</li>
<li>Поведение приложения при переходе iPhone в спящий режим
</li>
<li>Работа приложения с акселерометром (поворот экрана в соответствии с положением iPhone, использование функции акселерометра для получения данных приложением (шагомер))
</li>
<li>Тестирование локализации (при поддержке приложением)
</li>
<li>Проверка корректности работы приложения с камерой iPhone (если такая функциональность поддерживается), а также корректность работы приложения с iPod.
</li>
<li>быстрые «клики» по элементам интерфейса (переход по категориям, переход по записям внутри категории)
</li>
<li>если есть длительный workflow – проводить его весь (вроде длинных программ в Yoga) в реальном времени
</li>
<li>если есть готовый список и поле для вбивания параметров, то проверить поведение, когда в поле появляется подсказка из словаря и одновременно кликаешь по записи в списке <> подсказке. возможны конфликты между подсказкой айфона и реальным выбором.
</li>
<li>проверка контента: адекватный размер изображений (до 1МБ) и достаточное качество. Дополнительно смотреть на iPhone4 (большее разрешение) + см. MobileHIG.pdf chapter 11 для требований к разрешению изображений.
</li>
<li>GUI: иконки соответствуют тому, к чему относятся (хелп – знак вопроса, настройки – шестеренка и т.д.), новые окна плавно открываются справа, присутствует значок загрузки если происходит длительный процесс)
</li>
<li>Наличие экрана Game Over и корректные ссылки на нем – для игровых проектов (+ корректная отработка попадания на этот экран)
</li>
</ul>
Мультиплеерные игры.
<ul>
<li>корректность подключения игроков (напр., списывание баланса только после подключения)
</li>
<li>временные лаги
</li>
<li>подключение через различные сети
</li>
<li>корректное поведение при отключении игроков
</li>
<li>подключение ботов (если используются)
</li>
</ul>

Conformance testing:
<ul>
<li>Protocol testing
</li>
<li>Safety/<a href="https://www.guru99.com/what-is-security-testing.html">Security testing</a>
</li>
<li>SIM card testing
</li>
<li>Radio Frequency(RF) testing
</li>
<li>Audio Tests
</li>
<li>Specific Absorption Tests
</li>
</ul>

И еще: Физическая/виртуальная клавиатура, проверка обновления и чистой установки. Платный контент: соответствие цен и содержимого, покупки 2 типов (восстанавливаемые и невосстанавливаемые (кредиты)) - проверка восстановления покупок привязанных к учетке (переустановка/обновление/другое устройство)+должен быть выбор из текущего прогресса и сохраненного в учетке. Реклама: не должна перекрывать элементы, должна иметь доступную кнопку закрытия (А если кнопка еще не появилась, то каунтдаун до этого). Глобализация - меняется все что нужно и это происходит корректно. Защита от получения преимуществ при манипуляциях с датой и временем. Копирование и вставка из/в приложение.
Больше чек-листов и идей можно найти в разделе полезных ресурсов.
<h2>Как быть с покрытием девайсов?</h2>
Большинство багов обнаруживается на покрытии около 30% девайсов - разрешение, мощность, версия ос+нижняя граница для данной аппы. Варианты: физическая ферма устройств, эмулятор и симулятор (BrowserStack (облачный), родной в Android Studio, BlueStack, Genymotion и т.п.). Вообще физический устройств желательно иметь хотя бы штук 6 - два отличающихся айфона, по планшету на iOS и Android, 2 разных андроида. Хуавей сейчас тестится отдельно из-за гугл сервисов.
Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/516160/">Выбор мобильных устройств: пошаговая инструкция для начинающих QA. Часть II</a>
</li>
<li><a href="https://habr.com/ru/post/464433/">https://habr.com/ru/post/464433/</a>
</li>
</ul>
<h2>Последнее обновление Android/iOS, что нового?</h2>
Актуализируется перед собеседованием, т.к. написанное здесь будет слишком быстро устаревать.
<h2>Основные различия iOS и Android?</h2>
<ul>
<li>В первую очередь, очевидно, это разные операционные системы от разных компаний
</li>
<li>Различная целевая аудитория, в т.ч. разный ее размер (У Андроид сегодня ориентировочно 80% всех гаджетов в мире)
</li>
<li>Различная монетизация, в т.ч. ее размер (Согласно статистике, iOS пользуются более платежеспособные люди, которые делают покупки в 3 раза чаще). 
</li>
<li>Сложность вхождения в разработку (Для разработки желательно иметь реальный девайс на соответствующей ОС и ПК с соответствующей ОС для разработки. Технику для Android-разработки можно купить значительно дешевле. Даже подписка для разработчика iOS стоит в несколько раз дороже)
</li>
<li>Разное количество разработчиков (Java/Kotlin у Android намного распространеннее и чаще встречается в других сферах, нежели Swift у iOS)
</li>
<li>Отличия в модерации приложений для публикации в магазине приложений - у Android процедура значительно быстрее и проще, в Apple в первую очередь проверяют оплату через App Store, безопасность и очень большое внимание уделяют юзабилити и доступности;
</li>
<li>Отличия с точки зрения дизайна и всего связанного с ним можно узнать, прочитав гайдлайны к каждой системе (Гайдлайны (Guidelines) — набор рекомендаций, правил, принципов от создателей платформы, операционной системы, благодаря которым приложения под эти платформы и ОС от разных разработчиков выглядят единообразно). Вот некоторые из нескольких десятков отличий:
</li>
<ul>
<li>Human Interface Guidelines vs Material Design
</li>
<li>Единицы измерения: pt vs dp
</li>
<li>Размер экрана: 320 pt x 568 pt vs 360 dp x 640 dp
</li>
<li>Системный шрифт: San Francisco vs Roboto
</li>
<li>Android Navigation Bar (в отличие от iOS, у Android есть встроенный инструмент навигации назад)
</li>
<li>Важность теней в Material (в iOS они почти не используются)
</li>
<li>Отличия в нейминге в разных местах
</li>
<li>Отличия в навигации и паттернах (UX)
</li>
<li>Разные Status Bar
</li>
<li>Разные Control
</li>
<li>Разный вид стрелки «Назад» и положение заголовка
</li>
<li>Action View/Activity View vs Modal Bottom Sheet
</li>
<li>Разные требования к размеру зоны нажатия
</li>
</ul>
</ul>

Доп. материал:
<ul>
<li><a href="https://developer.android.com/distribute/best-practices/launch/launch-checklist">Google play Launch checklist</a>
</li>
<li><a href="https://developer.apple.com/app-store/review/guidelines/#sign-in-with-apple">App Store Review Guidelines</a>
</li>
</ul>
<h2>Что такое Middleware?</h2>
<img src="https://lh6.googleusercontent.com/Z3dobqqbYMLQ2f9tOl9hGDhC0Rmojtqb76yY4KOvku7DBIMinmeDmjSg0N2JjfG3ud1_h0J2dpYDMAcY8s2CJ7LM7W9OJfs5XYhFev-TFHTDdgCKYH8JqjRMVKsusde18Rw9t2c5">
Связу́ющее програ́ммное обеспе́чение (англ. middleware; также переводится как промежу́точное программное обеспечение, программное обеспечение среднего слоя, подпрогра́ммное обеспечение, межплатфо́рменное программное обеспечение) — широко используемый термин, означающий слой или комплекс технологического программного обеспечения для обеспечения взаимодействия между различными приложениями, системами, компонентами. (с) Вики. В данном разделе нас интересует применение в мобильной разработке.
Особенностью заказной разработки мобильных приложений является то, что основной сервер с API обычно предоставляет заказчик. Ниже список, с чем в этом случае придется иметь дело мобильным разработчикам:
<ul>
<li>API не дописано — разработчики заказчика загружены текущей работой и не мотивированы сдать его в срок, при том, что у маркетинга планы и сроки запуска мобильного приложения горят;
</li>
<li>API сильно не совпадает со структурой мобильного приложения (данные для экранов приходится дергать с 3-4 методов и обрабатывать локально);
</li>
<li>Нет документации, либо она сильно разрознена и не актуальна;
</li>
<li>Несколько точек входа (разросшаяся инфраструктура находится на нескольких серверах с разными адресами);
</li>
<li>Уже существующее API меняется после апдейтов основного сайта;Отсутствие тестовых серверов;
</li>
<li>Баги (много багов).
</li>
</ul>
И добавим сюда понимание, что со всем этим придется бороться сразу на двух платформах, которые хоть и являются мобильными, часто используют разные архитектурные подходы и, как следствие, разные сроки старта и готовности этапов. Все это приводит к увеличению сроков разработки и, соответственно, стоимости разработки. 
Для минимизации всех этих проблем предлагается использовать промежуточный сервер — шину данных.
Middleware - чаще всего простой быстро настраиваемый сервер, не хранящий каких-либо данных, кроме логов. Он позволяет использовать для общения мобильных приложений с собой простой REST API, строго подогнанный под логику экранов, а сам уже обращается к целевому API необходимым образом.
Бонусом мы имеем возможность разрабатывать приложения со своими наработками по авторизации, обработкам ошибок и прочим мелочам, протестированными и проверенными.
Плюсы такого подхода:
<ul>
<li>Отсутствуют простои из-за неготовности API заказчика — в худшем случае на шине отдаются тестовые данные;
</li>
<li>Упрощается реализация мобильного приложения практически до тонкого клиента;
</li>
<li>Единственная точка входа позволяет упростить архитектуру работы с сетью в МП;
</li>
<li>Возможность выкладывать обновления для сервера шины (меняющую взаимодействие с сервером заказчиком) без обновления МП, в кратчайшие сроки, без модерации со стороны третьих фирм;
</li>
<li>Простота и отсутствие полноценной БД позволяет легко разворачивать любое количество тестовых серверов;
</li>
<li>Удобное логирование всех сетевых ошибок и оповещение о них;
</li>
<li>Изменения в работе API заказчика необходимо вносить только в одном месте — на сервере шины;
</li>
<li>Документация ведется принятым и привычным в компании способом;
</li>
<li>Использование наработок снижает сроки и стоимость разработки.
</li>
</ul>
Все это позволяет снизить сроки и стоимость, напрямую и косвенно, за счет снижения рисков простоя, сложности реализации серверной части и тестирования. Шикарный бонус разработчику — возможность предложить более низкую цену и выиграть конкурс, а заказчику - сэкономить и уменьшить сроки внедрения МП.
Источник: <a href="https://vc.ru/dev/98973-middleware-neobhodimost-v-mire-razrabotki-mobilnyh-prilozheniy">Middleware: необходимость в мире разработки мобильных приложений</a>

<h2>Виды жестов и т.п.?</h2>
Основное, остальное см. в полезных материалах (сборники терминов).
<ul>
<li>Скроллинг (scrolling) – прокрутка экрана
</li>
<li>Драг-энд-дроп, дрэг-энд-дроп (drag-and-drop) — «тащить и бросить» — нажать в одном месте, затем двигать и отпустить в другом месте
</li>
<li>Гестуры, жесты (gestures) — разные формы движения мыши, пальца или другого указывающего устройства. Могут быть запрограммированы для выполнения определенных действий. Например, движение пальца сверху вниз по экрану мобильного браузера перезагружает страницу
</li>
<li>Тап, тэп (tap) — короткое нажатие пальцем, сродни клику
</li>
<li>Двойной тап, Дабл-тап, дабл-тэп (double tap) — два коротких нажатия пальцем, сродни дабл-клику
</li>
<li>Длинный тап, Тач (touch) — нажатие дольше, чем Тап
</li>
<li>Тач-энд-холд (touch and hold) — нажать и держать
</li>
<li>Флик (flick) — щелчок наискось по экрану в сторону будущего движения изображения экрана, после флика изображение продолжает двигаться по инерции
</li>
<li>Свайп (swipe), Слайд (slide) — продолжительное скольжение пальцем по экрану
</li>
<li>Пинч (pinch) — щипок, сжимающее движение одновременно двумя пальцами по экрану для уменьшения изображения
</li>
<li>Спред / Спрэд (spread), Стретч (stretch: для Microsoft), Пинч-ит-опен (pinch it open: для Apple) — растягивающее движение одновременно двумя пальцами по экрану для увеличения изображения
</li>
<li>Пан, пэн (pan) — медленное движение пальца по экрану для перемещения и разглядывания увеличенной картинки
</li>
</ul>

Доп. материал:
<a href="https://habr.com/ru/company/youla/blog/540768/">UI-элементы и жесты в мобильных приложениях</a>
<h2>Как проверить использование процессора на мобильных устройствах? </h2>
В Google Play или App Store доступны различные инструменты,, из которых можно установить приложения, такие как CPU Monitor, Usemon, CPU Stats, CPU-Z и т. д.  Это расширенный инструмент, который записывает информацию о процессах, запущенных на вашем устройстве. Не все показатели могут быть доступны, это зависит от конкретного устройства. Также в инструментах разработчика доступны инструменты профилирования. Другой вариант - профилировщик в IDE (Android Studio).
<h2>Что вы знаете о PWA?</h2>
Перспектива разработки мобильного приложения, которое не потребуется скачивать и ждать review из App Store, очень заманчива, ведь аналогов привычного ПО существует несколько: Progressive Web Apps (PWA), Android Instant Apps (AIA) и Accelerated Mobile Pages (AMP). 
Доп. материал:
<ul>
<li><a href="https://www.youtube.com/watch?v=i9kmWZGnVEY">Тестирование аналогов инсталлируемых приложений. Диана Пинчук. Comaqa Spring 2019</a>
</li>
<li><a href="https://medium.com/effective-developers/how-to-test-pwa-daa1a6eaf7bf">How to Test PWA. In this article we will look at PWA and… | by Slava Kirzhak | Effective Developers</a>
</li>
</ul>












<h1>----- Сети и около них -----</h1>

Некоторая база в одной статье: <a href="https://habr.com/ru/post/491540/">Сети для начинающего IT-специалиста. Обязательная база</a>
<h2>Что такое http?</h2>
HTTP — широко распространенный протокол передачи данных, изначально предназначенный для передачи гипертекстовых документов (то есть документов, которые могут содержать ссылки, позволяющие организовать переход к другим документам), сейчас же для любых данных.
Протокол HTTP предполагает использование клиент-серверной структуры передачи данных. Клиентское приложение формирует запрос и отправляет его на сервер, после чего серверное ПО обрабатывает данный запрос, формирует ответ и передает его обратно клиенту. 
То есть этот протокол не только устанавливает правила обмена информацией, но и служит транспортом для передачи данных — с его помощью браузер загружает содержимое сайта на ваш компьютер или смартфон.

У HTTP есть один недостаток: данные передаются в открытом виде и никак не защищены. На пути из точки А в точку Б информация в интернете проходит через десятки промежуточных узлов, и, если хоть один из них находится под контролем злоумышленника, данные могут перехватить. То же самое может произойти, когда вы пользуетесь незащищенной сетью Wi-Fi, например, в кафе. Для установки безопасного соединения используется протокол HTTPS с поддержкой шифрования.
Защиту данных в HTTPS обеспечивает криптографический протокол SSL/TLS, который шифрует передаваемую информацию. По сути этот протокол является оберткой для HTTP. Он обеспечивает шифрование данных и делает их недоступными для просмотра посторонними. Протокол SSL/TLS хорош тем, что позволяет двум незнакомым между собой участникам сети установить защищенное соединение через незащищенный канал. При установке безопасного соединения по HTTPS ваш компьютер и сервер сначала выбирают общий секретный ключ, а затем обмениваются информацией, шифруя ее с помощью этого ключа. Общий секретный ключ генерируется заново для каждого сеанса связи. Его нельзя перехватить и практически невозможно подобрать — обычно это число длиной более 100 знаков. Этот одноразовый секретный ключ и используется для шифрования всего общения браузера и сервера. Казалось бы, идеальная система, гарантирующая абсолютную безопасность соединения. Однако для полной надежности ей кое-чего не хватает: гарантии того, что ваш собеседник именно тот, за кого себя выдает. Для этой гарантии существует сертификат.
Вам как пользователю сертификат не нужен, но любой сервер (сайт), который хочет установить безопасное соединение с вами, должен его иметь. Сертификат подтверждает две вещи: 1) Лицо, которому он выдан, действительно существует и 2) Оно управляет сервером, который указан в сертификате. Выдачей сертификатов занимаются центры сертификации — что-то вроде паспортных столов. Как и в паспорте, в сертификате содержатся данные о его владельце, в том числе имя (или название организации), а также подпись, удостоверяющая подлинность сертификата. Проверка подлинности сертификата — первое, что делает браузер при установке безопасного HTTPS-соединения. Обмен данными начинается только в том случае, если проверка прошла успешно.

Доп. материал:
<ul>
<li><a href="https://www.youtube.com/watch?v=iS-D5jZ_c24&t=1s&ab_channel=HillelITSchool">HTTP для тестировщиков</a>
</li>
<li><a href="https://www.tutorialspoint.com/http/http_overview.htm">Официальная документация</a>
</li>
<li><a href="https://developer.mozilla.org/ru/docs/Web/HTTP/Overview">Обзор протокола HTTP</a>
</li>
</ul>
<h2>Компоненты HTTP?</h2>
HTTP определяет следующую структуру запроса (request):
<ul>
<li>стартовая строка (starting line) — определяет тип сообщения, имеет вид Метод URI HTTP/Версия протокола, например GET /web-programming/index.html HTTP/1.1
</li>
<li>заголовки запроса (header fields) — характеризуют тело сообщения, параметры передачи и прочие сведения
</li>
<li>тело сообщения (body) — необязательное
</li>
</ul>
HTTP определяет следующую структуру ответного сообщения (response):
<ul>
<li>строка состояния (status line), включающая код состояния и сообщение о причине
</li>
<li>поля заголовка ответа (header fields)
</li>
<li>дополнительное тело сообщения (body)
</li>
</ul>

Доп. материал: <a href="https://iit-web-lectures.readthedocs.io/ru/latest/www/http.html">https://iit-web-lectures.readthedocs.io/ru/latest/www/http.html</a>
<h2>Методы HTTP-запроса?</h2>
Метод, используемый в HTTP-запросе, указывает, какое действие вы хотите выполнить с этим запросом. Раньше хватало только GET, т.к. считалось, что вы можете хотеть от сервера только получить ответ. Но сейчас вам может понадобиться отредактировать профиль, удалить пост в соц. сети и т.п. Тогда для удобства были созданы различные методы. Вот основные:
<ul>
<li>GET: получить подробную информацию о ресурсе
</li>
<li>POST: создать новый ресурс
</li>
<li>PUT: обновить существующий ресурс
</li>
<li>DELETE: Удалить ресурс
</li>
</ul>

Вообще по спецификации HTTP из всех методов сервер должен уметь понимать только GET, а остальные на усмотрение. Но при этом и не задано строго, что сервер должен делать при получении запроса. То есть гипотетически вы с помощью одного метода можете делать вообще любую операцию. Однако в этом нет никакого практического смысла. В дальнейшем было введено соглашение REST, определившее структуру построения веб-приложений, в том числе и работу с методами.
Доп. материал:
<ul>
<li><a href="https://www.tutorialsteacher.com/webapi/parameter-binding-in-web-api">Parameter Binding</a>
</li>
<li><a href="https://stackoverflow.com/questions/611906/http-post-with-url-query-parameters-good-idea-or-not">HTTP POST with URL query parameters — good idea or not?</a>
</li>
</ul>
<h2>Что такое endpoint, ресурс? URI, URL, URN?</h2>
Смысл в том, что сайт, написанный на любом языке, поддерживающем HTTP запросы, не посылает на сервер никаких PHP/C/Python команд, а общается ним с помощью запросов, описанных в API.
Адрес, на который посылаются сообщения называется Endpoint. Обычно это URL (например, название сайта) и порт. Если я хочу создать веб сервис на порту 8080, Endpoint будет выглядеть так: http://vladislaveremeev.ru:8080
Если моему Web сервису нужно будет отвечать на различные сообщения я создам сразу несколько URL (interfaces) по которым к сервису можно будет обратиться. Например:
<ul>
<li>https://vladislaveremeev.ru:8080 /resource1/status
</li>
<li>https://vladislaveremeev.ru:8080 /resource1/getserviceInfo
</li>
<li>https://vladislaveremeev.ru:8080 /resource1/putID
</li>
<li>http://vladislaveremeev.ru:8080 /resource1/eventslist
</li>
<li>https://vladislaveremeev.ru:8080 /resource2/putID
</li>
</ul>
Как видите у моих эндпойнтов (Endpoints) различные окончания. Такое окончание в Endpoint называются Resource, а начало Base URL.
Такое определение Endpoint и Resource используется, например, в SOAP UI для RESTful интерфейсов
https://vladislaveremeev.ru:8080 - это Base URL
/resource1/status - это Resource
Endpoint = Base URL + Resource
Понятие Endpoint может использоваться в более широком смысле. Можно сказать, что какой-то определенный роутер или компьютер является Endpoint. Обычно это понятно из контекста.
Также следует обратить внимание на то, что понятие Endpoint выходит за рамки RESTful и может использовать как в SOAP так и в других протоколах.
Термин Resource также связан с RESTful, но в более широком смысле может означать что-то другое.
Итак, простейший запрос состоит из метода и Endpoint
Request = Method + Endpoint
Ресурс — это ключевая абстракция, на которой концентрируется протокол HTTP. Ресурс — это все, что вы хотите показать внешнему миру через ваше приложение. Например, если мы пишем приложение для управления задачами, экземпляры ресурсов будут следующие:
<ul>
<li>Конкретный пользователь
</li>
<li>Конкретная задача
</li>
<li>Список задач
</li>
</ul>
Когда вы разрабатываете RESTful сервисы, вы должны сосредоточить свое внимание на ресурсах приложения. Способ, которым мы идентифицируем ресурс для предоставления, состоит в том, чтобы назначить ему URI — универсальный идентификатор ресурса. Например:
<ul>
<li>Создать пользователя: POST /users
</li>
<li>Удалить пользователя: DELETE /users/1
</li>
<li>Получить всех пользователей: GET /users
</li>
<li>Получить одного пользователя: GET /users/1
</li>
</ul>
Расшифруем аббревиатуры:
<ul>
<li>URI –  Uniform Resource Identifier (унифицированный идентификатор ресурса) - имя и адрес ресурса в сети, включает в себя URL и URN
</li>
<li>URL – Uniform Resource Locator (унифицированный определитель местонахождения ресурса) -  адрес ресурса в сети, определяет местонахождение и способ обращения к нему
</li>
<li>URN – Uniform Resource Name (унифицированное имя ресурса) - имя ресурса в сети, определяет только название ресурса, но не говорит как к нему подключиться
</li>
</ul>
Рассмотрим примеры:
<ul>
<li>URI – <a href="https://wiki.merionet.ru/images/vse-chto-vam-nuzhno-znat-pro-devops/1.png">https://wiki.merionet.ru/images/vse-chto-vam-nuzhno-znat-pro-devops/1.png</a>
</li>
<li>URL - <a href="https://wiki.merionet.ru/">https://wiki.merionet.ru</a>
</li>
<li>URN - images/vse-chto-vam-nuzhno-znat-pro-devops/1.png
</li>
</ul>
URI содержит в себе следующие части:
<ul>
<li>Схема (scheme) - показывает на то, как обращаться к ресурсу, чаще всего это сетевой протокол (http, ftp, ldap)
</li>
<li>Иерархическая часть (hier-part) - данные, необходимые для идентификации ресурса (например, адрес сайта)
</li>
<li>Запрос (query) - необязательные дополнительные данные ресурса (например, поисковой запрос)
</li>
<li>Фрагмент (fragment) – необязательный компонент для идентификации вторичного ресурса ресурса (например, место на странице)
</li>
</ul>
Общий синтаксис URI выглядит так:
URI = scheme ":" hier-part [ "?" query ] [ "#" fragment ]
Теперь, когда мы знаем, что такое URI, URL тоже должен быть достаточно понятным. Всегда помните - URI может содержать URL, но URL указывает только адрес ресурса.
URL содержит следующую информацию:
<ul>
<li>Протокол, который используется для доступа к ресурсу – http, https, ftp
</li>
<li>Расположение сервера с использованием IP-адреса или имени домена - например, wiki.merionet.ru - это имя домена. https://192.168.1.17 - здесь ресурс расположен по указанному IP-адресу
</li>
<li>Номер порта на сервере. Например, http://localhost: 8080, где 8080 - это порт.
</li>
<li>Точное местоположение в структуре каталогов сервера. Например - https://wiki.merionet.ru/ip-telephoniya/ - это точное местоположение, если пользователь хочет перейти в раздел про телефонию на сайте.
</li>
<li>Необязательный идентификатор фрагмента. Например, https://www.google.com/search?ei=qw3eqwe12e1w&q=URL, где q = URL - это строка запроса, введенная пользователем.
</li>
</ul>
Синтаксис:
[protocol]://www.[domain_name]:[port 80]/[path or exaction resource location]?[query]#[fragment]

Источник: <a href="https://wiki.merionet.ru/servernye-resheniya/36/url-i-uri-v-chem-razlichie/#">url и uri - в чем различие?</a>
<h2>Что такое веб-сервис/веб-служба? (WS - Web service)</h2>
Web Service - программная система, предназначенная поддерживать взаимодействие между интераперабельными устройствами через сеть. Веб сервис обладает интерфейсом, описанным в WSDL формате. Другие системы, взаимодействуют с веб сервисом через SOAP-сообщения, которые обычно передаются с помощью HTTP с XML сериализацией в связке с другими веб-стандартами.
<ul>
<li>Сервис доступен по сети, может располагаться и выполняться на разных компьютерах.
</li>
<li>Передача сообщений между сервисом и клиентом происходит в независимом формате.
</li>
<li>Web Service может быть создан из существующего Web приложения.
</li>
<li>Сервис использует стандартизированную XML messaging систему.
</li>
<li>Не привязан к операционной системе или языку программирования
</li>
</ul>

Доп. материал:
<ul>
<li><a href="https://gist.github.com/vchernogorov/81da656048875132d6963304d449f770">Веб-сервисы</a>
</li>
<li><a href="https://coderlessons.com/tutorials/veb-razrabotka/izuchite-veb-servisy/veb-servisy-kratkoe-rukovodstvo">Что такое веб-сервисы?</a>
</li>
<li><a href="https://smartbear.com/solutions/microservices/">What is Microservices?</a>
</li>
<li><a href="https://www.n-ix.com/microservices-vs-monolith-which-architecture-best-choice-your-business/">Microservices vs Monolith: which architecture is the best choice for your business?</a>
</li>
</ul>
<h2>Отличие сервиса от сервера?</h2>
В контексте архитектуры программного обеспечения, сервис-ориентированности и сервис-ориентированной архитектуры термин <a href="https://en.wikipedia.org/wiki/Service_(systems_architecture)">«сервис» </a>относится к программным функциям или набору программных функций (таких как получение указанной информации или выполнение набора операций) или «механизм, обеспечивающий доступ к одной или нескольким возможностям, где доступ предоставляется с использованием предписанного интерфейса и осуществляется в соответствии с ограничениями и политиками, указанными в описании службы».
В вычислительной технике <a href="https://en.wikipedia.org/wiki/Server_(computing)">сервер </a>- это часть компьютерного оборудования или программного обеспечения (компьютерная программа), которая обеспечивает функциональные возможности для других программ или устройств, называемых «клиентами». Эта архитектура называется клиент-серверной. Серверы могут предоставлять различные функции, часто называемые «сервисами», такие как совместное использование данных или ресурсов между несколькими клиентами или выполнение вычислений для клиента. Один сервер может обслуживать несколько клиентов, а один клиент может использовать несколько серверов. Клиентский процесс может работать на том же устройстве или может подключаться по сети к серверу на другом устройстве. Типичными серверами являются серверы баз данных, файловые серверы, почтовые серверы, серверы печати, веб-серверы, игровые серверы и серверы приложений.
<h2>Отличие сервиса от веб-сайта?</h2>
<ul>
<li>Веб-сервис не имеет пользовательского интерфейса. Веб-сайт имеет пользовательский интерфейс или графический интерфейс. 
</li>
<li>Веб-сервисы предназначены для взаимодействия других приложений через Интернет. Веб-сайты предназначены для использования людьми. 
</li>
<li>Веб-сервисы не зависят от платформы, так как используют открытые протоколы. Веб-сайты являются кроссплатформенными, так как требуют настройки для работы в разных браузерах, операционных системах и т. д.  
</li>
<li>Доступ к веб-сервисам осуществляется с помощью HTTP-методов - GET, POST, PUT, DELETE и т. д.  Доступ к веб-сайтам осуществляется с помощью компонентов GUI - кнопок, текстовых полей, форм и т. д.  
</li>
<li>Например, Google maps API - это веб-сервис, который может использоваться веб-сайтами для отображения Карт путем передачи ему координат. Например, ArtOfTesting.com - это веб-сайт, на котором есть коллекция связанных веб-страниц, содержащих учебные пособия.
</li>
</ul>

<h2>Что такое REST, SOAP? В чем отличия?</h2>
<ul>
<li>SOAP (Simple Object Access Protocol) — стандартный протокол обмена структурированными сообщениями в распределенной вычислительной среде. Данные передаются в XML.
</li>
<li>REST (Representational State Transfer) — архитектурный стиль взаимодействия компьютерных систем в сети основанный на методах протокола HTTP. Данные по умолчанию передаются в JSON.
</li>
</ul>
SOAP и REST нельзя сравнивать напрямую, поскольку первый - это протокол (или, по крайней мере, пытается им быть), а второй - архитектурный стиль. 
Основное различие между SOAP и REST заключается в степени связи между реализациями клиента и сервера. Клиент SOAP работает как пользовательское настольное приложение, тесно связанное с сервером. Между клиентом и сервером существует жесткое соглашение, и ожидается, что все сломается, если какая-либо из сторон что-то изменит. Вам нужно постоянное обновление после любого изменения, но легче определить, выполняется ли контракт.
REST-клиент больше похож на браузер. Это универсальный клиент, который знает, как использовать протокол и стандартизированные методы, и приложение должно соответствовать этому. Вы не нарушаете стандарты протокола, создавая дополнительные методы, вы используете стандартные методы и создаете с ними действия для своего типа медиа. Если все сделано правильно, связности будет меньше, и с изменениями можно справиться более изящно. 

То есть SOAP более применим в сложных архитектурах, где взаимодействие с объектами выходит за рамки теории CRUD, а вот в тех приложениях, которые не покидают рамки данной теории, вполне применимым может оказаться именно REST ввиду своей простоты и прозрачности. Действительно, если любым объектам вашего сервиса не нужны более сложные взаимоотношения, кроме: «Создать», «Прочитать», «Изменить», «Удалить» (как правило — в 99% случаев этого достаточно), возможно, именно REST станет правильным выбором. Кроме того, REST по сравнению с SOAP, может оказаться и более производительным, так как не требует затрат на разбор сложных XML команд на сервере (выполняются обычные HTTP запросы — PUT, GET, POST, DELETE). Хотя SOAP, в свою очередь, более надежен и безопасен.

Доп. материал:
<a href="https://www.springboottutorial.com/rest-vs-soap-web-services">REST v SOAP - A few perspectives</a>
<h2>Что такое JSON, XML?</h2>
JSON (JavaScript Object Notation - обозначение объектов JavaScript) - текстовый формат обмена данными, основанный на JavaScript (но он не зависит от языка).
XML (eXtensible Markup Language — расширяемый язык разметки) - это язык разметки. Является выбором по умолчанию для обмена данными, остается легко читаемым, даже при больших массивах информации. 
JSON благодаря популярности технологии API REST, получил импульс развития в программировании API и веб-сервисов. Это текстовый, легкий и простой в разборе формат данных, не требующий дополнительного кода для анализа. Таким образом, JSON помогает ускорить обмен данными и для веб-сервисов, которые должны просто возвращать много данных и отображать их.
Пример JSON:
{
	
"title":"bananas",
	
"count":"1000",
	
"description":["500 green", "500 yellow"]
}
В python аналогичная структура данных – словари. То есть это просто набор ключ: значение. При этом ключ должен быть уникальным, значений может быть любое количество. Допускается вложенность (значением может быть другой json или список).

Пример XML:
<?xml version="1.0" encoding="UTF-8"?> 
<companies>
    <company>
        <company-id>12345</company-id>
        <name lang="ru">Абракадабра</name>
                <country lang="ru">Россия</country>
                <phone>
            <number>+7 (999) 999-99-99</number>
            <ext>777</ext>
            <info>Приемная</info>
            <type>phone</type>
        </phone>
    </company>    
</companies>
Как видно, XML похож на HTML, однако здесь теги не предопределены.

Если на собеседовании по какой-то причине захотят углубленно проверить эту тему, то могут спросить про разницу между well-formed и valid XML, развить в валидацию и XSD, через признаки Well-formed документа можно выйти на вложенность, а дальше на префиксы и namespace.

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/post/524288/">Что такое XML</a>
</li>
<li><a href="https://jsonlint.com/">JSONLint</a>
</li>
<li><a href="https://xmllint.com/">XML Formatting & Validation Tool</a>
</li>
</ul>
<h2>Коды ответов/состояния сервера с примерами? (HTTP status codes)</h2>
Несколько из них могут спросить чуть конкретнее, чем просто название, обычно на Ваш же выбор.
Иногда на собеседовании можно услышать вопрос: «Что дают эти коды ответа и что с ними можно делать?». На него настолько обширный ответ, что в рамках данной статьи это было бы не уместно, но конкретно для тестировщика чаще всего это просто удобное понимание, как именно отреагировал сервер на web или API запрос.
<ul>
<li>Информационные (100-105) 
</li>
<li>Успешные (200-226) 
</li>
<li>Перенаправление (300-307) 
</li>
<li>Ошибка клиента (400-499) 
</li>
<li>Ошибка сервера (500-510)
</li>
</ul>



<table>
<tr>
<td>Код ответа
</td><td>Название
</td><td>Описание
</td></tr>
<tr>
<td>100
</td><td>Continue
</td><td>"Продолжить". Этот промежуточный ответ указывает, что запрос успешно принят и клиент может продолжать присылать запросы либо проигнорировать этот ответ, если запрос был завершен.
</td></tr>
<tr>
<td>101
</td><td>Switching Protocol
</td><td>"Переключение протокола". Этот код присылается в ответ на запрос клиента, содержащий заголовок Upgrade, и указывает, что сервер переключился на протокол, который был указан в заголовке. Эта возможность позволяет перейти на несовместимую версию протокола и обычно не используется.
</td></tr>
<tr>
<td>102
</td><td>Processing
</td><td>"В обработке". Этот код указывает, что сервер получил запрос и обрабатывает его, но обработка еще не завершена.
</td></tr>
<tr>
<td>103
</td><td>Early Hints
</td><td>"Ранние подсказки". В ответе сообщаются ресурсы, которые могут быть загружены заранее, пока сервер будет подготавливать основной ответ. 
</td></tr>
<tr>
<td>200
</td><td>OK
</td><td>"Успешно". Запрос успешно обработан. Что значит "успешно", зависит от метода HTTP, который был запрошен:
GET: "ПОЛУЧИТЬ". Запрошенный ресурс был найден и передан в теле ответа.
HEAD: "ЗАГОЛОВОК". Заголовки переданы в ответе.
POST: "ПОСЫЛКА". Ресурс, описывающий результат действия сервера на запрос, передан в теле ответа.
TRACE: "ОТСЛЕЖИВАТЬ". Тело ответа содержит тело запроса полученного сервером.
</td></tr>
<tr>
<td>201
</td><td>Created
</td><td>"Создано". Запрос успешно выполнен и в результате был создан ресурс. Этот код обычно присылается в ответ на запрос PUT "ПОМЕСТИТЬ".
</td></tr>
<tr>
<td>202
</td><td>Accepted
</td><td>"Принято". Запрос принят, но еще не обработан. Не поддерживаемо, т.е., нет способа с помощью HTTP отправить асинхронный ответ позже, который будет показывать итог обработки запроса. Это предназначено для случаев, когда запрос обрабатывается другим процессом или сервером, либо для пакетной обработки.
</td></tr>
<tr>
<td>203
</td><td>Non-Authoritative Information
</td><td>"Информация не авторитетна". Этот код ответа означает, что информация, которая возвращена, была предоставлена не от исходного сервера, а из какого-нибудь другого источника. Во всех остальных ситуациях более предпочтителен код ответа 200 OK.
</td></tr>
<tr>
<td>204
</td><td>No Content
</td><td>"Нет содержимого". Нет содержимого для ответа на запрос, но заголовки ответа, которые могут быть полезны, присылаются. Клиент может использовать их для обновления кешированных заголовков полученных ранее для этого ресурса.
</td></tr>
<tr>
<td>205
</td><td>Reset Content
</td><td>"Сбросить содержимое". Этот код присылается, когда запрос обработан, чтобы сообщить клиенту, что необходимо сбросить отображение документа, который прислал этот запрос.
</td></tr>
<tr>
<td>206
</td><td>Partial Content
</td><td>"Частичное содержимое". Этот код ответа используется, когда клиент присылает заголовок диапазона, чтобы выполнить загрузку отдельно, в несколько потоков.
</td></tr>
<tr>
<td>300
</td><td>Multiple Choice
</td><td>"Множественный выбор". Этот код ответа присылается, когда запрос имеет более чем один из возможных ответов. И User-agent или пользователь должен выбрать один из ответов. Не существует стандартизированного способа выбора одного из полученных ответов.
</td></tr>
<tr>
<td>301
</td><td>Moved Permanently
</td><td>"Перемещен на постоянной основе". Этот код ответа значит, что URI запрашиваемого ресурса был изменен. Возможно, новый URI будет предоставлен в ответе.
</td></tr>
<tr>
<td>302
</td><td>Found
</td><td>"Найдено". Этот код ответа значит, что запрошенный ресурс временно изменен. Новые изменения в URI могут быть доступны в будущем. Таким образом, этот URI, должен быть использован клиентом в будущих запросах.
</td></tr>
<tr>
<td>303
</td><td>See Other
</td><td>"Просмотр других ресурсов". Этот код ответа присылается, чтобы направлять клиента для получения запрашиваемого ресурса в другой URI с запросом GET.
</td></tr>
<tr>
<td>304
</td><td>Not Modified
</td><td>"Не модифицировано". Используется для кэширования. Это код ответа значит, что запрошенный ресурс не был изменен. Таким образом, клиент может продолжать использовать кэшированную версию ответа.
</td></tr>
<tr>
<td>305
</td><td>Use Proxy
</td><td>"Использовать прокси". Это означает, что запрошенный ресурс должен быть доступен через прокси. Этот код ответа в основном не поддерживается из соображений безопасности.
</td></tr>
<tr>
<td>306
</td><td>Switch Proxy
</td><td>Больше не использовать. Изначально подразумевалось, что " последующие запросы должны использовать указанный прокси."
</td></tr>
<tr>
<td>307
</td><td>Temporary Redirect
</td><td>"Временное перенаправление". Сервер отправил этот ответ, чтобы клиент получил запрошенный ресурс на другой URL-адрес с тем же методом, который использовал предыдущий запрос. Данный код имеет ту же семантику, что код ответа 302 Found, за исключением того, что агент пользователя не должен изменять используемый метод HTTP: если в первом запросе использовался POST, то во втором запросе также должен использоваться POST.
</td></tr>
<tr>
<td>308
</td><td>Permanent Redirect
</td><td>"Перенаправление на постоянной основе". Это означает, что ресурс теперь постоянно находится в другом URI, указанном в заголовке Location: HTTP Response. Данный код ответа имеет ту же семантику, что и код ответа 301 Moved Permanently, за исключением того, что агент пользователя не должен изменять используемый метод HTTP: если POST использовался в первом запросе, POST должен использоваться и во втором запросе.
Примечание: Это экспериментальный код ответа, Спецификация которого в настоящее время находится в черновом виде.
</td></tr>
<tr>
<td>400
</td><td>Bad Request
</td><td>"Плохой запрос". Этот ответ означает, что сервер не понимает запрос из-за неверного синтаксиса. 
</td></tr>
<tr>
<td>401
</td><td>Unauthorized
</td><td>"Неавторизовано". Для получения запрашиваемого ответа нужна аутентификация. Статус похож на статус 403, но, в этом случае, аутентификация возможна. 
</td></tr>
<tr>
<td>402
</td><td>Payment Required
</td><td>"Необходима оплата". Этот код ответа зарезервирован для будущего использования. Первоначальная цель для создания этого когда была в использовании его для цифровых платежных систем(на данный момент не используется).
</td></tr>
<tr>
<td>403
</td><td>Forbidden
</td><td>"Запрещено". У клиента нет прав доступа к содержимому, поэтому сервер отказывается дать надлежащий ответ. 
</td></tr>
<tr>
<td>404
</td><td>Not Found
</td><td>"Не найден". Сервер не может найти запрашиваемый ресурс. Код этого ответа, наверно, самый известный из-за частоты его появления в вебе. 
</td></tr>
<tr>
<td>405
</td><td>Method Not Allowed
</td><td>"Метод не разрешен". Сервер знает о запрашиваемом методе, но он был деактивирован и не может быть использован. Два обязательных метода,  GET и HEAD,  никогда не должны быть деактивированы и не должны возвращать этот код ошибки.
</td></tr>
<tr>
<td>406
</td><td>Not Acceptable
</td><td>Этот ответ отсылается, когда веб сервер после выполнения server-driven content negotiation, не нашел контента, отвечающего критериям, полученным из user agent.
</td></tr>
<tr>
<td>407
</td><td>Proxy Authentication Required
</td><td>Этот код ответа аналогичен коду 401, только аутентификация требуется для прокси сервера.
</td></tr>
<tr>
<td>408
</td><td>Request Timeout
</td><td>Ответ с таким кодом может прийти, даже без предшествующего запроса. Он означает, что сервер хотел бы отключить это неиспользуемое соединение. Этот метод используется все чаще с тех пор, как некоторые браузеры, вроде Chrome и IE9, стали использовать HTTP механизмы предварительного соединения для ускорения серфинга  (смотрите баг 634278, будущей реализации этого механизма в Firefox). Также учитывайте, что некоторые серверы прерывают соединения не отправляя подобных сообщений.
</td></tr>
<tr>
<td>409
</td><td>Conflict
</td><td>Этот ответ отсылается, когда запрос конфликтует с текущим состоянием сервера.
</td></tr>
<tr>
<td>410
</td><td>Gone
</td><td>Этот ответ отсылается, когда запрашиваемый контент удален с сервера.
</td></tr>
<tr>
<td>411
</td><td>Length Required
</td><td>Запрос отклонен, потому что сервер требует указание заголовка Content-Length, но он не указан.
</td></tr>
<tr>
<td>412
</td><td>Precondition Failed
</td><td>Клиент указал в своих заголовках условия, которые сервер не может выполнить
</td></tr>
<tr>
<td>413
</td><td>Request Entity Too Large
</td><td>Размер запроса превышает лимит, объявленный сервером. Сервер может закрыть соединение, вернув заголовок Retry-After
</td></tr>
<tr>
<td>414
</td><td>Request-URI Too Long
</td><td>URI запрашиваемый клиентом слишком длинный для того, чтобы сервер смог его обработать
</td></tr>
<tr>
<td>415
</td><td>Unsupported Media Type
</td><td>Медиа формат запрашиваемых данных не поддерживается сервером, поэтому запрос отклонен
</td></tr>
<tr>
<td>416
</td><td>Requested Range Not Satisfiable
</td><td>Диапазон указанный заголовком запроса Range не может быть выполнен; возможно, он выходит за пределы переданного URI
</td></tr>
<tr>
<td>417
</td><td>Expectation Failed
</td><td>Этот код ответа означает, что ожидание, полученное из заголовка запроса Expect, не может быть выполнено сервером.
</td></tr>
<tr>
<td>500
</td><td>Internal Server Error
</td><td>"Внутренняя ошибка сервера". Сервер столкнулся с ситуацией, которую он не знает, как обработать. 
</td></tr>
<tr>
<td>501
</td><td>Not Implemented
</td><td>"Не выполнено". Метод запроса не поддерживается сервером и не может быть обработан. Единственные методы, которые сервера должны поддерживать (и, соответственно, не должны возвращать этот код) -  GET и HEAD.
</td></tr>
<tr>
<td>502
</td><td>Bad Gateway
</td><td>"Плохой шлюз". Эта ошибка означает что сервер, во время работы в качестве шлюза для получения ответа, нужного для обработки запроса, получил недействительный (недопустимый) ответ. 
</td></tr>
<tr>
<td>503
</td><td>Service Unavailable
</td><td>"Сервис недоступен". Сервер не готов обрабатывать запрос. Зачастую причинами являются отключение сервера или то, что он перегружен. Обратите внимание, что вместе с этим ответом удобная для пользователей(user-friendly) страница должна отправлять объяснение проблемы.  Этот ответ должен использоваться для временных условий и Retry-After: HTTP-заголовок должен, если возможно, содержать предполагаемое время до восстановления сервиса. Веб-мастер также должен позаботиться о заголовках, связанных с кэшем, которые отправляются вместе с этим ответом, так как эти ответы, связанные с временными условиями, обычно не должны кэшироваться. 
</td></tr>
<tr>
<td>504
</td><td>Gateway Timeout
</td><td>Этот ответ об ошибке предоставляется, когда сервер действует как шлюз и не может получить ответ вовремя.
</td></tr>
<tr>
<td>505
</td><td>HTTP Version Not Supported
</td><td>"HTTP-версия не поддерживается". HTTP-версия, используемая в запроcе, не поддерживается сервером.
</td></tr>
</table>
<h2>Почему ошибка 404 относится к 4** - клиентской, если по идее должна быть 5**?</h2>
Хотя интуитивно можно подумать, что данная ошибка должна относиться к ошибкам со стороны сервера, 404 по задумке является клиентской ошибкой, то есть подразумевается, что клиент (Вы) должен был знать, что URL страницы был перемещен или удален и Вы пытаетесь открыть несуществующую страницу.
<h2>Какие еще бывают протоколы?</h2>
<ul>
<li><a href="https://ru.wikipedia.org/wiki/FTP">FTP</a> (File Transfer Protocol) — это протокол передачи файлов со специального файлового сервера на компьютер пользователя. FTP дает возможность абоненту обмениваться двоичными и текстовыми файлами с любым компьютером сети. Установив связь с удаленным компьютером, пользователь может скопировать файл с удаленного компьютера на свой или скопировать файл со своего компьютера на удаленный.
</li>
<li><a href="https://ru.wikipedia.org/wiki/POP3">POP3</a> (Post Office Protocol) — это стандартный протокол почтового соединения. Серверы POP обрабатывают входящую почту, а протокол POP предназначен для обработки запросов на получение почты от клиентских почтовых программ.
</li>
<li><a href="https://ru.wikipedia.org/wiki/SMTP">SMTP</a> (Simple Mail Transfer Protocol) — протокол, который задает набор правил для передачи почты. Сервер SMTP возвращает либо подтверждение о приеме, либо сообщение об ошибке, либо запрашивает дополнительную информацию.
</li>
<li><a href="https://ru.wikipedia.org/wiki/TELNET">TELNET</a> — это протокол удаленного доступа. TELNET дает возможность абоненту работать на любой ЭВМ находящейся с ним в одной сети, как на своей собственной, то есть запускать программы, менять режим работы и так далее. На практике возможности ограничиваются тем уровнем доступа, который задан администратором удаленной машины.
</li>
<li>TCP — сетевой протокол, отвечающий за передачу данных в сети Интернет.
</li>
<li>UDP - это тоже транспортный протокол передачи данных, но без подтверждения доставки
</li>
<li>Ethernet — протокол, определяющий стандарты сети на физическом и канальном уровнях.
</li>
</ul>
<h2>TCP/IP это?</h2>
TCP/IP — сетевая модель передачи данных, представленных в цифровом виде. Модель описывает способ передачи данных от источника информации к получателю. В модели предполагается прохождение информации через четыре уровня, каждый из которых описывается правилом (протоколом передачи). Наборы правил, решающих задачу по передаче данных, составляют стек протоколов передачи данных, на которых базируется Интернет. 
Набор интернет-протоколов — это концептуальная модель и набор коммуникационных протоколов, используемых в Интернете и подобных компьютерных сетях. Он широко известен как TCP/IP, поскольку базовые протоколы в пакете — это протокол управления передачей (TCP) и интернет-протокол (IP). 
Набор интернет-протоколов обеспечивает сквозную передачу данных, определяющую, как данные должны пакетироваться, обрабатываться, передаваться, маршрутизироваться и приниматься. Эта функциональность организована в четыре слоя абстракции, которые классифицируют все связанные протоколы в соответствии с объемом задействованных сетей. 
От самого низкого до самого высокого уровня:
<ul>
<li>уровень связи, содержащий методы связи для данных, которые остаются в пределах одного сегмента сети; 
</li>
<li>интернет-уровень, обеспечивающий межсетевое взаимодействие между независимыми сетями; 
</li>
<li>транспортный уровень, обрабатывающий связь между хостами;
</li>
<li>прикладной уровень, который обеспечивает обмен данными между процессами для приложений.
</li>
</ul>

Доп. материал:
<a href="https://www.youtube.com/watch?v=rLUzYeLdM0k&t=1s&ab_channel=HillelITSchool">TCP/IP: что это и зачем это тестировщику</a>
<h2>Что такое куки (cookies)? Как их тестировать?</h2>
Файл cookie HTTP (файл cookie Интернета, файл cookie браузера) представляет собой небольшой фрагмент данных (часть http заголовка), который веб-сервер хранит в текстовом файле на жестком диске пользователя (клиента). Эта часть информации затем отправляется обратно на сервер каждый раз, когда браузер запрашивает страницу с сервера. Обычно cookie-файлы содержат персонализированные пользовательские данные или информацию, которые используются для определения того, поступили ли два запроса от одного и того же браузера - например, для входа пользователя в систему или для связи между различными веб-страницами. Он запоминает информацию stateful для stateless протокола HTTP. 
Куки в основном используются для трех целей: 
<ul>
<li>Управление сессиями: Логины, корзины покупок, результаты игр и все, что сервер должен запомнить 
</li>
<li>Пользовательские настройки, темы и другие настройки 
</li>
<li>Запись и анализ поведения пользователя
</li>
</ul>
Куки состоят в основном из трех вещей: 
<ul>
<li>Имя сервера, с которого был отправлен куки 
</li>
<li>Время жизни (Cookies Lifetime)
</li>
<li>Случайно сгенерированный уникальный номер
</li>
</ul>
<a href="http://www.faqs.org/rfcs/rfc2965.html">Максимальный размер кук</a> = 4 килобайт (4096 байт), <a href="https://askdev.ru/q/kakoy-maksimalnyy-razmer-fayla-cookie-i-skolko-mogut-hranitsya-v-brauzere-dlya-kazhdogo-sayta-67762/">в некоторых источниках</a> 4093 байт
Виды кук:
<ul>
<li>Сессионные cookie, также известные как временные cookie, существуют только во временной памяти, пока пользователь находится на странице веб-сайта. Браузеры обычно удаляют сессионные cookie после того, как пользователь закрывает окно браузер. В отличие от других типов cookie, сессионные cookie не имеют истечения срока действия, и поэтому браузеры понимают их как сессионные.
</li>
<li>Вместо того, чтобы удаляться после закрытия браузера, как это делают сессионные cookie, постоянные cookie-файлы удаляются в определенную дату или через определенный промежуток времени. Это означает, что информация о cookie будет передаваться на сервер каждый раз, когда пользователь посещает веб-сайт, которому эти cookie принадлежат. По этой причине постоянные cookie иногда называются следящие cookie, поскольку они могут использоваться рекламодателями для записи о предпочтениях пользователя в течение длительного периода времени. Однако, они также могут использоваться и в «мирных» целях, например, чтобы избежать повторного ввода данных при каждом посещении сайта.
</li>
<li>Обычно атрибут домена cookie совпадает с доменом, который отображается в адресной строке веб-браузера. Это называется первый файл cookie. Однако сторонний файл cookie принадлежит домену, отличному от того, который указан в адресной строке. Этот тип файлов cookie обычно появляется, когда веб-страницы содержат контент с внешних веб-сайтов, например, рекламные баннеры. Это открывает возможности для отслеживания истории посещений пользователя и часто используется рекламодателями для предоставления релевантной рекламы каждому пользователю.
</li>
<li>Супер-cookie — это cookie-файл с источником домена верхнего уровня (например, .ru) или общедоступным суффиксом (например, .co.uk). Обычные cookie, напротив, имеют происхождение от конкретного доменного имени, например, example.com. Супер-cookie могут быть потенциальной проблемой безопасности и поэтому часто блокируются веб-браузерами. Если браузер разблокирует вредоносный веб-сайт, злоумышленник может установить супер-cookie и потенциально нарушить или выдать себя за законные запросы пользователей на другой веб-сайт, который использует тот же домен верхнего уровня или общедоступный суффикс, что и вредоносный веб-сайт. Например, супер-cookie с происхождением .com может злонамеренно повлиять на запрос к example.com, даже если файл cookie не был создан с сайта example.com. Это может быть использовано для подделки логинов или изменения информации пользователя.
</li>
</ul>
<ul>
<li>Поскольку cookie можно очень легко удалить из браузера, программисты ищут способы идентифицировать пользователей даже после полной очистки истории браузера. Одним из таких решений являются зомби-cookie (или evercookie, или persistent cookie) — не удаляемые или трудно удаляемые cookie, которые можно восстановить в браузере с помощью JavaScript. Это возможно потому, что для хранения куков сайт одновременно использует все доступные хранилища браузера (HTTP ETag, Session Storage, Local Storage, Indexed DB), в том числе и хранилища приложений, таких как Flash Player (Local Shared Objects), Microsoft Silverlight (Isolated Storage) и Java (Java persistence API). Когда программа обнаруживает отсутствие в браузере cookie-файла, информация о котором присутствует в других хранилищах — она тут же восстанавливает его на место и, тем самым, идентифицирует пользователя для сайта.
</li>
</ul>
Примеры Test case для Cookie testing:
<ul>
<li>Отключение файлов cookie: отключите все файлы cookie и попытайтесь использовать основные функции сайта 
</li>
<li>Поврежденные файлы cookie: вручную отредактируйте файл cookie в блокноте и измените параметры на несколько случайных значений 
</li>
<li>Шифрование куки: конфиденциальная информация, такая как пароли и имена пользователей, должна быть зашифрована
</li>
<li>Тестирование файлов cookie в нескольких браузерах. Убедитесь, что с вашего веб-сайта правильно записываются cookie в разных браузерах 
</li>
<li>Проверка удаления куки с веб-сайта
</li>
<li>Удаление файлов cookie: удалите все файлы cookie для веб-сайтов и посмотрите, как веб-сайт среагирует 
</li>
<li>Доступ к файлам cookie: файлы cookie, написанные одним сайтом, не должны быть доступны другим 
</li>
<li>Не допускайте чрезмерного использования файлов cookie: если тестируемое приложение является общедоступным веб-сайтом, не следует злоупотреблять файлами cookie. 
</li>
<li>Тестирование с другими настройками. Тестирование должно выполняться правильно, чтобы убедиться, что веб-сайт работает хорошо с другими настройками файлов cookie. 
</li>
<li>Категоризируйте куки отдельно: куки не должны храниться в той же категории вирусов, спама или шпионских программ
</li>
</ul>

Доп. материал: <a href="https://testmatick.com/ru/chto-takoe-fajly-cookie-i-kak-ih-testirovat/">Что такое файлы cookie и как их тестировать</a>
<h2>Что такое Web Storage?</h2>
Почти всем настольным и мобильным приложениям нужно где-то хранить пользовательские данные. Но как быть веб-сайтам? В прошлом, мы использовали для этой цели файлы cookie, но у них есть серьезные ограничения. HTML5 предоставляет более подходящие инструменты для решения этой проблемы. Первый инструмент – это IndexedDB, который является излишним, говоря о замене cookie, а второй – Web Storage, являющееся комбинацией двух очень простых интерфейсов API.
Интернет-хранилище или <a href="https://ru.wikipedia.org/wiki/Document_Object_Model">DOM</a>-хранилище — это программные методы и протоколы <a href="https://ru.wikipedia.org/wiki/%D0%92%D0%B5%D0%B1-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5">веб-приложения</a>, используемые для хранения данных в веб-браузере. Интернет-хранилище представляет собой <a href="https://ru.wikipedia.org/w/index.php?title=%D0%9F%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%BD%D0%BE%D0%B5_%D1%85%D1%80%D0%B0%D0%BD%D0%B8%D0%BB%D0%B8%D1%89%D0%B5_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85&action=edit&redlink=1">постоянное хранилище данных</a>, похожее на <a href="https://ru.wikipedia.org/wiki/HTTP_cookie">куки</a>, но со значительно расширенной емкостью и без хранения информации в <a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D0%B7%D0%B0%D0%B3%D0%BE%D0%BB%D0%BE%D0%B2%D0%BA%D0%BE%D0%B2_HTTP">заголовке запроса HTTP</a>. Существуют два основных типа веб-хранилища: локальное хранилище (localStorage) и сессионное хранилище (sessionStorage), ведущие себя аналогично постоянным и сессионным кукам соответственно.

Доп. материал:
<ul>
<li><a href="https://developer.mozilla.org/ru/docs/Learn/JavaScript/Client-side_web_APIs/Client-side_storage">Client-side storage</a>
</li>
<li><a href="https://professorweb.ru/my/html/html5/level5/5_1.php">HTML5 Web Storage - обзор веб-хранилища</a>
</li>
</ul>
<h2>В чем отличие статических и динамических веб-сайтов?</h2>
Статические сайты состоят из неизменяемых страниц. Это значит, что сайт имеет один и тот же внешний вид, а также одно и то же наполнение для всех посетителей. При запросе такого сайта в браузере сервер сразу предоставляет готовый HTML-документ в исходном виде, в котором он и был создан. Кроме HTML, в коде таких страниц используется разве что CSS и JavaScript, что обеспечивает их легкость и быструю загрузку.
Чаще всего статическими бывают сайты с минимальным количеством страниц или с контентом, который не нужно регулярно обновлять, а именно сайты-визитки, каталоги продукции, справочники технической документации. Однако с помощью сторонних инструментов существует возможность добавить на такие страницы отдельные динамические элементы (комментарии, личный кабинет для пользователей, поиск).
Динамические сайты, в свою очередь, имеют изменяемые страницы, адаптирующиеся под конкретного пользователя. Такие страницы не размещены на сервере в готовом виде, а собираются заново по каждому новому запросу. Сначала сервер находит нужный документ и отправляет его интерпретатору, который выполняет код из HTML-документа и сверяется с файлами и базой данных. После этого документ возвращается на сервер и затем отображается в браузере. Для интерпретации страниц на серверной стороне используются языки программирования Java, PHP, ASP и другие.
Самыми яркими примерами динамических сайтов являются интернет-магазины, социальные сети и т.п.
Источники: 
<ul>
<li><a href="https://yandex.ru/turbo/jino.ru/s/journal/articles/staticheskie-dinamicheskie-sayty/">https://yandex.ru/turbo/jino.ru/s/journal/articles/staticheskie-dinamicheskie-sayty/</a>
</li>
<li><a href="https://wp-system.ru/sozdanie-sayta/staticheskie-i-dinamicheskie-sajty/">https://wp-system.ru/sozdanie-sayta/staticheskie-i-dinamicheskie-sajty/</a>
</li>
</ul>
<h2>Отличие stateless и stateful?</h2>
stateful — модель, при которой объект содержит информацию о своем состоянии, все методы работают в контексте его состояния
stateless не предоставляют эту информацию. Все методы объекта работают вне какого-либо контекста или локального состояния объекта, которого в этом случае просто нет. Не делается предположений о состоянии сессии, все изменения атомарны, нет каких-то сессионных переменных на сервере, помнящих результат предыдущего запроса. Они каждый раз дают один и тот же неизменный ответ на один и тот же запрос, функцию или вызов метода. HTTP не имеет состояния в необработанном виде - если вы выполняете GET для определенного URL, вы получаете (теоретически) один и тот же ответ каждый раз.
<h2>Различия методов GET и POST?</h2>
Основное состоит в способе передачи данных веб-формы обрабатывающему скрипту, а именно:
<ul>
<li>Метод GET отправляет скрипту всю собранную информацию формы как часть URL: http://www.komtet.ru/script.php?login=admin&name=komtet
</li>
<li>Метод POST передает данные таким образом, что пользователь сайта уже не видит передаваемые скрипту данные: http://www.komtet.ru/script.php
</li>
</ul>
Оба метода успешно передают необходимую информацию из веб-формы скрипту, поэтому при выборе того или иного метода, который будет наиболее подходить сайту, нужно учитывать следующие факторы:
<ul>
<li>Принцип работы метода GET ограничивает объем передаваемой скрипту информации;
</li>
<li>Так как метод GET отправляет скрипту всю собранную информацию формы как часть URL (то есть в открытом виде), то это может пагубно повлиять на безопасность сайта;
</li>
<li>Страницу, сгенерированную методом GET, можно пометить закладкой (адрес страницы будет всегда уникальный), а страницу, сгенерированную метод POST нельзя (адрес страницы остается неизменным, так как данные в URL не подставляются);
</li>
<li>Используя метод GET можно передавать данные не через веб-форму, а через URL страницы, введя необходимые значения через знак &: http://www.komtet.ru/script.php?login=admin&name=komtet
</li>
<li>Метод POST в отличие от метода GET позволяет передавать запросу файлы;
</li>
<li>При использовании метода GET существует риск того, что поисковый робот может выполнить тот или иной открытый запрос.
</li>
</ul>
<h2>Клиент - серверная архитектура?</h2>
<ul>
<li>Сервер – логический процесс, который обеспечивает некоторый сервис по запросу от клиента. Обычно сервер не только выполняет запрос, но и управляет очередностью запросов, буферами обмена, извещает своих клиентов о выполнении запроса и т. д.  
</li>
<li>Клиент – процесс, который запрашивает обслуживание от сервера. Процесс не является клиентом по каким-то параметрам своей структуры, он является клиентом только по отношению к серверу. 
</li>
<li>Сеть, протоколы – третий компонент, который обеспечивает обмен информацией между клиентом и сервером.
</li>
</ul>
При взаимодействии клиента и сервера инициатором диалога с сервером, как правило, является клиент, сервер сам не инициирует совместную работу. 

Технология клиент-сервер - шаблон проектирования, основа для создания веб-приложений, взаимодействие, при котором одна программа (клиент) запрашивает услугу (выполнение какой либо совокупности действий), а другая программа (сервер) ее выполняет.

Двухзвенная архитектура клиент-сервер:
<ul>
<li>«Толстый клиент»: на сервере реализованы главным образом функции доступа к базам данных, а основные прикладные вычисления выполняются на стороне клиента. 
</li>
<li>«Тонкий клиент»: на сервере выполняется основная часть прикладной обработки данных, а на клиентские рабочие станции передаются уже результаты обработки данных для просмотра и анализа пользователем с возможностью их последующей обработки (в минимальном объеме).
</li>
</ul>

Многоуровневая архитектура «клиент-сервер»:
Разновидность архитектуры клиент-сервер, в которой функция обработки данных вынесена на один или несколько отдельных серверов. Это позволяет разделить функции хранения, обработки и представления данных для более эффективного использования возможностей серверов и клиентов.

<img src="https://lh4.googleusercontent.com/7XPZfb-FP-EZRjWxvoEzjufyC41R9DIAWjBpgrAwL7G1ZqJLozBK2TD8FACZGYgDRia1nkcwbethz2H2gtQ_sbJ8XKKPbraPLRBTV-mp92RbQNrK1biSctjP53HT0KPBZ9ObBgCz">

<h2>Уровни OSI?</h2>
<table>
<tr>
<td>Модель OSI
</td></tr>
<tr>
<td>Уровень (layer)
</td><td>Тип данных (PDU)
</td><td>Функции
</td><td>Примеры
</td></tr>
<tr>
<td>Host
layers
</td><td>7. Прикладной (application)
</td><td>Данные
</td><td>Доступ к сетевым службам
</td><td>HTTP, FTP, POP3, WebSocket
</td></tr>
<tr>
<td>6. Представления (presentation)
</td><td>Представление и шифрование данных
</td><td>ASCII, EBCDIC
</td></tr>
<tr>
<td>5. Сеансовый (session)
</td><td>Управление сеансом связи
</td><td>RPC, PAP, L2TP
</td></tr>
<tr>
<td>4. Транспортный (transport)
</td><td>Сегменты
(segment) /Дейтаграммы (datagram)
</td><td>Прямая связь между конечными пунктами и надежность
</td><td>TCP, UDP, SCTP, PORTS
</td></tr>
<tr>
<td>Media
layers
</td><td>3. Сетевой (network)
</td><td>Пакеты (packet)
</td><td>Определение маршрута и логическая адресация
</td><td>IPv4, IPv6, IPsec, AppleTalk
</td></tr>
<tr>
<td>2. Канальный (data link)
</td><td>Биты (bit)/
Кадры (frame)
</td><td>Физическая адресация
</td><td>PPP, IEEE 802.22, Ethernet, DSL, ARP, сетевая карта.
</td></tr>
<tr>
<td>1. Физический (physical)
</td><td>Биты (bit)
</td><td>Работа со средой передачи, сигналами и двоичными данными
</td><td>USB, кабель («витая пара», коаксиальный, оптоволоконный), радиоканал
</td></tr>
</table>

Вместо OSI в реальности актуальнее знать TCP/IP. Тестировщики и разработчики почти всегда работают на прикладном уровне. Ниже может быть только тестирование VoIP и т.п.
<h2>Что вы подразумеваете под потоковыми медиа? (Streaming media) </h2>
Потоковая передача - это процесс загрузки данных с сервера. 
Потоковое мультимедиа - мультимедиа, которое непрерывно получает пользователь от провайдера потокового вещания. Это понятие применимо как к информации, распространяемой через телекоммуникации, так и к информации, которая изначально распространялась посредством потокового вещания (например, радио, телевидение) 
<h2>Основные команды Linux?</h2>
<ul>
<li>pwd - когда вы впервые открываете терминал, вы попадаете в домашний каталог вашего пользователя. Чтобы узнать, в каком каталоге вы находитесь, вы можете использовать команду «pwd». Это команда выводит полный путь от корневого каталога к текущему рабочему каталогу: в контексте которого (по умолчанию) будут исполняться вводимые команды. Корень является основой файловой системы Linux. Обозначается косой чертой (/). Каталог пользователя обычно выглядит как "/ home / username".
</li>
<li>ls - используйте команду "ls", чтобы узнать, какие файлы находятся в каталоге, в котором вы находитесь. Вы можете увидеть все скрытые файлы, используя команду "ls -a".
</li>
<li>cd - используйте команду "cd", чтобы перейти в каталог. Например, если вы находитесь в домашней папке и хотите перейти в папку загрузок, вы можете ввести «cd Downloads». Помните, что эта команда чувствительна к регистру, и вы должны ввести имя папки в точности так, как оно есть. Но есть один нюанс. Представьте, что у вас есть папка с именем «Raspberry Pi». В этом случае, когда вы вводите «cd Raspberry Pi», оболочка примет второй аргумент команды как другой, поэтому вы получите сообщение об ошибке, говорящее о том, что каталог не существует. Здесь вы можете использовать обратную косую черту, то есть: «cd Raspberry/ Pi». Пробелы работают так: если вы просто наберете «cd» и нажмете клавишу ввода, вы попадете в домашний каталог. Чтобы вернуться из папки в папку до этого, вы можете набрать «cd ..». Две точки возвращают в предыдущий каталог.
</li>
<li>mkdir и rmdir - используйте команду mkdir, когда вам нужно создать папку или каталог. Например, если вы хотите создать каталог под названием «DIY», вы можете ввести «mkdir DIY». Помните, как уже было сказано, если вы хотите создать каталог с именем «DIY Hacking», вы можете ввести «mkdir DIY/ Hacking». Используйте rmdir для удаления каталога. Но rmdir можно использовать только для удаления пустой директории. Чтобы удалить каталог, содержащий файлы, используйте команду rm.
</li>
<li>rm - используйте команду rm для удаления файлов и каталогов. Используйте «rm -r», чтобы удалить только каталог. Он удаляет как папку, так и содержащиеся в ней файлы при использовании только команды rm.
</li>
<li>touch - команда touch используется для создания файла. Это может быть что угодно, от пустого txt-файла до пустого zip-файла. Например, «touch new.txt».
</li>
<li>man и --help - Чтобы узнать больше о команде и о том, как ее использовать, используйте команду man. Показывает справочные страницы команды. Например, «man ls» показывает справочные страницы команды ls. Ввод имени команды и аргумента помогает показать, каким образом можно использовать команду (например, cd --help).
</li>
<li>cp - используйте команду cp для копирования файлов через командную строку. Он принимает два аргумента: первый - это местоположение файла, который нужно скопировать, второй - куда копировать.
</li>
<li>mv - используйте команду mv для перемещения файлов через командную строку. Мы также можем использовать команду mv для переименования файла. Например, если мы хотим переименовать файл «text» в «new», мы можем использовать «mv text new». Он принимает два аргумента, как и команда cp.
</li>
<li>locate - команда locate используется для поиска файла в системе Linux, так же, как команда поиска в Windows. Эта команда полезна, когда вы не знаете, где файл сохранен или фактическое имя файла. Использование аргумента -i с командой помогает игнорировать регистр (не имеет значения, является ли он прописным или строчным). Итак, если вам нужен файл со словом «hello», он дает список всех файлов в вашей системе Linux, содержащих слово «hello», когда вы вводите «locate -i hello». Если вы помните два слова, вы можете разделить их звездочкой (*). Например, чтобы найти файл, содержащий слова «hello» и «this», вы можете использовать команду «locate -i * hello * this».
</li>
</ul>

Промежуточные команды:
<ul>
<li>echo - команда "echo" помогает нам перемещать некоторые данные, обычно текст, в файл. Например, если вы хотите создать новый текстовый файл или добавить в уже созданный текстовый файл, вам просто нужно ввести «echo hello, меня зовут hich >> new.txt». Вам не нужно разделять пробелы с помощью обратной косой черты здесь, потому что мы заключаем в две треугольные скобки, когда мы заканчиваем то, что нам нужно написать.
</li>
<li>cat - Используйте команду cat для отображения содержимого файла. Обычно используется для удобного просмотра программ.
</li>
<li>nano, vi, jed - nano и vi уже установлены текстовые редакторы в командной строке Linux. Команда nano - хороший текстовый редактор, который помечает ключевые слова цветом и может распознавать большинство языков. И vi проще, чем nano. Вы можете создать новый файл или изменить файл с помощью этого редактора. Например, если вам нужно создать новый файл с именем «check.txt», вы можете создать его с помощью команды «nano check.txt». Вы можете сохранить ваши файлы после редактирования, используя последовательность Ctrl + X, затем Y (или N для no). По моему опыту, использование nano для редактирования HTML выглядит не очень хорошо из-за его цвета, поэтому я рекомендую jed текстовый редактор. Мы скоро приступим к установке пакетов.
</li>
<li>sudo - широко используемая команда в командной строке Linux, sudo означает «SuperUser Do». Поэтому, если вы хотите, чтобы любая команда выполнялась с правами администратора или root, вы можете использовать команду sudo. Например, если вы хотите отредактировать файл, такой как viz. alsa-base.conf, для которого требуются права root, вы можете использовать команду - sudo nano alsa-base.conf. Вы можете ввести корневую командную строку с помощью команды «sudo bash», а затем ввести свой пароль пользователя. Вы также можете использовать команду «su», но перед этим вам нужно установить пароль root. Для этого вы можете использовать команду «sudo passwd» (не с орфографической ошибкой, это passwd). Затем введите новый пароль root.
</li>
<li>df - используйте команду df, чтобы увидеть доступное дисковое пространство в каждом из разделов вашей системы. Вы можете просто ввести df в командной строке и увидеть каждый смонтированный раздел и его использованное / доступное пространство в % и в килобайтах. Если вы хотите, чтобы оно отображалось в мегабайтах, вы можете использовать команду «df -m».
</li>
<li>du - Используйте du, чтобы узнать, как файл используется в вашей системе. Если вы хотите узнать размер занимаемого места на диске для конкретной папки или файла в Linux, вы можете ввести команду df и имя папки или файла. Например, если вы хотите узнать размер дискового пространства, используемое папкой документов в Linux, вы можете использовать команду «du Documents». Вы также можете использовать команду «ls -lah», чтобы просмотреть размеры всех файлов в папке.
</li>
<li>tar - Используйте tar для работы с tarballs (или файлами, сжатыми в архиве tarball) в командной строке Linux. У него длинный список применений. Он может использоваться для сжатия и распаковки различных типов архивов tar, таких как .tar, .tar.gz, .tar.bz2 и т. д.  Это работает на основе аргументов, данных ему. К примеру, "tar -cvf" для создания .tar архива, -xvf для распаковки .tar архива, -tvf для просмотра содержимого архива и т. д. 
</li>
<li>zip, unzip - используйте zip для сжатия файлов в zip-архив и unzip для извлечения файлов из zip-архива.
</li>
<li>uname - используйте uname, чтобы показать информацию о системе, в которой работает ваш дистрибутив Linux. Использование команды «uname -a» выводит большую часть информации о системе: дату выпуска ядра, версию, тип процессора и т. д. 
</li>
<li>apt-get - используйте apt для работы с пакетами в командной строке Linux. Используйте apt-get для установки пакетов. Это команда требует прав суперпользователя, поэтому используйте команду sudo с ним. Например, если вы хотите установить текстовый редактор jed (как я упоминал ранее), мы можем ввести команду «sudo apt-get install jed». Точно так же любые пакеты могут быть установлены следующим образом. Рекомендуется обновлять ваш репозиторий каждый раз, когда вы пытаетесь установить новый пакет. Вы можете сделать это, набрав «sudo apt-get update». Вы можете обновить систему, набрав «sudo apt-get upgrade». Мы также можем обновить дистрибутив, набрав «sudo apt-get dist-upgrade». Команда «apt-cache search» используется для поиска пакета. Если вы хотите найти его, вы можете ввести «apt-cache search jed» (для этого не требуется root).
</li>
<li>chmod - используйте chmod, чтобы сделать файл исполняемым и изменить разрешения, предоставленные ему в Linux. Представьте, что на вашем компьютере есть код Python с именем numbers.py. Вам нужно будет запускать «python numbers.py» каждый раз, когда вам нужно его запустить. Вместо этого, когда вы делаете его исполняемым, вам просто нужно запустить «numbers.py» в терминале, чтобы запустить файл. Чтобы сделать файл исполняемым, вы можете использовать команду «chmod + x numbers.py» в этом случае. Вы можете использовать «chmod 755 numbers.py», чтобы дать ему права root, или «sudo chmod + x numbers.py» для исполняемого файла root.
</li>
<li>hostname - Используйте команду hostname, чтобы узнать ваше имя в вашем хосте или сети. По сути, он отображает ваше имя хоста и IP-адрес. Просто набрав «hostname», вы получите имя хоста. Набрав «hostname -I», вы получите свой IP-адрес в сети.
</li>
<li>ping - используйте ping для проверки вашего соединения с сервером. Википедия говорит: «Ping - это утилита для администрирования компьютерной сети, используемая для проверки доступности хоста в сети Интернет-протокола (IP)». Например, когда вы набираете, , «ping <a href="http://google.com/">google.com</a>», он проверяет, может ли он подключиться к серверу и вернуться обратно. Он измеряет это время в оба конца и дает вам подробную информацию о нем. Использовать эту команду можно и для проверки интернет-соединения. Если он пингует сервер Google (в данном случае) - интернет-соединение активно!
</li>
</ul>

Доп. материал:
<a href="https://cheatography.com/davechild/cheat-sheets/linux-command-line/">Linux Command Line Cheat Sheet by DaveChild</a>
<h2>Почему важно тестировать в разных браузерах?</h2>
Приложения и сайты в разных браузерах могут вести себя по-разному. Это связано с тем, что любой из браузеров имеет собственные движки, надстройки, плагины, а также различия в десктопной и мобильной версиях. Кроссбраузерное тестирование призвано сгладить эти различия, сделав разработку более или менее универсальной.
Почему возникают кросс-браузерные ошибки:
<ul>
<li>Иногда сами браузеры содержат баги или по-разному внедряют функции. Часто это происходит из-за попытки заполучить конкурентное преимущество.
</li>
<li>Некоторые браузеры могут иметь разные уровни поддержки технологических функций для других браузеров. JavaScript фичи, скорее всего, не будут работать на старых браузерах.
</li>
<li>Некоторые девайсы могут содержать ограничения, которые могут заставить веб-сайт работать медленнее или некорректно отображаться. Например, если сайт был спроектирован под десктоп, то вполне вероятно, что его контент будет сложно читать на мобильном устройстве.
</li>
<li>Приступать к тестированию сайта в популярных браузерах следует уже после того как он проверен на дефекты другими видами тестирования. Только в этом случае можно будет сказать, что выявленные некорректные сценарии имеют отношение именно к особенностям браузера, а не были пропущены на других стадиях. Разумеется, при этом ошибка должна проявляться не во всех браузерах. Внимание нужно также уделить сочетанию операционной системы и браузера, выбрав наиболее распространенные из них.
</li>
</ul>
<h2>Адаптивный веб-дизайн vs. Отзывчивый веб-дизайн, в чем разница? (Adaptive Vs. Responsive)</h2>
<img src="https://lh6.googleusercontent.com/fRFnPvlX-jzw2qOdOsmPfu2om3vH_Uz19o8XwB8LB9vMCdHWRFogQnAHZ8iniIVJdulStiL4CcXe-GSrhtfBPHWQ34RQKo7e5JEeMO3cTOFNYh31XCKVpFdsZyKH_K3xfjSTrf9u">
Responsive Design (RWD) — отзывчивый дизайн — проектирование сайта с определенными значениями свойств, например, гибкая сетка макета, которые позволяют одному макету работать на разных устройствах;
Помимо своей изменяющейся структуры, у респонсив дизайна есть несколько других преимуществ:
1. Одинаковый внешний вид ресурса в разных браузерах и на различных платформах
2. Наличие у сайта одинакового URL, что способствует SEO-оптимизации
3. Разработчикам необходимо обслуживать лишь один сайт, что позволяет сократить время, затрачиваемое на дизайн и контент
И хотя положительные стороны респонсивного дизайна очевидны, у этого метода существует ряд недостатков. Самым большим из них является скорость загрузки, которая значительно снижается из-за высокого разрешения изображений и других визуальных элементов, необходимых для оформления внешнего вида ресурса.

Adaptive Design (AWD) — адаптивный дизайн, или динамический показ — проектирование сайта с условиями, которые изменяются в зависимости от устройства, базируясь на нескольких макетах фиксированной ширины.
Для создания отзывчивых макетов используются медиазапросы и относительные размеры элементов сетки, заданные с помощью %. В адаптивном дизайне серверные скрипты сначала определяют тип устройства, с помощью которого пользователь пытается получить доступ к сайту (настольный ПК, телефон или планшет), затем загружает именно ту версию страницы, которая наиболее оптимизирована для него. Для элементов сетки задаются фиксированные в пикселях (px) размеры.
Поэтому основное отличие между этими приемами — отзывчивый дизайн — один макет для всех устройств, адаптивный дизайн — один макет для каждого вида устройства. Иными словами, сервер берет на себя всю «тяжелую» работу, вместо того, чтобы заставлять сайт оптимизировать самого себя. Среди достоинств адаптивного дизайна можно выделить следующие:
<ul>
<li>Изображения загружаются намного быстрее, так как они сжимаются и адаптируются под устройство пользователя
</li>
<li>Загрузка сайта происходит быстрее, так как сервер определяет тип устройства пользователя и загружает соответствующий ему программный код
</li>
<li>Разработчики пользуются свободой творчества, ведь они могут создавать различные версии сайтов и подгонять их под соответствующие типы устройств, чтобы сделать их более удобными для мобильных пользователей.
</li>
</ul>
Привлекательность этого метода омрачается тем, что создать адаптивный сайт не так-то просто. Из-за адаптации дизайна к различным устройствам, время, затрачиваемое на разработку, значительно увеличивается. Более того, если вам потребуется сделать какие-либо доработки на сайте, придется вносить изменения во все его версии. 
<h2>Как сервер узнает, с какого типа устройства/браузера/ОС/языка вы открываете веб-сайт? (Например, для Adaptive design)</h2>
Когда вы отправляете HTTP-запрос, он содержит в себе заголовки (headers) с различной информацией. Одним из них является User-Agent. Он сообщает: браузер, его версию и язык, движок браузера, версию движка, операционную систему. Данные могут быть написаны как угодно, однако примерный формат таков:
Браузер/Версия (Платформа; Шифрование; Система, Язык[; Что-нибудь еще]) [Дополнения].

Как еще можно определить, если не из хедеров? Определить версию и тип браузера можно при помощи JavaScript. 
<h2>Чем отличается авторизация от аутентификации?</h2>
<table>
<tr>
<td>Аутентификация
</td><td>Авторизация
</td></tr>
<tr>
<td>Процедура проверки подлинности субъекта
</td><td>Процедура присвоения и проверки прав на совершение определенных действий субъектом
</td></tr>
<tr>
<td>Зависит от предоставляемой пользователем информации
</td><td>Не зависит от действий клиента
</td></tr>
<tr>
<td>Запускается один раз для текущей сессии
</td><td>Происходит при попытке совершения любых действий пользователем
</td></tr>
</table>

<h2>Как работает авторизация/аутентификация? Как сайт понимает, что ты залогинен?</h2>
Классический вариант – регистрация по логину/почте и паролю. При входе и введении правильных данных, если данные совпадают с таковыми в базе, вы получаете доступ на сайт.

1. Т.к. протокол HTTP не отслеживает состояния, нельзя достоверно знать, что человек, залогинившийся до этого по почте и паролю остается тем же человеком. И тогда изобрели аутентификацию на основе сессий/кук, на основе которых реализовано отслеживание состояний (stateful), то есть аутентификационная запись или сессия хранятся как на сервере, так и на клиенте. Сервер отслеживает открытые сессии в базе данных или в оперативной памяти, в свою очередь на фронтенде создаются cookies, в которых хранится идентификатор сессии. Процедура аутентификации на основе сессий:
<ul>
<li>Пользователь вводит в браузере свое имя и пароль, после чего клиентское приложение отправляет на сервер запрос.
</li>
<li>Сервер проверяет пользователя, аутентифицирует его, шлет приложению уникальный пользовательский токен (сохранив его в памяти или базе данных).
</li>
<li>Клиентское приложение сохраняет токены в куках и отправляет их при каждом последующем запросе.
</li>
<li>Сервер получает каждый запрос, требующий аутентификации, с помощью токена аутентифицирует пользователя и возвращает запрошенные данные клиентскому приложению.
</li>
<li>Когда пользователь выходит, клиентское приложение удаляет его токен, поэтому все последующие запросы от этого клиента становятся неаутентифицированными.
</li>
</ul>
У этого метода есть и недостатки:
<ul>
<li>При каждой аутентификации пользователя сервер должен создавать у себя запись. Обычно она хранится в памяти, и при большом количестве пользователей есть вероятность слишком высокой нагрузки на сервер.
</li>
</ul>
<ul>
<li>Поскольку сессии хранятся в памяти, масштабировать не так просто. Если вы многократно реплицируете сервер, то на все новые серверы придется реплицировать и все пользовательские сессии. Это усложняет масштабирование. 
</li>
</ul>

2. Аутентификация на основе токенов в последние годы стала очень популярна из-за распространения одностраничных приложений (SPA), веб-API и интернета вещей. Чаще всего в качестве токенов используются Json Web Tokens (JWT). Хотя реализации бывают разные, но токены JWT превратились в стандарт де-факто.
При аутентификации на основе токенов состояния не отслеживаются (stateless). Мы не будем хранить информацию о пользователе на сервере или в сессии и даже не будем хранить JWT, использованные для клиентов.
Процедура аутентификации на основе токенов:
<ul>
<li>Пользователь вводит имя и пароль.
</li>
<li>Сервер проверяет их и возвращает токен (JWT), который может содержать метаданные вроде user_id, разрешений и т. д. 
</li>
<li>Токен хранится на клиентской стороне, чаще всего в локальном хранилище, но может лежать и в хранилище сессий или кук.
</li>
<li>Последующие запросы к серверу обычно содержат этот токен в качестве дополнительного заголовка авторизации в виде Bearer {JWT}. Еще токен может пересылаться в теле POST-запроса и даже как параметр запроса.
</li>
<li>Сервер расшифровывает JWT, если токен верный, сервер обрабатывает запрос.
</li>
<li>Когда пользователь выходит из системы, токен на клиентской стороне уничтожается, с сервером взаимодействовать не нужно.
</li>
</ul>

У метода есть ряд преимуществ:
Главное преимущество: поскольку метод никак не оперирует состояниями, серверу не нужно хранить записи с пользовательскими токенами или сессиями. Каждый токен самодостаточен, содержит все необходимые для проверки данные, а также передает затребованную пользовательскую информацию. Поэтому токены не усложняют масштабирование.
В куках вы просто храните ID пользовательских сессий, а JWT позволяет хранить метаданные любого типа, если это корректный JSON.
При использовании кук бэкенд должен выполнять поиск по традиционной SQL-базе или NoSQL-альтернативе, и обмен данными наверняка длится дольше, чем расшифровка токена. Кроме того, раз вы можете хранить внутри JWT дополнительные данные вроде пользовательских разрешений, то можете сэкономить и дополнительные обращения поисковые запросы на получение и обработку данных.
Допустим, у вас есть API-ресурс /api/orders, который возвращает последние созданные приложением заказы, но просматривать их могут только пользователи категории админов. Если вы используете куки, то, сделав запрос, вы генерируете одно обращение к базе данных для проверки сессии, еще одно обращение — для получения пользовательских данных и проверки, относится ли пользователь к админам, и третье обращение — для получения данных.
А если вы применяете JWT, то можете хранить пользовательскую категорию уже в токене. Когда сервер запросит его и расшифрует, вы можете сделать одно обращение к базе данных, чтобы получить нужные заказы.
У использования кук на мобильных платформах есть много ограничений и особенностей. А токены сильно проще реализовать на iOS и Android. К тому же токены проще реализовать для приложений и сервисов интернета вещей, в которых не предусмотрено хранение кук.
Благодаря всему этому аутентификация на основе токенов сегодня набирает популярность.
Примечание: в целях безопасности в некоторых случаях в дополнение к токену применяется сравнение user agent и подобного. В случае различия вас разлогинит. Так же, например, в банковских системах нельзя одновременно залогиниться в одну учетную запись с нескольких устройств одновременно.

3. Беспарольная аутентификация
Первой реакцией на термин «беспарольная аутентификация» может быть «Как аутентифицировать кого-то без пароля? Разве такое возможно?»
В наши головы внедрено убеждение, что пароли — абсолютный источник защиты наших аккаунтов. Но если изучить вопрос глубже, то выяснится, что беспарольная аутентификация может быть не просто безопасной, но и безопаснее традиционного входа по имени и паролю. Возможно, вы даже слышали мнение, что пароли устарели.
Беспарольная аутентификация — это способ конфигурирования процедуры входа и аутентификации пользователей без ввода паролей. Идея такая:
Вместо ввода почты/имени и пароля пользователи вводят только свою почту. Ваше приложение отправляет на этот адрес одноразовую ссылку, пользователь по ней кликает и автоматически входит на ваш сайт / в приложение. При беспарольной аутентификации приложение считает, что в ваш ящик пришло письмо со ссылкой, если вы написали свой, а не чужой адрес.
Есть похожий метод, при котором вместо одноразовой ссылки по SMS отправляется код или одноразовый пароль. Но тогда придется объединить ваше приложение с SMS-сервисом вроде twilio (и сервис не бесплатен). Код или одноразовый пароль тоже можно отправлять по почте.
И еще один, менее (пока) популярный (и доступный только на устройствах Apple) метод беспарольной аутентификации: использовать Touch ID для аутентификации по отпечаткам пальцев.  Если вы пользуетесь Slack, то уже могли столкнуться с беспарольной аутентификацией.
Medium предоставляет доступ к своему сайту только по почте. Auth0, или Facebook AccountKit, — это отличный вариант для реализации беспарольной системы для вашего приложения.
Что может пойти не так?
Если кто-то получит доступ к пользовательским почтам, он получит и доступ к приложениям и сайтам. Но это не ваша головная боль — беспокоиться о безопасности почтовых аккаунтов пользователей. Кроме того, если кто-то получит доступ к чужой почте, то сможет перехватить аккаунты в приложениях с беспарольной аутентификацией, воспользовавшись функцией восстановления пароля. Но мы ничего не можем поделать с почтой наших пользователей. Пойдем дальше.
В чем преимущества?
Как часто вы пользуетесь ссылкой «забыли пароль» для сброса пароля, который так и не смогли вспомнить после нескольких неудачных попыток входа на сайт / в приложение? Все мы бываем в такой ситуации. Все пароли не упомнишь, особенно если вы заботитесь о безопасности и для каждого сайта делаете отдельный пароль (соблюдая все эти «должен состоять не менее чем из восьми символов, содержать хотя бы одну цифру, строчную букву и специальный символ»). От всего этого вас избавит беспарольная аутентификация. Знаю, вы думаете сейчас: «Я использую менеджер паролей». Но не забывайте, что подавляющее большинство пользователей не такие техногики, как вы. Это нужно учитывать.
Если вы думаете, что какие-то пользователи предпочтут старомодные логин/пароль, то предоставьте им оба варианта, чтобы они могли выбирать.
Сегодня беспарольная аутентификация быстро набирает популярность.

4. Единая точка входа (Single Sign On, SSO)
Обращали внимание, что, когда логинишься в браузере в каком-нибудь Google-сервисе, например, Gmail, а потом идешь на Youtube или иной Google-сервис, там не приходится логиниться? Ты автоматически получаешь доступ ко всем сервисам компании. Впечатляет, верно? Ведь хотя Gmail и Youtube — это сервисы Google, но все же раздельные продукты. Как они аутентифицируют пользователя во всех продуктах после единственного входа?
Этот метод называется единой точкой входа (Single Sign On, SSO).
Реализовать его можно по-разному. Например, использовать центральный сервис для оркестрации единого входа между несколькими клиентами. В случае с Google этот сервис называется Google Accounts. Когда пользователь логинится, Google Accounts создает куку, которая сохраняется за пользователем, когда тот ходит по принадлежащим компании сервисам. Как это работает:
<ul>
<li>Пользователь входит в один из сервисов Google.
</li>
<li>Пользователь получает сгенерированную в Google Accounts куку.
</li>
<li>Пользователь идет в другой продукт Google.
</li>
<li>Пользователь снова перенаправляется в Google Accounts.
</li>
<li>Google Accounts видит, что пользователю уже присвоена кука, и перенаправляет пользователя в запрошенный продукт.
</li>
</ul>
Очень простое описание единой точки входа: пользователь входит один раз и получает доступ ко всем системам без необходимости входить в каждую из них. В этой процедуре используется три сущности, доверяющие другу прямо и косвенно. Пользователь вводит пароль (или аутентифицируется иначе) у поставщика идентификационной информации (identity provider, IDP), чтобы получить доступ к поставщику услуги (service provider (SP). Пользователь доверяет IDP, и SP доверяет IDP, так что SP может доверять пользователю.
Выглядит очень просто, но конкретные реализации бывают очень сложными. 

5. Аутентификация в соцсетях (Social sign-in) или социальным логином (Social Login). Вы можете аутентифицировать пользователей по их аккаунтам в соцсетях. Тогда пользователям не придется регистрироваться отдельно в вашем приложении.
Формально социальный логин — это не отдельный метод аутентификации. Это разновидность единой точки входа с упрощением процесса регистрации/входа пользователя в ваше приложение.
Пользователи могут войти в ваше приложение одним кликом, если у них есть аккаунт в одной из соцсетей. Им не нужно помнить логины и пароли. Это сильно улучшает опыт использования вашего приложения. Вам не нужно волноваться о безопасности пользовательских данных и думать о проверке адресов почты — они уже проверены соцсетями. Кроме того, в соцсетях уже есть механизмы восстановления пароля.
Большинство соцсетей в качестве механизма аутентификации используют авторизацию через OAuth2 (некоторые используют OAuth1, например Twitter). Разберемся, что такое OAuth. Соцсеть — это сервер ресурсов, ваше приложение — клиент, а пытающийся войти в ваше приложение пользователь — владелец ресурса. Ресурсом называется пользовательский профиль / информация для аутентификации. Когда пользователь хочет войти в ваше приложение, оно перенаправляет пользователя в соцсеть для аутентификации (обычно это всплывающее окно с URL’ом соцсети). После успешной аутентификации пользователь должен дать вашему приложению разрешение на доступ к своему профилю из соцсети. Затем соцсеть возвращает пользователя обратно в ваше приложение, но уже с токеном доступа. В следующий раз приложение возьмет этот токен и запросит у соцсети информацию из пользовательского профиля. Так работает OAuth (ради простоты я опустил технические подробности).
Для реализации такого механизма вам может понадобиться зарегистрировать свое приложение в разных соцсетях. Вам дадут app_id и другие ключи для конфигурирования подключения к соцсетям. Также есть несколько популярных библиотек/пакетов (вроде Passport, Laravel Socialite и т. д. ), которые помогут упростить процедуру и избавят от излишней возни.

6. Двухфакторная аутентификация (2FA) улучшает безопасность доступа за счет использования двух методов (также называемых факторами) проверки личности пользователя. Это разновидность многофакторной аутентификации. Наверное, вам не приходило в голову, но в банкоматах вы проходите двухфакторную аутентификацию: на вашей банковской карте должна быть записана правильная информация, и в дополнение к этому вы вводите PIN. Если кто-то украдет вашу карту, то без кода он не сможет ею воспользоваться. (Не факт! — Примеч. пер.) То есть в системе двухфакторной аутентификации пользователь получает доступ только после того, как предоставит несколько отдельных частей информации.
Другой знакомый пример — двухфакторная аутентификация Mail.Ru, Google, Facebook и т. д.  Если включен этот метод входа, то сначала вам нужно ввести логин и пароль, а затем одноразовый пароль (код проверки), отправляемый по SMS. Если ваш обычный пароль был скомпрометирован, аккаунт останется защищенным, потому что на втором шаге входа злоумышленник не сможет ввести нужный код проверки.
Вместо одноразового пароля в качестве второго фактора могут использоваться отпечатки пальцев или снимок сетчатки.
При двухфакторной аутентификации пользователь должен предоставить два из трех:
То, что вы знаете: пароль или PIN.
То, что у вас есть: физическое устройство (смартфон) или приложение, генерирующее одноразовые пароли.
Часть вас: биологически уникальное свойство вроде ваших отпечатков пальцев, голоса или снимка сетчатки.
Большинство хакеров охотятся за паролями и PIN-кодами. Гораздо труднее получить доступ к генератору токенов или биологическим свойствам, поэтому сегодня двухфакторка обеспечивает высокую безопасность аккаунтов.
И все же двухфакторка поможет усилить безопасность аутентификации в вашем приложении. Как реализовать? Возможно, стоит не велосипедить, а воспользоваться существующими решениями вроде Auth0 или Duo.

Доп. материал:
<ul>
<li><a href="https://gist.github.com/zmts/802dc9c3510d79fd40f9dc38a12bccfc">Про токены, JSON Web Tokens (JWT), аутентификацию и авторизацию. Token-Based Authentication</a>
</li>
<li><a href="https://developer.mozilla.org/ru/docs/Web/HTTP/%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F">HTTP авторизация</a>
</li>
</ul>
<h2>Почему важно делать подтверждение e-mail при регистрации?</h2>
<ul>
<li>Основная причина — это провести double opt-in, т.е. убедиться, что был введён валидный адрес пользователя и этот пользователь действительно дает свое согласие на регистрацию на данном ресурсе и получение дополнительных рассылок/писем. Это позволяет отсеивать "мусорные" регистрации, когда подписывают на что-нибудь посторонних людей (намеренно или нет), уменьшать количество спама (за что очень больно бьют по рукам) и т. д. 
</li>
<li>Для защиты страницы. Если кто-нибудь попытается получить доступ к аккаунту пользователя, то на почту пользователя придет соответствующее уведомление.
</li>
<li>Для быстрого и самостоятельного восстановления доступа (логина и пароля). Многие пользователи испытывают затруднения при восстановлении доступа, если не указали email при регистрации.
</li>
<li>Для отправки электронного чека после оплаты услуг сервиса.
</li>
<li>Для защиты от ботов.
</li>
<li>Если не подтверждать емайл, то в этом поле можно будет написать все что угодно (в рамках проверки). Соответственно один и тот же пользователь будет регистрироваться множество раз, забывая и свой предыдущий пароль, и логин.
</li>
</ul>
<h2>Что такое кэш и зачем его очищать при тестировании?</h2>
Кэш — это временное хранилище для данных (перечень определен создателем сайта) с посещенного сайта. Во-первых, многие элементы на страницах сайта одинаковы: изображения, HTML, CSS, JavaScript и нет смысла каждый раз загружать их заново. Во-вторых, при повторном открытии той же самой страницы действует та же логика – эти элементы уже были загружены, ни к чему грузить их каждый раз по новой.
Сохранение данных веб-страниц на компьютере, вместо их повторной загрузки, помогает экономить время открытия веб-сайтов в браузере и трафик, но с другой стороны снижает срок службы SSD-накопителей, так что вы всегда можете полностью отключить кеширование в своем браузере. 
Виды кеширования:
<ul>
<li>Кэширование в браузере. Устройство пользователя создает и сохраняет копию различных элементов сайта. Это могут быть: скрипты, текст, изображения и т. д.  При открытии страницы кэш браузера помогает загрузить все это в разы быстрее.
</li>
</ul>
<ul>
<li>Кэширование на сервере. Все данные хранятся на сервере. Он сохраняет результаты запросов, что помогает избежать повторной обработки одной и той же информации от пользователя.
</li>
</ul>

В тестировании практически во всех случаях правило – очищать кэш после каждого прохода теста (если только это не целенаправленной тестирование самого кэша или требуется наличие кэша по каким-либо причинам). Дело в том, что кэш очевидно искажает показатели performance testing, а также может быть причиной ошибочного дефект-репорта из-за устаревания и/или несогласованности актуальных и сохраненных данных. В некоторых ситуациях без очистки кеша не обойтись даже просто из-за огромного количества кешируемых данных. 
<h2>Что такое AJAX в вебе?</h2>
Ajax ( Asynchronous Javascript and XML — «асинхронный JavaScript и XML») — подход к построению интерактивных пользовательских интерфейсов веб-приложений, заключающийся в «фоновом» обмене данными браузера с веб-сервером. В результате при обновлении данных веб-страница не перезагружается полностью, и веб-приложения становятся быстрее и удобнее. По-русски иногда произносится транслитом как «аякс». У аббревиатуры AJAX нет устоявшегося аналога на кириллице.

В классической модели веб-приложения:
<ul>
<li>Пользователь заходит на веб-страницу и нажимает на какой-нибудь ее элемент.
</li>
<li><a href="https://ru.wikipedia.org/wiki/%D0%91%D1%80%D0%B0%D1%83%D0%B7%D0%B5%D1%80">Браузер</a> формирует и отправляет <a href="https://ru.wikipedia.org/wiki/HTTP">запрос</a> <a href="https://ru.wikipedia.org/wiki/%D0%92%D0%B5%D0%B1-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80">серверу</a>.
</li>
<li>В ответ сервер генерирует совершенно новую веб-страницу и отправляет ее браузеру и т. д. , после чего браузер полностью перезагружает всю страницу.
</li>
</ul>
При использовании AJAX:
<ul>
<li>Пользователь заходит на веб-страницу и нажимает на какой-нибудь ее элемент.
</li>
<li><a href="https://ru.wikipedia.org/wiki/JavaScript">JavaScript</a> определяет, какая информация необходима для обновления страницы.
</li>
<li><a href="https://ru.wikipedia.org/wiki/%D0%91%D1%80%D0%B0%D1%83%D0%B7%D0%B5%D1%80">Браузер</a> отправляет соответствующий запрос на <a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D1%80%D0%B2%D0%B5%D1%80_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)">сервер</a>.
</li>
<li>Сервер возвращает только ту часть документа, на которую пришел запрос.
</li>
<li><a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%BA%D1%80%D0%B8%D0%BF%D1%82">Скрипт</a> вносит изменения с учетом полученной информации (без полной перезагрузки страницы).
</li>
</ul>
<h2>Как работает браузер (коротко)?</h2>
Типичный сценарий использования предполагает отправку на некий сервер GET запроса и отображение полученного ответа. При этом происходит много всего: резолв домена в DNS -> получение целевого IP ->  TCP/IP финты -> на запрос отдается запрашиваемая страница. Отображение страницы тоже не такой простой процесс:
<img src="https://lh6.googleusercontent.com/_KvSpWy1Yk99GutocX7GamEGLrZuWECkParlBDDKAitmdxSGYHdc7nbf216d7QoEIjdNeKtOTND9eh77RnUz7MKISysFdljmRPH9TLALZeGoi4J31paKq1sJ6l09zAoi4HSke5fy">
Модуль отображения выполняет синтаксический анализ полученного HTML-документа и переводит теги в узлы DOM(DOM – объектная модель документа (Document Object Model) – служит для представления HTML-документа и интерфейса элементов HTML таким внешним объектам, как код JavaScript.) в дереве содержания. Информация о стилях извлекается как из внешних CSS-файлов, так и из элементов style. Эта информация и инструкции по отображению в HTML-файле используются для создания еще одного дерева – дерева отображения.
Оно содержит прямоугольники с визуальными атрибутами, такими как цвет и размер. Прямоугольники располагаются в том порядке, в каком они должны быть выведены на экран.
После создания дерева отображения начинается компоновка элементов, в ходе которой каждому узлу присваиваются координаты точки на экране, где он должен появиться. Затем выполняется отрисовка, при которой узлы дерева отображения последовательно отрисовываются с помощью исполнительной части пользовательского интерфейса.

Доп. материал:
<ul>
<li><a href="https://m.habr.com/en/company/htmlacademy/blog/254825/">Что на самом деле происходит, когда пользователь вбивает в браузер адрес google.com</a>
</li>
<li><a href="https://vc.ru/selectel/76371-chto-proishodit-kogda-polzovatel-nabiraet-v-brauzere-adres-sayta">Что происходит, когда пользователь набирает в браузере адрес сайта</a>
</li>
<li><a href="https://medium.com/@maneesha.wijesinghe1/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a">What happens when you type a URL in the browser and press enter?</a>
</li>
</ul>
<h2>Как работает сотовая связь?</h2>
Почему связь «сотовая»? Если посмотреть сверху на схему сети базовых станций, то их пересекающиеся краями круги покрытия похожи на пчелиные соты.
Сотовая связь потому и называется сотовой, что в основе любой сети — ячейки (соты), каждая сота представляет собой участок территории, который покрывает (обслуживает) базовая станция. Форма и размеры сот зависят от множества факторов, в том числе от мощности излучения базовой станции, стандарта, рабочих частот, направления антенн и т.п. Соты обязательно перекрывают друг друга, это необходимо для того, чтобы мобильное устройство (терминал) не теряло связь при перемещении из одной соты в другую. Особенно это важно для владельца сотового телефона, который разговаривает во время движения.
В условиях городской застройки невозможно разбить карту города на квадратики и поставить базовые станции через равные расстояния, чтобы добиться качественного покрытия. Начинают играть роль этажность застройки, препятствия в виде памятников, возможность установить базовые станции в том или ином месте. Не зря наши города назвали каменными джунглями, планирование в них радиосетей – это та еще задачка. Поэтому все операторы стараются резервировать дополнительные мощности в крупных городах, создавать перекрывающиеся зоны для базовых станций. И этому есть и другая причина.
Для эффективной работы сети одного покрытия мало, базовые станции должны обслуживать одновременно много пользователей. А в городах — очень много одновременно разговаривающих и пользующихся мобильным интернетом. Полосы частот, на которых передаются голос и данные, — ограниченный и крайне ценный ресурс, за их лицензирование операторы во всем мире платят государству большие деньги.

Когда вы набираете номер и начинаете звонить, ну, или вам кто-нибудь звонит, то ваш мобильный телефон по радиоканалу связывается с одной из антенн ближайшей базовой станции. От антенны сигнал по кабелю передается непосредственно в управляющий блок станции. Базовая станция должна выделить вам свободный голосовой канал. Вместе они и образуют базовую станцию [антенны и управляющий блок]. Несколько базовых станций, чьи антенны обслуживают отдельную территорию, например, район города или небольшой населенный пункт, подсоединены к специальному блоку – контроллеру. К одному контроллеру обычно подключается до 15 базовых станций. В свою очередь, контроллеры, которых также может быть несколько, кабелями подключены к «мозговому центру» – коммутатору. Коммутатор обеспечивает выход и вход сигналов на городские телефонные линии, на других операторов сотовой связи, а также операторов междугородней и международной связи.
В небольших сетях используется только один коммутатор, в более крупных, обслуживающих сразу более миллиона абонентов, могут использоваться два, три и более коммутаторов, объединенных между собой опять-таки проводами.
Когда человек передвигается по улице пешком или идет на автомобиле, поезде и т. д.  и при этом еще и разговаривает по телефону, важно обеспечить непрерывность связи. Связисты процесс эстафетной передачи обслуживания в мобильных сетях называют термином «handover». Необходимо вовремя переключать телефон абонента из одной базовой станции на другую, от одного контроллера к другому и так далее. 
Если бы базовые станции были напрямую подключены к коммутатору, то всеми этими переключениями пришлось бы управлять коммутатору. А ему «бедному» и так есть, чем заняться. Многоуровневая схема сети дает возможность равномерно распределить нагрузку на технические средства. Это снижает вероятность отказа оборудования и, как следствие, потери связи. Итак, достигнув коммутатора, наш звонок переводится далее – на сеть другого оператора мобильной, городской междугородной и международной связи. Конечно же, это происходит по высокоскоростным кабельным каналам связи. Звонок поступает на коммутатор другого оператора. При этом последний «знает», на какой территории [в области действия, какого контроллера] сейчас находится нужный абонент. Коммутатор передает телефонный вызов конкретному контроллеру, в котором содержится информация, в зоне действия какой базовой станции находится адресат звонка. Контроллер посылает сигнал этой единственной базовой станции, а она в свою очередь «опрашивает», то есть вызывает мобильный телефон. Точно также происходят телефонные звонки в разные города России, Европы и мира. Для связи коммутаторов различных операторов связи используются высокоскоростные оптоволоконные каналы связи. Благодаря им сотни тысяч километров телефонный сигнал преодолевает за считанные секунды или даже доли секунд.
<h2>Как работает подключение к Wi-Fi?</h2>
<ul>
<li>Начинает процесс подключения клиент, отправляя широковещательное сообщение Обнаружения DHCP (DHCP DISCOVER), в качестве обязательных полей передается номер транзакции - xid, MAC-адрес устройства - chaddr, также в опциях передается последний присвоенный клиенту IP-адрес, однако данная опция может быть проигнорирована сервером.
</li>
<li>Запрос обнаружения рассылается для всех узлов сети, но отвечают на него только DHCP-сервера, формируя сообщение Предложения DHCP (DHCP OFFER), которое содержит предлагаемую сервером сетевую конфигурацию. Если серверов несколько, то предложений клиент получит несколько. Из предложенных конфигураций клиент выбирает одну, как правило полученную первой.
</li>
<li>Так как MAC-адрес отправителя известен, то сервер направляет ответ непосредственно клиенту (unicast), хотя в некоторых случаях может ответить и широковещательным пакетом. 
</li>
<li>Приняв предложение, клиент официально запрашивает у сервера данную конфигурацию, для чего отправляет широковещательно Запрос DHCP (DHCP REQUEST), он полностью повторяет по структуре сообщение обнаружения (Discover), только добавляет к нему опцию 54 с адресом сервера, конфигурацию которого клиент принял. Опция 50 содержит предложенный сервером IP-адрес. Несмотря на то, что MAC-адрес DHCP-сервера известен, запрос (Request) рассылается широковещательно, это нужно для того, чтобы остальные DHCP-сервера понимали, что их предложение отвергнуто.
</li>
<li>Получив запрос сервер направляет клиенту в ответ Подтверждение DHCP (DHCP ACK), которое отправляется на MAC-адрес клиента (хотя может и широковещательно) и, получив которое, клиент должен настроить свой сетевой адаптер согласно указанному адресу и опциям.
</li>
<li>Получив адрес, клиент может проверить его на предмет использования при помощи широковещательного ARP-запроса (в большинстве реализаций так и происходит) и если будет обнаружено, что выделенный адрес уже используется (скажем, назначен вручную), то клиент посылает широковещательное сообщение Отказа DHCP (DHCP DECLINE) и начинает процесс получения адреса заново. Сервер, получив сообщение отказа, должен пометить указанный адрес как недоступный и уведомить администратора о возможной проблеме в конфигурации (например, записью в логе).
</li>
</ul>

После этого, все устройства, находящиеся во внутренней сети, будут выходить в Интернет через роутер под одним внешним IP-адресом, но в локальной сети они будут иметь разный IP.


<h1>----- Базы данных -----</h1>
<h2>Базовые понятия?</h2>
<ul>
<li>Информация - любые сведения о каком-либо событии, процессе, объекте. 
</li>
<li>Данные — это информация, представленная в определенном виде, позволяющем автоматизировать ее сбор, хранение и дальнейшую обработку человеком или информационным средством. Для компьютерных технологий данные — это информация в дискретном, фиксированном виде, удобная для хранения, обработки на ЭВМ, а также для передачи по каналам связи. 
</li>
<li>База данных (БД) — именованная совокупность данных, отражающая состояние объектов и их отношений в рассматриваемой предметной области, или иначе БД — это совокупность взаимосвязанных данных при такой минимальной избыточности, которая допускает их использование оптимальным образом для одного или нескольких приложений в определенной предметной области. БД состоит из множества связанных файлов. 
</li>
<li>Система управления базами данных (СУБД) — DBMS - Database management system - совокупность языковых и программных средств, предназначенных для создания, ведения и совместного использования БД многими пользователями. Автоматизированная информационная система (АИС) — это система, реализующая автоматизированный сбор, обработку, манипулирование данными, функционирующая на основе ЭВМ и других технических средств и включающая соответствующее программное обеспечение (ПО) и персонал. 
</li>
<li>Банк данных (БнД) является разновидностью ИС. БНД — это система специальным образом организованных данных: баз данных, программных, технических, языковых, организационно-методических средств, предназначенных для обеспечения централизованного накопления и коллективного многоцелевого использования данных. 
</li>
<li>Модель – способ структурирования данных, описания взаимосвязей между данными:
</li>
<li>Иерархическая модель. Модель представляет данные в виде иерархии. Модель ориентирована на описание объектов, находящихся между собой в неких отношениях. Например, структура кадров некоторой организации.
</li>
<li>Сетевая модель. Сетевая модель представляет собой развитие иерархической. Модель позволяет описывать более сложные виды взаимоотношений между данными. Однако расширение возможностей достигается за счет большей сложности реализации самой модели и трудности манипулирования данными.
</li>
<li>Реляционная модель. В реляционной модели данные представляются в виде таблиц, состоящих из строк и столбцов. Каждая строка таблицы – информация об одном конкретном объекте, столбцы содержат свойства этого объекта. Взаимоотношения между объектами задаются с помощью связей между столбцами таблиц. Реляционная модель на сегодняшний день наиболее распространена. Она достаточно универсальна и проста в проектировании. Строки таблиц называют записями или кортежами, столбцы – полями или атрибутами. Для того чтобы можно было сослаться на отдельную запись (строку) в некоторой таблице, каждая запись этой таблицы должна содержать уникальный идентификатор. Поле таблицы, значения которого гарантированно уникальны для каждой записи этой таблицы, называют ключевым полем или ключом. Ключ не обязательно должен быть числовым. Иногда уникальным идентификатором может служить не одно поле, а комбинация полей. При этом сочетание значений этих полей должно быть уникальным. Такие поля образуют составной ключ таблицы
</li>
<li>Объектная модель. В этой модели данные представляются в форме объектов. Объект имеет набор свойств, называемых атрибутами, и может включать в себя также процедуры для обработки данных, которые называют методами. Объекты, имеющие одинаковые наборы атрибутов и различающиеся только их значениями, образуют некоторый класс объектов. Например, класс «клиент» может иметь следующие атрибуты: «фамилия», «имя», «отчество», «номер кредитной карты». Для каждого объекта из этого класса определены конкретные значения перечисленных атрибутов. Говорят, что объект является экземпляром класса. На основе существующего класса могут создаваться новые, наследующие свойства исходного. При этом исходный класс именуется родителем нового класса. Производный класс называют потомком исходного. При этом объекты – экземпляры класса-потомка принадлежат также и родительскому классу, поскольку обладают всеми его атрибутами. Пример: на основе класса «клиент» может быть определен класс «постоянный клиент»
</li>
<li>Гибридные модели. В некоторых приложениях предпринимаются попытки смешения различных моделей представления данных. Пример такого смешения – объектно-реляционная модель. В ней использовано некоторое сходство между реляционной и объектной идеологией. Строки таблиц реляционной модели соответствуют объектам объектной модели, столбцы таблиц – атрибутам объектов. Таблицы в целом являются аналогом классов. Отсюда вытекает возможность введения наследования при определении таблиц – таблица-потомок содержит те же столбцы, что и родительская, и, кроме того – дополнительные, определенные при наследовании. По идее создателей, объектно-реляционная модель должна унаследовать от реляционной легкость описания и манипулирования данными, а от объектной – возможность определения более сложных взаимоотношений между объектами.
</li>
</ul>

Доп. материал:
<a href="https://habr.com/ru/company/yandex/blog/522164/">Базы данных: большой обзор типов и подходов. Доклад Яндекса</a>
<h2>Может ли у ПО быть сразу несколько баз данных?</h2>
Может и даже разного типа. Но в простых случаях делать это стоит только когда все упрется в предел производительности. Начиная с миллиардов записей у одной даже хорошо оптимизированной БД на одной hardware дисковой подсистеме уже могут начаться проблемы с performance, поэтому компания может принять решение разнести одну базу на несколько баз на разных серверах, но вместе с этим появляются вопросы к сетевому аспекту этого решения (задержки и т.п.). Помимо производительности, разделение на несколько БД может быть в угоду безопасности.
<h2>Что такое SQL?</h2>
structured query language — «язык структурированных запросов» — декларативный язык программирования, применяемый для создания, модификации и управления данными в реляционной базе данных, управляемой соответствующей системой управления базами данных.
<h2>Что вы знаете о NoSQL?</h2>
"NoSQL" имеет абсолютно стихийное происхождение и не имеет общепризнанного определения или научного учреждения за спиной. Это название скорее характеризует вектор развития ИТ в сторону от реляционных баз данных. Расшифровывается как Not Only SQL. Базы данных NoSQL специально созданы для определенных моделей данных и обладают гибкими схемами, что позволяет разрабатывать современные приложения. Базы данных NoSQL получили широкое распространение в связи с простотой разработки, функциональностью и производительностью при любых масштабах. 

Доп. материал:
<a href="https://aws.amazon.com/ru/nosql/">Что такое NoSQL? | Нереляционные базы данных, модели данных с гибкой схемой | AWS</a>
<h2>Что такое транзакция?</h2>
Транзакция — это набор операций по работе с базой данных (БД), объединенных в одну атомарную пачку. Или, если говорить по-научному, то транзакция — упорядоченное множество операций, переводящих базу данных из одного согласованного состояния в другое. Согласованное состояние — это состояние, которое подходит под бизнес-логику системы.
Источник: <a href="https://habr.com/ru/post/537594/">Что такое транзакция</a>
<h2>Что такое нормальные формы?</h2>
Терминология:
<ul>
<li>Атрибут — свойство некоторой сущности. Часто называется полем таблицы.
</li>
<li>Домен атрибута — множество допустимых значений, которые может принимать атрибут.
</li>
<li>Кортеж — конечное множество взаимосвязанных допустимых значений атрибутов, которые вместе описывают некоторую сущность (строка таблицы).
</li>
<li>Отношение — конечное множество кортежей (таблица).
</li>
<li>Схема отношения — конечное множество атрибутов, определяющих некоторую сущность. Иными словами, это структура таблицы, состоящей из конкретного набора полей.
</li>
<li>Проекция — отношение, полученное из заданного путем удаления и (или) перестановки некоторых атрибутов.
</li>
<li>Функциональная зависимость между атрибутами (множествами атрибутов) X и Y означает, что для любого допустимого набора кортежей в данном отношении: если два кортежа совпадают по значению X, то они совпадают по значению Y. Например, если значение атрибута «Название компании» — Canonical Ltd, то значением атрибута «Штаб-квартира» в таком кортеже всегда будет Millbank Tower, London, United Kingdom. Обозначение: {X} -> {Y}.
</li>
<li>Нормальная форма — требование, предъявляемое к структуре таблиц в теории реляционных баз данных для устранения из базы избыточных функциональных зависимостей между атрибутами (полями таблиц).
</li>
<li>Метод нормальных форм (НФ) состоит в сборе информации о объектах решения задачи в рамках одного отношения и последующей декомпозиции этого отношения на несколько взаимосвязанных отношений на основе процедур нормализации отношений.
Цель нормализации: исключить избыточное дублирование данных, которое является причиной аномалий, возникших при добавлении, редактировании и удалении кортежей(строк таблицы).
</li>
<li>Аномалией называется такая ситуация в таблице БД, которая приводит к противоречию в БД либо существенно усложняет обработку БД. Причиной является излишнее дублирование данных в таблице, которое вызывается наличием функциональных зависимостей от не ключевых атрибутов.
</li>
<li>Аномалии-модификации проявляются в том, что изменение одних данных может повлечь просмотр всей таблицы и соответствующее изменение некоторых записей таблицы.
</li>
<li>Аномалии-удаления — при удалении какого-либо кортежа из таблицы может пропасть информация, которая не связана на прямую с удаляемой записью.
</li>
<li>Аномалии-добавления возникают, когда информацию в таблицу нельзя поместить, пока она не полная, либо вставка записи требует дополнительного просмотра таблицы.
</li>
</ul>

Нормальные формы:
<ul>
<li>Первая нормальная форма: Отношение находится в 1НФ, если все его атрибуты являются простыми, все используемые домены должны содержать только скалярные значения. Не должно быть повторений строк в таблице.
</li>
<li>Вторая нормальная форма: Отношение находится во 2НФ, если оно находится в 1НФ и каждый не ключевой атрибут неприводимо зависит от Первичного Ключа(ПК).
Неприводимость означает, что в составе потенциального ключа отсутствует меньшее подмножество атрибутов, от которого можно также вывести данную функциональную зависимость.
</li>
<li>Третья нормальная форма: Отношение находится в 3НФ, когда находится во 2НФ и каждый не ключевой атрибут нетранзитивно зависит от первичного ключа. Проще говоря, второе правило требует выносить все не ключевые поля, содержимое которых может относиться к нескольким записям таблицы в отдельные таблицы.
</li>
<li>Четвертая нормальная форма: Отношение находится в 4НФ, если оно находится в НФБК и все нетривиальные многозначные зависимости фактически являются функциональными зависимостями от ее потенциальных ключей. В отношении R (A, B, C) существует многозначная зависимость R.A -> -> R.B в том и только в том случае, если множество значений B, соответствующее паре значений A и C, зависит только от A и не зависит от С.
</li>
<li>Пятая нормальная форма: Отношения находятся в 5НФ, если оно находится в 4НФ и отсутствуют сложные зависимые соединения между атрибутами. Если «Атрибут_1» зависит от «Атрибута_2», а «Атрибут_2» в свою очередь зависит от «Атрибута_3», а «Атрибут_3» зависит от «Атрибута_1», то все три атрибута обязательно входят в один кортеж. Это очень жесткое требование, которое можно выполнить лишь при дополнительных условиях. На практике трудно найти пример реализации этого требования в чистом виде.
</li>
<li>Шестая нормальная форма: Переменная отношения находится в шестой нормальной форме тогда и только тогда, когда она удовлетворяет всем нетривиальным зависимостям соединения. Из определения следует, что переменная находится в 6НФ тогда и только тогда, когда она неприводима, то есть не может быть подвергнута дальнейшей декомпозиции без потерь. Каждая переменная отношения, которая находится в 6НФ, также находится и в 5НФ. Идея «декомпозиции до конца» выдвигалась до начала исследований в области хронологических данных, но не нашла поддержки. Однако для хронологических баз данных максимально возможная декомпозиция позволяет бороться с избыточностью и упрощает поддержание целостности базы данных.
</li>
</ul>
<h2>Понятие хранимой процедуры?</h2>
Хранимые процедуры представляют собой группы связанных между собой операторов SQL, применение которых делает работу программиста более легкой и гибкой, поскольку выполнить хранимую процедуру часто оказывается гораздо проще, чем последовательность отдельных операторов SQL. Хранимые процедуры представляют собой набор команд, состоящий из одного или нескольких операторов SQL или функций и сохраняемый в базе данных в откомпилированном виде.
<h2>Понятие триггера?</h2>
Три́ггер (англ. trigger) — хранимая процедура особого типа, которую пользователь не вызывает непосредственно, а исполнение которой обусловлено действием по модификации данных: добавлением INSERT, удалением DELETE строки в заданной таблице, или изменением UPDATE данных в определенном столбце заданной таблицы реляционной базы данных. Триггеры применяются для обеспечения целостности данных и реализации сложной бизнес-логики. Триггер запускается автоматически при попытке изменения данных в таблице, с которой он связан. Все производимые им модификации данных рассматриваются как выполняемые в транзакции, в которой выполнено действие, вызвавшее срабатывание триггера. Соответственно, в случае обнаружения ошибки или нарушения целостности данных может произойти откат этой транзакции.
<h2>Что такое индексы? (Indexes)</h2>
Индекс - объект базы данных, создаваемый с целью повышения производительности поиска данных. Таблицы в базе данных могут иметь большое количество строк, которые хранятся в произвольном порядке, и их поиск по заданному критерию путем последовательного просмотра таблицы строка за строкой может занимать много времени. Индекс формируется из значений одного или нескольких столбцов таблицы и указателей на соответствующие строки таблицы и, таким образом, позволяет искать строки, удовлетворяющие критерию поиска. Ускорение работы с использованием индексов достигается в первую очередь за счет того, что индекс имеет структуру, оптимизированную под поиск — например, сбалансированного дерева. Различные типы индексов:
<ul>
<li>B-Tree index
</li>
<li>Bitmap index
</li>
<li>Clustered index
</li>
<li>Covering index
</li>
<li>Non-unique index
</li>
<li>Unique index
</li>
</ul>
<h2>Какие шаги выполняет тестировщик при тестировании хранимых процедур?</h2>
Тестировщик проверяет стандартный формат хранимых процедур, а также проверяет правильность полей, таких как updates, joins, indexes, deletions как указано в хранимой процедуре.
<h2>Как бы вы узнали для тестирования базы данных, сработал триггер или нет?</h2>
В журнале аудита (audit log) вы можете увидеть срабатывание триггеров.
<h2>Как тестировать загрузку данных при тестировании базы данных?</h2>
<ul>
<li>Исходные данные должны быть известны 
</li>
<li>Целевые данные должны быть известны 
</li>
<li>Совместимость источника и цели должна быть проверена 
</li>
<li>В диспетчере SQL Enterprise запустите пакет DTS после открытия соответствующего пакета DTS. 
</li>
<li>Вы должны сравнить столбцы цели и источника данных 
</li>
<li>Количество строк цели и источника должны быть проверены 
</li>
<li>После обновления данных в источнике проверьте, появляются ли изменения в цели или нет. 
</li>
<li>Проверьте на NULL и ненужные символы
</li>
</ul>
<h2>Основные команды SQL?</h2>
<ul>
<li>Просмотр доступных баз данных
</li>
</ul>
SHOW DATABASES;
<ul>
<li>Создание новой базы данных
</li>
</ul>
CREATE DATABASE;
<ul>
<li>Выбор базы данных для использования
</li>
</ul>
USE <database_name>; 
<ul>
<li>Импорт SQL-команд из файла .sql
</li>
</ul>
SOURCE <path_of_.sql_file>; 
<ul>
<li>Удаление базы данных
</li>
</ul>
DROP DATABASE <database_name>; 
<ul>
<li>Просмотр таблиц, доступных в базе данных
</li>
</ul>
SHOW TABLES; 
<ul>
<li>Создание новой таблицы
</li>
</ul>
CREATE TABLE <table_name1> (
<col_name1> <col_type1>,
<col_name2> <col_type2>,
<col_name3> <col_type3>
PRIMARY KEY (<col_name1>),
FOREIGN KEY (<col_name2>) REFERENCES <table_name2>(<col_name2>)
); 
<ul>
<li>Добавление данных в таблицу
</li>
</ul>
INSERT INTO <table_name> (<col_name1>, <col_name2>, <col_name3>, …)
VALUES (<value1>, <value2>, <value3>, …); 
При добавлении данных в каждый столбец таблицы не требуется указывать названия столбцов.
INSERT INTO <table_name>
VALUES (<value1>, <value2>, <value3>, …); 
<ul>
<li>Обновление данных таблицы
</li>
</ul>
UPDATE <table_name>
SET <col_name1> = <value1>, <col_name2> = <value2>, ...
WHERE <condition>; 
<ul>
<li>Удаление всех данных из таблицы
</li>
</ul>
DELETE FROM <table_name>; 
<ul>
<li>Удаление таблицы
</li>
</ul>
DROP TABLE <table_name>; 
SELECT используется для получения данных из определенной таблицы:
SELECT <col_name1>, <col_name2>, …
FROM <table_name>; 
<ul>
<li>Следующей командой можно вывести все данные из таблицы:
</li>
</ul>
SELECT * FROM <table_name>; 
SELECT DISTINCT
<ul>
<li>В столбцах таблицы могут содержаться повторяющиеся данные. Используйте SELECT DISTINCT для получения только неповторяющихся данных.
</li>
</ul>
SELECT DISTINCT <col_name1>, <col_name2>, …
FROM <table_name>; 
WHERE
<ul>
<li>Можно использовать ключевое слово WHERE в SELECT для указания условий в запросе:
</li>
</ul>
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
WHERE <condition>; 
<ul>
<li>В запросе можно задавать следующие условия:
</li>
</ul>
сравнение текста;
сравнение численных значений;
логические операции AND (и), OR (или) и NOT (отрицание).
Пример
Попробуйте выполнить следующие команды. Обратите внимание на условия, заданные в WHERE:
SELECT * FROM course WHERE dept_name=’Comp. Sci.’;
SELECT * FROM course WHERE credits>3;
SELECT * FROM course WHERE dept_name='Comp. Sci.' AND credits>3; 
<ul>
<li>Оператор GROUP BY часто используется с агрегатными функциями, такими как COUNT, MAX, MIN, SUM и AVG, для группировки выходных значений.
</li>
</ul>
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
GROUP BY <col_namex>; 
Пример
Выведем количество курсов для каждого факультета:
SELECT COUNT(course_id), dept_name
FROM course
GROUP BY dept_name; 
<ul>
<li>Ключевое слово HAVING было добавлено в SQL потому, что WHERE не может быть использовано для работы с агрегатными функциями.
</li>
</ul>
SELECT <col_name1>, <col_name2>, ...
FROM <table_name>
GROUP BY <column_namex>
HAVING <condition> 
Пример
Выведем список факультетов, у которых более одного курса:
SELECT COUNT(course_id), dept_name
FROM course
GROUP BY dept_name
HAVING COUNT(course_id)>1; 
<ul>
<li>ORDER BY используется для сортировки результатов запроса по убыванию или возрастанию. ORDERBY отсортирует по возрастанию, если не будет указан способ сортировки ASC или DESC.
</li>
</ul>
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
ORDER BY <col_name1>, <col_name2>, … ASC|DESC; 
Пример
Выведем список курсов по возрастанию и убыванию количества кредитов:
SELECT * FROM course ORDER BY credits;
SELECT * FROM course ORDER BY credits DESC; 
<ul>
<li>BETWEEN используется для выбора значений данных из определенного промежутка. Могут быть использованы числовые и текстовые значения, а также даты.
</li>
</ul>
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
WHERE <col_namex> BETWEEN <value1> AND <value2>; 
Пример
Выведем список инструкторов, чья зарплата больше 50 000, но меньше 100 000:
SELECT * FROM instructor
WHERE salary BETWEEN 50000 AND 100000; 
<ul>
<li>Оператор LIKE используется в WHERE, чтобы задать шаблон поиска похожего значения.
</li>
</ul>
Есть два свободных оператора, которые используются в LIKE:
% (ни одного, один или несколько символов);
_ (один символ).
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
WHERE <col_namex> LIKE <pattern>; 
Пример
Выведем список курсов, в имени которых содержится «to», и список курсов, название которых начинается с «CS-»:
SELECT * FROM course WHERE title LIKE ‘%to%’;
SELECT * FROM course WHERE course_id LIKE 'CS-___'; 
<ul>
<li>С помощью IN можно указать несколько значений для оператора WHERE:
</li>
</ul>
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
WHERE <col_namen> IN (<value1>, <value2>, …); 
Пример
Выведем список студентов с направлений Comp. Sci., Physics и Elec. Eng.:
SELECT * FROM student
WHERE dept_name IN (‘Comp. Sci.’, ‘Physics’, ‘Elec. Eng.’); 
<ul>
<li>JOIN используется для связи двух или более таблиц с помощью общих атрибутов внутри них. 
</li>
<li>View — это виртуальная таблица SQL, созданная в результате выполнения выражения. Она содержит строки и столбцы и очень похожа на обычную SQL-таблицу. View всегда показывает самую свежую информацию из базы данных.
</li>
</ul>
Создание
CREATE VIEW <view_name> AS
SELECT <col_name1>, <col_name2>, …
FROM <table_name>
WHERE <condition>; 
Удаление
DROP VIEW <view_name>; 
Пример
Создадим view, состоящую из курсов с 3 кредитами:
<ul>
<li>24. Агрегатные функции - эти функции используются для получения совокупного результата, относящегося к рассматриваемым данным. Ниже приведены общеупотребительные агрегированные функции:
</li>
</ul>
COUNT (col_name) — возвращает количество строк;
SUM (col_name) — возвращает сумму значений в данном столбце;
AVG (col_name) — возвращает среднее значение данного столбца;
MIN (col_name) — возвращает наименьшее значение данного столбца;
MAX (col_name) — возвращает наибольшее значение данного столбца.
<ul>
<li>Вложенные подзапросы — это SQL-запросы, которые включают выражения SELECT, FROM и WHERE, вложенные в другой запрос.
</li>
</ul>
Пример
Найдем курсы, которые преподавались осенью 2009 и весной 2010 годов:
SELECT DISTINCT course_id
FROM section
WHERE semester = ‘Fall’ AND year= 2009 AND course_id IN (
SELECT course_id
FROM section
WHERE semester = ‘Spring’ AND year= 2010
);

Доп. материал:
<a href="https://habr.com/ru/post/480838/">SQL запросы быстро. Часть 1</a>
 
<h2>Подробнее о джойнах? (Join)</h2>
Как и было сказано выше, различные виды JOIN помогают объединить некие данные из нескольких таблиц каким-либо образом.

Так чем отличается INNER JOIN от LEFT JOIN? Чаще всего ответ примерно такой: "inner join — это как бы пересечение множеств, т.е. остается только то, что есть в обеих таблицах, а left join — это когда левая таблица остается без изменений, а от правой добавляется пересечение множеств. Для всех остальных строк добавляется null". Еще, бывает, рисуют пересекающиеся круги. 
Это понимание и подобные ответы – по сути не верны, т.к. все джойны – декартово произведение (cross join) с фильтрами (предикатом и, возможно, UNION). Также стоит обратить внимание на порядок таблиц при различных джойнах.

Доп. материал:
<a href="https://habr.com/ru/post/448072/">Понимание джойнов сломано. Это точно не пересечение кругов, честно</a>

<h2>Типы данных в SQL?</h2>
<ul>
<li>Exact Numeric SQL Data Types:
</li>
<ul>
<li>bigint = Range from -2^63 (-9,223,372,036,854,775,808) to 2^63-1 (9,223,372,036,854,775,807)
int = Range from -2^31 (-2,147,483,648) to 2^31-1 (2,147,483,647)
smallint = Range from -2^15 (-32,768) to 2^15-1 (32,767)
tinyint = Range from 0 to 255
bit = 0 and 1
decimal = Range from –10^38 +1 to 10^38 -1
numeric = Range from -10^38 +1 to 10^38 -1
money = Range from -922,337,203,685,477.5808 to +922,337,203,685,477.5807
small money = Range from -214,748.3648 to +214,748.3647
</li>
</ul>
<li>Approximate Numeric SQL Data Types:
</li>
<ul>
<li>float = Range from -1.79E + 308 to 1.79E + 308
real = Range from -3.40E + 38 to 3.40E + 38
</li>
</ul>
<li>Date and Time SQL Data Types:
</li>
<ul>
<li>datetime = From Jan 1, 1753 to Dec 31, 9999
smalldatetime = From Jan 1, 1900 to Jun 6, 2079
date = To store a date like March 27, 1986
time = To store a time of day like 12:00 A.M.
</li>
</ul>
<li>Character Strings SQL Data Types:
</li>
<ul>
<li>char = Maximum length of 8,000 characters
varchar = Maximum of 8,000 characters
varchar(max) = Maximum length of 231 characters
text = Maximum length of 2,147,483,647 characters.
</li>
</ul>
<li>Unicode Character Strings SQL Data Types:
</li>
<ul>
<li>nchar = Maximum length of 4,000 characters
nvarchar = Maximum length of 4,000 characters
nvarchar(max) = Maximum length of 231 characters
ntext = Maximum length of 1,073,741,823 characters
</li>
</ul>
<li>Binary SQL Data Types:
</li>
<ul>
<li>binary = Maximum length of 8,000 bytes
varbinary  = Maximum length of 8,000 bytes
varbinary(max) = Maximum length of 231 bytes
image = Maximum length of 2,147,483,647 bytes
</li>
</ul>
</ul>

<h2>Шпаргалки SQL</h2>
<img src="https://lh4.googleusercontent.com/OdwSRZjYVUxTZjYqXdXxR729HZXVoRgMgch_oRiUe9G1l0Kp7k0kpjnbGroEF8p8M5xT9IZjKOm7FoziItfJMjBwIowd1o21u9L48R4yIKonaezq6AeT55TVNSroDclQapUeAu7f">
<img src="https://lh5.googleusercontent.com/2fzZW-u8156b-Lmit9e9N0rBs8kbFH793uJ20Ao0EwszIH8pj6YypH-qt4lpx14SSHSQ7J2R8fWaLp1zfEWJet3iWQP37z1csofFmLATtVx6T2Ynedi7fDRhp0OyOQLT0Fobs7U3">
<img src="https://lh3.googleusercontent.com/oSBePVtON4sIqr4lvo8KAqNl_lDwntMkwzXR4Wld1Gnc_fzWVqW_2nFGFPRfqQ8qpZNFcQ-Igsq24mr4o4vIfD7-EV1D3B87iJ3HRBHWplOy9n9DJY_fAvjRJLzRFT2PkmhyhU7A">

<h1> ----- Практическая часть -----</h1>
<h2>Дана форма для регистрации. Протестируйте.</h2>
Вопрос номер один практически на всех собеседованиях на младшую позицию. Он хорош еще и тем, что в зависимости от уровня кандидата будет раскрыт в разной степени. Всегда в первую очередь уточняйте хотя бы какие-то минимальные требования, даже если вначале озвучивают, что требования не формализованы.
<ul>
<li>Начальный уровень представляет из себя простые позитивные и негативные кейсы (в основном на валидацию):
</li>
<ul>
<li>Обязательные поля отмечены *
</li>
<li>Обязательные поля заполнены/нет
</li>
<li>Галочки на соглашениях проставлены/нет
</li>
<li>Поле password и подтверждение имеет соответствующий тип (в полях формы прописан корректный атрибут TYPE, сообщающий браузеру тип элементов формы.)
</li>
<li>Проверяется, что пароли одинаковы
</li>
<li>Имя пользователя валидируется как минимум на длину и спец. символы, остальное по ТЗ
</li>
<li>Адрес почты валидируется в соответствии со стандартом (наличие символа @, несколько символов @, длины частей до и после @, допустимые символы до и после, наличие пробелов перед адресом и после, корректная доменная часть и т.п.)
</li>
<li>Поля с ожидаемым числовым вводом и текстовым соответственно проверить позитивными и негативными кейсами по типам данных
</li>
</ul>
<li>Следующий уровень:
</li>
<ul>
<li>Все из предыдущего
</li>
<li>Кроссбраузерность
</li>
<li>Понятность формы. Присутствует описание полей или плейсхолдеры
</li>
<li>Сенситив данные не должны передаваться в URL
</li>
<li>Проверяем, как форма отображается до сабмита и после
</li>
<li>Поведение, если нажать сабмит несколько раз подряд 
</li>
<li>Если формы очищаются после сабмита, проверить регистрацию существующего пользователя
</li>
<li>Проверка глобализации – номер телефона, дата, почтовый индекс, валюта, вертикальное или RTL письмо и т.п. (опционально)
</li>
<li>Проверка простых инъекций 
</li>
<li>Правильная работа многошаговых форм (Навигация рядом с формой показывает текущий этап и количество оставшихся шагов.)
</li>
<li>Для полей, предполагающих загрузку файлов, прописан атрибут accept, определяющий тип загружаемых документов
</li>
<li>Текстовое многострочное поле при вводе объемного сообщения изменяет высоту либо в правой части появляется скроллбар для просмотра всего содержимого
</li>
<li>Для авторизованного пользователя в поля формы автоматически подставляются все известные о посетителе данные.
</li>
<li>Форма сохраняется в веб-формах (админ-панели) или SQL-таблицах.
</li>
<li>Прописан реальный e-mail лица, отвечающего за обработку заявок (если предполагается ОС)
</li>
<li>Опционально. Пользователь получает уведомление на свой e-mail об успешно полученной заявке и последующих действиях, которые от него требуются.
</li>
<li>Прописан атрибут autocomplete для полей, поддерживающих это значение
</li>
</ul>
<li>Extra:
</li>
<ul>
<li>Проверяем, отправились ли данные после сабмита
</li>
<li>Проверяем, добавились ли соответствующие записи в бд
</li>
<li>Проверка загрузки формы и сабмита при медленном/нестабильном интернет-соединении
</li>
<li>Корректность cookies/токена и т.п. после сабмита
</li>
</ul>
</ul>

Есть еще форма посложнее (с просторов коммьюнити, автор @azshoo):
<img src="https://lh3.googleusercontent.com/YWyjMbseI3vRYKMefpy_XtNsizwzxhdWs0l8FxMivLB3BYyb0G1a-zGw06KMBXKUntoL0lemzrNxqa49l1DN3uMOE8h6o0xgU4qpccTDpWaogddCsXSitS2Q1kutwEtkNahjZzzL">

Или вот еще с просторов, реальное тестовое задание. Можно их много найти, если поискать.
<img src="https://lh5.googleusercontent.com/xV3F1E1LjxPvnPBz0d4j2GSTxnCR_2JQ7IMaZ_lsE7QqWjY25VwrHctffEG3t1mnq3_fr5c4lq9IxwjEIuGRkJlvI9NFqDn2BjrcU4UPRgXu9EhxPCGecZZf0CcsJjf6JfNXbNTQ">
Доп. материал:
<ul>
<li><a href="https://training.qatestlab.com/blog/technical-articles/testing-and-using-passwords/">Пароли, их тестирование и использование</a>
</li>
<li><a href="https://testmatick.com/ru/osobennosti-testirovaniya-parolej/">Принципы и тестовые сценарии для тестирования паролей</a>
</li>
<li><a href="http://marshrut-testirovshika.ru/forma_vhoda/">Как Тестировать? Форма Входа</a>
</li>
</ul>
<h2>Определение серьезности и приоритета</h2>
Очень частый вопрос на собеседованиях. Либо вам дают конкретные примеры дефектов, для которых вы должны определить серьезность и приоритет, либо вас самих просят придумать варианты дефектов в каких-либо ситуациях. Например, дверь в магазине. Какой дефект может быть с низкой серьезностью, но высоким приоритетом? У каждой компании найдутся свои варианты вопросов, так что потренируйтесь заранее.
<h2>Определение граничных значений и классов эквивалентности</h2>
Следующий по популярности вопрос. Зная азы этих техник тест-дизайна, ответить довольно просто, но все равно будьте внимательнее. Потренироваться можно на просторах интернета.
<h2>Логические задачи</h2>
Могут быть буквально на логику (тесты Войнаровского):
«Саша смотрит на Ольгу, а Ольга смотрит на Андрея. У Саши есть дети, у Андрея нет. Смотрит ли человек, у которого есть дети, на человека, у которого детей нет? Варианты ответа: «Да», «Нет», «Нельзя определить». Объясните свою точку зрения.»

На рассуждение и перебор вариантов, цель - увидеть, как думает кандидат и насколько он эрудирован:
<ul>
<li>Мессенджер. Один пользователь отправляет другому сообщение – не доходит. В чем может быть причина? 
</li>
<li>Два абсолютно идентичных компьютера (аппаратная и программная конфигурация), файлы скачиваются с разной скоростью. Почему?
</li>
<li>Два абсолютно идентичных компьютера (аппаратная и программная конфигурация), на одном баг воспроизводится, на другом нет. Почему?
</li>
<li>Два разных мобильных устройства с одинаковой версией приложения. Бэк и связь стабильны. На одну приходят нотификации, на другую нет. В чем может быть причина?
</li>
<li>Есть форма с 5 полями, после отправки в БД записываются только 4. В чем может быть причина?
</li>
<li>Приложение при старте запрашивает по API профиль пользователя и на основе полученных данных расставляет в правильном порядке свои блоки интерфейса на главном экране. То есть ему нужны только цифры, остальное рендерится из готовых элементов приложения. На основе только этих данных, можно ли сказать что приложение является нативным или гибридным?
</li>
</ul>

Или на «логику»:
«Есть две изолированные друг от друга комнаты. В одной находятся 3 лампочки, в другой - три выключателя. Вы стоите в комнате с выключателями и можете перейти в комнату с лампочками лишь один раз. Необходимо определить, какая лампочка включается каким выключателем.»

К первому типу можно подготовиться, изучив самые азы мат. логики и порешав несколько примеров. Многие относятся к этому несерьезно и проваливают этот тип заданий, между тем такие задачки щелкают на олимпиадах 5-клашки.
Второй тип задач показывает эрудированность в области computer science, здесь помогут только базовые общие курсы.
Про подготовку ко третьему типу задач, если опустить дискуссии об их бесполезности, можно сказать только то, что проще их просто прочитать и запомнить решение. Подробнее изучить тему можно в популярной книге «Как сдвинуть гору Фудзи».
<h2>Еще примеры</h2>
<ul>
<li>Дан веб-сайт, на котором есть каталог и реализована регистрация. На каких уровнях и что будете тестировать, конкретно по пунктам?
</li>
<li>Дана багтрекинговая система. Протестируйте воркфлоу (жизненный цикл бага).
</li>
<li>Аутлук - протестировать форму отправки письма (только этот функционал).
</li>
<li>Дано мобильное приложение: случайное подбрасывание игрального кубика. Как будете тестировать (кейсы)?
</li>
<li>Могут попросить накидать кейсов и в другом направлении. Например, придумайте кейсы для метода замены строки.
</li>
<li>Возможно не актуально в СНГ, но в англоязычных ресурсах встречаются задачи на decision/statement/branch coverage
</li>
<li>Спроектировать спецификацию API для калькулятора
</li>
<li>На просторах есть: лексический анализатор Яндекса, листбоксер в Veeam, крестики-нолики в Fora-soft
</li>
<li>GIT: ты на новом рабочем месте. Перечисли действия и команды как ты склонируешь себе репозиторий и создашь свою ветку;
</li>
<li><a href="https://docs.google.com/forms/d/1EHN2NZSbeZa9DzenlNT6bZ-xqvYdmCdL4RSoklFiASQ/viewform?edit_requested=true">Тут можно запросить платное тестовое с проверкой</a> (просто наткнулся, так что хз что там)
</li>
<li><a href="http://testingchallenges.thetestingmap.org/index.php">Сайт для тренировки тестирования</a> 
</li>
<li><a href="https://drive.google.com/file/d/1bUoYe6KeNO8bR3hhv-9ChuNPo0CwG1PX/view">Несколько примеров задач с решениями</a>
</li>
</ul>

Доп. материал: 
<ul>
<li><a href="https://www.youtube.com/watch?v=WOo3YZHIDYE&feature=youtu.be&ab_channel=ArtsiomRusauQALife">Решаем тестовое задание на позицию тестировщика (Junior QA) / Ответы на вопросы тестировщику</a>
</li>
<li><a href="https://www.youtube.com/watch?v=q75avN98ibg&feature=youtu.be&ab_channel=AlphaITSchool">ТЕСТОВОЕ ЗАДАНИЕ ТЕСТИРОВЩИКА / Какие бывают тестовые задания для QA, как делать тестовое</a>
</li>
</ul>
<h2>Набор небольших задач по SQL</h2>
Дана база:

CREATE TABLE Departments
    ([Id] int, [Name] varchar(100))
;
 
CREATE TABLE Employees
    ([Id] int, [Name] varchar(100), [Salary] int, [ManagerId] int, [DepartamentId] int)
;
 
INSERT INTO Departments
    ([Id], [Name])
VALUES
    (1, 'Sales'),
    (2, 'Development')
;
 
 
INSERT INTO Employees
    ([Id], [Name], [Salary], [ManagerId], [DepartamentId])
VALUES
    (1, 'Ivanov', 100000, null, 1),
    (2, 'Petrov', 120000, 1, 1),
    (3, 'Sidorov', 130000, 2, 1),
    (4, 'Korotkov', 120000, 2, 1),
    (5, 'Filev', 90000, 1, 1),
    (6, 'Smirnov', 125000, null, 2),
    (7, 'Godov', 125000, null, null)  

/*1. Фамилии и зарплаты всех сотрудников*/
select Name, Salary from Employees
/*2. Фамилии и зарплаты всех сотрудников, отсортированные по зарплате по возрастанию*/
select Name, Salary from Employees order by Salary asc
/*3. Фамилии и зарплаты всех сотрудников, отсортированные по зарплате по убыванию*/
select Name, Salary from Employees order by Salary desc
/*4. Фамилии и зарплаты всех сотрудников, у которых зарплата больше 100000*/
select Name, Salary from Employees where Salary > 100000
/*5. Фамилии и зарплаты всех сотрудников, у которых зарплата равна 100000*/
select Name, Salary from Employees where Salary = 100000
/*6. Фамилии и зарплаты всех сотрудников, у которых зарплата больше либо равна 100000*/
select Name, Salary from Employees where Salary >= 100000
/*7. Фамилии и зарплаты всех сотрудников, у которых фамилия Ivanov*/
select Name, Salary from Employees where Name = ‘Ivanov’
/*8. Ид департамента и максимальная зарплата в этом департаменте*/
select DepartamentId, max(Salary) from Employees group by DepartamentId
/*9. Имя сотрудника и название его отдела*/
select emp.Name, dep.Name from Employees as emp
join Departments as dep on dep.Id = emp.DepartamentId
/*10. Имя сотрудника и имя его начальника*/
select emp2.Name, emp1.Name from Employees as emp1
join Employees as emp2 on emp1.Id = emp2.ManagerId
/*11. Добавить сотрудника с именем Semenov, зарплатой 70000, менеджером Ivanov и отделом Sales*/
insert into Employees
([Id], [Name], [Salary], [ManagerId], [DepartamentId])
values
(8, ‘Semenov’, 70000, 1, 1)
/*12. Изменить зарплату сотрудника Godov на 80000*/
update Employees
set Salary = 80000
where Id = 7
/*13. Удалить сотрудника Godov*/
delete from Employees
where Id = 7

Доп. материал:
<ul>
<li><a href="https://habr.com/ru/company/otus/blog/541882/">SQL для аналитики — рейтинг прикладных задач с решениями</a>
</li>
<li>Много ресурсов для практики есть в разделе инструментов тестировщика
</li>
</ul>
<h2>Тестирование чашки для кофе</h2>
Не уверен, что это еще популярно спрашивать, но на всякий случай пара примеров с просторов.

Сначала – позитивное тестирование.

Функции чашки:
- вмещать напитки,
- переносить напитки,
- возможность пить из нее,
- возможность греть напитки в микроволновке.

Проверим сначала «вмещать»:
Поставили на поверхность – стоит, не падает - все ок.
Холодной воды налили – вода внутри - все ок.
Кипятку налили - не треснула, не течет – все ок.
*сперва хотела лить только горячую (раз горячую выдержит, то холодную – само собой), но потом решила, что это будет заодно и стрессовое тестирование (испытание на перепад температур).

Теперь – «переносить»:
Есть ручка, за нее можно взяться и поднять/перенести даже полную и горячую чашку (пустую и холодную носить не станем, если предусмотрен более тяжелый тест).

Теперь – «пить из нее»:
Наклонять удается, отхлебывать – тоже. Все ок.

«Возможность греть в микроволновке»:
Если в инструкции к чашке не указана максимальная допустимая температура при подогреве в печи, наливаем воду, ставим чашку в печь и включаем на максимум 

По идее, нужно ставить таймер на время, достаточное для нагрева напитка до 100 градусов. Потому что если он выкипит, а чашка перегреется, это уже не будет позитивным тестированием.

Если позитивное тестирование удачно, проведем негативное (ошибочные или нестандартные, но возможные действия с предметом):
Подвергнем ее
- механическому (об пол, ап стену),
- химическому (кротом, адриланом, уксусной кислотой),
- физическому воздействию (перегреем в микроволновке, поставим на раскаленную горелку).

Еще - «тестирование удобства пользователя»:
удобно ли ставить, не горячо ли носить, приятно ли браться за ручку и т. д. 

Еще – «тестирование безопасности»:
Вот на работе у меня чашка – маленькая, и край отбитый. Поэтому ее никто не трогает, когда меня нет. А эту наверняка все таскали бы – большая, удобная, красивая… Мне не жалко, но тест безопасности она бы не прошла.

Еще – «тестирование взаимодействия»:
встает ли чашка на блюдца от других сервизов.


<h2>Тестирование карандаша</h2>
<img src="https://lh6.googleusercontent.com/gBKiJjJ95N09zu_q46yUieLT3q8EVaXm5NleB6AUvqW0lRS9G238qiF5MMAGrsYU9Dt9sTpQgULJHbRuNrtcAnebMMVIaQpwmu-iZt45g-nnYNTlQvw-IxXKGPiD139hJ5qFjYu3">
<h2>HR: Как вы будете решать конфликты между членами вашей команды? </h2>
А также еще уйма подобных каверзных вопросов, в ответах на которые вам нужно проявить чудеса маневрирования, менеджерских качеств, софт-скилов и т.п. В общем-то не всегда можно угадать, что от вас ожидают услышать, но в целом это вопросы на оценку вашей адекватности, умения работать в коллективе и прочих софт-скилов.
<h2>HR: Что делать, если разработчик утверждает, что найденный дефект таковым не является?</h2>
Указывать на требования, апеллировать к здравому смыслу, подключать аналитика, чтобы объяснил. Если это поведение не описано в доке, то это баг, либо недоработка. Но недоработка в терминах джиры все равно баг
Проверить ТЗ. Если есть расхождение с ожидаемым результатом – привязываем ссылку на ТЗ.
Если формально это не зафиксировано, но вы чувствуете, что на это стоит обратить внимание – идете к писателю/аналитику/менеджеру, объясняете и в случае согласия это попадает в ТЗ.
Если формально не зафиксировано и менеджер с вами не согласен – дефект закрывается.
<h2>Вот тебе комп и работающий сайт. Сделай мне 401-ю ошибку</h2>
Задача на умение пользоваться инструментами, позволяющими подменять трафик. По обстоятельствам.
<h2>Пришел баг из продакшена, что делаем?</h2>
Воспроизводим, запускаем по пути жизненного цикла дефекта и анализируем причины, как данный дефект прошел в прод. После исправления дефекта разработчиком проводим повторное тестирование. Добавляем данный дефект в регрессию. В зависимости от охватываемого функционала и Root Cause этих багов принимается решение о проведении санитарного/регрессионного тестирования после подтверждающего.

<h2>Оценить время на тестирование лендинга</h2>
"Нужны ТЗ, макет, идеально - прототип. "А дальше считаете по самой простой эстимации по тест-кейсам. Функциональное: позитивные и негативные сценарии на поля ввода; чек-боксы, подписки, имэйлы, тултипы, хинты, кнопки, линки и футэр; Кроссбраузерное и кроссплатформенное: здесь надо уточнить, для каких браузеров и девайсов тестируете; UI/UX: сверка с элементами макета в дев тулз на разных браузерах и девайсах; Грей бокс метод: смотрим, как сторятся отправленные данные в админке/бд. Плюс полный флоу прохождения регистрации в качестве смоука. Ну а потом прикидываете количество кейсов, на каждый кейс закладываете, сколько вы на него потратите времени (по-разному, здесь вы учитываете свою скорость)+20% на риски. Плюс закладываете время для регрессии. 
В общем, в этом задании вам важно задать правильные вопросы) иначе будет из оперы "не зная тз - получишь хз" (с) @DorityTM

Для оценок в общем виде существует <a href="https://doitsmartly.ru/all-articles/management/137-6-budgeting-techniques.html">Метод оценки по 3 точкам (Three Point Estimation)</a>
Один из самых распространенных и простых методов. В рамках него сначала определяются оптимистичная (O = Optimistic), пессимистичная (P = Pessimistic) и реалистичная/средняя (M = Middle) оценки.
Значения P, M и O определяются экспертно (в часах, днях, $), например, в ходе обсуждения внутри проектной команды. Для этого задаются вопросы такого типа: «сколько времени займет проект, если все пойдет хорошо, не будет никаких рисков и проблем?», «каким может быть самый негативный сценарий и сколько на него потребуется времени/усилий?» и т.п.
Далее полученные значения P, M и O подставляются в формулу: (O + 4 M + P) / 6
Результат расчета дает усредненную оценку. Такая формула позволяет с одной стороны учесть возможные позитивные и негативные сценарии, а с другой – «сгладить» их влияние и получить более реальное значение оценки.

Доп. материал:
<a href="https://www.youtube.com/watch?v=6_eKPbigA1o&ab_channel=EventsTeam">Truthful Estimations by James Bach at ThinkTest 2015</a> (вкратце:  "начну, потестирую немного, прикину, скажу")
<h1>----- Источники -----</h1>
<br> www.software-testing.ru
<br> www.techbeamers.com
<br> www.guru99.com/software-testing.html
<br> wikipedia.org
<br> www.softwaretestinghelp.com/mobile-testing-interview-questions-answers/
<br> medium.com/@sheidaievkostiantyn/capacity-testing-273c87ff03b4
<br> tproger.ru/translations/sql-recap/
<br> www.youtube.com/watch?v=SJwXK-2rw4M
<br> lsreg.ru/shpargalka-po-sql/
<br> lib.ssga.ru/
<br> vc.ru/design/93884-32-otlichiya-dizayna-mobilnogo-prilozheniya-pod-ios-i-android
<br> yamobi.ru/posts/kak_rabotaet_mobilnaya_svyaz_likbez.html
<br> mobile-review.com/articles/2016/likbez-1.shtml
<br> wifigid.ru/besprovodnye-tehnologii/kak-rabotaet-wi-fi
<br> thecode.media/wifi/
<br> html5book.ru/otzyvchivyj-dizayn-saita/#part5
<br> lpgenerator.ru/blog/2015/10/21/responsivnyj-vs-adaptivnyj-dizajn-chto-luchshe-dlya-polzovatelya/
<br> xakep.ru/2011/05/24/55557/
<br> habr.com/ru/company/livetyping/blog/307860/
<br> zen.yandex.ru/media/habr/kak-ty-realizuesh-autentifikaciiu-priiatel-5ec4cc1e033b1f6bec4ce836
<br> interface31.ru/tech_it/2019/07/kak-ustroen-i-rabotaet-protokol-dhcp.html
<br> www.youtube.com/watch?v=n_kl9sPQhXA
<br> www.bigdataschool.ru/wiki/agile
<br> www.youtube.com/watch?v=lKXGhh5un58
<br> habr.com/ru/company/otus/blog/502720/
<br> doitsmartly.ru/all-articles/blog-with-left-sidebar/88-requirements-for-qa-test-environment.html
<br> withsecurity.ru/chto-takoe-pentest-i-dlya-chego-on-nuzhen
<br> espressocode.top/software-testing-portability-testing/
<br> https://testmatick.com/ru/testirovanie-globalizatsii/
<br> artoftesting.com/
<br> www.antula.ru/cookies.htm
<br> yandex.ru/turbo?text=https%3A%2F%2Fnuancesprog.ru%2Fp%2F7833%2F
<br> yandex.ru/blog/company/77455
<br> www.rea.ru/ru/org/cathedries/infkaf/Documents/%D0%94%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%B2%D0%B5%D0%B1-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B%20%D0%B2%20%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B5.pdf
<br> habr.com/ru/company/sibirix/blog/223777/
<br> habr.com/ru/post/46374/
<br> www.intervolga.ru/blog/projects/relsy-veb-integratsii-rest-i-soap/
<br> flylib.com/books/en/2.156.1/control_flow_testing.html
<br> www.protesting.ru/testing/testcoverage.html
<br> kaner.com/pdfs/ScenarioIntroVer4.pdf
<br> www.simbirsoft.com/blog/tekhniki-test-dizayna-i-ikh-prednaznachenie/
<br> www.bullseye.com/coverage.html
<br> sysgears.com/articles/test-design-techniques-overview/
<br> www.youtube.com/watch?v=NrIN0qVBpZ4
<br> www.viva64.com/ru/t/0093/
<br> www.intuit.ru
<br> 33testers.blogspot.com/2015/06/blog-post_17.html

<br> Microsoft Corporation — Performance testing Guidance for Web Applications
<br> С. Куликов - Тестирование программного обеспечения. Базовый курс.
<h1>----- Поблагодарить автора -----</h1>

<i>Приятно читать ваши письма с благодарностями и понимать, что куча моих сил и огромное количество времени, проведенные за проектом не пропадают зря. Знать, что мой проект помогает экономить время, устраиваться на работу, нанимать, используется как обучающее пособие для новых сотрудников и для студентов в университетах. Все это очень мотивирует продолжать :) 
И все же некоторые люди считают более правильным говорить спасибо донатами, так что я наконец-то добавил возможность отправить мне скромную чашечку кофе :)   <s>а там кто знает, может так и до издания полноценной книги дойдет когда-нибудь))</s>
<br>
<br>
По России можно просто пополнить связь Теле2 +79044121375
<br>
Яндекс.Деньги <a href="https://sobe.ru/na/QA_Bible">https://sobe.ru/na/QA_Bible</a>
<br>
QIWI <a href="http://qiwi.com/n/VLADISLAV610">qiwi.com/n/VLADISLAV610</a>
<br>
PAYPAL <a href="http://paypal.me/QAbible">paypal.me/QAbible</a>
<br>
PAYEER P1044386908
<br>


Спасибо и удачи в карьере!</i>
