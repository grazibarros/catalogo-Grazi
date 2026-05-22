# UI/UX Template Design Tokens and Layout Guide

Este arquivo contém todas as especificações técnicas necessárias para que um engenheiro UI/UX possa replicar o template apresentado de forma pixel-perfect.

---

## 1. Design System Setup

### Checklist de Preparação

* Local style ready
* 12 Column desktop grid
* Well organized layer

### Cores (Color Palette)

| Nome         | Hex     | Uso                                   |
| ------------ | ------- | ------------------------------------- |
| Preto Escuro | #262626 | Texto principal, títulos              |
| Cinza Médio  | #525252 | Texto secundário, subtítulos          |
| Azul Escuro  | #143D4B | Footer, fundo de seções de destaque   |
| Azul Claro   | #94CCDF | Botões, highlights, CTA               |
| Branco       | #FFFFFF | Fundo principal, contraste com textos |

### Tipografia (Fonts)

| Tipo de Texto | Fonte            | Uso                        |
| ------------- | ---------------- | -------------------------- |
| Headings      | Playfair Display | Títulos principais H1-H3   |
| Main Text     | Manrope          | Corpo do texto, descrições |

### Grid e Layout

* Sistema de 12 colunas para desktop.
* Espaçamento consistente entre colunas e linhas.
* Layers nomeados semanticamente (`Header`, `Hero`, `CTA`, `Footer`, etc).

---

## 2. Template de Página

### Header

* Logo: canto esquerdo.
* Menu horizontal: canto direito (`Home`, `About Us`, `Product`, `Contact`).
* Fundo: Azul muito claro ou transparente.

### Hero Section

* Título: `Experience the Artistry of Makeup` (Playfair Display, 48px).
* Subtítulo abaixo do título (Manrope, 16px).
* CTA Button: `Order Now`, fundo `#94CCDF`, texto branco, borda arredondada 8px, hover com leve sombra.
* Imagem principal à direita (modelo ou produto).
* Elementos decorativos: símbolos `+` ou círculos pequenos, distribuídos.

### Produtos Destacados (Best Product)

* Layout: horizontal, 2-3 colunas.
* Cards: imagem do produto, nome, preço.
* Fundo: branco, sombra sutil (`box-shadow: 0 2px 6px rgba(0,0,0,0.1)`).
* CTA: `Buy Now`, azul claro com hover.

### Seção de Experiência / Destaques

* Cards informativos:

  * `15+ Years of Experience`
  * `5K Original Beauty Products`
  * `10K+ Happy Clients`
* Fundo azul claro `#94CCDF`, texto preto `#262626`.
* Títulos: Playfair Display, corpo: Manrope.

### Vídeo / Diferenciais

* Layout: imagem/vídeo à esquerda, título à direita.
* Título: `What Makes us Different From Others`.
* CTA: `Order Now`, fundo azul claro.
* Fundo: azul escuro `#143D4B` ou overlay escuro translúcido.

### QnA / FAQ

* Accordion vertical.
* Fundo: branco ou azul muito claro.

### Testemunhos de Clientes

* Cards: foto do cliente, nome, avaliação em estrelas.
* Fundo branco, borda sutil, sombra leve.

### Newsletter / Call to Action

* Input email + botão `Subscribe`.
* Fundo azul claro `#94CCDF`, texto preto.
* Centralizado horizontalmente.

### Footer

* Fundo azul escuro `#143D4B`, texto branco.
* Seções:

  * Quick links
  * Contato
  * Mídias sociais (ícones circulares)

---

## 3. Elementos Visuais e Estilo

* Bordas arredondadas: 6-12px.
* Sombra leve nos cards: `box-shadow: 0 2px 6px rgba(0,0,0,0.1)`.
* Espaçamento vertical entre seções: 40-60px.
* Imagens circulares para elementos de destaque e avatares.
* Pequenos elementos decorativos geométricos (`+`, círculos).

## 4. Tipografia e Hierarquia

* **H1:** 48px (Playfair Display, negrito)
* **H2:** 36px
* **H3:** 28px
* **Body:** 16px (Manrope, regular)
* **Botões:** 14-16px (Manrope, semi-bold)

## 5. Cores Aplicadas por Seção

| Seção                   | Fundo   | Texto   | Elementos/CTA   |
| ----------------------- | ------- | ------- | --------------- |
| Header                  | #FFFFFF | #262626 | -               |
| Hero                    | #FFFFFF | #262626 | #94CCDF (CTA)   |
| Produtos Destacados     | #FFFFFF | #262626 | #94CCDF (CTA)   |
| Destaques / Experiência | #94CCDF | #262626 | -               |
| Vídeo / Diferenciais    | #143D4B | #FFFFFF | #94CCDF (CTA)   |
| QnA / FAQ               | #FFFFFF | #262626 | -               |
| Testemunhos             | #FFFFFF | #262626 | -               |
| Newsletter              | #94CCDF | #262626 | #FFFFFF (botão) |
| Footer                  | #143D4B | #FFFFFF | -               |

---

Este documento fornece todos os valores de cores, fontes, tamanhos, espaçamentos e bordas necessários para replicar o template **pixel-perfect** em HTML/CSS ou Figma/Sketch.

