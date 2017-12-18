# Travis

**Ciągła integracja** to praktyka tworzenia oprogramowania, polegająca na częstej integracji kodu, zazwyczaj pochodzącego od róznych programistów. 
Oprócz integracji należy zapewnienić także poprawność kompilacji kodu źródłowego.
Dlatego do naszego kodu powinniśmy mieć napisane odpowiednie testy, które sprawdzą jego poprawność. 

Korzyści z automatycznego uruchamiania testów:
- nie trzeba pamiętać o uruchamianiu testów,
- w wypadku wykrycia błędu automatycznie wszyscy zainteresowaniu mogą dostać stosowne powiadomienie,
- dostępna jest historia przebiegu testów kolejnych wersji kodu,
- zwiększa poziom zaufania do pakietu.

[**Travis CI**](https://travis-ci.org/) - narzędzie wspomagające ciągłą integrację projektów znajdujących się na GitHubie.

[Core Concepts for Beginners](https://docs.travis-ci.com/user/for-beginners)

[Getting started](https://docs.travis-ci.com/user/getting-started/)

[Building na R Project](https://docs.travis-ci.com/user/languages/r/)

[Checking after every commit with Travis by Hadley Wickham](http://r-pkgs.had.co.nz/check.html#travis)

## Konfiguracja

Travisa konfiguruje się poprzez plik .travis.yml umieszczony w repozytorium projektu. 
Przykładowa zawartość [pliku konfiguracyjnego](https://github.com/mi2-warsaw/MI2DataLab_Seminarium/blob/master/2017_12_19_travis/.travis.yml):

```
language: R
sudo: false
cache: packages

notifications:
  email: false
```

Inne przydatne opcje:

`r_github_packages` - instalacja pakietów z GitHuba,

`r_binary_packages` - instalowanie prekompilowanych pakietów. Ta opcja pozwala zredukować czas budowy Travisa. 
Listę dostępnych pakietów można znaleźć na [stronie z pakietami dla systemu Ubuntu](https://packages.ubuntu.com/).



# AppVeyor

[AppVeyor](https://www.appveyor.com/) -  ciągła integracja - budowanie i testowanie projektów hostowanych na GitHubie na wirtualnej maszynie z Microsoft Windows.

[Jak używać AppVeyor w projektach R.](https://github.com/krlmlr/r-appveyor)
