---
title: Produktdokumentation
description: Lär dig hur du konfigurerar och använder nyckelfunktioner i Brand Concierge.
role: User,Admin
level: Beginner
source-git-commit: 2c3f3d009d8fef3eaf5bf32d73672eeda7ba05c8
workflow-type: tm+mt
source-wordcount: '1739'
ht-degree: 0%

---

# Hjälp om Brand Concierge

Lär dig hur du konfigurerar och använder nyckelfunktioner i Brand Concierge. Hitta svar på vanliga frågor om konfiguration, dataintegrering, sekretess, anpassning, prestandamätning och tekniska krav.

## Viktiga funktioner {#key-features}

Brand Concierge har ett antal viktiga funktioner:

* **Guided onboarding (Guided onboarding):** Följ en stegvis konfiguration för kunskaper, färdigheter och varumärkesuttryck.
* **Kunskapsintegrering:** Överför och hantera källor som CSV-filer med webbplatslänkar.
* **Konfigurera kunskaper** Integrera kompetenser som produktrådgivning.
* **Kontrollera branding:** Justera röst, ton och svarslängd så att de uppfyller varumärkets standard och strategi.
* **Förhandsgranska och iterera:** Använd ett omfattande förhandsvisningsgränssnitt för att simulera konversationer och utföra live-justeringar.
* **Feedback-system:** Använd ett feedbacksystem som gör att användare kan ange upp- eller nedgraderingar av tummar, tillsammans med detaljerade feedbackformulär som omfattar svarstäckning, ton, kvalitet och funktioner.
* **Kontrollpanel för analys:** Dra nytta av en kontrollpanel för analys som drivs av Customer Journey Analytics för mätvärden som konversationer, känslor och engagemang.

## Kom igång {#getting-started}

Du kommer åt Brand Concierge från Adobe Experience Cloud kontrollpanel. På en hög nivå utför du följande uppgifter på genomgången av startsidan:

1. [Skapa ett koncierge](#homepage)
1. [Lägg till kunskapskällor](#knowledge-sources)
1. [Konfigurera färdigheter](#skills-configuration)
1. [Ange ditt varumärkesuttryck](#brand-expression).

Om du vill se en självstudiekurs (video) kan du gå till [Skapa din första konferens](../getting-started/create-first-concierge.md)

I följande avsnitt beskrivs varje uppgift och gränssnittsalternativen i detalj.

## Skapa ett koncierge {#homepage}

Brand Concierge hemsida är utformad för att vara enkel att använda och effektiv och vägleder dig genom viktiga installationssteg med en dedikerad förstagångsgenomgång. En framträdande banderoll beskriver viktiga åtgärder som att specificera konferensens namn och syfte, lägga till kunskapskällor, konfigurera relevanta färdigheter och definiera ert varumärkesuttryck.

Medan du går visar en visuell spårare tydligt vilka installationskomponenter som har slutförts och alla återstående uppgifter markeras. För att ytterligare stödja dina satsningar har hemsidan ett inspirerande avsnitt med videor och demonstrationer av sammankopplingsfunktioner, som produktrekommendationer. Du har också snabb tillgång till Experience League-dokumentation för mer ingående tekniska insikter.

När konfigurationen är klar ger en konfigurationssammanfattning en heltäckande bild av dina detaljer, som ordnas med flikar för att underlätta pågående justeringar och förbättringar.

**Nyckelelement**

* **Första gången användaren går igenom**: En översta banderoll med steg för att konfigurera ditt koncierge (namn/syfte, kunskapskällor, kunskaper, varumärket).
* **Progress Tracker**: Visuella indikatorer för slutförda kontra väntande installationskomponenter.
* **Inspirationsavsnittet**: Videor och demonstrationer som visar sammankopplingsfunktioner (t.ex. produktrekommendationer).
* **Dokumentationslänkar**: Snabb åtkomst till Experience League-resurser för djupare tekniska insikter.
* **Konfigurationssammanfattning**: Vy efter konfiguration med alla detaljer, med flikar för förfining.

**Så här skapar du en konversation**

1. Navigera till genomsökningsbanderollen och klicka sedan på **[!UICONTROL Get started]**.
1. Ange ett namn för ditt concierge och definiera dess syfte (till exempel _Rekommendera personaliserade produkter_).
1. Följ de guidade stegen för att fortsätta.
1. När konfigurationen är klar går du tillbaka till startsidan för att övervaka eller redigera ditt medlemskap.

>[!TIP]
>
>Brand Concierge sparar automatiskt förloppet. En ofullständig konfiguration kan begränsa funktionaliteten, men kommer inte att blockera några försök att förhandsgranska.

### Kunskapskällor {#knowledge-sources}

[!UICONTROL Knowledge Sources] hjälper dig att hantera de datakällor som ligger till grund för konferensens svar. Du kan komma åt [!UICONTROL Knowledge Sources] när du har överfört dina initiala filer. [!UICONTROL Knowledge Sources] har ett antal nyckelelement att tänka på, till exempel:

* **Source-lista:** Visar alla överförda objekt, t.ex. CSV-filer med webbplatslänkar, och anger att de har statusen antingen bearbetad eller väntande.
* **Överföringsgränssnitt:** Gör att du kan dra och släppa eller bläddra efter CSV-filer som innehåller URL:er, som systemet crawlar för att extrahera kunskap.
* **Anslutningsalternativ:** Gör det möjligt att länka specifika kunskapskällor till relevanta kunskaper för mer målinriktad användning.

**Lägga till en kunskapskälla**

1. Klicka på **[!UICONTROL Knowledge Sources]** på startsidan.

1. Namnge kunskapskällan.

1. Klicka på **[!UICONTROL Add]** om du vill överföra en CSV-fil.

   Kontrollera att den innehåller en kolumn för webbplatsens URL:er.

1. Bearbetningen kan ta en stund.

   Det här steget löser sig ganska snabbt när status uppdateras i realtid.

1. Återgå till startsidan när du har lagt till den.

   Nu ska du se den nya källan som lagts till på hemsidan.

   Använd hemsidan för att redigera eller ta bort dina kunskapskällor efter behov. Du kan även koppla en kunskapskälla om det sker några ändringar.

### Konfigurera färdigheter {#skills-configuration}

Använd gränssnittet [!UICONTROL Skills Configuration] för att forma konciergans expertis genom att konfigurera kunskaper som **produktrådgivning**. Svara på enkäten för att ange indata som Adobe konsulter senare kommer att använda för snabb konstruktion. Kompetenskonfiguration har ett antal nyckelelement att tänka på, som:

* **Kompetensväljare:** Du kan välja bland tillgängliga kunskaper, t.ex. produktrådgivning, för att göra produktrekommendationer.
* **Frågeformulär:** Du kommer att slutföra en serie uppmaningar om att tillhandahålla produktkunskap, affärsregler, nyckelord som ska undvikas och källanslutningar.
* **Förhandsgranska:** Du kan välja att göra live-förbättringar och se hur dina justeringar påverkar svaren, med länkar till förhandsgranskningssidan.
* **Aktivera mötesbokning:** Du kan göra det möjligt för besökare att schemalägga möten direkt med företagsrepresentanter.

**Konfigurera kunskaper**

1. Navigera till förloppsspåraren på hemsidan och klicka sedan på **[!UICONTROL Configure skills]**.
1. Välj en kompetens (t.ex. produktrådgivning).
1. Svara på de konfigurationsfrågor som följer.

   Frågeexempel inkluderar: _Vad bör koncierge känna till om produkter?_, _Vilka affärsregler ska följas?_, _Vilka nyckelord ska undvikas?_

1. Anslut relevanta [kunskapskällor](#knowledge-sources).
1. Aktivera ytterligare funktioner (mötesbokning).
1. Skicka för behandling.

### Märkesuttryck {#brand-expression}

Du kan använda gränssnittet _[!UICONTROL Brand expression]_för att anpassa personligheten och stilen för ditt koncierges svar. Du kan komma åt Varumärkesuttryck från konfigurationsfaserna eller via sidofältet för förhandsgranskning för pågående ändringar.

Med Varumärkesuttryck kan du använda skjutreglage för att anpassa röstinställningar och toninställningar för ditt varumärke. Du kan välja mellan alternativ som &quot;Egen&quot;, &quot;Professionell&quot; och &quot;Energetisk&quot;. Dessutom kan du konfigurera svarstiderna efter dina önskemål. Du kan ställa in ditt medgivande så att det returnerar korta, medelstora eller långa utdata, beroende på varumärkets vision.

**Anpassa varumärkesuttrycket**

1. Klicka på **[!UICONTROL Customize Brand Expression]** på startsidan.
2. Konfigurera därefter varumärkets röst, ton och önskad svarslängd.
3. Välj **[!UICONTROL Save]** för att se till att ändringarna återspeglas i framtida svar.

### Förhandsgranska och testa {#preview-and-test}

Testa ditt konferenssamtal innan du startar för kunderna med hjälp av förhandsgransknings- och testvyn.

>[!BEGINTABS]

>[!TAB Förhandsgranskningsläge]

Använd förhandsgranskningsläget för att simulera konversationer och samtidigt göra justeringar i realtid.

1. Efter konfigurationen går du tillbaka till startsidan och klickar på **[!UICONTROL Preview]**.
1. Använd chattgränssnittet för att ange din fråga (till exempel _Rekommendera en bärbar dator under 1 000 USD_).
1. Granska concierge-svar.
1. Använd den högra panelen för att justera varumärkesuttrycksinställningarna.
1. Klicka på **[!UICONTROL Share]** om du vill generera en länk för teamfeedback.

>[!TAB Testvyn]

Använd testvyn för att samla in strukturerad feedback om prestanda och simulera slutanvändarupplevelsen.

1. Klicka på **[!UICONTROL Tester View]** i förhandsgranskningen.
1. Använd testvyn för att simulera slutanvändarkonversationer.
1. Använd reglaget uppåt och nedåt för att betygsätta varje svar du får.
1. Fyll i feedbackformulär för att dra ner tummen:
   **Svarstäckning:** Åtgärdade den avsikten?
   **Varumärkeston:** Justerad med personlighet?
   **Svarskvalitet:** Vill du rensa och strukturera?
   **Svarsfunktioner:** Användbara uppföljningar?
1. Lägg till kommentarer och specifika kommentarer.
1. Skicka feedback för granskning på kontrollpanelen.

>[!ENDTABS]

### Feedback {#feedback}

Efter testningen kan du använda fliken för feedback på hemsidan för att ge feedback och detaljerade granskningar.

I avsnittet med feedback finns flera viktiga funktioner som du kan använda för att övervaka och utvärdera dina Brand Concierge prestanda. Följande element är tillgängliga:

* **Prestandaögonblicksbild:** Visar kort som sammanfattar nyckeltal, inklusive totalt antal konversationer, unika användare, känslouttrender och engagemangsfrekvens.
* **Visa rapportknapp:** Gör att du kan öppna en instrumentpanel som drivs av Customer Journey Analytics för djupgående åtkomst till avancerade analyser och prestandamått.
* **Feedbacklista:** Visar en tabell med feedbacksessioner. Du kan klicka på enskilda rader för att visa hela chattutskriften för varje session.
* **Panelen Feedback:** Visar klassificeringskort på den högra sidan av gränssnittet. Genom att hovra över eller klicka på dessa kort markeras de relevanta delarna av chattutskriften för enkel referens.

**Om du vill skicka feedback**

1. Gå till Brand Concierge hemsida och välj **[!UICONTROL Feedback]**.
1. Använd den angivna ögonblicksbilden för att visa information om trender på hög nivå.
1. Om du vill få åtkomst till en djupdykning som drivs av Customer Journey Analytics väljer du **[!UICONTROL View Report]**.
1. Du kan även kontrollera panelen för att få ytterligare kopplad feedback.
1. När du är klar kan du exportera insikterna och använda dem senare och förfina arbetsflödet.

### Konfigurationer {#configurations}

Fliken _[!UICONTROL Configurations]_är en skrivskyddad sammanfattningsvy som du kan använda för att granska ditt koncierges fullständiga inställningar. Detta speglar startsidan direkt efter att den första konfigurationen har slutförts och ger en sammanfattning av dina uppgifter, kunskapskällor, kunskaper och konfigurerade varumärkesuttryck. Du kan använda den här funktionen som referens innan du förhandsgranskar eller delar ditt koncierge.

## Vad du kan göra med Brand Concierge

Läs mer om kundfunktioner, affärsmöjligheter och användningsexempel för Brand Concierge.

### Kundfunktioner

Brand Concierge har ett konversationsgränssnitt där kunderna kan hitta produkter, jämföra alternativ och få svar på sitt eget språk. Med personaliserade rekommendationer, omfattande produktjämförelser och möjlighet att eskalera till en medarbetare får kunderna en smidig och intuitiv upplevelse. Interaktionen är flexibel - kunderna kan använda text, röst eller bilder - och varje svar baseras på varumärkesets pålitliga dokumentation och kundsammanhang.

* Ställ frågor på ett naturligt språk och få personaliserade rekommendationer.
* Jämför produkter sida vid sida med visuella skärmar.
* Få svar från varumärkesdokumentationen.
* Växla till en live-agent med fullständig konversationshistorik.

### Affärsfunktioner

Brand Concierge ger företag avancerade konversationsbaserade AI-funktioner för kundengagemang. Det hjälper varumärken att öka konverteringsgraden genom att vägleda kunderna till rätt produkter, minskar supportkostnaderna genom snabba, korrekta svar och säkerställer en enhetlig varumärkesröst och regelefterlevnad. Brand Concierge optimerar både kundupplevelsen och företagsprestanda med hjälp av effektiva analysfunktioner, smidig AI-to-human-hantering och djupgående Adobe-integreringar.

* Vägled kunderna till rätt produkter för att öka konverteringsgraden.
* Minska supportkostnaderna med snabba och exakta svar.
* Styr kraven på varumärkesröst, ton och efterlevnad.
* Spåra prestanda med Customer Journey Analytics Dashboard.
* Möjliggör smidig AI-till-människa-hantering, inklusive schemaläggning av möten.
* Integrera med Adobe Experience Platform och Experience Manager.

## Användningsfall

Brand Concierge har stöd för användning både inom B2C och B2B i flera branscher.

| Bransch | Användningsfall |
|---|---|
| Detaljhandel och e-handel | Kunderna kan identifiera produkter och få personaliserade rekommendationer. Brand Concierge ger vägledning om storlek och anpassning, hjälper användarna att hitta lämpliga gåvor och matchar format eller inställningar baserat på kundindata. |
| B2B-försäljning | Brand Concierge guidar kunderna genom produktutvärderingar, erbjuder detaljerade funktioner och prisjämförelser, hjälper till med planeringen av säljmöten och tillhandahåller branschspecifika rekommendationer som är skräddarsydda för företagskunder. |
| Kundsupport | Användare kan få svar direkt från kunskapsbasen. Brand Concierge tillhandahåller information om policyer och procedurer, hjälper till att felsöka problem och tillhandahåller uppdateringar om orderstatus och spårning. |
| Resor och turism | Kunderna får skräddarsydda rekommendationer, hjälp med planeringsvägar, support under hela bokningsprocessen samt svar på resepolicyfrågor. |
| Finansiella tjänster | Brand Concierge erbjuder produktjämförelser för att hjälpa kunderna att välja rätt finansiella lösningar, tillhandahålla kontoinformation, tillhandahålla efterlevnadsstyrd vägledning och möjliggöra schemaläggning med finansiella rådgivare. |

