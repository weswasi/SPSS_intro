# (PART\*) Analysera data I {-}

# Beskrivande statistik

Innan ens hypoteser sätts på prov utförs en så kallad deskriptiv analys (även kallad explorativ dataanalys) där ens datamaterial och i synnerhet de aktuella variabler sammanfattas på olika kvantitativa sätt. Oftast görs det med hjälp av att frekvenstabeller, central- och spridningsmått.

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/process.png"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

## Frekvenstabeller, central- och spridningsmått

<img src="images/beskrivande1.png"  width="50%" height="50%"  class="cover"/><p>Det är vanligt att man inleder en studie med att studera hur observationsenheterna fördelar sig med
avseende på en enskild variabel. Viktiga verktyg i detta ändamål är frekvenstabeller, centralmått och
spridningsmått. Anta att du studerar den Nationella trygghetsundersökningen (NTU 2013-15 M2.sav)
och vill ha information om oro över brottsligheten i samhället:</p>

Analyze > Descriptive statistics > Frequencies

Börja med att söka upp den variabel du är intresserad av i rullistan till vänster (kom ihåg att du kan
välja att visa variabelnamn eller variabeletiketter genom att högerklicka på listan). Därefter markerar
du variabeln och flyttar över den till den högra rutan genom att använda pilen mellan rutorna
<img src="images/beskrivande2.png"  width="50%" height="50%" class="cover"/><p>alternativt dubbelklicka på variabeln. Om du nu väljer alternativet ”OK” kommer SPSS att producera en
frekvenstabell på variabeln. Detta är standardvalet (som du kan se är valet ”Display frequency tables”
markerat), men ofta vill man sammanfatta sin variabel lite mer utförligt. Längst till höger finns
möjligheter att ytterligare specificera vad du vill få fram för statistik. Till exempel kan du genom att
klicka på ”Statistics” välja central- och spridningsmått</p>

Skalnivån (mätnivån) för frågan om oro är på ordinal nivå varför vi i detta fall nöjer oss med en
frekvenstabell:

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

<center><img src="images/beskrivande3.png"/></center>

<hr style="height:2px;border-width:0;color:gray;background-color:LavenderBlush">

Av frekvenstabellen kan vi utläsa mer specifikt hur många individer och hur stor andel som uppger sig
vara oroliga för brottsligheten i samhället. Vi kan till exempel se att endast 24 procent svarar att de
inte alls är oroliga.

<center><iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/365/sp/36500/embedIframeJs/uiconf_id/23452190/partner_id/365?iframeembed=true&playerId=kaltura_player&entry_id=0_oa93699k&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=sv_SE&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_0ogmypot" width="608" height="402" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player"></iframe></center>

## Kort om grafiska tekniker

I syfte att beskriva våra resultat i grafisk form kan man även välja ”Graphs” i huvudmenyn. Genom
alternativet ”Chart Builder” kan du välja på en mängd olika diagramtyper som på bästa sätt beskriver
din/a variabel/ler. Alltså:

Graphs > Chart Builder

Vanliga diagramtyper för att beskriva enskilda variabler är stapeldiagram (”Bar chart”), cirkeldiagram
(”Pie chart”) och histogram. Med detta verktyg kan du på grafisk väg även studera eventuella samband
mellan två variabler. Vi återkommer senare till att åskådliggöra samvariationen mellan två kontinuerliga
variabler genom att ta fram ett så kallat spridningsdiagram (”Scatter plot”).

<img src="images/beskrivande4.png" class="cover"/><p>Det går även att i samband med skapandet av en frekvenstabeller ange att man vill ha ett diagram. De diagram som då finns att tillgå är stapeldiagram, cirkeldiagram och histogram. Klicka er fram till rutan för frekvenstabeller:

Analyze > Descriptive statistics > Frequencies

Mata sedan in den variabel som ni vill skapa ett diagram över. Klicka därfter på knappen Charts. Välj sedan vilket diagram ni önskar att få fram. Klicka därefter på Continue och sedan OK. I output:en ska ni nu ha fått fram en frekvenstabell samt den figur ni har valt.</p>

<center><iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/365/sp/36500/embedIframeJs/uiconf_id/23452190/partner_id/365?iframeembed=true&playerId=kaltura_player&entry_id=0_oa93699k&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=sv_SE&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_0ogmypot" width="608" height="402" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player"></iframe></center>
