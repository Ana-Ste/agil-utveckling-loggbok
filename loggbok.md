# Individuell loggbok – Ana Stevanović
## Agil utveckling – webbshopprojektet

## Första sammanfattningen – arbete hittills
Skriven den 3 november 2026. Detta är en sammanfattning i efterhand av mitt arbete hittills.

### Vad jag arbetade med
Jag har arbetat med order- och mailtjänsterna och med kopplingen mellan webbshoppens olika delar. I mailtjänsten har jag lagt till en RabbitMQ-listener för orderbekräftelser.

I frontend har jag konfigurerat Vitest och React Testing Library och skrivit tester för att ProductCard visar produkten och skickar rätt produkt vid klick. Jag har också arbetat med inloggnings- och utloggningsgränssnittet. Dessa frontendändringar har mergats.

Jag har undersökt Stripe Checkout, PayPal och Klarna och dokumenterat betalningsflödet. Därefter har jag arbetat med Stripe-integrationen och felsökt orderstatus efter betalning.

Jag har även arbetat med API Gateway, GitHub Actions, Docker och driftsättning på Render samt skrivit dokumentation för konfiguration och onboarding. Jag har också arbetat med README-filer för mikrotjänsterna.

### Eventuella problem och hur jag löste dem
Jag har stött på problem med CORS, inloggning och kommunikationen mellan tjänsterna. Jag har kontrollerat konfiguration och miljövariabler, testat anrop i Swagger och jämfört resultat med gruppen.

Ett problem var att en order fortfarande visades som pending i min lokala miljö efter en betalning. Jag tog upp detta med gruppen för fortsatt felsökning. Jag kunde då inte bekräfta att hela betalningsflödet fungerade lokalt.

Jag har lärt mig att skilja mellan att en enskild tjänst fungerar och att hela flödet fungerar tillsammans. Integrationen behöver också testas innan arbetet kan betraktas som färdigt.

### Samarbete och agilt arbete
Jag har deltagit i sprintplanering och Scrum Poker, där vi diskuterade arbetsmängd och osäkerhet innan vi uppskattade uppgifterna. Diskussionerna hjälpte oss att förstå uppgifterna och beroendena mellan dem.

Vi har använt Trello för att synliggöra arbetet. Jag har kommunicerat hinder och stämt av med Armin och Sofia när våra delar varit beroende av varandra.

Jag har även haft rollen som Scrum Master. Då förberedde jag en whiteboard med veckans arbete och uppmuntrade till dagliga avstämningar. Syftet var att upptäcka hinder tidigt och kunna anpassa arbetet mot sprintens mål.

Jag har skapat pull requests och granskat ändringar från andra i gruppen. Det har hjälpt mig att förstå helheten och bidragit till gemensam kvalitet i projektet.
