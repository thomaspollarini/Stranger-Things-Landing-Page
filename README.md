# 🦇 Landing Page "Mundo Invertido" - Desafio Stranger Things DIO

Este projeto é uma landing page temática e interativa inspirada no universo da série **Stranger Things**, desenvolvida como um desafio da plataforma **DIO**. O foco principal foi criar uma experiência imersiva através de **HTML semântico**, **CSS avançado com theming** e **JavaScript puro** para manipulação de DOM e áudio, permitindo ao usuário "inverter" entre o Mundo Normal e o Mundo Invertido.

---

## 🔗 Visualização do projeto

👉 [Acesse aqui!](https://thomaspollarini.github.io/Stranger-Things-Landing-Page/)

---

## 💡 Sobre o projeto

A página transporta o usuário para o clima de Hawkins, com uma narrativa que o convida a explorar o Mundo Invertido. A principal funcionalidade é o botão **"Inverter Mundos"**, que aciona uma troca completa de tema e de trilha sonora na página:

- **Mundo Normal (Tema Claro):** Apresenta um design limpo, com fontes clássicas, os heróis em destaque e uma trilha sonora correspondente.
- **Mundo Invertido (Tema Escuro):** Transforma a interface com um visual sombrio, fontes "glitch", cores ameaçadoras e uma trilha sonora sinistra, sincronizada com a mudança visual.

A página é estruturada em seções que apresentam a série, um teaser da próxima temporada, uma galeria de imagens e um formulário para os fãs se inscreverem no "Clube de D&D".

---

## ⚙️ Funcionalidades principais

- 🔄 **Botão "Inverter Mundos"** para alternar dinamicamente entre o tema claro (Mundo Normal) e o tema escuro (Mundo Invertido).
- 🎵 **Trilha sonora dinâmica** que alterna entre a música do "Mundo Normal" e a do "Mundo Invertido", sincronizada com a troca de tema.
- 🎨 **Alteração visual completa** na troca de tema, incluindo cores, fontes, imagens de fundo e orientação de elementos.
- 🎬 **Seção de trailer** com um frame de vídeo incorporado.
- 🖼️ **Galeria de imagens** da série com estilização temática.
- 📝 **Formulário de inscrição interativo** para o "Clube de Dungeons & Dragons" de Hawkins.
- 🎭 **Silhuetas de personagens** que mudam de posição e aparência conforme o tema, utilizando máscaras de CSS.

---

## 🚀 Tecnologias e ferramentas utilizadas

- **JavaScript (Puro)**
  - Manipulação do **DOM** para alternar as classes de tema (`light-theme` / `dark-theme`).
  - Controle de áudio com o construtor `new Audio()` para tocar e **trocar a fonte da música (`src`)** em tempo real.
  - Lógica de estado para gerenciar o tema e a música atual.

- **HTML5**
  - Estruturação semântica da página com tags como `<header>`, `<main>`, `<section>`, e `<footer>`.
  - Uso de atributos de acessibilidade como `aria-label` e `role`.
  - Inclusão de elementos de mídia como `<iframe>` e `<img>`.

- **CSS3**
  - Uso intensivo de **Variáveis CSS (Custom Properties)** para criar um sistema de temas (theming) robusto e de fácil manutenção.
  - **Layout com Flexbox** para organizar as seções e componentes da página.
  - **Efeitos de `transform`** para girar e inverter elementos visuais no tema do Mundo Invertido.
  - Uso de **máscaras CSS (`mask`)** para criar as silhuetas dinâmicas dos personagens na parte superior e inferior da página.
  - Estilização avançada de formulários, botões e outros elementos de interface.

- **Google Fonts**
  - Uso das fontes **Archivo**, **Libre Baskerville** e **Rubik Glitch** para construir a identidade visual contrastante entre os dois "mundos".

---

## 📚 Aprendizados e práticas consolidadas

- 🎨 **Criação de um sistema de temas (theming) do zero** utilizando o poder das Variáveis CSS.
- 🎵 **Manipulação da API de Áudio do navegador (`Audio()`)** para criar uma experiência sonora dinâmica e responsiva às ações do usuário.
- 🧩 **Gerenciamento de estado simples com JavaScript puro** para controlar a lógica da aplicação (tema e música).
- 🎭 **Aplicação de técnicas avançadas de CSS**, como `transform` e `mask`, para gerar efeitos visuais imersivos e criativos.
- 🏗️ **Estruturação de uma página web semântica**, organizada e acessível.
- 🔗 **Integração coesa entre HTML, CSS e JavaScript** para construir uma experiência de usuário unificada e temática.

---

> 🚀 **Observação:** Este projeto foi construído para fins didáticos, com o objetivo de colocar em prática os conhecimentos de front-end (HTML, CSS e JavaScript) de forma criativa, conforme proposto pelo desafio da DIO.
