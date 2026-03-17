Javascript prosjekt

GitHub repository

https://github.com/Abdalmageed-alsultan/javascript-prosjekt

Beskrivelse

Dette prosjektet er en enkel webapplikasjon laget med HTML, CSS og JavaScript. Applikasjonen fungerer som en to-do liste der brukeren kan skrive inn oppgaver og legge dem til i en liste på nettsiden. Målet med prosjektet var å lære hvordan JavaScript kan brukes til å manipulere DOM og håndtere brukerinteraksjon.
 Hvordan koden fungerer

Jeg startet med å lage HTML-strukturen som inneholder et inputfelt, en knapp og en liste. Inputfeltet brukes til å skrive inn oppgaver, knappen brukes for å legge til oppgaven, og listen viser oppgavene.

I JavaScript hentet jeg elementer fra DOM ved hjelp av `getElementById`. Disse ble lagret i variabler slik at jeg kunne bruke dem videre i koden.

Jeg brukte en event listener som lytter etter klikk på knappen. Når brukeren klikker, kjører en funksjon som henter teksten fra inputfeltet.

Jeg brukte en if-setning for å sjekke om inputfeltet er tomt. Hvis det er tomt, stopper funksjonen for å unngå tomme oppgaver.

Deretter opprettet jeg et nytt listeelement med `createElement`, og satte teksten ved hjelp av `textContent`. Til slutt brukte jeg `appendChild` for å legge elementet inn i listen i HTML.

Etter at oppgaven er lagt til, tømmes inputfeltet slik at brukeren kan skrive en ny oppgave.

Teknologier brukt

* HTML (struktur)
* CSS (design)
* JavaScript (funksjonalitet)
* Git og GitHub (versjonskontroll)

 Git og versjonskontroll

Jeg brukte Git til å holde kontroll på endringer i prosjektet. Jeg initialiserte prosjektet med `git init`, la til filer med `git add`, og lagde en commit med `git commit`. Deretter koblet jeg prosjektet til GitHub med `git remote add origin` og lastet opp koden med `git push`.

 Refleksjon

Gjennom dette prosjektet har jeg lært hvordan JavaScript kan manipulere DOM og oppdatere nettsiden dynamisk. Jeg har også fått bedre forståelse for hvordan event listeners fungerer og hvordan brukerinput behandles.

En utfordring var å få GitHub-opplastingen til å fungere, spesielt med autentisering, men dette løste jeg ved å bruke en personal access token.

Hvis jeg skulle forbedret prosjektet videre, ville jeg lagt til funksjonalitet for å slette oppgaver og lagre oppgaver med localStorage slik at de ikke forsvinner når siden oppdateres.
