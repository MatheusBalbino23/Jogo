# Jogo de Acertar o Monstro

Este é um jogo simples em C onde o jogador deve digitar um número e tentar acertar um "monstro" em uma posição aleatória na tela.

## Funcionamento

O jogo começa gerando aleatoriamente a posição vertical do monstro. O jogador tem 5 chances para tentar acertar o monstro. Ele digita um número e uma "bala" é disparada na horizontal na tentativa de acertar o monstro. Se o jogador não acertar o monstro após 5 tentativas, o jogo termina.

## Como Executar

1. Certifique-se de ter um compilador C instalado em seu sistema.
2. Abra um terminal na pasta onde está o arquivo fonte (`jogo_monstro.c`).
3. Compile o programa usando o compilador C. Por exemplo, usando o GCC:
   ```bash
   gcc -o jogo_monstro jogo_monstro.c
   ```
4. Execute o programa:
   ```bash
   ./jogo_monstro
   ```

## Exemplo de Uso

```
SEJA BEM VINDO AO NOSSO JOGO!!
Para acertar o monstro voce deve digitar um numero e ter sorte para acertar o monstro
O monstro tem 3 vidas e voce tem 5 chances, entao boa sorte
Sugerimos que nao tente numeros tao altos :)
PS: jogue o jogo em tela cheia!!

Digite um numero: 30
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
