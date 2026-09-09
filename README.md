# Achadinhos Mais — Link na Bio

Página única (estilo Linktree) para centralizar os links do **Achadinhos Mais**: canal do WhatsApp, Instagram, vitrine de afiliado e X.

🔗 **Preview:** https://claude.ai/code/artifact/f05c3ad6-ad2d-4742-8ae4-230a1bd11540

## Sobre

- Arquivo único (`index.html`), sem frameworks, sem build — HTML5 + CSS puro.
- Ícones em SVG inline (WhatsApp, Instagram, sacola, X) — carregamento rápido, zero dependências externas.
- Visual dark mode com acentos em degradê teal/dourado, no estilo da identidade visual do perfil.
- Totalmente responsivo (mobile-first).

## Como editar

Abra o `index.html` em qualquer editor de texto.

- **Links:** procure os comentários `<!-- COLE AQUI O LINK DO ... -->` e troque a URL dentro de `href="..."`.
- **Cores:** todas as cores ficam centralizadas no topo do arquivo, dentro do bloco `:root { ... }` no `<style>`.
- **Avatar/logo:** a imagem já está embutida no próprio HTML (como `data:image/jpeg;base64,...` na tag `<img class="avatar">`). Para trocar, basta substituir o `src` por outra imagem (embutida da mesma forma, ou um link/caminho para outro arquivo).

## Como publicar (GitHub Pages)

1. Vá em **Settings → Pages** neste repositório.
2. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
3. Salve. Em alguns minutos o site fica disponível em `https://matheusmontagner8.github.io/achadinhos-linktree/`.

---

Criado com apoio do Claude Code.
