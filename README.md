# Marques & Tasoko - Landing Page Jurídica

[![forthebadge](https://forthebadge.com/api/badges/generate?panels=2&primaryLabel=CRIADO+COM&secondaryLabel=JAVASCRIPT&primaryBGColor=%23edc707&primaryTextColor=%23000000&secondaryBGColor=%23fbff00&secondaryTextColor=%23000000&primaryFontSize=12&primaryFontWeight=600&primaryLetterSpacing=2&primaryFontFamily=Roboto&primaryTextTransform=uppercase&secondaryFontSize=12&secondaryFontWeight=900&secondaryLetterSpacing=2&secondaryFontFamily=Montserrat&secondaryTextTransform=uppercase)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/api/badges/generate?panels=2&primaryLabel=CRIADO+COM&secondaryLabel=CSS&primaryBGColor=%23295185&primaryTextColor=%23ffffff&secondaryBGColor=%23007bff&secondaryTextColor=%23000000&primaryFontSize=12&primaryFontWeight=600&primaryLetterSpacing=2&primaryFontFamily=Roboto&primaryTextTransform=uppercase&secondaryFontSize=12&secondaryFontWeight=900&secondaryLetterSpacing=2&secondaryFontFamily=Montserrat&secondaryTextTransform=uppercase)](https://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

## Sobre o Projeto

Uma **Landing Page Institucional** desenvolvida para o escritório de advocacia **Marques & Tasoko Advogados Associados**, especializado em Direito do Trabalho.

O projeto foi projetado para transmitir seriedade e confiança, utilizando uma paleta de cores sóbria (preto e dourado). O site apresenta as áreas de atuação (para empresas e empregados), a equipe de advogados e canais de atendimento digital e presencial.

A interface é totalmente responsiva, combinando a utilidade do **TailwindCSS** para estruturação rápida com **CSS3** personalizado para elementos visuais específicos, como faixas diagonais e efeitos de botões.

## Sumário

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Frontend & Estilização](#frontend-&-estilização)
- [Funcionalidades](#funcionalidades)
  - [Seções Principais](#seções-principais)
  - [Interatividade](#interatividade)
- [Estrutura de pastas](#estrutura-pastas)
- [Como Executar](#como-executar)
- [Autor](#autor)

## Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

### Frontend & Estilização
- **HTML5 Semântico**
- **JavaScript (ES6+):** Manipulação do DOM para menus e comportamento de scroll.
- **TailwindCSS:** Framework utilizado via CDN para configuração de tema (cores personalizadas e espaçamentos) e responsividade.
- **CSS3:** Utilizado para estilizações específicas que fogem do padrão do framework, como divisores dourados (`.golden-line`) e transformações geométricas (`skew`).

---

## Funcionalidades

### Seções Principais
- **Header Inteligente:** Barra de navegação fixa (Sticky Header) que muda de comportamento ao rolar a página.
- **Hero Section:** Banner principal com chamada para ação (CTA) clara.
- **Propostas de Serviço:** Cards destacando modalidades de atendimento (Digital, Reunião agendada, Análise).
- **Áreas de Atuação:** Seção dividida visualmente entre serviços para empresas e para empregados.
- **Equipe:** Apresentação dos advogados com fotos e cargos.
- **Footer Informativo:** Dados de contato, endereço e links para redes sociais.

### Interatividade
- **Menu Mobile:** Menu lateral deslizante para dispositivos móveis.
- **Sticky Navbar:** O menu superior torna-se fixo e ganha uma animação de "slide down" após a rolagem da página.
- **Compensação de Âncora:** Script para ajustar a posição de rolagem ao clicar nos links do menu, evitando que o conteúdo fique escondido atrás do header fixo.

---

## Estrutura de pastas

```text
marquestasoko-landingpage/
├── assets/                 # Recursos estáticos
│   ├── icons/              # Ícones SVG (Social, Menu, UI)
│   └── images/             # Fotos da equipe e banners
├── js/                     # Scripts auxiliares
│   └── tailwind.config.js  # Configuração do tema do Tailwind (Cores e Spacing)
├── style.css               # Estilos personalizados (CSS puro)
└── index.html              # Estrutura principal da página (Lógica JS inclusa no final)
```

## Como executar

Este é um projeto estático e leve

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/ns-works/marquestasoko-landingpage.git
   ```

2. **Abra o projeto**: Navegue até a pasta do projeto e abra o arquivo index.html no seu navegador.

## Autor

[Nicolas Samuel](https://www.linkedin.com/in/nicolas-samuel-veras/)

[![LinkedIn][linkedin-shield]][linkedin-url]
[![Behance][behance-shield]][behance-url]

<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin-white&colorB=555
[linkedin-url]: https://www.linkedin.com/in/nicolas-samuel-veras/
[behance-shield]: https://img.shields.io/badge/Behance-0054F7?style=for-the-badge&logo=behance&colorB=555
[behance-url]: https://www.behance.net/nicolsam
