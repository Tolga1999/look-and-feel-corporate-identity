> _Fork_ deze leertaak en ga aan de slag. 
Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. 
De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Plant Swap locatie pop up
<!-- Geef je project een titel en schrijf in één zin wat het is -->
Een pop up voor de locatie van Buurtcampus Oost, dit wordt getoond bovenop je huidige scherm.

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Je klikt op de knop "locatie" wat ervoor zorgt dat de pop up "triggered" en tevoorschijn komt bovenop de huidige scherm. De Google maps wordt getoond met de hulp van `<iframe>` dit is een export van Google zelf. Tot slot heeft de pop up een titel, zo weet je wat het precies inhoudt.

<!-- Voeg een mooie poster visual toe 📸 -->
![image](https://user-images.githubusercontent.com/112855878/205628961-09f64b68-fcea-4e75-8855-2b454a1874f0.png)

<!-- Voeg een link toe naar Github Pages 🌐-->
Github pages link: https://tolga1999.github.io/look-and-feel-corporate-identity/

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
Ik heb gebruik gemaakt van HTML, CSS en JS. 
- HTML: De "location" div staat standaard uit en wordt getoond met de hulp van JS en CSS, verder zie je `<iframe>` wat een export is van Google maps zelf.
- CSS: De twee belangrijke CSS classes zijn `.location` en `.locationOn`, de class `.locationOn` wordt toegevoegd (toggled) aan de class `.location` en weer verwijderd met JS.
- JS: In Javascript wordt de class `.locationOn` toegevoegd aan de class `.location`, je kan de link verder "togglen" en de location map weer uitzetten.

## Bronnen
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://developer.mozilla.org/en-US/docs/Web/API/Element/classList
