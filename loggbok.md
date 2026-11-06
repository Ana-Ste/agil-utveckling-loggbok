# Individuell loggbok – Ana Stevanović
## Agil utveckling – webbshopprojektet

Dessa anteckningar är skrivna i efterhand utifrån mitt arbete och mina erfarenheter under projektets sex sprintar.

## Sprint 1 – Planering och de första funktionerna

Scrum Master: Armin

### Vad jag arbetade med

Jag ansvarade för välkomstsidan efter inloggning, CORS-konfiguration för frontendens anrop till product-service samt gemensam header och footer. Arbetet gick bra och mina uppgifter blev färdiga.

### Eventuella problem och hur jag löste dem

I början var arbetssättet nytt och vi visste inte riktigt vad vi skulle förvänta oss. Trots att vi tidigare hade arbetat tillsammans med backend behövde vi tid för att planera nästa steg. Måndagens första möte tog ungefär en timme. Vi skapade vår Trello-tavla, gick igenom de första 13 punkterna i backloggen och fördelade arbetet.

### Samarbete och agilt arbete

Vi använde Scrum Poker för att uppskatta uppgifterna och diskutera deras omfattning. Under veckan kommunicerade vi främst genom meddelanden och hade inte dagliga möten. På fredagens retrospektiv bestämde vi därför att försöka ha korta dagliga avstämningar nästa sprint. Kommunikationen var redan från början öppen och gruppmedlemmarna svarade på frågor, vilket gjorde samarbetet tryggt och enkelt.

## Sprint 2 – Komponenttester och undersökning av betalning

Scrum Master: Sofia

### Vad jag arbetade med

Jag arbetade med FE-18, att konfigurera testmiljön och komponenttesta ProductCard, samt FE-19, att fortsätta undersöka betalningslösningar. Jag använde Vitest och React Testing Library för att testa produktinformationen och vad som händer vid klick.

Jag lade ungefär fyra timmar på betalningsundersökningen och gjorde en PowerPoint som jag presenterade för gruppen. Det var ett arbete som jag uppskattade mycket. Vi bestämde oss för att gå vidare med Stripe Checkout och prova betalningar i testmiljö.

### Eventuella problem och hur jag löste dem

Betalning var ett nytt område för mig. Jag jämförde alternativ och sammanställde hur ett möjligt betalningsflöde kunde fungera. Presentationen gav oss ett gemensamt underlag för nästa steg.

### Samarbete och agilt arbete

Vi försökte införa avstämningar på ungefär 10–15 minuter under tisdag till torsdag, efter ett längre planeringsmöte på måndagen. Vi lyckades inte genomföra alla möten. På retrospektiven tog vi därför åter upp behovet av regelbundna avstämningar. Jag såg hur retrospektiven kunde användas för att förbättra vårt arbetssätt.

## Sprint 3 – Kundvagn och utloggning

Scrum Master: Armin

### Vad jag arbetade med

Jag ansvarade för FE-21, Kundvagn del 3, och FE-22, möjligheten att logga ut. Kundvagnsuppgiften handlade om att behålla innehållet vid omladdning, skicka det till order-service vid köp och hantera resultatet. Jag arbetade också med utloggningsfunktionen i gränssnittet. Uppgifterna gick relativt snabbt och blev färdiga.

### Eventuella problem och hur jag löste dem

Jag upplevde inga större hinder i mina uppgifter under denna sprint. När något behövde stämmas av kunde jag snabbt ta upp det med gruppen och fortsätta arbetet.

### Samarbete och agilt arbete

Den här veckan lyckades vi genomföra dagliga avstämningar och fortsatte även kommunicera genom meddelanden. Det gjorde det lättare att veta vad de andra arbetade med och om någon behövde hjälp. Vi hade förbättrat en konkret sak som vi hade tagit upp på tidigare retrospektiv. För mig blev detta ett tydligt exempel på hur ett agilt arbetssätt utvecklas genom återkoppling och små förändringar.

## Sprint 4 – Gateway, Docker och CI/CD

Scrum Master: Ana

### Vad jag arbetade med

Vi arbetade med gateway-applikationen och dess driftsättning. Mina delar var att dockerisera gateway och konfigurera CI/CD samt implementera orderflöden via gateway. Arbetet omfattade bland annat Dockerfile, Docker Hub, GitHub Secrets, bygg- och testworkflow samt vidarebefordran av orderanrop.

Vi delade upp de stora uppgifterna i mindre delar. Mina två Trello-kort hade sex checklistpunkter vardera, vilket gjorde framstegen lättare att följa.

### Eventuella problem och hur jag löste dem

Inför demonstrationen kunde jag inte logga in lokalt och fick ett fel om för många inloggningsförsök. Armin visade därför systemet. När jag diskuterade problemet med gruppen upptäckte vi att jag bara hade startat frontend. Jag lärde mig att även de backendtjänster som den lokala konfigurationen använder måste vara igång. Orsaken till själva inloggningsbegränsningen behövde skiljas från detta.

### Samarbete och agilt arbete

Som Scrum Master bidrog jag till planeringen och uppföljningen av arbetet. Uppdelningen i mindre delar gjorde beroenden och återstående arbete tydligare. Vi kunde lättare diskutera hinder och samordna våra ändringar mot ett gemensamt sprintmål.

## Sprint 5 – Integrationstester med MSW

Scrum Master: Armin

### Vad jag arbetade med

Jag ansvarade för FE-38, att undersöka integrationstestning, FE-39, att konfigurera MSW, och FE-40, att testa produkthämtning. Jag undersökte hur frontend kunde testas med mockade API-svar och arbetade med testmiljön och testerna. Mina uppgifter blev färdiga och testerna gick bra.

### Eventuella problem och hur jag löste dem

Jag behövde invänta en annan gruppmedlems arbete innan jag kunde slutföra en del av mina uppgifter. Genom att stämma av beroendet med gruppen visste jag vad som återstod och kunde fortsätta när förutsättningarna fanns. Väntan blev kort och skapade inget större hinder.

### Samarbete och agilt arbete

Vi hade daglig kontakt och samarbetet kändes nu som arbetet i ett välfungerande utvecklingsteam. Avstämningarna gjorde beroenden synliga och hjälpte oss att anpassa ordningen på arbetet. Jag upplevde att det var enkelt att ställa frågor och få stöd. Det gjorde att jag kunde arbeta självständigt och samtidigt behålla kontakten med gruppens gemensamma mål.

## Sprint 6 – Dokumentation och avslutning

Scrum Master: Sofia

### Vad jag arbetade med

Jag ansvarade för FE-43, att skapa och uppdatera README-filer för systemets repozitorier: auth, product, order, mail, gateway och frontend. Jag dokumenterade tjänsternas ansvar, konfiguration och hur applikationerna startas. Arbetet innehöll mycket skrivande och genomgång av systemet, men var inte särskilt svårt kodmässigt. Uppgiften blev färdig.

### Eventuella problem och hur jag löste dem

Utmaningen var främst att samla information och beskriva systemet tydligt och konsekvent. Jag gick igenom konfigurationen och stämde av uppgifter med gruppen. Dokumentationen skulle göra det lättare för en ny utvecklare att förstå och köra projektet.

### Samarbete och agilt arbete

Under sista sprinten hade vi lärt känna varandras arbetssätt och kunde samordna oss bättre. Vi visste när våra delar behövde vara klara för att andra skulle kunna fortsätta.



Min viktigaste lärdom är hur mycket god kommunikation och ansvarstagande betyder. Lärarens återkoppling vid veckans presentationer hjälpte oss också att bedöma resultatet och välja nästa steg. Att få se våra framsteg och få konkret uppskattning gav mig motivation att fortsätta utvecklas.
