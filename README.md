# 📰 Portal de Notícias - Responsivo

> Desafio prático de responsividade do curso Fullstack da Rocketseat

Um portal de notícias moderno e totalmente responsivo, focado em tecnologia e inovação. Este projeto demonstra a implementação de layouts adaptativos usando CSS Grid, Media Queries e a metodologia Mobile First.

## 🚀 Demo

- **Design Original**: [Figma - Portal de Notícias](https://www.figma.com/community/file/1392188698846698895/portal-de-noticias)
- **Versão Desktop**: Layout complexo com sidebar e grid avançado
- **Versão Mobile**: Layout otimizado para dispositivos móveis

## 📱 Responsividade

O projeto foi desenvolvido seguindo a metodologia **Mobile First** com os seguintes breakpoints:

- 📱 **Mobile**: 320px - 768px
- 📟 **Tablet**: 768px - 1024px  
- 💻 **Desktop**: 1024px+

### Principais Adaptações

#### Mobile (< 768px)
- Layout em coluna única
- Navegação secundária oculta
- Tipografia otimizada para telas pequenas
- Cards empilhados verticalmente
- Imagens redimensionadas

#### Tablet (768px - 1024px)
- Grid de 2 colunas para conteúdo
- Navegação secundária visível com scroll horizontal
- Layout híbrido entre mobile e desktop

#### Desktop (1024px+)
- Layout complexo com sidebar (2fr + 1.4fr)
- Grid avançado para seção featured
- Navegação completa
- Tipografia e espaçamentos originais

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e layout
  - CSS Grid
  - Flexbox  
  - Media Queries
  - CSS Custom Properties (variáveis)
  - CSS Nesting
- **Google Fonts** - Tipografia (Archivo)

## 🎨 Features

- ✅ **Design Responsivo** - Adaptável a todos os dispositivos
- ✅ **Mobile First** - Desenvolvido prioritariamente para mobile
- ✅ **CSS Grid** - Layout moderno e flexível  
- ✅ **Media Queries** - Breakpoints otimizados
- ✅ **Semantic HTML** - Estrutura acessível
- ✅ **CSS Variables** - Sistema de design tokens
- ✅ **Performance** - CSS otimizado e modular

## 📂 Estrutura do Projeto

```
portal-de-noticias/
├── assets/
│   ├── icons/          # Ícones SVG
│   ├── images/         # Imagens das notícias
│   ├── Logo.svg        # Logo do TechNews
│   └── Ads.png         # Banner publicitário
├── styles/
│   ├── index.css                 # CSS original (desktop)
│   ├── index-mobile-first.css    # CSS Mobile First (atual)
│   ├── global-mobile-first.css   # Estilos base responsivos
│   ├── utility-mobile-first.css  # Classes utilitárias
│   ├── header-mobile-first.css   # Header responsivo
│   ├── sections-mobile-first.css # Seções responsivas
│   ├── global.css               # Estilos originais
│   ├── utility.css              # Utilities originais
│   ├── header.css               # Header original
│   └── sections.css             # Seções originais
└── index.html          # Página principal
```

## 🔧 Como Executar

1. **Clone o repositório**
```bash
git clone <url-do-repositorio>
cd portal-de-noticias
```

2. **Abra o arquivo**
```bash
# Abra o index.html em qualquer navegador
# Ou use um servidor local como Live Server
```

3. **Para testar responsividade**
- Use as DevTools do navegador (F12)
- Teste diferentes tamanhos de tela
- Verifique breakpoints: 768px, 1024px

## 🎯 Seções do Portal

### 🏠 Header
- **Navegação Principal**: Menu, Logo, Busca
- **Navegação Secundária**: Categorias (IA, Blockchain, Hologramas, etc.)

### 📰 Conteúdo Principal
- **Featured**: Notícia principal + grid de destaques
- **Mais Lidas**: Grid horizontal de notícias populares  
- **Destaques da IA**: Artigos sobre inteligência artificial
- **Viu isso aqui?**: Sidebar com notícias relacionadas

## 🎨 Sistema de Design

### Cores
```css
--brand-color-light: #60A5FA;
--brand-color-dark: #1D4ED8;
--bg-color: #0F172A;
--stroke-color: #1E293B;
--text-color-primary: #F1F5F9;
--text-color-secondary: #CBD5E1;
```

### Tipografia
- **Fonte**: Archivo (Google Fonts)
- **Escalas**: Responsiva por breakpoint
- **Pesos**: 400 (regular), 600 (semibold), 700-800 (bold)

## 📖 Aprendizados

Este projeto consolidou conhecimentos em:

- **CSS Grid avançado** com áreas nomeadas
- **Mobile First** como metodologia de desenvolvimento
- **Media Queries** estratégicas para diferentes dispositivos
- **CSS Architecture** modular e escalável
- **Responsive Design** patterns
- **Performance** em CSS

## 🚀 Melhorias Futuras

- [ ] Menu hamburger funcional em JavaScript
- [ ] Sistema de busca ativo
- [ ] Lazy loading para imagens
- [ ] Dark/Light mode toggle
- [ ] Animações e micro-interações
- [ ] PWA (Progressive Web App)

## 👨‍💻 Autor

Desenvolvido como parte do desafio de responsividade do curso Fullstack da [Rocketseat](https://rocketseat.com.br).

---

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!

💜 **Feito com carinho e muita responsividade**