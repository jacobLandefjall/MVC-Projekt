# Projekt: Hållbar Utveckling

## Scrutinizer Badges

[![Scrutinizer][![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/jacobLandefjall/mvc/badges/quality-score.png?b=main)](https://scrutinizer-ci.com/g/jacobLandefjall/mvc/?branch=main)
[![Coverage](https://scrutinizer-ci.com/g/jacobLandefjall/mvc/badges/coverage.png?b=main)](https://scrutinizer-ci.com/g/jacobLandefjall/mvc/?branch=main)
[![Build](https://scrutinizer-ci.com/g/jacobLandefjall/mvc/badges/build.png?b=main)](https://scrutinizer-ci.com/g/jacobLandefjall/mvc/build-status/main)


Projektet "Hållbar Utveckling" är en webbplats som marknadsför konceptet.
Webbplasen innehåller tre områden från de 17 globala målen, "Hållbar energi för alla", "God hälsa och välbefinnande" och "Hållbar konsumtion och produktion". Dessa områden har samlad fakta, mätvärden och visualiserande data genom diagram och tabeller.

Webbplatsen innehåller flera webbsidor, för en förbättrad struktur. Dessa är:
-Report: Alla redovisningstexter.
-About: Förklaring av projektet.
-Diagram: Alla diagram över områderna.
-JSON Api: Samtligga tabeller i JSON-format.
-Proj: Projektet som innehåller introduktion, fakta, och tabeller över de tre områderna.

Projektet innehåller mätvärden för att få en förbättrad och underhållbar kod. Dessa organiseras i dabasen, analyseras och blir sedan presenterade på webbsidan.

## Innehåll
- Symfony PHP-ramverket som används för att bygga webbapplikationerna.
- PHP hanterar webbsidans applikationer, som routing, logik och databasinteraktioner.
- HTML.Twig-filer skapar vyer för webbsidan.
- Composer pakethanteraren som används för att hantera vissa beroenden i projektet.
- CSS-filer för styling och typsnitt av webbplatsen.
- JavaScript-filer som använder Chart.js (skapar diagram).
- JavaScript-objekt som innehåller data som visas i diagrammen.

## Repo
Report är har skapats för att visa hur man kan strukturera och testa en PHP-baserad webbapplikation med hjälp av PHPUnit. Det innehåller exempel på både en webbapplikation och en terminalapplikation som kan förbättras och testas.

## Installation
-Klona repot till din dator: git clone https://github.com/jacobLandefjall/mvc.git
-Installera Composer med: composer install (Installera beroenden med Composer:)
-Unittester med PHPunit: vendor/bin/phpunit --version
-Starta webbapplikationen: php -S localhost:8888

## Användning av webbsidan
Nu när allt är installerat och webbplastsen är igång kan sidan navigeras genom olika sidor och interagera med diagrammen för att se olika värden och detaljerade mätningar inom de olika områden.

