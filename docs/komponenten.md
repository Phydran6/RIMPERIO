# Komponenten

Was in welchem Repo steckt, womit es gebaut ist und wo man hineinspringt.

← [Übersicht](../README.md) · [Architektur](architektur.md) · [Wegweiser](wegweiser.md)

---

## 🖥️ RIMPERIO-Server

> Der Kern. Nimmt Agents an, überwacht, patcht, zeigt alles im Browser und
> verwaltet sich selbst.

**[github.com/Phydran6/RIMPERIO-Server](https://github.com/Phydran6/RIMPERIO-Server)**

| | |
|---|---|
| **Technik** | Docker Compose, FastAPI (Python), Vue 3 + Tailwind, PostgreSQL 17, Caddy 2, Go-Agent |
| **Installation** | ein Befehl: `curl -sSL …/install.sh \| sudo bash` |
| **Betrieb** | alles im Browser — keine Konfigurationsdatei anfassen |
| **Lizenz** | MIT |

### Verzeichnisse

| Verzeichnis | Inhalt |
|---|---|
| [`backend/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/backend) | FastAPI: API, Auth, Enrollment, Check-in, Checks, Patches, Alarme, Webhooks |
| [`frontend/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/frontend) | Vue 3: Dashboard, Agents, Checks, Skripte, Patches, Integrationen |
| [`agent/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/agent) | Go-Agent (ein Binary) für Windows und Linux |
| [`installer/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/installer) | `.exe`/`.msi` bauen, signieren, verteilen |
| [`caddy/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/caddy) · [`db/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/db) · [`deploy/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/deploy) | Reverse Proxy, Datenbank, Betrieb |
| [`docs/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/docs) | Architektur und Bedienung |

---

## 📱 RIMPERIO-App

> Die eigene Instanz am Handy: gehärtete WebView auf den eigenen Server, Token
> verschlüsselt auf dem Gerät, Sperre per Biometrie.

**[github.com/Phydran6/RIMPERIO-App](https://github.com/Phydran6/RIMPERIO-App)**

| | |
|---|---|
| **Technik** | Flutter / Dart (Android &amp; iOS aus einer Quelle) |
| **Prinzip** | WebView auf `https://DEIN-SERVER/`, Zugangsdaten verschlüsselt (`flutter_secure_storage`) |
| **Bauen** | `flutter pub get` · `flutter build apk` bzw. `flutter run` |

---

## 🧭 RIMPERIO *(diese Repo)*

> Die Landkarte. Kein Code, keine Releases, keine Tags — nur Übersicht.

| Datei | Inhalt |
|---|---|
| [`README.md`](../README.md) | Einstieg: was RIMPERIO ist, die Bausteine, Schnellstart |
| [`docs/architektur.md`](architektur.md) | Zusammenspiel, Datenwege, Zugänge |
| [`docs/komponenten.md`](komponenten.md) | diese Seite |
| [`docs/wegweiser.md`](wegweiser.md) | jeder wichtige Link an einer Stelle |

---

## Weiter

- [Architektur](architektur.md)
- [Wegweiser — alle Links](wegweiser.md)
