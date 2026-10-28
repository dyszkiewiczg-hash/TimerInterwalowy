TIMER INTERWAŁOWY — projekt Android

To jest projekt źródłowy aplikacji Android opakowującej stronę HTML w WebView.
W tym środowisku nie ma Android SDK ani Gradle, więc nie mogę tu skompilować gotowego pliku APK.
Projekt można zbudować w Android Studio lub AndroidIDE na Androidzie.

NAJPROSTSZA DROGA PRZEZ GITHUB ACTIONS:
1. Rozpakuj ZIP na komputerze.
2. Utwórz repozytorium na GitHubie i wgraj zawartość folderu TimerInterwalowy.
3. Otwórz kartę Actions w repozytorium.
4. Wybierz workflow „Build APK” i kliknij „Run workflow”.
5. Po zakończeniu otwórz wykonany workflow i pobierz artefakt „TimerInterwalowy-debug-apk”.
6. Rozpakuj pobrany artefakt — znajdziesz w nim app-debug.apk.
7. Prześlij APK na telefon i otwórz plik. Android może poprosić o zezwolenie na instalowanie aplikacji z tej przeglądarki/pliku.

UWAGA:
- APK z tego projektu jest testową kompilacją debug, nie podpisanym wydaniem sklepowym.
- Aplikacja działa lokalnie; nie potrzebuje połączenia internetowego do wyświetlania interfejsu.
- Zapisane ustawienia przeglądarkowe zależą od pamięci WebView.
- Jeśli zmienisz plik app/src/main/assets/index.html, kolejna kompilacja użyje nowej wersji.
