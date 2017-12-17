# Travis - continuous integration

*Ci¹g³a* integracja to praktyka tworzenia oprogramowania, polegaj¹ca na czêstej integracji kodu, zazwyczaj pochodz¹cego od róznych programistów. 

[*Travis CI*](https://travis-ci.org/) - narzêdzie wspomagaj¹ce ci¹g³¹ integracjê projektów znajduj¹cych siê na GitHubie.

[Travis CI, przyjemne Continuous Integration dla projektów na GitHubie](http://www.simplecoding.pl/travis-ci/)

[Getting started](https://docs.travis-ci.com/user/getting-started/)

[Building na R project](https://docs.travis-ci.com/user/languages/r/)


## Konfiguracja

Travisa konfiguruje siê poprzez plik .travis.yml umieszczony w repozytorium projektu. 
Przyk³adowa zawartoœæ pliku konfiguracyjnego:

```
language: R
sudo: false
cache: packages

notifications:
  email: false
```



