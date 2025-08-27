# Reflektion — Stegvis HTML/CSS-övning

Svara kort på följande efter varje steg:

## 1) STEG 1: Vad gör `<meta name="viewport">` och varför är det viktigt?

**Svar:** styr hur webbsidan skalas och visas på olika enheter. Den gör att layouten anpassas till skärmens bredd (t.ex. mobil vs. dator). Utan den skulle sidan ofta zoomas ut på mobiler och se väldigt liten ut.

## 2) STEG 2: Varför använda en `.container`-klass och vad händer om du tar bort `padding`?

**Svar:** används för att centrera innehåll och ge det en maxbredd, så att text och element inte sträcker sig över hela skärmen. Om du tar bort padding trycks innehållet ända ut till kanterna, vilket gör det svårare att läsa och ser mindre snyggt ut.

## 3) STEG 3: Hur ändrar `padding` och `display: inline-block` länkelementets klickyta?

**Svar:** padding gör att länken får en större klickyta än bara texten (mer användarvänligt).

          display: inline-block gör att länken kan ha både bredd, höjd och padding, istället för att bara bete sig som ren text.

## 4) STEG 4: Hur påverkade `flex` layouten för projektboxarna jämfört med vanlig block-layout?

**Svar:** Med flex kan projektboxarna ligga bredvid varandra på rad, automatiskt anpassa sig efter utrymme och justeras med mellanrum. I vanlig block-layout staplas de bara ovanpå varandra vertikalt.

## 5) STEG 5: Varför vill vi återanvända header/nav/footer när vi skapar flera sidor?

**Svar:** För att skapa enhetlighet på webbplatsen och spara tid. Användaren känner igen strukturen, och du slipper skriva om samma kod flera gånger. Det blir också enklare att uppdatera designen senare.

## 6) STEG 6: Ge ett exempel på en hover-effekt du la till och vad den gör.

**Svar:** Ett exempel kan vara att en knapp byter bakgrundsfärg eller får en underline när muspekaren hovrar över den. Den gör att sidan känns mer interaktiv för användaren. 

## 7) STEG 7: Vilka ändringar gjorde du för att sidan ska fungera på mobiler?

**Svar:** Använde media queries för att anpassa layouten. Lade till meta name="viewport" 
