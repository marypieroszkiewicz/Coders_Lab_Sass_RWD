# Sass - Instalacja i uruchomienie
> Do kompilacji możesz używasz narzędzia gulp, albo kompilować za pomocą Ruby.
> Skorzystaj z przygotowanego już pliku gulpfile.js oraz skopiuj folder node_modules

## Zadanie rozwiązywane z wykładowcą

### Stwórz gulpfile.js (~ 7min - 10min)

Stwórz plik gulpfile.js. Stwórz w nim zadanie, za pomocą którego będzie można kompilować pliki Sass
do css. Stwórz odpowiedni watcher, który będzie obserwował nie tylko zmiany w jednym pliku, ale na całym katalogu.


###  Styl wyjściowy  (~ 2min - 10min)

Zmień styl wyjściowy kodu na expanded.


### Tworzenie projektu (~ 5min - 10min)
* Dodaj w pliku **index.html** nagłówek **h1** z tekstem, np.  „Hello, Sassy!” i otwórz go w przeglądarce.
* Utwórz katalog o nazwie **scss**, a w nim plik &ndash; **main.scss**. W pliku określ kolor nagłówka oraz kolor tła całej strony. Najlepiej tak, aby nagłówek był czytelny.
* W pliku **index.html** wczytaj wygenerowany arkusz styli (z odpowiednim rozszerzeniem).
* Skompiluj plik Sassa w znany Ci sposób (np. za pomocą Gulpa).
* Sprawdź, czy wygenerował się odpowiedni katalog z plikiem **css**.
* Odśwież stronę w przeglądarce.
* Zmień kolor nagłówka w pliku **scss** i ponownie odśwież stronę.

-------------------------------------------------------------------------------

## Zadania do samodzielnego wykonania

### Zadanie 1. Nadpisywanie zmian (~ 2min - 5min)
Bezpośrednio w wygenerowanym pliku **css** zmień kolor nagłówka i wprowadź dodatkową właściwość, np. margines. Sprawdź zmiany w przeglądarce. Przejdź do pliku **scss** i wprowadź dowolną zmianę inną od tej wprowadzonej w pliku **css**, np. padding. Zapisz plik i sprawdź rezultat zarówno w wynikowym pliku **css**, jak i w przeglądarce. Co się zmieniło?

### Zadanie 2. Watcher (~ 2min - 5min)
W pliku gulp ustaw odpowienio watcher, tak, aby moniotorwał zmiany.
