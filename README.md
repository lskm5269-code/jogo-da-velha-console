# Jogo da Velha - [Versão Console]

Este projeto foi desenvolvido durante as aulas de Programação em Python para praticar lógica, estruturas de controle e boas práticas de desenvolvimento.

## Funcionalidades principais
- Esse projeto é um jogo da velha, criado usando a linguagem pyton no console para praticar lógica, estruturas de controle e boas práticas de desenvolvimento. Ele foi desenvolvido no curso técnico em desenvolvimento de sistemas do SENAC DF com o Prof Alexandre.

Jogo da Velha – Versão Console (Python)
Descrição Geral

O projeto Jogo da Velha (Versão Console) é uma implementação simples e funcional do clássico jogo Tic-Tac-Toe, desenvolvida em Python puro, sem interface gráfica.
Ele permite que dois jogadores disputem alternadamente no mesmo computador, exibindo o tabuleiro e as jogadas diretamente no terminal (console).

⚙️ Funcionalidades Principais

Exibição do Tabuleiro

O jogo mostra o tabuleiro a cada jogada.

Cada casa é representada por um número (1 a 9), facilitando a escolha das posições.

Entrada dos Jogadores

Os jogadores alternam entre os símbolos X e O.

A cada turno, o jogo solicita que o jogador informe o número da posição desejada.

Validação de Jogadas

Se o jogador tentar jogar em uma posição já ocupada, o sistema rejeita a jogada e pede outra posição válida.

Alternância de Turnos

O programa alterna automaticamente entre o jogador X e o jogador O, mantendo o controle do turno atual.

Verificação de Vitória

Após cada jogada, o programa verifica se há três símbolos iguais em linha, coluna ou diagonal.

Quando um jogador vence, o jogo exibe uma mensagem informando o vencedor e encerra a partida.

Verificação de Empate

Se todas as casas forem preenchidas e não houver vencedor, o jogo declara empate.

Reinício da Partida

Após o término (vitória ou empate), o programa pode reiniciar automaticamente ou encerrar conforme a escolha do usuário.

 Recursos Utilizados:

Linguagem: Python 3

Conceitos aplicados:

Estruturas de repetição (while)

Condicionais (if, elif, else)

Listas

Funções

Controle de fluxo lógico

🏁 Fluxo de Execução

O programa inicia e mostra o tabuleiro vazio.

O Jogador X faz a primeira jogada.

O Jogador O joga em seguida.

O sistema verifica vitória ou empate a cada jogada.

Quando o jogo termina, o resultado é exibido e o jogo pode ser reiniciado.


## Como executar
Para rodar o projeto, execute o arquivo principal dentro da pasta `src`:

```bash
python src/main.py
