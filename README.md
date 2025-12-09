# Atividade_de_mineração

Este código realiza uma pequena atividade de mineração de dados, calculando a entropia de um atributo,
construindo uma árvore de decisão com base no ganho de informação e classificando novas instâncias de acordo com os ramos da árvore.
Ele demonstra conceitos fundamentais como impureza, divisão ótima e tomada de decisão.

```
--- Entropia ---
  Gênero  Idade         Escolaridade Estado Civil  Renda (R$) Comprou
0      F     22                Médio     Solteiro        2500     Não
1      M     35    Superior completo       Casado        4000     Sim
2      F     28  Superior incompleto     Solteiro        3200     Sim
3      M     40    Superior completo   Divorciado        4100     Sim
4      F     23                Médio     Solteiro        2700     Não
5      M     30                Médio       Casado        3000     Não
6      M     36        Pós-graduação       Casado        4200     Sim
7      F     27    Superior completo     Solteiro        2900     Não
8      M     50        Pós-graduação   Divorciado        4500     Sim
9      F     24  Superior incompleto     Solteiro        2600     Não

Quantidade total de valores analisados: 10
Quantidade de ocorrências de F: 5
Probabilidade (pᵢ): 0.5
Atributo analisado: Gênero
Valor atual: F
Entropia calculada:

--- Árvore de Decisão Construída ---
TESTA: 'Tempo'
  - Se 'Ensolarado':      
  --> DECISÃO: Jogar      
  - Se 'Nublado':
TESTA: 'Umidade'
    - Se 'Alta':
    --> DECISÃO: Não Jogar
    - Se 'Normal':        
    --> DECISÃO: Jogar    
  - Se 'Chuvoso':
  --> DECISÃO: Não Jogar  

--- Classificar Nova Instância ---
Digite 'atributo: valor' (ex: Tempo: Ensolarado). Digite 'fim' para terminar.
>>> Tempo
Formato inválido. Use 'atributo: valor'.
>>> Tempoo: Ensolarado 
>>> se Alta
Formato inválido. Use 'atributo: valor'.
>>>
Formato inválido. Use 'atributo: valor'.
>>>
Formato inválido. Use 'atributo: valor'.
>>>
Formato inválido. Use 'atributo: valor'.
>>>
Formato inválido. Use 'atributo: valor'.
>>>
Formato inválido. Use 'atributo: valor'.
>>> fim 
Aviso: Valor 'None' para 'Tempo' não tem caminho na árvore.
