---
---
Laddnings­tid och använd­barhet
=========================
På detta repport ska jag analysera laddnings­tid och använd­barhet för tre olika webbplatser baserat på deras resultat med <a href="https://developers.google.com/speed/">Google PageSpeed Insights</a>. Laddnings­tiden som redovisas är tid­punkten då respektive sidas samtliga egna resurser laddats färdigt, då det är denna som avgör när hela sidan kan renderas och inter­ageras med fullt ut.
Observera även att värdena för samtliga mät­punkter som redovisas i denna analys kan variera över tid eftersom de individu­ella sidorna ofta inte är statiska – liksom på grund av tillfälliga toppar och dalar i nätverks­trafiken – men nedan­stående värden var de som gällde när jag utförde mätningarna (13/12/ 2018).
<p>
    <em>
        <strong>OBS:</strong>
        Jag har utfört denna uppgift på egen hand och har därför inga övriga gruppmedlemmar att redovisa.
    </em>
</p>

<h2>1 Blekinge Tekniska Högskola</h2>

BTH är lärosätet som håller i den utbildning som denna kurs ingår i och denna webbplats borde därmed vara bekant för alla som läser den.


<a href="https://www.bth.se/"><img src="image/webbsites/bth.jpg" alt="Skärmdump av BTH" title="">
</a>
<h5>1.1 Startsida</h5>
<p><a href="https://www.bth.se/">http://www.bth.se</a></p>
<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>17/100</td></tr>
    <tr><td>Desktop Speed</td><td>81/100</td></tr>
    <tr><td>Laddningstid</td><td>3,6 s</td></tr>
    <tr><td>Antal resurser</td><td>62 st</td></tr>
    <tr><td>Total storlek</td><td>3 958 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skicka bilder i modernare bildformat</li>
<li>Använd bilder med rätt storlek</li>
<li>Skjut upp inläsningen av bilder som inte visas på skärmen</li>
<li>Minska svarstiderna från servern (tid till första byte)</li>
</ul>

<h4>1.2 Programsida</h4>

<p><a href="https://www.bth.se/utbildning/program/data-och-mjukvaruutveckling/webbprogrammering/">http://www.bth.se/distansutbildningar/webbprogrammering/</a></p>


<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>17/100</td></tr>
    <tr><td>Desktop Speed</td><td>86/100</td></tr>
    <tr><td>Laddningstid</td><td>3,6 s</td></tr>
    <tr><td>Antal resurser</td><td>61 st</td></tr>
    <tr><td>Total storlek</td><td>3 427 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skicka bilder i modernare bildformat</li>
<li>Använd bilder med rätt storlek</li>
<li>Skjut upp CSS som inte används</li>
<li>Minska svarstiderna från servern (tid till första byte)</li>
</ul>

<h4>1.3 Studentportalen</h4>

<p><a href="https://studentportal.bth.se/en/page/bth-card">https://studentportal.bth.se/en/page/bth-card</a></p>


<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>17/100</td></tr>
    <tr><td>Desktop Speed</td><td>63/100</td></tr>
    <tr><td>Laddningstid</td><td>3,9 s</td></tr>
    <tr><td>Antal resurser</td><td>13 st</td></tr>
    <tr><td>Total storlek</td><td>3 427 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skjut upp CSS som inte används</li>
</ul>

<h4>Utvärdering</h4>

De tydligaste åtgärderna som BTH bör överväga är att ta bort resurser som blockerar renderingen och slå ihop så många som möjligt av skript- och stilfilerna för att minska antalet anrop – bådadera ger just nu en betydande ökning i såväl storlek som väntetid – och använd bilder med rätt storlek, särskilt de stora. Student­portalen är dessutom inte mobil­anpassad över huvud taget, vilket är anledningen till det dåliga betyget för den sidan, och att hänvisa till en app med begränsad funktionalitet visar på en tveksam användning av utvecklings­resurser som förmodligen istället borde lagts på att skapa en responsiv layout.

<h2>2 Dbwebb.se</h2>

Dbwebb är webbplats som har alla kurser, utbildning och meterial som eleverna behöver dem att studera vid BTH i vissa ämnen. Denna webbplats borde därmed vara bekant för alla som läser den.


<a href="https://dbwebb.se/"><img src="image/webbsites/dbwebb.jpg" alt="Skärmdump av dbwebb" title="">
</a>
<h5>2.1 Startsida</h5>
<p><a href="https://dbwebb.se/">https://dbwebb.se/</a></p>
<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>96/100</td></tr>
    <tr><td>Desktop Speed</td><td>100/100</td></tr>
    <tr><td>Laddningstid</td><td>0.7 s</td></tr>
    <tr><td>Antal resurser</td><td>21 st</td></tr>
    <tr><td>Total storlek</td><td>147 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skicka bilder i modernare bildformat</li>
<li>Skjut upp inläsningen av bilder som inte visas på skärmen</li>
<li>Skjut upp CSS som inte används</li>
</ul>

<h4>2.2 Kursersida</h4>

<p><a href="https://dbwebb.se/kurser">https://dbwebb.se/kurser</a></p>


<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>99/100</td></tr>
    <tr><td>Desktop Speed</td><td>100/100</td></tr>
    <tr><td>Laddningstid</td><td>0.5 s</td></tr>
    <tr><td>Antal resurser</td><td>9 st</td></tr>
    <tr><td>Total storlek</td><td>147 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
</ul>

<h4>2.3 Utbildningsida</h4>

<p><a href="https://dbwebb.se/utbildning">https://dbwebb.se/utbildning</a></p>


<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>99/100</td></tr>
    <tr><td>Desktop Speed</td><td>100/100</td></tr>
    <tr><td>Laddningstid</td><td>0.5 s</td></tr>
    <tr><td>Antal resurser</td><td>24 st</td></tr>
    <tr><td>Total storlek</td><td>147 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
</ul>

<h4>Utvärdering</h4>

Den här sidan har fått bästa utvärdering i både desktop och mobil, nästan 100% i båda. Bara åtgärderna som bör Dbwebb överväga är att ta bort resurser som blockerar renderingen.

<h2>3 Svt Play</h2>

SVT Play är Sveriges Televisions webb-tv Där visar Sveriges Television (SVT) sina live-tv-kanaler samt de tv-program de har rättigheterna till, extramaterial och klipp ur program under en begränsad tid. Denna webbplats borde därmed vara bekant för alla som använder den.


<a href="https://www.svtplay.se/"><img src="image/webbsites/svt.jpg" alt="Skärmdump av BTH" title="">
</a>
<h5>3.1 Startsida</h5>
<p><a href="https://www.svtplay.se/">https://www.svtplay.se/</a></p>
<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>34/100</td></tr>
    <tr><td>Desktop Speed</td><td>98/100</td></tr>
    <tr><td>Laddningstid</td><td>0.7 s</td></tr>
    <tr><td>Antal resurser</td><td>6 st</td></tr>
    <tr><td>Total storlek</td><td>190 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Använd bilder med rätt storlek</li>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skjut upp CSS som inte används</li>
<li>Skjut upp inläsningen av bilder som inte visas på skärmen</li>
</ul>

<h4>3.2 Programsida</h4>

<p><a href="https://www.svtplay.se/program">https://www.svtplay.se/program</a></p>


<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>34/100</td></tr>
    <tr><td>Desktop Speed</td><td>88/100</td></tr>
    <tr><td>Laddningstid</td><td>0.7 s</td></tr>
    <tr><td>Antal resurser</td><td>6 st</td></tr>
    <tr><td>Total storlek</td><td>191 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skjut upp CSS som inte används</li>
<li>Minska svarstiderna från servern (tid till första byte)</li>
</ul>

<h4>3.3 Kanalersida</h4>

<p><a href="https://www.svtplay.se/kanaler">https://www.svtplay.se/kanaler</a></p>


<table>
<thead><tr><th>Mätpunkt</th><th>Värde</th></tr></thead>
<tbody>
    <tr><td>Mobile Speed</td><td>33/100</td></tr>
    <tr><td>Desktop Speed</td><td>99/100</td></tr>
    <tr><td>Laddningstid</td><td>0.8 s</td></tr>
    <tr><td>Antal resurser</td><td>9 st</td></tr>
    <tr><td>Total storlek</td><td>191 kB</td></tr>
</tbody>
</table>

<p>PageSpeed ger följande åtgärds­förslag:</p>
<ul>
<li>Ta bort resurser som blockerar renderingen</li>
<li>Skjut upp CSS som inte används</li>
</ul>

<h4>Utvärdering</h4>

De tydligaste åtgärderna som svtplay bör överväga är att skjut upp CSS som inte används och Ta bort resurser som blockerar renderingen – och Använd bilder med rätt storlek, särskilt de stora. svtplay är dessutom inte mobil­anpassad över huvud taget, vilket är anledningen till det dåliga betyget för denna sidan, och att hänvisa till det finns resurser som blockerar rederingen och CSS som inte används istället borde lagts på att skapa en responsiv layout.
