# Midvash

> 🌐 [English](./README.md) · **Português (BR)** · [Español](./README.es.md)

**Devocional diário com profundidade de estudo bíblico — leia, busque, estude e construa.**

🌐 **[midvash.com](https://midvash.com)** — o leitor · 🔌 **[api.midvash.com](https://api.midvash.com)** — a API pública

---

## O que construímos

A Midvash é um devocional diário com profundidade de estudo bíblico, na web,
no iOS e no Android. Mais de 100 traduções de licença livre em mais de 60
idiomas são servidas por uma API pública gratuita, um leitor web caprichado em 9 idiomas
de interface com busca em texto completo, estudo assistido por IA, leituras
diárias, referências cruzadas, perfis de personagens bíblicos, comentários
e um dicionário de teologia bíblica. O texto bíblico e o devocional diário são
grátis para todos; a conversa com a IA faz parte do Midvash Pro.

## Produtos

| | Produto | Onde |
|---|---|---|
| 📖 | **Leitor bíblico** — leia, busque, estude | [midvash.com](https://midvash.com) |
| 🔌 | **Bible API** — pública, gratuita, sem chave de API, 100+ versões livres | [api.midvash.com](https://api.midvash.com) |
| 🤖 | **Bible MCP** — servidor Model Context Protocol para LLMs | [mcp.midvash.com](https://mcp.midvash.com) |
| 🧩 | **Plugin WordPress** — autolinka referências bíblicas | [midvash.com/wordpress-plugin](https://midvash.com/wordpress-plugin) |
| 🧩 | **Extensão Chrome** — Bible Links em qualquer lugar da web | [midvash.com/chrome-extension](https://midvash.com/chrome-extension) |
| 🍎 | **App iOS** | [App Store](https://apps.apple.com/app/id6775930176) |
| 🤖 | **App Android** | [Google Play](https://play.google.com/store/apps/details?id=com.midvash.mobile) |

## Projetos open-source

| Repo | O quê |
|------|------|
| **[bible-api](https://github.com/midvash/bible-api)** | API bíblica pública, gratuita e sem chave — versículos, capítulos e versões em mais de 100 traduções bíblicas de licença livre, em mais de 60 idiomas. Move a api.midvash.com. |
| **[bible-mcp](https://github.com/midvash/bible-mcp)** | Servidor MCP gratuito e sem chave para a API bíblica pública — Escrituras para LLMs a partir de qualquer cliente MCP. Move a mcp.midvash.com. |
| **[bible-data](https://github.com/midvash/bible-data)** | Mais de 30 versões bíblicas de domínio público em mais de 20 idiomas, JSON + SQLite, codificadas em OSIS. O conjunto de dados que move nosso leitor. |
| **[bible-data-js](https://github.com/midvash/bible-data-js)** | SDK TypeScript para o conjunto de dados acima. `npm install @midvash/bible-data`. |
| **[bible-cross-references](https://github.com/midvash/bible-cross-references)** | 453 referências cruzadas temáticas curadas, rótulos multilíngues (en, pt, es). |
| **[bible-wordpress-plugin](https://github.com/midvash/bible-wordpress-plugin)** | Plugin WordPress: detecta automaticamente referências bíblicas nos posts e adiciona links com tooltip ao passar o mouse. |
| **[bible-emdash-plugin](https://github.com/midvash/bible-emdash-plugin)** | Plugin do CMS EmDash: autolinka referências bíblicas com tooltips ao passar o mouse. Movido pela API pública da Midvash. |
| **[bible-chrome-extension](https://github.com/midvash/bible-chrome-extension)** | Extensão Chrome que detecta referências bíblicas em qualquer página da web e as linka com um tooltip de pré-visualização ao passar o mouse. |

Tem mais por vir — publicamos as partes da nossa stack que são úteis para outros projetos (datasets, schemas, bibliotecas).

## Idiomas que suportamos

🇺🇸 English · 🇧🇷 Português · 🇪🇸 Español · 🇩🇪 Deutsch · 🇫🇷 Français · 🇮🇹 Italiano · 🇨🇳 中文 · 🇷🇺 Русский · 🇰🇷 한국어

*(A própria API serve conteúdo bíblico em mais de 60 idiomas — estes 9 são os
idiomas para os quais a interface do leitor está totalmente traduzida.)*

## Fale com a gente

- **Use o leitor**: [midvash.com](https://midvash.com)
- **Construa com a API**: [api.midvash.com](https://api.midvash.com)
- **Reporte um problema de conteúdo**: [midvash.com/feedback](https://midvash.com/feedback)
- **E-mail**: contact@midvash.com

## O ecossistema Midvash

Faz parte do [**Midvash**](https://midvash.com) — um devocional diário com profundidade de estudo bíblico. Tudo é aberto e se interliga:

| | |
|---|---|
| 📖 **Leitor (web)** | [midvash.com](https://midvash.com) — 9 idiomas |
| 📱 **App iOS** | [App Store](https://apps.apple.com/app/id6775930176) |
| 📱 **App Android** | [Google Play](https://play.google.com/store/apps/details?id=com.midvash.mobile) |
| 🔌 **API** | [api.midvash.com](https://api.midvash.com) · [`bible-api`](https://github.com/midvash/bible-api) |
| 🤖 **Servidor MCP** | [mcp.midvash.com](https://mcp.midvash.com) · [`bible-mcp`](https://github.com/midvash/bible-mcp) |
| 🧩 **Plugin WordPress** | [midvash.com/wordpress-plugin](https://midvash.com/wordpress-plugin) · [`bible-wordpress-plugin`](https://github.com/midvash/bible-wordpress-plugin) |
| 🧩 **Plugin EmDash** | [midvash.com/emdash-plugin](https://midvash.com/emdash-plugin) · [`bible-emdash-plugin`](https://github.com/midvash/bible-emdash-plugin) |
| 🌐 **Extensão Chrome** | [midvash.com/chrome-extension](https://midvash.com/chrome-extension) · [`bible-chrome-extension`](https://github.com/midvash/bible-chrome-extension) |
| 📦 **Dados abertos** | [`bible-data`](https://github.com/midvash/bible-data) · [`bible-data-js`](https://github.com/midvash/bible-data-js) · [`bible-cross-references`](https://github.com/midvash/bible-cross-references) |

<sub>Gratuito e aberto, feito pela [Midvash](https://midvash.com) · [midvash.com](https://midvash.com)</sub>
