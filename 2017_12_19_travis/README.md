# Travis

**Ci¹g³a integracja** to praktyka tworzenia oprogramowania, polegaj¹ca na czêstej integracji kodu, zazwyczaj pochodz¹cego od róznych programistów. 
Oprócz integracji nale¿y zapewnieniæ tak¿e poprawnoœæ kompilacji kodu Ÿród³owego.
Dlatego do naszego kodu powinniœmy mieæ napisane odpowiednie testy, które sprawdz¹ jego poprawnoœæ. 

Korzyœci z automatycznego uruchamiania testów:
- nie trzeba pamiêtaæ o uruchamianiu testów,
- w wypadku wykrycia b³êdu automatycznie wszyscy zainteresowaniu mog¹ dostaæ stosowne powiadomienie,
- dostêpna jest historia przebiegu testów kolejnych wersji kodu,
- zwiêksza poziom zaufania do pakietu.

[**Travis CI**](https://travis-ci.org/) - narzêdzie wspomagaj¹ce ci¹g³¹ integracjê projektów znajduj¹cych siê na GitHubie.

[Getting started](https://docs.travis-ci.com/user/getting-started/)

[Building na R Project](https://docs.travis-ci.com/user/languages/r/)

[Building a Python Project](https://docs.travis-ci.com/user/languages/python/)

[Checking after every commit with Travis by Hadley Wickham](http://r-pkgs.had.co.nz/check.html#travis)

## Konfiguracja

Travisa konfiguruje siê poprzez plik .travis.yml umieszczony w repozytorium projektu. 
Przyk³adowa zawartoœæ [pliku konfiguracyjnego](https://github.com/mi2-warsaw/MI2DataLab_Seminarium/blob/master/2017_12_19_travis/.travis.yml):

```
language: R
sudo: false
cache: packages

notifications:
  email: false
```

Inne przydatne opcje:

`r_github_packages` - instalacja pakietów z GitHuba

`r_binary_packages` - instalowanie prekompilowanych pakietów. Ta opcja pozwala zredukowaæ czas budowy Travisa. 
Listê dostêpnych pakietów mo¿na znaleŸæ na [stronie z pakietami dla systemu Ubuntu](https://packages.ubuntu.com/)



# AppVeyor

[AppVeyor](https://www.appveyor.com/) -  ci¹g³a integracja - budowanie i testowanie projektów hostowanych na GitHubie na wirtualnej maszynie z Microsoft Windows.

[Jak u¿ywaæ AppVeyor w projektach R.](https://github.com/krlmlr/r-appveyor)