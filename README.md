## [Zadaća 1](https://github.com/ajla-brdarevic/Poslovna-inteligencija/blob/main/1.%20zada%C4%87a%20iz%20Poslovne%20inteligencije.pdf)
1. Napisati pet poslovnih zahtjeva u vidu pitanja koje je potrebno odgovoriti.
2. Za svako pitanje napisati kratko obrazloženje šta se može saznati iz navedenog pitanja i na koji način takve informacije mogu uticati na donošenje neke odluke.
3. Navesti koje tabele su potrebne za zadane informacije i za svako pitanje navesti koje tabele je potrebno povezati i kako se povežu da bi se dobile tražene informacije.
4. Dizajnirati erd šemu za zvjezda šemu koja može odgovoriti na tražena pitanja.

## [Zadaća 2](https://github.com/ajla-brdarevic/Poslovna-inteligencija/blob/main/2.%20zadaća%20iz%20Poslovne%20inteligencije.pdf)
1. Koristeći generatedata.com generisati tabelu sa podacima prema datim postavkama.
2. Učitati tabelu u proizvoljnu bazu podataka.
3. Napraviti izmjene tabele koristeći skriptu Vjezba2Izmjene.sql (u slučaju druge baze koja nije SqlServer napraviti analogne izmjene).
4. Koristeći datum iz tabele kreirati vremensku dimenziju i njene hijerarhije.
5. Kreirati posebnu tabelu koja predstavlja olap kocku nad datom tabelom sa sve tri dimenzije i svim hijerarhijama za mjeru M1,M2 i MPostotak i Count.

## [Zadaća 3](https://github.com/ajla-brdarevic/Poslovna-inteligencija/blob/main/3.%20zadaća%20iz%20Poslovne%20inteligencije.pdf)
Nad bazom AdventureWorks(AW) ili nad bazom sa šemom sales history (SH) postavljenoj u Oracle live izvršiti sljedeće smislene analize. Za svaki upit napisati kratko obrazloženje, SQL kod upita i priložiti sliku rezultata upita.
1. Slice nad tabelom FactInternetSales(AW) ili Sales(SH)
2. Dice nad tabelom FactFinance(AW) ili Profits(SH)
3. ROLLUP nad tabelom FactResellerSales(AW) ili Costs(SH)
4. CUBE nad tabelom FactResellerSales(AW) ili Profits(SH)
5. GROUP SET nad tabelom FactResellerSales(AW) ili Costs(SH)
6. PIVOT nad tabelom FactFinance(AW) po godinama ili Sales(SH) po godinama

## [Zadaća 4](https://github.com/ajla-brdarevic/Poslovna-inteligencija/blob/main/4.%20zadaća%20iz%20Poslovne%20inteligencije.pdf)
Nad kockom AdventureWorks obaviti MDX analize. Za svaki upit napisati kratko obrazloženje, MDX kod upita i priložiti sliku rezultata upita. Nije dozvoljeno kopirati identičan upit sa prezentacije i ponuditi ga u takvoj formi kao jedan od upita.
1. SLICE nad mjerom [Resseler Gross Profit] prikazanu po dvije proizvoljne dimenzije i proizvoljnom trećom dimenzijom za slice bez null vrijednosti.
2. Dice nad proizvoljnom mjerom i proizvoljnom dimenzijom za godine 2011, 2012 i 2013.
3. PIVOT nad defaultnom mjerom, po dvije proizvoljne dimenzije.
4. Analiza sa izračunatom mjerom od Discount percentage i jednom ili više drugih mjera, po jednoj proizvoljnoj dimenziji.
5. Analizu koristeći RANGE u rasponu od 2010 do 2014 prikazati proizvoljnu mjeru po proizvoljnoj dimenziji.
6. Analiza koristeći HAVING sa proizvoljnom mjerom i lokacijskom dimenzijom.
7. DRILL-Down analiza sa proizvoljnom mjerom i dimenzijom koja nije vremenska dimenzija.
8. Podupit sa TOP analizom nad mjerom [Reseller order quantity].

## [Zadaća 5](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/5.%20zadaća%20iz%20Poslovne%20inteligencije)
Nad sample podacima iz PowerBi napraviti sljedeće vizuelizacije. Sve vizuelizacije priložiti u jednom Power BI projektu i na mail poslati PDF izvještaj i PowerBI projekat. U izvještaju je potrebno uzeti screenshot svake od vizuelizacija i obrazložiti vizuelizaciju. Za vizuelizaciju pod tačkom 1 je potrebno priložiti sliku prije i poslije drill down operacije.
1. Chart vizuelizaciju sa drill down mogućnošću, sa pie ili donut ili treemap vizuelizacijom sa 3 slicera.
2. Chart vizuelizaciju koja na sebi ima i line.
3. Vizuelizaciju mape sa državama i jednim slicerom.
4. KPI vizuelizacija gdje je potrebno odrediti referentnu vrijednost.
5. Importovati jednu proizvoljnu custom vizuelizaciju i primijeniti je nad podacima.
   
## [Zadaća 7](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/7.%20zadaća%20iz%20Poslovne%20inteligencije)
Data je šema relacione baze podataka. Potrebno je koristeći apache hop generisati sve tabele i njihove sadržaje kao jedan pipeline.
Drugi pipeline treba da sve tabele i podatke prebaci u star šemu datu na sljedećoj slici. Zarada se računa po dužini trajanja gledanja filma puta cijena po minuti, a gubici kao cijena licence po gledanju filma. Zatim je potrebno napraviti workflow koji prvo pokreće pipeline za generisanje a zatim pipeline za transformacije. Koristiti varijable za workflow konfiguraciju da li se radi generisanje ili transformacija. Dva pipeline i workflow trebaju biti u sklopu jednog projekta.

## [Zadaća 8](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/8.%20zadaća%20iz%20Poslovne%20inteligencije)
Koristeći rapidminer primijeniti detekciju outlier na sample skupu podataka iz rapidminera koji nije wine dataset. U izvještaju je potrebno priložiti screenshot i obrazloženje za:
1. Početni skup podataka.
2. Tabelu sa detektovanih 10 outlier vrijednosti.
3. Vizualizaciju outlier vrijednosti
   
## [Zadaća 9](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/9.%20zadaća%20iz%20Poslovne%20inteligencije)
Koristeći rapidminer nad skupom podataka iz predhodne vježbe proglasiti jednu kolonu za outlier vrijednosti kao null i obaviti čišćenje podataka. U izvještaju je potrebno priložiti screenshot i obrazloženje za:
1. Početni skup podataka.
2. Tabelu sa null vrijednostima
3. Pipeline i odabrani metod čišćenja (ne može ignore missing values)
4. Tabelu sa zamijenjenim očišćenim vrijednostima

## [Zadaća 10](https://github.com/ajla-brdarevic/Poslovna-inteligencija/blob/main/10.%20zadaća%20iz%20Poslovne%20inteligencije.pdf)
Koristeći GoogleBigQuery nad jednim od sample skupom podataka obaviti 3 proizvoljna upita. Za svaki upit je potrebno:
1. Objasniti koji su podaci i cilj upita
2. Priložiti screenshot upita
3. Priložiti screenshot rezultata
4. Priložiti screenshot vizualizacije rezultata upita

## [Zadaća 11](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/11.%20zadaća%20iz%20Poslovne%20inteligencije)
Nad sample skupom podataka iz rapidminer koji nije potrošačka korpa ili iris dataset kreirati asocijativna pravila. U izvještaju je potrebno prikazati sliku i obrazložiti sliku za:
1. Screenshot rapidminer projekta.
2. Primjer skupa podataka
3. Primjer kreiranih asocijativnih pravila.
4. Vizuelizaciju asocijativnih pravila.
5. Skup podataka sa podrškom i pouzdanošću

## [Zadaća 12](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/12.%20zadaća%20iz%20Poslovne%20inteligencije)
Nad sample skupom podataka iz rapidminer koji nije golf ili iris dataset kreirati dva stabla odlučivanja i uporediti rezultate. U izvještaju je potrebno prikazati sliku i obrazložiti sliku za:
1. Screenshot rapidminer projekta.
2. Primjer skupa podataka
3. Primjer oba kreirana stabla odlučivanja.
4. Prikazane predikcije za isti dataset za jedno i drugo stablo.

## [Zadaća 13](https://github.com/ajla-brdarevic/Poslovna-inteligencija/tree/main/13.%20zadaća%20iz%20Poslovne%20inteligencije)
Nad sample skupom podataka iz rapidminer koji nije polynomial dataset napraviti i primijeniti model linearne regresije. U izvještaju je potrebno prikazati sliku i obrazložiti sliku za:
1. Screenshot rapidminer projekta.
2. Primjer skupa podataka
3. Rezultat modela linearne regresije
4. Rezultat testnog skupa podataka
