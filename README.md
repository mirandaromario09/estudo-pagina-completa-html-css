# Natália - Nutrição Comportamental

Landing page da Natália Porto, nutricionista comportamental. Apresenta o **Método RD** (Rasgando a Dieta) com foco em emagrecimento sem dieta tradicional.

## Sobre

A cliente tinha uma página no WordPress que não atendia mais as necessidades dela. Peguei o conteúdo original e recriei tudo do zero com HTML e CSS puros, sem frameworks ou JavaScript.

## Tecnologias

- HTML5
- CSS3 (variáveis, animações, texturas SVG)
- Font Awesome 6
- Google Fonts (Playfair Display + Inter)

## Estrutura

```
canva/
├── index.html
├── assets/
│   └── css/
│       └── style.css
├── assets/img/
├── favicon_np.ico
└── README.md
```

## Seções

- Header com navegação fixa e menu mobile (checkbox puro, sem JS)
- Hero com parallax e CTA
- Método RD (grid texto + imagem)
- Cards do método (público-alvo e funcionamento)
- Sobre mim
- FAQ em accordion (`<details>` nativo)
- CTA com link direto pro WhatsApp
- Contato e footer

## Destaques

- Zero dependências JS — menu mobile, FAQ, animações tudo em CSS puro
- Texturas de fundo (noise/grid) geradas via SVG inline
- Design responsivo com breakpoints em 1024px, 768px e 480px
- Suporte a `prefers-reduced-motion`

---
[Ver online](https://mirandaromario09.github.io/canva)