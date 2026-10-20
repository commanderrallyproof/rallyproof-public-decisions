# RALLYPROOF — COMMANDER DECISION
## LEAN PATH V1.2 — MANDATORY DEVELOPMENT EXECUTION PROCESS

**DECISION ID:** `CMD-RALLYPROOF-LEAN-PATH-V1-2-ADOPTION-001`  
**ISSUING AUTHORITY:** Human Commander — Rallyproof  
**DATE:** 20. oktober 2026  
**DECISION CLASS:** Development Process Adoption  
**STATUS:** COMMANDER DECISION — FOR SIGNED PUBLICATION  
**APPLICABILITY:** All Rallyproof development activities

---

## 1. COMMANDER DECISION

Human Commander fastsetter herved **Lean Path v1.2 som Rallyproofs felles og obligatoriske utviklingsprosess**.

Prosessen skal benyttes av XO, S1–S6, IM, Bodyguard og øvrige relevante funksjoner ved planlegging, gjennomføring, verifisering og avslutning av utviklingsoppdrag.

**Commander setter oppdraget og rammene. Kompetente seksjoner leder gjennomføringen. Autoriserte utførere handler. Kompetente kontrollører verifiserer.**

Godkjente oppdrag skal gjennomføres sammenhengende til verifisert sluttilstand uten unødvendige nye godkjenningsrunder.

## 2. RELATIONSHIP TO HQ OPORD 001 v1.1

Lean Path v1.2 er Rallyproofs operative utviklingsprosess for å gjennomføre oppdrag innenfor organisasjons- og myndighetsmodellen beskrevet i:

**HQ-OPORD-001 v1.1**

https://github.com/RaunTechnologies/rallyproof/blob/main/01_HQ/OPORD.md

**OPORD effective from:** `2026-10-20T00:32:27Z`

**Effectivity receipt:**

https://github.com/RaunTechnologies/rallyproof/pull/1267#issuecomment-6280464799

Lean Path v1.2 operasjonaliserer OPORDs prinsipper for profesjonell, oppdragsstyrt gjennomføring.

Prosessen skal også anvendes i samsvar med:

- Rally OS Operating Model v2.
- Governed Execution of Approved Intent Standard 001.
- Gjeldende rollepakker, myndighetskonvolutter og delegasjoner.
- Eksisterende obligatoriske tekniske og uavhengige kontroller.

Lean Path endrer ikke OPORD 001 v1.1, Rally OS v2 eller eksisterende myndighetsfordeling.

## 3. MANDATORY LEAN PATH — NINE STEPS

### STEP 1 — HUMAN INTENT

Commander fastsetter oppdrag, ønsket sluttilstand, prioriteringer og myndighetsgrenser.

**Resultat:** Godkjent oppdrag med klare rammer.

### STEP 2 — AUTHORITY / REPRESENTATION PRECHECK

Oppdragsansvarlig funksjon kontrollerer eksisterende myndighet, oppgavebinding, utførerbinding og tillatt handlingsrom.

Ingen nye myndighetskrav opprettes dersom eksisterende autorisasjon er tilstrekkelig.

**Resultat:** PASS eller konkret myndighetsmangel.

### STEP 3 — CURRENT EFFECTIVE SPEC

Oppdragsansvarlig funksjon identifiserer gjeldende beslutninger, spesifikasjoner, dokumentasjon og effektivitetsgrunnlag.

Tidligere gyldig kvalifisering og evidens skal gjenbrukes.

**Resultat:** Verifisert gjeldende grunnlag.

### STEP 4 — DETERMINISTIC PRECONDITION RESOLUTION

Nødvendige myndighets-, currentness-, test-, sikkerhets- og kontrollforutsetninger verifiseres.

Deterministiske kontroller automatiseres der dette er tilgjengelig og autorisert.

**Resultat:** PASS eller eksakt BLOCKED.

### STEP 5 — AUTHORIZED SINGLE MUTATION

Kompetent funksjon leder gjennomføringen.

Autorisert teknisk utfører gjennomfører neste avgrensede, tillatte handling.

**Resultat:** Faktisk tilstandsendring eller dokumentert utføringsresultat.

### STEP 6 — DIRECT STATE READBACK

Faktisk resultat kontrolleres direkte fra relevant autoritativ systemkilde.

En utførers egen rapport er ikke alene tilstrekkelig dersom faktisk tilstand må verifiseres.

**Resultat:** Verifisert tilstand eller konkret avvik.

### STEP 7 — RECOMPUTE NEXT ALLOWED EDGE

Oppdragsansvarlig funksjon fastslår neste lovlige handling.

Hvis oppdraget og neste handling fortsatt er autorisert, fortsetter gjennomføringen direkte.

Kun forhold som faktisk har endret seg, kontrolleres på nytt.

**Resultat:** CONTINUE, COMPLETE eller BLOCKED.

### STEP 8 — INDEPENDENT REVIEW WHEN REQUIRED

Kompetent uavhengig reviewer gjennomfører kontroll **kun der og når gjeldende bindende krav krever det**.

Tidligere gyldige PASS-resultater gjenbrukes når de fortsatt dekker det aktuelle objektet og kontrollformålet.

**Resultat:** PASS eller konkret avvik.

### STEP 9 — NEXT HUMAN GATE ONLY WHEN ACTUALLY REQUIRED

En sak eskaleres bare dersom en reell myndighetsgrense, reservert beslutning eller obligatorisk menneskelig beslutning krever det.

Rutinemessige tekniske og administrative overganger skal ikke sendes tilbake til Commander.

**Resultat:** Kompetent beslutning ved behov; ellers fortsetter utførelsen.

## 4. MANDATORY CONTINUATION RULE

Følgende gjennomføringslogikk skal legges til grunn:

`AUTHORIZED + PRECONDITIONS PASS → EXECUTE → READBACK → RECOMPUTE → CONTINUE`

`MISSING AUTHORITY → STOP AFFECTED ACTION → COMPETENT AUTHORITY`

`REQUIRED INDEPENDENT REVIEW → VERIFY AT REQUIRED POINT`

`VERIFIED END STATE → COMPLETE`

Ett delsteg som er fullført, innebærer ikke at hele oppdraget er ferdig.

Utførende funksjon skal fortsette gjennom allerede autoriserte steg frem til faktisk verifisert sluttilstand.

## 5. PROHIBITED PROCESS EXPANSION

Det skal ikke innføres:

- Nye godkjenningsrunder uten konkret bindende grunnlag.
- Gjentatt Commander-godkjenning av samme autoriserte oppdrag.
- Fullstendig ny review av uendret og fortsatt kvalifisert innhold uten krav.
- Unødvendige administrative overleveringer.
- Nye registreringsmekanismer når eksisterende mekanismer er tilstrekkelige.
- Nye governance-prosesser for å gjennomføre allerede autoriserte beslutninger.

Eksisterende obligatoriske kontroll-, sikkerhets-, myndighets- og beskyttelseskrav skal fortsatt oppfylles.

Denne beslutningen gir ingen ny generell Writer-, merge-, deploy-, produksjons- eller profesjonell beslutningsmyndighet.

## 6. RESPONSIBILITY

**Commander:** Oppdrag, rammer og reserverte beslutninger.

**XO:** Koordinering, avhengigheter og kontinuerlig fremdrift innenfor gyldig mandat.

**Kompetent seksjon:** Faglig og operativ ledelse av eget oppdrag.

**S6 / autorisert teknisk utfører:** Teknisk gjennomføring innenfor gjeldende myndighet.

**IM:** Informasjonsintegritet, proveniens og currentness.

**S1:** Rolle- og organisatoriske myndighetsforutsetninger.

**Bodyguard:** Uavhengig kontroll når dette er påkrevd.

Ansvar innebærer ikke automatisk personlig eller teknisk utøvelsesmyndighet.

## 7. SUPERSESSION AND APPLICATION

Lean Path v1.2 skal benyttes som felles utviklingsprosess for fremtidige Rallyproof-utviklingsoppdrag fra gyldig prospektivt virkningstidspunkt.

Tidligere prosessbeskrivelser som ikke er bindende, skal ikke brukes til å innføre ekstra kontrolltrinn i strid med denne beslutningen.

Eventuelle konkret motstridende, tidligere effektive obligatoriske krav må avklares av kompetent myndighet; denne beslutningen opphever dem ikke automatisk.

Eksisterende relevante Lean-observasjoner og gjennomføringserfaringer skal gjenbrukes uten at nye lærings- eller governance-kampanjer blir obligatoriske.

## 8. EFFECTIVITY

Denne beslutningen er ment som en prospektiv Commander-adopsjon av Lean Path v1.2.

Den blir bindende når Commander har autentisert beslutningen og kompetent effektivitetsregistrering er gjennomført gjennom gjeldende gyldig kildevei.

Ingen tilbakevirkende effekt etableres.

Ingen ny separat prosess eller kontrollport opprettes gjennom denne bestemmelsen.

## 9. FINAL COMMANDER DIRECTIVE

**Lean Path v1.2 er Rallyproofs obligatoriske utviklingsprosess.**

Alle utviklingsoppdrag skal følge prosessens ni trinn, anvendt etter faktisk risiko, myndighet og gjeldende krav.

Kontroll skal sikre korrekt handling, ikke skape unødvendig friksjon.

**Oppdrag skal gjennomføres til verifisert sluttilstand uten nye beslutningsrunder når eksisterende myndighet allerede er tilstrekkelig.**

**COMMANDER INTENT:**

**MAXIMUM AUTHORIZED EXECUTION. MINIMUM UNNECESSARY GOVERNANCE.**

**HUMAN COMMANDER — RALLYPROOF**
