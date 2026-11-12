# 🎧 MusiXX - Twój Osobisty Odtwarzacz Muzyki

MusiXX to nowoczesny, Darmowy, lekki i napisany w Pythonie odtwarzacz muzyczny z eleganckim interfejsem graficznym. Aplikacja pozwala na bezproblemowe wyszukiwanie i odtwarzanie muzyki, zarządzanie własnymi playlistami oraz posiada inteligentny system Autoplay.

<img width="3839" height="2108" alt="image" src="https://github.com/user-attachments/assets/17e58d68-ed7e-4de4-82fb-8c5e5547b008" />


## ✨ Główne funkcje

* **Tryb Offline (Pobieranie):** Pobieraj całe playlisty na dysk i słuchaj ulubionych utworów bez dostępu do internetu. Aplikacja automatycznie zarządza lokalnymi plikami dźwiękowymi i zapisanymi okładkami.
* **Płynne przejścia (Crossfade):** Muzyka bez przerw! Gdy następny utwór jest załadowany w pamięci lub pobrany offline, aplikacja miękko przenika dźwięk między piosenkami (do wyboru 3 lub 5 sekund w ustawieniach).
* **Inteligentny Autoplay:** Algorytm, który uczy się Twojego gustu. Automatycznie dobiera kolejne utwory w podobnym klimacie, omijając parodie, vlogi i blokując ciągłe zapętlanie tego samego artysty.
* **Wbudowana wyszukiwarka:** Szukaj muzyki po tytule, wykonawcy lub po prostu wklej link (obsługuje formaty YouTube).
* **Zarządzanie playlistami:** Dodawaj utwory do kolejki lub zapisuj je w utworzonych przez siebie, stałych playlistach. Ustawiaj własne grafiki jako okładki dla swoich muzycznych kolekcji!
* **Personalizacja ustawień i Skróty klawiszowe:** Wybieraj preferowaną jakość dźwięku oraz przypisuj własne skróty klawiszowe do płynnego sterowania odtwarzaczem.
* **Integracja z Discord (RPC):** Pochwal się znajomym na Discordzie, czego aktualnie słuchasz (system w pełni wspiera również utwory odtwarzane z dysku w trybie offline!).
<img width="442" height="155" alt="image" src="https://github.com/user-attachments/assets/1063f0a5-48ba-4f05-a9e9-242acc195c7f" />

* **Auto-Updater:** Aplikacja sama sprawdza dostępność nowych aktualizacji na GitHubie i pozwala na ich bezinwazyjne pobranie jednym kliknięciem.
* **Integracja z Windows Media Player:** Możliwość natywnego sterowania muzyką na poziomie systemu Windows (obsługa klawiszy multimedialnych na klawiaturze).

## 🛠️ Wymagania
Windows 10/11

Pobranie z Releases: [Kliknij tutaj aby pobrać](https://github.com/xlunix221/MusiXX/releases/download/latest/MusiXX.exe)

Pobranie z HuggingFace: [Kliknij tutaj aby pobrać](https://huggingface.co/datasets/XluniX/MusiXX/resolve/main/MusiXX.exe)

*(Jeśli masz restrykcyjnego antywirusa, może on blokować uruchomienie odtwarzacza, ponieważ aplikacja używa skryptów .bat i pobiera aktualizacje prosto z GitHuba. Wystarczy dodać program do wyjątków).*

### 📝 Notatki
Aplikacja jest w 100% portable! Pobierz paczkę, wrzuć na pulpit, odpal i słuchaj muzyki bez przerwy, ciesząc się całkowitym brakiem reklam!

## ⚖️ Licencja i Odpowiedzialność

**Copyright © 2026 xlunix221. Wszelkie prawa zastrzeżone.**

### 1. Zastrzeżenie prawne (Disclaimer & AS IS)
Oprogramowanie jest dostarczane w stanie **„TAK JAK JEST”** (ang. *„AS IS”*), bez jakichkolwiek gwarancji, wyraźnych lub dorozumianych, w tym m.in. gwarancji przydatności handlowej, przydatności do określonego celu czy braku zakłóceń w działaniu. Projekt powstał w celach czysto edukacyjnych oraz hobbystycznych i jest przeznaczony **wyłącznie do prywatnego użytku osobistego**.

Autor nie ponosi żadnej odpowiedzialności za jakiekolwiek bezpośrednie lub pośrednie szkody, straty, awarie sprzętu ani konsekwencje prawne wynikające z instalacji, użytkowania bądź niewłaściwego użycia tego narzędzia, w tym za ewentualne naruszenia regulaminów serwisów trzecich (*Terms of Service*). Użytkownik korzysta z oprogramowania wyłącznie na własne ryzyko i odpowiedzialność.

### 2. Architektura i prywatność danych
* **Brak telemetrii marketingowej:** Aplikacja nie zawiera żadnych modułów szpiegujących, reklamowych ani skryptów analitycznych śledzących użytkownika.
* **Lokalne przetwarzanie multimediów:** Aplikacja działa jako lokalny klient i nie hostuje ani nie przechowuje na serwerach autora żadnych plików muzycznych czy chronionych prawem autorskim treści. Wszystkie strumienie audio, teksty piosenek i okładki są pobierane w czasie rzeczywistym bezpośrednio na komputerze użytkownika z publicznie dostępnych źródeł zewnętrznych.
* **Synchronizacja w chmurze:** Funkcje społecznościowe (konta użytkowników, kopie zapasowe playlist, lista znajomych oraz wspólne sesje MusiXX Jam) wykorzystują zabezpieczoną bazę danych (Supabase) oraz dedykowany serwer czasu rzeczywistego wyłącznie w celu realizacji tych funkcji na życzenie użytkownika.

### 3. Zewnętrzne znaki towarowe i usługi
Wszelkie znaki towarowe, nazwy produktów, logotypy, tytuły utworów, nazwy wykonawców oraz materiały multimedialne należą do ich odpowiednich właścicieli prawnych (m.in. YouTube, Google, Spotify, Deezer, Discord). Projekt **MusiXX** nie jest w żaden sposób oficjalnie powiązany, sponsorowany ani zatwierdzony przez żadną z wymienionych marek.

### 4. Prawa autorskie i warunki użytkowania (Closed Source)
Aplikacja jest udostępniana bezpłatnie jako **Freeware o zamkniętym kodzie źródłowym (Closed Source / Proprietary)**:
* Użytkownik otrzymuje ograniczoną, osobistą, niewyłączną i odwołalną licencję na pobieranie i uruchamianie aplikacji wyłącznie w celach niekomercyjnych.
* Kod źródłowy aplikacji nie jest udostępniany publicznie i stanowi wyłączną własność intelektualną autora.
* **Zabrania się:** dekompilacji, inżynierii wstecznej (*reverse engineering*), modyfikacji, redystrybucji, sprzedaży, sublicencjonowania lub jakiegokolwiek komercyjnego wykorzystywania programu bez uprzedniej, wyraźnej zgody autora wyrażonej na piśmie.
