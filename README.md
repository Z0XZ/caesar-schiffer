## Cæsarchifferet

### Historisk bakgrunn:

Cæsarchifferet er oppkalt etter **Julius Cæsar**, den romerske generalen og statsmannen, som angivelig brukte dette chifferet for å sikre meldingene han sendte. Selv om Cæsar sannsynligvis ikke var den første til å bruke denne typen kryptering, er hans bruk av den grunnen til at chifferet bærer hans navn.

### Hvordan det fungerer:

Cæsarchifferet er et substitusjonschiffer der hver bokstav i teksten erstattes av en bokstav som ligger et fast antall plasser nedover eller oppover i alfabetet.

Hvis vi for eksempel bruker en forskyvning på 3:

- **A** blir erstattet med **D**
- **B** blir erstattet med **E**
- **C** blir erstattet med **F**
  ... og så videre, inntil:
- **Z** blir erstattet med **C**

For å kryptere en melding, går man enkelt og greit gjennom hver bokstav i meldingen og erstatter den med den korresponderende bokstaven basert på forskyvningen. Dekryptering gjøres ved å reversere prosessen, det vil si å gå motsatt vei i alfabetet basert på forskyvningen.

### Eksempler:

La oss kryptere meldingen "HEI" med en forskyvning på 3:

- **H** blir erstattet med **K**
- **E** blir erstattet med **H**
- **I** blir erstattet med **L**

Resultatet blir da: **KHL**

For å dekryptere "KHL" med samme forskyvning:

- **K** blir erstattet med **H**
- **H** blir erstattet med **E**
- **L** blir erstattet med **I**

Resultatet er den opprinnelige teksten: **HEI**

Cæsarchifferet er i dag betraktet som et svært usikkert kryptosystem, fordi det bare er 25 mulige nøkler (forskyvninger), og det er derfor enkelt å knekke ved hjelp av brute force-angrep (prøve alle mulige nøkler). Likevel er det et utmerket verktøy for å introdusere grunnleggende konsepter innen kryptografi.

## Oppgaven

Oppgaven din nå er å lage et program som kan kryptere og dekryptere en melding når man vet forskyvningen. Altså om jeg har meldingen "Hei" og forskyvning 5 som input skal jeg få ut igjen "Mjn". Inkluder gjerne norske bokstaver også slik at man kan skrive ø, æ og å.

Du kan strukturere programmet slik du vil, men kriteriet er at det skal kunne motta input fra brukeren og komme med riktig output. Den skal også kunne både kryptere og dekryptere teksten.

Denne oppgaven er vanskelig og du vil få bruk for det meste vi har vært innom knyttet til programmering.
