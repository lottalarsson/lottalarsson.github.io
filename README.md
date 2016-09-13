lottalarsson.se
===
Se siten på [lottalarsson.se](http://lottalarsson.se).

## Allmänt
Detta är en instruktion för hur du redigerar sidan och lägger upp nya projekt.

Enklast är att skapa och ändra filer direkt på Github. Det går också att ladda ner hela webbplatsens mapp till din dator och ändra där. Då måste du synka filerna när du är klar, och allt detta kan du göra genom att installera [Github GUI](https://desktop.github.com/).

## Skapa nytt projekt
### Ladda upp bild
Ladda upp bilder till mappen `images`.

### Skapa projekt-sida
Skapa en ny fil i mappen `_posts`. Döp filen enligt `YYYY-MM-DD-projektnamn.md`, där YYYY-MM-DD är ett datum för projektet (endast år kommer att synas på sidan).

Innehållet i filen ska se ut såhär:

    ---
	title:  "Projektnamn"
	description: Denna beskrivning kommer att visas på startsidan
	image: images/kandidat.jpg
	layout: post
	---
	Ditt inlägg här...

	Nytt stycke. Lägg in en bild såhär (notera att du måste börja med ett / i filsökvägen):
	![Bildbeskrivning](/images/kandidat.jpg)

	Länka till någonting såhär: [Google](http://google.com).

Den första delen (mellan två ---) innehåller information om inlägget. `image` pekar på den bild som ska visas på startsidan.
Därefter följer själva inlägget.

Du använder en speciell syntax för att lägga in bilder och länkar i inlägget. Du kan formatera text hur du vill - för mer information, se [en guide i Markdown](https://guides.github.com/features/mastering-markdown/).

## Ändra info om dig
I sidfoten ligger info om dig. För att ändra detta, se filen `_includes/footer.html`.

## Sidans namn och beskrivning för Google
Uppdatera filen `_config.yml` för att ändra beskrivningen som syns i Google eller sidans namn.

## Mall
Hämtad från [HTML5 UP](https://html5up.net/uploads/demos/phantom/).
