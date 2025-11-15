# 🍟 Prigles | Landing Page Pringles

> Recriação e estudo de uma landing page para a marca Pringles, com foco em animações de alto impacto, carrossel de produtos interativo e efeitos de rolagem (scroll effects).

[![Tecnologias](https://skillicons.dev/icons?i=html,css,js&theme=dark)](https://skillicons.dev/)
[![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)](https://github.com/Carol0021/Prigles)

## 🌟 Demonstração

Veja o projeto rodando e sinta a experiência das animações em tempo real:

| Plataforma | Link |
| :---: | :---: |
| **GitHub Pages** | [https://carol0021.github.io/Prigles/](https://carol0021.github.io/Prigles/) |
| **Vercel** | [https://prigles.vercel.app/](https://prigles.vercel.app/) |



## ✨ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e bibliotecas de animação:

* **HTML5:** Estrutura semântica do projeto.
* **CSS3 (Puro):** Estilização, layout responsivo (Media Queries) e design moderno.
* **JavaScript (Puro):** Lógica principal de interação e manipulação do DOM.
* **[GSAP (GreenSock Animation Platform)](https://gsap.com/):** Biblioteca líder para criar animações de alto desempenho e complexidade, essencial para todos os efeitos de rolagem e transições.
* **[ScrollTrigger (GSAP Plugin)](https://gsap.com/docs/v3/Plugins/ScrollTrigger/):** Usado para disparar animações com base no progresso da rolagem da página.
* **[SplitType](https://splittype.com/):** Usado para dividir o texto (títulos `<h2>`) em caracteres para aplicar animações de entrada de texto com `GSAP`.

## ⚙️ Funcionalidades e Destaques

O Prigles foi desenvolvido com foco em performance e experiência visual, destacando-se pelas seguintes funcionalidades:

1.  **Carrossel de Produtos Interativo:** Transição suave entre os sabores, utilizando transições CSS e JavaScript. A transição é acionada pelos botões de navegação, pelos *bullets* e ao clicar na próxima lata (`.imgNext`).
2.  **Animações de Entrada de Texto:** Os títulos dos slides (`<h2>`) têm um efeito de digitação/entrada de baixo para cima, controlado pelo **SplitType** e **GSAP**.
3.  **Animações de Rolagem (ScrollTrigger):**
    * **Faixa Animada (Marquee):** O texto na seção 2 se move horizontalmente junto com a rolagem, criando um efeito imersivo de *marquee* em curva.
    * **Desenho Vetorial (SVG):** A linha vetorial (*path*) se desenha progressivamente conforme o usuário desce a página.
    * **Latas em Movimento:** As latas de Pringles na seção 2 têm animações sutis de rotação e deslocamento (`rotate`, `y`), reagindo ao progresso da rolagem.
4.  **Design Responsivo:** Layout adaptável para telas móveis (`@media screen and (max-width: 820px)`), garantindo uma experiência consistente em diferentes dispositivos.

## 🤝 Contribuição e Implementação Local

Este projeto foi desenvolvido como parte de um estudo no **DevArt**. Sinta-se à vontade para clonar e explorar o código.

### Pré-requisitos

Você só precisará de um navegador web (como Chrome, Firefox ou Edge).

### Como Rodar o Projeto

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/Carol0021/Prigles.git](https://github.com/Carol0021/Prigles.git)
    ```
2.  **Entre na Pasta do Projeto:**
    ```bash
    cd Prigles
    ```
3.  **Abra o Arquivo:**
    Simplesmente abra o arquivo `index.html` no seu navegador favorito.

## 👩‍💻 Autor

Este projeto foi desenvolvido por:

| [![Caroline dos Reis](https://avatars.githubusercontent.com/u/SEU_ID_DO_GITHUB?v=4&s=100)](https://github.com/Carol0021) |
| :---: |
| **Caroline dos Reis** |
| [GitHub](https://github.com/Carol0021) |
| [LinkedIn](https://www.linkedin.com/in/carolinedev) |
| *Projeto desenvolvido no DevArt* |

---

_A marca Pringles e seus ativos visuais são de propriedade da Kellogg's. Este projeto é estritamente para fins educacionais e de portfólio, sem fins comerciais._
