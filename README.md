Klart. Her er en **kortere og mye mer kompakt versjon** av presentasjonen — omtrent **halvparten så mange slides**, mindre tekst, jevnere fordelt mellom **4 personer**, og fortsatt dekkende for kravene i oppgaven.

Jeg anbefaler **8 slides totalt** for en 20-minutters presentasjon.
Da får hver person **2 slides** og omtrent **4–5 minutter hver**.

---

# Fordeling mellom 4 personer

## Person 1

* Slide 1
* Slide 2

## Person 2

* Slide 3
* Slide 4

## Person 3

* Slide 5
* Slide 6

## Person 4

* Slide 7
* Slide 8

---

# Kort presentasjon – slide for slide

---

## Slide 1 — Introduksjon til prosjektet

### Tittel

**Home Rentals – Systemanalyse**

### Tekst på slide

```text
• Digital plattform for korttidsutleie
• Vert legger ut bolig
• Gjest søker og bestiller
• Fokus i analysen:
  – Kravliste
  – Use Case-diagram
  – Use Case-beskrivelser
  – DFD-fragmenter
  – Datakatalog
```

### Bilde

* Forside / enkel illustrasjon av boligplattform
* Eller skjermbilde av hovedside / annonseoversikt

### Hvem snakker

**Person 1**

### Hva personen sier

> Hei, vi er Gruppe 07, og vi skal presentere analysedelen av prosjektet vårt, Home Rentals.
> Home Rentals er en digital plattform for korttidsutleie, der verter kan legge ut boliger og gjester kan søke og bestille.
> I presentasjonen skal vi vise kravlisten, use case-diagrammet, use case-beskrivelser, DFD-fragmenter og datakatalogen.

---

## Slide 2 — Kravliste

### Tittel

**Kravliste**

### Tekst på slide

```text
Funksjonelle krav:
• Vertshåndtering
• Gjestehåndtering
• Annonsehåndtering
• Formidling

Ikke-funksjonelle krav:
• Sikkerhet
• Ytelse
• Responsivt design
• Brukervennlighet
```

### Bilde

* lite skjermbilde av kravlisten
* eller enkel ikonoversikt

### Hvem snakker

**Person 1**

### Hva personen sier

> Kravlisten er grunnlaget for hele analysen.
> Her beskriver vi både hva systemet skal gjøre, og hvilke kvalitetskrav systemet må oppfylle.
> De funksjonelle kravene er delt inn i vert, gjest, annonser og formidling.
> De ikke-funksjonelle kravene handler blant annet om sikkerhet, ytelse og brukervennlighet.

### Overgang

> Når kravene er definert, kan vi modellere funksjonene i systemet.

---

## Slide 3 — Use Case-diagram

### Tittel

**Use Case-diagram**

### Tekst på slide

```text
To hovedaktører:
• Gjest
• Vert

Hovedområder:
• Registrering og profil
• Annonser
• Formidling
```

### Bilde

* stort skjermbilde av use case-diagrammet

### Hvem snakker

**Person 2**

### Hva personen sier

> Use case-diagrammet gir den overordnede oversikten over systemet.
> Det viser hvilke aktører vi har, og hvilke funksjoner de kan bruke.
> I vårt system har vi to hovedaktører: gjest og vert.
> Diagrammet viser også at funksjonene i systemet er gruppert i registrering, profilhåndtering, annonser og formidling.

---

## Slide 4 — Use Case Description

### Tittel

**Use Case Description**

### Tekst på slide

```text
Hver use case-beskrivelse inneholder:
• Aktør
• Trigger
• Preconditions
• Hoved flyt
• Postconditions

Eksempler:
• UC-1 Registrering av vert
• UC-10 Formidling av eiendom til gjest
```

### Bilde

* ett skjermbilde av en enkel use case-tabell
* gjerne UC-1 eller UC-10

### Hvem snakker

**Person 2**

### Hva personen sier

> Use case-beskrivelsen går dypere enn use case-diagrammet.
> Her beskriver vi én funksjon steg for steg.
> Vi viser hvem som starter funksjonen, hvilke forutsetninger som gjelder, hvordan hovedflyten foregår, og hva resultatet blir etterpå.
> I prosjektet vårt har vi både enkle use cases, som registrering av vert, og mer komplekse use cases, som formidling av eiendom til gjest.

### Overgang

> Når en use case er beskrevet i tekst, kan vi modellere hvordan data flyter i systemet.

---

## Slide 5 — DFD Fragment

### Tittel

**DFD-fragment**

### Tekst på slide

```text
Et DFD-fragment viser:
• Aktør (external entity)
• Prosess
• Datalager
• Dataflyt

Eksempler:
• Enkel: UC-1
• Mer kompleks: UC-10
```

### Bilde

* ett enkelt DFD-fragment
* eller to små bilder: UC-1 og UC-10

### Hvem snakker

**Person 3**

### Hva personen sier

> DFD-fragmentet viser hvordan data beveger seg i én bestemt funksjon.
> Her modellerer vi samspillet mellom aktør, prosess og datalager.
> De enkle use casene får enklere DFD-fragmenter, mens de mer komplekse use casene får rikere dataflyt og flere datalager.
> På denne måten blir analysen mer teknisk og mer presis.

---

## Slide 6 — Data Catalog

### Tittel

**Datakatalog**

### Tekst på slide

```text
Datakatalogen forklarer:
• hva dataflytene inneholder
• hva datalagrene inneholder

Eksempel:
• Ny bruker = e-postadresse + passord
• Brukere = bruker ID + e-postadresse + passord + datoer
```

### Bilde

* skjermbilde av datakatalog
* gjerne en enkel del som er lett å lese

### Hvem snakker

**Person 3**

### Hva personen sier

> Datakatalogen er ordboken til DFD-en.
> Den forklarer hva hver dataflyt betyr, og hva hvert datalager inneholder.
> Dette gjør modellen mer presis, fordi vi tydelig viser hvilke data systemet faktisk bruker og lagrer.
> Datakatalogen gjør det derfor lettere å forstå både DFD-fragmentene og systemdesignet som helhet.

### Overgang

> Nå vil vi vise hvordan disse delene henger sammen i vårt prosjekt.

---

## Slide 7 — Sammenheng i prosjektet

### Tittel

**Fra krav til dataflyt**

### Tekst på slide

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

### Bilde

* enkel prosesslinje / pilmodell

### Hvem snakker

**Person 4**

### Hva personen sier

> I prosjektet vårt henger alle delene sammen.
> Vi startet med kravlisten, og brukte den som grunnlag for use case-diagrammet.
> Deretter beskrev vi funksjonene i use case-tabeller.
> Så laget vi DFD-fragmenter for å vise dataflyten, og til slutt datakatalogen for å forklare dataene.
> Dette gjør analysen strukturert og sammenhengende.

---

## Slide 8 — Oppsummering

### Tittel

**Oppsummering**

### Tekst på slide

```text
Vi har vist:
• hvilke krav systemet bygger på
• hvilke aktører og funksjoner systemet har
• hvordan funksjonene beskrives
• hvordan data flyter i systemet
• hvordan datakatalogen gjør modellen tydelig
```

### Bilde

* enkel avslutningsslide
* eller liten collage av kravliste + use case + DFD

### Hvem snakker

**Person 4**

### Hva personen sier

> Oppsummert har vi gått fra krav til funksjoner, og videre til dataflyt og datadefinisjoner.
> Kravlisten definerer behovene, use case-diagrammet viser funksjonene, use case-beskrivelsene forklarer dem steg for steg, DFD-fragmentene viser hvordan data beveger seg, og datakatalogen forklarer hva dataene betyr.
> Takk for oss. Vi er klare for spørsmål.

---

# Jevn fordeling mellom 4 personer

## Person 1

**Tema:** prosjekt + kravliste
**Slides:** 1–2
**Tid:** ca. 4–5 min

## Person 2

**Tema:** use case-diagram + use case descriptions
**Slides:** 3–4
**Tid:** ca. 4–5 min

## Person 3

**Tema:** DFD-fragment + datakatalog
**Slides:** 5–6
**Tid:** ca. 4–5 min

## Person 4

**Tema:** sammenheng + oppsummering
**Slides:** 7–8
**Tid:** ca. 4–5 min

---

# Hva dere bør bruke som eksempler i presentasjonen

For å holde presentasjonen kort og tydelig, bruk bare disse konkrete eksemplene:

* **UC-1 Registrering av vert** → som eksempel på enkel funksjon
* **UC-10 Formidling av eiendom til gjest** → som eksempel på mer kompleks funksjon
* **ett enkelt DFD-fragment** → UC-1
* **ett mer komplekst DFD-fragment** → UC-10

Da slipper dere å vise for mange detaljer og mister ikke oversikten.

---

# Kort tips til selve fremføringen

* Ikke les alt som står på sliden.
* Bruk sliden som støtte, og forklar med egne ord.
* Hold rolige overganger mellom personene.
* Ikke gå for dypt inn i detaljer på alle use casene — bruk bare noen få representative eksempler.

Hvis du vil, kan jeg nå lage en enda mer praktisk versjon: **ferdig PowerPoint-tekst slide for slide**, veldig kort, slik at dere bare kan lime den rett inn i presentasjonen.
