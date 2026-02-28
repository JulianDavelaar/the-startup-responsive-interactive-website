

# Titel
<!-- Geef je project een titel en schrijf in één zin wat het is -->
**Soundslice ASCII Notation converter** 

Met deze pagina kunnen muzikanten ASCII music notation(dit is een vorm van muzieknotatie gegenereerd door AI) omzetten naar normale muziek notatie

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Dit project wordt een nieuwe functie op de Soundslice-website. Mensen kunnen hun ASCII plakken in de tekstarea en vervolgens op de 'convert'-knop drukken. Een API zal dan de input omzetten naar door mensen leesbare bladmuziek. Deze pagina is een soort landingpage gemaakt voor AI-traffic, eigenlijk een vorm van gratis marketing van traffic die er toch al is. Op deze manier kan Soundslice muzikanten kennis laten maken met wat soundslice voor hun kan betekenen. En ervoor zorgen dat ze zich aanmelden voor Soundslice en hopelijk wanneer het ze bevalt een abonnement afsluiten.
<img width="941" height="794" alt="image" src="https://github.com/user-attachments/assets/0ced6d34-bdaf-41b3-9346-f67f123317eb" />
https://juliandavelaar.github.io/the-startup-responsive-interactive-website/

## Responsive
Ik heb de website mobile first gebouwt, voor de mobiele versie staat alles onder elkaar met als belangrijkste bovenaan de converter, 
<img width="640" height="833" alt="image" src="https://github.com/user-attachments/assets/cb4a0a02-e7c0-46de-b356-166e36fc47f5" />

er is maar 1 breakpoint dat is wanneer de viewport groter is dan 850px dan veranderd de pagina in 2 kolommen voor desktop gebruikers 
<img width="936" height="800" alt="image" src="https://github.com/user-attachments/assets/fce0835b-1aba-43be-9fd5-b9ae4939f098" />

De footer heeft meerdere breakpoints. Onder de 550 px komen alle items daarin onder elkaar te staan in 1 kolom.
<img width="507" height="831" alt="image" src="https://github.com/user-attachments/assets/2004c7ed-b7b9-4688-b2b0-4db925c9757c" />
tot 1000px zijn het 2 kolommen 
<img width="933" height="805" alt="image" src="https://github.com/user-attachments/assets/0562d07f-7db7-4bb6-8fad-e8c7ffa2d17d" />
en na 1000px zijn het 4 kolommen
<img width="1038" height="827" alt="image" src="https://github.com/user-attachments/assets/9506317b-22cf-4bae-9920-9345c2d3e642" />

## Toegankelijkheid
Ik heb op verschillende manieren de toegankelijkheid getest, beginnend met de WCAG-audit. Deze staat beschreven in de wiki.
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/wiki/WCAG-Audit
Ook het kleurcontrast moest aangepast worden. Volgens de test had de kleur van de knoppen een te laag contrast met de rest van de pagina. Ik heb daarom de kleur donkerder gemaakt. Niemand let hierop, maar mensen die moeite hebben met contrast zien hier veel baat bij. 
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/wiki/Color-contrast-test

## Huisstijl
De belangrijkste items van de huisstijl zijn het logo en twee tinten oranje voor titels en knoppen, maar de knopkleur heb ik dus meer rood gemaakt voor het contrast.

## Interactief
Ik heb ervoor gekozen om een interactie te maken met de converter omdat dit is waar de website om draait. Als je op convert klikt verschijnt er een voorbeeld van hoe je geconverteerde bladmuziek eruit gaat komen te zien. 
Als feedforward zie je dat de knop wat groter wordt als je erop hovert, dit toont aan dat je erop kan klikken en dat er dan iets gebeurt, de feedback is de voorbeeld bladmuziek die verschijnt.
<img width="502" height="476" alt="image" src="https://github.com/user-attachments/assets/cc2612d0-03da-418f-a499-49b6818135af" />
<img width="499" height="441" alt="image" src="https://github.com/user-attachments/assets/c19d61d6-4703-4c52-996c-54c0ed0b1718" />


## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? -->
In de HTML maak ik gebruik van duidelijke landmarks en articles om de verschillende secties te laten zien. 
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/994d178f707e3c7e97594e8c8dd99d2848d23d8e/index.html#L12-L203

de CSS is in de volgorde van de HTML zodat het overzichtelijk is, ik maak gebruik van een stylesheet om de belangrijkste kleuren in te gebruiken. 
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/994d178f707e3c7e97594e8c8dd99d2848d23d8e/ss.css#L5-L11

Met JS heb ik gebruik gemaakt van duidelijke benamingen om te verbinden met de CSS en HTML zodat ik zelf goed begrijp en kan uitleggen waar het naar verwijst. 

voor de button heb ik .convert-button dit verwijst naar de convert knop 
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/994d178f707e3c7e97594e8c8dd99d2848d23d8e/index.html#L35

De image met de bladmuziek heet .notation wanneer hij niet zichbaar is en voor de zichtbare versie .notation-visble
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/994d178f707e3c7e97594e8c8dd99d2848d23d8e/index.html#L37


**HTML**
* De HTML heeft een semantische structuur met: header main section article en footer.
* Formulier elementen zoals <textarea> voor ASCII input en <output> voor geconverteerde bladmuziek
* Video element met autoplay en loop voor demo
* voor toegangelijkheid alt teksten en 'for' en 'id' attributen bij de label-input

**CSS**
* CSS custom properties voor consistent kleurenschema
* CSS grid voor responsive layout met mobile first
* geneste media queries binnen selectors
* Keyframe animaties voor interactie
* Hover effecten op buttons
* Flexbox voor alignment van checkmarks en review cards

**JS**
* DOM selectie met queryselector voor het targeten
* Event listeners op convert button voor interactie
* classList.toggle om classes toe te voegen en te verwijderen


## Bronnen
**Soundslice**
https://www.soundslice.com/music-practice/

**Animaties**
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/animation

**Grid**
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/grid

**Textarea output en forms**
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/textarea
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/output
**Soundslice**
Deze website dient als visueel prototype voor een nieuwe pagina voor de soundslice website. de knoppen en converter zijn niet werkzaam omdat dit van onze opdrachtgever niet nodig is. 
Op de site is te zien hoe functionaliteit en marketing samen gaan om zo AI traffic door te sturen naar de soundslice site om zo het klantenbestand uit te breiden.

**Hoe werkt het?**
dit is de pagina waarop AI traffic opgevangen wordt wanneer ze doorgeleid worden naar Soundslice, de pagina bestaat uit een werkzaam gedeelte met 2 textarea's. daarnaast zijn info en reviews te zien van bestaande gebruikers van soundslice.

**ademruimte en inspringen**
Per stuk in me code heb ik gebruik gemaakt van tab's en spaties om het zo overzichtelijk te maken.
hier is te zien dat ik bij de sections overzichtelijk tab's heb gebruikt.
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/85e65ddb4b7e77679657f911b0e393d0d235d9f8/index.html#L43-L55

**Volgorde en nesten van CSS selectors**
Mijn CSS is zo gestructureerd dat het gelijk loopt met mijn HTML, ook heb ik dingen die bij elkaar horen zoveel mogelijk genest en tussen bepaalde elementen wat ademruimte gelaten. spaties overal hetzelfde en tab's ook.
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/b84f91b7f0bb76725723812b9ddb036c1a9dba54/Asciiconv.css#L53-L76

**Nesten van media queries**
Ik heb de media queries gezet waar ze horen, en de dubbele code verwijderd. ook heb ik het beter genest waardoor het nu overzichtelijker is, de max-width is ook weg omdat het genest is. en & gebruikt voor moderne nesting.
https://github.com/JulianDavelaar/the-startup-responsive-interactive-website/blob/a64247a7901e54af2220ba3e55638e578879200d/Asciiconv.css#L43-L63





Ontwerp en maak een responsive website voor een startup.

De instructies voor deze opdracht staan in: [INSTRUCTIONS.md](https://github.com/fdnd-task/the-startup-responsive-interactieve-website/blob/main/docs/INSTRUCTIONS.md)

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).


