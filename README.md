# SIGIC – Sistema Inteligente de Gerenciamento da Infraestrutura da Colônia

## 1. Introdução

O SIGIC foi desenvolvido para representar computacionalmente a infraestrutura da colônia Aurora Siger em Marte. O sistema utiliza grafos para representar os módulos da base e suas conexões, permitindo visualizar a rede, consultar módulos, executar algoritmos de busca e encontrar caminhos mais eficientes.

O projeto integra conceitos de grafos, BFS, DFS, algoritmo de Dijkstra, estruturas de dados em Python, modelagem matemática, otimização computacional, distribuição de energia, sustentabilidade e governança ESG.

## 2. Organização da infraestrutura da colônia

A colônia foi organizada em oito módulos principais: Habitação, Centro de Controle, Armazenamento de Energia, Agricultura, Laboratório, Comunicação, Suporte Médico e Produção de Oxigênio.

Cada módulo possui prioridade operacional, consumo energético e status. Essa organização permite identificar quais módulos são essenciais para a sobrevivência da colônia e quais podem ter funcionamento reduzido em situações de baixa energia.

## 3. Representação da rede com grafos

A infraestrutura foi representada por meio de um grafo ponderado. Cada módulo da colônia representa um vértice, enquanto cada conexão entre módulos representa uma aresta.

Os pesos das arestas representam custos relacionados à distância, consumo energético ou tempo de transmissão. Dessa forma, o sistema consegue calcular rotas mais eficientes e avaliar o desempenho da rede.

## 4. Estruturas de dados utilizadas

O sistema utiliza dicionários para armazenar os módulos e suas conexões. As listas são utilizadas para controlar os módulos visitados pelos algoritmos BFS e DFS. Também são utilizados pares de valores, semelhantes a tuplas, para representar custos e módulos na execução do algoritmo de Dijkstra.

Essas estruturas foram escolhidas porque permitem organizar os dados de forma clara, simples e eficiente.

## 5. Algoritmos implementados

O algoritmo BFS realiza uma busca em largura, explorando primeiro os módulos mais próximos do ponto inicial. Ele é útil para verificar conectividade e mapear a rede por níveis.

O algoritmo DFS realiza uma busca em profundidade, explorando cada caminho até o fim antes de retornar. Ele é útil para analisar possíveis rotas e conexões da infraestrutura.

O algoritmo de Dijkstra foi aplicado para encontrar o caminho mínimo entre dois módulos, considerando os pesos das conexões. Ele permite otimizar rotas de energia, comunicação e transporte de recursos.

## 6. Modelagem matemática

A modelagem escolhida foi a perda energética na rede.

A fórmula utilizada foi:

P(d) = C × d

Onde P(d) representa a perda energética, C representa o consumo por unidade de distância e d representa a distância total da rota.

Essa modelagem permite avaliar o impacto da distância na distribuição de energia e ajuda a escolher rotas mais eficientes para reduzir desperdícios.

## 7. Otimização computacional

A otimização ocorre principalmente pelo uso do algoritmo de Dijkstra, que permite encontrar a rota de menor custo entre módulos.

Isso reduz desperdício de energia, melhora a comunicação entre setores da colônia e aumenta a eficiência operacional da infraestrutura.

## 8. Sustentabilidade e governança ESG

O SIGIC contribui para o uso sustentável de energia ao identificar rotas mais eficientes e reduzir perdas energéticas.

Em situações de baixa energia, o sistema prioriza módulos críticos como Habitação, Centro de Controle, Comunicação, Suporte Médico e Produção de Oxigênio.

A governança tecnológica aparece na aplicação de regras claras para tomada de decisão, garantindo que os recursos sejam distribuídos de forma responsável e segura.

## 9. Funcionalidades do sistema

O sistema permite visualizar a rede da colônia, consultar módulos, executar BFS, executar DFS, encontrar caminhos mínimos com Dijkstra, calcular perda energética e simular situações operacionais.

Essas funcionalidades tornam o sistema útil para monitoramento, análise e otimização da infraestrutura.

## 10. Conclusão

O desenvolvimento do SIGIC demonstrou a aplicação prática de conceitos fundamentais da computação em um cenário de infraestrutura espacial.

O sistema integra grafos, algoritmos de redes, estruturas de dados, modelagem matemática e sustentabilidade, contribuindo para uma gestão mais eficiente da colônia Aurora Siger.
