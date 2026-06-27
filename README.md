# 🥗 Piano Alimentare 16/8

> App web per la gestione e il tracciamento di un piano alimentare in digiuno intermittente 16/8, pensata per chi pratica sport a livello amatoriale con obiettivi di dimagrimento e mantenimento della massa muscolare.

🌐 **Live app → [acnologia97.github.io/piano-alimentare](https://acnologia97.github.io/piano-alimentare)**

---

## Funzionalità

### 📅 Piano settimanale
- Calendario a griglia con tutti i pasti visibili in un colpo d'occhio
- **Drag & drop** per spostare i pasti tra i giorni — lo scambio è consentito solo tra pasti della stessa categoria (pranzo↔pranzo, cena↔cena, spuntino↔spuntino)
- **Modifica testo** di ogni pasto tramite il tasto ✏️
- Tutte le modifiche vengono salvate automaticamente nel browser

### 🛒 Lista della spesa
- Checklist interattiva con barra di avanzamento
- Aggiunta e rimozione di articoli per categoria
- Spunte persistenti tra le sessioni
- Reset rapido per ricominciare ogni settimana

### 📉 Obiettivi & tracciamento peso
- Inserimento misurazioni (data + peso) con storico completo
- Variazione colorata rispetto alla misurazione precedente
- Grafico che sovrappone la curva prospettata e quella reale, aggiornato in tempo reale

### 📋 Regole del piano
- Accessibili tramite il pulsante in basso a destra
- Popup con tutte le linee guida: finestra oraria, condimenti, giorni di allenamento, pasto libero, idratazione

---

## Stack tecnico

- **HTML5 + CSS3 + JavaScript vanilla** — nessun framework, nessun build step
- [Chart.js](https://www.chartjs.org/) per il grafico dell'andamento peso
- Dati salvati interamente in **localStorage** — nessun backend, nessun account necessario
- Funziona offline dopo il primo caricamento

---

## Installazione come app su iPhone

1. Apri il link su **Safari**
2. Tocca il tasto **Condividi** ↑
3. Seleziona **"Aggiungi alla schermata Home"**
4. L'app si aprirà a schermo intero come un'app nativa

---

## Roadmap

- [ ] Supporto multi-utente
- [ ] Piani alimentari personalizzabili per profilo
- [ ] Esportazione dati (PDF / CSV)
- [ ] Notifiche per le finestre dei pasti
- [ ] Dark mode

---

## Contribuire

Pull request e suggerimenti sono benvenuti. Apri una issue per proporre nuove funzionalità o segnalare bug.

---

## Note

- Tutti i dati (misurazioni, modifiche ai pasti, spesa) rimangono **solo sul dispositivo dell'utente** — nessun dato viene inviato a server esterni
- Per resettare tutto: Impostazioni browser → Cancella dati sito
