# Jogo de Adivinhação

Jogo de terminal em Python: o computador "pensa" em um número e o jogador tenta adivinhar qual é.

> **Versão base:** nesta versão, o número escolhido pelo computador é fixo (sempre `0`), para praticar a lógica do jogo. A escolha aleatória está nos próximos passos.

## Como funciona

1. O programa avisa que vai pensar em um número entre 0 e 5.
2. O jogador digita o palpite.
3. O programa compara o palpite com o número escolhido e mostra se o jogador venceu ou perdeu.

## Como usar

1. Tenha o Python 3 instalado.
2. Execute no terminal:

   ```bash
   python jogo.py
   ```

3. Digite o seu palpite quando o programa pedir.

## Exemplo de execução

```
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
     Vou pensar em um número  entre 0 e 5. Tente adivinhar... 
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
Em que número eu pensei? 3
PROCESSANDO...
!!*GANHEI*!! Eu pensei no número 0 e não 3
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
```

## O que pratiquei

- Entrada de dados com `input()` e conversão para inteiro com `int()`
- Estruturas condicionais (`if` / `else`)
- Comparação de valores
- Formatação de texto com `.format()`
- Repetição de textos com `"-=-=" * 17`

## Próximos passos

- Fazer o computador escolher o número de verdade, de forma aleatória, com `random.randint(0, 5)`
- Tratar entradas que não são número (hoje o programa dá erro se o jogador digitar letras)
- Permitir várias tentativas até acertar
