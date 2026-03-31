# ⚔ DevOps Quest — Study RPG

> **Gamifique seu aprendizado de DevOps.** Registre sessões de estudo, suba de rank, conquiste emblemas, acompanhe blueprints e visualize sua evolução com gráficos — tudo no navegador, sem backend.

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Status](https://img.shields.io/badge/status-active-00ff88?style=for-the-badge)

</div>

---

## 📸 Preview

```
⚔ DEVOPS QUEST ⚔
╔══════════════════════════════════════════╗
║  🗺 MAPA DO HERÓI     🔥 0 DIAS STREAK  ║
║  ┌─────────┬────────┬──────────┬───────┐ ║
║  │ HOJE    │ SEMANA │ MÊS      │ XP    │ ║
║  │  2.5h   │ 14h    │  48h     │ 3200  │ ║
║  └─────────┴────────┴──────────┴───────┘ ║
║  [RANK: GOLD I ████████░░ 72%]           ║
╚══════════════════════════════════════════╝
```

---

## ✨ Funcionalidades

| Feature | Descrição |
|---------|-----------|
| ⚔ **Registro de Missões** | Registre sessões com tecnologia, duração, tipo e dificuldade |
| ⏳ **Timer de Combate** | Cronômetro e modo Pomodoro com XP ao vivo |
| 📊 **Stats & Gráficos** | Diário, semanal, mensal, heatmap, por tecnologia e XP cumulativo |
| 👑 **Sistema de Ranks** | 9 ranks (Ferro → Challenger) baseados em XP acumulado |
| 🏆 **Emblemas** | Mais de 80 conquistas desbloqueáveis por categorias e raridades |
| 🗺 **Blueprints** | Roteiros de estudo para 12 tecnologias DevOps com checklists |
| ⚡ **Skill Tree** | Níveis 1–20 por tecnologia baseados em horas de estudo |
| 📜 **Certificações** | Catálogo de 50+ certs (AWS, Azure, GCP, CKA, Terraform...) |
| 💾 **Save/Load** | Export e import via arquivo `.json` — dados no `localStorage` |
| 🎨 **Pixel Art UI** | Tema RPG com matrix rain, cursor trail, confetti e animações |

---

## 🗂 Estrutura do Projeto

```
Estudo-Progresso-DevOps/
├── index.html          # Estrutura HTML (markup puro)
├── assets/
│   ├── css/
│   │   └── style.css   # Estilos, animações, responsividade
│   └── js/
│       └── app.js      # Toda a lógica da aplicação
└── README.md
```

---

## 🚀 Como usar

### Localmente
Basta abrir o `index.html` diretamente no navegador — não requer servidor.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/Estudo-Progresso-DevOps.git

# Abra no browser
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

### Deploy (GitHub Pages, Netlify, Vercel)
Como é um projeto estático, faça upload dos arquivos manualmente ou conecte o repositório diretamente — funciona sem nenhuma configuração extra.

```bash
# GitHub Pages — comando via gh CLI
gh repo create Estudo-Progresso-DevOps --public --source=. --push
# Depois: Settings → Pages → Branch: main
```

---

## 🎮 Sistemas do Jogo

### 🏆 Ranks
```
🥉 Ferro      →  Bronze  →  Prata  →  Ouro
💎 Platina    →  Diamante  →  Mestre
👑 Grão-Mestre  →  CHALLENGER
```

### ⭐ XP por sessão
- **Base:** 1 XP por minuto
- **Multiplicadores por tipo:** Lab/Simulado `×1.5` · Projeto `×1.3` · Revisão `×0.8`
- **Multiplicadores por dificuldade:** Médio `×1.5` · Difícil `×2.0`
- **Eventos:** Pomodoro `+50 XP` · Certificado `+500 XP`

### 🗺 Blueprints disponíveis
Linux · Docker · Kubernetes · Terraform · AWS · Azure · CI/CD · DevSecOps · Observability · Networking · Git · Python DevOps

---

## 🛠 Stack Técnica

| Tecnologia | Uso |
|-----------|-----|
| HTML5 semântico | Estrutura do app |
| CSS3 Vanilla | Estilos, variáveis, keyframes, responsividade |
| JavaScript ES6+ | Lógica, storage, rendering |
| [Chart.js 4.4](https://www.chartjs.org/) | Gráficos interativos |
| Google Fonts | `Press Start 2P` (pixel font) |
| localStorage | Persistência de dados |

> **Zero dependências de build.** Sem Node.js, sem bundler, sem framework. Abre e funciona.

---

## 💾 Dados & Privacidade

Todos os dados ficam **100% no seu navegador** via `localStorage` (chave: `devops_quest_v1`). Nenhuma informação é enviada a servidores externos.

Para **backup**, use o botão **⚙ SAVE → Exportar Save** que gera um arquivo `.json` local.

---

## 🤝 Contribuindo

Pull requests são bem-vindos! Para mudanças maiores, abra uma issue primeiro descrevendo o que você quer mudar.

```bash
git checkout -b feature/nova-funcionalidade
git commit -m "feat: adiciona nova funcionalidade"
git push origin feature/nova-funcionalidade
```

---

## 📄 Licença

MIT © 2025 — Feito com ☕ e muito estudo DevOps.

<div align="center">
  <sub>Construído com IA · Desenvolvido para quem estuda de verdade 🚀</sub>
</div>
