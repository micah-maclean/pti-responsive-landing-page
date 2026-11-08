## 🎯 Objetivo do Projeto

Construir uma landing page responsiva de página única (*single-page*).

A página foi estruturada em seções:
1. **Hero Section:** Proposta de valor clara e CTA com seta animada (*jiggle*).
2. **Metodologia:** Divisão modular em cards dos programas de treino e consultoria.
3. **Vantagens & Benefícios:** Layout em duas colunas com lista de diferenciais.
4. **Resultados (Depoimentos):** Avaliações de clientes reais, estrelas e métricas de impacto.
5. **Contato & Diagnóstico:** Bloco amplo com canais diretos (WhatsApp, e-mail, studio presencial) e formulário completo para captação de dados do lead.

---

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`).
- **CSS3 Puro:**
  - Variáveis CSS (`:root`) para consistência de cores e espaçamentos.
  - CSS Flexbox
  - Animações CSS com `@keyframes` (efeito *jiggle* na seta de rolagem).
  - Tipografia web com *Google Fonts* (`Inter` e `Merriweather`).
  - Efeitos modernos com *backdrop-filter* (efeito de vidro no cabeçalho).
- **Sem Frameworks:** Nenhum framework externo (como Bootstrap ou Tailwind) foi utilizado.

---

## 📱 Responsividade e Breakpoints

A página foi construída seguindo uma abordagem *desktop-first* com adaptação fluida para dispositivos móveis através de Media Queries integradas:

| **> 950px** | **≤ 950px** | **≤ 768px**  | **≤ 600px**   |

---

## 📂 Estrutura de Arquivos

```text
├── index.html       # Estrutura HTML5 semântica da landing page
├── style.css        # Folha de estilos CSS3 com Flexbox, variáveis e media queries
└── README.md        # Documentação completa do projeto
```

---

## ⚡ Como Executar o Projeto Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/personal-trainer-landing-page.git
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd personal-trainer-landing-page
   ```

3. **Abra no navegador:**
   - Dê um duplo clique no arquivo `index.html`, ou
   - Use uma extensão como o **Live Server** no VS Code para recarregamento em tempo real.

---