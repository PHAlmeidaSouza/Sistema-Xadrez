# Chess System Java

Este é um projeto desenvolvido como parte do curso **"Programação Orientada a Objetos com Java"**, ministrado pelo Prof. Dr. Nelio Alves, disponibilizado pela plataforma [educandoweb.com.br](http://educandoweb.com.br).

## Objetivo Geral

O objetivo deste projeto é aplicar os conhecimentos aprendidos até o momento no curso para a construção de um sistema de jogo de xadrez em Java.

## Estrutura do Projeto

O projeto segue uma estrutura organizada em classes e métodos, conforme descrito abaixo:

### Classes e Funcionalidades Implementadas

1. `<Position>`: Representa uma posição no tabuleiro de xadrez.
2. `<Piece>`: Classe base para as peças do xadrez.
3. `<Board>`: Representa o tabuleiro de xadrez e suas funcionalidades.
4. `<ChessPiece>`: Classe que estende Piece e representa as peças de xadrez.
5. `<ChessMatch>`: Classe principal que gerencia o jogo de xadrez.
6. `<ChessConsole.UI>`: Classe responsável pela interface de usuário no console.
7. `<Rook>`: Classe que representa a torre no jogo de xadrez.
8. `<King>`: Classe que representa o rei no jogo de xadrez.
9. `<BoardException>`: Exceção para tratamento de erros relacionados ao tabuleiro.
10. `<ChessException>`: Exceção para tratamento de erros relacionados ao jogo de xadrez.
11. `<ChessPosition>`: Representa uma posição no formato do jogo de xadrez.

### Funcionalidades Implementadas

- Inicialização do tabuleiro.
- Impressão do tabuleiro no console.
- Movimentação das peças.
- Validação de movimentos.
- Identificação de xeque.
- Identificação de xeque-mate.
- Implementação de jogadas especiais como Roque, En Passant e Promoção.

## Configuração do Ambiente de Desenvolvimento

Para configurar o ambiente de desenvolvimento, siga as instruções abaixo:

1. Clone este repositório.
2. Certifique-se de ter o JDK (Java Development Kit) instalado em seu sistema.
3. Abra o projeto em sua IDE preferida.
4. Compile e execute o código para iniciar o jogo de xadrez.

## Como Jogar

Após iniciar o jogo, siga as instruções apresentadas no console para movimentar suas peças e interagir com o jogo.

## Referências

- [Documentação do Projeto](https://github.com/acenelio/chess-system-design)
- [Java Clear the Console](https://stackoverflow.com/questions/2979383/java-clear-the-console)

Divirta-se jogando xadrez!
