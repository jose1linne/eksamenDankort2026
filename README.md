# Teknisk dokumentation for eksamen 2. semester EK 2026 gruppe 2

## Projektstruktur

Vi har valgt at dele alt op i mapper under src, så det er nemt at navigere i for alle.

###Astro
Ved brug af astro har vi valgt at lave komponenter. For eksempelvis footer, header og cards. Så er det nemmere for os at holde styr på de forskellige elementer.

## Opdeling

Vi kommer til at skrive her, hvem der koder hvad:

### Komponenter:

naturomraadercards.astro -
footer.astro -
header.astro -
dropdown -
CTA -

### pages:

Forsiden -
Naturomraader -
Q&A -

## Database struktur

Vi kommer til at bruge superbase til at holde styr på vores data. Det er Denzel som styrer vores superbase.

---

## Navngivning

For at sikre en ensartet struktur og undgå forvirring i projektet har vi aftalt nogle regler for, hvordan vi navngiver filer og mapper.

### Filnavne

Til navngivning bruger vi en kombination af **camelCase**.

---

## Git branches

Vi sikre os at vi altid laver nye brances så vi ikke arbejder i main

### Navngivning af branches

Vi laver branches navne så det passer med det vi arbejder i.
**Format:**

**Eksempler:**

- `menuForside`
- `footerOpdatering`

Denne struktur gør det lettere for alle i gruppen at forstå, hvad der arbejdes på i de forskellige branches.

---

### Fordeling af arbejde

For at undgå at flere arbejder i de samme filer samtidigt, tildeler vi **en side til hver person i gruppen**.
Den person har ansvar for funktioner og kode, der hører til den pågældende side.

### Kommunikation om ændringer i main

Når en **feature-branch merges ind i `main`**, kommunikerer vi ændringen i **gruppechatten**, så alle er opmærksomme på opdateringen.

Vi forsøger også så vidt muligt kun at **merge til `main`, når vi er samlet**, så vi kan undgå konflikter og fejl.

# Funktionalitet

Vi henter alt vores data fra superbase, så vi kan hente vores date fra et sted.

## Eksempel på mappestruktur

```
/src
│ /css
│ └── global.css
│
│/pages
│ └── global.css
│ ├── produkt.js
│ ├── produktliste.js
│ └── burger.js
│
│/components
│└──index.html
│├── produkt.html
│└── produktliste.html

```
