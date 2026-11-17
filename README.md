# Achadinhos Mais

Página de links do **Achadinhos Mais**: reúne a vitrine de ofertas, o canal do WhatsApp, o Instagram e o X em um só endereço, pensada para a bio das redes sociais.

🔗 **Site:** https://matheusmontagner8.github.io/achadinhos-linktree/

## Destaques

- **Leve e rápida:** HTML e CSS puros, sem frameworks e sem dependências externas. Ícones em SVG embutido e imagens otimizadas.
- **Mobile-first:** pensada para quem chega pelo link da bio, no celular.
- **Botão "Compartilhar":** abre o menu de compartilhamento do celular; no computador, copia o link.
- **Acessível:** HTML semântico (`main`, `nav`, `footer`), foco visível ao navegar pelo teclado e animações desligadas para quem prefere menos movimento.
- **Pronta para compartilhar:** tags Open Graph e Twitter Card para a prévia no WhatsApp e nas redes, mais `sitemap.xml` e verificação no Google Search Console.
- **Transparente:** aviso de links de afiliado no rodapé.

## Arquivos

| Arquivo | Para que serve |
| --- | --- |
| `index.html` | A página (HTML, CSS e um pequeno JavaScript) |
| `avatar.jpg` | Foto/logo do topo da página (480 × 480) |
| `logo.jpeg` | Imagem da prévia ao compartilhar o link (Open Graph) |
| `favicon.png` e `apple-touch-icon.png` | Ícone da aba do navegador e da tela inicial do celular |
| `robots.txt` e `sitemap.xml` | Ajudam os buscadores a encontrar a página |

## Como editar

Abra o `index.html` em qualquer editor de texto.

- **Links:** procure os comentários `<!-- COLE AQUI O LINK DO ... -->` e troque a URL dentro de `href="..."`.
- **Textos e seguidores:** cada link tem um título (`link-title`) e uma linha de apoio (`link-sub`).
- **Cores:** ficam centralizadas no bloco `:root { ... }`, no início do `<style>`.
- **Foto/logo:** substitua o arquivo `avatar.jpg` por outra imagem quadrada com o mesmo nome.

## Publicação

O site é publicado pelo **GitHub Pages** a partir da branch `master` (pasta `/ (root)`). Cada alteração enviada para a `master` atualiza o site em poucos minutos.

---

Criado com apoio do Claude Code.
