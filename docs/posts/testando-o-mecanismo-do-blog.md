---
slug: testando-o-mecanismo-do-blog
date: 2025-02-28
title_pt: "Testando o mecanismo do blog"
title_en: "Testing the blog mechanism"
tags: ["blog", "teste", "tutorial"]
---

## PT
Este post serve para você **visualizar** como o blog está funcionando e avaliar a página.

### O que você pode usar no texto

- **Negrito** e *itálico*
- Listas numeradas e com marcadores
- [Links externos](https://github.com/andferr)
- Blocos de código

Exemplo de código:

```javascript
function saudacao(idioma) {
  return idioma === 'pt' ? 'Olá!' : 'Hello!';
}
```

O seletor **PT / EN** no topo da página alterna o idioma. A preferência é guardada no navegador.

### Como testar localmente

Se estiver abrindo os arquivos direto do disco, use um servidor local (ex.: `npx serve docs`) para que o `fetch` dos arquivos `.md` e do `list.json` funcione corretamente.

## EN
This post lets you **see** how the blog is working and evaluate the page.

### What you can use in the text

- **Bold** and *italic*
- Numbered and bullet lists
- [External links](https://github.com/andferr)
- Code blocks

Code example:

```javascript
function greeting(lang) {
  return lang === 'pt' ? 'Olá!' : 'Hello!';
}
```

The **PT / EN** selector at the top switches the language. The preference is stored in the browser.

### How to test locally

If you're opening files directly from disk, use a local server (e.g. `npx serve docs`) so that fetching the `.md` files and `list.json` works correctly.
