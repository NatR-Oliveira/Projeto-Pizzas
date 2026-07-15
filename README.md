# 🍕 Oliveira's Pizzas

Um e-commerce de delivery focado em experiência do usuário (UX) e design limpo. Este projeto simula a interface completa de um pedido de pizza, desde a escolha no cardápio até a finalização no carrinho, com cálculos dinâmicos de preço e animações fluídas.

> 🔗 https://natr-oliveira.github.io/Projeto-Pizzas/

 <img width="2485" height="900" alt="Captura de tela 2026-07-14 215220" src="https://github.com/user-attachments/assets/c5ba29f7-b643-4698-9ae1-c18a9d21238f" />

## ✨ Funcionalidades

O projeto foi construído para ser interativo e responsivo, contendo:

* **Cardápio Dinâmico:** As pizzas são renderizadas na tela a partir de um banco de dados local (Array de Objetos em JS).
* **Modal de Detalhes:** Ao clicar em uma pizza, uma janela fluida se abre para escolha de tamanhos e quantidades.
* **Lógica de Precificação:** O valor da pizza muda dinamicamente dependendo do tamanho escolhido (Pequena, Média ou Grande).
* **Carrinho Inteligente:** Adição, remoção e alteração de quantidade de itens com cálculo em tempo real do subtotal, desconto e total.
* **Animações em CSS (Particles):** Fundo imersivo animado utilizando apenas CSS `@keyframes` para criar o efeito de folhas caindo.
* **Design Responsivo:** Layout 100% adaptado para dispositivos móveis, com menu lateral (sidebar) deslizante.
* **Checkout de Sucesso:** Modal de finalização de compra amigável que limpa os dados e encerra a jornada do usuário.

## 🚀 Tecnologias Utilizadas

O projeto foi desenvolvido puramente com as tecnologias base da web (Vanilla), sem uso de frameworks, para consolidar os fundamentos de Front-end e UI Design:

* **HTML5:** Estrutura semântica.
* **CSS3:** Estilização avançada com Flexbox, CSS Grid, Variáveis (Custom Properties) e Animações.
* **JavaScript (ES6+):** Manipulação de DOM, eventos, cálculos matemáticos para regras de negócio e manipulação de Arrays/Objetos.

## 🎨 UI/UX Design

Foi dado um foco especial à interface do usuário para criar um ambiente moderno e agradável:
* Uso de paleta de cores orgânica (tons de verde sálvia e branco) para remeter à culinária e ingredientes frescos.
* Centralização e respiro visual (White Space) nos cards para destacar o produto.
* Feedback visual constante (Hover states, transições suaves de opacidade e movimento).

## 💻 Como rodar o projeto localmente

Como é um projeto Vanilla (HTML, CSS e JS puros), não é necessária nenhuma instalação complexa.

1. Faça o clone deste repositório executando o comando abaixo no seu terminal:
`git clone https://github.com/natr-oliveira/Projeto-Pizzas.git`

2. Abra a pasta do projeto.
3. Dê um duplo clique no arquivo `index.html` para abrir no seu navegador padrão.
