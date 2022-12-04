---
Title: Kmom05
Description: My report for kmom05.
---

Laddningstid och användbarhet
=======================

Rapporten handlar om att analysera tre olika webbplatser laddningstid och användbarhet.

Urval
-----------------------

Webbplatserna som jag har valt att undersöka är [Marques Brownlee](https://mkbhd.com/), [Carl Bildt](https://carlbildt.wordpress.com/) och [Sara Dietschy](https://www.saradietschy.com/). Valt samma webbplatser från tidigare kmom för få harmoniserande och jämförbar resultatutvärding mot tidigare repport.

Metod
-----------------------

De verktyg som jag har använt i min analys är [PageSpeed insights](https://pagespeed.web.dev/) och Edge Devtools. PageSpeed insight är ett verktyg för prestandaoptimering och Edge Devtools för att debuga sidor.

Resultat
-----------------------

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSx6cUSMzQVe7KHOcNVQBJGjVuhc3AGU_78w1hTrsBtuzOSYB1Fns9a20IB34ihiW5DvGGmzz3RpfqA/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="900" height="300"></iframe>

[Marques Brownlee (Skärmdump)](../assets/img/mkbhd.PNG)

I webbshoppen laddar bilderna för mobila enheten långsamt, för högupplösta bilder för en telefon. 


[Carl Bildt (Skärmdump)](../assets/img/carlbildt.PNG)

Länkar och andra klickbara element bör vara tillräckligt stora och ha tillräckligt mycket utrymme runt för att inte besökaren ska råka klicka på fel. 

[Sara Dietschy (Skärmdump)](../assets/img/saradietschy.PNG)

På sidan finns det oanvänd JavaScript och använding av bild filformat som tar längre tid att ladda än WebP och AVIF.

Analys
-----------------------

Det är tydligt att man kan påverka laddningstiden på en mängd olika sätt. Bland annat undvik ompekning, optimera bilder och radera oanvänd kod. Det sidorn har gemensamt är att prestandan i mobiltelefon inte håller samma höga standard som för datorn, fel storlek på bilderna är sidornas akilleshäl. Minska kvalitén på bilden, ändra storlek eller filformat är tre enkla åtgärder.

Resultat laddningstid:
1. Marques Brownlee
2. Carl Bildt
3. Sara Dietschy 

En hemsida som laddar på under 1-2 sekunder uppfattar jag som snabb sida. Allt över 3 sekunder, när det tar tid att se bilderna uppfattar jag som långsam. Alla tre sidor som jag har valt klarar gränsvärdet för ett snabb sida och är generellt sett bra optimerade.

Referenser
-----------------------

[Google PageSpeed Insight Ruels](https://developers.google.com/speed/docs/insights/rules)

Övrigt
-----------------------
Marcus Lundstedt