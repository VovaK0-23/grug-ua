> Переклад статті від розробника з 30-річним досвідом, 
> маґістра Стенфордського університету і автора HTMX - Carson Gross
> https://grugbrain.dev/

![grug](./grug.png)
# Розробник з мозком Ґруґа (The Grug Brained Developer)
Посібник для чайників про те, як мислити, як самосвідомий простак 
(A layman's guide to thinking like the self-aware smol brained)

## Вступ

це збірка думок про розробку програмного забезпечення, зібрана розробником з ґруґ-мозок.

ґруґ-мозок не розумний, але програмає вже багато років і дещо навчився, хоча плутається.

ґруґ-мозок намагається зібрати свої знанинки у маленьку, легку та смішну сторінку, не тільки для вас, молодих ґруґів, але і для себе, тому що з віком він забуває важливі речі, наприклад, що їв на сніданок або чи надів штани.

розумний-мозок розробників багато, і деякі з них не подобається читати це, робити кисле обличчя.

*ДУМАЮТЬ*, що вони розумний-мозок розробники ще більше, багато більше, і ще більше, напевно, можливо, їм точно не сподобається читати це, багато кислих облич (такий інтернет).

(примітка: ґруґ колись думав, що він розумний, але навчився важким шляхом).

це нормуль!

це вільна країна, до певної міри, і в кінці кінців все це не має великого значення, але ґруґ сподівається, що вам буде весело читати і, можливо, ви навчитеся з багатьох, багатьох помилок, які ґруґ зробив за довге програмістське життя.

## Вічний ворог: Складність (The Eternal Enemy: Complexity)

головний хижак ґруґа - це складність

складність - погано

повторюю:

складність - *дуже* погано

всі разом зараз:

складність - *дуже-дуже* погано

якби був вибір між складністю та боєм раз на раз з тиранозавром, ґруґ обрає тиранозавра: принаймні ґруґ бачить тиранозавра

складність - це дух демон, він входить в кодові бази через добрих в сердці, але в кінцевому результаті таких, яких дуже хочеться вдарити дубиною, розробників без ґруґ-мозку та менеджерів проєктів, які не бояться духа демона складності або навіть не знають про нього

одного дня кодова база зрозуміла, і ґруґ може працювати, все добре!

наступного дня - неможливо: дух демона складності увійшов у код і дуже небезпечна ситуація!

ґруґ не може бачити духа демона складності, але ґруґ відчуває його присутність у кодовій базі

дух демона складності насміхається над ним, змінює тут, ламає щось інше!?! mock mock mock(насмішка) ха-ха так весело, ґруґ любить програмування і не стає шукачем блискучих каменів, як радив старший ґруґ

дубина не працює на демона духа складності, а бити розробника який впустив духа, погана ідея, іноді це сам ґруґ!

на жаль, часто це сам ґруґ

тож ґруґ повторює знову і знову: складність *дуже*, *дуже* погано

### Казати "Ні"

найкраща зброя проти духа демона складності - це чарівне слово: "ні"

"ні, ґруґ не буде будувати цю функцію"

"ні, ґруґ не буде створювати цю абстракцію"

"ні, ґруґ не буде лити воду на тіло щодня або пити менше чорного соку для думання, припиніть запитувати це знову"

зауважте, це добра інженерна порада, але погана кар'єрна порада: "так" - чарівне слово для отримання більше блискучих каменів і керування великою плем'ю розробників

сумно, але правда: навчіться казати "так", а потім навчіться звинувачувати інших ґруґів, коли щось не виходить, ідеальна кар'єрна порада

але ґруґ має бути вірним собі, і "ні" - це чарівне слово ґруґа. Спочатку важко, особливо якщо ти добрий ґруґ і не любиш розчаровувати людей (багато таких ґруґів!), але з часом легше, навіть якщо купа блискучих каменів не така висока, як могла б бути

це нормально: скільки блискучих каменів ґруґу насправді потрібно?

### Казати "Ок"

іноді компроміс необхідний, інакше не буде блискучих каменів, а це означає, що не буде м'яса динозавра, що не добре, дружина суворо нагадує ґруґу про молодих ґруґів вдома, які потребують даху, їжі тощо, не цікавиться ґруґовими балачками про демона складності в п'ятдесятий раз

у такій ситуації ґруґ рекомендує "ок"

"ок, ґруґ побудує цю функцію"

потім ґруґ витрачає час на обдумування рішення 80/20 і будує це замість іншого.
рішення 80/20 каже "80% бажаного з 20% коду", можливо, воно не має всіх прикрас, які хоче менеджер проєкту, може бути трохи некрасивим, але працює і надає більшість цінності, і тримає демона складності осторонь, частково.

іноді, можливо, найкраще просто не казати менеджеру проєкту і робити це по-своєму 80/20. легше просити вибачення, ніж дозволу, менеджери проєктів, як метелики, часто перевантажені і мають справу з багатьма ґруґами. часто забувають, що взагалі повинна робити ця функція, або рухаються далі, або звільняються, або їх звільняють, ґруґ бачив багато таких випадків

в будь-якому випадку, це в інтересах менеджера проєкту, тому ґруґу не слід надто сильно перейматися цим підходом

### Факторинг вашого коду

наступна стратегія дуже складніша: правильно розділити кодову базу (модне слово: "факторинг коду"). тут важко дати загальні поради, бо кожна система дуже різна. проте одна річ, у яку ґруґ вірить: не факторуйте свій додаток занадто рано!

на початку проєкту все дуже абстрактне і схоже на воду: дуже мало твердих основ для мозку ґруґа. потрібен час, щоб розвинути "форму" системи і зрозуміти, що взагалі робиться. ґруґ намагається не факторувати на початковому етапі проєкту, і в певний момент з коду з'являються хороші точки розділу

хороша точка розділу має вузький інтерфейс з рештою системи: невелика кількість функцій або абстракцій, які приховують демона складності всередині, як у кристалі

ґруґ дуже задоволений, коли демон складності правильно заточений у кристалі, це найкраще відчуття — заточити смертельного ворога!

ґруґ намагається терпляче спостерігати, як з коду з'являються точки розділу і повільно рефакторує, з часом кодова база приймає форму, накопичується досвід. немає чітких/швидких правил для цього: ґруґ знає точку розділу, коли її бачить, просто потрібен час, щоб розвинути вміння бачити, терплячість

іноді ґруґ починає занадто рано і неправильно створює абстракції, тому ґруґ схиляється до очікування.

великий-мозок розробникам це часто зовсім не подобається, і вони винаходять багато абстракцій на початку проєкту

ґруґу хочеться дотягнутися до дубини і кричати "великий мозок не пиши код! великий мозок переходь до наступного комітету з архітектури, залиш код для ґруґа!"

але ґруґ вчиться контролювати свої пристрасті, це головна різниця між ґруґом і твариною

натомість ґруґ намагається обмежити шкоду від великий-мозок розробника на початку проєкту, даючи їм такі речі, як UML-діаграми (не шкодить коду, ймовірно, їх все одно викинуть) або вимагаючи робочий демо-зразок на завтра

робочий демо-зразок — особливо гарний трюк: змушує великий мозок створити щось, що насправді працює, про що можна говорити і код, який допоможе великому мозку швидше побачити реальність на місцях

пам'ятайте! великий мозок має великий мозок! його потрібно лише спрямувати на добро, а не випадково в служіння демону складності, часто бачив таке

(найкращий ґруґ-мозок здатний направити кілька великих мізків у правильному напрямку і створити багато кристалів для заточення демонів складності, велика купа блискучих каменів чекає на такого ґруґа!)

також іноді називають підхід з демо-зразком "прототипування", звучить більш витончено для менеджера проєкту

ґруґ каже, прототипуй на ранніх етапах розробки програмного забезпечення, *особливо* якщо є багато великих мізків

## Tестування

ґруґ любить і ненавидить тестування: тести врятували ґруґа багато, багато незліченних разів, і ґруґ любить і поважає тести.

на жаль, також існує багато шаманів тестування. деякі шамани тестування роблять тест ідолом, вимагають речі на кшталт "спочатку тест", перш ніж ґруґ навіть напише код або зрозуміє, що ґруґ робить у цій галузі!

як ґруґ може тестувати те, чого ще не розуміє в домені!?

"О, не хвилюйся: тести покажуть тобі, що потрібно робити."

ґруґ знову повільно тягнеться до дубини, але залишається спокійним

ґруґ замість цього воліє писати більшість тестів після фази прототипування, коли код починає набувати форми

але, зверніть увагу: тут ґруґ повинен бути дуже дисциплінованим!

легко ґруґу перейти далі і не писати тести, бо "працює на машині ґруґа"!

це дуже, дуже погано: немає гарантії, що працюватиме на іншій машині і немає гарантії, що працюватиме на машині ґруґа в майбутньому, багато разів перевірено

шамани тестування мають слушну думку щодо важливості тестування, навіть якщо шамани тестування часто не завершують навіть одну корисну функцію в житті і говорять лише про тестування весь час, заслуговують на дубину, але серце у них в правильному місці

також, шамани тестування часто дуже багато говорять про юніт-тести, але ґруґ не знаходить їх настільки корисними. ґруґ досвід показує, що ідеальні тести — це не юніт-тести або end-to-end тести, а щось середнє між ними

ґруґ пише юніт-тести переважно на початку проєкту, допомагає розпочати, але не дуже прив'язується і не очікує великої цінності на довгий час.

end-to-end тести хороші, показують роботу всієї системи, але! важко зрозуміти, коли вони ламаються і часто зводять ґруґа з розуму, іноді ґруґи просто ігнорують їх, бо "о, вони ламаються постійно" - дуже погано!

тести посередині, ґруґ чув, шамани іноді називають "інтеграційні тести" з кислим виразом обличчя. але ґруґ каже, що інтеграційні тести - це ідеальне місце: досить високого рівня, щоб тестувати коректність системи, і досить низького рівня, щоб з хорошим налагоджувачем легко було бачити, що ламається

ґруґ воліє деякі юніт-тести, особливо на початку, але не 100% покриття всього коду тестами і точно не "спочатку тест". "тестування по ходу" працює досить добре для ґруґа, особливо коли ґруґ розбирається з речами

ґруґ фокусується на інтеграційних тестах з моменту, коли з'являються точки розділу і система стабілізується! api і точки розділу, сподіваємось, стабільніші порівняно з реалізацією, і інтеграційні тести залишаються цінними на довгий час, і легко налагоджувати

також створюється невеликий, добре обраний набір end-to-end тестів, який підтримується в робочому стані під загрозою дубини. фокус важливих end-to-end тестів на найпоширеніших функціях ui та кількох найважливіших крайніх випадках, але не надто багато, інакше стане неможливо підтримувати, і їх почнуть ігнорувати

це ідеальний набір тестів для ґруґа.

можливо, вам не сподобається, але це вершина ґруґ-тестування.

також, ґруґ не любить мокати в тестах, воліє тільки коли абсолютно необхідно (рідко/ніколи) і тільки грубе мокання (точки розділу/системи).

один виняток "спочатку тест", який любить ґруґ: коли знайдено помилку. ґруґ завжди намагається спочатку відтворити помилку за допомогою регресійного тесту, а потім виправити помилку, цей випадок чомусь працює краще

## Agile

ґруґ думає, що agile не жахливий, не хороший.

в кінці дня, це не найгірший спосіб організувати розробку, можливо, краще за інші, ґруґ припускає, що нормально.

небезпека, однак, у шаманах agile! багато, багато блискучих каменів втрачається через шаманів agile!

коли agile проєкт зазнає невдачі, шаман agile каже "ви неправильно використовували agile!" ґруґ відзначає, що це дуже зручно для шамана agile, просить більше блискучих каменів для кращого навчання молодих ґруґів agile, небезпека!

ґруґ спокушається дотягнутися до дубини, коли занадто багато розмов про agile, але завжди залишається спокійним.

прототипування, інструменти та наймання хороших ґруґів є кращими ключами до успіху в програмному забезпеченні: процес agile ок і трохи допомагає, але іноді шкодить, коли його сприймають занадто серйозно.

ґруґ каже, що жодна срібна дубина не виправить усі проблеми програмного забезпечення, незалежно від того, що каже шаман agile (небезпека!).

## Рефакторинг

рефакторинг - хороша діяльність і часто гарна ідея, особливо пізніше в проєкті, коли код уже стабілізувався.

проте, ґруґ помічає, що багато разів у кар'єрі "рефакторинги" йшли жахливо невдало і завдавали більше шкоди, ніж користі.

ґруґ не зовсім впевнений, чому деякі рефакторинги працюють добре, а деякі зазнають невдачі, але ґруґ помічає, що чим більший рефакторинг, тим більше ймовірності, що станеться невдача.

тому ґруґ намагається тримати рефакторинги відносно невеликими і не віддалятися "занадто далеко від берега" під час рефакторингу. ідеально, щоб система працювала весь час, і кожен крок був завершений перед початком наступного.

end-to-end тести тут - справжні рятівники, але часто дуже важко зрозуміти, чому вони ламаються... такий вже він, рефакторинг.

також ґруґ помічає, що введення занадто великої кількості абстракцій часто призводить до невдачі рефакторингу і невдачі системи. хороший приклад - введення [J2EE](https://www.webopedia.com/definitions/j2ee/), багато великих мізків сиділи, обдумували занадто багато абстракцій, нічого хорошого з цього не вийшло, багато проєктів постраждало

ще один хороший приклад - коли компанія, де працював ґруґ, впровадила [OSGi](https://www.techtarget.com/searchnetworking/definition/OSGi), щоб допомогти керувати/заточити духа складності в кодовій базі. не тільки OSGi не допоміг, але й зробив демона складності набагато потужнішим! знадобилося кілька років найкращих розробників, щоб переробити все це! більше демона складності і тепер неможливо реалізувати нові функції! дуже погано!

## Огорожа Честертона

мудрий шаман ґруґів, [Честертон](https://en.wikipedia.org/wiki/G._K._Chesterton), одного разу сказав:

 > є певна інституція або закон; скажімо, для простоти, паркан або ворота, зведені через дорогу. більш сучасний тип реформатора підходить до нього весело і каже: «я не бачу сенсу в цьому; давайте приберемо його.» на що більш розумний тип реформатора відповість: «якщо ти не бачиш у цьому сенсу, я, звісно, ​​не дозволю тобі прибрати це. йди подумай. тоді, коли ти зможеш повернутися і сказати мені, що бачиш у цьому сенс, я, можливо, дозволю тобі його зруйнувати.»

багато старших ґруґів добре засвоїли цей урок, не починають виривати код бездумно, незалежно від того, наскільки він потворний

ґруґ розуміє, що всі програмісти-платоністи на якомусь рівні бажають досконалості коду, подібної до музики сфер. але тут є небезпека, світ часто потворний і незграбний, і тому код також повинен бути таким

скромність не часто властива великим мізкам або тим, хто вважає себе великими мізками, або навіть самому ґруґу, але ґруґ часто знаходить, що "о, ґруґ не подобається вигляд цього, ґруґ виправить" приводить до багатьох годин болю для ґруґа і не кращої або навіть гіршої системи

ґруґ на початку кар'єри часто вривався в кодову базу, розмахуючи дубиною і все трощив, вчився, що це не добре

ґруґ не каже, що ніколи не потрібно покращувати систему, це було б зовсім дурно, але рекомендує спочатку витратити час на розуміння системи, особливо якщо вона велика, і поважати код, який працює сьогодні, навіть якщо він не ідеальний

тут тести часто є хорошою підказкою, чому паркан не варто руйнувати!

## Мікросервіси

ґруґ дивується, чому великі мізки беруть найважчу задачу — правильно розбити систему на частини — і додають до цього ще й мережевий виклик.

це здається дуже заплутаним для ґруґа.

## Інструменти

ґруґ обожнює інструменти. інструменти та вміння їх використовувати — це те, що відрізняє ґруґа від динозаврів! інструменти дозволяють ґруґ-мозку створювати код, який інакше був би неможливим, оскільки вони роблять думання за ґруґа — це завжди приємний відпочинок! ґруґ завжди витрачає час, щоб навчитися використовувати нові інструменти, аби максимізувати продуктивність: два тижні на освоєння інструментів часто роблять розробку вдвічі швидшою, а ще ґруґ не повинен постійно ритися та просити допомоги у інших розробників, документації звісно немає.

автозаповнення коду в IDE дозволяє ґруґу не запам'ятовувати всі API, дуже важливо!

програмування на java майже неможливе без цього для ґруґа!

це дійсно змушує ґруґа задуматися час від часу.

гарний дебаггер вартий своєї ваги в блискучих каменях, а насправді ще більше: коли стикаєшся з багом, ґруґ часто був би готовий обміняти всі свої блискучі камені, і, можливо, навіть декількох дітей на гарний дебаггер, та й взагалі, дебаггер нічого не важить, наскільки ґруґ може судити.

ґруґ завжди радить новим програмістам глибоко вивчати доступний дебаггер, особливості, як-от умовні точки зупину, оцінка виразів, навігація по стеку тощо, часто навчать нового ґруґа більше про комп'ютер, ніж університетський курс!

ґруґ каже: ніколи не зупиняйся на шляху до покращення інструментів.

## Системи типів (Type Systems)

ґруґ дуже любить системи типів, вони роблять програмування легшим. для ґруґа система типів найбільше цінна, коли ґруґ натискає крапку на клавіатурі, і магічно з'являється список того, що можна зробити. це 90% або більше цінності системи типів для ґруґа.

великі мізки шаманів систем типів часто кажуть, що правильність типів — головне в системі типів, але ґруґ помічає, що деякі великі мізки шаманів систем типів не часто випускають код. ґруґ припускає, що код, який ніколи не випускається, в певному сенсі правильний, але це не зовсім те, що ґруґ має на увазі, коли говорить про правильність.

ґруґ каже, що магія підказки того, що можна зробити, і завершення коду — головна користь системи типів, правильність також важлива, але далеко не так сильно.

також, іноді треба бути обережним з великими мізками тут!

деякі великі мізки мислять у системах типів і говорять про [леми](./lemms.md), це потенційна небезпека!

небезпека високих абстракцій: код з системою типів великих мізків стає астральною проекцією платонічної моделі обчислень Тьюринга в кодову базу. ґруґ заплутується і погоджується, що на певному рівні це дуже елегантно, але також дуже важко зробити щось типу запису кількості дубин для Grug Inc. — завдання, яке потрібно виконати.

generics тут особливо небезпечні, ґруґ намагається обмежувати generics до контейнерних класів, де вони найбільш корисні.

спокуса до узагальнень дуже велика — це хитрість! дух демона складності дуже любить цей трюк! будьте обережні!

завжди пам'ятайте, що головна цінність системи типів: натиснути крапку, побачити, що ґруґ може зробити, ніколи не забувайте!

### Expression Complexity

ґруґ колись дуже любив мінімізувати кількість рядків коду настільки, наскільки це можливо. писав код ось так:

```javascript
if(contact && !contact.isActive() && (contact.inGroup(FAMILY) || contact.inGroup(FRIENDS))) {
  // ...
}
```

з часом ґруґ навчився, що такий код важко дебажити, і почав віддавати перевагу такому стилю:

```javascript
if (contact) {
  var contactIsInactive = !contact.isActive();
  var contactIsFamilyOrFriends = contact.inGroup(FAMILY) || contact.inGroup(FRIENDS);
  if (contactIsInactive && contactIsFamilyOrFriends) {
    // ...
  }
}
```

ґруґ чує крики молодих ґруґів, які жахаються від великої кількості рядків коду і вважають, що ці зайві змінні безглузді. але ґруґ вже готовий захищати себе своєю дубиною.

починається битва з іншими розробниками, які атакують, але ґруґ кричить у відповідь: "легше дебажити! можна чітко побачити результат кожного виразу і дати йому гарне ім'я! легше зрозуміти умовний вираз! ЛЕГШЕ ДЕБАЖИТИ!"

дебажити справді легше, і коли битва закінчується і молоді ґруґи трохи обмірковують, вони розуміють, що ґруґ має рацію.

ґруґ все ще іноді ловить себе на тому, що пише код, як у першому прикладі, і часто про це шкодує, тому ґруґ не судить молодих ґруґів.

### DRY (Don't Repeat Yourself)

[DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) означає "не повторюй себе" — потужне правило, яке має великий вплив на мислення більшості розробників.

ґруґ поважає DRY і вважає, що це гарна порада. однак ґруґ також рекомендує дотримуватися балансу у всьому, як і рекомендував великий мислитель арістотель, якого ґруґ вважає наймудрішим з великих мізків.

ґруґ помітив гумористичний графік від Lea Verou, яка відображає його пристрасть не повторювати код:
![code concerns over time](./over-time.png)

занепокоєння щодо коду з часом
з роками програмування ґруґ все менше переймається повторенням коду. якщо повторюваний код достатньо простий і очевидний, ґруґ починає вважати, що повторення або копіювання коду з невеликими змінами іноді краще, ніж складні рішення з багатьма колбеками, замиканнями або складними об'єктними моделями. такі рішення можуть бути надто складними і давати занадто мало вигоди.

це складний баланс. повторюваний код завжди змушує ґруґа задумливо бурмотіти "ммм", але досвід показує, що іноді повторення коду краще, ніж надто складне рішення на основі DRY.

**примітка:** ґруґ радить надто серйозним розробникам не сприймати буквально жартівливі зауваження про те, що працює чи ні. це лише жарт.

### Separation of Concerns (SoC)

[Separation of Concerns (SoC)](https://en.wikipedia.org/wiki/Separation_of_concerns) ще одна потужна ідея, яка захопила розум багатьох розробників. ідея полягає в тому, щоб розділити різні аспекти системи на окремі частини коду.

канонічний приклад з веб-розробки: розділення стилів (файл CSS), розмітки (файл HTML) і логіки (файл JavaScript).

тут ґруґ набагато більше кислий на обличчі, ніж від DRY, і навіть написав великий розумний есей про альтернативний принцип дизайну — [locality of behavior (LoB)](https://htmx.org/essays/locality-of-behaviour/) проти SoC.

ґруґ набагато більше любить залишати код на штукі яка робить штуку. тепер, коли ґруґ дивиться на штуку, ґруґ знає, що ця штука робить, завжди добре!

коли застосовується separation of concerns, ґруґ часто мусить бігати по всіх файлах, щоб зрозуміти, як працює кнопка, багато плутанини і марнування часу: погано!

### Замикання (Closures)

ґруґ любить closures для відповідної роботи, і ця робота зазвичай полягає в абстрагуванні операцій над колекціями об'єктів.

ґруґ попереджає: closures як сіль, системи типів і generics — невелика кількість має великий ефект, але легко зіпсувати речі, занадто багато використання може викликати серцевий напад.

JavaScript розробники викликають дуже особливого демона складності — "callback hell", тому що надто багато closures використовуються в бібліотеках JavaScript, це дуже сумно, але також JavaScript розробники отримують те, на що заслуговують, давайте будемо чесними.

### Логування

ґруґ великий фанат логування і закликає робити цього багато, особливо в хмарних середовищах. деякі не-ґруґи кажуть, що логування дороге і не важливе. ґруґ колись думав так само, але вже ні.

смішна історія: ґруґ дізнався, що його кумир [Роб Пайк](https://en.wikipedia.org/wiki/Rob_Pike) працює над логуванням у Google, і вирішив: "якщо сам Роб Пайк працює над логуванням, що тут робить ґруґ?!?" і не став цим займатися (бо це тільки для кращих з кращих). виявилося, що логування дуже важливе для Google, тому, звичайно, найкращий програміст працює над цим, ґруґ!

не будь таким ґруґ-мізком, ґруґ, тепер набагато менше блискучих каменів!

ну що ж, ґруґ все одно опинився в хорошій компанії, а Роб Пайк дедалі частіше [вдягався дивно](https://www.youtube.com/watch?v=KINIAgRpkDA), тому все врешті вийшло, але думка залишається: логування дуже важливе!

поради ґруґа щодо логування:

- логуй усі основні логічні гілки в коді (if/for)
- якщо "запит" охоплює кілька машин в хмарній інфраструктурі, включай ідентифікатор запиту у всі журнали, щоб їх можна було згрупувати
- якщо можливо, зроби рівень логування динамічно контрольованим, щоб ґруґ міг увімкнути/вимкнути його, коли потрібно налагодити проблему (багато!)
- якщо можливо, зроби рівень логування на користувача, щоб можна було налагоджувати проблеми конкретного користувача

останні два пункти особливо зручні, коли доводиться боротися з багами в проді, дуже часто

на жаль, бібліотеки логування часто дуже складні (java, [чому ти така?](https://stackify.com/logging-java/)), але інвестиції часу в налаштування логування "як слід" окупаються пізніше, за досвідом ґруґа.

логування потрібно більше викладати в школах, вважає ґруґ.

### Паралельність (Concurrency)

ґруґ, як і всі здорові розробники, боїться паралельності.

ґруґ намагається якомога більше покладатися на прості моделі паралелізму, такі як безстанні обробники веб-запитів (stateless web request handlers) і прості черги віддалених робочих завдань (remote job worker queues), де завдання не залежать одне від одного, і прості API.

[optimistic concurrency](./optimistic-concurency.md) добре працює для веб-речей.

іноді ґруґ використовує [thread local variable](./thread-local-variable.md), зазвичай, коли пише код для фреймворку.

деякі мови мають хороші concurrent структури даних, такі як `ConcurrentHashMap` в Java, але все одно потрібна обережність ґруґа, щоб все правильно налаштувати.

ґруґ ніколи не використовував [Erlang](https://en.wikipedia.org/wiki/Erlang_(programming_language)), чув хороші речі, але мова виглядає дивно для ґруґа, вибачте.

### Оптимізація

ґруґ колись почув від ультра великого розуму, що:

*premature optimization is the root of all evil*
(передчасна оптимізація — корінь усього зла)

це майже всім відомо, і ґруґ у смиренній, але жорстокій згоді з ультра великим мозком.

ґруґ завжди радить мати конкретний, реальний профіль продуктивності, який показує специфічну проблему продуктивності, перш ніж починати оптимізацію.

ніколи не знаєш, яка проблема може бути насправді, ґруґ часто дивується! дуже часто!

варто остерігатися надмірної уваги до CPU: легко бачити CPU, і багато великих розробників в школі багато думають про O(n) та O(n^2), але це часто не є джерелом усієї повільності, що є несподіванкою для багатьох, включаючи ґруґа.

робота з мережею еквівалентна багатьом, багатьом мільйонам циклів CPU і завжди повинна бути мінімізована, якщо це можливо, запам’ятайте це добре, великі мозки розробників мікросервісів!

недосвідчений великий мозок бачить вкладені цикли та часто каже: "O(n^2)? Ні в якому разі!"

дух демона складності посміхається.

### APIs

ґруґ любить гарні API. гарні API не змушують ґруґа занадто багато думати.

на жаль, багато API дуже погані, змушують ґруґа багато думати. це трапляється з різних причин, ось дві з них:

1. **Автори API думають в термінах реалізації або домену API, а не в термінах використання API.**
2. **Автори API думають занадто абстрактно і занадто великими мізками.**

звичайно, ґруґ не дуже дбає про деталі API: хоче записати файл або відсортувати список чи щось інше, просто хоче викликати `write()` або `sort()` чи щось подібне.

але великі мізки розробників API кажуть:

"не так швидко, ґруґ! чи цей файл відкритий для запису? чи визначив ти `Comparator` для цього сортування?"

ґруґ стримує руку, щоб знову не тягнутися за дубиною.

не хочу зараз турбуватися про ці речі, просто хочу відсортувати і записати файл, пане великий мозок!

ґруґ визнає, що великі мізки розробників API мають рацію і що іноді ці речі важливі, але часто це не так. великі мізки розробників API були б кращими, якби вони проєктували прості API для простих випадків і складні API для складних випадків.

ґруґ називає це "шаруванням" API: два або три різні API на різних рівнях складності для різних потреб ґруґа.

також, якщо об'єктно-орієнтовано, помістіть API на ту річ, яка робить дію, а не кудись ще. Java найгірша в цьому!

ґруґ хоче відфільтрувати список у Java.

"Чи конвертував ти його в стрім?"

добре, ґруґ конвертує у стрім.

"ОК, тепер ти можеш відфільтрувати."

ОК, але тепер потрібно повернути список! у ґруґа є стрім!

"Ну, чи зібрав ти свій стрім у список?"

що?

"Визнач `Collector<? super T, A, R>`, щоб зібрати свій стрім у список."

ґруґ тепер присягає на могилі предків, що він буде бити всіх у кімнаті, але рахує до двох і залишається спокійним.

помістіть загальні речі, як `filter()`, на список і поверніть список, слухайте добре, великі мізки розробників Java API!

ніхто не турбується про "стрім" і ніколи раніше не чув про "стрім", це ж не мережевий API, усі ґруґи в Java використовують список, пане великий мозок!

### Парсинг

ґруґ дуже любить створювати мови програмування на льоту і вважає, що [рекурсивний спуск](https://en.wikipedia.org/wiki/Recursive_descent_parser) — це найвеселіший і найкрасивіший спосіб створити парсер.

на жаль, багато великих мізків у школах навчають тільки використанню генераторів парсерів. тут ґруґ не відчуває звичної любові до інструментів: генератори парсерів створюють код, що схожий на зміїне кубло: неможливо зрозуміти, робота відбувається знизу догори, що? приховують рекурсивну природу граматики від ґруґа, а дебажити це неможливо, дуже погано на думку ґруґа!

ґруґ вважає так через те, що хоча демон складності поганий для кодової бази і розуміння, він дуже хороший для створення великої кількості академічних статей, сумно, але правда.

продакшн парсери майже завжди використовують рекурсивний спуск, незважаючи на те, що школи ігнорують це! ґруґ був в люті, коли дізнався, наскільки просто створити парсер! парсинг — це не магія тільки для великих мізків: це може зробити і ти!

ґруґ був дуже радий, коли знайшов великий-мізок розробника Боба Ністрома, який реабілітував плем'я великих мізків і написав відмінну книгу про рекурсивний спуск: [*Crafting Interpreters*](https://craftinginterpreters.com/).

книга доступна онлайн безкоштовно, але ґруґ настійно рекомендує всім зацікавленим ґруґам купити книгу з принципових міркувань, вона містить багато порад від великих мізків, і ґруґ дуже любить цю книгу, за винятком патерну відвідувача (пастка!).

### Патерн Відвідувача (The Visitor Pattern)

[погано](./visitor-pattern.md).

### Front End Development

деякі не-ґруґи, зіткнувшись із веб-розробкою, кажуть:

"Я знаю! Я розділю кодову базу на фронтенд і бекенд і використаю нову бібліотеку для SPA, яка взаємодіє з GraphQL JSON API через HTTP (що смішно, тому що я не передаю гіпертекст)."

тепер у вас два лігва демона складності.

і що ще гірше, демон складності на фронтенді навіть могутніший і має глибокий духовний вплив на всю індустрію фронтенду, наскільки ґруґ може судити.

бекенд-розробники намагаються тримати все просто, і це може працювати, але фронтенд-розробники дуже швидко роблять все складним і вводять багато коду, що приваблює демона складності.

навіть коли сайт потрібно просто додати форму в базу даних або створити простий інформаційний сайт!

всі зараз так роблять!

ґруґ не впевнений чому, хіба що може бути тому, що Facebook і Google так кажуть, але це не здається ґруґу дуже хорошою причиною.

ґруґ не любить великі складні фронтенд-бібліотеки, які всі використовують.

ґруґ створив [htmx](https://htmx.org/) і [hyperscript](https://hyperscript.org/), щоб уникнути цього.

тримайте складність на низькому рівні, використовуйте простий HTML, уникайте великої кількості JavaScript — це природне середовище для демона складності.

можливо, це підійде вам, але роботи з цим не отримати, вибачте.

React краще для роботи, а також для деяких типів застосунків, але також ви стаєте послідовником демона складності, хочете ви цього чи ні, вибачте, таке життя фронтенд-розробника.

### Fads

ґруґ помічає багато модних тенденцій у розробці, особливо у фронтенд-розробці сьогодні.

бекенд більш нудний, і це краще, тому що всі погані ідеї вже пробувалися на цьому етапі, можливо (хоча деякі все одно повторюють!).

у фронтенд-розробці все ще пробують усі погані ідеї, тому все ще багато змін і важко орієнтуватися.

ґруґ рекомендує брати всі революційні нові підходи з часткою скептицизму: великі мізки працюють над комп’ютерами вже давно, більшість ідей вже випробували хоча б один раз.

ґруґ не каже, що не можна вчитися нових трюків або що немає хороших нових ідей, але також багато часу витрачається на відновлення старих поганих ідей. багато сил демона складності виходить із введення нових ідей навмання в кодову базу.

### Cтрах виглядати дурними (Fear Of Looking Dumb (FOLD))

**примітка!** дуже добре, якщо старший ґруґ готовий публічно сказати: "гммм, це занадто складно для ґруґа!"

багато розробників мають страх виглядати дурними (Fear Of Looking Dumb, FOLD). ґруґ теж колись страждав від FOLD, але ґруґ навчився долати цей страх: дуже важливо, щоб старший ґруґ сказав: "це занадто складно і незрозуміло для мене."

це робить нормальною ситуацію, коли молодші ґруґи також зізнаються, що їм щось здається занадто складним і вони цього не розуміють, що відбувається дуже часто! FOLD — основне джерело сили демона складності над розробниками, особливо молодими ґруґами!

забрати силу FOLD — дуже добре для старшого ґруґа!

**примітка:** важливо зробити задумливе обличчя і виглядати великим розумом, коли кажеш це. будь готовий до того, що великий мозок або, що гірше і набагато частіше, той, хто вважає себе великим мозком, зробить глузливий коментар на адресу ґруґа.

будь сильним! жодного FOLD!

дубина іноді корисна тут, але частіше допомагає почуття гумору, а особливо останній провалений проєкт великого мозку, дуже корисно збирати такі моменти і залишатися спокійним.

### Синдром Самозванця (Impostor Syndrome)

ґруґ помічає, що багато таких відчуттів "самозванця" існує в розробці.

завжди ґруґ у двох станах: або ґруґ володар усього, що він бачить, розмахує кодовою дубиною як Тор, АБО ґруґ не має жодного уявлення, що робить.

ґруґ здебільшого у другому стані більшість часу, але приховує це доволі добре.

тепер ґруґ робить багато софтів, має [помірний успіх в open source](https://star-history.com/#bigskysoftware/htmx&bigskysoftware/_hyperscript&Date), і все ж ґруґ часто відчуває, що не має жодного уявлення, що робить! дуже часто! ґруґ все ще боїться зробити помилку, зламати код усім і розчарувати інших ґруґів — самозванець!

це, можливо, природа програмування для більшості ґруґів відчувати себе самозванцем, і змиритися з цим — найкраще: ніхто не самозванець, якщо всі самозванці.

будь-який молодий ґруґ, який дочитав до цього місця, мабуть, добре справляється в кар'єрі програміста, навіть якщо розчарування і занепокоєння завжди будуть там, вибачте.

### Почитати

ґруґу подобається:

- [Worse is Better](https://www.dreamsongs.com/WorseIsBetter.html)
- [Worse is Better is Worse](https://www.dreamsongs.com/Files/worse-is-worse.pdf)
- [Is Worse Really Better?](https://www.dreamsongs.com/Files/IsWorseReallyBetter.pdf)
- [A Philosophy of Software Design](https://www.goodreads.com/en/book/show/39996759-a-philosophy-of-software-design)

### Висновок

ти кажеш: складність дуже, дуже погано
