# pkgdown - generowanie statycznych dokumentacji html w R

*pkgdown* umożliwia proste oraz szybkie tworzenie stron html pakietów. Więcej o pkgdown można dowiedzieć się [tutaj](http://hadley.github.io/pkgdown/)

## Przykładowe strony pakietów wygenerowane przy pomocy *pkgdown*:
- Standardowy szablon: [archivist](http://pbiecek.github.io/archivist/),
- Szablon grupy MI2: [auditor](https://github.com/mi2-warsaw/auditor).

## Jak wygenerować taką stronę?

Należy zainstalować pkgdown z repozytorium na GitHubie. Następnie, w katalogu z wybranym pakietem użyć funkcji `build_site()`.

```
devtools::install_github("hadley/pkgdown")
pkgdown::build_site()
```

Instrukcja pozwalająca wygenerować stronę z szablonem MI2 DataLabu znajduje się w repozytorium pakietu [MI2template](https://github.com/mi2-warsaw/MI2template).
