<div align="center">

<img src="logo-icon.png" alt="NexusCharts" width="120">

# NexusCharts

**Echtzeit-Charts, Indikatoren, Skripte und Alarme — immer in deiner Tasche.**
Eine schnelle, elegante Chart-App für iPhone, Android und Computer, mit tiefschwarzem Design im Stil von Umlaufbahnen.

[English](README.md) · [Italiano](README.it.md) · [Español](README.es.md) · [Français](README.fr.md) · **Deutsch**

[![Version](https://img.shields.io/badge/version-v0.45.0-d9a441?style=for-the-badge)](../../releases)
![Plattform](https://img.shields.io/badge/iPhone%20%7C%20Android%20%7C%20Computer-web%20app-2962ff?style=for-the-badge)
![Sprachen](https://img.shields.io/badge/sprachen-IT%20%7C%20EN%20%7C%20ES%20%7C%20FR%20%7C%20DE-22ab94?style=for-the-badge)
![Preis](https://img.shields.io/badge/installation-kostenlos-111111?style=for-the-badge)

</div>

<p align="center">
  <img src="screenshots/de/watchlist.png" width="24%">
  <img src="screenshots/de/chart.png" width="24%">
  <img src="screenshots/de/indicators.png" width="24%">
  <img src="screenshots/de/settings.png" width="24%">
</p>
<p align="center">
  <img src="screenshots/de/hub.png" width="24%">
  <img src="screenshots/de/drawings.png" width="24%">
  <img src="screenshots/de/editor.png" width="24%">
  <img src="screenshots/de/login.png" width="24%">
</p>

---

## 📖 Inhalt

- [Was ist NexusCharts](#-was-ist-nexuscharts)
- [Funktionen](#-funktionen)
- [Installation](#-installation)
- [So bekommst du Zugang](#-so-bekommst-du-zugang)
- [Kompatibilität](#-kompatibilität)
- [Datenschutz & Sicherheit](#-datenschutz--sicherheit)
- [Wie es gebaut ist](#%EF%B8%8F-wie-es-gebaut-ist)
- [Versionen](#-versionen)
- [FAQ](#-faq)
- [Roadmap](#-roadmap)
- [Danksagungen](#-danksagungen)

---

## ✨ Was ist NexusCharts

NexusCharts ist eine **Web-App**, die du auf deinem Home-Bildschirm installierst und die wie eine echte App funktioniert: Vollbild, mit eigenem Symbol, ohne App Store.
Sie ist für Trader gemacht, die **saubere Charts, Live-Preise, Indikatoren und Zeichenwerkzeuge** auf dem Telefon wollen, ohne Grenzen, Werbung oder Abos.

| | |
|---|---|
| ⚡ **Live-Preise** | Kurse und Kerzen aktualisieren sich automatisch alle paar Sekunden |
| 📈 **42 Indikatoren + deine Skripte** | Integrierte Bibliothek und eine mit Pine Script™ kompatible Engine |
| 🔔 **Echte Alarme** | Push-Benachrichtigungen, auch wenn die App geschlossen ist |
| 📱 **Wie eine native App** | Vollbild, haptisches Feedback, flüssige Animationen, keine Browserleisten |
| 🔄 **Immer aktuell** | Bei jedem Öffnen bekommst du automatisch die neueste Version |
| 🌍 **5 Sprachen · 2 Designs** | Italienisch, Englisch, Spanisch, Französisch, Deutsch · Dunkel und Hell |

> 📝 Was in jeder Version neu ist: siehe die Seite [Releases](../../releases).

### 🆕 Neu in 0.45.0 — Design 3.0 in der App, mehrere Watchlists und Signale

- 🪐 **Design 3.0 in der App**: Watchlist, Chart-Menüs, Indikatoren, Skript-Editor, Bar Replay und Profil haben jetzt denselben Umlaufbahn-Stil wie die Anmeldung, im dunklen und hellen Design. Die Kerzen im Chart bleiben schlicht.
- 📋 **Mehrere Watchlists**: erstelle, benenne um und lösche eigene Listen unter *Alle Watchlists*. Deine bisherige Liste bleibt die **Watchlist**, beim Update geht nichts verloren.
- 🛰️ **Signale**: halte ein Paar gedrückt und wähle eine von 7 Farben. Jede Farbe bekommt einen eigenen Tab vor *Watchlist* mit den Paaren dieser Farbe aus allen Listen. Signale lassen sich umbenennen und löschen.
- 🫙 **Leere Zustände**: eine leere Liste zeigt pro Kategorie ein klares leeres Feld, und ohne offenes Symbol zeigt der Chart *Kein Symbol geöffnet* mit der Taste **Symbol suchen** (es werden keine Daten geladen).
- ✏️ **Zeichnungen**: Fadenkreuz, das den Punkt unter dem Finger nie verdeckt, **Linienstärke** (1–4 px) und **Stil** (durchgezogen, gestrichelt, gepunktet) und die Taste **Rückgängig** (bis zu 30 Schritte pro Symbol).
- 📤 **Teilen**: zuerst eine Design-3.0-Vorschau des Charts, dann das Teilen-Menü des Systems nur mit dem Bild.
- 🧩 **Minimap im Skript-Editor**: eine farbige Übersicht des Codes rechts; tippen oder ziehen zum Springen.

### Vorher in 0.44.0 — Deutsch

- 🇩🇪 **Deutsch** ist die fünfte Sprache der App: Anmeldung, Willkommensbildschirme, Watchlist, Chart, Indikatoren, Skript-Editor, Alarme, Profil und Installationsanleitung.
- 🔢 Zahlen und Daten im **deutschen Format** (zum Beispiel 1.234,56).
- 🪐 Das **Sprachmenü mit Umlaufbahn** hat jetzt fünf runde Flaggen.
- 📲 Die Taste **Installieren** auf den Anmeldebildschirmen zeigt jetzt auf allen Geräten und in allen Sprachen nur das Symbol, gleich groß wie die Flagge.

<details>
<summary>Vorher in 0.43.0 — Design-3.0-Anmeldung</summary>

- 🔐 **Neuer Anmeldebildschirm** genau wie der Design-3.0-Prototyp: Logo mit Umlaufbahn, Face-ID-Scanner, Felder im Konsolenstil und goldene und blaue Tasten mit drehendem gestricheltem Ring.
- 🔢 **Zugangscode in 8 Feldern** (4 + 4): jedes Zeichen fällt in sein Feld und die acht Segmente um das Logo leuchten nacheinander auf. Ein falscher Code wird rot und wackelt.
- 💫 **Logo-Übergang bei jedem Öffnen der App**, nicht nur nach den Willkommensbildschirmen.
- 🏳️ **Runde Sprachflaggen** überall in der App.
- 🖤 **0.43.1**: schwarzer Startbildschirm, das neue saubere Logo überall und kein gelber Hintergrund mehr, wenn das iPhone E-Mail und Passwort ausfüllt.
- 📲 **0.43.2**: die Taste **Installieren** ist zurück auf den Anmeldebildschirmen, im Design-3.0-Stil, mit der Schritt-für-Schritt-Anleitung für iPhone und Android.

</details>

---

## 🚀 Funktionen

### 📋 Watchlist
- Forex, Rohstoffe, Krypto, Indizes und Aktien, nach Kategorien gruppiert
- Suche jedes Symbol und füge es mit einem Tipp hinzu
- Live-Preis, Tagesveränderung in Punkten und Prozent, Flaggen- und Münzsymbole
- Mini-Player unten mit dem ausgewählten Symbol und seinem Verlauf
- **Mehrere Watchlists** (*Alle Watchlists*: erstellen, umbenennen, löschen) und farbige **Signale** mit eigenen Tabs
- Paar gedrückt halten für Signal und Entfernen

### 📊 Chart
- Vollbild-Chart mit **Live-Aktualisierung** und **Countdown** der Kerze
- **Zeiteinheiten:** Sekunden 1s · 5s · 10s · 15s · 30s · 45s — Minuten 1m · 3m · 5m · 15m · 30m · 45m — Stunden 1H · 2H · 3H · 4H — Tage 1D · 1W · 1M · 3M · 6M · 12M
- **Chart-Typen:** Kerzen · Balken · Linie · Fläche · Heikin Ashi
- **Eigene Farben:** Körper, Ränder und Dochte der Kerzen mit Deckkraft, dazu Hintergrund der Leinwand und Skalen
- **Schnellauswahl:** auf Symbol oder Zeiteinheit gedrückt halten und wischen, um sie sofort zu wechseln
- **Fadenkreuz** mit Preis- und Zeitangabe und einer **„+“-Taste** für schnelle Alarme
- **Vergleiche** ein zweites Symbol in Prozent
- Mit zwei Fingern zoomen, ziehen zum Scrollen, ein Bild des Charts teilen

### 📈 Indikatoren
- Bildschirm **Indikatoren & Kennzahlen** mit Suche, **Favoriten** (tippe auf den Stern) und **Meine Skripte**
- **34 technische:** SMA, EMA, WMA, HMA, VWMA, ALMA, MA Ribbon, Bollinger-Bänder (+ %B und BandWidth), Keltner, Donchian, Envelopes, Supertrend, Ichimoku, VWAP, Lineare Regression, RSI, Stoch RSI, Stochastik, MACD, CCI, ADX, ATR, MFI, Williams %R, Momentum, ROC, Awesome Oscillator, Aroon, OBV, Volumen, Pivot-Punkte, ZigZag
- **8 fundamentale** (aus den Preisen berechnet): Hoch/Tief des Vortags, Hoch/Tief der Vorwoche, Tageseröffnung, durchschnittliche Tagesspanne, Tagesveränderung %, historische Volatilität, 52-Wochen-Hoch/Tief, Hoch/Tief der Session
- **Kompakte Legende:** tippe auf einen Indikator, um ihn **ein- oder auszublenden**, seine **Einstellungen** zu öffnen oder ihn zu **entfernen**
- **Einstellungsfenster** mit **Eingaben**, **Stil** (Sichtbarkeit, Farbe und Stärke jeder Linie) und **Sichtbarkeit** (Minuten / Stunden / Tage)
- **Menü •••:** Einstellungen zurücksetzen oder **als Standard speichern** für das nächste Hinzufügen

### 🧩 Skript-Editor
- Schreibe eigene Indikatoren in einer mit **Pine Script™ kompatiblen** Sprache (v5/v6)
- Code-Editor mit Zeilennummern, Fehlerprüfung und Konsole
- Unterstützt Plots, Formen, Boxen, Linien, Beschriftungen, Tabellen, Füllungen, Eingaben, Alarme, höhere Zeiteinheiten und Sessions
- Speichere deine Skripte und füge sie über **Meine Skripte** zum Chart hinzu
- **Minimap** des Codes rechts: tippen oder ziehen, um durch lange Skripte zu springen
- Der Code der Skripte bleibt wie bei Pine Script™ immer auf Englisch; Menüs und Meldungen des Editors sind auf Deutsch

### ✏️ Zeichenwerkzeuge
Werden für jedes Symbol automatisch gespeichert.

| Gruppe | Werkzeuge |
|---|---|
| Trend | Trendlinie · Horizontale Linie · Paralleler Kanal |
| Prognose & Messung | Long-Position · Short-Position (mit Ziel, Stop und R:R) |
| Formen | Pinsel · Pfeil · Rechteck · Pfad · Ellipse |
| Anmerkungen | Text · Notiz |

Wähle eine Zeichnung aus, um sie zu verschieben, ihre Farbe, **Linienstärke und Stil** zu ändern oder sie zu löschen. Die Taste **Rückgängig** nimmt bis zu 30 Schritte zurück.

### 🔔 Alarme
- Erstelle einen Preisalarm über das **„+“** am Fadenkreuz oder in der Alarmverwaltung
- Alarmlinie auf dem Chart: tippe darauf, um sie zu löschen
- Liste aktiver und inaktiver Alarme, abbrechen und löschen
- **Push-Benachrichtigungen auch bei geschlossener App** (abschaltbar unter Profil › Benachrichtigungen)

### ⏪ Bar Replay
- Setze eine **Hilfslinie** genau auf die gewünschte Kerze und starte dort
- Abspielen mit 1x–10x oder Kerze für Kerze — ideal für Backtests

### 🧭 Chart-Hub
| Bereich | Was er macht |
|---|---|
| **Layouts** | Neu · Speichern · Öffnen deiner gespeicherten Chart-Einstellungen |
| **Chart** | Chart-Typ, Chart-Einstellungen, Leinwand, Symboldetails |
| **Analyse** | Vergleichen · Bar Replay · Alarme · Technische Analyse · Skript-Editor |
| **Technische Analyse** | Kauf-/Verkaufsanzeige aus Oszillatoren und gleitenden Durchschnitten |
| **Teilen** | Erstellt ein Bild deines Charts und öffnet das Teilen-Menü |

### 👤 Profil & Einstellungen
- Design (dunkel/hell), Sprache und Benachrichtigungen
- Formular, um ein Problem zu melden oder eine Idee vorzuschlagen
- Daten aktualisieren, sicheres Zurücksetzen, Abmelden

---

## 📲 Installation

> NexusCharts wird über den Browser installiert — ohne App Store oder Play Store.

### 🍎 iPhone (Safari)
1. Öffne den NexusCharts-Link in **Safari**.
2. Tippe auf **Teilen** (das Quadrat mit dem Pfeil). Unter iOS 26 tippe zuerst auf die **drei Punkte ⋯**, dann auf **Teilen**.
3. Tippe auf **Zum Home-Bildschirm** (wenn du es nicht siehst, tippe auf **Mehr anzeigen**).
4. Lass **Als Web-App öffnen** aktiviert, prüfe, dass der Name **NexusCharts** ist, und tippe auf **Hinzufügen**.
5. Öffne **NexusCharts** vom Home-Bildschirm.

### 🤖 Android (Chrome)
1. Öffne den NexusCharts-Link in **Chrome**.
2. Tippe oben rechts auf die **drei Punkte ⋮**.
3. Tippe auf **App installieren** (oder **Zum Startbildschirm hinzufügen**) und bestätige.

### 💻 Computer (Chrome / Edge)
1. Öffne den NexusCharts-Link.
2. Klicke auf das **Installationssymbol** in der Adressleiste oder nutze die App in einem normalen Tab.

> 💡 Dieselbe Anleitung gibt es in der App: tippe oben rechts auf dem Anmeldebildschirm auf die Taste **Installieren** (sie erscheint nur, wenn die App im Browser geöffnet ist).

---

## 🔑 So bekommst du Zugang

NexusCharts nutzt **persönliche Zugangscodes** — ohne Registrierung und ohne Broker-Konto.

1. Frag auf Telegram nach deinem Code 👉 **[t.me/albaexe](https://t.me/albaexe)**
2. Öffne die App und tippe auf **Ohne Broker eintreten**.
3. Gib deinen Code ein (Format `XXXX-XXXX`) — und du bist drin.

Ab dann meldet dich die App automatisch an.

Schon angemeldet? Nach einem Update siehst du vielleicht einmal die Willkommensbildschirme: dein Code bleibt gespeichert und die App meldet dich wie gewohnt an.

> ⚠️ Jeder Code gilt nur auf **einem Gerät**, wie eine Lizenz. Wenn du das Telefon wechselst oder die App zurücksetzt, frag einfach nach einem neuen.

---

## ✅ Kompatibilität

| Gerät | Browser | Status |
|---|---|---|
| iPhone (iOS 16.4 oder neuer) | Safari | ✅ Empfohlen |
| iPhone | Chrome / Edge | ✅ Funktioniert (Installation über Teilen) |
| Android 10 oder neuer | Chrome | ✅ Unterstützt |
| Android | Samsung Internet / Edge | ✅ Funktioniert |
| iPad | Safari | ⚠️ Funktioniert, gemacht für Telefone |
| Computer | Chrome / Edge / Safari | ⚠️ Funktioniert, volle Computer-Version kommt |

**Voraussetzungen:** eine Internetverbindung. Push-Benachrichtigungen auf dem iPhone brauchen die App auf dem Home-Bildschirm.

---

## 🔒 Datenschutz & Sicherheit

- 🚫 **Keine persönlichen Daten nötig**, um die App mit einem Code zu nutzen.
- 📱 Zeichnungen, Layouts, Indikatoren, Skripte und Einstellungen werden **nur auf deinem Gerät** gespeichert.
- 🔔 Wenn du Benachrichtigungen aktivierst, bleiben deine aktiven Preisalarme nur auf dem Server, um dich zu benachrichtigen; löschst du einen Alarm, ist er weg.
- 🔐 In diesem Repository sind keine Passwörter oder privaten Schlüssel gespeichert.
- 🎟️ Zugangscodes sind an ein einziges Gerät gebunden und können jederzeit widerrufen werden.
- 🛡️ **Schutz gegen das Erraten von Codes**: nach zu vielen falschen Codes aus demselben Netz pausiert die Anmeldung eine Weile und die App zeigt eine klare Meldung. Gültige Codes und verbundene Geräte sind nie betroffen.
- 🧹 **App zurücksetzen** löscht alles, was auf dem Gerät gespeichert ist.

---

## 🏗️ Wie es gebaut ist

- 🖥️ **Die App** (was du auf dem Bildschirm siehst) liegt in diesem Repository und wird als Web-App veröffentlicht.
- ⚙️ **Die Engine** läuft auf Cloudflare: sie prüft Zugangscodes, leitet Live-Preise weiter und sendet Alarme. Sie wird getrennt verwaltet und ist nicht Teil dieses Repositorys.
- 🔐 Schlüssel und Passwörter liegen nur in den verschlüsselten Einstellungen der Engine, nie im Code.

---

## 🔢 Versionen

Versionen haben drei Zahlen, **MAJOR.MINOR.PATCH** (zum Beispiel 0.44.0):

- **Erste Zahl**: große Änderungen.
- **Mittlere Zahl**: neue Funktionen.
- **Letzte Zahl**: Korrekturen und Verbesserungen.

---

## ❓ FAQ

<details>
<summary><b>Muss ich bezahlen oder ein Abo abschließen?</b></summary>
Nein. Installation und Nutzung von NexusCharts sind kostenlos — du brauchst nur einen Zugangscode.
</details>

<details>
<summary><b>Brauche ich ein Broker-Konto?</b></summary>
Nein. Mit einem Zugangscode meldest du dich ohne Registrierung bei einem Broker an.
</details>

<details>
<summary><b>Kann ich in der App handeln?</b></summary>
Nein. NexusCharts dient nur für Charts und Analyse — es platziert nie Orders.
</details>

<details>
<summary><b>Kann ich meine eigenen Pine Script™-Indikatoren nutzen?</b></summary>
Ja. Füge dein Skript im Skript-Editor ein, speichere es und füge es über Meine Skripte hinzu. Die meisten Funktionen von v5/v6 werden unterstützt; wenn etwas nicht geht, zeigt dir die Konsole die Zeile.
</details>

<details>
<summary><b>Funktionieren Preisalarme bei geschlossener App?</b></summary>
Ja, mit aktiven Push-Benachrichtigungen. Auf dem iPhone muss die App auf dem Home-Bildschirm installiert sein.
</details>

<details>
<summary><b>Mein Code wird angeblich schon auf einem anderen Gerät verwendet.</b></summary>
Jeder Code gilt nur auf einem Gerät. Frag auf Telegram nach einem neuen.
</details>

<details>
<summary><b>Muss ich die App aktualisieren?</b></summary>
Nein. Sie aktualisiert sich bei jedem Öffnen selbst.
</details>

<details>
<summary><b>Werden Zeichnungen und Indikatoren zwischen Geräten synchronisiert?</b></summary>
Noch nicht: sie werden auf dem Gerät gespeichert, auf dem du sie erstellt hast.
</details>

---

## 🗺️ Roadmap

| Status | Funktion |
|---|---|
| ✅ | Watchlist, Live-Chart, Zeiteinheiten, Chart-Typen, eigene Farben |
| ✅ | Zeichenwerkzeuge, Bar Replay, Chart-Hub, Layouts |
| ✅ | 42 integrierte Indikatoren, Favoriten, Indikator-Einstellungen |
| ✅ | Mit Pine Script™ kompatible Engine und Skript-Editor |
| ✅ | Preisalarme mit Push-Benachrichtigungen |
| ✅ | Dunkles und helles Design |
| ✅ | Design 3.0: Willkommensbildschirme, Logo-Animation, Sprachmenü mit Umlaufbahn |
| ✅ | Design-3.0-Anmeldung: Logo mit Umlaufbahn, Zugangscode in 8 Feldern, runde Flaggen |
| ✅ | 5 Sprachen: Italienisch, Englisch, Spanisch, Französisch, Deutsch |
| ✅ | Design 3.0 in der App, mehrere Watchlists, Signale, Linienstärke/-stil und Rückgängig |
| 🔜 | Schnelleres Laden der Daten |
| 🔜 | Volle Computer-Version |
| 💡 | Synchronisierung zwischen Geräten |

---

## 🙏 Danksagungen

- Charts mit [TradingView Lightweight Charts™](https://www.tradingview.com/lightweight-charts/) (Apache 2.0).
- TradingView und Pine Script sind Marken von TradingView, Inc. NexusCharts ist nicht mit TradingView verbunden.

---

## ⚠️ Haftungsausschluss

NexusCharts ist ein Analysewerkzeug. Nichts in der App ist eine Finanzberatung. Trading ist mit Risiken verbunden: recherchiere immer selbst.

<div align="center">

**© 2026 NexusCharts — Alle Rechte vorbehalten.**

</div>
