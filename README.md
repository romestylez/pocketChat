<div align="center">

# 📱 PocketChat

**Dein Stream. In deiner Tasche.**

Die mobile Companion-App für Live-Streamer — Chat aller Plattformen, Stream-Events und TTS, alles auf deinem Handy.

[![Twitch](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv)
[![Kick](https://img.shields.io/badge/Kick-53FC18?style=for-the-badge&logo=kick&logoColor=black)](https://kick.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com)
[![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apple.com)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/romestylez/pocketChat/releases)

</div>

---

## ✨ Was ist PocketChat?

PocketChat ist für Streamer gebaut, die auch abseits des PCs mit ihrem Chat interagieren wollen. Ob beim IRL-Streamen, Kochen oder auf der Couch — Chat und Events immer im Blick.

PocketChat betreibt eine eigene Backend-API. Kein Drittanbieter, keine Datenweitergabe. **Dein Stream, deine Daten.**

---

## 💬 Chat

Alle Plattformen in einer einheitlichen Ansicht.

| Plattform | Chat lesen | Chat senden | Nachricht löschen | Timeout | Ban |
|-----------|-----------|-------------|-------------------|---------|-----|
| **Twitch** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Kick** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **YouTube** | ✅ | ✅ | — | — | — |

- **Unified Chat Feed** — alle Plattformen in einer Liste, farblich nach Quelle unterschieden
- **Nachrichten senden** — direkt vom Handy an Twitch, Kick, YouTube oder alle Plattformen gleichzeitig
- **Plattform-Switcher** — Icon antippen für die gewünschte Plattform (Twitch → Kick → YouTube → ALL)
- **Mod-Aktionen** — Nachrichten löschen, User timeouten oder bannen direkt aus dem Chat-Feed (Twitch & Kick)
- **Emotes** — Twitch-Emotes sowie BTTV, FFZ und 7TV
- **Badges** — Subscriber-, Mod-, VIP-, Broadcaster- und alle channel-spezifischen Badges
- **Chat-Historie** — letzte Nachrichten werden beim Verbinden geladen
- **Ignore-Liste** — Bots und Spam-User aus dem Chat-Feed filtern

---

## 🎉 Stream Events

Echtzeit-Benachrichtigungen für alles, was in deinem Stream passiert.

**Event-Plattformen verbinden:**

| Plattform | Donationen | Subs | Follows | Cheers | Raids |
|-----------|-----------|------|---------|--------|-------|
| **TipeeeStream** | ✅ | ✅ | ✅ | ✅ | — |
| **StreamElements** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Streamlabs** | ✅ | ✅ | ✅ | ✅ | ✅ |

**Was angezeigt wird:**
- 💸 Donationen mit Betrag, Währung und Nachricht
- ⭐ Subscriptions mit Monatszahl, Tier (1/2/3) und Gift-Info
- 🎁 Gift-Bombs — „eddiich hat 5 Subs verschenkt"
- ❤️ Follows
- 💎 Cheers mit Bit-Anzahl
- ⚔️ Raids mit Zuschauerzahl

**Event-Filter** — selbst wählen, welche Event-Typen angezeigt werden sollen. Nur Donos und Raids? Kein Problem.

**Event-Replay** — vergangene Events erneut abspielen (TipeeeStream, StreamElements, Streamlabs).

**Teilbares Split-View** — Trennlinie zwischen Events und Chat verschieben für die perfekte Aufteilung.

---

## 🔊 Text-to-Speech

Lass deinen Stream sprechen — direkt in der App, ohne zusätzliche Drittanbieter-Software. Folgende Anbieter werden unterstützt:

- **On-Device TTS** — kostenlos, funktioniert offline
- **Amazon Polly** — natürliche Cloud-Stimmen (156 Stimmen, alle Engines)
- **ElevenLabs** — hochwertige KI-Stimmen

Viewer können per Bits, Donationen oder Kanalpunkten TTS-Nachrichten abspielen. TTS ab einem konfigurierbaren Mindestbetrag für Donationen ist in Planung.

**Chat vorlesen** — der komplette Chat-Feed kann automatisch vorgelesen werden. Plattform wählbar: alle, nur Twitch, nur Kick oder nur YouTube etc.

**TTS-Delay** — konfigurierbarer Verzögerungspuffer, damit Ansagen von trägen Boxen nicht abgeschnitten werden.

---

## 📡 BelaBox / SRT Stats

Live-Überblick über deinen Stream-Output — zwei Modi werden unterstützt:

- **BelaBox (Hardware)** — Verbindung über den BelaBox Secret-Link, wie auf der offiziellen BelaBox-Seite. Zeigt Live-Bitrate aller Netzwerk-Interfaces (cam, usb0, usb1, wg0 etc.) sowie Streaming-Status mit Offline-Erkennung. Stream starten/stoppen und Interfaces deaktivieren direkt aus der App.
- **JSON-Stats-URL** — für alle anderen Quellen die Stats als JSON ausliefern, z.B. Bela Cloud oder eigene SRT-Server. Nur Anzeige der Bitrate, keine Steuerung.

---

## 🎛️ PocketDeck

Anpassbares Streamboard direkt in PocketChat — kein separates Streamdeck nötig.

- **Button-Grid** — frei konfigurierbare Kacheln, Anzahl pro Zeile einstellbar
- **OBS-Integration** — Szenen wechseln, Quellen und Filter ein-/ausschalten (via OBS WebSocket v5)
- **Twitch Chat-Steuerung** — Subs-only, Emote-only, Followers-only und Slow-Mode direkt per Knopf
- **TTS-Warteschlange leeren** — mit einem Tipp alle ausstehenden TTS-Nachrichten abbrechen
- **Bestätigungsabfrage** — kritische Aktionen können mit Sicherheitsabfrage gesichert werden
- **Live-Status** — OBS-Verbindungsstatus und aktive Chat-Modi werden in Echtzeit angezeigt
- **Zwei Zugangswege** — als eigener Tab in der Navigation oder als kompaktes Popup über den ⚡-Button im Chat

> *OBS-Verbindung (IP, Port, Passwort) wird direkt in den PocketDeck-Einstellungen konfiguriert.*

---

## 🔔 Alert Box

Integrierter WebView für browserbasierte Alert-Overlays.

- StreamElements-, Streamlabs- oder eigene Alert-Box-URL eintragen
- Alerts spielen direkt in der App ab — kein zweites Gerät nötig

---

## 🎥 DJI Kamera Integration

Verbinde deine DJI Kamera (Osmo, Pocket, Action) direkt per Bluetooth mit PocketChat — ohne Moblin oder iOS.

- **BLE-Verbindung** — automatische Kamerasuche, Auto-Connect beim App-Start optional
- **RTMP Stream Start / Stop** — Stream direkt von der Kamera starten und stoppen
- **WiFi-Konfiguration** — SSID und Passwort direkt in der App eintragen
- **Live-Akkustand** — wird in der App, in der Titelleiste und als OBS Browser Source angezeigt
- **Browser Source URL** — Akkustand farbkodiert (grün/orange/rot) für OBS, aktualisiert sich automatisch alle 5 Sekunden
- **Legacy-Modus** — `&legacy=1` gibt nur den reinen Prozentwert zurück, nutzbar in Streamer.bot oder Chat-Commands

> ⚠️ Nicht kompatibel mit Moblin — DJI Kameras erlauben nur eine BLE-Verbindung gleichzeitig.

---

## 🌐 Browser Tab

Eingebetteter Browser direkt in der App — frei konfigurierbar.

- **Eigene URL** — beliebige Webseite als Tab einbinden (z.B. Stream-Stats, Dashboards, OBS-Overlays)
- **Persistente Cookies** — Sitzungen und Logins bleiben auch nach App-Neustart erhalten
- **Frei benennbar** — Tab-Name selbst wählen (z.B. „Stats", „Twitch", „Dashboard")
- **JavaScript & DOM Storage** — volle Browser-Funktionalität, keine Einschränkungen

---

## 🔧 Architektur

PocketChat nutzt eine **eigene Backend-API** als sichere Schnittstelle zwischen App und den Streaming-Plattformen.

```
Twitch / Kick / YouTube
         │
    [PocketChat API]       ← Node.js + WebSocket + OAuth
         │
    [PocketChat App]       ← Android, Jetpack Compose
```

**Warum eine eigene API?**
- OAuth-Tokens bleiben auf dem eigenen Server
- Chat wird plattformübergreifend normalisiert und dedupliziert
- Twitch-Badges, Emotes und Chat-Historie werden serverseitig gecacht
- Token-Refresh läuft automatisch — keine Unterbrechung

---

## 📋 Voraussetzungen

- Android 8.0+
- Twitch-Account für den Login
- Optional: Kick, YouTube, TipeeeStream, StreamElements, Amazon Polly, ElevenLabs
- Optional: OBS 28+ mit aktiviertem WebSocket-Server für OBS Remote
- Optional: DJI Kamera (Osmo Pocket, Action Series) für BLE-Integration

---

## 🚀 Erste Schritte

### App installieren

APK von der [Releases](../../releases)-Seite herunterladen und auf dem Android-Gerät installieren.

### Verbinden

1. **Twitch verbinden** antippen und autorisieren
2. Optional: Kick oder YouTube unter **Accounts** verbinden
3. Optional: TipeeeStream oder StreamElements unter **Events → Quellen** verbinden
4. Optional: pocketDeck unter **Hamburger-Menü → pocketDeck** konfigurieren
5. Chat-Tab öffnen — du bist live 🎉

---

## 🛣️ Roadmap

- [ ] TTS-Konfiguration pro Event-Typ (z.B. Donationen ab 5 € vorlesen)
- [ ] Mod-Aktionen: weitere Plattformen (YouTube)
- [ ] iOS-Version

---

## 📄 Lizenz

MIT — mach damit was du willst aber bleibt fair und gib Credits.

---

<div align="center">

Mit ♥ gemacht — von einem Nerd, für Streamer.

</div>
