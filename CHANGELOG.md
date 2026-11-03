# Changelog

Versioning semantico: MAJOR.MINOR.PATCH (es. v1.1.0 = nuova funzione, v1.0.1 = correzione).

## v3.0.0
- Case study: aggiunta la migrazione del sistema da HTML a Figma e la pipeline dei token verso il codice (Tokens Studio, GitHub); il processo passa da 3 a 5 passi, il ruolo da 4 a 5 voci con la validazione in auto.
- Punti dell'esperienza riscritti per comunicare il livello del ruolo, con numeri e ownership in apertura.
- Competenze riorganizzate in cinque gruppi: design system, ricerca, design di prodotto, strumenti, modo di lavorare.
- Chi sono riscritto su tre paragrafi a partire dal profilo reale; il dato inventato "20+ progetti" sostituito da "111 team usano il design system".

## v2.13.0
- Sezione Esperienza con i dati reali: ALTEN, Tata Consultancy Services, Auto Gest, TESYouth, con ruolo, tipo di contratto, periodo, luogo e punti di attivita, in italiano e inglese.
- Esperienza ridisegnata come timeline verticale al posto delle card.
- Link LinkedIn al profilo reale; il numero dei settori passa da 3 a 5.

## v2.12.0
- Il nome del cliente non compare piu: il case study si chiama "Automotive Design System" e il cliente e indicato come "Il cliente".
- Sfondo animato del case study: tre aloni sfocati nel colore del progetto che derivano lentamente, griglia sottile e grana, con una velatura dietro la colonna di testo per tenerlo leggibile.

## v2.11.0
- Hero ridotta a un solo elemento: un pulsante play al centro, in vetro smerigliato, con anello di avanzamento nel colore del progetto e alone pulsante. Premendolo si apre il progetto mostrato dallo slideshow.
- Slideshow di sfondo più visibile e velatura alleggerita.

## v2.10.0
- Slideshow animato dietro la hero: una scena per progetto, nei suoi colori, con forme che fluttuano e lento ingrandimento, in dissolvenza incrociata ogni 6,5 secondi. Attenuato da una velatura scura perché non disturbi la UI sopra.

## v2.9.0
- Hero svuotata dei contenuti di progetto: ora è una zona di rilascio con uno slot tratteggiato, tre mini-card che fluttuano e il testo che spiega come trascinare dentro un case study. Su dispositivi touch il testo invita a toccare una card.
- Rimossi ricerca e campanella dalla barra di navigazione.

## v2.8.0
- Logo Alten reale nelle cover del case study, su targhetta bianca.
- Terminologia: "variabili" sostituito da "token" in tutto il case study.
- Sfondo delle cover derivato dall'accent color del progetto, in versione smorzata; accent passato a un blu Alten.
- Hero interattiva: passando sopra una card il progetto appare sullo schermo, si può trascinare una card dentro lo schermo per aprirla, e ci sono i pallini per scegliere il progetto.

## v2.7.0
- Cover del case study Audi: composizione centrata sul nome Alten, su griglia tecnica sfumata.
- Rimosso il pulsante avatar "AT" dalla barra di navigazione.
- La finestra "Altre info" mostra un riassunto breve del progetto invece del testo lungo.

## v2.6.0
- Case study riorganizzato: testo allineato a sinistra su colonna singola, sommario con metadati (cliente, anno, ruolo, team, durata, strumenti), sezioni numerate 01-06 e processo a passi verticali.
- Selettore lingua: toggle con bandiera italiana e inglese al posto del menu a tendina.
- Rimossi i numeri grandi accanto alle card dei progetti: le copertine occupano tutta la larghezza della card.

## v2.5.0
- Case study Audi: dati reali dalle analytics della libreria (370 componenti, 1.000 variabili, 48 stili, 111 team, 10.400 inserimenti a settimana), durata di 1 anno, sezione "Il mio ruolo", riflessione finale sulla concentrazione dell'adozione.
- Cover dedicata al design system (cockpit e variabili) per card e billboard, con il credito "Audi · Italdesign".

## v2.4.0
- Primo case study reale: Audi Design System al posto del segnaposto "Nido", riscritto con contesto, problema, vincoli dell'automotive, decisioni, sistema, adozione, risultati e riflessione finale.
- I case study ora supportano sezioni libere con elenchi, statistiche e visuali (schema token/componenti/schermate).

## v2.3.0
- Sezione progetti ridisegnata: card più grandi su griglia a 3 colonne, copertine con forme e etichetta del tipo di progetto, pannello hover con la descrizione.
- Risolto il taglio del contenuto in hover (il contenitore con scorrimento orizzontale ritagliava card e pannello).
- Su mobile le card scorrono in orizzontale con i dettagli sempre visibili.

## v2.2.2
- Card dei progetti più piccole (16:9), visibili senza scorrere la pagina, con numero grande in stile Top 10 di Netflix.

## v2.2.1
- I case study occupano tutta la larghezza sulla propria riga e UX Dash è sotto, a tutta larghezza.

## v2.2.0
- UX Dash spostato a destra dei case study, sulla stessa riga (su schermi piccoli va sotto).
- Gli ostacoli sono commenti in stile Figma di clienti e stakeholder ("Puoi ingrandire il logo di 1px?"), in italiano e inglese.
- Sfondo animato: cursori multiplayer che ridimensionano e spostano i frame dietro il gioco.
- Salto più morbido per rendere superabili i commenti più lunghi.

## v2.1.0
- Nuova sezione Giochi con UX Dash, un runner in stile Geometry Dash: gli ostacoli sono i fastidi della UX (cookie banner, popup, captcha, caricamento infinito, 404, lorem ipsum). Record salvato nel browser.

## v2.0.1
- Corretto il pulsante Chiudi del case study, che era coperto dalla barra di navigazione.

## v2.0.0
- Hero ridisegnata come billboard Netflix: barra di navigazione con pillole, ricerca, notifiche e menu profilo (cambio lingua), progetto in evidenza con titolo, metadati, descrizione e pulsanti Riproduci / Altre info.
- "Riproduci" espande il billboard a schermo intero con il case study.
- Riga progetti con hover card (play e info), finestra di dettaglio "Altre info" e ricerca.
- Rimossi TV, particelle e cambio canale.

## v1.1.1
- Hero: testi riscritti, nuova frase di presentazione e pulsanti "Scopri chi sono" e "Contattami".

## v1.1.0
- Navigazione con link e barra che si sfuma allo scroll.
- Nuove sezioni: frase di presentazione, Chi sono, Competenze e strumenti, Esperienza, Contatti con copia email.
- Poster dei progetti con anteprima play al passaggio del mouse e da tastiera.
- Accessibilità: il case study a schermo intero è un dialog e il resto della pagina viene disattivato mentre è aperto.
- Titolo pagina, descrizione, favicon e tag social.

## v1.0.0
- Prima versione del portfolio in stile Netflix: intro, TV nella hero, selettore progetti, case study a schermo intero, toggle IT/EN.
