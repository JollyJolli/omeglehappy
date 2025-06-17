# 🔍 OmegleHappy v3.0

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

## 📹 Kamera/Mikrofon wechseln (OBS Virtual Camera)
Um eine OBS-Virtualkamera oder eine andere Kamera/Mikrofon zu verwenden:
1. Öffnen Sie die Entwicklertools
2. Gehen Sie zum 'Console' Tab
3. Kopieren und fügen Sie den Code aus der Datei `code-to-use-OBS-cam.txt` ein (erstellt von [robiot](https://github.com/robiot) auf GitHub, [originaler Code hier](https://gist.github.com/robiot/fb05b6528a76ec1142842913b5eca38a))
4. Ein Auswahlfeld erscheint über Ihrem Video, um Kamera und Mikrofon zu wechseln

## 🎮 Steuerung
- 📜 Verlauf-Button: Zeigt/versteckt die letzten 10 Verbindungen
- 🙈 Zensur-Button: Versteckt/zeigt die aktuelle IP
- – Minimieren-Button: Reduziert/erweitert das Informationsfenster

## 📌 Alternative Methode (Lesezeichen)
1. Erstellen Sie ein neues Lesezeichen in Ihrem Browser
2. Setzen Sie "OmegleHappy" als Namen
3. Kopieren Sie als URL den folgenden Code:
```javascript
javascript:fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt").then(r=>r.text()).then(c=>eval(c))
```
4. Gehen Sie zu [Ome.tv](https://ome.tv)
5. Klicken Sie auf das Lesezeichen, um OmegleHappy zu aktivieren

## ⚠️ Hinweise
- Das Tool funktioniert nur, während die Ome.tv-Seite geöffnet ist
- Der Verlauf wird lokal in Ihrem Browser gespeichert
- Verwenden Sie dieses Tool verantwortungsvoll und ethisch
- Die Lesezeichen-Methode ist eine schnellere Möglichkeit, das Tool zu aktivieren

## 👨‍💻 Erstellt von
Gemacht mit 💻 von Jolly