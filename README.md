# WCAG Audit 

In de WCAG-audit ga ik de website van de Slapping Studs IJshockeyvereniging bekijken. Dit is om te onderzoeken hoe toegankelijk de website is, want "het web is voor iedereen". Het is daarom belangrijk dat de website voor iedereen een goede gebruikservaring biedt, ook als je bijvoorbeeld een screenreader gebruikt of geen muis hebt. In de wiki heb ik mijn bevindingen bijgehouden.

<img width="100%" height="100%" alt="502056217-c3209e81-335c-44eb-9e93-bc8e688992e0" src="https://github.com/user-attachments/assets/8a0a31af-724b-4088-93d4-cb7fa55898b1" />
<img width="100%" height="100%" alt="image" src="https://github.com/user-attachments/assets/ff890529-5468-4d9b-9a5a-141c9a972fa4" />

Over het algemeen heeft de website een redelijk oke score op toegankelijkheid. De voornaamste punten die naar voren kwamen, waren de ontbrekende namen van buttons en links, en het contrast dat duidelijk maakte dat dit links waren. Dit zijn dingen die heel snel opgelost kunnen worden door er een aria-label aan toe te voegen. Daarnaast misten de afbeeldingen een duidelijke alt-tekst, wat ook gemakkelijk kan worden aangepast.
Iets wat slecht was gedaan, is de semantiek van de HTML. Er werden vrijwel geen landmarks gebruikt zoals `<header>`, `<nav>`, `<main>`, etc., en wanneer ze wel gebruikt werden, zaten ze vaak in een `<div>` verstopt. Verder werden er in de HTML veel `<div>`-elementen gebruikt. Dit samen maakt het lastig voor screenreaders om door de site te navigeren.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
