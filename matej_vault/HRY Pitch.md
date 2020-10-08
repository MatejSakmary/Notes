## Engine
[[Unity]][[Pitch]]
## Rogue like
-> binding of isaac - jedna mítnost na fullscreen
								zvyšující obtížnost s každou projitou místností
								cíl hry přežít-porazit bosse
								
### Grafika 
 - pseudo 3D isometrické
 - efekty jako "komiks" bubliny

### Combat 
- hráč začíná se základní zbraní (meč) a v průběhy hry dostává přístup k pokročilejšímu vybavení
- secret schovaný za zničitelnou zdí

### Mechaniky
- boj zblízka i na dálku
- inventář, speciánlí předměty aka potion atd...
- zničitelné prostředí
- FOV popřípadě hra se světlem
- xp systém 
- jednoduchá fyzika 
- achievementy
- (savování postav)
- WASD movement, míření myší (dodge)
- hudba, zvuky - zvukové efekty
- ukládání hry
- setting hry (context 'proč utíkám, bojuju atd')
- každý enemy má vlastní styl boje popř. kooperace AI

# Základní myšlenka
Top down Roguelike hra na styl Binding of Isaac. Mapa by se skládala z  pospojovaných místností, které se prostupně procházejí. Každá místnost bude obsahovat náhodně vygenerované nepřátele a prostředí. Počet a obtížnost jednotlivých místností stoupá s počtem hráčem již projitých místností. Hráč ale může v každé místnosti nalézt lepší vybavení a získávat xp zabíjením nepřátel. Cílem hry je projít co nejvíce nejvíce místností, porazit bosse a tím vyhrát hru.

# Grafika 
Hra by vykerslována z isometrické perspektivy a skládala by se z 2D spritů, čímž by byla vytvořena iluze 3D grafiky. Na obrazovce by se vždy nacházela pouze ta místnost ve které se hráč aktuálně nachází. Půdorys jedné místnosti by byl vždy čtvercový a místnost by dále mohla být rozdělená na více meších částí pomocí zdí.

# Feature list
- Boj zblízka i na dálku - hráč bude moct nalézt různé typy zbraní a vybavení, kterými se bude bránit novým nepřátelům v každé místnosti. Třídy zbraní budou meče, dýky a jiné zbraně na blízkou vzdálenost, nebo luky a jiné zbraně na dálku.
- inventář - Bude obsahovat základní přehled o hráčově vybavení např. jakou zbraň zrovna používá.
- zničitelné prostředí - Hráč mít možnost zničit barely, džbány a některé zdi, pomocí různě silných útoků
- FOV - Ve hře bude implementována "fog of war" mechanika založená na FOV. Například, pokud se za hráčem bude nacházet nepřítel, nebude vidět, dokud se hráč neotočí a nepřítel se nedostane do hráčova zorného pole
- XP - Za každého zabitého nepřítele bude získáno určité množství xp zvyšující level postavy
- Netriviální AI -  Různé typy nepřátel např. Thief - snaží se dostat se z FOV a připlížit ze za záda, nebo Warrior - útočí na hráče přímo např pomocí charge nebo podobné mechaniky
- Achievemety - zabito 50 nepřátel mečem, boss poražen do x minut atd
- Pathfinding na Gridu


# Ovládání
Pohyb herní postavy bude ovládán pomocí WASD, míření a boj bude ovládán myší. Hráčova postava bude mít možnost úskoku z nepřátelnkých útoků. Popřípadě podpora Gamepadu.
