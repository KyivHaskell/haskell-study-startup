# Група з вивчення мови Хаскель

Велика подяка нашим спонсорам! Завдяки ним маємо сплату оренди та подальший розвиток івентів від KyivLambda. Golden sponsors: [Grammarly](https://grammarly.com), [IOHK](https://iohk.io/en/). Silver sponsors: [Attendify](https://attendify.com), [Preply](https://preply.com/ua/), [Takeoff](https://www.takeoff.com).

![sponsors](https://github.com/kyivlambda/haskell-study-group/raw/master/images/sponsors.png "Sponsors")

Хаскель – потужна, статично-типізована, чиста, функційна мова програмування, що збирає навколо себе як комерційних користувачів з індустрії, так і науковців-інформатиків.

- **Розклад зустрічей**: [Meetup.Events](https://meetup.events/meetup/2)

## Принципи

Ми працюватимемо за книгою [_Haskell Programming from First Principles_](http://haskellbook.com/) (aka the "Haskell Book") авторства Крістофера Алена та Джулі Моронукі. Єдиними передумовами для участі є ця книга, комп’ютер, знання англійської (на рівні читання простої мови зі словником), та ви. Вільний розум також був би в нагоді. Жодного попереднього досвіду з Хаскелем, функційним програмуванням, або програмуванням в цілому не потрібно.

Для підготовки до вашого першого візиту, будь ласка, зробіть наступне:

- **Доєднайтесь до [Slack-спільноти KyivHaskell](https://github.com/KyivHaskell/KyivHaskell/blob/master/README.md#join-our-slack-channel).** Всі анонси, що стосуються цієї групи з вивчення будуть надіслані через [Meetup](https://meetup.events/meetup/2) та Slack. В Slack-чаті KyivHaskell, шукайте канал `#haskell-study-group`.

- **[Придбайте](https://gumroad.com/l/haskellbook) свою особисту копію книги (доступні знижки: дивіться нижче).**
Вам знадобиться власна копія на вашому комп’ютері задля того, щоби працювати із PDF-контентом та терміналом, відкритими поруч. Цю книжку було незалежно досліджено, написано та видано двома Хаскель-розробниками, що працювали в свій вільний час для підтримки навчання функційному програмуванню. Будучи членом стійкої та підтримувальної спільноти, ми знаємо, що ви занадто віддані духу благої дії "позичити" чиюсь копію. Хочемо зазначити, що автори набирали цю книгу в LaTeX! Поважайте їхню роботу.

- **Встановіть [Stack](https://docs.haskellstack.org/en/stable/README/), інструмент для управління Хаскель-проектами.**
Якщо ви знайомі із пакетними менеджерами типу npm, pip, та apt, Stack схожий на них. Вам не потрібно приходити на зустріч експертом, але просимо [вивчити основи](https://github.com/kyivlambda/haskell-study-group/blob/master/resources/haskell-stack-notes.md). Якщо ви, все ж, хочете все знати, ви можете подивитись [дане відео](https://www.youtube.com/watch?v=sRonIB8ZStw). Найголовніше: що би ви не робили, _не встановлюйте Haskell Platform_.

- **Налаштуйте проектне середовище для свого практикування в кодингу, також ознайомтесь із GHC та GHCi.**
Не потрібно робити набагато більше, ніж створити директорію для вашого коду та впевнитись, що ви вмієте запускати компілятор GHC на ваших першокодах, та GHCi, коли вам потрібен REPL. Ми пропонуємо створювати окремі теки для кожного розділу, але ви вільні робити як вам здається зручнішим. Не очікуйте на зустрічі робочий WiFi, хоч ми й будемо докладати зусиль, аби він був доступним.

### Очікування

Очікується, що учасники групи з вивчення зможуть встановити та дотримуватись принципу самовідповідальності. Це тягне за собою зміцнення завдяки нормам підтримувального одне одного та ретельно працівного середовища. Щотижня ви маєте виконати наступні задачі:

- прочитати весь матеріал
- набрати весь код
- спробувати виконати всі завдання
- зустрітись із партнером/партнеркою із вивчення задля обговорення вашої роботи
- відвідати групову зустріч

Ці очікування було встановлено не для того, аби зробити ваше життя жалюгідним, але щоби підготувати базу вашого успіху. Якщо ви дійсно хочете вивчити Хаскель, ключ, як завжди, лежить в постійності та послідовності. Оскільки в цій групі ми вивчатимемо Хаскель разом, неодмінною є ваша самостійна праця над кожним розділом перед зустріччю, щоби ви прийшли на неї підготовленими, знаючи наперед, де саме ви потребуєте допомоги та що ви розумієте достатньо добре, аби допомогти іншим. Якщо ви застрягли із проблемою — продовжуйте рухатись, але не пропускайте вправи повністю.

#### Ще раз наголошуємо: _не пропускайте вправи!_

Якщо ви зовсім новачок у програмуванні або за якоїсь причини маєте проблеми із встановленням Хаскеля на вашому комп’ютері, не переживайте! Приходьте в групу з вивчення, ми вам допоможемо розібратись. На щастя, вам навіть не потрібен комп’ютер, аби працювати із першим розділом: тільки ручка, листок, та терпіння. Тому впевніться, що ви зробили хоча б це, навіть якщо потребуєте технічної допомоги.

**Коди знижки** на книгу доступні, якщо він вам дійсно потрібен. Автори не хочуть, аби ціна на книгу відмовила когось від придбання, тому, будь ласка, зв’яжіться зі мною, якщо ціна є зависокою для вас, та ви б хотіли отримати знижку. Будь ласка, не просіть знижку, якщо вона вам не потрібна. Кількість знижок обмежена, і я б хотів залишити їх для тих, кому вони дійсно потрібні.

Також зауважимо, що якщо ви студент або не маєте можливості придбати книжку з інших причин, **ми також готові купити вам її зі спонсорського бюджету**. Обов'язково напишіть організаторам курсу!

### Норми поведінки

Беручи участь в цій групі з вивчення, ви погоджуєтесь із наступними нормами:

Щотижня, до групової зустрічі, ви завершите читання та намагатиметесь виконати вправи із максимальними зусиллями, доступними вам. Якщо ви маєте проблеми із виконанням завдань, ви повинні попросити допомоги на зустрічах, від вашого партнера/партнерки з навчання, або онлайн.

Ви докладете всіх зусиль, аби взяти участь у щотижневій зустрічі. Кількість місць обмежена, тому якщо ви не впевнені в можливості регулярно долучатись, не реєструйтесь. Якщо ви не можете попасти на мітинг, приберіть відмітку участі (RSVP) щонайшвидше.

На додаток до зазначеного, від всіх учасників групи з вивчення очікується докладання найбільших зусиль із дотримання людської поведінки. Учасники, чиї дії відходять занадто далеко або занадто часто від розумних кордонів поваги, доброзичливості, та колегіальності можуть бути усунені з групи на розсуд організаторів.

На сайті [Recurse Center](https://www.recurse.com) є корисний список [соціальних правил](https://www.recurse.com/manual#sub-sec-social-rules), із яким ми рекомендуємо ознайомлення перед відвідуванням наших зустрічей.

### Формат

Ми працюватимемо крізь розділи 1-18 книги Haskell Book протягом 12 тижнів, зустрічаючись приблизно на дві години щотижня. Ми можемо розширити список зустрічей для покриття наступних розділів, якщо матимемо достатньо ентузіазму та доступність організаторів.

Тим не менш, **це не курси**, тому не очікуйте формату лекцій. Навзамін, ви матимете можливість переглянути свою роботу та обговорити концепції та вправи, із якими ви мали проблеми, коли працювали з книгою власноруч.

Ви вільні вибирати зручний вам режим роботи з книгою, плануючи роботу як завгодно близько до щотижневих зустрічей, аби ви тільки могли підтримувати власний ритм. Тому слід зазначити, що якщо життєві події стануть перешкодою, так тому і бути, але намагайтесь якомога швидше наздогнати пропущене, та не пропускайте жодних матеріалів, бо кожен наступний розділ ґрунтується на попередніх. Ми завжди можемо обговорити вправи на Slack-каналі, але просимо втриматись від публікації ваших рішень (в тому числі на GitHub).

### Реєстрація

Всі зустрічі буде оголошено на Meetup та Slack. Ви маєте відмітитись як учасник (RSVP) окремо на кожну зустріч, оскільки кількість місць обмежена. Якщо ви не можете відвідати зустріч через нестачу місць, будь ласка, працюйте самостійно та приходьте на наступну зустріч. Не відмічайтесь (RSVP), якщо не можете прийти.

### Слайди та інші ресурси

Дивіться суб-теку [resources](https://github.com/kyivlambda/haskell-study-group/tree/master/resources) в цьому репозиторії для презентаційних слайдів, бонусних вправ, або інших матеріалів, використаних під час зустрічей групи. Якщо ви маєте щось, що б ви хотіли додати, будь ласка, зробіть pull request.

### Розклад

Chapters mentioned are meant to be read by the week's meeting with exercises done.

**Week 1. Introduction. Lambda calculus.**
- Haskell Book, Chapter 1

**Week 2. Getting started with Haskell.**
- Chapters 2 and 3

**Week 3. Basic datatypes.**
- Chapters 4 and 5

**Week 4. Types and Typeclasses.**
- Chapter 6

**Week 5. Functional patterns. Working with recursion.**
- Chapters 7 and 8

**Week 6. Lists and folding lists.**
- Chapters 9

**Week 7. Lists and folding lists (pt 2).**
- Chapters 10

**Week 8. Algebraic datatypes.**
- Chapters 11 and 12

**Week 9. Peer-to-peer review. Projects and Modules.**
- Post solutions to the phone exercise from chapter 11, review at least 2 of your peers.
- Chapter 13

**Week 10. Midpoint review. Testing with QuickCheck.**
- Chapter 14

**Week 11. Monoid and Semigroup.**
- Chapter 15

**Week 12. Functor.**
- Chapter 16

**Week 13. Applicative.**
- Chapter 17

**Week 14. Monad. How to apply structure to your code. Conclusion.**
- Chapter 18
- Read Chapter 19 on your own
- General review and look ahead

**Week 15. Foldable. (We decided to move on)**
- Chapter 20

**Week 16. Traversable**
- Chapter 21

**Week 17. Reader, State**
- Chapter 22
- Chapter 23

**Week 18. Parser combinators, part 1**
- Chapter 24. Up until "24.8 Character and token parsers"

**Week 19. Parser combinators, part 2**
- Chapter 24. "24.8 Character and token parsers" and further
- Only do exercises 1-5

**Week 20. Composing types**
- Chapter 25
- Do exercise 5 from previous chapter peer to peer

**Week 21. Monad transformers**
- Chapter 26

Дні зустрічей, час, та місце проведення може змінюватись в залежності від доступності місця.

Для деталей щодо конкретної зустрічі, дивіться [сторінку на Meetup](https://meetup.events/meetup/2).
