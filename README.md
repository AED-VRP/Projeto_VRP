###### UNB - Universidade de Brasília
###### Instituto de Ciências Exatas 
###### Departamento de Ciência da Computação
###### Disciplina: Algoritmos e Estrutura de Dados (PPCA 2020.2)
###### Professor: Edison Ishikawa


Integrantes:
- Edmilson Cosme da Silva
- Fernanda Lopes de Lima
- Lucilene da Silva Leite
- Marcos Paulo Pereira da Silva
    
# Projeto_VRP
Repositório para entrega do trabalho da disciplina de AED do PPCA 2020.2

###### VRP - Vehicle routing problem

O Vehicle routing problem (VRP) é um dos mais estudados problemas na área da otimização combinatória. Consiste no atendimento de um conjunto de consumidores por intermédio de uma frota de veículos, que partem de um ou mais pontos denominados depósitos. O principal objetivo é minimizar os custo de transporte das mercadorias para os consumidores. Este problema apresenta uma quantidade enorme de variações, baseadas na carga dos veiculos, janela de tempo, demanda dos clientes,dentre outras.

O VRP, apesar do seu enunciado relativamente simples, apresenta elevada complexidade computacional, devido à quantidade de combinações geradas conforme se aumenta a quantidade valores e variaveis envolvidas pelo que é interessante como problema no teste de diversas heurísticas.

Neste trabalho implementamos uma versão da solução com algoritmo exato de força bruta e outra versão utilizando um algoritmo aproximando com meta heurística simulated annealing.
A implementação que utilizada a força bruta que calcula todas as combinações possíveis de rotas com os seus respectivos custos, de forma identificar a rota de menor custo.
A implementação que utiliza o simulated annealing tenta se aproximar da solução ótima com um número limitado de execuções. 
Basicamente forma observadas as seguinte premissas:

    Todos as entregas partem de apenas um deposito;
    Apenas dois veiculos envolvidos;
    Todos os veiculo partem do deposito e devem concluir a rota no mesmo;
    Cada cliente só pode ser visitado uma vez;
    Todos os clientes devem ser visitados;
    Todos os veiculo devem sair para realizar entregas.
    Esta implementação busca implementar o VRP Classico, de forma que não estão implementadas restrição que geram variações do modelo.

Restrições como capacidade dos veículos, demanda dos clientes, limites de tempo e precedência de atendimento dos clientes, não estão sendo consideradas.

Os algoritmos foram implementados utilizando a ferramenta COLAB do Google.

Segue a Função Objetivo:

![funcao_objetivo_VRP](https://user-images.githubusercontent.com/79127526/112634457-6123e100-8e19-11eb-9a1e-a24d921fa2ec.png)

Organização dos arquivos: 

    Pastas: 

        - codigo - Contém o codigo dos algoritmos e do gerador de dataset;

        - dataset- Contém os dataset utilizados;

        - log_execucao - Contém os logs de execução.
