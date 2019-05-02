# Javascript Övningar Modul 3
Lite blandade övningar från Högskolan Väst introduktionskurs i JavaScript.


**Övning 1**
Utgå från följande data:
      `var tempen = [ 
      ["","00-08","08-16","16-24"], 
      ["Malmö",12,16,9], 
      ["Mariestad",13,15,10], 
      ["Stockholm",13,15,13], 
      ["Upphärad",14,16,15], 
      ["Göteborg",13,14,12] 
      ]; `
Vi har ett antal mätstationer utplacerade på strategiska positioner i sverige där vi mäter temperaturen. Vi vill göra utskriften enligt nedan och medeltemperaturen skall räknas ut (gör er lösning så likt utskriften nedan som möjligt):
 	00-08	08-16 	16-24	medel
Malmö	12	16	9	12.3
Mariestad	13	15	10	12.7
Stockholm	13	15	13	13.7
Upphärad	14	16	15	15
Göteborg	13	14	12	13

**Övning 2**
Nedan är data som kommer från svenska städers mätstationer. använd alert (eller annat valfritt sätt) för att skriva ut alla Stockholms temperaturer med hjälp av datan nedan:
var tempen = {
"stad" : [
{"namn" : "Malmö", "natt" : "12", "morgon" : "14","kvall" : "10"},
{"namn" : "Göteborg", "natt" : "11", "morgon" : "15","kvall" : "9"},
{"namn" : "Stockholm", "natt" : "10", "morgon" : "13","kvall" : "10"},
{"namn" : "Mariestad", "natt" : "11", "morgon" : "16","kvall" : "11"}
]
};

**Övning 3**
 Gör om uppgift 9 och 10 från modul 2 som handlar om läraren Morgan. Programmet ska ha samma funktionalitet men istället för att lagra namn och betyg som två arrayer ska du använda en array av lämpliga objekt istället. se exemplet på en aray med objekt nedan.
var exempelArayMedObjekt = [
{"namn" : "kalle", "betyg" : "A"},
{"namn" : "sara", "betyg" : "E"},
{"namn" : "erik", "betyg" : "F"},
{"namn" : "mia", "betyg" : "B"}
];
x. Det finns färdig kod (Libris Kod (Länkar till en externa sida.)Länkar till en externa sida.) (använd filen som finns under övriga filer på disco istället) för att söka efter böcker i Kungliga bibliotektets databas Libris. Gör en sida som frågar efter ett sökord, utför en sökning på libris.kb.se och presentera resultatet av sökningen snyggt på sidan. Välj själv 3-4 st fält du vill visa upp från resultatet. Du behöver inte kunna hur själva sökningen går till - du får färdig kod för detta.


**Övning 4**
Studera koden nedan och förklara vad som skrivs ut. Tänk först - provkör sedan!
// Vad skrivs ut?

var personA = {firstName:"Thomas", lastName:"Lundqvist", age:47, favorite:"apple"}
var personB = personA;

personB.favorite = "pear";

printit(personA);
printit(personB);

personA = {firstName:"Robert", lastName:"Andersson Dahlberg", age:23, favorite:"banana"} 

printit(personA);
printit(personB);

function printit(person) {
     console.log(person.firstName + " likes " + person.favorite);
}

**Övning 5**
Gör ett eget namespace och lägg till funktionen addera. Funktionen adderaskall ta två tal som inparameter och skriva ut summan av dessa på lämpligt ställe (t.ex. genom att ändra innerHTML i ett element).

**Övning 6**
Gör ett eget namespace och lägg till en variabel som heter antalClick. Skapa en funktion som heter click och varje gång funktionen körs skall 1 läggas till variabeln antalClick. Total antal klick skall skrivas ut på skärmen på valfritt ställe. Funktionen skall "triggas" när man trycker på en knapp.


**Övning 7**
Skriv ett program som men hjälp av javascript ändrar bakgrundsfärgen på ett div-element när man håller musen över den, och sedan ändrar tillbaka till ursprungsfärgen när man flyttar bort muspekaren (använd namespace).

**Övning 8**
Skapa ett program som består av ett textfält (t.ex. <input type=text"">), en knapp och ett div-element. När man trycker på knappen skall det som står i textrutan skrivas ut i div-elementet (använd namespace).

**Övning 9**
Skapa ett program där ett div-element rör sig fram och tillbaka i x-led på skärmen automatiskt. Använd setInterval eller setTimeout (och använd namespace).

**Övning 10**
Skapa en klass som heter Vara den skall innehålla följande attribut: namn, pris, beskrivning, antal samt en metod som heter calcSubTotal. calcSubTotal skall returnera pris*antal (alternativt skriv ut totalpriset någonstans på sidan) skapa ett objekt av denna klass direkt när sidan laddas. Anropa metoden calcSubTotal genom att trycka på en knapp.

**Övning 11**
Återanvänd om möjligt klassen som skapades i föregående övning. Skapa en klass som heter Kundkorg. En kundkorg innehåller flera varor alltså är ett av attributen en array av Varor. Kundvagnen har en metod som heter calcTotal som loopar igenom alla varor i kundvagnen och skriver ut totalpriset någonstans på skärmen. Det är ok att initiera ett antal objekt direkt när sidan laddas. (om denna uppgift känns svår spara den till slutet av modulen)

**Övning 12**
Rita ett klassdiagram med klasserna Kundvagn och Vara. Kundvagn skall innehålla en metod för att kalkylera totalpris samt ett attribut med en array av Vara detta attribut kan vi kalla för Varoror. Vara skall innehålla namn,beskrivning, pris och antal (paint fungerar om ni inte vill ladda hem något annat ritverktyg).

**Övning 13**
Använd (och demonstrera) minst två klasser i ett eget program (fritt val men det får inte vara samma som i tidigare uppgifter) klasserna skall innehålla attribut och metoder. 
