# SmartAgentStateMachine

**Autor:** Luiz Gustavo Domingues Lacerda  
**RA:** 123220641

## Descrição

Neste projeto, desenvolvido como parte de uma tarefa do professor Alexandre Montanha, implementamos um **agente inteligente** para um jogo de adivinhação de números. O agente responde aos palpites do usuário e transita entre diferentes estados até que o jogo termine.

Além disso, realizamos **melhorias significativas** no código para adicionar novas opções de jogabilidade, tornando o jogo mais flexível e desafiador. O agente pode agora operar em diferentes modos de jogo e níveis de dificuldade, o que oferece uma experiência personalizada para o jogador.

## Funcionalidades

- **Modos de Jogo:** O jogador pode escolher entre:
  - **Normal**: Jogo sem restrições especiais.
  - **Pares**: O número secreto será sempre par.
  - **Ímpares**: O número secreto será sempre ímpar.
  
- **Dificuldades:** O jogo oferece três níveis de dificuldade:
  - **Fácil**: Máximo de 10 tentativas.
  - **Médio**: Máximo de 5 tentativas.
  - **Difícil**: Máximo de 3 tentativas.

- **Feedback Inteligente:** O agente oferece feedback a cada tentativa, indicando se o palpite é muito alto ou muito baixo, além de apresentar sugestões de direções para o próximo palpite.

- **Visualização:** Ao final do jogo, o desempenho do jogador é mostrado em um gráfico, com a evolução dos palpites ao longo das tentativas, permitindo que o jogador visualize como suas tentativas se comparam com o número secreto.

## Requisitos

Para rodar o projeto, é necessário ter as seguintes dependências instaladas:

- Python 3.x
- `matplotlib` (para plotar os gráficos)
- `colorama` (para melhorar a formatação das saídas no terminal)

Para instalar as dependências, basta executar:

    !pip install matplotlib
    !pip install colorama

# Como Jogar:
- 1- Copie o codigo e cole no (https://colab.google/).
- 2- Abra um New Notebook
- 3- Clique em + codigo e cole o codigo do jogo.
