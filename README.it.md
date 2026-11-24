<div align="center">

<img src="logo-icon.png" alt="NexusCharts" width="120">

# NexusCharts

**Grafici in tempo reale, indicatori, script e alert — sempre in tasca.**
Un'app di grafici veloce e bella per iPhone, Android e computer, con un design nero assoluto ispirato alle orbite.

[English](README.md) · **Italiano** · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md)

[![Versione](https://img.shields.io/badge/versione-v1.26.0-d9a441?style=for-the-badge)](../../releases)
![Piattaforma](https://img.shields.io/badge/iPhone%20%7C%20Android%20%7C%20Computer-web%20app-2962ff?style=for-the-badge)
![Lingue](https://img.shields.io/badge/lingue-IT%20%7C%20EN%20%7C%20ES%20%7C%20FR%20%7C%20DE-22ab94?style=for-the-badge)
![Prezzo](https://img.shields.io/badge/installazione-gratis-111111?style=for-the-badge)

</div>

<div align="center">
<table>
  <tr>
    <td align="center" width="25%"><img src="screenshots/it/01-welcome.png" width="190" alt="Benvenuto"><br><sub>1. Benvenuto</sub></td>
    <td align="center" width="25%"><img src="screenshots/it/02-sign-in.png" width="190" alt="Accesso"><br><sub>2. Accesso</sub></td>
    <td align="center" width="25%"><img src="screenshots/it/03-watchlist.png" width="190" alt="Watchlist"><br><sub>3. Watchlist</sub></td>
    <td align="center" width="25%"><img src="screenshots/it/04-signals.png" width="190" alt="Segnali"><br><sub>4. Segnali</sub></td>
  </tr>
  <tr>
    <td align="center" width="25%"><img src="screenshots/it/05-chart-drawings.png" width="190" alt="Grafico e disegni"><br><sub>5. Grafico e disegni</sub></td>
    <td align="center" width="25%"><img src="screenshots/it/06-indicators.png" width="190" alt="Indicatori"><br><sub>6. Indicatori</sub></td>
    <td align="center" width="25%"><img src="screenshots/it/07-script-editor.png" width="190" alt="Editor di script"><br><sub>7. Editor di script</sub></td>
    <td align="center" width="25%"><img src="screenshots/it/08-bar-replay.png" width="190" alt="Bar Replay"><br><sub>8. Bar Replay</sub></td>
  </tr>
</table>
</div>

---

## 📖 Indice

- [Cos'è NexusCharts](#-cosè-nexuscharts)
- [Funzioni](#-funzioni)
- [Installazione](#-installazione)
- [Come ottenere l'accesso](#-come-ottenere-laccesso)
- [Compatibilità](#-compatibilità)
- [Privacy e sicurezza](#-privacy-e-sicurezza)
- [Come è fatta](#%EF%B8%8F-come-è-fatta)
- [Numeri di versione](#-numeri-di-versione)
- [Domande frequenti](#-domande-frequenti)
- [Prossimamente](#-prossimamente)
- [Riconoscimenti](#-riconoscimenti)

---

## ✨ Cos'è NexusCharts

NexusCharts è una **web app** che si installa sulla schermata Home e funziona come un'app vera: a tutto schermo, con la sua icona, senza passare dall'App Store.
È pensata per i trader che vogliono **grafici puliti, prezzi in tempo reale, indicatori e strumenti di disegno** sul telefono, senza limiti, pubblicità o abbonamenti.

| | |
|---|---|
| ⚡ **Prezzi live** | I prezzi arrivano in diretta dal nostro server dati, spesso più volte al secondo |
| 📈 **42 indicatori + i tuoi script** | Libreria integrata e un motore compatibile con Pine Script™ |
| 🔔 **Alert veri** | Notifiche push anche ad app chiusa |
| 📱 **Come un'app vera** | Tutto schermo, vibrazione al tocco, animazioni fluide, niente barre del browser |
| 🔄 **Sempre aggiornata** | Ogni volta che la apri hai l'ultima versione, in automatico |
| 🌍 **5 lingue · 2 temi** | Italiano, inglese, spagnolo, francese, tedesco · Scuro e chiaro |

> 📝 Le novità di ogni versione sono nella pagina [Releases](../../releases).

### 🆕 Novità della 1.26.0 — Arrotondamento a metà in su

- 🔢 I numeri esattamente a metà si arrotondano in su (3971,165 → 3971,17) in math.round, str.tostring, math.round_to_mintick e nei prezzi mostrati sul grafico.
- 🧮 Niente più errori dovuti a come il computer memorizza i decimali (3971,16499…).
- ✅ Stessi risultati di prima su tutti gli script di prova e sul controllo indipendente dei calcoli.

### In precedenza, nella 1.25.0 — Funzioni Pine con più forme

- 🧩 Ogni funzione di Pine v6 con più di una forma è stata controllata sul manuale ufficiale, ogni forma contro l'altra.
- 🎚️ input.int e input.float con le opzioni scritte in fila ora mostrano il menu a tendina; input(close) mostra il menu Sorgente.
- 🕒 time e time_close accettano bars_back e timeframe_bars_back in entrambe le forme della v6.

### In precedenza, nella 1.24.0 — Riempimenti a sfumatura e script più compatibili

- 🌈 I riempimenti a sfumatura (valore e colore in alto e in basso) sono disegnati come su TradingView, con i colori in alto e in basso in Stile; l'RSI li usa per ipercomprato e ipervenduto.
- 🧓 Script vecchi Pine v3/v4: ora valgono la trasparenza transp, la trasparenza di serie di sfondi e riempimenti e la condizione when degli ordini delle strategie.
- 🧩 line.new, box.new e label.new con chart.point, i nomi alternativi ufficiali dei parametri e l'avviso automatico dei parametri non supportati.

<details>
<summary>In precedenza, nella 1.23.0 — Riempimenti, sfondi e riquadri sotto il grafico</summary>

- 🎨 Stile ora elenca ogni riempimento e sfondo colorato dello script: mostra/nascondi e, se lo script usa più colori, ognuno si cambia con la sua trasparenza.
- 📉 Gli indicatori nei riquadri sotto il grafico ora disegnano anche segnali, riempimenti, sfondi, riquadri, etichette e linee (per esempio la fascia dell'RSI tra 30 e 70).
- 🔒 Riempimenti e sfondi che lo script segna come non modificabili restano nascosti in Stile, come su TradingView.

</details>

<details>
<summary>In precedenza, nella 1.22.0 — Scheda Stile completa per segnali e disegni</summary>

- 🎯 Stile ora elenca i segnali di ogni script (plotshape, plotchar, plotarrow): mostra/nascondi, colore e trasparenza, forma, posizione, dimensione e colore del testo.
- 🧩 Nuova sezione Oggetti grafici: riquadri, etichette, linee, tabelle e polilinee da accendere o spegnere.
- 🔒 Linee e segnali che lo script segna come non modificabili restano nascosti in Stile, come su TradingView.

</details>

<details>
<summary>In precedenza, nella 1.21.0 — Volume e livelli rifatti</summary>

- 📊 OBV, Volume, Pivot Points High Low, ZigZag e gli indicatori di livelli (massimo e minimo del giorno e della settimana prima, aperture, ADR, variazione %, volatilità storica, massimo e minimo a 52 settimane, massimo e minimo della sessione) rifatti con le impostazioni di TradingView più etichette, opzioni in più e avvisi.
- 🎯 Nuovo: Pivot Points Standard (Tradizionale, Fibonacci, Woodie, Classico, DM, Camarilla) giornalieri, settimanali, mensili, trimestrali o annuali.
- ✅ Tutta la libreria di indicatori è ora rifatta.

</details>

---

## 🚀 Funzioni

### 📋 Watchlist
- 79 strumenti: Forex, metalli, energia, indici, cripto e 7 azioni USA, divisi per categoria
- Cerca qualsiasi simbolo e aggiungilo con un tocco
- Prezzo live, variazione giornaliera in punti e percentuale, icone con bandiere e monete
- Mini player in basso con il simbolo selezionato e il suo grafichino
- **Più watchlist** (*Tutte le watchlist*: crea, rinomina, elimina) e **Segnali** colorati con le loro schede
- Tieni premuto un pair per Segnale e Rimuovi

### 📊 Grafico
- Grafico a tutto schermo con **aggiornamento live** e **conto alla rovescia** della candela
- **Timeframe:** minuti 1m · 3m · 5m · 15m · 30m · 45m — ore 1H · 2H · 3H · 4H — giorni 1D · 1W · 1M · 3M · 6M · 12M
- **Tipi di grafico:** Candele · Barre · Linea · Area · Heikin Ashi
- **Colori personalizzati:** corpo, bordi e stoppini delle candele con opacità, più sfondo e scale del grafico
- **Selettore rapido:** tieni premuto e scorri sulla pillola del simbolo o del timeframe per cambiarlo al volo
- **Mirino** con etichette di prezzo e orario e **pulsante "+"** per creare alert al volo
- **Confronta** un secondo simbolo in percentuale
- Pizzica per lo zoom, trascina per scorrere, condividi un'immagine del grafico

### 📈 Indicatori
- Schermata **Indicatori e metriche** con ricerca, **Preferiti** (tocca la stellina) e **I miei script**
- **34 Tecnici:** SMA, EMA, WMA, HMA, VWMA, ALMA, MA Ribbon, Bande di Bollinger (+ %B e BandWidth), Keltner, Donchian, Envelopes, Supertrend, Ichimoku, VWAP, Regressione lineare, RSI, Stoch RSI, Stocastico, MACD, CCI, ADX, ATR, MFI, Williams %R, Momentum, ROC, Awesome Oscillator, Aroon, OBV, Volume, Pivot Points, ZigZag
- **8 Fondamentali** (calcolati dai prezzi): massimo/minimo del giorno e della settimana precedente, apertura giornaliera, range medio giornaliero, variazione giornaliera %, volatilità storica, massimo/minimo a 52 settimane, massimo/minimo di sessione
- **Legenda compatta:** tocca un indicatore per **mostrarlo/nasconderlo**, aprire le **impostazioni** o **toglierlo**
- **Finestra impostazioni** con **Input**, **Stile** (visibilità, colore e spessore di ogni linea) e **Visibilità** (minuti / ore / giorni)
- **Menu •••:** ripristina le impostazioni o **salva come predefinito** per la prossima volta che lo aggiungi

### 🧩 Editor script
- Scrivi i tuoi indicatori in un linguaggio **compatibile con Pine Script™** (v5/v6)
- Editor di codice con numeri di riga, controllo errori e console
- Supporta plot, forme, box, linee, etichette, tabelle, riempimenti, input, alert, timeframe superiori e sessioni
- Salva i tuoi script e aggiungili al grafico da **I miei script**
- **Minimappa** del codice a destra: tocca o trascina per muoverti negli script lunghi

### ✏️ Strumenti di disegno
Salvati in automatico per ogni simbolo.

| Gruppo | Strumenti |
|---|---|
| Trend | Trendline · Linea orizzontale · Canale parallelo |
| Previsione e misurazione | Posizione long · Posizione short (con target, stop e R:R) |
| Figure | Pennello · Freccia · Rettangolo · Percorso · Ellisse |
| Annotazioni | Testo · Nota |

Seleziona un disegno per spostarlo, cambiargli colore, **spessore e stile** o eliminarlo. Il pulsante **Annulla** torna indietro fino a 30 passi.

### 🔔 Alert
- Crea un alert sul prezzo dal **"+"** del mirino o dalla gestione **Alert**
- Linea dell'alert sul grafico: toccala per eliminarla
- Elenco attivi / non attivi, annulla ed elimina
- **Notifiche push anche ad app chiusa** (si disattivano da Profilo › Notifiche)

### ⏪ Bar Replay
- Metti una **linea guida** sulla candela esatta che vuoi e parti da lì
- Riproduci da 1x a 10x o avanza una candela alla volta: perfetto per il backtest

### 🧭 Hub del grafico
| Sezione | Cosa fa |
|---|---|
| **Layout** | Nuovo · Salva · Apri le tue configurazioni del grafico |
| **Grafico** | Tipologia, impostazioni grafico, canvas, dettagli simbolo |
| **Analisi** | Confronta · Bar Replay · Alert · Tecnici · Editor script |
| **Tecnici** | Indicatore compra/vendi da oscillatori e medie mobili |
| **Condividi** | Crea un'immagine del grafico e apre la condivisione |

### 👤 Profilo e impostazioni
- Tema (scuro/chiaro), lingua e notifiche
- Modulo per segnalare un problema o proporre un'idea
- Social: canale Telegram, Instagram, TikTok, YouTube e X, che si aprono direttamente nelle loro app
- Aggiorna dati, ripristino sicuro, esci

---

## 📲 Installazione

> 🌐 L'indirizzo dell'app è **[nexuscharts.app](https://nexuscharts.app)**.

> NexusCharts si installa dal browser: niente App Store o Play Store.

### 🍎 iPhone (Safari)
1. Apri il link di NexusCharts con **Safari**.
2. Tocca **Condividi** (il quadrato con la freccia). Su iOS 26 tocca prima i **tre puntini ⋯**, poi **Condividi**.
3. Tocca **Aggiungi alla schermata Home** (se non lo vedi, tocca **Mostra altro**).
4. Lascia attivo **Apri come web app**, controlla che il nome sia **NexusCharts** e tocca **Aggiungi**.
5. Apri **NexusCharts** dalla schermata Home.

### 🤖 Android (Chrome)
1. Apri il link di NexusCharts con **Chrome**.
2. Tocca i **tre puntini ⋮** in alto a destra.
3. Tocca **Installa app** (oppure **Aggiungi a schermata Home**) e conferma.

### 💻 Computer (Chrome / Edge)
1. Apri il link di NexusCharts.
2. Clicca l'**icona di installazione** nella barra degli indirizzi, oppure usala in una normale scheda.

> 💡 La stessa guida è dentro l'app: tocca **Installa** in alto a destra nella schermata di accesso (compare solo quando l'app è aperta dal browser).

---

## 🔑 Come ottenere l'accesso

1. Apri **[nexuscharts.app](https://nexuscharts.app)** e tocca **Crea un account**.
2. Scegli username, email e password, e conferma di avere almeno 18 anni e di aver letto l'Informativa Privacy.
3. Inserisci il codice di 6 cifre che arriva per email e sei dentro.

Da quel momento l'app ti fa entrare da sola. Se cambi telefono basta accedere con username o email e password.

Hai un **codice amico**? Tocca **Entra con un codice** e scrivilo (formato `XXXX-XXXX`): funziona su un solo dispositivo.

> 💬 Serve aiuto? Scrivi a **support@nexuscharts.app**.

---

## ✅ Compatibilità

| Dispositivo | Browser | Stato |
|---|---|---|
| iPhone (iOS 16.4 o successivo) | Safari | ✅ Consigliato |
| iPhone | Chrome / Edge | ✅ Funziona (installa da Condividi) |
| Android 10 o successivo | Chrome | ✅ Supportato |
| Android | Samsung Internet / Edge | ✅ Funziona |
| iPad | Safari | ⚠️ Funziona, pensata per telefoni |
| Computer | Chrome / Edge / Safari | ⚠️ Funziona, versione completa per computer in arrivo |

**Requisiti:** una connessione a internet. Su iPhone le notifiche push richiedono l'app installata sulla schermata Home.

---

## 🔒 Privacy e sicurezza

- 👤 Per l'account servono solo **username, email e password**. La password non la vediamo mai: sul server c'è solo una sua impronta cifrata.
- 📜 Tutti i dettagli sono nell'**[Informativa Privacy](https://nexuscharts.app/privacy.html)**.
- 📱 Disegni, layout, indicatori, script e impostazioni restano **solo sul tuo dispositivo**.
- 📡 Il server dati conserva solo i prezzi di mercato: nessun indirizzo IP e nessun dato personale.
- 🔔 Se attivi le notifiche, i tuoi alert attivi vengono tenuti sul server solo per avvisarti; elimini l'alert e sparisce.
- 🔐 In questo repository non ci sono password né chiavi private.
- 🛡️ **Protezione contro chi prova a indovinare i codici**: dopo troppi codici sbagliati dalla stessa rete, l'accesso si mette in pausa per un po' e l'app mostra un messaggio chiaro. I codici validi e i dispositivi collegati non vengono toccati.
- 🧹 **Ripristina l'app** cancella tutto quello che è salvato sul dispositivo.

---

## 🏗️ Come è fatta

- 🖥️ **L'app** (quello che vedi sullo schermo) sta in questo repository ed è pubblicata come web app.
- ⚙️ **Il motore** gira su Cloudflare: un **server degli account** (registrazione, accesso, email), un **server dati** che manda i prezzi in diretta e conserva lo storico delle candele, e un server per i codici amico e gli alert. Sono gestiti a parte e non fanno parte di questo repository.
- 🔐 Chiavi e password stanno solo nelle impostazioni cifrate del motore, mai nel codice.

---

## 🔢 Numeri di versione

Le versioni hanno tre numeri, **MAGGIORE.MINORE.CORREZIONE** (per esempio 0.43.0):

- **Primo numero**: cambiamenti grandi.
- **Numero centrale**: nuove funzioni.
- **Ultimo numero**: correzioni e miglioramenti.

---

## ❓ Domande frequenti

<details>
<summary><b>Devo pagare o abbonarmi?</b></summary>
No. Installare e usare NexusCharts è gratis: ti basta creare un account gratuito con username, email e password.
</details>

<details>
<summary><b>Mi serve un conto con un broker?</b></summary>
No. Entri con il tuo account NexusCharts, senza registrarti da nessun broker.
</details>

<details>
<summary><b>Posso fare trading dall'app?</b></summary>
No. NexusCharts serve solo per grafici e analisi: non apre mai ordini.
</details>

<details>
<summary><b>Posso usare i miei indicatori Pine Script™?</b></summary>
Sì. Incolla lo script nell'Editor script, salvalo e aggiungilo da I miei script. La maggior parte delle funzioni v5/v6 è supportata; se qualcosa non lo è, la console ti dice la riga.
</details>

<details>
<summary><b>Gli alert funzionano ad app chiusa?</b></summary>
Sì, con le notifiche push attive. Su iPhone l'app deve essere installata sulla schermata Home.
</details>

<details>
<summary><b>Il codice amico dice che è già usato su un altro dispositivo.</b></summary>
Ogni codice amico funziona su un solo dispositivo. Su un altro dispositivo entra con un account NexusCharts gratuito: funziona su tutti i tuoi dispositivi.
</details>

<details>
<summary><b>Devo aggiornare l'app?</b></summary>
No. Si aggiorna da sola ogni volta che la apri.
</details>

<details>
<summary><b>Disegni e indicatori si sincronizzano tra dispositivi?</b></summary>
Non ancora: restano sul dispositivo dove li hai creati.
</details>

---

## 🗺️ Prossimamente

| Stato | Funzione |
|---|---|
| ✅ | Watchlist, grafico live, timeframe, tipi di grafico, colori personalizzati |
| ✅ | Strumenti di disegno, Bar Replay, Hub del grafico, layout |
| ✅ | 42 indicatori integrati, preferiti, impostazioni indicatore |
| ✅ | Motore compatibile con Pine Script™ ed editor script |
| ✅ | Alert sul prezzo con notifiche push |
| ✅ | 5 lingue (tedesco dalla 0.44.0), tema scuro e chiaro |
| ✅ | Design 3.0: schermate di benvenuto, animazione del logo, menu lingue a orbita |
| ✅ | Accesso Design 3.0: logo a orbite, codice in 8 caselle, bandiere rotonde |
| ✅ | Design 3.0 dentro l'app, più watchlist, Segnali, spessore/stile dei disegni e Annulla |
| ✅ | Server dati nostro: prezzi in diretta, 79 strumenti, nomi in 5 lingue |
| ✅ | Account NexusCharts, nuovo indirizzo nexuscharts.app, Informativa Privacy |
| ✅ | Azioni: Apple, Microsoft, NVIDIA, Amazon, Alphabet, Meta, Tesla, con gli orari di Borsa |
| 🔜 | Storico delle candele più lungo (anni) |
| 🔜 | Versione completa per computer |
| 💡 | Sincronizzazione tra dispositivi |

---

## 🙏 Riconoscimenti

- Grafici realizzati con [TradingView Lightweight Charts™](https://www.tradingview.com/lightweight-charts/) (Apache 2.0).
- Dati di mercato forniti dai server NexusCharts. I prezzi servono per l'analisi e possono essere diversi da quelli del tuo broker.
- Icone cripto da [cryptocurrency-icons](https://github.com/spothq/cryptocurrency-icons) (CC0 1.0).
- Loghi delle azioni: Apple, NVIDIA, Google, Meta e Tesla da [Simple Icons](https://simpleicons.org) (CC0 1.0); Microsoft e Amazon da [Wikimedia Commons](https://commons.wikimedia.org) (pubblico dominio). I loghi sono marchi dei rispettivi proprietari e servono solo a riconoscere il titolo; NexusCharts non è legata a queste aziende.
- TradingView e Pine Script sono marchi di TradingView, Inc. NexusCharts non è affiliata a TradingView.

---

## ⚠️ Avvertenza

NexusCharts è uno strumento di analisi. Niente nell'app è un consiglio finanziario. Il trading comporta rischi: fai sempre le tue valutazioni.

<div align="center">

**© 2026 NexusCharts — Tutti i diritti riservati.**

</div>
