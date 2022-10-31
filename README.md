# Obligatorisk oppgave 3 i Algoritmer og Datastrukturer

Denne oppgaven er en innlevering i Algoritmer og Datastrukturer. 
Oppgaven er levert av følgende student:
Wardah Fatima Naqvi, S348559, s348559@oslomet.no


# Oppgavebeskrivelse 

Oppgave 1 er inspirert fra programkoden 5.2.3 a. Jeg har innført noen endringer for å få koden til å passe bedre med oppgaven. Først utelukker vi at verdien ikke kan være null. etter det kjøres en while loop 

Oppgave 2 var for det meste ferdigkodt lagde metoden public int antall (t-verdi) ved lage en metode som først initialer P, så kjøres en while loop som sammenigner verdier, oppdaterer først venstrebarn så høyrebarn, for å så returne antall forekomster av verdi i Sbintreet. 

Oppgave 3: for å lage førstePostorden metoden må vi først finne ut av om p er null, ettersom null verdier ikke er gyldig. Vi kjører så en while loop sjekker postorderen om p ikke er lik 0. Først sjekker den mot venstre, så mot høyre. For å lage metoden nestePostorden initialerte jeg f som p.foreldre. Deretter kjørte jeg en if sjekk som igjen sjekker om verdien er null. Om verdien er null vil det ikke være noe neste postorden. 

Oppgave 6: veldig inspirert fra programkode, fasitt til tidligere oppgaver. Har skrevet i kommentar ved siden av koden hvor den er tatt fra. Metoden boolean fjern(T verdi) består av flere if sjekker og en while loop. Sjekker først om treet har null verdier, leter så etter verdier. Vi sammenlginer så verdiene, sjekker  ventre og så høyre. 
public int fjern alle metoden tar først til seg en hjelpevariabel som skal teller antall verdier fjernet. Den legger så disse sammen og returnerer antall.
public void nullstill() metoden består også av flere if sjekker og while løkker. Metoden vil starte med å ikke returnere noe dersom antaller er lik nill. Initialiserer så p som rot. 


