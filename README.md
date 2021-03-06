# Архитектура социальной сети Tik Tok
Популярность ТикТока выросла, потому что пользователи могут за короткий период набрать большую активную аудиторию. Происходит подобное благодаря алгоритмам приложения. Однако определить, как они работают, сложно. Система постоянно меняет способы оценки роликов.

## Интерфейс и алгоритмы рекомендаций

Когда речь заходит об алгоритмах китайской соцсети, многие представляют себе какой-то волшебный фрагмент кода. Но знатоки отрасли считают, что в целом TikTok подходит к решению задач машинного обучения сходно с остальными компаниями.
Для сервисов вроде TikTok успех во многом зависит от того, как работают алгоритмы машинного обучения.
Перед тем как видео попадёт в ленту рекомендаций пользователя, его посмотрит сотрудник отдела по контенту и расставит метки:

+ Что на видео: танцы, пение под фонограмму, видеоигры, котёнок, еда.
+ Кто на видео: мужчина или женщина, сколько их, какого они возраста.
+ Где происходит действие.
+ Какие фильтры и эффекты.

Видео также анализирует система ИИ, причём иногда даже во время съёмки: некоторые фильтры в TikTok фиксируют изменения мимики и движения тела.
На начальной странице TikTok отображается только одно видео. Механизм сервиса похож на бесконечную ленту, но на деле у каждого ролика своя страница. Пока воспроизводится один, другие загружаются в фоновом режиме. Такой метод позволяет приложению анализировать отношение к конкретному ролику.

Каждое действие — сигнал для системы:
+ Если пользователь не досмотрел видео и перешёл к следующему, значит, оно ему не понравилось.
+ Повторное воспроизведение, интерес к музыкальному сопровождению или решение поделиться указывают на увлечённость.
+ Посещение страницы автора и подписка — на высокий интерес.

Ещё алгоритм учитывает, что TikTok уже знает о пользователе:
+ Предыдущие действия.
+ Демографические и психографические характеристики.
+ Где он смотрит видео и на каком устройстве.
+ Какие пользователи на него похожи.

TikTok собирает достаточно данных даже за короткое время. Ролики небольшие и пользователь точно посмотрит несколько. А пролистывать нудные видео ему даже приятно, ведь он знает: в будущем алгоритм учтёт предпочтения.
## Как алгоритм Тик Ток работает с новыми аккаунтами
Если вы только зарегистрировались на платформе, важно разобраться, какие ваши шаги могут повлиять на просмотры. Пользователи часто сообщают о том, что алгоритм учитывает следующие детали:
+ Контент. Система обращает внимание на людей, которые появляются в вашем ролике, а также на окружающую местность. Если вы нарушаете правила площадки даже косвенно, в рекомендации не попадете.
+ Уникальность сюжета. Если вы используете контент другого пользователя, алгоритм расценит это за нарушение авторских прав и не пропустит клип к аудитории.
Обработка материалов. Если ваш видеоклип редактируется в ТикТоке, система выделит вашу работу среди других, а при обработке на сторонних ресурсах вы теряете шансы попасть в рекомендации.
+ Музыка. Здесь учитывается, авторская ли мелодия или принадлежит другому человеку. 

Эти детали работы алгоритма могут применяться и к опытным пользователям, если период их подъема на платформе прошел.
## Бесконечная прокрутка и негативная оценка публикаций
Ленты многих соцсетей давно работают на алгоритмах. Чаще всего они устроены по принципу бесконечной прокрутки и отображают сразу несколько элементов. Но в таком случае алгоритм не узнает, какая публикация привлекла внимание пользователя и как он к ней отнёсся.
Возможно, он забыл поставить отметку «Нравится» или хотел возразить, но передумал, потому что автор его друг или коллега. Алгоритм не может распознать отрицательный отклик, нет негативной обратной связи. Некоторые платформы позволяют указывать на содержание нежелательного характера, но эти функции «спрятаны», и поэтому ими редко пользуются.
Такие ленты формируют Facebook, Instagram и Twitter. Они ориентируются в первую очередь на социальные графы: учитывают возраст, родной город, подписки на сообщества и предпочтения «друзей». Недостаток — интересы пользователя могут не совпадать с интересами «друзей», часть из которых он едва знает.
Reddit использует графы интересов и поэтому разработала механизм отрицательных оценок. Главная задача площадки — удержать пользователей за счёт увлекательного контента, а для этого необходимо отсеять неподходящий.
_____________________________________________________________________________________
Эту же цель ставит TikTok, хотя очевидной негативной отметки для видео в нём не предусмотрено. Алгоритм учится считывать отрицательную реакцию сам — по отсутствию положительного отклика и досрочному перелистыванию. Впрочем, за долгим нажатием на видео всё же спрятана функция «Не интересно».
______________________________________________________________________________________________
Восприимчивость алгоритма вынуждает создателей контента завлекать зрителей. Один из популярных приёмов — использование «вирусных» песен. Скорее всего, пользователь прослушает фрагмент несколько раз и дождётся кульминации. Но в видео её может и не быть. Поэтому авторы нередко добавляют «результат в конце» или «обязательно досмотри», чтобы создать интригу.
Такое проектирование интерфейса позволяет алгоритмам китайской соцсети постоянно учиться, и поэтому сервисам вроде Reels или Triller может быть трудно её догнать.
