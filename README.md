# 🔍 OmegleHappy v3.0

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/JollyJolli/omeglehappy)

## 🌎 Languages
[🇪🇸 Español](README.md) • [🇬🇧 English](READMEs/README.en.md) • [🇫🇷 Français](READMEs/README.fr.md) • [🇩🇪 Deutsch](READMEs/README.de.md) • [🇵🇹 Português](READMEs/README.pt.md)

## 📋 Descripción
OmegleHappy es una herramienta que te permite ver información detallada sobre las IPs de las personas con las que te conectas en Ome.tv, incluyendo su ubicación, zona horaria y más.

## 🚀 Características
- 🌍 Muestra información detallada de la IP del usuario conectado
- 📍 Visualiza país, ciudad y zona horaria
- 📜 Historial de las últimas 10 conexiones
- 🙈 Opción para censurar la IP
- 🖱️ Ventana arrastrable
- 🔄 Actualización en tiempo real
- 📹 Soporte para cambiar cámara y micrófono (script adicional)

## 💻 Cómo Usar
1. Ve a [Ome.tv](https://ome.tv)
2. Abre las Herramientas de Desarrollo (F12 o clic derecho -> Inspeccionar)
3. Ve a la pestaña 'Consola'
4. Copia y pega el siguiente código:
```javascript
fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt")
    .then(res => res.text())
    .then(code => eval(code));
```

## 📹 Cambiar Cámara/Micrófono (OBS Virtual Camera)
Para usar una cámara virtual de OBS u otra cámara/micrófono:
1. Abre las Herramientas de Desarrollo
2. Ve a la pestaña 'Consola'
3. Copia y pega el código del archivo `code-to-use-OBS-cam.txt` (creado por [robiot](https://github.com/robiot) en GitHub, [código original aquí](https://gist.github.com/robiot/fb05b6528a76ec1142842913b5eca38a))
4. Aparecerá un selector sobre tu video para cambiar la cámara y el micrófono

## 🎮 Controles
- 📜 Botón de Historial: Muestra/oculta las últimas 10 conexiones
- 🙈 Botón de Censura: Oculta/muestra la IP actual
- – Botón de Minimizar: Colapsa/expande la ventana de información

## 📌 Método Alternativo (Marcador)
1. Crea un nuevo marcador en tu navegador
2. Como nombre, pon "OmegleHappy"
3. Como URL, copia y pega el siguiente código:
```javascript
javascript:fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt").then(r=>r.text()).then(c=>eval(c))
```
4. Ve a [Ome.tv](https://ome.tv)
5. Haz clic en el marcador para activar OmegleHappy

## ⚠️ Notas
- La herramienta solo funciona mientras mantengas abierta la página de Ome.tv
- El historial se guarda localmente en tu navegador
- Usa esta herramienta de manera responsable y ética
- El método del marcador es una forma más rápida de activar la herramienta

## 👨‍💻 Creado por
Hecho con 💻 por Jolly
