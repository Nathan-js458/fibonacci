# Fibonacci em C

Projeto simples em C que imprime a sequência de Fibonacci no terminal.

## Como funciona

O programa inicia com `x = 0` e `y = 1`, imprime os valores da sequência e calcula o próximo termo com a soma dos dois anteriores.

No estado atual, ele:

- imprime os números de Fibonacci enquanto `x < 255`;
- ao atingir o limite, reinicia a sequência;
- executa em loop infinito.

## Requisitos

- Compilador C (GCC/Clang)

## Compilar

```bash
gcc -Wall -Wextra -O2 -o fibonacci main.c
```

## Executar

```bash
./fibonacci
```

## Estrutura

- `main.c`: implementação principal
- `README.md`: documentação do projeto

## Próximas melhorias sugeridas

- Remover loop infinito por padrão
- Permitir configurar limite via argumento de linha de comando
- Melhorar tratamento de overflow
- Adicionar testes automatizados
