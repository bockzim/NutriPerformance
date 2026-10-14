# NutriPerformance — landing page

Baseada na página enviada (mesmo visual, mesma copy e mesmos valores), com a proposta **"+100 ferramentas prontas"** adaptada ao produto. Estrutura igual à do projeto de referência.

```
nutriperformance/
├── index.html      estrutura da página (markup com utilitários Tailwind via CDN)
├── css/style.css   cores, componentes e ajustes mobile
├── js/main.js      preços/links, listas, carrosséis, FAQ, popup, barra fixa de CTA
├── images/         hero, fotos, 21 prévias, logo e favicons
├── media/          vídeo (quando existirem)
├── README.md
├── CATALOGO.md     catálogo do projeto
└── LISTA-IMAGENS.md  o que ainda falta gerar
```

## Onde editar
| O quê | Onde |
|---|---|
| Preços, economia, links de checkout | `js/main.js`, objeto `C` (primeiras linhas) |
| Lista de documentos das prévias | `js/main.js`, `const docs` |
| Pilha da oferta, listas dos planos, comparação, FAQ | `js/main.js` (`st`, `lb`, `lf`, `rw`, `fq`) |
| Textos fixos (hero, seções, rodapé) | `index.html` |
| Cores | `css/style.css`, bloco `:root` |

Para rodar, abra o `index.html` (precisa de internet para o Tailwind CDN e as fontes).
