# Refleksjon: Grunnleggende JavaScript

Korte svar er greit.

---

## A. Forklar med egne ord

**1. Hva er forskjellen på `let` og `const`? Når bruker du hvilken?**

> `let` kan endres. `const` kan ikke endres.  
> Bruk `const` når verdien ikke skal endres. Bruk `let` når den skal endres.

**2. Hvorfor ble `"5" + 5` til `55`, mens `5 + 5` ble `10`?**

> `"5"` er tekst. Da blir `+` til å sette tekst sammen.  
> `5 + 5` er tall, så det blir regning.

**3. Hva gjør `%`? Gi et eksempel fra oppgavene der du brukte den.**

> `%` gir resten etter deling.  
> Eksempel: `17 % 4` gir 1 (i oppgave 9).

**4. Hva er forskjellen på `=` og `===`?**

> `=` setter en verdi.  
> `===` sjekker om to ting er like.

**5. Forklar de tre delene i denne linja:** `for (let i = 1; i <= 5; i++)`

> 1. `let i = 1` starter telleren.  
> 2. `i <= 5` sjekker om vi skal fortsette.  
> 3. `i++` øker med 1.

**6. Når er en `while`-løkke bedre enn en `for`-løkke? Hva kan gå galt med en `while`-løkke?**

> `while` er bra når du ikke vet hvor mange ganger.  
> Den kan kjøre for alltid hvis du glemmer å endre verdien.

**7. Hvorfor er den første byen i lista `byer[0]` og ikke `byer[1]`?**

> Fordi lister starter på 0. Første er alltid `[0]`.

---

## B. Bruk det du har lært

**8. Hva skrives ut her?**

> Kaldt

**9. Hva skrives ut her?**

> 4  
> Ulvene

**10. Denne koden skal skrive ut 1, 2 og 3, men gjør det ikke. Hva er feil?**

> Den stopper før 3 fordi det står `i < 3`.  
> Endre til `i <= 3`.

---

## C. Om din egen læring

**11. Hvilken oppgave var vanskeligst, og hvordan løste du den?**

> Oppgave 19 og 24 var vanskeligst.  
> Jeg sjekket betingelsene i riktig rekkefølge og laget en ny liste.

**12. Hvilken feilmelding fikk du oftest? Hva betydde den?**

> `SyntaxError`.  
> Det betyr at koden har en skrivefeil (for eksempel manglende `}` eller feil plassering av `else`).

**13. Hva gjorde du når du sto fast? Hva vil du gjøre annerledes neste gang?**

> Jeg tenkte på C++ og sjekket om det var samme regler.  
> Neste gang sjekker jeg JavaScript-reglene først, ikke C++.

**14. Hvor langt kom du?**

| Nivå | Kryss av |
|---|---|
| Grunnleggende |  |
| Middels |  |
| Avansert | X |

**15. Kryss av for det du kan nå.**

| Jeg kan... | Ja | Litt | Nei |
|---|---|---|---|
| lage variabler med `let` og `const` | X |  |  |
| bruke tekst og tall, og sette dem sammen med `${}` | X |  |  |
| ta valg med `if`, `else if` og `else` | X |  |  |
| skrive en `for`-løkke | X |  |  |
| hente, legge til og gå gjennom verdier i en array | X |  |  |
| lese en feilmelding og finne riktig linje | X |  |  |

**16. Hva vil du øve mer på før vi går videre til funksjoner?**

> Mer på løkker med `if` og på å lage nye lister.
