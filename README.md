<div align="center">

# 📱 pocketChat

**Dein Stream. In deiner Tasche.**

Die mobile Companion-App für Live-Streamer — Chat aller Plattformen, Stream-Events und TTS, alles auf deinem Handy.

[![Twitch](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv)
[![Kick](https://img.shields.io/badge/Kick-53FC18?style=for-the-badge&logo=kick&logoColor=black)](https://kick.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com)
[![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/de/app/pocketchat/id6760356504)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://play.google.com/store/apps/details?id=dev.romestylez.pocketchat)

</div>

---

## ✨ Was ist pocketChat?

pocketChat ist für Streamer gebaut, die auch abseits des PCs mit ihrem Chat interagieren wollen. Ob beim IRL-Streamen, Kochen oder auf der Couch — Chat und Events immer im Blick.

pocketChat betreibt eine eigene Backend-API. Kein Drittanbieter, keine Datenweitergabe. **Dein Stream, deine Daten.**

---

## 💬 Chat

Alle Plattformen in einer einheitlichen Ansicht.

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

| Plattform | Donationen | Subs | Follows | Cheers | KICKs | Raids | Channel Points | Super Chats | Super Stickers | Juwelen | Mitgliedschaften |
|-----------|------------|------|---------|--------|-------|-------|----------------|-------------|----------------|---------|------------------|
| **Twitch** | — | ✅ | ✅ | ✅ | — | ✅ | ✅ | — | — | — | — |
| **Kick** | — | ✅ | ✅ | — | ✅ | — | ✅ | — | — | — | — |
| **YouTube** | — | — | — | — | — | — | — | ✅ | ✅ | ✅ | ✅ |
| **TipeeeStream** | ✅ | ✅ | ✅ | ✅ | — | — | — | — | — | — | — |
| **StreamElements** | ✅ | ✅ | ✅ | ✅ | — | ✅ | — | — | — | — | — |
| **Ko-fi** | ✅ | — | — | — | — | — | — | — | — | — | — |
| **PayPal** | ✅ | — | — | — | — | — | — | — | — | — | — |

Bei YouTube umfasst **Mitgliedschaften** auch verschenkte Mitgliedschaften. Weitere Twitch-Events wie Combos, Watch Streaks, Hype Trains, empfangene Shoutouts und Creator Goals stehen im Feed.

Twitch, Kick und YouTube werden unter **Accounts** verbunden; die übrigen Event-Quellen unter **Events → Quellen**. Streamlabs kann als Alert-Box eingebunden werden, steht aber nicht als eigene Quelle im aktuellen Event-Filter.

**Was angezeigt wird:**
- 💸 Donationen mit Betrag, Währung und Nachricht
- ⭐ Subscriptions mit Monatszahl, Tier (1/2/3) und Gift-Info
- 🎁 Gift-Bombs — „romestylez hat 5 Subs verschenkt"
- ❤️ Follows
- 💎 Cheers mit Bit-Anzahl
- ⚔️ Raids mit Zuschauerzahl
- 🎯 Channel Point Redemptions und Creator Goals (Twitch)
- 📣 Empfangene Shoutouts (Twitch)
- 🔥 Combo-Events und Watch Streaks (Twitch)
- 🚂 Hype Trains (Twitch) und KICKs (Kick)
- 🔴 YouTube Super Chats mit Betrag und Nachricht
- 🌟 YouTube Super Stickers, Juwelen-Geschenke und Mitgliedschaften (auch verschenkte)
- 🅿️ Direkte PayPal-Spenden mit Betrag und Nachricht

**Event-Filter** — selbst wählen, welche Event-Typen angezeigt werden sollen und welche Quelle sie liefert. Nur Donos und Raids? Kein Problem.

**Events zu TTS** — Follows, Subs, Cheers, Raids, Hype Trains, KICKs, YouTube-Events und Donations nach eigenen Regeln ansagen lassen. Details stehen im Abschnitt [Text-to-Speech](#-text-to-speech).

**Event-Sounds** — eigene Audiodateien importieren und vor ausgewählten Event-Ansagen abspielen.

**Event-Replay** — vergangene Events erneut abspielen (TipeeeStream, StreamElements, Streamlabs).

**Teilbares Split-View** — Trennlinie zwischen Events und Chat verschieben für die perfekte Aufteilung.

**„Über dem Chat anzeigen"** — Events lassen sich über dem Chat ein- oder ausblenden. Wenn deaktiviert, füllt der Chat die volle Bildschirmhöhe. Browser-Tabs mit aktiviertem „Über dem Chat" bleiben dabei weiterhin sichtbar.

---

## 🔊 Text-to-Speech

Lass deinen Stream sprechen — direkt in der App, ohne zusätzliche Drittanbieter-Software. Folgende Anbieter werden unterstützt:

- **On-Device TTS** — kostenlos, funktioniert offline
- **Amazon Polly** — natürliche Cloud-Stimmen (156 Stimmen, alle Engines)
- **ElevenLabs** — hochwertige KI-Stimmen
- **Google Cloud TTS** — Cloud-Stimmen über einen eigenen API Key

Viewer können per Bits, Donationen oder Kanalpunkten TTS-Nachrichten abspielen.

**Chat vorlesen** — der komplette Chat-Feed kann automatisch vorgelesen werden. Plattform wählbar: alle, nur Twitch, nur Kick oder nur YouTube etc.

**Events zu TTS** — unter **Events → Events zu TTS** für Twitch, Kick, YouTube, TipeeeStream, StreamElements, Ko-fi und PayPal getrennt einrichten. Pro Plattform gibt es einen Hauptschalter und eine Stimmauswahl; jeder unterstützte Eventtyp lässt sich einzeln aktivieren und mit einem eigenen Ansagetext versehen. Dazu gehören beispielsweise Twitch-Follows, Subs, Cheers, Raids und Hype Trains, Kick-Follows, Subs und KICKs sowie YouTube-Superchats, Super Sticker, Juwelen und Mitgliedschaften. Bei den externen Donation-Quellen werden Donations angesagt.

**Varianten nach Betrag und Anzahl** — für passende Events lassen sich zusätzliche Ansagevarianten anlegen, etwa ein anderer Text für Donations ab einem bestimmten Wert. Jede Variante kann einen eigenen Text, eine Stimmauswahl und einen Event-Sound erhalten.

**Event-Sounds** — MP3-, M4A-, AAC- oder WAV-Dateien in **Events → Event-Sounds** importieren und vor einer Ansage abspielen. Sound und Ansage bleiben in der gemeinsamen Warteschlange zusammen.

**TTS-Warteschlange** — Ansagen pausieren, fortsetzen, überspringen oder die wartenden Einträge leeren. Event-Ansagen werden vor bereits wartenden Chat-Nachrichten eingeordnet.

**Moderator-Steuerung** — einen persönlichen Link für vertrauenswürdige Moderatoren erzeugen, damit sie TTS pausieren, fortsetzen, die Warteschlange leeren und das Vorlesen einzelner Chat-Plattformen steuern können.

**Vorlaufstille** — konfigurierbarer Verzögerungspuffer (bis 500 ms), damit Ansagen von trägen Boxen nicht abgeschnitten werden.

**Keep-Alive** — optionaler Stille-Ton im Hintergrund verhindert, dass Bluetooth-Boxen in den Standby wechseln und den Anfang der nächsten TTS-Ansage abschneiden. Intervall frei einstellbar.

---

## 📡 SRT/SRTLA Stats & Bela Control

Live-Überblick über deinen Stream-Output — getrennt nach Stats-only und BelaBox-Steuerung:

- **SRT/SRTLA Stats** — Belabox Cloud oder eine eigene SRT Stats URL als reine Stats-Quelle.
- **Bela Control** — Verbindung über Belabox Secret oder lokale BelaBox IP mit Steuerung und Stats.
- **Gemeinsamer Anzeige-Tab** — heißt je nach aktiver Quelle **SRT** oder **Bela**.

---

## 🎛️ pocketDeck

Anpassbares Streamboard direkt in pocketChat — kein separates Streamdeck nötig.

- **Button-Grid** — frei konfigurierbare Kacheln, Anzahl pro Zeile einstellbar
- **OBS-Integration** — Szenen wechseln, Quellen und Filter ein-/ausschalten (via OBS WebSocket v5)
- **OBS Audio-Toggle** — Mikrofon oder Desktop-Audio per Knopfdruck stumm/aktiv schalten, 🔊/🔇 zeigt den Live-Status direkt auf dem Button
- **Multi Action Buttons** — mehrere Aktionen auf einen einzigen Button legen, inklusive Pausen zwischen den Schritten (z.B. Szene wechseln, 2 Sekunden warten, Mikro aktivieren)
- **Twitch Chat-Steuerung** — Subs-only, Emote-only, Followers-only und Slow-Mode direkt per Knopf
- **TTS-Warteschlange leeren** — mit einem Tipp alle ausstehenden TTS-Nachrichten abbrechen
- **Bestätigungsabfrage** — kritische Aktionen können mit Sicherheitsabfrage gesichert werden
- **Live-Status** — OBS-Verbindungsstatus und aktive Chat-Modi werden in Echtzeit angezeigt
- **Zwei Zugangswege** — als eigener Tab in der Navigation und/oder als kompaktes Popup über den ⚡-Button im Chat

> *OBS-Verbindung (IP, Port, Passwort) wird direkt in den pocketDeck-Einstellungen konfiguriert.*

---

## 🔔 Alert Box

Integrierter WebView für browserbasierte Alert-Overlays.

- StreamElements-, Streamlabs- oder eigene Alert-Box-URL eintragen
- Alerts spielen direkt in der App ab — kein zweites Gerät nötig

---

## 🎥 DJI Kamera Integration

Verbinde deine DJI Kamera (Osmo, Pocket, Action) direkt per Bluetooth mit pocketChat — ohne Moblin oder iOS.

- **BLE-Verbindung** — automatische Kamerasuche, Auto-Connect beim App-Start optional
- **RTMP Stream Start / Stop** — Stream direkt von der Kamera starten und stoppen
- **WiFi-Konfiguration** — SSID und Passwort direkt in der App eintragen
- **Kamera-Profile** — mehrere Kamera-Setups (WLAN, RTMP, Bitrate, Auflösung, FPS, Stabilisierung) speichern und per Tipp umschalten; optional ein Profil für Auto-Stream beim Verbinden
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

pocketChat nutzt eine **eigene Backend-API** als sichere Schnittstelle zwischen App und den Streaming-Plattformen.

```
Twitch / Kick / YouTube
         │
    [pocketChat API]       ← Node.js + WebSocket + OAuth
         │
    [pocketChat App]       ← Android (Jetpack Compose) & iOS (Swift/KMP)
```

**Warum eine eigene API?**
- OAuth-Tokens bleiben auf dem eigenen Server
- Chat wird plattformübergreifend normalisiert und dedupliziert
- Twitch-Badges, Emotes und Chat-Historie werden serverseitig gecacht
- Token-Refresh läuft automatisch — keine Unterbrechung

---

## 📋 Voraussetzungen

- Android 8.0+
- iOS 16.0+
- Twitch-Account für den Login
- Optional: Kick, YouTube, TipeeeStream, StreamElements, Ko-fi, PayPal, Amazon Polly, ElevenLabs, Google Cloud TTS
- Optional: OBS 28+ mit aktiviertem WebSocket-Server für OBS Remote
- Optional: DJI Kamera (Osmo Pocket, Action Series) für BLE-Integration

---

## 🚀 Erste Schritte

### App installieren

**Android**
pocketChat im [Google Play Store](https://play.google.com/store/apps/details?id=dev.romestylez.pocketchat) laden.

**iOS**
pocketChat im [App Store](https://apps.apple.com/de/app/pocketchat/id6760356504) laden.

Bug Reports bitte in meinen [Discord](https://discord.gg/h89JeFHm6n).

### Verbinden

1. **Twitch verbinden** antippen und autorisieren
2. Optional: Kick oder YouTube unter **Accounts** verbinden
3. Optional: Event-Quellen unter **Events → Quellen** verbinden
4. Optional: **Events → Events zu TTS** und **Events → Event-Sounds** einrichten
5. Optional: pocketDeck unter **Hamburger-Menü → pocketDeck** konfigurieren
6. Chat-Tab öffnen — du bist live 🎉

---

## 📄 Lizenz

MIT — mach damit was du willst aber bleibt fair und gib Credits.

---

<div align="center">

Mit ♥ gemacht — von einem Nerd, für Streamer.

</div>
