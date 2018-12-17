---
---
Rapport kmom05 - laddningstid
=========================

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/rapport/05_laddningstid.md`.

Uppgiften handlar om att utvärdera tre olika webbplatsers laddningstid och därmed användbarhet.

Urval
-------------------------
Jag valde att titta på tre olika webbplatser inom den offentliga hälso-och sjukvårdssektorn.<br>
De valda webbplatserna är:<br>

1. www.regionkronoberg.se
[FIGURE src="image/rgk1.jpg?w=800" class="right" caption="Bild Region Kronobergs startsida"]<br>

Enligt PageSpeed Insights finns förbättringspotentialen på denna webbplatsen framför allt på mobil-sidan där resurser som blockar renderingen ökar på laddningstiderna rejält. Samma fenomen finns även på desk-top-sidan men dock inte lika markant. Det sammantagna resultatet för webbplatsen gällande hastighet är enligt PageSpeed Insights snabb på desk-top-sidan och långsam på mobil-sidan.
Tittar man på resultatet från Devtools är laddningtiden liksom antalet resurser och den totala storleken för denna webbplats i mitten på urvalet.

2. www.rjl.se
[FIGURE src="image/rjl.jpg?w=800" class="right" caption="Bild Region Jönköpings startsida"]<br>

Enligt PageSpeed Insights finns förbättringspotential även här framför allt på mobilsidan där bilder drar ner betyget i form av längre laddningstider. Samma fenomen finns även på desk-top-sidan men inte heller här lika markant.
Det sammantagna resultatet för webbplatsen gällande hastighet enligt PageSpeed Insights är snabb på desk-top-sidan och genomsnittlig på mobil-sidan.
I Devtools hamnar webbplatsen på de högsta värdena i detta urvalet när det gäller både laddningstid, antal resurser samt total storlek.

3. www.ltblekinge.se.
[FIGURE src="image/ltblekinge.jpg?w=800" class="right" caption="Bild Landstinget Blekinges startsida"]<br>

Även på denna webbplatsen finns enligt PageSpeed Insights förbättringspotential framför allt på mobilsidan där mestadels resurser som blockerar renderingen samt utebliven textkomprimering ökar på laddningstiderna. Även här samma tendens på desk-top-sidan men inte lika markant.
Det sammantagna resultatet för webbplatsen gällande hastighet enligt PageSpeed Insights är snabb på desk-top-sidan och genomsnittlig på mobil-sidan.
I Devtools hamnar denna webbplatsen bäst när det gäller laddningstider. Den har också minst antal resurser och är minst i storlek.

Metod
-------------------------
Jag använde mig, enligt instruktion i uppgiften, av PageSpeed Insights (f d Google Pagespeed) samt devtools. I PageSpeed Insights noterades hastighetsresultatet baserat på labbdata samt top tre föreslagna optimeringar och dess möjligheter och uppskatttade tidsbesparingar. I devtools mättes laddningstid, antal resurser som laddas samt sidans totala storlek. I båda verktygen mättes värdena tre gånger per sida och omladdningar med shift-ctrl-r gjordes mellan mätningarna. Slutligen beräknades medelvärdet på samtliga mätningar. Samtliga mätvärden finns noterade i Google kalkylark, se länk nedan.

[Laddningstider](links\laddningstid-kmom05.xlsx)  

Sammanfattning
-------------------------
Sammanfattningsvis dras webbplatsernas betyg ner av främst två anledningar - bilder och resurser som blockerar renderingen. Samtliga webbplatser får enligt PageSpeed Insights hastighetsresultatet snabb på desk-top-sidan, två genomsnittlig på mobil-sidan och en långsam och då mycket långsam på mobilsidan vilket för mig är otroligt förvånande i dessa "mobila tider" och borde absolut vara något som man vill förbättra. De vanligaste förbättringsåtgärderna/förslagen är modernare bildformat och att resurser som blockerar renderingen tas bort.


Utifrån resultatet i PageSpeed Insights utses Landstinget Blekinge till vinnare dock ganska tätt följt av Region Jönköping. Region Kronobergs låga betyg på PageSpeed Insights när det gäller mobilsidan drar ner det sammanlagda resultatet rejält och därför hamnar denna webbplatsen i en "egen division". I Devtools kan man dock kanske se en förklaring till att Landstinget Blekinge vinner. Detta då både antalet resurser och den totala storleken på webbplatsen är avsevärt mindre än framför allt Region Jönköpings men även Region Kronobergs. I Devtools kan man också se att Region Jönköping faktiskt är den stora förloraren när det gäller laddningsstider, ett resultat som inte stämmer överens med betyget i PageSpeed Insights. Man kan också se att Region Jönköping totalt sett har har avsevärt högre värden i allt än både Landstinget Blekinge och Region Kronoberg, vilket i sin tur borde ge Region Kronoberg mycket bättre resultat på framför allt mobilsidan i PageSpeed Insights. Slutligen kan man väl säga att det man mäter får man också svar på och det påverkar ju så klart också resultaten. När jag t ex har testat Region Kronobergs webbsida på mobiltelefonen är det för mig helt obegripligt hur betyget för mobil endast är 17. Detta får mig snarare att tvivla på vad som verkligen mäts med PageSpeed Insights...

Jag tycker att en laddningstid om mindre en 1 sekund kan klassas som en snabb webbplats och det uppfyller ju inte någon av webbplatserna i mitt urval, åtminstone inte om man ska/kan lita på verktygen.

Detta är ett grupparbete av me, myself and I.
