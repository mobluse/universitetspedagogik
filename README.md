# Universitetspedagogik

Jag lånade "Lär dig koda : grunderna i programmering - steg för steg", men hade inte tid att läsa den, men jag testade Logo-kapitlet i den.
Jag har läst:  
http://www.adlibris.com/se/bok/pa-aventyr-med-raspberry-pi-9789186917326  
Jag har nästan läst hela:  
http://www.adlibris.com/se/bok/hjalp-ditt-barn-med-programmering-en-illustrerad-guide-som-lar-ut-programmering-steg-for-steg-9789176172056  

Jag har även läst Mikael Tylmads tidigare bok:  
"Spelprogrammering.nu med HTML5 och JavaScript".

Man vet inte hur det kommer gå i framtiden om Python eller JavaScript (Node.js) vinner. JavaScript är snabbare så Node vinner kanske 
med tiden. Dock tror jag att alla elever och därmed lärare bör lära sig Scratch först och det ingår i de tre första böckerna.
Man bör ju förstå det eleverna förstår. Jag kan tänka mig att vissa grundskoleelever inte kommer att bli produktiva i Python,
JavaScript eller något annat programspråk där man måste skriva alla tecken, såvida det inte finns en bra redigerare. För Microbit
finns en utvecklingsmiljö där man kan omvandla blockprogram till JavaScript. Arduino använder C++, vilket är ganska likt JavaScript.

Förutom att Scratch är lätt att lära och bli produktiv i så är fördelar med Scratch att det kan köra flera processer samtidigt, att man
kan redigera programmen under körning, att programspråket är på svenska eller annat valfritt språk, samt att det finns ett stort
Scratch-community för ungdomar (dock mest på engelska). Man kan skriva moduler till Scratch med JavaScript, se http://scratchx.org/.

## Koppla BBC micro:bit till Scratch 2 via endast radiovågor (Bluetooth LE)

Video med BBC micro:bit trådlöst kopplad till Scratch 2: https://vimeo.com/213841640 (1 min)

Video om hur man väljer Microbit i S2Bot 4 Scratch: https://youtu.be/W4B8IywVtRQ (2 min). S2Bot 4 Scratch är ett gratis tillägg till 
Chrome (och Chromium). Jag har fått det att funka nu på Raspberry Pi 2 med Bluetooth-dongeln BLED112 & Scratch 2 i Chromium, men ej
i Chrome i Windows 10. Andra har samma problem:
http://www.picaxeforum.co.uk/showthread.php?29947-S2Bot-app-connecting-(but-not-working)-with-Micro-bit-on-Win10&p=310775 . 
En hypotes om vad problemet beror på kan vara att Chrome i Windows10 är nyare än Chromium med Flash i Raspberry Pi och att S2Bot 
ej är uppdaterad. Deras hypotes om att det skulle bero på andra BT-prylar stämmer nog inte, ty jag har stängt av alla andra BT-prylar 
inklusive Windows10-datorns interna och det fungerar ju i Raspberry Pi på samma plats.

Jag har gjort ett demoprogram. Man flyger en ballong genom att luta och byter bakgrund fram och tillbaka med 
knapparna B respektive A: https://pic.twitter.com/wL9g54K3sR  
Man använder alltså Microbit som en fjärrkontroll som kan visa (rullande) text och spela ljud (om man har kopplat in en högtalare).

Större bild: https://u.cubeupload.com/EUHJcZ.png

Man måste använda en Bluetooth-dongel med ett visst chipset vilket emulerar en serieport: BLED112. Jag köpte denna från 
RS: http://se.rs-online.com/web/p/bluetooth-adapters/8077742/ . För att få gratis frakt köpte jag även en Raspberry Pi 3 och en 
Raspberry Pi Sense Hat. De är billigare där än på andra ställen. Man kan nog bara beställa på RS som företag. Leveransen tog bara 
några dagar.

Dock lär man inte behöva BLED112 om man kör Chromebook. BLED112 har redan inbyggda drivrutiner i Windows och Raspbian (och verkar 
kunna fungera i Mac OS X). Dock uppfattas BLED112 inte som en BT-dongel utan som en serieport.

De borde utvidga S2Bot så att den även kan hantera pinnar och displayen mer detaljerat. Nu kan man bara skriva rullande text med 
ASCII-tecken -- t.ex. ÅÄÖ fungerar ej, och man kan använda högtalare (om man ansluter en). Det hade ju även varit en fördel om den 
kunde använda Raspberry Pi 3 och Zero:s interna Bluetooth, och även andra datorers interna BT4. Man kan förresten köpa 
Raspberry Pi Zero W på Electrokit i Malmö -- tidigare kunde man bara köpa den från UK. https://www.electrokit.com/


Det är någon som tycker att Scratch har ett marknadsföringsproblem i och med att det ser ut att vara gjort för yngre barn, men ändå 
kan vara avancerat:  
https://stevekrouse.com/scratch-has-a-marketing-problem-f84626bd18ef

Jag upptäckte denna artikel här och den diskuteras också här:  
https://scratch.mit.edu/discuss/topic/251639/


https://mobluse.github.io/gr/teknik/


Man kan slippa nätverksproblem genom att köra MIT AppInventor 2 helt i webbläsaren Chrome genom att installera en Android-emulator i
Chrome och AI Companion i den. Jag har lyckats installera detta på offentliga datorer.
https://www.youtube.com/playlist?list=PLUx1NFKWh2OFkAeVaskaZttQeaeM7cp8E

Ett annat alternativ är att ha en 3g-->WiFi-router (t.ex, dela ut WiFi via en mobil) i klassrummet som inte har spärrat nätverk.


En 13-åring från Sverige har fått sitt spel på svenska på Scratch-MIT:s förstasida (d.v.s. featured projects), trots att det är 
en amerikansk sajt på engelska. MIT lär vara världens ledande universitet. Så det är en stor ära att få sitt projekt på dess 
förstasida.  
https://scratch.mit.edu/projects/118793893/


Greenfoot


Om nu elever börjar lära sig programmera när de är 8 år så vill de kanske göra mer avancerade saker i slutet av högstadiet samtidigt 
som vissa elever fortfarande lär sig grunderna i Scratch. För de mer avancerade eleverna kan detta system vara intressant, ty man 
använder fortfarande Scratch, men det är ett textbaserat programspråk.

Detta FORTH-programmeringsspråk har uppdaterats mycket sedan dess tillkomst i slutet av december 2016 och har nu sju gillanden 
på Scratch från viktiga medlemmar:  
https://scratch.mit.edu/projects/137676871/

Artikel om programspråket FORTH och detta system på engelska:  
https://scratch.mit.edu/discuss/topic/233532/

In English:  
I have made some new videos about this FORTH programming language and a FORTH playlist:

1. (old) https://youtu.be/VZfUFnioLko     1 min <– Dec 26 2016  
2. (new) https://youtu.be/FwEgRetggFg     1 min <– Feb 4 2017  
3. (new) https://youtu.be/tPk1nNgq6NE     1 min  
4. (new) https://youtu.be/tZOYPTv77pI     1 min  
5. (new) https://youtu.be/nr0c87lrC64     1 min  

https://www.youtube.com/playlist?list=PLD8D8534DD63B28EA

In Swedish/På svenska:  
En fördel är att man kan använda en hel del Scratch-funktioner från FORTH och att man kan hitta en massa FORTH-kod på nätet som 
man kan testa. Man kan som Scratch-programmerare lära sig hur en kompilator kan fungera, och som gammal FORTH-programmerare kan 
man delta i Scratch och använda sin gamla kod.

Tyvärr har Scratch 2 begränsningar vad gäller tangentbordet, så man får använda pil upp som shift, pil ner som vagnretur (enter), 
pil vänster som radera (backspace) och pil höger som punkt (.), samt pil upp+pil höger som komma (,), och dessutom 
pil upp+mellanslag (space) som avbrott (break). Övriga specialtecken fås med pil upp följt av B-Z eller 0-9 (pröva dig fram!). 
Pil upp+A startar ett inmatningsfönster där man kan klistra in kod. Programmet fungerar även troligen på surfplattor om man 
kör Phosphorus-versionen:  
http://phosphorus.github.io/#137676871  
Då kan man klicka på det blå tangentbordet för att öppna en inmatningsruta och då startar troligen skärmtangentbordet.


Ja, ty det är MicroBit:en man programmerar och den kan f.n. programmeras i textprogramspråken Python (MicroPython), 
JavaScript (2 olika) och TouchDevelop på webbplatsen. Vilket programspråk som exemplen som följer med roboten har vet jag inte, 
men man kan nog lätt översätta exemplen. MicroPython kan även användas offline. Man kan även programmera i C++, men det är 
krångligare, ty man använder då miljön för proffs. Det finns även FORTH till micro:bit.

Jag tror att man bara behöver få robotar till en klass, ty det som tar lång tid är att programmera. 

https://hos.se/produkt/microbit-rover/2808?categoryId=262  
Detta är visserligen en byggsats, men läraren kan ju bygga den. Nästan alla robotar man köper måste monteras.

Den du har köpt, mBot, duger säkert också. Jag har använt Sparki-robotar på en 6-9-skola. De var dyrare och hade fler 
finesser än mBot och fick beställas via Amazon i USA.  
https://groups.google.com/d/msg/coderdojo-lund/l3KbUyRWfo0/0aJpDeI0-EAJ  
Sparki är liksom mBot Arduino-kompatibel och kan förutom ett Block-språk även programmeras i C++ med Arduino IDE. mBot går också 
att programmera i C++.


En fördel med MicroBit är att de kan använda samma språk (JavaScript) som de lärt sig på http://koda.nu/ -- det kan man 
inte med Arduino, även om JavaScript liknar C++ ytligt sett. Det är svårt att säga vilket programspråk som är mest 
gångbart i framtiden. JavaScript är ju ett ganska säkert kort ty det finns i alla webbläsare, men måste installeras för 
fristående bruk (Node.js). Python är inbyggt i MacOS, Linux och i Windows 10 (om man installerar BashOnWindows ä.k. WSL). 
Python verkar vara enklare än Node.js -- det finns i alla fall barnböcker på svenska om Python, men ännu ej om Node.js. 
Det finns en barnbok (från 10 år) på engelska om JavaScript (Javas JavaScript) i kombination med 
Minecraft: https://www.adlibris.com/se/bok/a-beginners-guide-to-writing-minecraft-plugins-in-javascript-9780133930146  


Detta är en ganska animerad kurs i datavetenskap med ca 10 min långa avsnitt. Den skall täcka allt utom programmering. Det har 
varit tre avsnitt hittills. Kursen hålls av en grundskollärare, Carrie Anne Philbin. Samma som skrivit 
boken http://www.bokus.com/bok/9789186917326/pa-aventyr-med-raspberry-pi/ .  
https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo


Kojo på http://www.lth.se/programmera/
 
 
http://www.rosettacode.org/wiki/Hello_world/Text
 
 
Jag har testat micro:bit ikväll för första gången. Jag köpte 2 st. på Electrokit för att kunna testa radiokommunikationen. 
Först provade jag JavaScript, men avläsning av knapparna fungerade ej pålitligt med hjälp av händelser. Programmet fungerade 
bra i emulatorn, men inte så bra i verkligheten. Därefter gick jag över til MicroPython. Där verkar det inte finnas en 
emulator, men man kan köra kommandon interaktivt. Jag använde pdf-filen "micro:bit MicroPython in 60 minutes" 
http://www.rareschool.com/workshops/microbitmicropython.pdf (gratis) för att komma igång. Boken använder Mu som redigerare. 
Jag har testat den mesta hårdvaran: display, knappar, accelerometer, termometer, kompass, radio. Kompassen verkade vara lite 
okänslig. 
Radion fungerade bara om man använder versionen av Mu på hemsidan, och inte den som finns lätt installerbar i 
Raspberry Pi -- detta skall dock fixas om några veckor. Radioapparaterna fungerar bra, men använder ett eget protokoll 
och inte Bluetooth (BT)  när man kör MicroPython (MP), ty MP+BT kräver mer RAM än de 16 KB som micro:bit har (samma som 
ABC 80 i original). Mu på hemsidan finns för Windows, Mac OS X och Linux x86. Jag beställde även ett startpaket för 
micro:bit med elektronik, men det var tillfälligt slut.
 
 
Det finns något som heter Web Bluetooth som skall fungera med MicroBit i Chrome för Mac, Linux, Chrome OS, Android:
http://www.espruino.com/MicroBit  
https://www.kitronik.co.uk/5604-line-following-buggy-for-the-bbc-microbit.html


Jag tyckte på sista frågan:
Jag tycker det bästa för grundskolan vore om man använde blockbaserade språk som Scratch ( http://scratch.mit.edu/ ), 
Blockly (t.ex. http://studio.code.org/ ), Snap! ( http://snap.berkeley.edu/ ) och 
MIT App Inventor 2 ( http://ai2.appinventor.mit.edu/?locale=sv ), ty då programmerar man på svenska eller andra naturliga språk 
och slipper en massa strul med syntaxfel och specialtecken. I och med att man lätt kan byta språk så överbryggar man språkklyftor. 
Helst skulle systemen kunna köra offline eller med egen server på skolan -- detta gäller för idag för Scratch och 
MIT App Inventor 2 och går troligen att lösa för Snap!. Det allra bästa vore ett blockbaserat språk som kan översättas automatiskt 
till t.ex. JavaScript eller Python, och då tillåta avancerade elever att använda dessa som alternativ till det blockbaserade. 
Dock är det dåligt att tvinga alla elever att lära sig JavaScript eller Python eftersom bl.a. dyslektiker troligen inte skulle komma 
speciellt långt. Att tvinga någon att använda (en delmängd av) sitt modersmål för programmering är inte lika kontroversiellt.

Vilket programspråk menar du att eleverna på t.ex. högstadiet skall använda? Vilken utvecklingsmiljö?

Pyonkee, Scratch 1.4 för iPad:
https://itunes.apple.com/us/app/pyonkee/id905012686?mt=8

Nu finns MIT App Inventor 2 för utveckling av Android-appar på svenska: http://ai2.appinventor.mit.edu/?locale=sv 
Diskutera översättningen på https://groups.google.com/forum/#!topic/coderdojo-malmo/IQVLJOA_TcI

Jag hittade en app och en pdf som verkar indikera att det går: 
https://play.google.com/store/apps/details?id=bp.usbbridge.appinv&hl=sv
http://www.mytopschool.net/mysti2d/activites/polynesie2/tuto/arduino/Communication_Appinventor_Arduino.pdf


Denna tecknade serie innehåller en del om datorns historia: http://www.bokus.com/bok/9789188376084/datorn-i-bild-och-bubblor/
Boken finns även på många bibliotek.


https://www.skolverket.se/skolutveckling/larande/nt/grundskoleutbildning/teknik/arskurs-4-6/avfallshantering-och-programmering-i-scratch-1.237735


Få syn på digitaliseringen på grundskolenivå
https://www.skolverket.se/om-skolverket/publikationer/visa-enskild-publikation?_xurl_=http%3A%2F%2Fwww5.skolverket.se%2Fwtpub%2Fws%2Fskolbok%2Fwpubext%2Ftrycksak%2FRecord%3Fk%3D3783&fref=gc

Man kan ju hitta på en egen algoritm för att blanda en kortlek. Då har man ju skapat en algoritm även om den inte är snabbast eller mest rättvis.


GeoGebra


Programmet bör vara öppen källkod och gratis så att eleverna har nytta av det efter gymnasiet även om de inte får något jobb som har 
programmet. T.ex. Octave, Maxima, Python och JavaScript uppfyller dessa krav. Däremot inte t.ex. Matlab och Mathematica. Matlab är 
lite mer acceptabelt eftersom Octave finns och är ganska kompatibelt. D.v.s. om någon har lärt sig Matlab har de stor nytta av de 
kunskaperna om de senare använder Octave. Om programmet är gratis men inte öppen källkod så riskerar man att villkoren ändras senare. 
Mathematica är t.ex. gratis på Raspberry Pi, men inte öppen källkod. Elever som lär sig Mathematica riskerar dock att inte ha nytta 
av kunskaperna om Wolfram slutar ge gratis tillgång till Mathematica på Raspberry Pi (man kan visserligen köra en gammal version av 
operativsystemet, men de kanske inte fungerar i nyare Raspberry Pi:er). Att använda gratis webbtjänster där motsvarande system inte är 
öppen källkod är heller inte acceptabelt eftersom de kan försvinna. D.v.s. egentligen är Google Sheets oacceptabelt och man borde 
använda t.ex. LibreOffice Calc.


Programmet bör vara interaktivt, d.v.s. man skall kunna skriva (eller dra eller klicka på) kommandon på en kommandorad och få ett 
svar (d.v.s. REPL). Om man endast kan köra det genom att skriva filer så är det inte OK.

Jo, det är lättare att lära sig och att experimentera med olika uttryck. När man har fått fram ett fungerande uttryck så kan man 
klistra in det i sin programfil. De flesta programspråk finns i en interaktiv version.

Man bör ju också tänka på att Internet kanske slutar att fungera och att man bör lära ut program som även fungerar utan Internet. 
Det är acceptabelt att det använder en server på ett lokalt nätverk, ty man kan nog hålla igång stora lokala nätverk även om t.ex. 
kablarna till USA sågas av.

Det är kanske inte så att Internet slutar att fungera helt, men kontakten till servern som man är beroende av är kanske bruten. 
Serverföretaget kan ju också gå i konkurs. Man bör ändå ta det lugnt i krissituationer och fortsätta undervisningen som vanligt, 
men det kräver ju att man har allt man behöver på det lokala nätverket. Jag har t.ex. Peercall-telefoner, men serverföretaget gick 
i konkurs så nu kan jag inte använda telefonerna längre, ty det finns ingen annan server som stödjer dem.

Vad säger att de kan Python? Visserligen finns det barnböcker på svenska om Python, men inte så många om JavaScript. De måste ju 
lära sig något konkret programspråk -- åtminstone tillräckligt mycket för att skriva program för matematik. Det kan ju lika gärna 
vara JavaScript och då slipper man byta från Python till JavaScript senare för det är bara JS som fungerar i GeoGebra.

Systemen borde vara sådana att data bara lagras lokalt på skolans servrar (eller kommunens eller friskolekoncernens). Alla elever 
vill inte att deras data skall lagras utomlands. Man bör ju också ha en krisberedskap så att inte utbildningen stoppas bara för 
att t.ex. kablarna till USA klipps av.

Det finns vissa system där man kan omvandla från block till JavaScript, Python eller C++. T.ex. Coding with Chrome -- en app i 
Chrome: https://chrome.google.com/webstore/detail/coding-with-chrome/becloognjehhioodmnimnehjcibkloed  
Där kan man omvandlar Blockly till JavaScript.


Här är ett Scratch-program som beräknar när påskdagen infaller: https://scratch.mit.edu/projects/108815587/

Formeln programmet använder förklaras i "Gauss : matematikernas konung" av Tord Hall: http://libris.kb.se/bib/8074192 . Jag läste 
dock boken i gymnasiet 1982-1985 och har inte kollat i den sedan dess. Jag tror dock den boken kan vara bra även för 
dagens gymnasieelever. Boken finns också på engelska: http://www.amazon.com/Carl-Friedrich-Gauss-Tord-Hall/dp/0262080400

Jag har översatt ett program i C till Java till Scratch (samtliga program är öppen källkod). Se mer information i beskrivningen på 
sidan för programmet.

iiS har nyligen gett ut en bok om algoritmer, men jag vet inte om den är bra: https://www.iis.se/fakta/algoritmer/


Hej,
jag har gjort en video som visar ett ScratchX-projekt som högläser tweets på Twitter som innehåller ett visst ord -- just nu #RaspberryPi:
https://youtu.be/2EpZ1zx6DRU
Mer information om projektet som är öppen källkod finns här:
https://mobluse.github.io/scratchx/

Man behöver bara klicka på en länk och vänta en stund medan projektet laddas och sen klicka på grön flagga. (Det var en bugg tidigare som gjorde att alla extensions inte laddades, utan man fick ladda in vissa manuellt, men det verkar fungera automatiskt nu.)
http://scratchx.org/?url=https://mobluse.github.io/scratchx/speaktweet.sbx
Instruktioner finns i en kommentar i projektet:
' Click a green flag. It reads selected tweets aloud. Tweets are selected if they contain a word: now "#raspberrypi", and are not replies. An alarm starts sounding after that and you need to stop it by clicking the bell. Tweets are also stored in a list with the latest on top.

Sometimes Twitter doesn't load automatically, but then you can load it using Load Experimental Extension in More Blocks:  
https://technoboy10.github.io/twitter/extension.js

Text to Speech, in case you need to load that manually:  
http://sayamindu.github.io/scratch-extensions/text-to-speech/text_to_speech_extension.js '

Man måste möjligen också ha installerat något uppläsningssystem i Chrome/Chromium. Jag har SpeakIt! 0.2.995.

ScratchX är ett system för att utvidga Scratch2 med extensions skrivna i JavaScript. Det finns t.ex. en extension för att koppla till Arduino UNO, men jag har inte testat den. Det finns en annan extension för att koppla till en vädertjänst och den har jag testat för Lund.

Det finns ett forum för hur man utvecklar Scratch extensions. Jag skrev frågor här och de problemen är lösta:  
https://scratch.mit.edu/discuss/topic/265410/  
https://scratch.mit.edu/discuss/topic/265601/

Det finns en officiell lista med extensions http://scratchx.org/#extensions och även en inofficiell:
http://savaka2.github.io/scratch-extensions-directory/

ScratchX-projekt kan även fungera i Raspberry Pi 2 och 3 om man använder den inbyggda Scratch 2 och byter filändelse från sbx till sb2, samt laddar extensions manuellt. De kan även fungera i webbläsaren Chromium, ty den har inbyggd Flash.

ScratchX är bra för dem som kan Scratch 2 eftersom det gör det möjligt att skriva Scratch-program som kopplar mer till Internet och hårdvara. Man kan skriva egna extensions i JavaScript som t.ex. skickar e-brev via GMail. Det kan motivera mer avancerade elever att lära sig JavaScript, ty man kan hjälpa elever som bara kan Scratch att skriva mer verklighetsnära program.


Scratch 3:  
https://llk.github.io/scratch-gui/

Det finns ytterligare ett blockspråk nu: Python i form av block: http://edublocks.org/
Har ej testat det än.

NetsBlox ser inte ut som Python. Det är dåligt att EduBlocks bara finns för Raspberry Pi (ARM), men det kanske portas till x86 med 
tiden, ty så har skett med SonicPi. Jag har testat EduBlocks på Raspberry Pi 3. Jo, det fungerar, men har inte lika många funktioner 
som Scratch. Man kan i vissa fall skriva in Python-funktioner för hand. EduBlocks kör i Chromium och använder en egen webbserver. 
Systemet kan ibland haka upp sig.

I demon finns inga listor alls. Jag hoppas listor blir första klassens objekt, d.v.s. att man kan ha listor som argument till procedurer och ha listor med listor o.s.v. Snap! har redan detta, men var ganska buggigt när jag provade det sist.
