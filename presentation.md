# Kurs: Programmering för lärare F-9 i matematik och teknik
Finns det många sökande kan man dela upp kursen i flera -- med olika stadier och ämnen.

## Mål
Det finns fler mål på kursen och detta är bara ett exempel: Att kunna motivera en kombination av hårdvara, programspråk och 
utvecklingsmiljö (d.v.s. ett programmeringssystem/verktyg) av dem som presenterats på kursen. Man behöver kunna motivera valt system
för programmering för elever och föräldrar eftersom vissa redan har favoritsystem.

## Examination
Skriftlig inlämningsuppgift. Studenterna får olika programmeringssystem som de skall motivera. Detta är en sen uppgift på kursen.
Det är en uppgift som testar högre förmågor som argumentationsteknik och att man verkligen förstår systemen. Jag tänker mig att
det finns bara underkänt och godkänt som betyg, så det gör inte så mycket att de utdelade programmeringssystemen är olika 
komplicerade.

## Programmeringssystem
Det finns många olika system för programmering med barn i skolåldern och även på förskola, t.ex. ScratchJr, Scratch 2, MIT App Inventor,
Micro:bit med Blockly och JavaScript, Micro:bit med Mu (MicroPython), Koda.nu (JavaScript i webbläsare), Kojo (Scala), 
Arduino med Arduino (C++), Arduino med Scrach, Micro:bit med Scratch, Lego-robotar med kompilerad Scratch (egentligen Snap!) 
eller LabView, Code.org (Blockly) o.s.v.

## Föreläsning som exempel på lösning: Scratch 2 på gymnasiet
I enlighet med: [Diskussion i Matematikundervisning på Facebook](https://www.facebook.com/groups/matematikundervisning/permalink/1370508519676612/?match=b2xvZiBkYWhsLGRhaGwsb2xvZiw%3D).  
Trots att detta är en kurs för grundskollärare kan det vara intressant att utreda om ett system avsett för yngre ungdomar går
att använda på gymnasienivå.

### Duger verktyget för alla gymnasiets kurser?
Scratch 2 duger kanske inte för alla kurser i programmering, ty man kan inte namnge data detaljerat. Scratch har inte bitvisa operatorer
(men jag och andra har utvecklat sådana med hjälp av flyttalsfunktionerna). Vissa har implementerat emulatorer för processorer
och gamla spelkonsoler, t.ex. CHIP-8, samt interpreterande och kompilerade programspråk, t.ex. LISP respektive FORTH -- det senare
skapat av mig. Även 3D-spel typ DOOM finns, trots att det inte finns någon inbyggd 3D-grafik i Scratch utan bara pennor, vilka kan 
vara osynliga. Dock är Scratch inte lämpat för extremt avancerad programmering, utan det är mer en sport att skriva avancerade 
program ändå. Stora program är också svåra att hantera genom att släpa skript på skärmen.

### Enkel installation?
Det är bara att gå in på http://scratch.mit.edu/ i webbläsaren (om den har Flash) och börja skapa. Man kan också installera 
en offline-version, men det är lite krångligare, ty Scratch 2 använder Adobe Air -- dock har förhoppningsvis nätverksteknikerna
redan installerat allt.

### Körbart i webbläsare?
Jo, och om man bara vill köra program behöver man inte ha Flash, ty det finns ett system för enbart körning som använder 
enbart JavaScript: Phosphorus. Det finns ett liknande system för körning i mobiler och surfplattor: Sulfurous.

### Går det fort att komma igång med verktyget?
Jo, det startar snabbt och är lätt för nybörjare i och med att man kan se kategorier och tillgängliga block i dem. Det har inbyggd
grafikeditor för bitmap- och vektor-grafik, samt ljudredigerare. Det finns inbyggda bibliotek med bakgrunder, sprajtar, ljudeffekter
och musikinstrument. Scratch 1.4 och 2 är lämpat från 8 år och ScratchJr från 5 år.

### Enkel syntax och enkelt användargränssnitt?
Scratch har en teateranalogi med scen, skådespelare (sprajtar) och kostymer. Att bygga program med block behöver man också
lära sig. Man kan välja bland många naturliga språk. Man kan bara sätta ihop blocken till körbara program -- man undviker alltså
syntaxfel. Man slipper skriva långa texter och memorera kommandon. Man kan enkelt ändra namn på variabler m.m. Det går inte att
söka efter text. Undo med flera nivåer saknas. Man kan tyvärr inte stega sig igenom koden. 

Det finns ett alternativt gränssnitt för att utveckla Scratch-kod som text: [Tosh](http://tosh.tjvr.org/).

### Lätt att skapa roliga/relevanta animeringar?
Ja, men det finns inte något automatiskt system för att skapa filmer med hjälp av enbildstagning. Man kan spela in 1 minut långa filmer
från Scratch 2. Man kan utveckla spelprogram som reagerar på tangentbordet, musen, mikrofonen (ljudnivå) och kameran och man kan
ändra bild och ljud direkt. Det finns både musikinstrument och ljudeffekter.

### Kan verktyget lätt ge lämpliga matematiska utdata som diagram och tabeller?
Man kan spara i listor och dessa kan exporteras (och importeras) från redigeringsläge. Dessa kan sedan plottas med andra program,
t.ex. Excel. Man får skriva program för att rita diagram -- eller hitta färdiga kodbibliotek. Koordinatsystem är som i matematiken,
men vinklarna är som på en kompass, vilket retar matematiker. Det finns bakgrunder som är koordinatsystem.

### Stödjer verktyget villkorssatser och iteration i form av loopar och/eller rekursion?
Ja, dock finns bara rekursiva procedurer och inte rekursiva funktioner som returnerar värden.

### Hanterar verktyget underprogram i funktionsform?
Man kan ha procedurer med argument, men de kan inte returnera värden. Man kan använda variabler i objekten sprajtar för 
att lagra resultat.

### Finns stöd för att använda funktioner som argument till andra funktioner/underprogram?
Ja, man kan skicka strängar som meddelanden och man kan ha strängar som argument till procedurer. Dock kan "skicka meddelande" inte
returnera värden eller ta argument.

### Stabilt?
Jo, det är stabilt och har ett stort utvecklarteam och flera miljoner användare över hela världen.

### Är verktyget interaktivt, d.v.s. kan man skriva kommandon på en kommandorad eller liknande och få ett svar?
#### Se: [REPL](https://en.m.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop)
På sätt och vis. Man kan t.o.m. redigera program medan de kör och ändringarna slår igenom direkt.

### Kan eleverna lätt kan dela kod med varandra och läraren?
Jo, det finns klassrum och man kan remixa andras program. Jag har dock ej testat klassrummen. Det finns en ryggsäck i
online-redigeraren som gör att man kan transportera kod inom och mellan projekt. Det finns ett community där man kan få 
hjälp och man kan kommentera projekt. Projekt kan få beröm och kan hamna på första sidan, vilket är en stor ära.

### Verktyget är rimligt vanligt, så att det finns mycket information om det på nätet.
Jo, det är väldigt populärt och det finns inbyggd hjälp och ett stort forum, samt böcker.

### Är verktyget är plattformsoberoende?
Jo, man kör det i webbläsare med Flash. Den tidigare versionen, Scratch 1.4, finns även 
till [iPad](https://itunes.apple.com/us/app/pyonkee/id905012686?mt=8). Scratch 3 skall använda enbart JavaScript och klarar sig 
alltså utan Flash. Offline-versionen av Scratch 2 finns till Mac OS X, Linux, Windows, samt en speciell
offline-version, till Raspbian. Scratch 1.4 finns till Mac OS X, Linux, Windows och Raspbian.

### Användbart på högskola/arbetsliv?
Tyvärr inte, men det finns ScratchX som gör att man kan använda Scratch 2 till vad som helst genom tillägg i webbläsaren.
I framtiden kommer kanske Scratch att användas på laboratorier för icke-professionella programmerare som ändå behöver utveckla
program då och då.

### Väl utvecklade paket som innehåller subrutiner för matematik/naturvetenskap?
Inte som standard, men det går att utveckla. Dock är det inte lika lätt att importera bibliotek i Scratch som i t.ex. Python,
ty man måste släpa in dem eller starta från ett mallprojekt.

### Strömförbrukning/Snabbhet?
Det är ett tolkat språk och alltså ganska långsamt -- dock finns en turbo-mod. Det finns ett kompilerande system kallat 
Phosphorus som enbart kräver JavaScript och som är mycket snabbare.

### Öppen källkod?
Ja, och gäller Scratch 3, Scratch 2, Scratch 1.4, ScratchJr.

### Flera processer?
Ja, och det är mycket lätt att skapa nya processer och för barn är det naturligt att skapa processer.

### Flera objekt?
Jo, de kallas sprajtar. De är dock inte lika generella som objekt i t.ex. Java eller C++. Sprajtarna kan dock klonas i Scratch 2,
men inte i Scratch 1.4 eller ScratchJr.

### Listor?
Ja, men inte multidimensionella eller listor med listor. Det finns många inbyggda procedurer och funktioner för att hantera listor
i Scratch 1.4 och Scratch 2. ScratchJr har inte listor.

### Koppling till hårdvara?
Ja, via ScratchX kan man koppla till hårdvara, t.ex. Arduino och Micro:bit, eller talsyntes, eller 3D-skärm. Dock fungerar 
inte allt med alla operativsystem. Det finns speciella versioner av Scratch 1.4 för Lego-robotar och Raspberry Pi. Det finns en
speciell version av Scratch 2 för Raspberry Pi som kan använda dess pinnar och ett tillbehör som heter Sense HAT.

### Koppling till Internet?
Ja, via ScratchX. Man kan t.ex. läsa Twitter och princip göra allt som en webbläsare kan göra om man skriver plugginner i JavaScript.

### Preppad?
Scratch kan användas offline och man kan ladda upp projekten till annan server.

### Pris?
Gratis och Scratch 1.4 kan köras på Raspberry Pi Zero som kostar ca 150 kr med kablar, men utan laddare, minneskort, skärm,
tangentbord och mus.
