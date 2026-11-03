# Changelog

Versioning semantico: MAJOR.MINOR.PATCH (es. v1.1.0 = nuova funzione, v1.0.1 = correzione).

## v4.3.0
- Tolto il pulsante play: ora è la proiezione sul parabrezza (centrata nel vetro) ad aprire il progetto, con clic, tap o Invio; al passaggio si avvicina e si illumina.
- Frecce olografiche a sinistra e a destra della proiezione con chevron animati e impulso, per scorrere i progetti (anche con le frecce della tastiera); indicatori a pallini e suggerimento "Clicca la proiezione o trascinaci una card".
- Navigatore animato: la mappa scorre con la velocità e ruota in curva, il percorso fluisce, distanza alla prossima svolta e orario di arrivo aggiornati, freccia di svolta che cambia lato.
- Volante che sterza davvero seguendo la curva con piccole correzioni; frecce di direzione che lampeggiano nel quadro in curva; luce ambiente che respira; scocca che si inclina leggermente in curva.

## v4.2.0
- Abitacolo ridisegnato in SVG per un effetto più realistico: volante sportivo in pelle con cuciture, razze con tasti, palette del cambio, airbag e tacca rossa in alto; il volante gira seguendo la curva della strada.
- Strumentazione digitale nella palpebra dietro al volante (tachimetro ad arco, marcia, temperatura), schermo centrale con navigatore, bocchette d'aria, luce ambiente nel colore del progetto, cuciture sulla plancia.
- Montanti con bordo serigrafato, alette parasole, cielo dell'abitacolo, specchietto interno con riflesso del lunotto e specchietti laterali.
- Guida a sinistra: su mobile l'inquadratura si centra sul volante; leggera vibrazione della scocca in base alla velocità (disattivata con riduzione movimento).
- Titolo dell'ologramma non più tagliato su tablet.

## v4.1.0
- Hero a tutta pagina, senza cornice arrotondata: l'abitacolo parte sotto la barra e il cruscotto sfuma nello sfondo della pagina, con la riga dei progetti che ci sale sopra.
- Strada disegnata con proporzioni reali su qualsiasi schermo (niente deformazioni in verticale).
- Il rilascio delle card vale solo sul parabrezza, non sul fondo sfumato.
- Testo dell'ologramma adattato su mobile.

## v4.0.0
- Hero trasformata nel posto di guida di un'auto sportiva: parabrezza con montanti, tetto e specchietto, cruscotto con volante e tachimetro, strada in prospettiva su canvas con linee, bande d'asfalto, colline e lampioni che scorrono, curva lenta.
- Lo slideshow dei progetti e proiettato sul parabrezza come ologramma (HUD): pannello traslucido con angoli, linee di scansione, sfarfallio e cono di luce dal cruscotto. Tutta la scena prende il colore del progetto in onda.
- Il play apre il progetto mostrato; trascinando una card sullo schermo l'auto accelera a 210 km/h e il quadro diventa rosso.
- Su touch la frase sotto I miei progetti dice "Tocca una card" invece di "Passa sopra".

## v3.3.0
- Nome in alto trattato come un logotipo: maiuscolo, rosso, molto pesante, lettere strette e leggermente allungate in altezza, con ombra. Stesso trattamento nell'intro. Sui telefoni stretti diventa il monogramma AT.

## v3.2.1
- I tre dati della sezione Chi sono ora raccontano il percorso invece di un progetto: anni di esperienza, paesi, settori.

## v3.2.0
- UX Dash in verticale su mobile (21:31): campo di gioco, fisica del salto, velocita e a capo dei commenti ricalcolati perche gli ostacoli restino superabili.
- Sezione rinominata da "Giochi"/"Games" a "UX Dash".
- Corretti i link della barra che andavano a capo tra 760 e 1024px: testo su una riga sola e barra scorrevole in orizzontale se lo spazio non basta.

## v3.1.0
- Header del case study: resta sfumato in cima e diventa pieno e sfocato appena si scorre, cosi il testo non ci passa sotto.
- Responsive rivisto su tre soglie: tablet a 1024px (case study su due colonne), mobile a 760px (case study in colonna, pannelli sempre aperti), telefoni stretti a 420px.

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
