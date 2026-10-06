# Tilbakemelding på product brief

| | |
|---|---|
| **Gruppe** | G139 – G139-bakke |
| **Product brief** | Ingen product brief funnet på `main` per 2026-10-06 (repoet inneholder bare `README.md` og `.gitignore` fra opprettelsen) |
| **Tilbakemelding fra** | Faglærer i IBE160 (utarbeidet med KI-støtte) |
| **Dato** | 2026-10-06 |

## Samlet vurdering

- **Bør revideres før dere går videre.** Det ble ikke funnet noen product brief eller tilsvarende dokument (proposal, prosjektbeskrivelse, idénotat) på `main` i repoet per 2026-10-06. Repoet har bare den første commiten fra opprettelsen, og README sier ikke noe om hvilken app dere planlegger. Lag og commit en product brief før dere går videre til PRD og arkitektur.

Har dere skrevet briefen et annet sted (lokalt, i en annen gren eller i et delt dokument), må den inn på `main` i dette repoet. Det er repoet sensor vurderer.

## Hvorfor product brief er viktig for mappen

Product brief er utgangspunktet for PRD, arkitektur, stories og til slutt koden. Del 1 av mappen vurderes blant annet på om sensor kan følge en sporbar vei fra plan til ferdig app. Kriteriet «Prosess og KI-styring» teller 30 % av del 1, og der ser sensor etter BMAD-dokumenter som faktisk er brukt og oppdatert, og en commit-historikk som viser jevn utvikling over tid. Del 1 vurderes også på om appen gjør det dere har beskrevet, om den er testet, om den er godt designet, og om den kan kjøres etter README. Uten en brief mangler startpunktet for hele denne kjeden, og det blir vanskelig å vise at appen svarer til en plan.

Semesteret er godt i gang. Jo tidligere briefen kommer på plass, jo mer tid får dere til PRD, arkitektur, stories, implementering, testing og README.

## Hva briefen bør inneholde

Følg strukturen fra BMAD (`bmad-product-brief`) og malen dere har fått:

| Del av brief | Hva den skal svare på |
|---|---|
| Executive Summary | Hva appen er, og hvilket problem den løser, kort nok til at en som bare leser denne delen forstår ideen. |
| The Problem | Et konkret problem med reelle situasjoner og brukere: hvem har problemet, hvordan løser de det i dag, og hva koster det? |
| The Solution | Hva brukeren opplever og oppnår. Beskriv kjerneflyten i 3–5 steg. Teknologivalg hører hjemme i arkitekturen. |
| What Makes This Different | En ærlig vurdering av eksisterende alternativer og hva som skiller deres løsning fra dem. |
| Who This Serves | Én tydelig primærbruker: hvem de er, hvilken situasjon de er i, og hva de skal få gjort i appen. |
| Success Criteria | Kriterier som kan sjekkes eller testes, f.eks. «brukeren kan registrere X og se det i oversikten». |
| Scope | Hva som er med i første versjon («In for v1»), og hva som eksplisitt ikke er det («Explicitly out»). |
| Vision | Hvor appen kan gå videre, uten at det blåser opp første versjon. |

I tillegg bør dere vurdere vanskelighetsgrad og gjennomførbarhet selv, og skrive det kort inn i briefen eller i et vedlegg:

- **Vanskelighetsgrad:** Sammenlign med forslagslista «Prosjektforslag for IBE160 Programmering med KI». Enkle prosjekter (f.eks. 1) AI Study Buddy eller 6) To-do-liste med smarte etiketter) har CRUD og én avgrenset KI-funksjon. Middels prosjekter (f.eks. 2) AI CV- og søknadsassistent eller 7) Kurs-FAQ-chatbot) har flere sammenhengende funksjoner. Vanskelige prosjekter (f.eks. 3) prosjektledelsessimulering eller 4) MRP II) har omfattende domenelogikk som må stemme. Et enkelt prosjekt gir større sjanse for å bli ferdig, men krever mer i gjennomføringen for å nå helt opp.
- **Gjennomførbarhet:** Kan første versjon bli ferdig og stabil i løpet av semesteret med BMAD og Claude Code? Kan dere selv kontrollere at KI-ens kode gir riktige svar? Kan sensor kjøre appen lokalt etter README, uten deres nøkler eller betalte kontoer? Bruker appen en språkmodell, trenger dere en plan for kostnad og en demo- eller testmodus.

## BMAD-flyten og eksempel

Planleggingen i emnet følger BMAD: product brief → PRD → arkitektur → epics og stories → implementering med Claude Code. Faglærers eksempelprosjekt viser hele flyten, inkludert hvordan briefen ser ut og hvor den ligger i repoet: https://github.com/IBE160-2026/beergame

Legg briefen i repoet, for eksempel som `_bmad-output/planning-artifacts/briefs/<navn>/brief.md` eller `product-brief.md` i roten, og commit den slik at historikken viser når den ble laget og hvordan den endres.

## Neste steg for gruppen

1. Velg prosjektidé, gjerne med utgangspunkt i forslagslista, og lag en product brief med BMAD (`bmad-product-brief`). Ta med en kort vurdering av vanskelighetsgrad og gjennomførbarhet.
2. Commit briefen til `main` i dette repoet, og oppdater README med en kort beskrivelse av appen.
3. Gå videre til PRD og arkitektur så snart briefen er på plass, og lagre prompts og KI-økter underveis, slik at prosessen blir sporbar.

Oppdater product brief i repoet når dere har gjort endringene, slik at historikken viser hvordan planen utviklet seg. Det er en del av prosessen sensor ser etter.
