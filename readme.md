# Pod pokličkou SW inženýra (Arduino Day 2019)

Podklady pro přednášku z [Arduino Day 2019](http://robodoupe.cz/2019/arduino-day/) v Praze.

> Psaní programu je jen malý kousek skládačky. Opravdový *SW inženýr™* toho umí mnohem víc. V této přednášce se koukneme na některé věci z kuchyně SW inženýra, které by se mohly hodit i na takové to domácí programování…

## Osnova

* Co je SW proces
* Verzování zdrojového kódu
* Architektura a design aplikace
* Testování (Unit Test)
* CI/CD Pipeline

-----

## Co je SW proces

![SDLC](doc/img/sdlc.jpg)


------

## Verzování (nejen) zdrojového kódu

### Proč?

* historie
* cooperace
* single point of true
* branches
* zaloha

### github (i pro sdileni projektu)

* nejen verzovaci system ale i sw lifetime mgmt.
* ukazka projektu

### Tipy

* vsechny zavislosti musi byt verzovane nebo explicitne uvedene (napr. verze knihovny v platformio.ini)
* Primarne se verzuje zdrojovy kod (tooling je na to navrzeny) ale obecne vse co je potreba k sestaveni artefaktu
* Knihovny a ext. zavislosti neverzovat pokud jsou dostupne pres uloziste (repozitory) ktere verzovani umoznuje (pio lib library), v opacnem pripade radeji verzovat kopii nez *googlem*



