# Projeto_VRP
Repositório para entrega do trabalho da disciplina de AED do PPCA 2020.2

VRP - Vehicle routing problem
O Vehicle routing problem (VRP) é um dos mais estudados problemas na área da otimização combinatória. Consiste no atendimento de um conjunto de consumidores por intermédio de uma frota de veículos, que partem de um ou mais pontos denominados depósitos. O principal objetivo é minimizar os custo de transporte das mercadorias para os consumidores. Este problema apresenta uma quantidade enorme de variações, baseadas na carga dos veiculos, janela de tempo, demanda dos clientes,dentre outras.

O VRP, apesar do seu enunciado relativamente simples, apresenta elevada complexidade computacional, devido a quantidade de combinações geradas conforme se aumenta a quantidade valores e variaveis envolvidas pelo que é interessante como problema no teste de diversas heurísticas.

Esta implementação é um algoritmo de força bruta que calcula todas as combições possiveis de rotas com os seu respectivo custo, de forma identifica a rota de menor custos. Basicamente forma observadas as seguinte premissas:

Todos as entregas partem de apenas um deposito;
Apenas dois veiculos envolvidos;
Todos os veiculo partem do deposito e devem concluir a rota no mesmo;
Cada cliente só pode ser visitado uma vez;
Todos os clientes devem ser visitados;
Todos os veiculo devem sair para realizar entregas.
Esta implementação busca implementar o VRP Classico, de forma que não estão implementadas restrição que geram variações do modelo. Restrições como capacidade dos veiculos, demanda dos clientes, limites de tempo e precedência de atendimento dos clientes, não estão sendo consideradas.

Segue a Função Objetivo:

image.png
