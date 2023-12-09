# Algoritmo Genético em C

Este repositório contém a implementação de um Algoritmo Genético em linguagem C. Os Algoritmos Genéticos são técnicas de otimização baseadas em processos inspirados na evolução natural. Este código em particular aborda a resolução de problemas de otimização usando uma população de cromossomos que evoluem ao longo de várias gerações.

## Como Funciona

### Representação do Cromossomo
Cada indivíduo no algoritmo é representado por um cromossomo, que consiste em uma sequência de bits.

### Função de Avaliação
A função de avaliação determina o quão bem um indivíduo se adapta ao ambiente. No código fornecido, a função de avaliação é definida pela função `funcaoAvaliacao(int x)`.

### Gerações e Evolução
O algoritmo evolui a população ao longo de várias gerações. Em cada geração, os indivíduos são avaliados, selecionados para reprodução, sofrem crossover (recombinação genética), e alguns indivíduos podem sofrer mutação.

### Execução
O programa pode ser compilado e executado em um ambiente C. Certifique-se de ter um compilador C instalado. Abaixo está um exemplo de como executar o código:

```bash
gcc algoritmo_genetico.c -o algoritmo_genetico
./algoritmo_genetico
```

### Parâmetros Configuráveis
- `TAM`: Quantidade de bits na representação do cromossomo.
- `POPULACAO`: Tamanho da população.
- `GERACOES`: Número de gerações.
- `MUTACAO`: Taxa de mutação.

## Contribuição
Sinta-se à vontade para contribuir para o desenvolvimento e aprimoramento deste algoritmo genético. Você pode propor melhorias, otimizações ou adicionar recursos adicionais.

## Referências
- [Wikipedia - Algoritmo Genético](https://en.wikipedia.org/wiki/Genetic_algorithm)

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.
