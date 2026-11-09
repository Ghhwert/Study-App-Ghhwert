# Analyse

## User Stories:

### US 1 (M):

Als student wil ik studiesessies op kunnen slaan, zodat ik weet hoeveel studiesessies ik heb gedaan.

### US 2 (M):

Als student wil ik alle onderwerpen dat ik studeer op kunnen slaan, zodat ik weet welke onderwerpen ik heb bestudeerd.

### US 3 (M):

Als student wil ik alle deelonderwerpen per onderwerpen dat ik studeer op kunnen slaan, zodat ik weet welke deelonderwerpen ik heb bestudeerd.

### US 4 (M):

Als student wil ik een overzicht van alle studiesessies kunnen zien, zodat ik overzicht krijg op al mijn studiesessies.

### US 5 (M):

Als student wil ik een overzicht van een studiesessie kunnen zien, zodat ik weet hoe lang ik elk deelonderwerp gestudeerd heb.

### US 6 (S):

Als student wil ik een overzicht, waarin ik per onderwerp kan zien hoeveel tijd ik er in totaal aan heb besteed, zodat ik weet hoe lang ik heb gestudeerd voor dat onderwerp.

### US 7 (S):

Als student wil ik een overzicht, waarin ik per onderwerp van de deelonderwerpen kan zien hoeveel tijd ik er in totaal aan heb besteed, zodat ik weet hoe lang ik heb gestudeerd voor dat onderwerp.

### US 8 (C):

Als student wil ik een overzicht, waarin ik kan zien wat ik in de laatste periode heb gestudeerd per (deel)onderwerp, om zo snel een geschiedenis te kunnen zien van mijn laatst gestudeerde (deel)onderwerpen.

### US 9 (M):

Als student wil ik een studiesessie kunnen starten met een studietimer die mij om de zoveel tijd een signaal geeft, zodat ik weet dat ik het volgende onderwerp moet gaan studeren.

### US 10 (C):

Als student wil ik zelf notities kunnen toevoegen bij een bepaald deelonderwerp, om zo snel aantekeningen te kunnen maken.

### US 11 (C):

Als student wil ik een overzicht, waarin ik de notities kan zien die ik wil zien, om zo snel mijn aantekeningen te benaderen.

### US 12 (M):

Als student wil ik een timer van een onderwerp ook eerder kunnen afkappen en de tijd opslaan, zodat ik precies weet hoeveel tijd ik daadwerkelijk aan dat onderwerp heb besteed.

### US 13 (C):

Als student wil ik bij het instellen van mijn sessie, suggesties voor deelonderwerpen krijgen, om zo sneller aan de slag te kunnen gaan.

### US 14 (C):

Als student wil ik een soort shuffle functionaliteit, waarmee ik snel de deelonderwerpen van een onderwerp kan bestuderen op een willekeurig volgorde.

### US 15 (C):

Als student wil ik 'playlists' op kunnen slaan, met daarin een vaste volgorde van deelonderwerpen, zodat ik een sessie kan herhalen.

#3# US 16 (W):

Als student wil ik een ringtoon kunnen toevoegen als mijn alarm, om zo meer personaliteit erin te verwerken.

### US 17 (W):

Als student wil ik een lied of nummer kunnen toevoegen als mijn bgm, om zo meer personaliteit erin te verwerken.

## User Concerns:

### C 1: Userfriendly

### C 2: Simple

### C 3: Secure

## User Cases:

### UC 1. Hulp/ menu tonen

_Actor_: Student
_Beschrijving_:

1. De student toetst 'h' of 'help' in.
2. Het systeem toont een hulp menu met alle opties.

_Alternate Flows_:

1. De student toets een ongeldige waarde in. Het systeem geeft een foutmelding, de usecase stopt.

### UC 2. Start een nieuwe sessie

_Actor_: Student
_Beschrijving_:

1. De student toetst 'new', 'nieuw' in.
2. Het systeem toont het nieuwe sessie menu met daarin de instellingen van de laatste sessie.
3. Het systeem geeft de gebruiker opties om dingen aan te passen of de sessie te starten.
4. De student kiest de optie 'Sessie Starten'.
5. Het systeem start de sessie.

_Alternate Flows_:

1. De student toets een ongeldige waarde in. Het systeem geeft een foutmelding, de usecase stopt.
2. De student kiest een ongeldige optie. Het systeem geeft een foutmelding, de usecase stopt.

### UC 3: Studiesessies opslaan

_Actor_: Student
_Beschrijving_:

1. De student pauzeerd de studiesessie met de spatie balk.
2. Het systeem toont het pauze menu.
3. De student kiest de optie 'Sluit Studiesessie'.
4. Het systeem vraag de gebruiker of die het zeker weet dat die wilt aflsuiten.
5. De student kiest 'Sluit'.
6. Het systeem vraag de gebruiker of de sessie opgeslagen moet worden.
7. De student kiest 'Sla op'.
8. Het systeem geeft een bevestiging.

_Alternate Flows_:

3. De student kiest een ongeldige optie. Het systeem geeft een foutmelding, de usecase stopt.
4. De student kiest een ongeldige optie. Het systeem geeft een foutmelding, de usecase stopt.

### UC 4: Deelonderwerp aan studiesessie toevoegen.

_Actor_: Student
_Beschrijving_:

1. In het menu 'Nieuwe sessie' kies de optie 'Inhoud'.
2. Het systeem toont het inhoud menu.
3.

### UC 5: Onderwerpen opslaan

_Actor_: Student
_Beschrijving_:

1. In het menu 'Sessie instellen' kies de optie 'Deelonderwerpen'

### UC 6: Deelonderwerpen opslaan

_Actor_: Student
_Beschrijving_:

### UC 7: Overzicht van studiesessies bekijken

_Actor_: Student
_Beschrijving_:

1. De student toetst 'ov' of 'overzichten'.
2. Het systeem toont een lijst van verschillende overzichten.
3. De student kiest de optie 'Toon alle studiesessies.'
4. Het systeem toont een overzicht met daarin de laatste 20 studiesessies.
5. De student kan evt. ervoor kiezen om de volgende 20 studiesessies weer te geven, Enzovoort.

### UC 8: Details van een studiesessie bekijken

_Actor_: Student
_Beschrijving_:

### UC 9: Totale studietijd per onderwerp bekijken

_Actor_: Student
_Beschrijving_:

### UC 10: Totale studietijd per deelonderwerp bekijken

_Actor_: Student
_Beschrijving_:

### UC 11: Recent bestudeerde (deel)onderwerpen bekijken

_Actor_: Student
_Beschrijving_:

### UC 12: Studiesessie met timer starten

_Actor_: Student
_Beschrijving_:

### UC 13: Notitie toevoegen aan een deelonderwerp

_Actor_: Student
_Beschrijving_:

### UC 14: Notities bekijken

_Actor_: Student
_Beschrijving_:

### UC 15: Timer eerder stoppen en tijd opslaan

_Actor_: Student
_Beschrijving_:

### UC 16: Suggesties voor deelonderwerpen bekijken

_Actor_: Student
_Beschrijving_:

### UC 17: Deelonderwerpen in willekeurige volgorde studeren

_Actor_: Student
_Beschrijving_:

### UC 18: Playlist met deelonderwerpen opslaan

_Actor_: Student
_Beschrijving_:

### UC 19: Ringtone instellen

_Actor_: Student
_Beschrijving_:

### UC 20: Achtergrondmuziek instellen

_Actor_: Student
_Beschrijving_:
