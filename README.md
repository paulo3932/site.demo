# ✦ Nexus Digital

![Status](https://img.shields.io/badge/status-live-success)
![Acessibilidade](https://img.shields.io/badge/a11y-WCAG_2.1_AA-blue)
![Vercel](https://img.shields.io/badge/deploy-Vercel-black)

> Landing page com acessibilidade integrada, tema escuro, alto contraste e navegação SPA.

---

## 🚀 Demo

[https://nexus-digital.vercel.app](https://nexus-digital.vercel.app)

---

## 📁 Estrutura

---

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript ES6
- Font Awesome 6
- Google Fonts (Inter)
- Vercel (hospedagem)

---

## ♿ Recursos de Acessibilidade

| Recurso | Como usar |
|---------|-----------|
| Tema escuro/claro | Botão no cabeçalho |
| Alto contraste | Botão com ícone de ajuste |
| Aumentar fonte | Botão com ícone de texto |
| Destaque de foco | Botão com ícone de teclado |
| Navegação por teclado | Tecla `TAB` |

---

## 🔧 Execução Local

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nexus-digital.git

# Acesse a pasta
cd nexus-digital

# Abra no navegador
start index.html   # Windows
open index.html    # macOS

# Instalar CLI
npm install -g vercel

# Fazer deploy
vercel --prod
{
  "routes": [
    { "handle": "filesystem" },
    { "src": "/.*", "dest": "/index.html" }
  ]
}


