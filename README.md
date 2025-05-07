# 🔍 OmegleHappy v1.0

| Language | Flag |
|----------|------|
| Español 🇪🇸 | [README.md](README.md) |
| English 🇬🇧 | [README.en.md](READMEs/README.en.md) |
| Français 🇫🇷 | [README.fr.md](READMEs/README.fr.md) |
| Deutsch 🇩🇪 | [README.de.md](READMEs/README.de.md) |
| Português 🇵🇹 | [README.pt.md](READMEs/README.pt.md) |

## 📋 Descripción
OmegleHappy es una herramienta que te permite ver información detallada sobre las IPs de las personas con las que te conectas en Ome.tv, incluyendo su ubicación, zona horaria y más.

## 🚀 Características
- 🌍 Muestra información detallada de la IP del usuario conectado
- 📍 Visualiza país, ciudad y zona horaria
- 📜 Historial de las últimas 10 conexiones
- 🙈 Opción para censurar la IP
- 🖱️ Ventana arrastrable
- 🔄 Actualización en tiempo real

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

## 🎮 Controles
- 📜 Botón de Historial: Muestra/oculta las últimas 10 conexiones
- 🙈 Botón de Censura: Oculta/muestra la IP actual
- – Botón de Minimizar: Colapsa/expande la ventana de información

## ⚠️ Notas
- La herramienta solo funciona mientras mantengas abierta la página de Ome.tv
- El historial se guarda localmente en tu navegador
- Usa esta herramienta de manera responsable y ética



## 👨‍💻 Creado por
Hecho con 💻 por Jolly