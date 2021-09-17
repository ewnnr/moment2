# Moment 2
## Automatiserings-processens syfte:
Genom att använda automatiserings-process, i detta fall gulp, så går det som användare att vara väldigt mycket effektivare i sitt arbete. Istället för att ladda upp sina publiceringsfiler på nytt om man gör en ändring så hjälper gulp till med detta. Man kan också minifiera sin källkod och komprimera sina bilder så att sidan blir snabbare vid uppladdning. 
## Använda paket och verktyg:
Jag har använt mig av systemet gulp som innehåller massor av paket, nedan följer en lista över vilka paket jag använt för denna uppgift. 

Jag har använt mig av dessa paket :

1. gulp-concat - Slår ihop samma typ av fil till en och samma, te.x 2 eller fler JavaScript filer blir till 1.  
2. gulp-terser- Minifierar JavaScript, tar bort radbrytningar och kommentarer. 
3. gulp.cssnano - Minifierar CSS, tar bort radbrytningar och kommentarer. 
4. gulp-imagemin - Komprimerar bildfiler. 
5. browser-sync - Livereload som läser om sidan när en förändring sker. 

## Skapat system och dess task:
Jag har gjort följande tasks: 
1. copyHTML - kopierar HTML filer till pub-katalogen.  
2. cssTask- Slår ihop css-filerna till en och samma, minifierar, lägger över till pubkatalogen samt uppdaterar CSS för webbläsaren vid förändringar.  
3. jsTask - Slår ihop Js-filerna till en och sammma, minifierar, lägger över till pubkatalogen. 
4. imagesTask- komprimerar bildfiler och lägger över dem till pubkatalogen.
5. watchTask - Lyssnar efter förändringar i src-katalogen, hittar den förändringar så skrivs ändringen över till pub-katalogen. Liveserver körs i denna task, dvs att sidan laddas om vid upptäckt färändring i filerna.

### För att installera systemet:
För att installera mitt system krävs Node.JS, gulp och npm. Om dessa finns tillgängligt/installerat kan man sedan skriva först npm install och när det är klart skriver man gulp, i terminalen. Jag har använt mig av bash i Visual Studio Code. 

### Extra
Jag har inte lagt till något extra i denna uppgift. 
