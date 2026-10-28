# BRIEF · El Matador (demo Rivela)

> Documento modificabile. Aggiornare le sezioni man mano che arrivano dati confermati dal locale.

## 1. Dati dell'attività e fonti

| Dato | Valore | Stato | Fonte |
|---|---|---|---|
| Nome | El Matador (zona Ruzafa) | Verificato | Registro imprese e ricerca web |
| Ragione sociale | Restaurant El Matador Ruzafa SL | Verificato | Registro imprese (ranking-empresas.eleconomista.es) |
| Indirizzo | C/ de Sevilla, 12, 46006 Valencia | Verificato | Registro imprese (sede sociale) |
| Telefono | 651 59 16 69 | **Non verificato** | Dato fornito; il registro mostra il numero parzialmente oscurato |
| Email | inakigc@icloud.com | **Non pubblicata** nel sito | Dato fornito; indirizzo personale, non mostrato in demo |
| Instagram | https://www.instagram.com/ruzafamatador/ | Da verificare | Indicato nelle note legali (fonte non raggiunta, risposta 403) |
| Prenotazioni | https://www.opentable.es/r/el-matador-valencia | Da testare prima della consegna | Indicato dall'utente |
| Note legali | https://www.covermanager.com/legal/load_legal_dynamic/restaurante-elmatador/spanish/use_conditions/0/0 | Non consultabile (HTTP 403) | Dato fornito |
| Carta / menu | — | **Da reperire** | Le fonti indicano servizi esterni per carta e prenotazioni; non è stata trovata la carta ufficiale |
| Orari | — | **Da confermare** | Nessuna fonte affidabile trovata |

Nota: non è stato confermato se esista già un sito proprio del locale. Le fonti indicano solo servizi esterni per carta e prenotazioni.

## 2. Obiettivo del sito

Vetrina riconoscibile con identità, carta e percorso di prenotazione chiaro. Il sito presenta il locale come attività già esistente, senza affermare che non abbia strumenti online.

## 3. Identità grafica

- Direzione: contemporanea e urbana, con nero caldo, bordeaux e avorio. Distinta da La Calita.
- Colori: nero `#140F0E`, nero morbido `#1F1716`, bordeaux `#6B1E2A`, bordeaux scuro `#4F1520`, avorio `#F3EDE2`.
- Font: Oswald (titoli e pulsanti, maiuscolo), Inter (testo).
- File immagini attesi: `images/hero.jpg` (foto di copertina) e `images/logo.png` (logo). Se mancano, il sito usa i gradienti e il nome testuale.
- Immagini: nessuna fotografia del locale nel repository. Il sito usa gradienti scuri, senza immagini generiche.

## 4. Struttura delle sezioni

1. Banner: "Propuesta independiente de Rivela · Demo no oficial"
2. Cabecera con navigazione (Carta, Reservas, Ubicación, Tu sitio)
3. Hero: nome in grande, messaggio, pulsanti "Reservar mesa" e "Ver la carta"
4. Presentazione breve (testo da validare)
5. Carta: struttura con sezioni (Entrantes, Principales, Postres, Bebidas), contenuti segnaposto
6. Reservas: pulsante verso OpenTable
7. Ubicación: indirizzo, link a Google Maps e Instagram
8. Propuesta Rivela: spiegazione, prezzo orientativo, contatti
9. Pie di pagina con dichiarazione di demo

## 5. Testi in spagnolo

Sono già nella pagina `index.html`. Messaggi chiave:

- Titolo: **El Matador**
- Sottotitolo: "Carácter urbano en el corazón de Ruzafa. Carta, identidad y una forma sencilla de reservar."
- Pulsanti: "Reservar mesa", "Ver la carta", "Ir a reservas", "Abrir en Google Maps"
- Rivela: "Rivela puede realizar el sitio de tu negocio". Precio: "Desde 350 € (precio orientativo, a definir según el proyecto)." Contatto: rivelaastudio@gmail.com

## 6. Funzionalità previste

- Pagina statica, HTML + CSS, senza framework e senza JavaScript.
- Responsive: testato per smartphone, tablet e computer (breakpoint 600px, 768px, 1024px).
- Link esterni con `target="_blank"` e `rel="noopener"`.
- Nessun modulo, nessuna raccolta dati dei visitatori, nessuna prenotazione simulata.
- Nessuna analisi o tracciamento.

## 7. Dati da confermare

- [ ] Telefono reale del locale (651 59 16 69 non verificato)
- [ ] Orari di apertura
- [ ] Instagram ufficiale (@ruzafamatador da verificare)
- [ ] Link OpenTable funzionante e riferito al locale corretto
- [ ] Carta ufficiale (piatti e prezzi), da ottenere solo dal locale
- [ ] Testo di presentazione del locale con il locale
- [ ] Eventuale sito o servizio di carta già esistente da integrare o sostituire

## 8. Modifiche successive

- Inserire la carta reale, solo dopo averla ricevuta dal locale.
- Inserire foto reali del locale (sostituiscono i gradienti).
- Inserire telefono e orari confermati.
- Sostituire il link di prenotazione se il locale usa un altro sistema.
- Rimuovere la dicitura "Demo no oficial" solo in caso di accordo con il locale e nuovo sito approvato.
