# Vinteum

Jogo de cartas "Vinteum" implementado em Java com JavaFX.

## Sobre

Este projeto é uma aplicação desktop que simula o jogo de cartas Vinteum (similar ao Blackjack). O jogador compete contra o computador, pedindo cartas e tentando chegar o mais próximo possível de 21 pontos sem ultrapassar.

## Funcionalidades

- Interface gráfica feita com JavaFX.
- Distribuição de cartas clássicas.
- Pontuação dinâmica para jogador e computador.
- Botões para pedir carta, parar e iniciar novo jogo.

## Estrutura

src/ main/ java/ com/ example/ App.java PrimaryController.java resources/ com/ example/ primary.fxml classic-cards/ (imagens das cartas)


## Como executar

1. Certifique-se de ter o [Java 11+](https://adoptopenjdk.net/) instalado.
2. Instale o [Maven](https://maven.apache.org/).
3. Execute o comando abaixo na raiz do projeto:

mvn clean javafx:run

## Dependências

- JavaFX Controls
- JavaFX FXML

As dependências são gerenciadas via Maven no arquivo pom.xml.

## Lincença

Este projeto está sob a licença MIT.