# Haupt Bot

Discord-Bot für Moderation, Verifikation, Tickets, Umfragen, Warnsystem und Logging.

## Einrichtung

1. Kopiere `.env.example` nach `.env`.
2. Trage deinen Discord-Bot-Token und die Server-IDs ein.
3. Starten:

```bash
npm start
```

## Wichtige Hinweise

- Für Slash-Commands muss der Bot auf dem Zielserver installiert sein.
- Der Bot versucht automatisch fehlende Textkanäle zu erstellen.
- Für den Verifikations- und Ticket-Teil sollten die Rollen und Kanalnamen auf dem Server entsprechend benannt sein.

## Standardrollen

- `nicht verify`
- `Verify`
- `MEMBER`
- `head of Projekt`
- `Verwarnung I`
- `Verwarnung II`
- `Verwarnung III`

## Standardkanäle

- `#verify✅`
- `#ticket🎫`
- `#arohn-nachrichten`
- `#umfragen`
- `#umfragen-top-10`
- `#umfragen-logs-arohn`
- `#chat😀`
- `#punkt-chat`

## Bot-Namen

Der Bot wird beim Start auf `DC BOTTS HUB 4` gesetzt. Wenn du den Namen ändern willst, bearbeite `BOT_USERNAME` in der `.env`.
