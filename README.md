# Lobby-System für Minecraft Server ⚡

Willkommen zu unserem praktischen **Minecraft Lobby-System**! 🎮  
Dieses Skript bietet eine vollständig anpassbare Lobby-Umgebung für deinen Server. Du kannst die Lobby-Position, das Scoreboard und viele weitere Features direkt über eine **`config.yml`** konfigurieren. 🛠️

## Features 🚀
- **Lobby-Wechsel** 🏃‍♂️: Wechsel zwischen verschiedenen Lobbys per Item (z.B. Enderperle).
- **Unsichtbarkeit** 👻: Mache dich unsichtbar mit einem Item.
- **Scoreboard** 📊: Zeigt wichtige Infos wie:
  - Anzahl der Online-Spieler
  - Spieler-Rang (mit Plugins wie LuckPerms)
  - Lobby-Welt
- **Blockabbau verhindern** 🚫: Spieler können keine Blöcke abbauen.
- **PvP verhindern** 🛡️: Kein Schlagen in der Lobby.
- **Willkommensnachricht** 👋: Eine freundliche Nachricht beim Betreten des Servers.
  
## Installation ⚙️
1. Lade das Skript herunter und platziere es im `plugins/Script`-Ordner deines Servers.
2. Passe die `config.yml` an, um die Lobby-Optionen zu konfigurieren:
    - Welt, Koordinaten, Nachrichten und mehr.
3. Starte deinen Server neu, um das Skript zu aktivieren. 💥

## Konfiguration 📝
Die **`config.yml`** bietet dir alle Einstellungen zur Anpassung des Lobby-Systems. Du kannst die Lobby-Welt, die Koordinaten und viele andere Optionen nach deinen Wünschen ändern. 💡

```yaml
# Beispiel eines Konfigurationsabschnitts
lobby:
  world: "world"
  x: 0
  y: 64
  z: 0
  welcome-message: "Willkommen, %player%! Viel Spaß in der Lobby!"
