# TRYP EXPO 2027 · Delegationsdossier

Passwortgeschuetzte Kuration neuer Pflanzenmedizin-Delegationen fuer TRYP EXPO Berlin 2027 (SuperBrain-gestuetzt, 6 Kandidaten-Gemeinschaften, Governance-first-Kriterien).

- **Live:** https://noiion828-ui.github.io/tryp-expo-delegationsdossier/
- **Passwort:** siehe persoenliche Nachricht
- **Quelle (claude.ai Artifact, mit Live-Feedback-Sync):** https://claude.ai/code/artifact/819e5a59-4641-433f-b56d-af7d99495c16

## Anti-Discovery-Schicht

- `<meta name="robots" content="noindex, nofollow, noarchive">`
- `robots.txt` blockt alle Crawler
- JS-Password-Gate (clientseitig, SHA-256 via Web Crypto) — bewusste Friction gegen zufaelliges Oeffnen eines geteilten Links, kein Schutz gegen einen determinierten Angreifer (Inhalt bleibt in View-Source lesbar)

## Unterschied zur claude.ai-Version

Diese GitHub-Pages-Version ist ein statischer Snapshot fuer Empfaenger ohne Claude-Zugang. Die Feedback-Buttons/Notizfelder funktionieren interaktiv, speichern aber NICHT dauerhaft (keine artifact-Sync-Capability ausserhalb claude.ai) — reine Gespraechs-Gedaechtnisstuetze vor Ort.

## Deploy

```bash
git push origin main
# GitHub Pages aktiviert sich auf main / root
```
