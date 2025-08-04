# 🎲 Jogo do Número Secreto

Seja bem-vindo(a) ao "Jogo do Número Secreto"! Prepare-se para testar sua intuição e sorte. Este é um projeto de um jogo simples, mas divertido, onde você tenta adivinhar o número secreto gerado aleatoriamente.

## 🎯 Objetivo do Jogo

O objetivo é adivinhar o número secreto que está entre 1 e 10. A cada tentativa, o jogo dá uma dica se o número secreto é maior ou menor que o seu chute. O jogo continua até você acertar!

## ✨ Funcionalidades Principais

* **Geração Aleatória:** Um novo número secreto é gerado a cada rodada, utilizando a função `gerarNumeroAleatorio()`.
* **Pistas Inteligentes:** Receba dicas de "maior" ou "menor" para ajudar na sua próxima tentativa. A lógica para isso está na função `verificarChute()`.
* **Contador de Tentativas:** Descubra quantas tentativas você precisou para acertar o número. O contador `tentativas` é incrementado a cada erro.
* **Reinicio Rápido:** Um botão de "Novo Jogo" (com o ID `reiniciar`) é habilitado após você acertar, permitindo que você comece uma nova rodada instantaneamente.
* **Lista de Números:** O jogo mantém um histórico dos números sorteados na `listaDeNumerosSorteados` para garantir que não se repitam até que todos os números no limite (1 a 10) sejam sorteados, evitando repetições imediatas.

## 💻 Tecnologias Utilizadas

* **HTML5:** Estrutura da página, com os elementos para o título (`h1`), parágrafo (`p.texto__paragrafo`), campo de input (`input.container__input`) e botões (`button.container__botao`).
* **CSS3:** Estilização com a classe `.container__conteudo` para organizar o layout, e `.container__imagem-pessoa` para a imagem visual. O design é responsivo, se adaptando a telas menores que 1250px.
* **JavaScript:** Toda a lógica do jogo, incluindo a manipulação do DOM para exibir textos, a contagem de tentativas, a verificação do chute e o controle dos botões.
* **ResponsiveVoice.js:** Biblioteca externa utilizada para a narração das mensagens de texto, proporcionando uma experiência de usuário mais rica.

## 🚀 Como Jogar

1.  Abra o arquivo `index.html` em seu navegador.
2.  Leia a mensagem de boas-vindas e insira seu chute no campo de texto.
3.  Clique no botão "Chutar" para verificar sua resposta.
4.  Siga as dicas ("O numero secreto é maior!" ou "O numero secreto é menor!").
5.  Quando você acertar, o botão "Novo Jogo" será habilitado para começar uma nova partida.

## 🤝 Contribuições

Sinta-se à vontade para sugerir melhorias, reportar bugs ou adicionar novas funcionalidades. Toda contribuição é bem-vinda!

## 📜 Licença

Este projeto está sob a licença **MIT**.

## * **LINK** *

HTML:* https://jogo-do-numero-secreto-gilt-two.vercel.app/