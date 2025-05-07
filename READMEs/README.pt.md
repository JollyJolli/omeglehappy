# 🔍 OmegleHappy v1.0

## 📋 Descrição
OmegleHappy é uma ferramenta que permite visualizar informações detalhadas sobre os IPs das pessoas com quem você se conecta no Ome.tv, incluindo sua localização, fuso horário e mais.

## 🚀 Características
- 🌍 Mostra informações detalhadas do IP do usuário conectado
- 📍 Visualiza país, cidade e fuso horário
- 📜 Histórico das últimas 10 conexões
- 🙈 Opção para censurar o IP
- 🖱️ Janela arrastável
- 🔄 Atualização em tempo real

## 💻 Como Usar
1. Vá para [Ome.tv](https://ome.tv)
2. Abra as Ferramentas de Desenvolvedor (F12 ou clique direito -> Inspecionar)
3. Vá para a aba 'Console'
4. Copie e cole o seguinte código:
```javascript
fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt")
    .then(res => res.text())
    .then(code => eval(code));
```

## 🎮 Controles
- 📜 Botão de Histórico: Mostra/oculta as últimas 10 conexões
- 🙈 Botão de Censura: Oculta/mostra o IP atual
- – Botão de Minimizar: Recolhe/expande a janela de informações

## ⚠️ Notas
- A ferramenta só funciona enquanto mantiver a página do Ome.tv aberta
- O histórico é salvo localmente no seu navegador
- Use esta ferramenta de forma responsável e ética

## 👨‍💻 Criado por
Feito com 💻 por Jolly