# Słówka z klawiatury

Aplikacja do pisania bezwzrokowego na własnych tekstach i listach słówek (angielski – polski, hiszpański – polski).
Działa w przeglądarce, bez serwera i bez instalacji. Twoje teksty i wyniki zapisują się tylko w Twojej przeglądarce.

## Pliki

- `index.html` – cała aplikacja
- `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png` – opcjonalne, pozwalają zainstalować aplikację jak program i używać jej offline

## Wersja online na GitHub Pages

1. Na github.com utwórz nowe repozytorium (np. `slowka`).
2. Kliknij **Add file → Upload files**, przeciągnij wszystkie pliki z tego folderu (bez folderu nadrzędnego, `index.html` ma być w głównym katalogu) i zatwierdź (**Commit changes**).
3. Wejdź w **Settings → Pages**. W polu **Branch** wybierz `main` i katalog `/ (root)`, kliknij **Save**.
4. Po minucie lub dwóch aplikacja będzie pod adresem `https://TWOJ-LOGIN.github.io/slowka/`.
5. W Chrome lub Edge możesz kliknąć ikonę instalacji w pasku adresu i dodać ją jak aplikację.

## Wersja lokalna (bez internetu)

Pobierz folder i otwórz `index.html` dwuklikiem. Wszystko działa, ale czcionki z Google Fonts nie załadują się bez internetu (aplikacja użyje czcionek systemowych), a zapis działa osobno dla każdego sposobu otwierania (plik lokalny i strona GitHub mają osobne dane).

## Przenoszenie tekstów między komputerami

Dane są w przeglądarce na danym komputerze. Na liście tekstów użyj **Eksportuj teksty** (zapisze plik `slowka-kopia.json`) i na innym komputerze **Importuj teksty**.

## Uwagi

- Głos korzysta z syntezy mowy w przeglądarce. Jakość i dostępność hiszpańskiego zależą od systemu.
- Na GitHub Pages strona jest publiczna, ale Twoje teksty nigdy nie opuszczają przeglądarki.
