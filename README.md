# Kryzys 2025
Kryzys 2025 to seria wirtualnych gier planszowych zrealizowanych w silniku Vassal, opartych na systemie World War 3 (WW3) wydawnictwa Taktyka i Strategia.
Gry i instrukcje do systemu można zakupić m.in. tutaj:

* 👉 System WW3 Taktyka i Strategia https://taktykaistrategia.pl/kategoria-produktu/nasze-gry/?filter_system=ww3&query_type_system=or
* 👉 Sklep Taktyka i Strategia https://taktykaistrategiasklep.pl/


## Uwaga
<span style="color:red"> 
Scenariusze nie przedstawiają żadnej oceny wydarzeń politycznych w Polsce i w Europie. Ta hipotetyczna sytuacja jest wymyślona w celach zabawy i refleksji nad sposobem i procesem prowadzenia działań zbrojnych na terenie Polski, z uwzględnieniem ludności cywilnej oraz infrastruktury krytycznej dla Polski.
</span>

## Opis konfliktu

Seria opowiada o hipotetycznej wojnie domowej w Polsce. Na skutek pogarszającej się sytuacji międzynarodowej kraj znalazł się w stanie głębokiego politycznego kryzysu, a wrogie sobie siły rozdzierają państwo od środka. W tych czasach niepewności, powstaje kilka zmilitaryzowanych bloków, które dążąc do realizacji swoich politycznych planów, wpadają w spiralę konfliktu.

W konflikcie biorą udział cztery frakcje:

* 🟦 Lojalne wobec rządu siły **Sojuszu Europejskiego**, dążące do przyłączenia Polski do Federacji Europejskiej.
* 🟥 Narodowi buntownicy z **Armii Wolności**, którzy dążą do zachowania maksymalnej suwerenności Polski.
* 🟩 Państwowcy z **Polskiej Ligi Samoobrony**, opierający się na sojuszu z Ameryką, próbujący opanować sytuację w kraju.
* 🟨 Separatystyczna **Autonomia Śląska** dążąca do uniezależnienia się Śląska od Polski.

## 🔧 Jak uruchamiać

Do gry niezbędna jest aplikacja Vassal. Jest to darmowy silnik do uruchamiania wirtualnych gier planszowych. Można ją pobrać tutaj: https://vassalengine.org/download.html

* Pobierz i uruchom moduł **Kryzys 2025.vmod**. Jest to podstawowa wersja gry, nie zawiera scenariuszy.
* W folderze ze scenariuszami pobierz odpowiedni plik **Rozszerzenie - xxx.vmdx** i zainstaluj go jako dodatek do modułu **Kryzys 2025** w Vassal.

## 📁 Struktura repozytorium

``` yaml
Kryzys-2025/
│
├── Kryzys 2025.vmod         # Podstawowy moduł Vassal – bez scenariuszy
├── resources/               # Wspólne zasoby: ikonki, dźwięki, itp.
└── scenarios/               # Katalogi scenariuszy:
  └── [nazwa_scenariusza]/
    ├── graphics/            # Mapy, jednostki, okładki, screeny
    ├── scenario/            # Opisy scenariuszy i zmiany zasad
    ├── psd/                 # Źródła graficzne (Photoshop)
    ├── saves/               # Zapisy do gry (np. rozstawienie początkowe)
    ├── *.vmdx               # Rozszerzenie do głównego modułu
    └── *.vmod               # Czasem osobny moduł dla danego scenariusza
```

## 🎲 Scenariusze
### 1️⃣ Incydent Tarnowski
<img src="scenarios/tarnovian_incident/graphics/screenshots/screen.png" width="400" height="280">

Regularne wojsko Sojuszu Europejskiego próbuje spacyfikować buntujące się bojówki Armii Wolności z Tarnowa.

<details>
<summary>➡️ Incydent Tarnowski - więcej informacji</summary>

### Droga w dół
Sytuacja w Polsce pogarszała się już od roku 2004, tuż po przystąpieniu Polski do Unii Europejskiej. Obiecywane dofinansowanie realizowane było nawet wolniej niż przewidywali eurosceptycy, a międzynarodowy kryzys finansowy roku 2008 nie oszczędził Polaków, powodując gwałtowny wzrost bezrobocia i kosztów życia.

Pomiędzy Zachodem a Wschodem
Unia Europejska, opuszczana przez kolejne państwa (Frexit 2010, Brexit 2018), przyjęła w końcu radykalny kurs reform, wzmacniając swoje struktury i obierając kurs na zjednoczenie. Z kolei na wschodzie, Rosja prowadziła swoją własną politykę terytorialną, wchłaniając kolejno Gruzję (2008), Białoruś (2015) i tzw. Noworosję (2018).

Kolejne rządy w Polsce, czując zagrożenie ze wschodu i niestabilność na zachodzie, gwałtownie zwiększały nakłady na zbrojenia. Powszechna stała się militaryzacja życia społecznego, a poprzednie plany rozformowania dywizji szybko zostały zastąpione przez plany tworzenia nowych jednostek, często uzbrojonych w co tylko się dało: w europejski, amerykański, polski czy też zmodernizowany postsowiecki sprzęt.

Swoistą enklawą spokoju pozostawał Śląsk, gdzie popularność zyskiwał ruch tamtejszej, neutralnej wobec obu stron konfliktu, Autonomii.

### Początek kryzysu
Iskrą w beczce prochu była decyzja Niemiec o reformie Unii w pełną Federację. Rządzące Polską siły proeuropejskie, skupione wokół koalicji politycznej o nazwie Sojusz Europejski, parły do podpisania Akcesji Berlińskiej, aby zapewnić Polsce bezpieczeństwo w ramach europejskiego superpaństwa. W odpowiedzi na to opozycyjne partie utworzyły Blok Wolności, powołując się na konstytucyjną suwerenność państwa polskiego. Obie strony zaczęły mobilizować swoje bojówki, a generałowie i dowódcy wojsk deklarowali poparcie poszczególnych bloków politycznych.

Rosnące napięcie osiągnęło swoje apogeum, kiedy o północy 13 grudnia roku 2025, w odpowiedzi na gromadzenie się uzbrojonych grup opozycyjnych, prezydent pochodzący z partii Sojuszu Europejskiego ogłosił stan wojenny. Posłowie Bloku Wolności zaczęli wówczas nocną okupację Sejmu i nawoływali do obalenia rządu. Z kolei wyprowadzone na ulice lojalne wobec rządu wojska starały się siłą blokować protesty.

### Incydent Tarnowski
Podczas jednego z takich protestów, tłum pracowników kluczowych dla przemysłu zbrojeniowego Zakładów Mechanicznych w Tarnowie próbował usunąć stacjonujących tam żołnierzy. Padły strzały i pojawiły się pierwsze ofiary śmiertelne. Naprędce zmobilizowane przez prezydenta miasta oddziały samoobrony wyparły żołnierzy i opanowały cały teren zakładów. Lokalni politycy Bloku przemawiając do rozentuzjazmowanego tłumu, wypowiedzieli posłuszeństwo rządowi w Warszawie, a Tarnowskie Zakłady zapowiedziały zwiększenie produkcji broni i amunicji dla oddziałów buntowników.

Rząd nie zamierzał tolerować takiej sytuacji. Autostradą A4, pomimo drogowych blokad tworzonych przez mieszkańców Małopolski, błyskawicznie zmierzały do Tarnowa lojalne wobec rządu jednostki 2. Brygady Zmechanizowanej Legionów, mające zaprowadzić porządek w zbuntowanym mieście. W odpowiedzi na to Blok Wolności ogłosił powstanie Armii Wolności, a siły samoobrony przemianowane zostały w 16. Tarnowską Samodzielną Brygadę Armii Wolności (TSB-AW). Formowano prowizoryczne jednostki, sprowadzając koleją sprzęt z Lublina i Rzeszowa, które sympatyzowały z Blokiem Wolności.

Rankiem 20 grudnia wrogie siły spotkały się pod Tarnowem. Cały naród z zapartym tchem nasłuchuje informacji o tym, czy to już początek końca perturbacji, czy też dopiero koniec początku...
</details>


### 2️⃣ Marsz przez Magnuszew
<img src="scenarios/march_through_magnushew/graphics/screenshots/screen.png" width="240" height="340">

Armia Wolności i Sojusz Europejski ścigają się wzdłuż Wisły, aby dotrzeć do Warszawy. Na drodze staje im Polska Liga Samoobrony.

<details>
<summary>➡️ Marsz przez Magnuszew - więcej informacji</summary>

### Wojna informacyjna
Po wydarzeniach pod Tarnowem wszystkie kanały komunikacyjne, od telewizji po media społecznościowe, zostały zalane przez burzę informacji, dezinformacji i manipulacji. Każda ze stron konfliktu wykorzystywała media jako broń, celując w serca i umysły Polaków.

Sojusz Europejski, mając dostęp do zaawansowanych technologii Federacji Europejskiej, uruchomił profesjonalne kampanie propagandowe. W telewizji emitowano obrazy przedstawiające rządowe wojska jako jedyną siłę zdolną zaprowadzić porządek. Tymczasem Blok Wolności skutecznie wykorzystywał oddolne kanały komunikacyjne – fora, lokalne grupy na platformach społecznościowych i amatorskie nagrania, które podkreślały brutalność rządu oraz heroizm „Armii Wolności”

Zachodnia Europa, w szczególności kraje Federacji Europejskiej, przyjęły narrację rządu w Warszawie. Jednak za oceanem, w Stanach Zjednoczonych, popularność zdobywały opowieści o walce o „prawdziwą wolność” przedstawiane przez Blok Wolności. Sytuację dodatkowo zaogniały fałszywe wiadomości, które trafiały zarówno do Polaków, jak i na arenę międzynarodową, zwiększając napięcie w dyplomacji.

### Polska Liga Samoobrony – narodziny trzeciej siły
W obliczu eskalacji konfliktu politycznego i wojskowego, a także narastającej obecności rosyjskich wojsk na wschodnich granicach, dowódcy do tej pory jeszcze niezależnych jednostek Wojska Polskiego postanowili działać. Tak powstała Polska Liga Samoobrony (PLS) – niezależne ugrupowanie wojskowe, którego celem było zapewnienie suwerenności Polski wobec zagrożeń zewnętrznych i wewnętrznych.

PLS, złożona głównie z oddziałów Garnizonu Warszawa i 1 Brygady Pancernej, szybko zdobyła poparcie wśród obywateli zmęczonych zarówno rządami Sojuszu Europejskiego, jak i chaosem wywołanym przez Blok Wolności. Liga deklarowała neutralność wobec stron konfliktu politycznego, stawiając na „narodowe odrodzenie”. Jednak jej działania, takie jak przejmowanie magazynów wojskowych i blokowanie marszów obu stron, wskazywały na rosnącą ambicję, by przejąć kontrolę nad sytuacją w kraju.

### Marsz ku Warszawie
Pojawienie się PLS spowodowało zmianę rządowych planów, w związku z czym oddziały 17 Wielkopolskiej Brygady Zmechanizowanej, wcześniej skierowane do wsparcia pacyfikacji Tarnowa, zmieniły kurs i ruszyły w stronę Warszawy. Wsparte przez silne lotnictwo wojska lojalistów miały opanować stolicę i nie dopuścić do przeprowadzenia przewrotu wojskowego.

Jednak to nie był koniec komplikacji. Z południa nadciągała 19 Brygada Zmechanizowana z Lublina, również zmierzająca ku Warszawie. Jej celem było obalenie proeuropejskiego rządu. Sympatycy i bojówkarze Bloku Wolności sformowali również 1 Samodzielny Garwoliński Pułk Strzelców, a z Krakowa nadlatywało wsparcie w postaci wyborowych kompanii powietrznodesantowych.

W odpowiedzi na zbliżające się zagrożenie, Polska Liga Samoobrony postawiła swoje oddziały w stan najwyższej gotowości, i zablokowała drogi prowadzące do stolicy. Na przedpolach Warszawy, w rejonie historycznego przyczółka Magnuszewskiego, doszło do dramatycznego spotkania trzech sił: lojalistycznego Sojuszu Europejskiego, buntowniczej Armii Wolności oraz Polskiej Ligi Samoobrony.

### Druga Bitwa o Przyczółek Warecko-Magnuszewski
Poranek 25 grudnia roku 2025 przyniósł wydarzenia, które nawiązywały do historycznych walk o przyczółek warecko-magnuszewski z czasów II wojny światowej. Z jednej strony rządowe siły 17 Brygady Zmechanizowanej próbowały otworzyć drogę do Warszawy, z drugiej Armia Wolności, w postaci 19. Brygady Zmechanizowanej z Lublina wsparta formacjami z Garwolina i Krakowa, dążyła do zdobycia przewagi w stolicy.

Wydarzenia które miały się wydarzyć pod Magnuszewem unaoczniły, że Polska znalazła się na krawędzi całkowitej anarchii. Zamiast dwóch stron konfliktu – rządu i opozycji – wyłoniła się trzecia siła, która zaczęła gromadzić coraz większe poparcie. Wśród obywateli coraz częściej padało pytanie: czy Polska Liga Samoobrony jest jedyną nadzieją na uratowanie kraju przed wojną domową i zagrożeniami z zewnątrz, czy też stanie się kolejnym aktorem w walce o władzę?

Europa i świat spoglądały na Polskę z rosnącym niepokojem. Konflikt przestał być wewnętrzną sprawą jednego kraju, a stał się areną, na której ścierały się interesy międzynarodowe. Jak zakończy się ta dramatyczna rozgrywka? Czy kraj znajdzie drogę do pokoju, czy też chaos pochłonie całą Europę Środkowo-Wschodnią?
</details>

### 3️⃣ Włocławska Zapora
<img src="scenarios/wloclavian_dam/graphics/screenshots/screenshot.png" width="340" height="240">

Polska Liga Samoobrony planuje przejąć infrastrukturę krytyczną z rąk Sojuszu Europejskiego.

<details>
<summary>➡️ Włocławska Zapora - więcej informacji</summary>

### Infrastruktura prawdziwie krytyczna

W mroźny lutowy poranek 2026 roku Polska Liga Samoobrony (PLS) rozpoczęła operację mającą na celu przejęcie strategicznego kompleksu przemysłowego we Włocławku. Główne cele obejmowały elektrownię wodną na Wiśle, kluczową dla dostaw energii w centralnej Polsce, oraz zakłady produkcyjne w regionie, które mogły zostać wykorzystane do produkcji sprzętu wojskowego.

### Pospieszna obrona

Miasta bronił Włocławski Samodzielny Batalion Gwardii Obywatelskiej – siły porządkowe Sojuszu Europejskiego, złożone z lokalnych rezerwistów i oddziałów przeszkolonych do tłumienia protestów, ale nieprzygotowanych na pełnowymiarowe starcie z PLS. Mimo ograniczonych zasobów batalion przygotował wielowarstwowe linie obrony, wykorzystując naturalne przeszkody, takie jak rzeka Wisła, oraz improwizowane barykady na głównych arteriach komunikacyjnych.

### Atak i Odsiecz
1 Brygada Zmechanizowana Legionów wierna PLS zaatakowała z dwóch kierunków – od północnego i południowego wschodu. Kolumny pojazdów opancerzonych i ciężarówek wypełnionych piechotą szturmową posuwały się w stronę mostu drogowego oraz kompleksu elektrowni.

Gdy sytuacja wydawała się beznadziejna, z południa nadeszła wiadomość o zbliżających się posiłkach – elementach 17 Wielkopolskiej Brygady Zmechanizowanej, lojalnych wobec rządu w Warszawie. Ich szybki marsz w stronę Włocławka zmusił PLS do przyspieszenia operacji przejęcia infrastruktury krytycznej dla dalszego prowadzenia wojny.

Operacja we Włocławku unaoczniła, że konflikt w Polsce staje się coraz bardziej brutalny i zacięty. Tereny, które wcześniej były jedynie areną politycznych sporów, zamieniały się w pola bitwy, a nadzieje na pokojowe rozwiązanie oddalały się z każdym kolejnym starciem.


</details>

### 4️⃣ Atak na Kielce
<img src="scenarios/attack_on_kielce/graphics/splash.png" width="400" height="240">

<details>
<summary>➡️ Atak na Kielce - więcej informacji</summary>

### Odwrót Sojuszu
2 Brygada Legionów, naciskana przez siły Armii Wolności, rozpoczęła odwrót na północ, kierując się z Tarnowa w stronę Kielc. Dowództwo Sojuszu uznało, że utrzymanie dotychczasowych pozycji jest niemożliwe, a kluczowe było pokonanie wojsk Armii Wolności w Kielcach.

Kolumna wozów przemieszczała się szybko, gotowa do przegrupowania i podjęcia nowej ofensywy.

### Desperacka obrona
Jednak Kielce, zajęte przez oddziały buntowników, nie były na straconej pozycji. W stronę miasta zmierzała 21 Brygada Strzelców Podhalańskich, która, korzystając z drogi S17, błyskawicznie dotarła w rejon walk.

Podhalańczycy planowali zatrzymać przeciwnika przed wejściem do miasta i uderzyć świeżymi siłami, zmuszając lojalistów do desperackiej obrony.
</details>


### 5️⃣ Hasło "Kraków"
<img src="scenarios/codename_krakow/graphics/screenshots/screen.png" width="340" height="240">


<details><summary>➡️ Hasło "Kraków" - więcej informacji</summary>

### Zmierzch polityki, świt wojny
Na północ od Krakowa, na terenie Wyżyny Małopolskiej, rozgrywały się kolejne dramatyczne wydarzenia, które miały zaważyć na losach kraju. Armia Wolności, skonsolidowana po zwycięstwie pod Tarnowem, rozpoczęła kontrofensywę w kierunku Kielc. Ich celem było odcięcie lojalistycznych sił rządowych od wsparcia z Warszawy i zabezpieczenie południowego frontu. Buntownicze kolumny pojazdów bojowych i żołnierzy sunęły na północ przez wiosenne roztopy.

### Polityczne fiasko
W tym samym czasie w Warszawie rozmowy między przedstawicielami rządu, Polskiej Ligi Samoobrony i delegatami Armii Wolności zakończyły się fiaskiem. Wszystkie strony oskarżały się nawzajem o zdradę, brak dobrej woli i współpracę z siłami zewnętrznymi. Polska Liga Samoobrony, początkowo dążąca do neutralności, coraz wyraźniej pokazywała swoje ambicje, prezentując siebie jako jedyną siłę zdolną uratować kraj przed upadkiem. Jednak ich postulaty o przejęciu pełnej władzy tymczasowej spotkały się z ostrym sprzeciwem zarówno Sojuszu Europejskiego, jak i Bloku Wolności.
Coraz większe obszary kraju ogarniały bunty. Na Mazurach pojawiły się grupy separatystyczne, które, powołując się na historyczne krzywdy, żądały autonomii. Na Pomorzu, gdzie kontrolę utrzymywały siły rządowe, wybuchły masowe protesty stłumione brutalnie przez żandarmerię wojskową. W centralnej Polsce powstawały kolejne oddziały Armii Wolności, kierowane przez byłych wojskowych.

### Widmo interwencji
Na wschodnich granicach Polski Rosja zwiększyła swoją obecność wojskową, oficjalnie deklarując, że działania mają na celu ochronę ludności rosyjskojęzycznej w regionie. W praktyce jednak Kreml bacznie obserwował rozwój wydarzeń, gotowy wkroczyć w odpowiednim momencie. Tymczasem Federacja Europejska wysłała do Warszawy ultimatum, żądając od rządu zdławienia buntu i stabilizacji sytuacji w kraju.
Stany Zjednoczone, wciąż rozdarte wewnętrznymi problemami, nie podjęły żadnych działań, ograniczając się do symbolicznego wsparcia Armii Wolności w postaci dostaw sprzętu przez prywatne firmy.

### Ofensywa na Wyżynie Małopolskiej
Na wyżynnych terenach Małopolski Armia Wolności posuwała się szybko. Lojalistyczne jednostki, wyczerpane walkami pod Tarnowem, nie były w stanie skutecznie stawiać oporu. Kluczowymi punktami stały się Chmielnik, Jędrzejów i Szczekociny, których strategiczne położenie mogło zapewnić kontrolę nad drogami do Kielc i Warszawy. Władze tych miast, rozdarte między lojalnością wobec rządu a rosnącym poparciem dla Armii Wolności, ogłosiły neutralność. To jednak nie powstrzymało walk.
W teren walk została skierowana elitarna 10 Brygada Kawalerii Pancernej. Czekając na wsparcie z reorganizujących się oddziałów 2 Brygady Legionów i 17 Wielkopolskiej Brygady Zmechanizowanej, siły Sojuszu czekały na przeciwnika. Oddziały Strzelców Podhalańskich z Rzeszowa i Kłodzka zostały wyznaczone do przeprowadzenia ataku, przy wsparciu Brygady Powietrznodesantowej z Krakowa. Posiłki, w postaci brygad Lubelskich i Tarnowskich zmierzały już na pole bitwy.

### Przyszłość w chaosie
Wraz z nadejściem nowego roku Polska znajdowała się na krawędzi. Kraj, rozdarty między trzema głównymi siłami i niezliczonymi lokalnymi ruchami, zmierzał ku niepewnej przyszłości. Czy którakolwiek ze stron będzie w stanie przechylić szalę zwycięstwa na swoją korzyść? A może naród, zmęczony krwią i zniszczeniem, odnajdzie sposób na odbudowę, zanim chaos pochłonie całą Europę Środkowo-Wschodnią?.



</details>