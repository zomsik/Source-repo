### Repozytoria na githubie:

https://github.com/zomsik/source-repo

https://github.com/zomsik/config-repo

W ramach zadania zostały wykonane wszystkie polecenie ze skryptu. Utworzony obraz zad2gitops został z pliku Dockerfile znajdującego się w folderze stepcd. CronJob natomiast z pliku stepcd/cron.yaml.


Poniżej widać automateczny update strony po wykonaniu CronJoba. Pierwsze zdjęcie jest przed commitem i pushem, a drugie po zmianie wersji na 1.4 i pushu na repozytorium github.


![Przed commitem i pushem](images/przed.png)


![Po commicie i pushu](images/po.png)

Poniżej przedstawiono również przybliżenie urywku konsoli po wykonaniu wszystkich zadań. Pracowałem na systemie windows i tutaj nie mogłem wejść przez adres http://zad2.lab, a przez wykonanie polecenie
```
minikube service zadanie2-service
```
, które otwierało w przeglądarce wyżej pokazaną stronę.

![Konsola](images/konsola.png)