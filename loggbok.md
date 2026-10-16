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

## Sprint 4 - vecka 43 
