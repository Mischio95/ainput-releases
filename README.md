# AInput — Releases

> Dettatura vocale AI per Mac. Locale. Privata. Ovunque.

Questa repository contiene esclusivamente gli artifact di rilascio di **AInput** (DMG + blockmap) usati dal sistema di auto-aggiornamento integrato nell'app.

---

## Download

Vai alla sezione [**Releases**](../../releases) e scarica il `.dmg` più recente per Apple Silicon.

| Versione | Architettura | Download |
|----------|-------------|---------|
| Latest   | Apple Silicon (arm64) | [Releases →](../../releases/latest) |

> **Requisiti**: macOS 13 o superiore · Mac con chip M1, M2, M3 o M4 · 8 GB RAM (16 GB consigliati)

---

## Cos'è AInput

**AInput** trasforma la voce in testo professionale dentro qualsiasi applicazione — Mail, Slack, ChatGPT, VS Code, Notion, Word, qualunque cosa abbia un cursore.

Si attiva con una scorciatoia (es. doppio tap `Fn`), ascolta, e inserisce il testo già pulito e formattato esattamente dove stai lavorando. Niente copia-incolla, niente switch di finestra.

### Tutto gira sul tuo Mac

Niente cloud · niente account obbligatorio · niente API a pagamento · niente quote mensili di parole.

La trascrizione (Whisper / Parakeet) e la riformulazione AI opzionale (modelli Qwen) girano in locale sul chip Apple Silicon sfruttando l'**Apple Neural Engine** e **Metal GPU**.

### Cosa fa in più rispetto al semplice voice-to-text

- **Pulisce** la trascrizione — rimuove "ehm", ripetizioni, capitalizza, aggiunge punteggiatura
- **Adatta il registro** al contesto: formale, casual, tecnico, verbatim
- **Riformatta** in 5 layout pronti: prosa, email, chat, lista puntata, prompt AI
- **Personalizza** il riconoscimento al tuo vocabolario (nomi propri, acronimi, tecnicismi)
- **Espande snippet vocali** — dici "firma" e inserisce la firma completa
- **Cronologia** cifrata locale di tutte le dettature (AES-256-GCM)

---

## Installazione

1. Scarica `AInput-x.x.x-arm64.dmg` dalla sezione Releases
2. Apri il `.dmg` e trascina **AInput** in `/Applications`
3. Al primo avvio: tasto destro → **Apri** (bypass Gatekeeper per app non notarizzata)
4. Concedi i permessi richiesti: Microfono · Accessibilità · Input Monitoring

Gli aggiornamenti successivi vengono notificati direttamente dall'app e installati in un click.

---

## Auto-aggiornamento

AInput include **electron-updater** configurato su questa repository. Quando una nuova versione viene pubblicata qui, l'app mostra una notifica e permette di aggiornare senza riaprire il browser.

---

## Sorgente

Il codice sorgente dell'applicazione è sviluppato in privato in [`Mischio95/voice-flow-llm`](https://github.com/Mischio95/voice-flow-llm).

---

*© 2026 — Tutti i diritti riservati.*
