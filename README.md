# 🚴‍♂️ Mini Bikcraft Web

Um projeto pequeno de **HTML** e **CSS** focado nas melhores práticas de desenvolvimento web moderno, apresentando uma landing page responsiva para a marca Bikcraft - especializada em bicicletas elétricas feitas à mão.

## 🎨 Melhores Práticas Implementadas

### **HTML Semântico**

- ✅ Uso correto de tags semânticas (`header`, `main`, `article`, `nav`, `footer`)
- ✅ Atributos de acessibilidade (`aria-label`, `aria-labelledby`)
- ✅ IDs descritivos para navegação por teclado
- ✅ Meta tags essenciais para SEO e responsividade
- ✅ Alt text apropriado para imagens

### **CSS Moderno**

- ✅ **CSS Grid**: Layout principal com `grid-template-columns`
- ✅ **Flexbox**: Navegação e elementos flexíveis
- ✅ **Variáveis CSS**: Cores consistentes (#e21, #900, #f7f7f7)
- ✅ **Box-sizing**: border-box para controle preciso de dimensões
- ✅ **Hover Effects**: Interatividade visual elegante
- ✅ **Pseudo-elementos**: Detalhes decorativos com `::after`

### **Design Responsivo**

- ✅ Viewport meta tag configurada
- ✅ Imagens responsivas com `max-width: 100%`
- ✅ Layout flexível com CSS Grid
- ✅ Unidades relativas (rem, %)
- ✅ Uso de media queries (@media) para adaptar o layout em diferentes larguras de tela:
  - `@media (max-width: 950px)`: Ajusta grid de vantagens para uma coluna e centraliza subtítulo.
  - `@media (max-width: 600px)`: Reduz espaçamentos, muda grid principal para uma coluna, ajusta texto e oculta detalhes decorativos.
  - `@media (max-width: 400px)`: Diminui ainda mais o tamanho do subtítulo para telas muito pequenas.

Essas media queries garantem que o site seja totalmente adaptável e legível em dispositivos móveis, tablets e desktops.

### **Performance e UX**

- ✅ Reset CSS personalizado
- ✅ Otimização de fontes web-safe
- ✅ Estrutura de pastas organizada
- ✅ Código limpo e bem documentado

## 📁 Estrutura do Projeto

```
Mini-Bikcraft-Web/
├── index.html          # Página principal
├── style.css           # Estilos globais
├── README.md           # Documentação
└── img/                # Assets visuais
    ├── bicicleta.jpg   # Imagem principal do produto
    ├── bikcraft.svg    # Logo da marca
    ├── eletrica.svg    # Ícone motor elétrico
    ├── onda.svg        # Padrão decorativo
    ├── rastreador.svg  # Ícone rastreador
    └── velocidade.svg  # Ícone velocidade
```

## 🎯 Seções da Landing Page

### **Header**

- Logo da marca Bikcraft
- Navegação principal: Sobre | Produtos | Lojas | Contato

### **Hero Section**

- Título principal: "Bicicletas Feitas a Mão"
- Descrição da Nimbus Stark
- CTA button "VER MAIS"
- Imagem do produto em destaque

### **Vantagens Bikcraft**

- Cards informativos com ícones SVG
- Grid layout responsivo
- Hover effects interativos

### **Footer**

- Informações de copyright
- Design minimalista

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone [url-do-repositorio]
```

2. Navegue até o diretório:

```bash
cd Mini-Bikcraft-Web
```

3. Abra o `index.html` em seu navegador preferido ou use um servidor local:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (live-server)
npx live-server
```

## 🎨 Paleta de Cores

| Cor                | Hex       | Uso                     |
| ------------------ | --------- | ----------------------- |
| Vermelho Principal | `#e21`    | Botões, destaques       |
| Vermelho Escuro    | `#900`    | Hover states, bordas    |
| Cinza Claro        | `#f7f7f7` | Background, alternância |
| Branco             | `#fff`    | Cards, navegação        |
| Preto              | `#000`    | Texto principal         |

## 📱 Responsividade

O projeto utiliza CSS Grid e Flexbox para garantir uma experiência consistente em:

- 📱 **Mobile**: Layout em coluna única
- 💻 **Desktop**: Layout em duas colunas
- 🖥️ **Wide screens**: Conteúdo centralizado com max-width

## 🎯 Objetivos de Aprendizado

Este projeto demonstra:

- ✅ Estruturação semântica de HTML
- ✅ Layout moderno com CSS Grid/Flexbox
- ✅ Princípios de acessibilidade web
- ✅ Design responsivo mobile-first
- ✅ Organização de código e assets
- ✅ Boas práticas de nomenclatura CSS

**Desenvolvido com foco em código limpo, semântica web e experiência do usuário.** 🚴‍♂️✨
