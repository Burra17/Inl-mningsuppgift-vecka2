# Fråga 1
## 1. Skillnaden mellan vattenfallsmetoden och agil metodik

### Vattenfallsmetoden
Enligt vattenfallsmetoden skulle jag börja med att samla information och krav på vilka funktioner som appen ska innehålla.  
I detta fall hade det varit funktioner som: konto, inlägg, kommentarer, gilla-markeringar osv.  

Efter det går man vidare till **design och arkitektur**, där man bestämmer hur appen ska se ut samt planerar hur man ska tänka när man börjar koda.  

Nästa steg är **implementering**, där jag faktiskt kodar appen efter designen jag bestämt och utvecklar varje modul som behövs.  
Därefter testar jag appen så att allt fungerar som det ska och korrigerar buggar.  

Till slut läggs appen ut på Appstore till användarna, och därefter sker **underhåll** med uppdateringar, baserat på teknikens utveckling och användarnas feedback.  

---

### Agil metodik
Enligt den agila metoden bryter jag ner uppgiften i mindre delar, t.ex.:  
- skapa konto  
- göra ett inlägg  
- kunna kommentera  

Varje del kan utvecklas och testas för sig. Om jag har hjälp i ett team kan man dela upp arbetet så att olika personer jobbar med olika delar. Dessa delar kallas för **sprintar**.  

När kärnfunktionerna är klara distribueras appen till användarna. Efter användarfeedback kan man skapa nya sprintar för att lägga till nya funktioner, till exempel en **stories-funktion** som inte fanns med från början.  

---

### Reflektion
Jag hade valt **vattenfallsmetoden** om jag utvecklade appen helt själv, eftersom den är linjär och man tydligt gör allt steg för steg.  
Men om jag arbetade i ett team hade jag valt **agil metodik**, eftersom arbetet kan delas upp och varje utvecklare kan fokusera på sin egen del av appen.  

---

# Fråga 2
## 2. Vad är ett git commit och varför är det viktigt?
Ett commit i Git är som att spara i projektet. När jag gör ett commit så sparar jag den kod jag skrivit i det tillståndet den är just nu, tillsammans med ett meddelande som beskriver vad jag har ändrat. 
På så sätt får jag en historik över alla förändringar jag gjort i projektet.  

Det är viktigt eftersom det gör det möjligt att:  
- Gå tillbaka till en tidigare version om något går fel  
- Se vem som har gjort vilken ändring  
- Hålla ordning när man jobbar flera i samma projekt  

Ett exempel: Om jag bygger en app och råkar ta bort en hel funktion av misstag, så kan jag enkelt gå tillbaka till en commit där funktionen fortfarande fanns. Det gör att jag slipper återskapa koden från början och sparar mycket tid.  

---

# Fråga 3
## 3. Samarbete med GitHub – pull requests, branches och merge

När man samarbetar via GitHub så kan flera utvecklare arbeta på samma projekt utan att trampa varandra på tårna. GitHub fungerar som en gemensam plats där all kod sparas, och där man kan se vem som gjort vad och när.

### Branches
En branch är som en egen kopia av projektet där man kan testa nya idéer eller bygga en funktion utan att störa huvudkoden (main). På så sätt kan man experimentera och jobba parallellt.

### Pull Requests
En pull request (PR) används när man vill få in sin branch i huvudprojektet. Då säger man i princip:  
Till exempel: "Hej team, jag har gjort klart min nya funktion i min branch. Kan ni kolla på den och se om allt ser bra ut innan vi lägger till den i main?"  
Det gör att teamet kan diskutera, kommentera och se till att koden håller bra kvalitet.

### Merge
När en pull request har blivit godkänd så "mergas" branchen in i huvudprojektet. Det betyder att de nya ändringarna läggs ihop med main, och hela teamet får tillgång till den uppdaterade koden.

### Reflektion
Fördelen med det här arbetssättet är att man undviker kaos i koden. Alla kan jobba på sina egna delar, men samtidigt ha kontroll över vad som faktiskt hamnar i slutversionen. Det blir också tydligt vem som gjort vad och varför.
