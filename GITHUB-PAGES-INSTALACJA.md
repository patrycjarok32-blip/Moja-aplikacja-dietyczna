# Dieta Fit AI — instalacja na GitHub Pages

Ta paczka jest przygotowana jako statyczna aplikacja PWA pod GitHub Pages.

## Pliki

Do GitHuba wrzuć zawartość tej paczki po rozpakowaniu, czyli pliki takie jak:

- index.html
- 404.html
- manifest.webmanifest
- sw.js
- registerSW.js
- workbox-*.js
- .nojekyll
- folder assets
- ikony PWA

Nie wrzucaj `node_modules`.
Nie wrzucaj całego projektu źródłowego jako strony.
Nie wrzucaj folderu nadrzędnego zamiast zawartości builda.

## Najprostsza publikacja przez przeglądarkę

1. Wejdź na https://github.com.
2. Zaloguj się albo załóż darmowe konto.
3. Kliknij przycisk `+` w prawym górnym rogu.
4. Wybierz `New repository`.
5. Nazwij repozytorium np. `dieta-fit-ai`.
6. Ustaw repozytorium jako `Public`.
7. Kliknij `Create repository`.
8. Rozpakuj plik `dieta-fit-ai-github-pages.zip` na komputerze albo telefonie.
9. W repozytorium kliknij `Add file`.
10. Wybierz `Upload files`.
11. Przeciągnij wszystkie pliki i foldery z rozpakowanej paczki do okna GitHuba.
12. Kliknij `Commit changes`.
13. Wejdź w `Settings`.
14. Po lewej wybierz `Pages`.
15. W sekcji `Build and deployment` ustaw:
    - `Source`: `Deploy from a branch`
    - `Branch`: `main`
    - folder: `/root`
16. Kliknij `Save`.
17. Poczekaj, aż GitHub opublikuje stronę.
18. Link będzie wyglądał podobnie do:
    `https://twoja-nazwa.github.io/dieta-fit-ai/`

## Instalacja na Androidzie

1. Otwórz link GitHub Pages w Chrome na Androidzie.
2. Kliknij menu `⋮`.
3. Wybierz `Dodaj do ekranu głównego` albo `Zainstaluj aplikację`.
4. Potwierdź instalację.
5. Uruchamiaj `Dieta Fit AI` z ikony na ekranie telefonu.

## Ważne

- Aplikacja działa lokalnie w przeglądarce.
- Dane są przechowywane lokalnie na telefonie w pamięci przeglądarki.
- Aplikacja nie wymaga backendu.
- PWA wymaga HTTPS; GitHub Pages daje adres HTTPS.
- Gdy zaktualizujesz pliki w repozytorium, aplikacja może wymagać odświeżenia albo zamknięcia i ponownego otwarcia na telefonie.
