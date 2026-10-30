# Individuell loggbok – Webbshop

## Sprint 3 – vecka 42

### Vad jag arbetade med

Den här veckan har jag främst arbetat med vår auth-service och gateway. Jag har konfigurerat gatewayen så att login och register fungerar via den istället för att anropa auth-service direkt. Jag har även arbetat med SecurityConfig och sett till att exempelvis order-service fungerar via gatewayen med rätt säkerhetskonfiguration.

Utöver det har jag arbetat med DTO:er för att strukturera vilken data som skickas mellan frontend och backend.

Jag har även arbetat med konfigurationen i Render genom att uppdatera miljövariablerna så att vår DataInitializer fungerade som den skulle och såg till att en admin-användare skapades korrekt, utan att behöva ändra i själva koden.

### Eventuella problem och hur jag löste dem

Ett problem jag stötte på var att min databas hade gått ut, vilket gjorde att auth-service inte längre kunde ansluta till den. Jag fick därför skapa en ny databas och uppdatera anslutningen för att få tjänsten att fungera igen.

Jag har även behövt felsöka och justera konfigurationen i gatewayen och SecurityConfig för att få både autentiseringen och anrop till order-service att fungera som tänkt.

### Samarbete och agilt arbete

Vi har fortsatt arbeta agilt med en gemensam backlog där vi delar upp arbetet i mindre uppgifter under varje sprint. Jag har främst fokuserat på autentiseringen och gatewayen, vilket är delar som de andra tjänsterna i webbshoppen är beroende av.

Under veckan hade vi även en sprint retrospective där vi gick igenom vad som fungerat bra och vad vi kunde förbättra i vårt arbetssätt. Vi kom bland annat överens om att börja använda Discord istället för Teams för att underlätta kommunikationen inom gruppen.

Jag tog initiativ till att skapa en Discord-server, bjuda in gruppmedlemmarna och sätta upp olika kanaler för att göra det enklare att kommunicera och hålla ordning på diskussionerna.

Jag tycker att retrospektivet var ett bra exempel på hur vi kan använda det agila arbetssättet för att kontinuerligt förbättra vårt samarbete. Istället för att bara prata om vad som kan förbättras tog vi också ett konkret steg för att förändra hur vi arbetar tillsammans.


## Sprint 4 – vecka 43

### Vad jag arbetade med

Den här veckan har jag fortsatt arbeta med autentiseringen i vår webbshop. Jag har framför allt arbetat med JWT och cookies för att hantera användarnas inloggning.

Jag har även implementerat funktionalitet för att återställa den inloggade användaren när sidan laddas om, så att användaren inte behöver logga in på nytt varje gång sidan uppdateras. Jag har också testat att återställningen fungerar som tänkt.

Utöver detta har jag lagt till en cookie-banner i frontend och tillsammans med gruppen undersökt hur vi kan använda integrationstester för att testa våra tjänster.

### Eventuella problem och hur jag löste dem

En utmaning har varit att få hanteringen av JWT och cookies att fungera tillsammans med frontend, framför allt när det gäller att behålla användarens inloggning efter att sidan laddats om.

Jag har därför behövt testa och felsöka hur autentiseringen fungerar mellan frontend och backend och hur vi kan återställa användarens inloggningsstatus.

### Samarbete och agilt arbete

Vi har fortsatt arbeta utifrån vår gemensamma backlog i Trello och fördelat uppgifter under sprinten.

Under veckan har vi även tittat närmare på integrationstestning och diskuterat hur vi skulle kunna använda det i vårt projekt. Det har varit intressant att få en bättre förståelse för hur man kan testa att flera delar av ett system fungerar tillsammans, istället för att bara testa enskilda metoder.

Jag har fortsatt fokusera på autentiseringen och fått en bättre förståelse för hur JWT, cookies och frontend fungerar tillsammans i praktiken.

## Sprint 5 – vecka 44

### Vad jag arbetade med

Den här veckan har vi främst fokuserat på att förbättra dokumentationen i vårt projekt. Vi har arbetat med att lägga till och uppdatera Javadocs samt README-filer för samtliga repositories, så att det blir enklare att förstå hur våra olika tjänster fungerar och hur man kommer igång med projektet.

Utöver dokumentationen har vi även gjort mindre justeringar i frontend för att förbättra användarupplevelsen och få de sista detaljerna på plats.

### Eventuella problem och hur jag löste dem

Den här veckan har vi inte stött på några större tekniska problem. Arbetet har snarare handlat om att gå igenom det vi redan byggt och se till att dokumentationen är tydlig och uppdaterad.

Att skriva Javadocs har också varit ett bra tillfälle att gå tillbaka till tidigare kod och fundera över hur vi kan göra den mer lättförståelig för andra utvecklare.

### Samarbete och agilt arbete

Vi har fortsatt arbeta agilt med vår gemensamma backlog i Trello och fördelat uppgifter inom gruppen.

Den här veckan har vi lagt mer fokus på att förbättra och färdigställa det vi redan har utvecklat istället för att lägga till nya funktioner.

Jag tycker att det har varit nyttigt att få arbeta mer med dokumentation eftersom det är en viktig del av systemutveckling som man kanske inte alltid tänker på när man främst fokuserar på att skriva kod.


