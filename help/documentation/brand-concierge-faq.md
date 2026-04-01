---
title: Vanliga frågor
description: Få svar på vanliga frågor om Adobe Brand Concierge.
role: User,Admin
level: Beginner
source-git-commit: 06911f38d17882cdae8441d5cbdbcdf786d9e6bb
workflow-type: tm+mt
source-wordcount: '1537'
ht-degree: 0%

---

# Frågor och svar

Här hittar du svar på vanliga frågor om Brand Concierge.

## Allmänt

### Varför använda Brand Concierge? Vilket problem löser det?

Mer forskning görs om externa AI-verktyg (till exempel ChatGPT, Gemini) i stället för om de finns på företagets webbplatser. Besökarna vill i allt högre grad&quot;komma till saken&quot;, till exempel&quot;Berätta för mig om X&quot;&quot;Kan jag göra Y?&quot; Brand Concierge hjälper er att hålla konversationen på er webbplats: när besökare landar på era sidor (även från en AI-assistent) kan de fortsätta konversationen med en assistent som är utbildad i ert innehåll. Ni levererar en enhetlig varumärkesupplevelse istället för att förlora dem till generiska svar någon annanstans.

### Hur skiljer sig Brand Concierge från chattbotar?

Brand Concierge skiljer sig från traditionella chattbottar genom att utnyttja generativ AI som är specifikt utbildad i organisationens innehåll och kunddata, i stället för att förlita sig på skriptade svar eller generiska webbresultat. Detta gör att assistenten kan ge personaliserade svar som bygger på kundbeteende, integrera med era Adobe-verktyg och -data, kontinuerligt lära sig av varje interaktion och tolka kundens avsikter på ett korrekt sätt utöver grundläggande nyckelordsmatchning.

### Kan jag använda Brand Concierge för både B2C och B2B?

Ja. Användningsexempel:

* **B2C:** Produktupptäckt, shoppinghjälp, kundsupport, personaliserade rekommendationer.
* **B2B:** Guidade utvärderingar, funktionsjämförelser, schemaläggning av möten, routning av säljare, rådgivande bokning.

### Vilka branscher kan använda Brand Concierge?

Brand Concierge kan användas i många olika branscher, bland annat detaljhandel och e-handel, resor och turism, finansiella tjänster, hälso- och sjukvård (med efterlevnadskontroller), media och underhållning samt teknik och programvara. I grund och botten kan alla branscher som hjälper kunderna att hitta information och fatta beslut dra nytta av att implementera Brand Concierge.

## Data och integritet

### Är kunddata säkra?

Ja. Brand Concierge ser till att kunddata är säkra genom att följa GDPR- och CCPA-regler, bearbeta data i Adobe säkra infrastruktur, ge dig kontroll över dataanvändningen och skydda konversationer genom kryptering och granskningsloggning.

Alla konversationer sker på dina egenskaper, inte på servrar från tredje part.

### Vilka datakällor kan jag ansluta?

Du kan ansluta följande typer av datakällor till Brand Concierge:

| Source-datatyp | Tillgängliga källor/information |
|------------------|---------------------------|
| **Produkt och innehåll** | Produktkataloger<br>Inventeringssystem<br>Knowledge Base och dokumentation<br>Webbplatsinnehåll via CSV URL-överföring<br>Adobe Experience Manager-innehåll<br>Adobe Commerce-data |
| **Kunddata** | Adobe Experience Platform-profiler<br>Adobe Analytics beteendedata<br>Första parts kundattribut<br>Tredjeparts-API:er (konfigurerade) |
| **CSV-filformat** | En kolumn som innehåller webb-URL:er<br>Brand Concierge crawlar URL:er och extraherar innehåll automatiskt<br>Bearbetning av statusuppdateringar i realtid<br>Flera CSV-filer kan överföras för olika innehållsområden |

Alla data följer era styrningsregler.

### Kan kunderna välja bort personalisering?

Ja. Kunder som avanmäler sig får användbara svar utan beteendeanpassning. Du konfigurerar hantering av avanmälan så att den matchar dina sekretesspolicyer.

### Finns det några konsekvenser för samtycke eller integritet?

Ja. **Konversationsdata:** Om konversationen innehåller personlig eller identifierbar information, insamling, lagring och användning måste uppfylla ditt samtycke och din sekretesspolicy (till exempel GDPR, CCPA). **Analys:** När Concierge skickar händelser till Experience Platform eller analyser kan dessa händelser omfattas av ditt befintliga samtycke och din befintliga styrning (till exempel medgivandesträngar, dataanvändningsetiketter). Vi rekommenderar att du behandlar Concierge som andra digitala upplevelser från första part: se till att webbplatsens medgivandebanderoll och inställningar täcker konversations- och chattdata och analyser, och anpassa händelsedata till din samtyckesstrategi. Granska lagar och regler innan du publicerar.

## Profiler och personalisering

### Använder Concierge kundprofiler (till exempel Real-Time CDP) för att anpassa svaren? Vad händer om besökaren är på väg genom en resa?

I det aktuella omfånget fokuserar Concierge på anonyma besökare: det är svar från konversationen och din kunskapsbas (webbplats och katalog), inte från en aktiv sökning efter identitet eller resestatus i Real-Time CDP. Färdkartor kan bland annat användas för näring av leads, överlämning till försäljning och återmarknadsföring, vilket kommer att ge mer uppmärksamhet åt kända profiler och resekontext. Anpassa svaren efter&quot;har den här besökaren en profil?&quot; eller &quot;var befinner de sig på en resa?&quot; är en framtida förbättring. För närvarande är upplevelsen densamma för anonyma besökare.

## Utrullning och tidslinje

### Hur lång tid tar det att leva?

Med parallellt arbete och aktivt samarbete kan många implementeringar bli verklighet på cirka 6-9 veckor. Mellanlagring kan börja snabbt när dina indata (URL:er, katalog, varumärkesriktlinjer) är klara. Efter avtal- och produktionskonfigurationen går du igenom kvalitetsjustering och en kontrollerad utrullning (till exempel 5 % och sedan skalas till 100 % på ungefär en vecka).

## Konfiguration och kontroll

### Hur kontrollerar jag varumärkesuttrycket?

Du kan styra varumärkesuttrycket direkt i användargränssnittet genom att konfigurera element som ton (från formell till tillfällig), språk (från enkel till teknisk) och personlighet (till exempel användbar, entusiastisk eller professionell). Dessutom kan ni definiera svarsmönster med hjälp av mallar och exempel, och upprätta skyddsmekanismer för att tillämpa regler och gränser för regelefterlevnad. Börja med Adobe referensfrågor och skräddarsy dessa inställningar så att de speglar ert varumärkes unika identitet.

### Vad händer när Brand Concierge inte kan besvara en fråga?

Du kan konfigurera reservbeteenden för att avgöra hur Brand Concierge svarar när det inte kan besvara en fråga. Det kan vara bra att visa meddelandet&quot;Jag kan inte hjälpa till med det&quot;, föreslå alternativa frågor, länka till självbetjäningsresurser eller automatiskt eskalera frågan till en handläggare. Välj vad som fungerar bäst för ert varumärke.

### Kan jag anpassa den visuella designen?

Ja. Anpassa alla visuella element, inklusive:

* Färger och varumärken
* Teckensnitt och typografi
* Knappformat
* Widgetplacering
* Kortlayouter
* Svarsformatering

SDK:er innehåller standardkomponenter och fullständiga anpassningsalternativ.

### Hur lång tid tar installationen?

Installationens längd kan bero på vilken typ av implementering du har. En grundläggande implementering som innehåller en befintlig produktkatalog, standardinnehåll för vanliga frågor och svar och standardinställningar kan ta ca 3-5 dagar att konfigurera. Å andra sidan kan avancerade implementeringar med anpassade integreringar, omfattande personalisering, komplexa arbetsflöden och anpassade efterlevnadsregler ta cirka 2-4 veckor att slutföra.

### Hur fungerar förhandsgranskning och testning?

Brand Concierge innehåller inbyggda testverktyg:

| Testverktyg | Funktioner |
|--------------|----------|
| **Förhandsgranskningsläge** | Simulera kundkonversationer<br>Justera inställningar i realtid<br>Se ändringarna direkt<br>Dela förhandsgranskningslänkar med teamet |
| **Testvy** | Klassificera svar med tummen upp/ned<br>Ge strukturerad feedback i 4 kategorier<br>Lägg till detaljerade kommentarer<br>Håll ordning på feedback i instrumentpanelen |

Alla tester utförs innan ni distribuerar till kunderna.

### Kan kunderna boka möten med vårt team?

Ja, kunderna kan schemalägga möten med ditt team med mötesbokningskunskaper. Aktivera funktionen genom att aktivera kunskapen i Kunskapskonfiguration, definiera aktiveringsmetoder (som&quot;tala med försäljning&quot;), ansluta kalendern eller schemaläggningssystemet och ange din tillgänglighet och mötestyper. När konfigurationen är klar kan kunderna begära möten under konversationer, och Brand Concierge underlättar schemaläggningsprocessen utan att de behöver lämna chatten.

### Vem hanterar promptkonstruktionen?

Adobe konsulter hanterar snabbkonstruktion i bakgrunden:

1. Du besvarar konfigurationsfrågor på sidan Kompetens.
1. Tillhandahåll produktkunskap, affärsregler och undvik nyckelord.
1. Skicka in dina indata.
1. Adobe konsulter använder dina svar för att ta fram optimerade instruktioner.
1. Ändringarna återspeglas automatiskt i ditt concierge.

På så sätt kan du vara säker på att ditt varumärke använder AI-promptmönster enligt god praxis, samtidigt som du behåller dina specifika varumärkeskrav.

## Märkesuttryck och -ton

### Om jag ställer in &quot;lekfull och entusiastisk&quot; i varumärkesuttrycket, kommer AI att göra det överdrivet?

Det kan det. Vissa kunder har rapporterat att AI tenderar att överdriva entusiasmen när det är inställt på&quot;lekfull och entusiastisk&quot;, till exempel dubbla utropstecken eller starka superlativ. För reglerade eller medicinska målgrupper (till exempel farma, näring i tidig tillvaro) rekommenderar vi att ni dämpar entusiasm och lekhet samtidigt som tonen förblir konversativ och vardaglig. Använd måttliga inställningar och justera baserat på feedback. För reglerade branscher väljer du&quot;konversationsläge&quot; istället för&quot;entusiastisk&quot;.

## Prestanda och analys

### Hur mäter jag framgång?

Du kan mäta framgång med Brand Concierge Dashboard. Använd kontrollpanelen för att spåra mätvärden som:

| Mått | Vad det spårar |
|--------|----------------|
| **Förlovning** | Konversationsvolym, sessionslängd |
| **Nöjd** | Känslighetspoäng, feedback-betyg |
| **Konvertering** | Inköpsbelopp för assisterade jämfört med icke-assisterade |
| **Ämnen** | De vanligaste frågorna |
| **Leverans** | Eskaleringsgrad och orsaker |
| **Prestanda** | Svarsnoggrannhet, lösningstid |

Ni kan också integrera med Adobe Analytics för djupare analyser.

### Vad ska jag göra om känslan faller?

Om du märker en minskning av känslan bör du undersöka de underliggande orsakerna genom att granska nyligen misslyckade frågor, kontrollera om det finns innehållsluckor, analysera negativ feedback, testa lämpliga toner och verifiera tekniska problem. När rotorsakerna har identifierats kan du snabbt åtgärda dem och fortsätta att övervaka dem för förbättring.

## Integrering och teknik

### Behöver jag andra Adobe-produkter?

Nej, men de förbättrar prestandan:

| Integrationsalternativ | Funktioner |
|-------------------|--------------|
| **Fristående** | Fungerar med produktkatalogen och -innehållet |
| **Med Adobe Experience Platform** | Enhetliga kundprofiler<br>Avancerad personalisering<br>Konsekvens över flera kanaler |
| **Med Adobe Commerce** | Realtidslager<br>Orderhistorik<br>Kundintegrering |
| **Med Adobe Experience Manager** | Innehållshantering<br>Dynamiska uppdateringar<br>Stöd för flera webbplatser |

### Vad händer om min webbplats inte finns på Adobe?

Brand Concierge fungerar med alla plattformar. JavaScript SDK kan integreras med alla webbplatser och SDK:er för mobiler fungerar med alla appar.

### Hur fungerar överlämningen?

När agentöverföringen aktiveras överför Brand Concierge hela konversationshistoriken, kundprofilen och ID:t, identifierad avsikt, information om produkter som diskuterats och eventuella lösningsförsök till agenten. Detta garanterar att agenterna har ett fullständigt sammanhang och kan fortsätta konversationen utan att kunderna behöver upprepa informationen.

### Kan jag stödja flera språk?

Ja. Konfigurera språkstöd per assistent baserat på kundbas. Brand Concierge identifierar kundens språk och svarar därefter.
