# 🔍 OmegleHappy v1.0

## 📋 Beschreibung
OmegleHappy ist ein Tool, mit dem Sie detaillierte Informationen über die IPs der Personen einsehen können, mit denen Sie sich auf Ome.tv verbinden, einschließlich ihres Standorts, ihrer Zeitzone und mehr.

## 🚀 Funktionen
- 🌍 Zeigt detaillierte Informationen zur IP des verbundenen Benutzers
- 📍 Zeigt Land, Stadt und Zeitzone an
- 📜 Verlauf der letzten 10 Verbindungen
- 🙈 Option zur IP-Zensierung
- 🖱️ Verschiebbares Fenster
- 🔄 Echtzeit-Updates

## 💻 Verwendung
1. Gehen Sie zu [Ome.tv](https://ome.tv)
2. Öffnen Sie die Entwicklertools (F12 oder Rechtsklick -> Untersuchen)
3. Gehen Sie zum 'Konsole' Tab
4. Kopieren und fügen Sie den folgenden Code ein:
```javascript
fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt")
    .then(res => res.text())
    .then(code => eval(code));
```

## 🎮 Steuerung
- 📜 Verlauf-Button: Zeigt/versteckt die letzten 10 Verbindungen
- 🙈 Zensur-Button: Versteckt/zeigt aktuelle IP
- – Minimieren-Button: Verkleinert/erweitert das Informationsfenster

## ⚠️ Hinweise
- Das Tool funktioniert nur, während die Ome.tv-Seite geöffnet ist
- Der Verlauf wird lokal in Ihrem Browser gespeichert
- Verwenden Sie dieses Tool verantwortungsvoll und ethisch

## 👨‍💻 Erstellt von
Entwickelt mit 💻 von Jolly