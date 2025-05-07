# 🔍 OmegleHappy v1.0

## 📋 Description
OmegleHappy est un outil qui vous permet de voir des informations détaillées sur les IPs des personnes avec lesquelles vous vous connectez sur Ome.tv, y compris leur localisation, fuseau horaire et plus encore.

## 🚀 Caractéristiques
- 🌍 Affiche des informations détaillées sur l'IP de l'utilisateur connecté
- 📍 Visualise le pays, la ville et le fuseau horaire
- 📜 Historique des 10 dernières connexions
- 🙈 Option pour censurer l'IP
- 🖱️ Fenêtre déplaçable
- 🔄 Mise à jour en temps réel

## 💻 Comment Utiliser
1. Allez sur [Ome.tv](https://ome.tv)
2. Ouvrez les Outils de Développement (F12 ou clic droit -> Inspecter)
3. Allez dans l'onglet 'Console'
4. Copiez et collez le code suivant :
```javascript
fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt")
    .then(res => res.text())
    .then(code => eval(code));
```

## 🎮 Contrôles
- 📜 Bouton Historique : Affiche/masque les 10 dernières connexions
- 🙈 Bouton Censure : Masque/affiche l'IP actuelle
- – Bouton Réduire : Réduit/agrandit la fenêtre d'information

## ⚠️ Notes
- L'outil ne fonctionne que lorsque la page Ome.tv reste ouverte
- L'historique est sauvegardé localement dans votre navigateur
- Utilisez cet outil de manière responsable et éthique

## 👨‍💻 Créé par
Fait avec 💻 par Jolly