# ICA — Segnatavoli

Progetto per creare segnatavoli pieghevoli di **In Cerca di Avventura** a partire dagli asset originali.

## Obiettivi
- Formato A4 orizzontale, **3 segnatavoli per foglio**.
- Due facciate identiche per dimensioni e correttamente orientate dopo la piegatura.
- Linguette alla base per la chiusura/incollaggio.
- Numero del tavolo nella parte alta; logo ICA originale al centro; scritta **In Cerca di Avventura** in oro sotto il logo; QR autentico sotto la scritta.
- Grafica fantasy anni '90, palette coerente con il logo.
- Nessun logo Sorcery e nessuna rosa dei venti.
- Misure, margini, posizionamenti e pieghe definiti con coordinate, non tramite immagini generate approssimative.

## Cartelle
- `assets/logo/` — loghi originali
- `assets/qr/` — QR fornito dall'organizzatore
- `assets/sfondi/` — sfondi originali o approvati
- `assets/decorazioni/` — cornici e fregi
- `templates/A4-3-segnatavoli/` — file sorgente e sagome
- `output/anteprime/` — prove di impaginazione
- `output/pdf-stampa/` — PDF finali

## Flusso di lavoro
1. Caricare gli asset originali nelle cartelle `assets/`.
2. Verificare contenuto e leggibilità del QR.
3. Approvare una singola facciata grafica.
4. Comporre il foglio A4 con dimensioni misurabili e due facce simmetriche.
5. Verificare il prototipo stampato al 100%, poi produrre la serie.

**Stato:** repository inizializzato; in attesa degli asset sorgente.
