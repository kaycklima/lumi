# 💡 Mascote Lumi — Assistente Virtual Interativo

<div align="center">

**Um mascote assistente virtual interativo com 14 estados emocionais, eye tracking, drag & drop com física e console REPL — 100% vanilla JS + CSS puro.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kayck%20Lima-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kayck-lima/)
[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-222?style=for-the-badge&logo=github&logoColor=white)](#-demo)

</div>

---

## ✨ Sobre o Projeto

O **Lumi** é um mascote virtual interativo criado como projeto de portfólio. Ele foi construído em um **único arquivo HTML** sem frameworks — utilizando apenas HTML semântico, CSS avançado e JavaScript vanilla.

O mascote reage ao cursor, reconhece padrões de clique, dorme quando ocioso, fala frases motivacionais e pode ser arrastado com física realista. Tudo renderizado em tempo real com `requestAnimationFrame`.

## 🎯 Features

| Feature | Descrição |
|---|---|
| 🎭 **14 Emoções** | Happy, Sad, Angry, Dizzy, Love, Shocked, Laughing, Sleeping, Privacy, Curious, Disappointed, Indignant, Mindblown e Normal |
| 👁️ **Eye Tracking** | As pupilas seguem o cursor do mouse em tempo real |
| 🖱️ **Drag & Drop** | Arraste o Lumi e veja-o ficar tonto ao soltar (spring-back com física) |
| ⚡ **Detecção de Cliques** | 4 cliques rápidos = modo irritado |
| 💤 **Idle Detection** | Dorme após 12 segundos sem interação |
| 🌱 **Frases Motivacionais** | Ciclo automático a cada 30s (configurável) |
| 💬 **Balão de Fala** | Envie mensagens personalizadas para o Lumi |
| 🎨 **5 Temas de Cor** | Sapphire, Rose, Violet, Emerald, Amber |
| 🌗 **Light / Dark Mode** | Alternância completa com ~360 linhas de CSS |
| 🖥️ **Showcase Mode** | Tela cheia imersiva para apresentações |
| 💻 **Console REPL** | Execute JavaScript diretamente na página |
| ♿ **Acessibilidade** | Navegação por teclado, `aria-live`, `focus-visible` |
| 📱 **Responsivo** | Adaptado para desktop e mobile |

## 🚀 Como Usar

### Visualizar Localmente

Basta abrir o arquivo `index.html` no navegador:

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/Lumi.git

# Abra no navegador
open Lumi/index.html
```

### GitHub Pages

Este projeto está pronto para deploy via GitHub Pages:

1. Vá em **Settings** → **Pages** no repositório
2. Em **Source**, selecione **Deploy from a branch**
3. Escolha a branch `main` e a pasta `/ (root)`
4. Clique em **Save**

O site estará disponível em `https://SEU-USUARIO.github.io/Lumi/`

## 🛠️ Tecnologias

- **HTML5** — Markup semântico com atributos ARIA
- **CSS3** — Animações, keyframes, gradients, custom properties, media queries
- **JavaScript ES6+** — Classes, Pointer Events API, requestAnimationFrame
- **Tailwind CSS** — Via CDN (configuração runtime)
- **Google Fonts** — Plus Jakarta Sans + JetBrains Mono

> **Zero dependências de build.** Sem Node.js, sem bundlers, sem frameworks. Apenas um arquivo HTML.

## 🎮 Comandos do Console

O Lumi possui um console interativo integrado. Experimente:

```javascript
lumi.setMood('love')           // Muda para modo apaixonado
lumi.celebrate()               // Comemoração com confetes
lumi.shake()                   // Balança a cabeça (erro)
lumi.say('Olá!', '👋', 3000)  // Faz o Lumi falar
lumi.speakMotivationalQuote()  // Frase motivacional
toggleThemeMode()              // Alterna claro/escuro
toggleShowcaseMode(true)       // Modo apresentação
```

## 📁 Estrutura

```
/
├── index.html    ← Aplicação completa (single file)
├── README.md     ← Este arquivo
└── LICENSE        ← Licença MIT
```

## 👨‍💻 Autor

**Kayck Lima** — Desenvolvedor de Sistemas | Estudante de Análise e Desenvolvimento de Sistemas

Atuo no desenvolvimento de sistemas empresariais e projetos web. O Lumi é um dos meus projetos pessoais para demonstrar habilidades de frontend interativo.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kayck%20Lima-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kayck-lima/)

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
