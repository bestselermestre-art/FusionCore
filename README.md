## Módulo de "Conversor de Fusão Direta"
O Conceito de Fusão Direta (Plasma-Elétrica)
Em vez de usar o plasma apenas para esquentar água, usamos Campos Magnéticos em Expansão. Quando a reação de fusão ocorre, ela libera partículas carregadas (íons). Se você colocar essas partículas dentro de um campo magnético que se expande e contrai rapidamente, você induz uma corrente elétrica direto no circuito.

## Exemplo de como os seus dois projetos se conversam:
from FusionCore import converter_fusao_em_eletricidade

## O Escâner pede energia ao Núcleo
energia_disponivel = converter_fusao_em_eletricidade(500)
print(f"ATM iniciando busca com {energia_disponivel}")
