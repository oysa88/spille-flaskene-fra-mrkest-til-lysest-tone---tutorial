# Post7_Robothakkespettene

## Steg 1

### Instruksjon

Inne i denne skogen er det utplassert flere robot-hakkespetter. En av disse har startet å hakke på en litt rar måte. 

Din oppgave er å finne den og bokstaven den vil gi deg.

Følg Instruksjonen for hvordan du kan bruke programmering til å finne hakkespetten!

## Steg 2

### Ved start

Sett opp egen ``||radio:Radio sett gruppe||``. Den skal være den samme som posten du er på. Sett den inn i ``||basic: ved start||``.

```blocks
radio.setGroup(7)
```

## Steg 3

### Når knapp A trykkes

Finn frem blokken: ``||input: Når knapp A trykkes||``.

Inni her skal vi plassere en ``||radio: radio send tekst||``. Teksten vi skal sende er: Finn defekt hakkespett.

```blocks
input.onButtonPressed(Button.A, function () {
    radio.sendString("Finn defekt hakkespett")
})
```

## Steg 4

### Finn defekt hakkespetten

Last koden din inn på en micro:bit. Trykk på knapp A for å spille av alle hakkespettene. Gå rundt i skogen og lytt etter den defekte hakkespetten.

Når du finner den, titt opp i trestammen du hører den defekte hakkespetten. Da vil du finne bokstaven den vil vise deg!