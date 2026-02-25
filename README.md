<div align="center">

# 📱 PocketChat

**Dein Stream. In deiner Tasche.**

Die mobile Companion-App für Live-Streamer — Chat aller Plattformen, Stream-Events und TTS, alles auf deinem Handy.

[![Twitch](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv)
[![Kick](https://img.shields.io/badge/Kick-53FC18?style=for-the-badge&logo=kick&logoColor=black)](https://kick.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com)

</div>

---

## ✨ Was ist PocketChat?

PocketChat ist für Streamer gebaut, die auch abseits des PCs mit ihrem Chat interagieren wollen. Ob beim IRL-Streamen, Kochen oder auf der Couch — Chat und Events immer im Blick.

PocketChat betreibt eine eigene Backend-API. Kein Drittanbieter, keine Datenweitergabe. **Dein Stream, deine Daten.**

---

## 💬 Chat

Alle Plattformen in einer einheitlichen Ansicht.

| Plattform | Chat lesen | Chat senden |
|-----------|-----------|-------------|
| **Twitch** | ✅ | ✅ |
| **Kick** | ✅ | ✅ |
| **YouTube** | 🔜 Soon | 🔜 Soon |

- **Unified Chat Feed** — alle Plattformen in einer Liste, farblich nach Quelle unterschieden
- **Nachrichten senden** — direkt vom Handy an Twitch, Kick oder alle Plattformen gleichzeitig
- **Plattform-Switcher** — Icon antippen für die gewünschte Plattform (Twitch → Kick → YouTube → ALL)
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
| **Streamlabs** | 🔜 Soon | 🔜 Soon | 🔜 Soon | 🔜 Soon | 🔜 Soon |

**Was angezeigt wird:**
- 💸 Donationen mit Betrag, Währung und Nachricht
- ⭐ Subscriptions mit Monatszahl, Tier (1/2/3) und Gift-Info
- 🎁 Gift-Bombs — „eddiich hat 5 Subs verschenkt"
- ❤️ Follows
- 💎 Cheers mit Bit-Anzahl
- ⚔️ Raids mit Zuschauerzahl

**Event-Filter** — selbst wählen, welche Event-Typen angezeigt werden sollen. Nur Donos und Raids? Kein Problem.

**Teilbares Split-View** — Trennlinie zwischen Events und Chat verschieben für die perfekte Aufteilung.

---

## 🔊 Text-to-Speech

Lass deinen Stream sprechen — direkt in der App, ohne zusätzliche Drittanbieter-Software. Folgende Anbieter werden unterstützt:

- **On-Device TTS** — kostenlos, funktioniert offline
- **Amazon Polly** — natürliche Cloud-Stimmen
- **ElevenLabs** — hochwertige KI-Stimmen

Viewer können per Bits, Donationen oder Kanalpunkten TTS-Nachrichten abspielen. In Zukunft soll es außerdem automatische TTS ab einem konfigurierbaren Mindestbetrag geben.

---

## 📡 BelaBox Integration

Voller Überblick über deine BelaBox-Stats direkt im Chat-Tab.

- Live-Bitrate aller Netzwerk-Interfaces zusammengefasst
- Streaming-Status und Offline-Erkennung mit visueller Warnung
- Stream starten und stoppen

---

## 🔔 Alert Box

Integrierter WebView für browserbasierte Alert-Overlays.

- StreamElements-, Streamlabs- oder eigene Alert-Box-URL eintragen
- Alerts spielen direkt in der App ab — kein zweites Gerät nötig

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
- Optional: Kick, TipeeeStream, StreamElements, Amazon Polly oder ElevenLabs

---

## 🚀 Erste Schritte

### App installieren

APK von der [Releases](../../releases)-Seite herunterladen und auf dem Android-Gerät installieren.

### Verbinden

1. **Twitch verbinden** antippen und autorisieren
2. Optional: Kick unter **Accounts** verbinden
3. Optional: TipeeeStream oder StreamElements unter **Events → Quellen** verbinden
4. Chat-Tab öffnen — du bist live 🎉

---

## 🛣️ Roadmap

- [ ] YouTube Chat & Senden
- [ ] Replay von Events (Tipeeestream/Streamelements etc.)
- [ ] OBS Anbindung (Stream Start/Stop, Szenenwechsel etc.)
- [ ] TTS-Konfiguration pro Event-Typ (z.B. Donationen ab 5 € vorlesen)
- [ ] Mod-Aktionen im Chat Tab
- [ ] Tabs aus/einblenden
- [ ] Streamlabs als Event-Quelle
- [ ] iOS-Version

---

## 📄 Lizenz

MIT — mach damit was du willst aber bleibt fair und gib Credits.

---

<div align="center">

Mit ♥ gemacht — von einem Nerd, für Streamer.

</div>
