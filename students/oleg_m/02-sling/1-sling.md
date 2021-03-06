## Структурна лінгвістика

### 1. Побудуйте ланцюжок походження слів за зразком:

оженитися: (о + (женити + ся))

1. несприйнятливість: (не + (с +(прийнят + ливість)))
2. атиповий: (а + (тип + о + вий))
3. безвідповідально: (без + (від + (повід) + альн + о))
4. мореплавання: (мор) + е + (плав + ання)
5. оподаткувати: (о + (податк + увати))
6. перевтілитися: (пере + ((в + тіл) + итися))
7. схилившись: ((с + хил + ив) + шись))
8. трьохярусний: (трьох + (ярус + ний))
9. підсніжник: (під + (сніж + ник))
10. зужиткований: (з + ((у + жит) + кований))


### 2. Перевірте роботу [SnowballStem](http://snowballstem.org/) для спільнокореневих слів. Напишіть ваші спостереження.

1. truth, truthful, truthfulness, countertruth, untruthful, truthology.
   
   Корені: truth, truth, truth, countertruth, untruth, trutholog

2. flaw, flaws, flawed, flawless, flawlessness, flawlessly, 
 
   Корені: flaw, flaw, flaw, flawless, flawless, flawless

3. лес, лесной, лесник, лесничий, лесничество, пролесье

   Корені: лес, лесн, лесник, леснич, лесничеств, пролес

4. окно, окошко, подоконник, оконный, окнище

   Корені: окн, окошк, подоконник, окон, окнищ
   
Видно, що алгоритм побудовано на правилах і визначення корення відбувається тільки за рахунок відділення відомих закінчень чи суфіксів. Префікси або інші корені не виділяються як в англыйській так і в російській мові.


### 3. Визначте частину мови виділеного слова і зв'язок до його батька (за зразком):

{I} like turtles.: pronoun, nsubj(like, I)  
I {like} turtles.: verb, root(ROOT, like)  
I like {turtles}.: noun, dobj(like, turtles)

1. We can {but} hope that everything will be fine.: conj, cc(can, but)
2. It's sad {but} true.: conj, cc(sad, but)
3. Jack brings nothing {but} trouble. adp, prep(nothing, but)
4. {As} we were talking, I realised how to solve the issue.: adp, mark(talking, as)
5. This hot dog isn't {as} big as usual.: adv, advmod(big, as)
6. This hot dog isn't as big {as} usual.: adv, advmod(big, as)
7. This hot dog isn't as big {as} I expected.: adv, advmod(expected, as)
8. I work {as} a teacher.: adp, prep(work, as)
9. Let's do it this {way}!: noun, npadvmod(do, way)
10. This is {way} too much!: adv, advmod(much, way)
11. The prices are going {down}.: adv, advmod(going, down)
12. Someone pushed him and he fell {down} the stairs.: adp, prep (fell, down)
13. I’ve been feeling rather {down} lately. adv, advmod(feeling, down)
14. It's not easy to {down} a cup of coffee in one gulp. verb, xcomp(is, down)
15. Bring a {down} jacket and a pair of gloves, and you'll be fine. noun, dobj(bring, a down jacket)


### 4. Визначте частину мови виділеного слова, його лему і зв'язок до його батька (за зразком):

{Я} люблю черепашок.: займенник, я, nsubj(люблю, Я)  
Я {люблю} черепашок.: дієслово, любити, root(ROOT, люблю)  
Я люблю {черепашок}.: іменник, черепашка, dobj(люблю, черепашок)  

1. Рада міністрів Європейського союзу затвердила угоду про спрощений порядок видачі {віз} для України.: іменник, віза, dobj(видачі, віз) 
2. Батько Себастьяна {віз} на санях їх театральний гурт до Львова.: дієслово, возити, root(ROOT, віз)
3. А ще дивний елемент інтер’єру – {віз} із продукцією одного з херсонських виробників. іменник, віз, appos(елемент, віз)
4. У цю мить {повз} Євгена пролетів останній вагон товарняка.: прийменник, повз, advmod(Євгена, повз)
5. Кліпнув очима і побачив малого песика, який саме пробігав {повз} у бік села.: прислівник, повз, conj(пробігав, повз)
6. Степанко перестав кричати, тільки ламкий стогін {повз} йому із грудей.: дієслово, повзти, root(ROOT, повз)
7. Часу не {гай} – декларацію подай!: дієслово, гаяти, root(ROOT, гай)
8. І коляд заспівали, і {гай} врятували.: іменник, гай, dobj(врятували, гай)
9. {Гай}, чи ви забулися, братове?: вигук, гай, intj(забулися, гай)
10. Ось присіла на {край} ліжка.: іменник, край, pobj(на, край)
11. Поставив ту кузню не {край} дороги, як було заведено, а на Красній горі, біля Прадуба.: прийменник, край, ccomp(дороги, край)
12. Розповідаючи про передній {край} лінґвістики, фон Лібіх, як завжди, мислив широко і глобально.: іменник, край, pobj(про, край)
13. Не {край} мені серце.: дієслово, краяти, root(ROOT, край)
14. І {щойно} тоді додаємо до борщу смажену цибулю.: частка підсилювач, щойно, сс(тоді, щойно)
15. Бо {щойно} я задрімав, віддавши тіло подушці з периною, як мене розбудив поштовх у бік.: сполучник, щойно, adv(задрімав, щойно) 

### 5. Побудуйте синтаксичну структуру речень за зразком:

Я люблю черепашок.  
nsubj(люблю, Я)  
root(ROOT, люблю)  
dobj(люблю, черепашок)

1. Пригадую, уже згодом, коли я відбував свій термін у таборі № 36 у Кучино Пермської області, я отримав від Михасі листівку з жартівливим описом того, як Київ готується до святкування свого 1500-ліття.
Пригадую: root(ROOT, люблю) 
,
уже згодом: pobj(Пригадую, уже згодом)
,
коли: advmod(відбував, коли)
я: nsubj(відбував, я)
відбував: advcl(Пригадую, відбував)
свій: poss(термін, свій)
термін: dobj(відбував, термін)
у: prep(відбував, у)
таборі: pobj(у, таборі)
№ 36: nummod(таборі, № 36)
у: prep(таборі, у)
Кучино: pobj(у, Кучино)
Пермської: amod(області, Пермської)
області: appos(Кучино, області)
,
я: nsubj(отримав, я)
отримав: ccomp(Пригадую, отримав)
від: prep(листівку, від)
Михасі: pobj(від, Михасі)
листівку: dobj(отримав, листівку)
з: prep(листівку, з)
жартівливим: amod(описом, жартівливим)
описом: pobj(з, описом)
того: advmod(описом, того як)
Київ: nsubj(готується, Київ)
готується: acl(описом, готується)
до: aux(святкування, до)
святкування: xcomp(готується, святкування)
свого: poss(1500-ліття, свого)
1500-ліття: pobj(святкування, 1500-ліття)
.

2. 6C приземляється на плече, перекочуючись, пролітає метрів п’ятдесят і витягується на снігу за кілька кроків від забризканої палаючими уламками посадкової смуги.
6C: nsubj(приземляється, 6C)
приземляється: root(ROOT, приземляється)
на: prep(приземляється, на)
плече: pobj(на, плече)
,
перекочуючись: advmod(приземляється, перекочуючись)
,
пролітає: ccomp(приземляється, пролітає)
метрів: dobj(пролітає, метрів)
п’ятдесят: nummod(метрів, п’ятдесят)
і: conj(пролітає, i)
витягується: ccomp(пролітає, витягується)
на: prep(витягується, на)
снігу: pobj(на, снігу)
за: prep(витягується, за)
кілька: nummod(кроків, кілька)
кроків: pobj(за, кроків)
від: prep(кроків, від)
забризканої: amod(смуги, забризканої)
палаючими: amod(уламками, палаючими)
уламками: dobj(забризканої, уламками)
посадкової: amod(смуги, посадкової)
смуги: dobj(смуги, від)
.


3. Дівчина стояла там, де й була, і намагалася привести до ладу скуйовджене волосся, вкрай розлючена тим, що це побачили водії, які чекали на переїзді.
Дівчина: nsubj(стояла, Дівчина)
стояла: root(ROOT, стояла)
там, де й: advmod(була, там, де й)
була: ccomp(стояла, була)
,
і: cc(стояла, і)
намагалася: ccomp(стояла, намагалася)
привести: ccomp(намагалася, привести)
до ладу: advmod(привести, до ладу)
скуйовджене: amod(волосся, скуйовджене)
волосся: dobj(привести, волосся)
,
вкрай: advmod(розлючена, вкрай)
розлючена: advmod(була, розлючена)
тим, що: mark(розлючена, тим що)
це: dobj(побачили, це)
побачили: ccomp(стояла, побачили)
водії: dobj(побачили, водії)
,
які: det(водії, які)
чекали: csubj(водії, чекали)
на: prep(чекали, на)
переїзді: pobj(на, переїзді)
.


### 6. Виберіть одне cлово зі списку та побудуйте лексико-семантичні зв'язки до трьох різних значень цього слова. Фактично, потрібно побудувати WordNet-подібні вузли. Значення слів можна перевірити у [СУМі](http://sum.in.ua/) та [Словниках України](http://lcorp.ulif.org.ua/dictua/).

Слова на вибір: вік, стіна, добро, серце, центр, куля, міст, ланцюг, бік, дух.

стіна
1. стіна - підлога - дах - кімната - будівля
2. стіна - паркан - огорожа - мур
3. сітна - захисна споруда - фортеця - замок