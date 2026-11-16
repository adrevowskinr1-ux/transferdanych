# BanSwap Transfer

Strona do przesyłania plików i filmów z komputera na telefon w przeglądarce, bez przechowywania plików w chmurze.

## Publikacja na GitHub Pages

1. Utwórz **publiczne repozytorium** GitHub, np. `transfer`.
2. Prześlij do głównego folderu repozytorium plik **`index.html`**.
3. Otwórz **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
4. Wybierz **main**, folder **/(root)**, kliknij **Save**.
5. Strona będzie dostępna pod `https://TWOJ_LOGIN.github.io/transfer/` (o ile repozytorium nazywa się `transfer`).

## Transfer

1. Otwórz stronę na komputerze i kliknij **Wyślij pliki**.
2. Telefonem zeskanuj QR albo otwórz tę samą stronę i wpisz kod.
3. Na komputerze kliknij **Zezwól**, wybierz pliki i kliknij **Wyślij**.
4. Na telefonie poczekaj na koniec przesyłania i kliknij **Pobierz** lub **Udostępnij**.
5. Nie zamykaj kart podczas przesyłania. Transfer bezpośredni działa najlepiej, gdy urządzenia są podłączone do tej samej sieci Wi-Fi.

## Ważne

- Statyczna strona GitHub Pages nie jest serwerem do składowania plików. Transfer realizuje WebRTC, a PeerJS Cloud służy wyłącznie do zestawienia połączenia.
- Połączenie WebRTC jest szyfrowane. Wymagana jest zgoda na komputerze; kod udostępniaj tylko zaufanej osobie.
- Publiczny serwer sygnalizacyjny i ograniczenia sieciowe NAT/firewalla mogą uniemożliwić połączenie. Nie ma gwarancji, że zadziała w każdej sieci.
- Odbiorca składa plik w przeglądarce. Bardzo duże filmy mogą przekroczyć dostępną pamięć urządzenia. Do plików wielogigabajtowych lepszy będzie lokalny serwer HTTP lub rozwiązanie z zapisem strumieniowym.
- W iOS, w zależności od typu pliku, pobranie może trafić do aplikacji Pliki. Dla zdjęć i filmów opcja „Udostępnij” może ułatwić zapis w aplikacji Zdjęcia.
