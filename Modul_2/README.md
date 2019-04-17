# Javascript Övningar Modul 2
Lite blandade övningar från Högskolan Väst introduktionskurs i JavaScript.


**Övning 1**
Skapa en funktion som adderar två tal och returnerar svaret.  När sidan laddas skall sidan visa vad 2+2 blir med hjälp av den nya funktionen (använd alert() men lägg den inte i funktionen).

**Övning 2**
Skapa 3 funktioner och ett formulär. Den första funktionen skall köras när man trycker på knappen och ska använda sig av de andra funktionerna. De andra två funktionerna skall räkna ut summan av två tal och produkten av två tal. Se exempel nedan när man tryckt på knappen:

Tal1	2
Tal2	3
[CALCULATE KNAPP]	 
Summa	5
Produkt	6

**Övning 3**
Bygg ut tidigare exempel utan att skapa några nya funktioner så ni även skriver ut summan av de tidigare framräknade talen (vilket bör bli 11 i ovanstående exempel)

 **Övning 4**
Lägg de två funktionerna från förra uppgiften, som tar inparametrar och ger returvärde, i en extern javascript fil och länka in den. Testa så det fortfarande fungerar.

**Övning 5**
Skapa en array med orden "God", "och", "JUL", "Gott", "år", "Nytt" (i den ordningen). När användaren trycker på en knapp skall texten "God Jul och Gott Nytt år" skrivas ut med hjälp av arrayen.

**Övning 6**
Skapa en array med orden "Hej", "Nej", "EJ", "Leverpastej", "42". Via ett formulär ska användaren kunna skriva en siffra och ni skall då visa positionens ord i arrayen. Till exempel: anger användaren 2 skall ordet "EJ" visas.

**Övning 7**
Skapa en array med orden "Hej", "Nej", "EJ", "Leverpastej", "42". Slumpa fram ett av orden och visa dem med valfri metod när ni trycker på en knapp.

**Övning 8**
Skapa en array med orden "det", "är", "kul", "att", "programmera". Använd en loop för att skriva ut texten "det är kul att programmera".

**Övning 9**
Morgan, som är högstadielärare, behöver ett register för att hålla ordning på sina elevers betyg. Antag att du har två arrayer, en med namn och en med betyg. Exempelvis: namn = ["Klara", "Andrea", "Emil", "Sarah", "Alicia", "Victor", "Thomas", "Robert"] med betygen: betyg = ["A", "B", "C", "A", "D", "C", "E", "E"]. Gör därefter en funktion (getGrade) som söker efter ett namn och returnerar betyget (första matchande namnet räcker). Gör därefter en sida som testar och demonstrerar din nya funktion (automatiskt när sidan laddas eller via en knapptryckning). Arrayerna namn och betyg kan vara globala variabler eller, lite snyggare, lokala variabler som skickas som indata till funktionerna.

**Övning 10**
Bygg ut uppgiften innan med en funktion (getNames) som returnerar alla namn (i form av en array) som har ett visst betyg

**Övning 11**
Bygg vidare uppgiften med en funktion (sortNames) som returnerar alla elever sorterade i betygsordning. Tips: använd den inbyggda sorteringen (lite klurigt), skriv en egen sorteringsalgoritm (t ex sök på "insertion sort" - också lite klurigt) eller fuska lite: anropa den tidigare funktionen getNames för att få alla namn som har "A", därefter igen för att få alla "B", osv. Lägg ihop alla svar så har du namnen sorterade i betygsordning.

**Övning 12**
Gör ett program som demonstrerar strängmetoderna: slice(), split(), och join().

**Övning 13**
Det finns även andra strängmetoder som är väldigt användbara: indexOf(), charAt(), toUpperCase(), och toLowerCase(). Läs på hur dessa fungerar och skriv ett program som demonstrerar dessa metoder.(kolla boken)

**Övning 14**
Gör ett program som frågar efter en text och sedan skriver ut texten flera gånger. Först med bara en bokstav, därefter två, och så vidare. T ex: matar användaren in "Thomas" så ska strängarna "T", "Th", "Tho", "Thom", "Thoma", "Thomas" skrivas ut.

 **Övning 14b**
Fortsätt med mer utskrifter i föregående uppgift. Efter att "Thomas" har skrivit uts (6 st delsträngar) så ska allt börja om från andra bokstaven i strängen. Dvs, följande skrivs ut: "h", "ho", "hom", "homa", "homas" (5 st delsträngar). Därefter ska allt skrivas om från 3:e bokstaven, 4:e bokstaven, osv, tills strängen inte har fler bokstäver. Vi skulle alltså få även: "o", "om", "oma", "omas", och: "m", "ma", "mas", och: "a", "as", och slutligen "s".

**Övning 15**
Gör en funktion (kryptera) som krypterar en text genom att byta ut bokstäverna "o", "e", "t", och "n" till tecknen "!", "#", "%", och "&" (om du vill kan du lägga till lite fler bokstäver som byts ut). Gör också en funktion (dekryptera) som byter tillbaks tecknen till klartext igen. Testa och demonstrera att dina funktioner fungerar.

**Övning 15b**
En IT-avdelning behöver skicka ut lösenord till sina användare. Skriv ett program som genererar (skriver ut) 10 st slumpmässiga lösenord. Lösenorden ska inte vara helt slumpmässiga utan vara uppbyggda enligt vissa regler för att lättare komma ihåg dem: (1) de ska vara 9 tecken långa (3 grupper med 3 tecken), (2) varje grupp av 3 tecken ska bestå av konsonant + vokal + konsonant, (3) bara små bokstäver ska användas. Ett lösenord skulle t ex kunna se ut som: "kolnimpup" - mycket lätt att komma ihåg!

**Övning 16**
Borttagen

**Övning 17**
Gör en sida som innehåller en knapp. När man trycker på knappen skall texten "God Jul" skrivas ut som ett h1 element (ett nytt h1-element ska läggas till) inuti body-elementet. Färgen på God Jul skall vara röd.

**Övning 18**
Gör en sida som har ett div-element som det står God Jul i med absolutpositionering samt en knapp. När användaren trycker på en knapp skall ny x och y position slumpas fram så att texten flyttar sig.

**Övning 19**
Gör en sida som visar en text med olika fontstorlekar. Fråga användaren först efter en text och ett antal gånger att visa texten. Skapa därefter en massa element som visar texten från användaren (så många element som användaren valde). Varje text ska ha lite större fontstorlekar. Variera, till exempel, storleken från 10% upp till 200% i lagom många steg.

**Övning 20**
Gör en sida som har ett div-element som det står God Jul i med absolut positionering. Sätt en timer som kallar på en funktion som flyttar elementet 1 pixel åt höger 20 ggr per sekund.

**Övning 21**
Gör ett program som  placerar ut 1 st div-element 50*50 pixlar per sekund på en slumpad position. (Det kan finnas flera sätt att lösa uppgiften på, t.ex. kan ett div-element flyttas till en ny position en gång per sekund, eller så kan ett nytt div-element skapas en gång per sekund.)

**Övning 22**
Gör ett program som  placerar ut 5 st div-element 50*50 pixlar på slumpade positioner. När användaren drar musen över dem skall de slumpas ut på en ny position.

**Övning 23**
Gör ett div-element 50*200 pixlar som rör sig fram och tillbaka på skärmen med texten God jul den skall röra sig en pixel åt höger i ett visst intervall. när elementet flyttat sig 200 pixlar skall det byta till motsatt riktning. 

**Övning 23b**
Gör nu samma uppgift igen men få nu God Jul att röra sig i en cirkel på sidan istället.
 
