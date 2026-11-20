# Portfolio – Danyil Davydyuk

Strony internetowe dla firm: landing page, strony wizytówki i strony firmowe w czystym HTML, CSS i JavaScript.

## Projekty

| Projekt | Rodzaj strony | Folder |
|---|---|---|
| Wpadaj | Landing page aplikacji mobilnej | `wpadaj/` |
| Liczydło | Landing page usług dla gastronomii (ciemny motyw) | `liczydlo/` |
| Zielony Kąt | Strona oferty: rośliny i donice na zamówienie | `zielony-kat/` |
| Kierunek Cargo | Strona firmy spedycyjnej | `kierunek-cargo/` |
| Poziomica | Strona firmy remontowej z kalkulatorem kosztów | `poziomica/` |

Wszystkie projekty to prace koncepcyjne. Marki, dane kontaktowe, liczby i treści są fikcyjne, a formularze działają w trybie demonstracyjnym i niczego nie wysyłają.

## Jak to jest zbudowane

- Każda strona to jeden plik `index.html` z własnym CSS i JavaScript, bez frameworków i bez kroku budowania.
- Fonty są hostowane lokalnie w folderze `fonts/` każdej strony (pliki WOFF2, podzbiory latin i latin-ext).
- Grafiki to SVG i CSS. Miniatury w `assets/thumbs/` to zrzuty ekranu stron.
- Strony są responsywne: sprawdzone na szerokościach 375, 768 i 1440 px.

## Uruchomienie lokalnie

Otwórz `index.html` w przeglądarce albo uruchom prosty serwer:

```
python3 -m http.server 8000
```

## Fonty

Bricolage Grotesque, Figtree, Instrument Serif, IBM Plex Sans, IBM Plex Mono, Marcellus, Karla, Barlow, Barlow Condensed, Red Hat Display, Red Hat Text i Schibsted Grotesk. Wszystkie na licencji SIL Open Font License 1.1, pobrane z pakietów Fontsource.
