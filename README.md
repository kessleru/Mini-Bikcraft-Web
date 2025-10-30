# Mini Bikcraft Web

Landing page responsiva para a Bikcraft, marca de bicicletas elétricas feitas à mão. Projeto focado em HTML semântico e CSS moderno.

## Tecnologias

- HTML5 (tags semânticas e acessibilidade)
- CSS3 (Grid, Flexbox e variáveis CSS)
- Design responsivo com media queries
- Modo claro/escuro automático

## Recursos

- Layout responsivo com CSS Grid e Flexbox
- Tema claro/escuro usando `prefers-color-scheme`
- Navegação com hover effects
- Ícones SVG otimizados
- Estrutura semântica para SEO

## Estrutura

```
Mini-Bikcraft-Web/
├── index.html
├── style.css
└── img/
    ├── bicicleta.jpg
    ├── bikcraft.svg
    └── [ícones].svg
```

## Como Usar

Abra o arquivo [index.html](index.html) diretamente no navegador ou use um servidor local:

```bash
# Python
python -m http.server 8000

# Node.js
npx live-server
```

## Responsividade

- **Desktop**: Layout em duas colunas (max-width: 1000px)
- **Tablet** (≤950px): Grid de vantagens em coluna única
- **Mobile** (≤600px): Layout completo em coluna única
- **Mobile pequeno** (≤400px): Ajustes de tipografia

## Paleta de Cores

- Primária: `#ee2211`
- Destaque: `#900900`
- Fundos: `#f7f7f7` / `#ffffff`
