# PAR problem

 Inspirerad av denna [blog](https://undergroundmathematics.org/blog/peer-assisted-reflection) så är detta mitt försök att samanställa ett antal uppgifter som lämpar sig för denna typ av läxor. Fokus kommer till att börja med vara ma2, men ska så småningom utvidgas till ma3c också.

## Instruktioner för latex filerna

De individuella uppgifterna ligger i mappen [uppgift](/uppgifter/) dessa inkluderas sedan i [huvudfilen](Par_paket.tex) genom tex `\input{uppgifter/glasspaketet.tex}`. Resten av huvudfilen är bara mall för att få läxorna att se rätt ut och de ända man behöver ändra är nummer på uppgiften och de olika inlämnings datumen. Detta gör på rad 13-17.

Filerna är tänkta att fungera i visual studio code med LaTeX Workshop. De borde fungera i tex overleaf också, men vissa saker som de "magiska" kommentarerna i början på par_paket.tex som har till syfte att tala om för LaTeX Workshop vilken fil som är huvudfil kanske behöver filas på.
