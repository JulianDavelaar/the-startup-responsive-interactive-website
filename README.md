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


# Titel
<!-- Geef je project een titel en schrijf in één zin wat het is -->
**Soundslice ASCII Notation converter** 

Met deze pagina kunnen muzikanten ASCII music notation(dit is een vorm van muzieknotatie gegenereerd door AI) omzetten naar normale muziek notatie

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Dit project wordt een nieuwe functie op de Soundslice website, mensen kunnen hun ASCII plakken in de tekst area en vervolgens op de 'convert' knop drukken, een API zal dan de input omzetten naar door mensen leesbare bladmuziek. Deze pagina is een soort landingpage gemaakt voor AI traffic, eigenlijk een vorm van gratis marketing van traffic wat er toch al is. Op deze manier kan Soundslice muzikanten kennis laten maken met wat soundslice voor hun kan betekenen. En ervoor zorgen dat ze zich aanmelden voor Soundslice en hopelijk wanneer het ze bevalt een abbonement afsluiten.
<img width="941" height="794" alt="image" src="https://github.com/user-attachments/assets/0ced6d34-bdaf-41b3-9346-f67f123317eb" />
https://juliandavelaar.github.io/the-startup-responsive-interactive-website/


## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? -->
Bij dit project is gebruik gemaakt van HTML, CSS & JS. 

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

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).


