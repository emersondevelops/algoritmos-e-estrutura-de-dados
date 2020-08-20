# Estrutura de Dados

## Introdução

Uma estrutura de dados organiza os dados relacionados em um computador para que possam ser usados com eficiência.

Diferentes tipos de estruturas de dados são adequados para diferentes tipos de aplicações e alguns são altamente especializados para tarefas específicas. Por exemplo, os grafos são usados para representar conexões em sites sociais (como Twitter e Facebook), árvores são usadas para representar dados hierárquicos, como arquivos e pastas em um sistema de arquivos, filas podem ser usadas para criar agenda de tarefas, implementações de compilador geralmente usam tabelas hash (ou tabela de dispersão) para procurar identificadores, árvores binárias são usadas em algoritmos de pesquisa, etc.

Normalmente, escolher a estrutura de dados correta é a chave para projetar um algoritmo eficiente.

Algumas das estruturas de dados mais comuns são:

- Array
- Lista encadeada
- Pilha
- Fila
- Grafo
- Árvore
- Tabela Hash

Algumas estruturas de dados podem ser usadas para criar outras, por exemplo, listas encadeadas podem ser usadas para criar pilhas e filas.

```
Cada estrutura de dados possui uma série de operações que podem ser realizadas nos dados que ela armazena. Selecionamos uma estrutura de dados baseada nas operações necessárias para implementar um algoritmo.
```

## Lista Encadeada

A estrutura de dados de lista encadeada é frequentemente usada para implementar outras estruturas de dados.

Uma lista encadeada é uma sequência de nós onde cada nó armazena seus próprios dados e um ponteiro (endereço) para a localização do próximo nó.
Um nó se liga a outro formando o que pode ser considerado uma cadeia ligada:

![Esquema de uma lista encadeada](./img/lista-encadeada.jpg)

O último item da lista tem um link para NULL, indicando o fim da cadeia.

### Vantagens

- Embora uma lista vinculada seja semelhante a um array, ela não está restrita a um número definido de elementos.
- Ao contrário de um array que armazena dados sequencialmente na memória ou no disco, uma lista encadeada pode inserir ou remover facilmente elementos sem realocação ou reorganização de toda a estrutura, porque os itens de dados não precisam ser armazenados sequencialmente.

### Desvantagens da lista encadeada

- O acesso aleatório não é permitido. Devemos acessar os nós sequencialmente a partir do primeiro. Portanto, não podemos fazer uma pesquisa binária em uma lista encadeada.
- É necessário espaço de memória adicional é necessário a cada novo elemento da lista.

```
Listas encadeadas geralmente são usadas como o bloco de construção fundamental para a implementação de estruturas de dados como pilhas, filas, árvores e grafos.
```
### Implementação

- Python
- C#