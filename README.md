# SIGIC – Sistema Inteligente de Gerenciamento da Infraestrutura da Colônia

## Sobre o projeto

O SIGIC é um sistema desenvolvido em Python para representar a infraestrutura da colônia Aurora Siger em Marte.

A infraestrutura foi modelada como um grafo ponderado, onde cada módulo da colônia é um vértice e cada conexão é uma aresta com peso.

## Funcionalidades

- Visualizar a rede da colônia
- Consultar módulos
- Executar BFS
- Executar DFS
- Encontrar caminhos mínimos com Dijkstra
- Calcular perda energética
- Simular situações operacionais

## Módulos da colônia

- Habitação
- Centro de Controle
- Armazenamento de Energia
- Agricultura
- Laboratório
- Comunicação
- Suporte Médico
- Produção de Oxigênio

## Algoritmos utilizados

### BFS

Busca em largura usada para explorar a rede por níveis.

### DFS

Busca em profundidade usada para explorar rotas possíveis.

### Dijkstra

Algoritmo usado para encontrar o caminho mínimo entre dois módulos.

## Estruturas de dados

O sistema utiliza:

- Dicionários
- Listas
- Grafos ponderados
- Pares de valores para custos e caminhos

## Modelagem matemática

A perda energética foi modelada pela fórmula:

P(d) = C × d

Onde:

- P(d): perda energética
- C: consumo por unidade de distância
- d: distância total da rota

## Como executar

1. Baixe o arquivo `codigo_fonte.py`
2. Abra em uma IDE Python
3. Execute o programa
4. Escolha uma opção no menu

---

## 5. link_video.txt

```text
Link do vídeo de apresentação:

https://youtube.com/SEU-LINK-AQUI

```

## Exemplo de uso

Entrada:

```text
Origem: Armazenamento de Energia
Destino: Suporte Médico
