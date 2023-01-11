---
Title: 02 Load
Description: This is our index page.
Template: report
---

Laddningstiden för hemsidor
=======================

<!-- Skriv en eller två rader om vad uppgiften handlar om. -->

Uppgiften handlar om att mäta laddningstiden. Det vill säga hur lång tid det tar att ladda in all text, bilder, videos från hemsidan.

Urval
-----------------------

<!-- Berätta vilka webbplatser du valt att undersöka och varför eller hur du gick tillväga när du gjorde ditt urval. -->

Jag har valt Giphy, WikiHow och Aftonbladet. Varför jag har valt dem, är hur mycket information (bilder/gifs/artiklar) som visas upp. Jag vill undersöka om dem här hemsidor har gjort ett bra jobb att minska på laddningstiden.

Metod
-----------------------

<!-- Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg. -->

Jag använder utav ett verktyg som heter *PageSpeed*. *PageSpeed* är en hemsida som mäter hemsidans laddningstid. Detta hjälper att avgöra hur snabb/effektiv hemsidan har gjorts.

Därefter använder jag mig utav *Google Spreadsheets* (*Google Kalkylark*), för då samla in data och organisera data.

Sedan efter använder jag mig utav *devtools* från Google Chrome webbläsaren. *Devtools* hjälper då att mäta laddningstiden, samt hur mycket som har laddas in via webbläsaren.


Resultat
-----------------------

<!-- Dokumentera dina resultat från din studie. Berätta vad du kom fram till, vilka resultat du hittade och observerade. -->

![Giphy](%base_url%/image/giphy.png?w=600)<br><br><br><br>
![aftonbladet](%base_url%/image/aftonbladet.png?w=600)<br><br><br><br>
![wikiHow](%base_url%/image/wikiHow.png?w=600)<br><br><br><br>

<a href="https://docs.google.com/spreadsheets/d/1a9gR8rwH7Ms_RVXA4M1bbLaq5f1RI3kuhlubmBT1FAs/edit?usp=sharing" target="_blank">Länk till Excel</a>

<div class="excel">
    <iframe title="Design Load Times" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7sC6yMj4V8djsCIhMeM7HFR9GfQ4bsmU-BS6IwT6_ul4j1_K1rjykhHKKKxFFJyWI1UOBGui2w0VZ/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

Analys
-----------------------

<!-- Diskutera och analysera de resultaten du fann. -->

<br>

<h3>Rangordning</h3>
<ol type="1">
  <li>wikiHow - Poäng Avg: <b>88</b></li>
  <li>Giphy - Poäng Avg: <b>55</b></li>
  <li>Aftonbladet - Poäng Avg: <b>39,5</b></li>
</ol>

<br>

Resultat visar att *wikiHow* laddar snabbast på både datorer och mobiler.*Giphy* och *Aftonbladet* laddar däremot mycket långsammare, med nästan **2,5** gånger så lång laddningstid jämfört med *wikiHow*.

Det är väntat att nyhetssidor tar längre tid att ladda, eftersom de ofta innehåller många artiklar och mycket information. Överlag kan man säga att ju mer innehåll en sida har, desto mer data kommer den att behöva hämta och därmed påverka laddningstiden.

De skulle kunna minimera all information som hämtas in. Till exempel istället för hämta alla artiklar och deras data, kan man bara hämta alla titlar. Sedan om användaren trycker in sig på artikeln, kan hela artikelns data laddas in. Detta kallas för *Lazy loader*. Ladda in data, när det behöves.

En sak som *Giphy* skulle kunna göra att använda olika metoder för komprimera gifs:en till ett lägre format. Samt använda olika cache tekniker för att då spara gifs:en på webbläsaren. *Giphy* skulle kunna använda metoder för då ta bort många färger på gifs:en, samt ta bort frame som är en kopia av en annan frame.

Enligt MIT's forskning (MIT, In the blink of an eye) kan människans öga se upp till 80 ms. Detta innebär att människor inte kan processa för snabb information. Därför anses en snabb laddningstid för en hemsida vara mellan 10-50 ms, medan 100-1000 ms anses vara en långsam laddningstid.

Referenser
-----------------------

<!-- Ange de eventuella referenser du använder dig av, om några. -->

[Länk till MIT, In the blink of an eye](https://news.mit.edu/2014/in-the-blink-of-an-eye-0116)<br>
[Länk till Giphy](https://giphy.com/)<br>
[Länk till wikiHow](https://www.wikihow.com/Main-Page)<br>
[Länk till Aftonbladet](https://www.aftonbladet.se/)


Övrigt
-----------------------

Robin Johannesson