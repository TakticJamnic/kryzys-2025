# Kryzys-2025

Kryzys 2025 to seria wirtualnych gier planszowych zrealizowanych w silniku Vassal w systemie World War 3 (WW3) wydawnictwa Taktyka i Strategia (Gry w tym systemie można kupić np. tu https://taktykaistrategia.pl/kategoria-produktu/nasze-gry/?filter_system=ww3&query_type_system=or)

Kryzys 2025 opowiada o hipotetycznej wojnie domowej w Polsce - trzy strony konfliktu

* Postępowi lojaliści z Sojuszu Europejskiego,
* Konserwatywni buntownicy z Armii Wolności, 
* Zachowawczy państwowcy z Polskiej Ligi Samoobrony

## Jak uruchamiać

* Należy otworzyć moduł "WW3 - Kryzys 2025.vmod". Jest to podstawowa wersja gry nie zawierająca żadnego scenariusza.
* Następnie należy pobrać plik *.vmdx z odpowiedniego scenariusza i zainstalować jako dodatek do modułu.

## Scenariusze

---

1️⃣ **Incydent Tarnowski**

<img src="scenarios/tarnovian_incident/graphics/splash.png" width="400" height="240">

<img src="scenarios/tarnovian_incident/graphics/screenshots/screen.png" width="400" height="280">

Siły Sojuszu Europejskiego próbują zgasić zarzewie buntu w Tarnowie

---

2️⃣ **Marsz przez Magnuszew**

<img src="scenarios/march_through_magnushew/graphics/splash.png" width="400" height="240">

<img src="scenarios/march_through_magnushew/graphics/screenshots/screen.png" width="240" height="340">

Sojusz Europejski i Armia Wolności ścigają się do Warszawy aby obalić albo obronić rząd, ale na drodze staje im Polska Liga Samoobrony.

---

3️⃣ **Włocławska Zapora**

  <img src="scenarios/wloclavian_dam/graphics/splash.png" width="400" height="240">

<img src="scenarios/wloclavian_dam/graphics/screenshots/screenshot.png" width="340" height="240">


Polska Liga Samoobrony planuje przejąć infrastrukturę krytyczną z rąk Sojuszu Europejskiego. 


---
4️⃣ **Atak na Kielce**

<img src="scenarios/attack_on_kielce/graphics/splash.png" width="400" height="240">

Garnizon Kielc broni się przed Sojuszem Europejskim w oczekiwaniu na odsiecz ze strony Armii Wolności.

---

  <img src="scenarios/codename_krakow/graphics/splash.png" width="400" height="240">

<img src="scenarios/codename_krakow/graphics/screenshots/screen.png" width="340" height="240">

* 5️⃣ Hasło "Kraków" - Sojusz Europejski uderza na stolicę buntu - Kraków. Naprzeciw stoją regularne siły Armii Wolności.

## Struktura repozytorium

* WW3 - Kryzys 2025.vmod - plik zawierający moduł Vassal
* scenarios/ - katalogi ze scenariuszami, każdy scenariusz zawiera:
  * graphics/ - grafiki związane ze scenariuszem, mapy, jednostki, okładki, screenshoty
  * scenario/ - scenariusz/kolejne scenariusze do gry z opisami i zmianami w zasadach
  * psd/ - pliki źródłowe w formacie photoshop
  * saves/ - pliki z zapisami do gry, zwykle jest to rozstawienie początkowe zgodnie ze scenariuszem
  * *.vmdx - plik z dodatkiem do głównego modułu
  * *.vmod - niektóre scenariusze mają też swój samodzielny moduł, nie dodatek
* resources/ - różne pliki, ikonki, dźwięki wspólne dla wszystkich (albo części) gier

