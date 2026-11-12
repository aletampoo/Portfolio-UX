# Changelog

Versioning semantico: MAJOR.MINOR.PATCH (es. v1.1.0 = nuova funzione, v1.0.1 = correzione).

## v9.14.2
- Fewer hero particles: start at about 30% density and fade up over ~9 s; steady state slightly lower.

## v9.14.1
- Hero particles start already at their steady density (pre-warmed, constant spawn rate) instead of an initial burst.

## v9.14.0
- Restored the previous background (dot grid + cursor spotlight) on the site and in case studies; particles now only come out of the hero frame, stronger on hero hover.

## v9.13.1
- Homepage particles calmer at rest (about half intensity); hovering the hero brings them up to full strength. Case studies unchanged.

## v9.13.0
- Hovering the hero boosts the particles: more spawn from the frame and all particles get brighter, easing back on leave.

## v9.12.2
- Particle background slightly more intense: more particles, higher opacity and halo, site-wide and in the hero emitter.

## v9.12.1
- Particle-field background also inside case studies (canvas moves into the case study layer; parallax follows the case study scroll).

## v9.12.0
- Site background is now a full-page particle field (depth, scroll parallax, gentle cursor push) replacing the dot grid and spotlight.

## v9.11.0
- Subtle particles that drift out of the hero frame and fade behind the content; hero background made transparent so they show through.

## v9.10.5
- "Recruiter" cursor tag back to the previous shape, now see-through like the "Go to projects" button: translucent blue tint, light-blue 1.3px border, light text. Holographic version removed.

## v9.10.4
- "Recruiter" cursor tag now holographic: iridescent gradient (blue, lilac, pink, yellow, mint, same palette as the pixel intro) with a glossy top highlight.

## v9.10.3
- "My journey" timeline redesigned: each stop is a pill (city · year) linked by a dashed line; "Turin · Today" highlighted with the hero gradient, glow and a pulsing dot; pills lift on hover. On mobile the pills wrap without the line.

## v9.10.2
- Info window (i button on cards) takes the case study's accent colour: border and glow, close and Play buttons, client label, Role/Duration/Tools labels, tinted bottom panel. Orange for the AI case study, blue for the design system, violet for NatWest.

## v9.10.1
- First card: removed the "AI-powered" chip, only the rotating holographic stroke remains.

## v9.10.0
- First project card highlighted as AI work: holographic "✦ AI-powered" badge (shimmering iridescent gradient, same palette as the pixel intro) and a slowly rotating holographic border. Border hides on hover so the Netflix-style hover stays clean; static with reduced motion.

## v9.9.2
- Updated CV (EN, November 2026) behind every Download CV button; link has a version query so browsers don't serve the old cached file.

## v9.9.1
- Intro lasts 2.2s: pixels appear over ~0.9s, the LOADING bar fills over ~1.9s, then the intro dissolves.

## v9.9.0
- New intro, no longer repeating the hero: an 8-bit "AT" monogram built from holographic pixels (iridescent gradient with hue shift) that pop in one by one, a pixel LOADING bar, and the pixels dissolve when the intro ends. Same ~1s, click to skip; static with reduced motion.

## v9.8.4
- Clean URL: in-page links (nav, logo, "Go to projects") smooth-scroll to their section without adding #top, #row, #about… to the address. A link opened with a hash still lands on the section, then the hash is removed.

## v9.8.3
- Case study opening: "EPISODE n" label in the hero light blue (#9cd4f1, soft glow) instead of Netflix red.

## v9.8.2
- "Recruiter" cursor label redesigned like a Figma multiplayer tag: snug to the arrow, square top-left corner pointing at it, 6px radius elsewhere, thin light top highlight, semibold 11.5px text.

## v9.8.1
- "Recruiter" cursor label: solid light blue (#9cd4f1) instead of gradient; the arrow keeps the gradient.

## v9.8.0
- Cursor is now a Figma-style multiplayer cursor with a "Recruiter" label, in the hero name gradient (white to light blue), on the whole site including links and cards. Mouse only; text fields keep the text cursor.

## v9.7.0
- Intro restyled to match the site: near-black dot-grid canvas (no blue glow or line grid), "Alessio Tampone" in the hero gradient (no glitch effect), a Figma frame with handles drawn around name and role, and the blue "Alessio" cursor gliding in. Same ~1s duration, click to skip.

## v9.6.0
- Custom cursor (mouse only): a dark arrow with a light outline, like the Figma pointer; over links, buttons and cards it turns blue with a small dot. Text fields keep the text cursor; touch devices unchanged.

## v9.5.3
- Background cursor spotlight made more subtle: lit dots at about 40% and the soft glow at 50% of their previous strength.

## v9.5.2
- AI case study title: "AI connects, you decide" (IT: "L’AI collega, tu decidi"), on the card and in the case study.

## v9.5.1
- AI case study, "The process": shorter and clearer English (about a third shorter), same five steps. IT updated to match.

## v9.5.0
- AI case study: new "Prototype in code" step in the process (design ideas iterated with Claude directly in code for the real look and feel, tested in the browser, brought into the real software only once everything worked with the developers). New trade-off on prototyping in code instead of static mockups. Tools: Figma, Claude. Trade-offs subtitle no longer says "Two". IT/EN.

## v9.4.6
- Card hover: the border around thumbnail + info panel is now drawn once (one rounded 1px stroke with a soft glow in the project colour), so the left and right strokes line up exactly. Thin gradient divider between thumbnail and panel.

## v9.4.5
- Card hover cleaned up: thumbnail and info panel now read as one card (one continuous coloured border, one shadow, no corner brackets or glow at the join).

## v9.4.4
- Relations case study, "The process" simplified into four steps (Understand, Design, Test, Deliver), with AI inside the Design step and the rule "AI suggests, people decide". IT/EN.

## v9.4.3
- Project card hover (desktop), Netflix style: the card scales up and the info panel opens below the thumbnail (play and info buttons, year in green and type, tagline), so it never covers the name and subtitle. Mobile unchanged.

## v9.4.2
- Relations screens simplified: no page subtitle, no minimap, no footnote under Item types; AI assistant without tabs and confidence bars (just "94% match"), one "Accept both suggestions" button.

## v9.4.1
- Relations screens: cleaner "Item types" panel in every screen (one grouped list instead of separate boxes, count badge instead of the repeated "on map" label, no drag handles, compact AI entry, quieter footnote).

## v9.4.0
- Relations case study retold around AI in the product: "AI that links the tickets" (IT: "L'AI che collega i ticket"). AI at three moments of the flow: from text to items, relation type suggested while linking, assistant with suggestions (reason + confidence) and consistency checks. Principle: AI suggests, people decide. New trade-offs, role, process, outcome, looking back. IT/EN.
- New screens: rel-cover (AI assistant on the map), rel-gen (create items from text), rel-props (relation properties, the old cover). Picker shows "AI suggested"; library has an "Items from text" AI entry.

## v9.3.2
- Nav logo ("ALESSIO TAMPONE" on desktop, "AT" on mobile) now uses the hero name style: white to light-blue gradient with a soft blue glow, instead of red.

## v9.3.1
- Relations case study, "My role" rewritten with senior ownership: framing the problem, interaction model and rules, every state, 8-user usability tests, design QA through to release. IT/EN.

## v9.3.0
- Projects order: Relations (Italdesign) first, then Design system (Italdesign), then NatWest. The Bugzer case study is hidden (data kept in the file, easy to bring back). Grid back to 3 columns.

## v9.2.2
- Case study galleries ("The work"): images stacked vertically at full width, in every case study.

## v9.2.1
- Case study highlights: the Figma-frame boxes are replaced by a simple underline in the project colour (2px gradient line, semibold text).

## v9.2.0
- All case studies: key phrases highlighted with the Figma-frame style used in Experience (challenge, role, process, outcome, looking back), IT/EN.
- All case studies: key numbers shown as stat cards in "The outcome".
- Relations case study: post-launch and test metrics added (100% task success in the final round, up from 6/8; −64% wrong relations in 2 months; 5× faster, 1m 40s → 20s). These are ESTIMATES to replace with real data.

## v9.1.1
- Relations case study: year 2026; "My role" rewritten; usability tests with 8 users (task success rate and error rate) described in the process; removed the line about improving the UI for the portfolio. Post-launch metrics still to add (waiting for real numbers).

## v9.1.0
- New 4th case study: Italdesign "Relations you can see" (IT: "Relazioni che si vedono"). Advanced relations between tickets in the internal project-management tool: drag & connect map, relation picker, rules list. Feature design, testing and delivery.
- Four new screens with improved UI, built from the original Figma screens: rel-cover, rel-connect, rel-picker, rel-list (3200×1800 webp).
- Projects grid is 2×2 on desktop now that there are four cards.

## v9.0.5
- Spotlight fix, part 2: the lit dots layer no longer uses a full-screen mask either. It's a 520px round element that follows the cursor, with its dot pattern offset so it stays aligned to the background grid. No full-screen gradients or masks follow the cursor anymore, so there's nothing left for the browser to split into tiles.

## v9.0.4
- Fix background spotlight glitch: the soft glow was a full-screen radial gradient that the browser cut off with a hard vertical/horizontal edge around the middle of the screen. It is now a fixed-size round glow (1040px) moved with transform, so no edges and cheaper to repaint.

## v9.0.3
- About me shortened: two short paragraphs (role, experience and focus; daily AI use). IT/EN.

## v9.0.2
- Hero headline from Alessio's sentence, polished: "Product designer shaping design systems and UX/UI for fintech, automotive and SaaS." (IT: "Product designer che costruisce design system e UX/UI per fintech, automotive e SaaS.").

## v9.0.1
- Hero headline simplified to one line: "Product designer focused on design systems and AI-powered workflows." (IT: "Product designer specializzato in design system e flussi di lavoro con l’AI.").

## v9.0.0
- New background for home and case studies: no more blurred colour blobs and line grid. Now a near-black canvas with a fine dot grid (like a design tool canvas) and light grain. With a mouse, a spotlight follows the cursor and lights up the dots around it, tinted with the project colour (changes on card hover). On touch devices only the static dot grid.

## v8.14.0
- About me: added a second paragraph on using AI every day (research, ideas, prototypes and code faster; the decisions stay mine). IT/EN.

## v8.13.1
- Hero headline polished, first person: "I design digital products on design systems that scale, with AI built into my workflow. Automotive, fintech and enterprise." (IT to match).

## v8.13.0
- Hero headline rewritten to focus on product design, design systems and AI in the design workflow (EN: "Product design built on strong design systems, with AI in the workflow. For automotive, fintech and enterprise products."; IT version to match).

## v8.12.2
- Removed the intro eating/plates animation (v8.12.0 and v8.12.1). The intro is back to the v8.11.1 version: logo, name and role, 1.05s.

## v8.12.1
- Intro: the eater is now an original abstract character (inline SVG blob with blue-violet gradient, antenna, blinking eyes, chomping mouth) instead of Alessio's avatar.

## v8.12.0
- Intro: under the logo, name and role, a loading gag with Alessio's avatar eating from a bowl (chewing bob, crumbs) while plates stack up on both sides, with a "Loading · n plates" counter ("Caricamento · n piatti" if Italian was chosen). Original animation, no game characters. Intro now lasts 2.1s instead of 1.05s; still skippable by click; hidden with reduced motion.

## v8.11.1
- Sound on mobile: the audio context is unlocked inside the tap (silent buffer + resume), so the ta-dum also plays on iOS/Android after the scroll-to-hero delay. On iOS the audio session is set to "playback" where supported, so it isn't muted by the silent switch.

## v8.11.0
- Project cards: the case study title (e.g. "One system, many cars") now sits under the client name. Also included in the card search text.

## v8.10.0
- Hidden from search engines: robots meta tags (noindex, nofollow, noarchive, nosnippet, noimageindex) in the page, and an X-Robots-Tag header on every file (index, images, CV PDF) via _headers. No robots.txt Disallow on purpose, so crawlers can read the noindex rule. The site stays reachable by link.

## v8.9.0
- Info modal (i button on project cards) now shows the case study cover image (himg), with a dark gradient so title and Play stay readable.

## v8.8.1
- Project info modal: removed the grey box behind the Play button (a badge style named .bt was also being applied to the button row).

## v8.8.0
- Hero: removed the video player controls (progress bar, play/pause, ±10s, volume, title, time, subtitles, fullscreen). Frame padding back to normal; desktop gap to Projects re-tuned to about 70px. The case study opening (cover in the frame, then fade) is unchanged.

## v8.7.1
- Italdesign "One system, many cars" case study: role is now Senior Product Designer (IT/EN).

## v8.7.0
- English is the default language on every device (no more auto-detect from the browser or old saved setting); Italian only if the visitor picks it with the toggle.
- Mobile: the hero frame starts below the header (no overlap) and the hero height follows the frame, so the gap to Projects is about 70px on every phone.
- Removed the "97% match" labels from the project cards.
- Shorter case study opening (about 1.3s instead of 2.1s).

## v8.6.0
- Simpler case study opening: the episode plays inside the hero player (cover image, "EPISODE n", title, red progress bar, player title updated), then fades to black and opens full screen with a fade-in. Synthesized "ta-dum" sound (Web Audio, not the original Netflix audio). Replaces the ribbon intro from v8.5.0.

## v8.5.1
- Bigger gap between the hero and Projects on desktop (about 70px, was about 7px).

## v8.5.0
- Case study opening: Netflix-style intro inside the hero (red ribbons, "EPISODE n" + title + headline, red progress bar), then the hero expands into the case study. Scrolls to the hero first if needed; stops the cursors easter egg; skipped with reduced motion.

## v8.4.0 — Hero as a Netflix-style player

- Hero keeps the Figma build animation and easter eggs, and adds a Netflix-style player bar: red progress synced to the animation, replay, back/forward 10s (forward goes to projects), title "S1:E1", time, subtitles and full screen.

## v8.3.3 — NatWest: sharper images, copy aligned with Rooster Money

- Rooster Money cover and boards re-rendered at 3200×1800 with light sharpening.
- Case study copy rewritten so it explains Rooster Money and where gifting fits; captions say which boards show the gifting context and which show the rest of the app.

## v8.3.0 — NatWest: Rooster Money cover and The work by feature

- New cover: two Rooster Money phones (chores and pots) on the site background.
- The work rebuilt by feature, each board full width: virtual pocket money (accounts, pots, transactions, boosts), chores (list, edit, repeat), approval and allowance.

## v8.2.0 — Rooster Money screens in the NatWest case study

- The work (NatWest) now shows the official NatWest Rooster Money app screens, restyled on the site background: goals, family and chores; card, balance and spending limits.

## v8.1.1 — Theme names blurred

- Drive mode / theme names blurred in the variables visual.

## v8.1.0 — Variables visual, no image links

- Gallery images in case studies are no longer links (no new tab, no ↗).
- New custom visual of the semantic variables (one name, four drive modes) at the end of The work, full width.

## v8.0.8 — Climate screen

- The tokens image in The work replaced with the climate controls screen (steering wheel logo blurred).

## v8.0.7 — Gallery cleanup

- Removed "Components in their four states" from The work in the design system case study.

## v8.0.6 — New list screen

- "List with tabs and selection" in The work now uses the new list screen.

## v8.0.5 — New parking assist screen

- "Parking assist" in The work now uses the new screen; brand logos on the cars blurred.

## v8.0.4 — New home screen in The work

- "Home with widgets, media and climate" now uses the new home screen.

## v8.0.3 — New navigation screen in The work

- First image of The work (design system case study) replaced with a navigation screen; brand logos on the map blurred.

## v8.0.2 — New cover for the design system case study

- Cover of the first case study replaced with a cockpit photo (steering wheel logo blurred), full width 16:9.

## v8.0.1 — Netflix-style project cards

- Project cards back to the Netflix style: 16:9 thumbnail with the holographic name; on hover the card grows and shows the tagline, play and info buttons, match, year and type.
- 3 columns on desktop, 2 on tablet, 1 on mobile.

## v8.0.0 — New hero and About features

- New hero: a Figma cursor builds the name, tokens and buttons, then settles into a clean frame as wide as the content; buttons: Go to projects, LinkedIn, Download CV.
- Easter eggs: click the hero to invite the team (cursors comment and live-edit the page, then everything resets; click again to stop); ⌘/Ctrl+Y toggles Figma outline mode.
- About: journey timeline merged into the animated heading line; new "Your team, with and without Alessio" simulator (switch, confetti, illustrative numbers).
- Experience timeline no longer clipped; LinkedIn button removed from About; smaller gap between hero and Projects.
- Hidden, not deleted: the 2x2 positioning matrix (with PNG export) and the peeking mascot.

## v7.5.6 — Case study order

- Swapped case studies 2 and 3: the Bugzer redesign now comes second, NatWest third.

## v7.5.5 — Projects heading

- Home section heading renamed from "Case studies" to "Projects" (IT: "Progetti").

## v7.5.4 — LinkedIn button label

- The About button now just says "LinkedIn".

## v7.5.3 — Experience timeline fix

- The experience timeline inside the dropdown was clipped on the left; added left padding.

## v7.5.2 — No numbers on home cards

- Removed 01/02/03 from the case study cards on the home page.

## v7.5.1 — No numbering in case studies

- Removed 01/02 numbering from section titles, contents, gallery captions and trade-offs.
- Trade-offs use a small glowing holographic diamond as a bullet.

## v7.5.0 — Plain-language case studies

- Process is now a short paragraph, like the other sections.
- Trade-offs: a simple numbered list, each with the choice in bold and one sentence on what it cost and why.
- All case study copy rewritten in plain, simple Italian and English.

## v7.4.0 — Simpler process and trade-offs

- Process: three side-by-side steps (stack on mobile), each with a step label, a one-line heading and one or two short sentences.
- Trade-offs: no cards or strikethrough; each shows the choice, "instead of…", then Why and The cost in two short lines.
- Shorter IT/EN copy for both sections.

## v7.3.1 — Case study copy

- Rewrote all three case studies in IT and EN: openings now say what I did and the outcome; the challenge ends on the core question; clearer role, process, result and looking-back sections.
- Trade-offs reworded, and the Bugzer "looking back" no longer contradicts its trade-off.
- Facts and numbers unchanged.

## v7.3.0 — Copy review IT/EN

- Native-speaker pass on all visible copy, in Italian and English: hero, About, journey, CV dropdown, case cards, case studies, trade-offs, experience bullets and footer.
- Hero label and page title now say Senior Product Designer.
- Case-study sections renamed: The work / The outcome / Looking back (Il lavoro / Il risultato / In retrospettiva); "Back to menu" becomes "Back to projects".
- "gifter" becomes "gift-giver"; the CV summary no longer gives an inaccurate company count.
- No facts, numbers or [[frame]] markers changed.

## v7.2.1
- Case study: intestazione (titolo, introduzione, dati, etichette) larga quanto la copertina.

## v7.2.0
- Case study: blocco "I trade-off" alla fine di "03 Il processo", con due compromessi per progetto, ognuno strutturato in Ho scelto / Invece di (barrato) / Il prezzo / Perché.

## v7.1.1
- Case study: colonna del contenuto più larga (da 820 a 940 px) e pagina fino a 1280 px.

## v7.1.0
- Case study: immagine di copertina sotto l'intestazione, in una cornice luminosa con didascalie (non più ripetuta nella galleria).
- Indice fisso a sinistra mentre si scorre, con la sezione attiva evidenziata; su tablet e mobile torna sopra il contenuto.

## v7.0.0
Case study ristrutturati sul modello fredux.design/telepass, tutti e tre con la stessa struttura:
- Intestazione: riga terminale "A:\CLIENTE> type progetto.htm", titolo, introduzione, dati (Cliente, Anno, Ruolo, Team), etichette e badge "CLIENTE.DSK · N file".
- Indice numerato 01–06 con link alle sezioni.
- 01 La sfida, 02 Il mio ruolo (un paragrafo ciascuno), 03 Il processo (tre passi "titolo: sottotitolo" con descrizione), 04 Il lavoro, in sintesi (galleria con didascalie numerate 04.1… e ↗ per aprire l'immagine), 05 Il risultato, 06 Cosa resta.
- Chiusura: progetto precedente e successivo, "Torna al menu", "Scrivimi su LinkedIn ↗", piè di pagina terminale con Esc e ← → per cambiare progetto (anche da tastiera).
- Tolti dai case study "In breve", competenze, prima/dopo, metriche e placeholder.

## v6.7.1
- Primo case study (design system automotive): nome "Italdesign" al posto di "Alten".

## v6.7.0
- Nuova intro di 1,5 secondi: una linea di luce attraversa lo schermo, un anello olografico si disegna attorno al monogramma "AT", il nome si rivela da sinistra a destra con "Senior Product Designer" sotto, poi l'intro si chiude a iride sul sito. Clic per saltarla; con riduzione del movimento dura 0,2 s.

## v6.6.6
- Primo case study: nome "Alten" al posto di "Audi" (card, intestazione, "Progetto successivo").

## v6.6.5
- Case study: rimosso il sottotitolo sotto il titolo della sezione.

## v6.6.4
- Case study: rimossa la riga "Altri progetti, anche sotto NDA, li racconto volentieri in fase di colloquio".

## v6.6.3
- Chi sono: la descrizione viene prima della timeline "Il mio percorso".

## v6.6.2
- Chi sono: rimossa (nascosta) la sezione "Cosa dicono i colleghi".

## v6.6.1
- Chi sono: tolto il pannello di sfondo dietro la descrizione; il testo sta direttamente sulla pagina.

## v6.6.0
- Case study più in evidenza: titolo di sezione "Case study" più grande con sottotitolo "Tre progetti scelti, raccontati dal problema al risultato". Card alte e sempre leggibili (senza bisogno di hover): numero, focus, nome del cliente olografico grande, headline, numero chiave del risultato (111 team, 70%, 49 → 31), anno e ruolo, "Apri il case study →". Al passaggio la card si alza e si illumina; apribili anche da tastiera.

## v6.5.0
- Esperienza e Formazione raccolte in un pannello a scomparsa olografico ("Esperienza e formazione · 4 ruoli in 3 aziende · MSc in User Experience Design"), chiuso di default. Si apre con un'animazione morbida e la freccia che ruota; le voci Esperienza e Formazione del menu lo aprono e scorrono alla sezione. I cursori Figma partono all'apertura.

## v6.4.3
- Chi sono: rimossa (nascosta) la sezione "Come lavoro".

## v6.4.2
- Cosa dicono i colleghi: sezione semplificata. Quattro citazioni brevi in una riga, ognuna con una linea luminosa a sinistra, nome e ruolo; tolti pannelli, iniziali, virgolette decorative e la riga sul rapporto di lavoro.

## v6.4.1
- Ologramma: vetro sfocato e più scuro dietro nome e headline, così la strada e le linee non disturbano la lettura.

## v6.4.0
- Rimosse (nascoste) le sezioni "Su cosa sono forte" e "Competenze e strumenti".
- Chi sono: descrizione ridotta a tre frasi, testo più grande.
- Pulsante "Scarica il CV" accanto a LinkedIn (public/Alessio-Tampone-CV.pdf).

## v6.3.0
- Hero: abitacolo (plancia, volante, specchietto) ridotto; l'ologramma con nome e headline è più grande e al centro del parabrezza. Rimossa l'etichetta "Clicca per vedere i progetti".

## v6.2.6
- Ologramma su mobile: il riquadro si adatta all'altezza del testo, così etichetta, nome e headline restano dentro la cornice.

## v6.2.5
- Su cosa sono forte: padding uniforme di 28 px nelle schede, più spazio tra titolo e punti e tra un punto e l'altro.

## v6.2.4
- Su cosa sono forte: tolti i numeri 01, 02, 03 dalle schede.

## v6.2.3
- Su cosa sono forte: tolta la frase sotto il titolo di ogni scheda; restano numero, titolo e punti.

## v6.2.2
- Ologramma: headline riscritta in linea con i case study, "Design system e UX per automotive, fintech e tool enterprise".

## v6.2.1
- Il mio percorso: l'etichetta "Oggi" non viene più tagliata in alto; tutte le date hanno la stessa altezza e la linea passa al centro delle icone.

## v6.2.0
- Chi sono: timeline orizzontale "Il mio percorso" sopra il testo: 2017 Torino, 2018–2021 Cambridge, 2022 Loughborough, 2023 Londra, oggi Torino. Ogni tappa ha un'icona al tratto luminoso del monumento simbolo (Mole Antonelliana, King's College Chapel, Carillon Tower, Elizabeth Tower), con un impulso di luce che scorre sulla linea e la tappa attuale evidenziata. Su mobile scorre in orizzontale.

## v6.1.0
- Su cosa sono forte: spostata sotto i progetti, solo titoli, frase e punti (tolti i blocchi delle prove).
- Chi sono: nuova sezione "Cosa dicono i colleghi" con quattro raccomandazioni LinkedIn (Pooja Sehgal, Reuben Valpy-White, Gareth Byrne, Nunzio Digregorio) in schede olografiche con iniziali, ruolo e rapporto di lavoro.
- Competenze e strumenti: da cinque pannelli con chip a una scheda tecnica compatta, una riga per area con le voci separate da "/" che si illuminano al passaggio del mouse.

## v6.0.1
- Su cosa sono forte: le prove nei pilastri non sono più link ai case study.
- I miei progetti: card senza copertina, con il nome del progetto al centro in stile olografico.
- Dal laboratorio: sezione nascosta per ora (contenuto mantenuto).
- Come lavoro: testi delle schede ridotti a una riga.

## v6.0.0
Applicato il feedback di un design manager: mostrare a colpo d'occhio su cosa sei forte.
- Headline dell'ologramma: "Design system, ricerca utente e AI per prodotti complessi".
- Nuova sezione "Su cosa sono forte" prima dei progetti: tre pilastri (Design system, Prodotto e ricerca utente, AI nel processo di design), ognuno con come lo fai e una prova che porta al progetto.
- Progetti etichettati per focus (Audi: design system e visual; NatWest: UX di prodotto e ricerca; Italdesign: ricerca utente e analisi) e riga "altri progetti in fase di colloquio".
- Case study: "Competenze in questo progetto" all'apertura, scheda "Contesto" in "In breve", ultima sezione evidenziata come "Riflessioni".
- Nuova sezione "Dal laboratorio: questo portfolio" sul flusso con l'AI (Claude, Higgsfield, R3).
- "Come lavoro" in Chi sono: team, metodo Agile/SCRUM, lingue ed esperienza nel Regno Unito, formazione continua (placeholder).

## v5.17.0
Case study più solidi, su tutti e tre i progetti:
- "Cosa ho fatto io / Con il team" nella sezione del ruolo.
- Un artefatto di processo per progetto (struttura dei token, sketch e Crazy 8s, estratto dell'audit), per ora come placeholder.
- "Prima e dopo" con tre note numerate in stile frame Figma che spiegano le decisioni. Italdesign con le immagini reali; Audi e NatWest con il "prima" come placeholder.
- Italdesign: "Prima e dopo, in numeri" con tre metriche da inserire (tempo per esportare un report, errori per sessione, SUS). L'interfaccia originale si è spostata dalla sfida al prima/dopo.
- Placeholder riconoscibili: bordo tratteggiato, righe diagonali, etichetta "Immagine da inserire" / "Dato da inserire".

## v5.16.1
- Card Audi: rimosso il logo Alten dalla copertina.

## v5.16.0
- Esperienza: quando un'esperienza entra nello schermo, un cursore stile Figma con etichetta colorata (Alessio, Dev, PM, Research) si sposta sulle parti chiave una alla volta e le seleziona: il frame compare con bordo, maniglie e l'etichetta "Frame" per un attimo. Ogni esperienza ha il suo cursore. Disattivato con riduzione del movimento.

## v5.15.0
- I tre progetti prendono il nome del cliente: Audi, NatWest, Italdesign (card, intestazione, "Progetto successivo").
- Apertura dei case study: al posto del nome, un titolo-headline grande in peso medio con alone luminoso nel colore del progetto ("Un sistema, tante auto", "Regali che restano", "Meno attrito, più analisi"), con la descrizione sotto in tinta.

## v5.14.1
- Bugzer: aggiunti gli strumenti (Figma, Crazy 8s) e la sezione 06 "Cosa farei dopo" con quattro lezioni coerenti con il case study.

## v5.14.0
- Terzo case study: Bugzer per Italdesign (2026, Senior Product Designer, 2 designer, 6 mesi) al posto di Fiore, con la stessa struttura: In breve, La sfida con l'interfaccia originale ("Prima"), Il mio ruolo, Il processo in 4 passi, La soluzione con quattro schermate del redesign, Il risultato (49 problemi, 31 schermate, 5 flussi). Immagini scontornate dallo sfondo trasparente e ottimizzate (bug-hero, bug-before, bug-states). Colore ciano.

## v5.13.2
- GiftIt: schermate ricomposte senza le bande nere tra un telefono e l'altro (sfondo trasparente, spazi più stretti, ombra sui singoli schermi). Logo e nome del cliente sfocati in tutte le schermate e nell'immagine principale, compreso l'indirizzo nella barra del browser.

## v5.13.1
- GiftIt: immagine principale con i due schermi del compleanno di Jake (anche come copertina della card nella home) e, nel risultato, galleria "Schermate del prodotto" con le quattro righe di schermate a tutta larghezza: scartare i regali, il regalo svelato, ringraziare e timeline, imparare (risparmio, spesa, investimento). File: public/gift-hero.webp, gift-row1..4.webp.

## v5.13.0
- Secondo case study: GiftIt per NatWest (2023, Product Designer, 3 designer, 6 mesi) al posto di Pulse, con la stessa struttura del primo: apertura con dati, etichette e "In breve", poi La sfida (5 obiettivi), Il mio ruolo, Cosa abbiamo scoperto (3 insight → scelte), La soluzione (bambino, genitore, chi regala), Il risultato (70% dei bambini attivi in 3 settimane) e Cosa farei dopo. Testi in italiano e inglese, colore viola. Immagine principale ancora da inserire.

## v5.12.2
- Chi sono: al posto della ricerca "seduto in auto con gli utenti", un passaggio che evidenzia, oltre ai design system, la progettazione UX/UI end-to-end e il design thinking.

## v5.12.1
- Schede dei case study (vincoli, ruolo, scelte chiave, risultato): griglia che riempie sempre le righe. 3 schede in tre terzi, 4 in 2×2, 5 in 3 + 2. Prima, con la colonna più larga, l'ultima riga restava con una scheda isolata o una a tutta larghezza. Tablet: due colonne; mobile: una colonna.

## v5.12.0
- Case study automotive: l'immagine principale nella cornice è ora il mockup reale con i due display (navigazione e home con Automatic Smart Entry, media e clima), ritagliato e scontornato dallo sfondo chiaro, con ombra e alone nel colore del progetto. La copertina generata resta come sfondo della card nella home. File: public/ds-hero.webp (120 KB).

## v5.11.1
- Card dei progetti: i dettagli al passaggio del mouse ora compaiono dentro la card, in basso (titolo, descrizione, pulsanti, dati), invece del pannello che scendeva sotto la card e copriva la sezione "Chi sono". Cursore a mano invece che "afferra" (il drag è stato tolto). Il titolo della card con copertina non finisce più sotto il logo Alten.

## v5.11.0
- Nuova apertura dei case study, al posto della copertina a tutto schermo: riga in stile terminale con cursore lampeggiante, titolo grande con alone, descrizione breve, dati del progetto in una fascia con divisori (Cliente, Anno, Ruolo, Team, Durata, Strumenti), etichette, "In breve" e poi l'immagine del progetto in una cornice luminosa ridotta con griglia e didascalie in monospace. La colonna dei case study passa da 780 a 1080 px.

## v5.10.1
- Case study: testi in peso regular e più chiari (lead bianco, paragrafi e schede quasi bianchi) e a tutta larghezza della colonna, senza il limite di caratteri per riga.

## v5.10.0
- Case study automotive, "Il risultato": nuova galleria "Schermate reali" con tre schermate dell'interfaccia in produzione (home con widget e clima, assistente al parcheggio con telecamera, lista con tab), ritagliate dall'immagine fornita e senza la cornice bianca. Prima immagine a tutta larghezza, le altre due affiancate; una colonna su mobile. File: public/ds-real-home.jpg, ds-real-park.jpg, ds-real-list.jpg.

## v5.9.0
- Case study automotive, sezione "Il sistema": i tre schemi grigi sono sostituiti da tre immagini generate con Higgsfield nello stile olografico del sito: Tokens (campioni di colore, spaziature, raggi, chip "Aa"), Components (pulsanti nei quattro stati, interruttori, cursori, liste, ricerca) e Screens (cruscotto, clima, impostazioni, profilo). Layout: Tokens e Components affiancati, Screens a tutta larghezza; una colonna su mobile. Rimosso il watermark di Higgsfield ritagliando il bordo inferiore. File: public/ds-tokens.jpg, ds-components.jpg, ds-screens.jpg (~60 KB l'una).

## v5.8.0
- Nuova sezione Formazione / Education, identica a Esperienza (timeline con nodi luminosi e impulso), con voce nel menu: MSc User Experience Design (Loughborough University, 2021–2022), BSc International Business & Management (Anglia Ruskin University, Cambridge, 2017–2019), Diploma (IIS Europa Unita, Chivasso, 2010–2016).
- Rimosso il drag and drop delle card sul parabrezza: le card si aprono con un clic. Il suggerimento sotto l'ologramma diventa "Clicca per vedere i progetti".

## v5.7.0
- La home usa lo stesso sfondo dei case study: base quasi nera, griglia sottile, grana leggera e tre aloni sfocati che si muovono lentamente. Il colore segue il progetto proiettato sul parabrezza e cambia con una transizione morbida passando sulle card. Sostituisce il vecchio alone sotto i progetti.

## v5.6.2
- Chi sono: il pannello con il paragrafo occupa tutta la larghezza della sezione.

## v5.6.1
- Case study automotive: "Il cliente · Alten" / "The client · Alten" diventa solo "Alten" (card, copertina e metadati).

## v5.6.0
- Copertina del case study Automotive Design System generata con Higgsfield (Nano Banana Pro, 16:9): abitacolo di un'auto sportiva di notte con componenti del design system proiettati come ologrammi sopra la plancia. Lo stemma sul volante è stato rimosso per mantenere anonimo il cliente.
- La copertina è usata nella card del progetto (logo Alten spostato in basso a destra) e come sfondo della copertina del case study, scurita per la leggibilità del titolo. File: public/cover-automotive.jpg (113 KB).

## v5.5.0
Case study Automotive Design System riscritto per essere letto in fretta.
- Testi ridotti di circa la metà, in italiano e in inglese: ogni sezione apre con una frase, il resto è in punti brevi.
- Nuovo blocco "In breve" sotto i metadati: Problema, Soluzione e Risultato in tre pannelli affiancati.
- Vincoli, ruolo e fattori di adozione in schede su due colonne, con il titolo in evidenza e una riga di spiegazione.
- "Il processo" diventa "Le scelte chiave": cinque schede numerate in griglia invece di una lunga lista verticale.
- Sezioni rinominate dove serviva ("Il sistema", "Cosa farei dopo"); Tokens Studio aggiunto agli strumenti.

## v5.4.0
- Intro olografica: su uno sfondo blu notte con griglia, un proiettore accende un fascio di luce dal basso e la proiezione si apre da una linea sottile con un breve sfarfallio. Dentro compaiono "Portfolio", il nome lettera per lettera (bianco con alone e leggera aberrazione cromatica, come l'ologramma della hero), "Product Designer" e una barra di caricamento; una banda di scansione attraversa lo schermo. In chiusura la proiezione sale e si rimpicciolisce, come se andasse a posarsi sul parabrezza.

## v5.3.2
- Finestra "Altre info": il pulsante di chiusura torna nell'angolo in alto a destra (lo stile olografico lo aveva spostato nel flusso della pagina).

## v5.3.1
- Comparsa degli elementi più morbida: niente più scansione e sfarfallio, solo una dissolvenza con leggera sfocatura e un piccolo bagliore che si spegne, con un ritardo più breve tra un elemento e l'altro.

## v5.3.0
Il linguaggio olografico diventa il design language di tutto il sito.
- Comparsa "materializzata": titoli, paragrafi, pannelli, esperienze e blocchi dei case study appaiono allo scroll con una scansione dall'alto, un lampo di luce e un leggero sfarfallio, uno dopo l'altro.
- Titoli di sezione con rombo luminoso che pulsa e una linea su cui scorre un lampo di luce.
- Chi sono, gruppi di competenze, metadati, punti elenco e risultati dei case study in pannelli di vetro colorato con staffe agli angoli che si allungano al passaggio del mouse; chip delle competenze olografiche.
- Esperienza: timeline con nodi luminosi pulsanti e un impulso di luce che scorre lungo la linea; puntini e azienda nel colore olografico.
- Case study: cornice a staffe intorno alla copertina con una banda di scansione che scende, "Now playing" come chip luminoso, numeri delle sezioni in chip olografici, passaggi del processo come nodi luminosi, barra di avanzamento e mockup nel colore del progetto, numeri dei risultati che contano fino al valore finale.
- Finestra "Altre info" in vetro colorato. Pulsante Chiudi senza a capo su mobile.

## v5.2.0
- Tile dei case study in stile olografico: vetro scuro tinto col colore del progetto, bordo luminoso, staffe agli angoli, mockup disegnati come linee di luce, titolo con alone, etichetta e pannello dei dettagli in vetro colorato.
- Al passaggio del mouse la tile si illumina, le staffe si allungano e una banda di luce scorre dall'alto in basso come una scansione; i pulsanti della tile prendono il colore del progetto.

## v5.1.2
- Menu: la voce attiva segue lo scroll in modo affidabile. "Progetti" si evidenzia mentre le card sono a schermo e anche dopo il clic sulla voce; nessun momento senza voce attiva tra una sezione e l'altra.

## v5.1.1
- Pulsanti olografici con riempimento semplice: tolte le righe di scansione, resta solo la sfumatura di colore.

## v5.1.0
- Tutti i pulsanti nello stile dell'ologramma: vetro colorato semitrasparente, bordo luminoso sottile, angoli a staffa in alto a sinistra e in basso a destra, righe di scansione e testo con alone. Vale per menu, selettore lingua, LinkedIn, pulsanti delle card, Chiudi e Progetto successivo.
- Nel case study i pulsanti prendono il colore del progetto aperto.

## v5.0.0
- La proiezione olografica ora presenta Alessio: "Product Designer · Torino", nome e cognome e la headline "Rendo semplici i prodotti complessi." Cliccandola si scende ai progetti; le card si aprono ancora trascinandole sul parabrezza. Tolte frecce e pallini dei progetti.
- UX Dash nascosto (sezione e voce di menu), il codice resta nel file per riattivarlo.
- Chi sono riassunto in un solo paragrafo; al posto dei tre riquadri numerici c'è il pulsante per il profilo LinkedIn.
- Esperienza: le parti chiave di ogni punto sono evidenziate come una selezione di Figma (bordo blu, maniglie agli angoli, etichetta "Frame" al passaggio del mouse).
- Rimossa la sezione "Lavoriamo insieme?" e la voce Contatti dal menu.

## v4.4.1
- Lo sfondo colorato ora sta sotto l'hero: l'abitacolo resta sempre in primo piano e il colore si vede solo dove l'hero sfuma.
- Animazione dietro i case study semplificata: un solo alone morbido nel colore del progetto che respira e oscilla lentamente.

## v4.4.0
- L'hero non si interrompe più di netto: l'abitacolo sfuma gradualmente verso la sezione dei progetti.
- Sfondo animato dietro ai case study: macchie di luce morbide che si muovono lentamente nel colore primario del progetto mostrato sul parabrezza; passando su una card il colore passa a quello di quel progetto, con una transizione dolce.

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
