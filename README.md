[Klart — her får du **punkt 3, 4 og 5 skrevet på nytt**, nå **på norsk**, men med **delen til person 4 på engelsk**, slik du ba om.
Jeg hopper over punkt 6, 7 og 8.

Jeg bygger dette på strukturen dere faktisk har i rapporten: **4.1 Kravliste**, **4.2 Use Case-diagram**, og **4.3 Use Case beskrivelser, DFD-fragmenter og Datakatalog**. Det er også samme hovedstruktur som i eksempelet fra 2024. Prosjektet deres er en **digital plattform for korttidsleie av boliger**, der verter legger ut eiendommer og gjester søker og bestiller, så presentasjonen bør følge akkurat denne logikken.

---

# 3. Detaljert fordeling av presentasjonen på 4 personer

Jeg anbefaler en presentasjon på **14–15 slides** totalt, slik at dere rekker alt på **20 minutter** uten å stresse.

## Tidsfordeling

* **Person 1**: 4 minutter
* **Person 2**: 4 minutter
* **Person 3**: 5 minutter
* **Person 4**: 6 minutter
* ca. **1 minutt buffer** til overgang eller spørsmål underveis

## Hvem gjør hva

### Person 1

Ansvar:

* intro
* kort forklaring av prosjektet
* kravliste
* overgangen fra krav til modeller

### Person 2

Ansvar:

* use case-diagrammet
* aktørene
* hovedområdene i systemet

### Person 3

Ansvar:

* use case descriptions
* én enkel use case
* én mer kompleks use case

### Person 4

Ansvar:

* DFD-fragment
* Data Catalog
* sammenhengen mellom use case, dataflyt og datalager
* teknisk oppsummering

---

# 4. Presentasjonen slide for slide – veldig detaljert

---

## Slide 1 — Forside

### Tittel på slide

**Home Rentals – Systemanalyse**

### Hva som skal stå på slide

```text
Home Rentals – Systemanalyse
SYS1000 – Systemutvikling
Gruppe 07

Presentasjonen dekker:
• Kravliste
• Use Case-diagram
• Use Case-beskrivelser
• DFD-fragmenter
• Datakatalog
```

### Hvilket bilde dere bør bruke

* en enkel forside med hus/booking-ikon
* eller et skjermbilde fra forsiden/designet deres
* eller et enkelt “Home Rentals”-layout

### Hvem snakker

**Person 1**

### Hva personen skal si

> Hei, vi er Gruppe 07, og vi skal presentere analysedelen av prosjektet vårt, Home Rentals.
> Home Rentals er en digital plattform for korttidsleie av boliger.
> I denne presentasjonen skal vi vise hvordan vi har arbeidet med kravliste, use case-diagram, use case-beskrivelser, DFD-fragmenter og datakatalog.

### Tips

Dette skal være rolig og kort, rundt 20–30 sekunder.

---

## Slide 2 — Hva slags system utvikler vi?

### Tittel på slide

**Hva slags system utvikler vi?**

### Hva som skal stå på slide

```text
Home Rentals:
• Digital plattform for korttidsleie
• Vert legger ut bolig
• Gjest søker og bestiller
• Systemet støtter hele prosessen fra søk til formidling
```

### Hvilket bilde dere bør bruke

* et skjermbilde av en annonseoversikt
* eller et skjermbilde av boligdetaljer
* gjerne noe som viser både “vert”- og “gjest”-siden visuelt

### Hvem snakker

**Person 1**

### Hva personen skal si

> Prosjektet vårt handler om å utvikle et system for korttidsutleie av boliger.
> Ideen er at verter kan legge ut eiendommer for leie, mens gjester kan søke etter boliger, se detaljer og sende bestilling eller forespørsel.
> Målet er å gjøre hele prosessen enkel, oversiktlig og brukervennlig.

### Ekstra replikk

> Med andre ord er dette ikke bare en nettside med annonser, men et system som også støtter registrering, oppdatering og formidling.

---

## Slide 3 — Kravliste

### Tittel på slide

**Kravliste: grunnlaget for analysen**

### Hva som skal stå på slide

Lag to kolonner.

**Venstre side:**

```text
Funksjonelle krav (FR)
• Vertshåndtering
• Gjestehåndtering
• Annonsehåndtering
• Formidling
```

**Høyre side:**

```text
Ikke-funksjonelle krav (NFR)
• Nettbasert løsning
• Responsivt design
• Sikkerhet og innlogging
• Ytelse og brukervennlighet
• Tilpasning til Norge
```

### Nederst på slide – konkrete eksempler

```text
Eksempler:
• FR 1.1 Registrering av vert
• FR 3.2 Visning av annonse
• FR 4.1 Formidling av eiendom til gjest
• NFR 3.2 Systemet skal kreve innlogging for registrering og oppdatering av data
```

### Hvilket bilde dere bør bruke

* et lite skjermbilde av kravlisten deres
* eller små ikoner som viser funksjonelle og ikke-funksjonelle krav

### Hvem snakker

**Person 1**

### Hva personen skal si

> Kravlisten er grunnlaget for hele analysen.
> Her beskriver vi både hva systemet skal gjøre, og hvilke kvalitetskrav det må oppfylle.
> De funksjonelle kravene i vårt prosjekt er delt inn i fire hovedområder: vertshåndtering, gjestehåndtering, annonsehåndtering og formidling.
> De ikke-funksjonelle kravene handler blant annet om sikkerhet, ytelse, brukervennlighet og at systemet skal fungere godt i en norsk kontekst.

### Fortsettelse

> For eksempel har vi krav om registrering av vert, visning av annonse og formidling av eiendom til gjest.
> Samtidig har vi krav om at systemet skal være nettbasert, responsivt og kreve innlogging for registrering og oppdatering av data.

---

## Slide 4 — Fra krav til modeller

### Tittel på slide

**Fra krav til modeller**

### Hva som skal stå på slide

```text
Kravliste
↓
Use Case-diagram
↓
Use Case-beskrivelser
↓
DFD-fragmenter
↓
Datakatalog
```

### Hvilket bilde dere bør bruke

* en enkel pilmodell eller prosesslinje
* ikke overfyll denne sliden

### Hvem snakker

**Person 1**

### Hva personen skal si

> Vi jobbet ikke med disse delene som separate elementer.
> Vi startet med kravlisten, og brukte den som utgangspunkt for use case-diagrammet.
> Deretter beskrev vi hver use case i detalj, før vi laget DFD-fragmenter for å vise dataflyten.
> Til slutt laget vi datakatalogen for å forklare hva dataflytene og datalagrene faktisk inneholder.

### Overgang til neste person

> Nå går vi videre til use case-diagrammet, som viser den overordnede funksjonsstrukturen i systemet.

---

## Slide 5 — Use Case-diagram

### Tittel på slide

**Use Case-diagram**

### Hva som skal stå på slide

* bruk et stort og tydelig bilde av hele use case-diagrammet
* ha bare litt støttetekst nederst:

```text
To hovedaktører:
• Gjest (bruker)
• Vert (utleier)

Use casene dekker:
• registrering
• visning og oppdatering
• annonser
• formidling
```

### Hvem snakker

**Person 2**

### Hva personen skal si

> Use case-diagrammet gir den overordnede oversikten over systemet.
> Det viser hvilke aktører vi har, og hvilke funksjoner de kan bruke.
> I vårt system har vi to hovedaktører: gjest og vert.
> Diagrammet viser også at funksjonene er gruppert i flere områder, som registrering, profilhåndtering, annonser og formidling.

### Ekstra replikk

> Use case-diagrammet viser ikke detaljene i hver funksjon, men det viser hele funksjonskartet til systemet.

---

## Slide 6 — Aktører og hovedområder

### Tittel på slide

**Aktører og hovedområder i systemet**

### Hva som skal stå på slide

Lag to blokker.

**Venstre blokk:**

```text
Gjest:
• registrere seg
• se og oppdatere profil
• søke og vise annonser
• sende bestilling / forespørsel
```

**Høyre blokk:**

```text
Vert:
• registrere seg
• se og oppdatere profil
• registrere og oppdatere annonse
• oppdatere formidlingsstatus
```

### Hvilket bilde dere bør bruke

* to ikoner: én for gjest, én for vert
* eller en zoomet del av use case-diagrammet med markering rundt aktørene

### Hvem snakker

**Person 2**

### Hva personen skal si

> Gjesten er brukeren som søker etter bolig, ser detaljer, velger datoer og sender bestilling eller forespørsel.
> Verten er brukeren som oppretter og administrerer egne annonser, og som senere kan oppdatere status på formidlingen.
> Denne rollefordelingen er viktig, fordi den påvirker både use case-beskrivelsene og DFD-fragmentene våre.

### Overgang til neste person

> Når vi vet hvilke funksjoner systemet har, kan vi gå dypere inn i hvordan hver enkelt funksjon beskrives.

---

## Slide 7 — Use Case Description

### Tittel på slide

**Use Case Description: hvordan én funksjon beskrives**

### Hva som skal stå på slide

```text
Hver use case-beskrivelse inneholder:
• Use case navn og ID
• Aktør
• Trigger
• Preconditions
• Hoved flyt
• Postconditions
```

### Hvilket bilde dere bør bruke

* et skjermbilde av en faktisk use case-tabell fra rapporten
* bruk helst en som er lett å lese, for eksempel UC-1 eller UC-4

### Hvem snakker

**Person 3**

### Hva personen skal si

> En use case-beskrivelse går ett nivå dypere enn use case-diagrammet.
> Her beskriver vi én konkret funksjon steg for steg.
> Vi viser hvem som starter funksjonen, hva som utløser den, hvilke forutsetninger som må være oppfylt, hvordan hovedflyten går, og hva resultatet er etterpå.

### Ekstra replikk

> På denne måten blir systemfunksjonene konkrete og lettere å modellere videre.

---

## Slide 8 — Eksempel på enkel use case

### Tittel på slide

**Eksempel: UC-1 Registrering av vert**

### Hva som skal stå på slide

```text
Aktor:
• Potensiell vert

Trigger:
• ønsker å opprette vertskonto

Hovedlogikk:
1. brukeren oppgir informasjon
2. systemet validerer dataene
3. systemet oppretter bruker
4. systemet oppretter vertsprofil
5. systemet bekrefter registreringen
```

### Hvilket bilde dere bør bruke

* skjermbilde av UC-1-tabellen
* eventuelt lite skjermbilde av UC-1-design dersom det ser ryddig ut

### Hvem snakker

**Person 3**

### Hva personen skal si

> Her ser vi et eksempel på en enkel use case, nemlig registrering av vert.
> Denne use casen starter når en potensiell vert ønsker å opprette konto.
> Brukeren fyller inn informasjon, systemet validerer dataene, oppretter bruker og deretter vertsprofil.
> Til slutt får brukeren en bekreftelse.

### Poeng å fremheve

> Dette er et godt eksempel på en enkel og grunnleggende funksjon i systemet.

---

## Slide 9 — Eksempel på kompleks use case

### Tittel på slide

**Eksempel: UC-10 Formidling av eiendom til gjest**

### Hva som skal stå på slide

```text
Aktor:
• Gjest

Hovedlogikk:
1. velge annonse
2. angi datoer og antall gjester
3. kontrollere tilgjengelighet
4. beregne totalpris
5. opprette formidling
6. vise bekreftelse
```

### Hvilket bilde dere bør bruke

* skjermbilde av UC-10-tabellen
* eller skjermbildet fra design for UC-10

### Hvem snakker

**Person 3**

### Hva personen skal si

> Denne use casen er mer kompleks enn registrering av vert.
> Her velger gjesten en annonse, oppgir datoer og antall gjester, og systemet kontrollerer om oppholdet er mulig.
> Deretter beregner systemet totalpris og oppretter en formidling.
> Til slutt får brukeren en bekreftelse.
> Dette er derfor en tydelig forretningstransaksjon i systemet.

### Overgang til neste person

> Når use casen er beskrevet i tekst, kan vi modellere hvordan data faktisk beveger seg i systemet. Derfor går vi nå videre til DFD-fragmentene.

---

## Slide 10 — Fra Use Case til DFD

### Tittel på slide

**Fra use case til DFD-fragment**

### Hva som skal stå på slide

```text
Use Case Description → DFD Fragment

Vi oversetter:
• aktør → external entity
• handling → prosess
• lagring → datalager
• informasjonsutveksling → dataflyt
```

### Hvilket bilde dere bør bruke

* enkel illustrasjon med én aktør, én prosess, ett datalager og én pil
* eller et lite fragment fra deres egen rapport

### Hvem snakker

**Person 4**

### What this person should say

> In the next step, we translate the textual use case into a DFD fragment.
> The actor becomes an external entity, the action becomes a process, stored information becomes data stores, and the communication between them becomes data flows.
> This makes the analysis more technical and helps us understand how information moves through the system.

---

## Slide 11 — Enkel DFD

### Tittel på slide

**DFD-eksempel: UC-1 Registrering av vert**

### Hva som skal stå på slide

```text
External entity:
• Potensiell vert

Prosess:
• Registrere vert

Datalager:
• Brukere
• Verter

Dataflyt:
• Ny bruker
• Ny vert
• Tilbakemelding
```

### Hvilket bilde dere bør bruke

* skjermbilde av UC-1-fragmentet

### Hvem snakker

**Person 4**

### What this person should say

> This is an example of a simple DFD fragment.
> The potential host sends information into the process “Registrere vert”.
> The process stores data in two data stores: one for the user account and one for the host profile.
> Finally, the system returns feedback to the user.
> This shows a basic and easy-to-follow data flow.

---

## Slide 12 — Kompleks DFD

### Tittel på slide

**DFD-eksempel: UC-10 Formidling**

### Hva som skal stå på slide

```text
Flere datalager:
• Gjester
• Annonser
• Boliger
• Bestillinger
• Formidlinger

Viser en faktisk transaksjon:
• kontroll av datoer
• totalpris
• ny formidling
```

### Hvilket bilde dere bør bruke

* skjermbilde av UC-10-fragmentet

### Hvem snakker

**Person 4**

### What this person should say

> Here we see a more complex DFD fragment.
> In this use case, the system has to read data from several data stores at the same time.
> It needs guest data, listing data, housing data and booking data before it can create a new mediation record.
> This is a good example of how a business transaction becomes more detailed in the data flow model.

---

## Slide 13 — Data Catalog

### Tittel på slide

**Datakatalog: ordboken til DFD**

### Hva som skal stå på slide

```text
Datakatalog forklarer:
• hva hver dataflyt inneholder
• hva hvert datalager inneholder

Eksempel:
Ny bruker = e-postadresse + passord
Brukere = bruker ID + e-postadresse + passord + registreringsdato + oppdateringsdato
```

### Hvilket bilde dere bør bruke

* et tydelig skjermbilde av datakatalogen
* gjerne en enkel og en mer kompleks variant

### Hvem snakker

**Person 4**

### What this person should say

> The data catalog is the dictionary of the DFD.
> It explains exactly what each data flow contains and what each data store contains.
> Without the data catalog, the DFD would be much less precise.
> It is the data catalog that makes the model unambiguous and technically clear.

---

## Slide 14 — Hvordan alt henger sammen

### Tittel på slide

**Hvordan krav, use case og dataflyt henger sammen**

### Hva som skal stå på slide

```text
FR 4.1
↓
UC-10 Formidling av eiendom til gjest
↓
Use Case-beskrivelse
↓
DFD-fragment
↓
Datakatalog
```

Og ved siden av:

```text
Resultat:
• krav blir konkret funksjon
• funksjon blir tekstlig scenario
• scenario blir dataflyt
• dataflyt blir definert i datakatalog
```

### Hvilket bilde dere bør bruke

* ingen stor grafikk nødvendig
* bare en ren, tydelig modell

### Hvem snakker

**Person 4**

### What this person should say

> This slide shows the most important relationship in the analysis.
> We start with a requirement, for example that a guest must be able to send a booking request.
> Then we turn that requirement into a use case.
> The use case is described step by step in a table.
> After that, we model the data flow in a DFD fragment.
> Finally, the data catalog defines exactly what the data means.
> This is how the whole analysis becomes connected and traceable.

---

## Slide 15 — Oppsummering

### Tittel på slide

**Oppsummering**

### Hva som skal stå på slide

```text
Vi har vist:
• kravene til systemet
• aktører og funksjoner
• hvordan use cases beskrives
• hvordan data flyter i systemet
• hvordan datakatalogen gjør modellen presis

Takk for oss
```

### Hvilket bilde dere bør bruke

* ren avslutningsslide
* eventuelt et lite bilde med hus/booking-ikon

### Hvem snakker

**Person 1** eller alle sammen veldig kort

### Hva som skal sies

> Oppsummert har vi gått fra krav til modeller.
> Vi har først definert hva systemet skal gjøre, deretter vist hvem som bruker funksjonene, hvordan funksjonene beskrives steg for steg, hvordan data flyter, og til slutt hva dataene faktisk består av.
> Takk for oss. Vi er klare for spørsmål.

---

# 5. Hva hver person konkret skal forberede

## Person 1

Denne personen skal forberede:

* Slide 1
* Slide 2
* Slide 3
* Slide 4

Denne personen må kunne:

* forklare hva Home Rentals er
* forklare forskjellen mellom funksjonelle og ikke-funksjonelle krav
* trekke fram 2–3 konkrete krav fra prosjektet
* forklare hvorfor kravlisten er utgangspunktet for resten av analysen

Denne personen må huske å si:

> Kravlisten er grunnlaget for hele modellen vår.

---

## Person 2

Denne personen skal forberede:

* Slide 5
* Slide 6

Denne personen må kunne:

* forklare use case-diagrammet
* peke ut aktørene
* forklare hvilke hovedoppgaver gjest og vert har
* vise hvordan use casene er gruppert

Denne personen må huske å si:

> Use case-diagrammet gir oversikten, men ikke detaljene.

---

## Person 3

Denne personen skal forberede:

* Slide 7
* Slide 8
* Slide 9

Denne personen må kunne:

* forklare hva en use case-beskrivelse er
* lese en use case-tabell riktig
* forklare forskjellen mellom en enkel og en kompleks use case
* bruke UC-1 og UC-10 som hovedeksempler

Denne personen må huske å si:

> Use case-beskrivelsen er bindeleddet mellom krav og teknisk modellering.

---

## Person 4

This person should prepare:

* Slide 10
* Slide 11
* Slide 12
* Slide 13
* Slide 14

This person should be able to explain:

* what a DFD fragment is
* how it is created from a use case
* the difference between a simple and a complex DFD
* what the data catalog does
* how requirement → use case → DFD → data catalog creates traceability

This person should remember to say:

> The DFD is not just a picture. It is a structured way to show how information moves through the system.

If you want, I can also rewrite this into a **ready-to-copy PowerPoint outline**, with only slide titles and exact bullet points, so you can paste it directly into the presentation.
](https://vandalvape.life/nabori-dlja-samozamsu-fucked-lab-salt-30-ml-50-mg-blue-raspberry-ua)
