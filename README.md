# Podatkovno rudarjenje 2021/2022 - Projektna naloga

Člani:
* Aladin Ćemalović
* Marta Rašeta
* Tilen Berlak

### Predstavitev podatkov

Za projektno nalogo bomo poskusili odkriti zanimive vzorce iz podatkov o porabi energije po namembnosti in viru v Sloveniji. Podatke smo pridobili s spletne strani https://podatki.gov.si/

Podatki iz spletne strani so v formatu PX, zato jih bo potrebno primerno obdelati. Meritve so zajete od leta 2000 do 2020. Preverili bomo energetske vire (premog, lesna goriva, električna energija, zemeljski plin, itd.) in namene za katere se uporabljajo (ogrevanje prostorov, kuhanje, razsvetljava, itd.). Iz tega lahko na primer primerjamo koliko energije iz kurilnega olja ali lesnih goriv gre za ogrevanje gospodinjskih prostorov.

| Atribut         | Opis        | Podatkovni tip |
| -----------     | ----------- | -------------- |
|   Leto          | Meritve so za vsako leto od 2000 do 2020            |       string         |
| Energetski vir  |   lesna goriva, električna energija, premog itd.          |    string            |
|  Namen uporabe  |  kje se energija uporablja (ogrevanje prostorov, kuhanje , itd.)           |    string            |
| Poraba energije |   Merska enota električne energije je v TJ (Terajoules)                    | float |

### Ugotovitve

Najprej smo primerjali povprečno porabo skozi leta vseh energijskih virov. Iz grafa lahko razberemo, da ima največji delež porabe ogrevanje prostorov. Naslednji po vrsti je ogrevanje vode. Ostali porabniki predstavljajo zelo majhen delež.

![Vizualizacija1](Projekt/graph1.png)

Nato smo preverili kako se poraba dveh največjih električnih porabnikov (ogrevanje prostorov in vode) spreminja skozi leta. V zadnjih petih letih se je poraba ogrevanja prostorov precej zmanjšala. Ogrevanje vode pa je ostalo konstantno.

![Vizualizacija2](Projekt/graph2.png)

