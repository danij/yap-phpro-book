81663d9e1f7ca1141acd88920521ddd021542d00

prima linie din "HTTP e stateless.txt" implica ca toate cererile HTTP ar avea
nevoie de cookie(/session), trebuie reformulat cu un "daca vrem sa ..." pe
undeva pe acolo.

a inteles rapid si a si corectat

STATUS: passed

----

fc0ca8dbf832214c53c517e76bea1c0608516b24

la 1. fi cat mai exact, descrie EXACT locul unde apare metoda http. la 4-8
spune si contextul semantic, si semantica, gen " ... are semantica de ... in
contextul semantic ... "

STATUS: pending

eb1d309ded9b0dbed633fcd0f7b1f3f1eae5063a

STATUS: still pending

hint: defineste "request http"

(tutors: ideea din spate e ca "http reeust" e mare, constituita din mai multe
lucruri, trebuie sa vina cu "request line" ca si context semantic)


la 7:

poti pune codul html intr-un fisier .php si tot ca html se vede, deci nu
extensia este determinanta

fa urmatorul experiment: pune intr-un fisier test.php din DocumentRoot asta:
<h1>scris mare</h1>
fa cererea GET /test.php cu telnet
si apoi cu un browser, dar presupun ca stii deja care va fi rezultatul
apoi, al doilea stadiul al experimentului, modifica test.php asa:
<?php header('Content-Type: text/plain');?><h1>scris mare</h1>
fa cererea cu un browser, si apoi cu telnet
temă: explică ce se întâmplă şi de ce, în termeni tehnici

(tutors: s-a descurcat bine, fara ezitari majore, it looks good)

la 8: cauta documentatia HTML 4.01 si vezi ca ai acolo un index cu tagurile
corespunzatoare fiecarui atribut, ca <a> nu e singurul tag cu href

(tutors: are tendinta de a se exprima incalcit, trebuie sa invete sa se exprime
punctual)
