# Atividade – Algoritmos de Ordenação em C

Foram realizados testes com os algoritmos **Bubble Sort** e **Selection Sort**,
utilizando vetores de tamanhos **100**, **1000** e **10000**, inicializados em
ordem decrescente.

A comparação considerou os seguintes critérios:
- Tempo de execução
- Número de comparações
- Número de movimentações

## Análise dos resultados

Os resultados mostram que o **Bubble Sort** apresentou um maior número de
movimentações, pois realiza diversas trocas sempre que encontra elementos fora
de ordem. Esse comportamento faz com que seu tempo de execução aumente,
principalmente para vetores de maior tamanho.

Já o **Selection Sort** apresentou melhor desempenho em relação às
movimentações, pois realiza apenas uma troca por iteração, mesmo mantendo um
número semelhante de comparações. Dessa forma, seu tempo de execução mostrou-se
mais eficiente nos testes realizados.

## Conclusão

Conclui-se que o **Selection Sort** apresentou melhor desempenho geral,
mostrando-se mais adequado para vetores de maior tamanho quando comparado ao
**Bubble Sort**.

## Arquivos do repositório
- `atividade_semana02.c` – Código-fonte em linguagem C
- `link.txt` – Arquivo contendo o link do repositório para entrega no AVA
