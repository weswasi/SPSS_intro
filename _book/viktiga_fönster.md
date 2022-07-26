# Viktiga fönser i SPSS

SPSS består i huvudsak av tre olika fönster med skilda funktioner: Datamatrisfönstret, variabelfönstret och resultatfönstret. Därutöver finns det ett ytterligare fönster - Syntaxfönstret - vilket inte används lika ofta. Här nedan finns en beskrivning vad respektive fönster avser.

## Datamatrisfönstret (Data view)

Detta fönster redovisar variablerna (t.ex. en fråga i en enkäteundersökning) kolumnvis och observationsenheterna (exempelvis de skolelever som svarat på en enkät) radvis. En enskild cell redovisar alltså en specifik observationsenhets värde på en specifik variabel. Klicka på Data view-knappen längst nere till vänster för att öppna datamatrisfönstret.

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/data_view.png" width="90%" height="90%"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

## Variabelfönstret (Variable view)

I detta fönster visas de olika variablerna och deras egenskaper. Variablerna redovisas radvis och egenskaperna kolumnvis. Byte av fönster görs enkelt genom att klicka nere i vänstra hörnet, där man kan välja mellan Data View och Variable View.

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/variable_view.png" width="90%" height="90%"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<img src="images/a1.png" class="cover"/><p>När du öppnar ett befintligt datamaterial får du upp datamatrisfönstret (Data View), antingen med variabelvärden i text (bilden till vänster) eller som siffror (till höger). Hur man väljer att se värdena kan man ange genom att trycka på knappen till höger.

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/variable_view_text.png" width="47%" height="47%" style="padding: 10px"/>  <img src="images/variable_view_dummy.png" width="53%" height="53%" style="padding: 10px"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

I exemplet har datafilen Skol05.sav öppnats och varje rad motsvarar här en skolelev och dennes svar på
de olika frågorna i enkäten. Vid kodningen har varje svar kodats in med en siffra och dessa värden har
getts etiketter/labels.

<img src="images/data_variable_view.png" width="20%" height="20%" class="cover"/><p>Om du byter till Variable View (detta görs enkelt längst ner till vänster) ser du hur materialet kodats in
med etiketter (labels) som anger både en precisering av de olika variablerna och de olika variabelvärdena:</p>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/variable_view_2.png" width="90%" height="90%"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

I variabelfönstret redovisas alltså variablerna radvis och dess egenskaper kolumnvis. I detta fönster finns ett antal kolumner som är viktiga att känna till. Under den första kolumnen ”Name” listas variabelnamnet på varje variabel i ditt dataset. Variabelnamnet hålls vanligtvis kort och det blir därför ofta svårt att utläsa vad variabeln mäter. Information om vad variablerna mäter och hur de är konstruerade finns ibland i en separat kodbok eller variabellista men du kan även förtydliga dina variabler i själva datafilen. Under kolumnen ”Label” anges variabeletiketten, som är en kort beskrivning av variabeln. Under kolumnen ”Values” anges vad variabelns olika värden svarar mot.

<img src="images/value_labels.png" width="50%" height="50%" class="cover"/><p>Variabeln ”kon” har till exempel värde 0 eller 1, där värde 0 betyder ”flicka” och värde 1 betyder ”pojke”. För att undersöka detta markerar du cellen för den aktuella variabeln under kolumnen ”Values” och klickar därefter på den lilla rutan till höger. Nu kommer fönstret ”Value Labels” upp. Om variabeln saknar etiketterade variabelvärden kan du ange dessa genom att föra in värdet i rutan ”Value” och vad värdet står för i rutan ”Label”. Klicka därefter ”Add”. När du etiketterat samtliga variabelvärden klickar du **OK**.</p>

Tänk på att variabelns värden endast behöver specificeras för variabler som befinner sig på nominal eller ordinal skalnivå. Om du till exempel har en kontinuerlig variabel som mäter ålder i antal år (kvotskala) är variabelvärdena i sig informativa och du behöver inte förtydliga vad dessa står för.

## Resultatfönstret (Output)

I detta fönster visas resultat. Det kan röra sig om resultat från hypotesprövningar, frekvenstabeller, korstabeller eller olika typer av diagram. Till vänster finns en översiktsmeny där du enkelt kan bläddra mellan dina resultat.

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/output_view.png" width="90%" height="90%"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

## Syntax (Syntax editor)

Vissa bearbetningar av data där man vill kombinera olika variabler kan vara enklare att göra i syntax. I syntax kan du skriva kommandon, dvs. det du vill att SPSS ska göra åt dig – en frekvenstabell, korstabell, omkodning av variabler mm. Alla sådana moment har sina egna kommandon.

Du kan öppna syntax via File > New > Syntax:

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/syntax.png" width="90%" height="90%"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

Kommandon kan antingen skrivas direkt i syntax eller så kan du gå via menysystemets funktioner och klick på **Paste**.

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/syntax2.png" width="90%" height="90%" /></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

Klickar du på denna knapp så kommer syntax kommandot för denna omkodning att öppnas i syntaxfönstret:

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/syntax3.png" width="90%" height="90%"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

“Syntaxspråket” tar ett tag att lära sig, och är heller inte nödvändigt för er att kunna, men att använda sig av syntax (direkt eller via ”paste”) kan många gånger underlätta arbetet i SPSS och om du sparar syntax får du en loggbok över det du har gjort, på så sättt är det enkelt att gå tillbaka för att se hur du gått tillväga vid analyser, omkodningar etc. (Om du sparar de kommandon och körningar du har gjort och har användning för i syntax, skriv gärna rubriker/kommentarer som anger vad och varför du gjort olika moment. Obs: För att inte programmet ska missta rubriker/kommentarer för kommandon måste du skriva en asterisk (*) före dessa och avsluta med en punkt.). Om ni är intresserade av att <a href="https://www.spss-tutorials.com/spss-syntax/">lära er mer om syntaxspråket rekommenderas följande sida.</a>
