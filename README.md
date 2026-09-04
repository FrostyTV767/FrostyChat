# FrostyChat v5

Enthält:
- Reaktionen 👍
- Antworten ↩️
- Nachrichten löschen 🗑️ (nur eigene)
- Bilder senden 🖼️ (bis 2 MB)
- mehrere Textkanäle: #allgemein, #gaming, #memes
- @-Text kann normal geschrieben werden (visuell vorbereitet; echte Mention-Benachrichtigung folgt später)
- Profile/Profilkarten
- ungelesene Nachrichten-Badges bei anderen Kanälen
- echter P2P-Chat zwischen Geräten über PeerJS
- Raum-Code und Online-Status

## Nutzung
Wie bei v2: `index.html` auf beiden Geräten öffnen, Raum erstellen, Code teilen und auf dem zweiten Gerät beitreten.

Hinweis: Für die P2P-Verbindung wird PeerJS aus dem Internet geladen. Der Host muss online bleiben.
\n\n## v4 mobile/scroll fixes\n- Nachrichtenbereich scrollt zuverlässig auch bei vielen Nachrichten.\n- Bilder bleiben innerhalb des Chatbereichs und lassen sich ohne horizontales Überlaufen anzeigen.\n- Auf Hochformat-Handys wird der Chat breiter und die unnötige Seitenleiste ausgeblendet.\n- Neue Nachrichten erzwingen nicht mehr das Scrollen nach unten, wenn du gerade ältere Nachrichten liest.\n