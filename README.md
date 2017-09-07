# apsolventske-ekskurzije
Projekat iz Programiranja Baza Podataka


### 📕 Opis 📕
Matematički fakultet za apsolvente tradicionalno organizuje apsolventsku ekskurziju na destinaciju za koju se opredeli najveći broj zainteresovanih studenata. Apsolventom se smatraju studenti kojima je ostalo manje od 60 bodova do završetka studija. Spisak ponuda koje turistička agencija nudi dat je u tabeli: 
```
create table ponude( 
rbr smallint not null, 
destinacija char[30] not null, 
cena smallint not null, 
min_broj smallint not null, 
primary key(rbr)) 
```
Kolona rbr označava jedinstveni redni broj ponude, a pored nje dat je i naziv ponuđene destinacije i njena cena, kao i minimalan neophodan broj studenata potreban da bi se ekskurzija realizovala. Spisak anketiranih studenata zajedno sa njihovim željama dat je u tabeli anketa: 
```
create table anketa( 
indeks integer not null, 
rbr smallint not null, 
primary key(indeks)) 
```
Napisati program kojim se od svih ponuđenih destinacija izdvaja ona za koju se opredelio najveći broj studenata među onima za koje postoji minimalan potreban broj zainteresovanih studenata; pritom zanemariti glasove studenata koji nisu apsolventi. Politika agencije jeste da na svakih 30 studenata da jednu besplatnu ekskurziju i dve sa 50% popusta. Fakultet određuje da će to biti najbolji studenti (rangirani prema proseku, a među onima koji imaju isti prosek boljim se smatra onaj student koji kraće studira) od onih koji su se odlučili za tu opciju. Apsolventima koji su podržavali neku od drugih opcija daje se mogućnost (postavljanjem odgovarajućeg pitanja) da se odluče da li ipak žele da putuju na izglasanu destinaciju. Izmene se vrše nad tabelom anketa. Nakon toga štampa se izveštaj o troškovima ekskurzije: za svakog od studenata koji putuje ispisuju se troškovi ekskurzije, uzimajući u obzir da neki od studenata putuju po povlašćenim cenama. Izveštaj prikazati uređen rastuće prema troškovima.

### 💻 Tehnologije 💻
* Java
* JavaFx
* DB2

### 🌈 Demo 🌈
![alt tag](https://raw.githubusercontent.com/fr1sk/apsolventske-ekskurzije/master/screenshoots/1.png)
ekran 1

![alt tag](https://raw.githubusercontent.com/fr1sk/apsolventske-ekskurzije/master/screenshoots/2.png)
ekran 2

![alt tag](https://raw.githubusercontent.com/fr1sk/apsolventske-ekskurzije/master/screenshoots/3.png)
ekran 3

![alt tag](https://raw.githubusercontent.com/fr1sk/apsolventske-ekskurzije/master/screenshoots/4.png)
ekran 4

![alt tag](https://raw.githubusercontent.com/fr1sk/apsolventske-ekskurzije/master/screenshoots/5.png)
ekran 5

![alt tag](https://raw.githubusercontent.com/fr1sk/apsolventske-ekskurzije/master/screenshoots/6.png)
ekran 6

