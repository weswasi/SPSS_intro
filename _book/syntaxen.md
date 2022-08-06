# Variabelkonstruktion med hjälp av syntax

Ett exempel på när bearbetningar är bra att göra i SPSS är när man vill kombinera olika variabler och
svaralternativ för att skapa en ny variabel. En funktion för detta är Compute (se kapitlet Databearbetning), en annan är funktionen If. Med If kan man precisera villkor för variabelvärden utifrån en eller flera variabler.

Se kapitlet Viktiga rutor i SPSS för en kort beskrivning av syntaxen.

I skolunderökningen (Skol05.sav) finns tre variabler som anger födelseland: För eleven själv
(”fodland1”), för dennes mor (”mfodland”) respektive för dennes far (”pfodland”). Utifrån dessa tre
variabler kan man skapa en varaibel som anger utländsk bakgrund – ”utl_bkgr” - som får värdet 0 om
eleven själv och dennes föräldrar är födda i Sverige och värdet 1 om eleven själv och någon av dennes
föräldrar är födda i annat land.

Öppna syntax: File / New / Syntax

Skriv ett kommande som anger hur variabeln ska skapas i stil med nedanstående kod. Granska gärna kommandot nedan och fundera över dess innebörd. Täcker villkoren in alla? Finns andra möjliga definitioner?


```r
if (fodland1=0 and mfodland=0 and pfodland=0) utl_bkgr=0.
if (fodland1=1 or mfodland=1 or pfodland=1) utl_bkgr=1.
execute.
```

<img src="images/syntax5.png" class="cover"/><p>Markera programsatsen och klicka på den gröna pilen. I datafilen finns nu den nya variabeln ”utl_bkgr”. Nästa steg är att kontrollera så att den konstruerade
variabeln blivit korrekt: Ta fram en frekvens (se vidare nedan), ser fördelninge rimlig ut om du jämför
med ursprungsvariablerna? Kontrollera också gärna ett par av dina observationsenheter – utifrån de
värden de har på de tre ursprungliga variablerna, har det blivit korrekt? Därefter går du vidare med att
sätta labels på variabeln. Observera att när du konstruerar nya variabler är det självfallet viktigt att dessa är genomtänkta och välmotiverade.</p>

### Videoinstruktioner

<center><iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/365/sp/36500/embedIframeJs/uiconf_id/23452190/partner_id/365?iframeembed=true&playerId=kaltura_player&entry_id=0_6ijes7do&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=sv_SE&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_abtlgq9o" width="608" height="402" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player"></iframe></center>
