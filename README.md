Caveatron

Caveatron to unikalne, kompaktowe, ręczne urządzenie elektroniczne do mapowania jaskiń lub innych środowisk podziemnych. Funkcjonuje jako narzędzie do pomiarów jaskiniowych, rejestrując konwencjonalne pomiary odległości, azymutu i nachylenia, ale potrafi również znacznie więcej dzięki zintegrowanemu systemowi LIDAR, który pozwala na przechwycenie pełnego skanu 3D wnętrza jaskini. Znacznie przyspiesza proces kartowania jaskiń, rejestrując pomiary między stanowiskami w zaledwie kilka sekund i wykonując skanowanie 3D całego ciągu między stanowiskami w mniej niż minutę. Użytkownik może w pełni wchodzić w interakcję z urządzeniem i przeglądać dane za pomocą wbudowanego ekranu dotykowego. Port USB zapewnia dostęp do zapisanych danych z poziomu komputera PC lub Mac, a także służy do ładowania zintegrowanego zestawu akumulatorów o długiej żywotności. Plik pomiarowy stanowisk jest kompatybilny z oprogramowaniem mapującym Walls Cave Mapping Software, a plik skanu LIDAR może zostać szybko przetworzony do standardowej chmury punktów za pomocą specjalnie napisanego oprogramowania. Caveatron został zaprojektowany tak, aby był łatwy do przenoszenia, lekki i tani, a także odporny na wodę i brud oraz wystarczająco trwały, aby przetrwać regularne użytkowanie w jaskini.
Kluczowe cechy

    Pomiary i skanowanie 3D jaskiń

    Zasięg LIDAR 12 m lub 30 m przy prędkości do 32 000 pkt/s

    Dalmierz laserowy do 40 m

    Zintegrowana jednostka pomiarowa inercyjna (IMU) zawierająca cyfrowy kompas, inklinometr i żyroskop

    Estymacja pozycji podczas skanowania

    Szybki procesor Teensy

    Transfer plików do komputera przez USB

    Odporna na wodę/kurz obudowa z druku 3D

    Dedykowana płytka drukowana (PCB)

Co nowego (2024-05-03)

Rev C jest obecną i preferowaną wersją oraz jedyną w aktywnej fazie rozwoju. Ta wersja wykorzystuje szybszy procesor Teensy 4.1 i posiada kilka ulepszeń, w tym możliwość korzystania z 30-metrowego RPLIDAR S2 lub 12-metrowego RPLIDAR A1M8, nowy moduł magnetometru dla znacznie poprawionej dokładności i niezawodności kompasu, pojemnościowy ekran dotykowy, szybsze ładowanie baterii oraz mniejszy rozmiar.
Nowe rewizje płytki Rev C (C.3 i C.4) zostały opublikowane wraz ze zaktualizowaną listą materiałów (BOM). Dokumentacja montażu Rev C nie została jeszcze zaktualizowana dla nowych płytek drukowanych, ale nie różni się ona znacząco.

Rev B jest oparta na starszym procesorze Teensy 3.6, jest obecnie przestarzała, a niektóre komponenty mogą być już niedostępne.

Informacje o oryginalnej wersji opartej na Arduino Due (Rev A) są wciąż dostępne i można je teraz znaleźć w katalogu legacy_material_rev-A.
W wersji Rev A wiele osób miało trudności z kompilacją kodu w zakresie sprawienia, by wszystkie biblioteki ze sobą współpracowały i dobrania odpowiednich ustawień. W przypadku Teensy stosunkowo łatwo jest załadować wstępnie skompilowany plik HEX, unikając wszelkich problemów z oprogramowaniem. Na ten moment będę dostarczać tylko plik HEX zamiast całego kodu, aby uprościć sprawę, ponieważ kod stał się jeszcze bardziej złożony w nowej wersji, a ja nie używam już Arduino IDE. Jeśli chcesz popracować nad kodem, skontaktuj się ze mną bezpośrednio.
Podsumowanie zawartości katalogu Caveatron dla każdej rewizji
Dokumentacja

    Lista materiałów (Bill of Materials)

    Instrukcje montażu

    Instrukcje montażu wiązek przewodów

    Opis części drukowanych 3D

PCB

    Schemat ideowy

    Pliki KiCad

    Pliki gerber PCB

Mechanika

    Pliki STL dla wszystkich części drukowanych 3D

    Pliki STEP dla wszystkich części drukowanych 3D

Te elementy można znaleźć w innych folderach:
Kalibracja

Informacje i kalkulatory można znaleźć pod adresem https://github.com/Caveatron/Calibration
Oprogramowanie

Oprogramowanie można znaleźć pod adresem https://github.com/Caveatron/Software
