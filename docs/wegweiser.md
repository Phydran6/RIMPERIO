# Wegweiser

Jeder Link, den man beim Arbeiten an RIMPERIO braucht — an einer Stelle.

← [Übersicht](../README.md) · [Architektur](architektur.md) · [Komponenten](komponenten.md)

---

## Die drei Repos

| Repo | Code | Issues | Commits | Releases |
|---|---|---|---|---|
| **RIMPERIO-Server** | [→](https://github.com/Phydran6/RIMPERIO-Server) | [→](https://github.com/Phydran6/RIMPERIO-Server/issues) | [→](https://github.com/Phydran6/RIMPERIO-Server/commits/main) | [→](https://github.com/Phydran6/RIMPERIO-Server/releases) |
| **RIMPERIO-App** | [→](https://github.com/Phydran6/RIMPERIO-App) | [→](https://github.com/Phydran6/RIMPERIO-App/issues) | [→](https://github.com/Phydran6/RIMPERIO-App/commits/main) | [→](https://github.com/Phydran6/RIMPERIO-App/releases) |
| **RIMPERIO** *(hier)* | [→](https://github.com/Phydran6/RIMPERIO) | [→](https://github.com/Phydran6/RIMPERIO/issues) | [→](https://github.com/Phydran6/RIMPERIO/commits/main) | keine |

---

## Server — in den Code springen

| Was | Datei |
|---|---|
| Installer | [`install.sh`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/install.sh) |
| Compose-Stack | [`docker-compose.yml`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/docker-compose.yml) |
| Backend-Einstieg | [`backend/app/main.py`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/backend/app/main.py) |
| Datenmodelle | [`backend/app/models.py`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/backend/app/models.py) |
| Agent-Ingest / Check-in | [`backend/app/routes/ingest.py`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/backend/app/routes/ingest.py) |
| Webhooks | [`backend/app/events.py`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/backend/app/events.py) |
| Agent (Go) | [`agent/cmd/rimperio-agent/main.go`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/agent/cmd/rimperio-agent/main.go) |
| Patchmanagement (Agent) | [`agent/internal/core/patch.go`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/agent/internal/core/patch.go) |
| Checks (Agent) | [`agent/internal/core/checks.go`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/agent/internal/core/checks.go) |
| Oberfläche | [`frontend/src/views/`](https://github.com/Phydran6/RIMPERIO-Server/tree/main/frontend/src/views) |
| Installer &amp; Signatur | [`installer/README.md`](https://github.com/Phydran6/RIMPERIO-Server/blob/main/installer/README.md) |

## Server — Dokumentation

| Thema | Link |
|---|---|
| Architektur | [docs/architektur.md](https://github.com/Phydran6/RIMPERIO-Server/blob/main/docs/architektur.md) |
| Bedienung | [docs/bedienung.md](https://github.com/Phydran6/RIMPERIO-Server/blob/main/docs/bedienung.md) |
| n8n / Telegram / KI | [n8n/README.md](https://github.com/Phydran6/RIMPERIO-Server/blob/main/n8n/README.md) |

## App

| Was | Datei |
|---|---|
| App-Einstieg | [`lib/main.dart`](https://github.com/Phydran6/RIMPERIO-App/blob/main/lib/main.dart) |
| Einrichtung (Server-URL) | [`lib/setup_page.dart`](https://github.com/Phydran6/RIMPERIO-App/blob/main/lib/setup_page.dart) |
| WebView | [`lib/webview_page.dart`](https://github.com/Phydran6/RIMPERIO-App/blob/main/lib/webview_page.dart) |

---

## Alle offenen Punkte

[alle offenen Issues](https://github.com/search?q=owner%3APhydran6+repo%3APhydran6%2FRIMPERIO-Server+repo%3APhydran6%2FRIMPERIO-App+repo%3APhydran6%2FRIMPERIO+is%3Aissue+is%3Aopen&type=issues)

---

## Weiter

- [Architektur](architektur.md)
- [Komponenten](komponenten.md)
