<div align="center">

# ♿ AcessoTrip

**Protótipo de Alta Fidelidade para Turismo Acessível**

<br>

Uma plataforma colaborativa que permite a pessoas com deficiência planejar,
avaliar e compartilhar experiências de viagens acessíveis — reduzindo barreiras
e promovendo autonomia desde a concepção do design.

<br>

![Status](https://img.shields.io/badge/status-Protótipo%20Funcional-green?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white)
![WCAG](https://img.shields.io/badge/WCAG-2.1%20AA-005A9C?style=for-the-badge)

</div>

---

## 📚 Tabela de Conteúdos

> Navegue rapidamente pelas seções do projeto.

| # | Seção |
|:-:|:------|
| 1 | [📖 Sobre o Projeto](#-sobre-o-projeto) |
| 2 | [😓 O Problema Central](#-o-problema-central) |
| 3 | [👥 As Personas](#-as-personas-o-coração-do-ux) |
| 4 | [✨ Funcionalidades do Protótipo](#-funcionalidades-do-protótipo) |
| 5 | [🛠️ Stack Tecnológica](#️-stack-tecnológica) |
| 6 | [♿ Foco em Acessibilidade](#-foco-em-acessibilidade-e-inclusão) |
| 7 | [💡 Notas de Arquitetura](#-notas-de-arquitetura-frontend) |
| 8 | [🚀 Como Executar](#-como-executar) |
| 9 | [📂 Estrutura de Pastas](#-estrutura-de-pastas) |
| 10 | [👨‍💻 Autor](#-autor) |
| 11 | [📄 Licença](#-licença) |

---

## 📖 Sobre o Projeto

> **AcessoTrip** nasceu como um **Projeto Final de UX/UI** com o objetivo de resolver um problema real e frustrante: a dificuldade que pessoas com deficiência (PCD) enfrentam ao tentar planejar viagens.

A metodologia utilizada foi o **Design Centrado no Usuário (DCU)**. O projeto não começou pelo código — começou pela investigação e empatia, através da criação de **Personas** e **Jornadas de Usuário**, garantindo que cada decisão de design fosse orientada por uma necessidade real.

O resultado é um **protótipo funcional de alta fidelidade** que simula uma aplicação web responsiva, construída com abordagem **Mobile-First** e adaptação completa para Desktop, com acessibilidade como requisito central desde a sua concepção.

---

## 😓 O Problema Central

> Pessoas com deficiência enfrentam barreiras constantes que sites e apps de turismo convencionais ignoram.

| Barreira | Descrição do Problema |
|:---------|:----------------------|
| 🪜 **Informações Enganosas** | "Rampas falsas" (muito inclinadas ou que terminam em degraus) e banheiros declarados "adaptados" sem espaço real de manobra. |
| 🖥️ **Exclusão Digital** | Sites e apps não compatíveis com leitores de tela, vídeos sem legendas e ausência de interpretação em Libras. |
| 😟 **Falta de Confiança** | O medo de chegar ao destino sem autonomia, dependendo da boa vontade de prestadores de serviço despreparados. |

---

## 👥 As Personas — O Coração do UX

> O design foi guiado por **três personas principais**, cada uma representando um espectro distinto de acessibilidade e orientando diretamente as decisões de interface.

| Persona | Perfil | Dores Principais | Funcionalidade-Chave |
|:--------|:------:|:-----------------|:---------------------|
| 👩‍🦽 **Mariana, 32** | Cadeirante | Rampas falsas, banheiros inadaptados, informação visual enganosa. | Fotos reais e verificadas pela comunidade (na `tela-local`). |
| 👨‍🦯 **Eduardo, 45** | Deficiente Visual | Sites sem rótulos semânticos, incompatíveis com leitores de tela. | Uso correto de tags ARIA e formulários 100% acessíveis (avaliação por estrelas via `radio`). |
| 👩‍🦻 **Ana Luiza, 27** | Deficiente Auditiva | Vídeos sem legendas, guias que falam de costas, falta de comunicação visual. | Abas de acessibilidade (ex: "Auditiva") e foco em comunicação textual (posts, avaliações). |

---

## ✨ Funcionalidades do Protótipo

> O protótipo implementa **5 telas principais** e diversas funcionalidades de acessibilidade e inclusão.

| Tela | Funcionalidades |
|:-----|:----------------|
| 🏠 **Tela Inicial** | Busca por Voz (simulada) e filtros por tipo de deficiência: Física, Visual, Auditiva e Cognitiva. |
| 🏳️‍🌈 **Filtros de Inclusão** | Expansão para necessidades sociais e alimentares: Vegano, Sem Glúten e LGBTQ+ Friendly. |
| 🗺️ **Tela de Resultados (Responsiva)** | **Mobile:** alterna entre Mapa Colaborativo (pins coloridos) e Modo Lista (para leitores de tela). **Desktop:** mapa e lista exibidos lado a lado. |
| 📍 **Tela do Local** | Núcleo da confiança: fotos reais enviadas por usuários, notas de acessibilidade por abas (Física, Visual, etc.) e sistema de avaliação por estrelas 100% acessível. |
| 💬 **Tela de Comunidade** | Feed social de troca de dicas e relatos, criando uma rede de confiança colaborativa entre usuários. |
| 🛠️ **Assistente de Acessibilidade** | Botão flutuante (FAB) com modal de opções: Alto Contraste, Aumentar Fonte e Modo Leitura Simplificada (para necessidades cognitivas). |

---

## 🛠️ Stack Tecnológica

> Tecnologias escolhidas com foco em **prototipagem rápida**, **responsividade** e demonstração de conceitos modernos de frontend acessível.

| Tecnologia | Versão | Propósito e Justificativa |
|:-----------|:------:|:--------------------------|
| **HTML5** | — | Estruturação **semântica** (`<main>`, `<nav>`, `<section>`, `<fieldset>`) — fundamental para acessibilidade e SEO. |
| **CSS3 (Vanilla)** | — | **Mobile-First** com `@media queries` para Tablet e Desktop. **Variáveis CSS** (`:root`) para tematização e funcionalidade de Alto Contraste. |
| **JavaScript ES6+** | — | **Arquitetura SPA** simulada via `aria-hidden`. **Código assíncrono** com `async/await`. **IIFE** para encapsulamento seguro e prevenção de poluição do escopo global. |
| **Mapbox GL JS** | — | Renderização do mapa interativo com personalização de pins e popups por categoria de acessibilidade. |

---

## ♿ Foco em Acessibilidade e Inclusão

> Mais do que uma funcionalidade, a acessibilidade é o **requisito não-funcional principal** do projeto. Diversas técnicas de **WAI-ARIA** e design inclusivo foram aplicadas de forma intencional.

| Tópico | Implementação Técnica | Quem é beneficiado |
|:-------|:----------------------|:-------------------|
| 🎛️ **Controles de Formulário** | O seletor de estrelas (`#star-rating-input`) é um `<fieldset>` com `<input type="radio">` ocultos e `<label>`s estilizados — acessível por teclado e leitores de tela. | 👨‍🦯 **Eduardo** — `div`s e `span`s com JS são inacessíveis. |
| 🏷️ **Semântica e ARIA** | `aria-label` (botões-ícone), `aria-hidden` (gestão de telas), `role="dialog"` e `aria-modal="true"` (assistente de acessibilidade). | 👨‍🦯 **Eduardo** — fornece contexto essencial para leitores de tela na arquitetura SPA. |
| 🎨 **Acessibilidade Adaptativa** | O modal do assistente ativa classes no `<body>`: `.high-contrast`, `.large-font` e `.reading-mode`. | 👨‍🦯 **Eduardo** e usuários com necessidades cognitivas. |
| 🔁 **Navegação Alternativa** | Botão "Modo Lista" na tela de resultados e simulação de Busca por Voz. | 👨‍🦯 **Eduardo** e 👩‍🦽 **Mariana** — alternativas para quem não pode interagir com mapa visual ou tem dificuldade de digitação. |
| 📏 **Alvos de Toque (WCAG)** | Todos os controles interativos possuem `min-width: 44px` e `min-height: 44px`, em conformidade com as diretrizes da **WCAG 2.1**. | 👩‍🦽 **Mariana** e usuários com limitações motoras. |

---

## 💡 Notas de Arquitetura (Frontend)

### 1️⃣ Arquitetura SPA Simulada

O projeto **não recarrega a página**. A função `showScreen()` gerencia o estado de visibilidade das telas alternando `aria-hidden` entre `true` e `false`, garantindo que leitores de tela foquem apenas no conteúdo da tela ativa.

### 2️⃣ API Assíncrona e Robusta

A busca de dados utiliza `async/await` com a função `simularChamadaAPI()`, que retorna uma `Promise` — preparando a arquitetura para substituição por uma API real sem refatoração estrutural.

### 3️⃣ Gestão de Carregamento e Timeout

| Mecanismo | Função |
|:----------|:-------|
| `try...catch...finally` | Garante que `hideLoader()` seja **sempre** executado, mesmo em caso de falha na API. |
| `Promise.race` | Implementa um **timeout de 5 segundos**, evitando que o usuário espere indefinidamente. A simulação retorna em ≈1.2s. |

### 4️⃣ Design Responsivo Híbrido

O CSS não é apenas "mobile". Em telas Desktop, a interface é reorganizada: a barra de navegação inferior transforma-se em menu lateral e o mapa é exibido lado a lado com a lista. O JavaScript detecta essa mudança e ajusta o comportamento do `alternarView()` dinamicamente.

---

## 🚀 Como Executar

> Por ser um protótipo HTML/CSS/JS puro, a execução é simples e não requer instalação de dependências.

### 📋 Pré-requisitos

| Requisito | Detalhe |
|:----------|:--------|
| **Navegador moderno** | Chrome, Firefox, Edge ou Safari (versões recentes). |
| **Git** | Para clonar o repositório. |
| **Live Server** *(opcional)* | Extensão do VS Code recomendada para hot-reload. |

### 🔧 Passo a Passo

**1. Clone o repositório:**

```bash
git clone https://github.com/VictorHJesusSantiago/AcessoTrip.git
cd AcessoTrip
```

**2. Abra o projeto:**

```bash
# Opção A: Direto no navegador
# Clique duplo no arquivo index.html

# Opção B: Via Live Server (VS Code)
# Clique com botão direito em index.html → "Open with Live Server"
```

**3. Acesse o protótipo:**

| Método | Endereço |
|:-------|:---------|
| 🖥️ **Arquivo local** | `file:///caminho/para/AcessoTrip/index.html` |
| 🔴 **Live Server** | `http://localhost:5500` |

> ⚠️ **Nota sobre o Mapbox:** Para o mapa interativo funcionar corretamente, é necessário inserir seu token de API do Mapbox no arquivo `script.js` na variável `mapboxgl.accessToken`.

---

## 📂 Estrutura de Pastas

```plaintext
AcessoTrip/
│
├── 📄 index.html                  # 🏠 Arquivo principal — todas as telas (SPA)
│
├── 📁 css/
│   ├── 📄 style.css               # 🎨 Estilos globais e variáveis CSS (:root)
│   ├── 📄 tela-inicial.css        # Estilos específicos da tela inicial
│   ├── 📄 tela-resultados.css     # Estilos do mapa, lista e responsividade
│   ├── 📄 tela-local.css          # Estilos da ficha do local e abas
│   ├── 📄 tela-comunidade.css     # Estilos do feed social
│   └── 📄 assistente.css          # Estilos do FAB e modal do assistente
│
├── 📁 js/
│   ├── 📄 app.js                  # 🧠 IIFE principal — gestão de telas (SPA)
│   ├── 📄 mapa.js                 # 🗺️  Inicialização e gestão do Mapbox GL JS
│   ├── 📄 api.js                  # 🔌 Simulação de chamadas de API (async/await)
│   └── 📄 assistente.js           # ♿ Lógica do assistente de acessibilidade
│
└── 📁 assets/
    └── 📁 img/                    # 🖼️  Imagens e fotos dos locais (mock)
```

---

## 👨‍💻 Autor

<div align="center">

<br>

**Victor H. J. Santiago**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VictorHJesusSantiago)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-henrique-de-jesus-santiago/)

</div>

---

## 📄 Licença

<div align="center">

Este projeto foi desenvolvido para fins de **estudo e demonstração de conceitos de UX/UI e acessibilidade web**.
Uso livre para fins educacionais, desde que mantida a atribuição ao autor original.

![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

<div align="center">

*Feito com 💙 e acessibilidade por **Victor H. J. Santiago***

</div>
