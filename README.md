 # Testando se uma fórmula bem formulada é uma tautologia

Explicar lógica proposicional
Explicar o que é uma tautologia
Explicar brevemente como o código funciona (o que é a entrada e a saida..)

O projeto formulado visa testar se uma FBF (fórmula bem formulada, expressão lógica válida) é uma tautologia, em um contexto de lógica proposicional.

### O que é lógica proposicional?
A lógica proposicional é um tipo de lógica formal, que se baseia na relação de proposições (que podem ou ser falsas ou ser verdadeiras), através de símbolos e regras para analisar a estrutura e a validez dos argumentos, independentemente do seu conteúdo. Os conectivos válidos dentro da lógica proposicional são: 

Negação - inverte a valor de uma proposição, se ela for verdadeira, virará falsa (vice e versa). Ela pode ser escrita como "não"

| A | ¬A |
| - | -- |
| V | F  |
| F | V  |

Conjunção - retorna Verdadeiro somente se as duas proposições analisadas forem verdadeiras. Caso contrário, retorna Falso. Ela pode ser escrita como "e".

| A | B | A ∧ B |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | F     |

Disjunção - retorna Verdadeiro se pelo menos uma das proposições for verdadeira. Caso contrário, retorna Falso. Ela pode ser escrita como "ou", sendo esse um "ou" inclusivo.

| A | B | A ∨ B |
| - | - | ----- |
| V | V | V     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

Condicional - retorna Verdadeiro se a proposição antecedente for falsa ou se as duas proposições analisadas são verdadeiras. Caso contrário, retorna Falso. Ele pode ser escrito como "então".

| A | B | A → B |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | V     |
| F | F | V     |

Bicondicional - retorna Verdadeiro se as duas proposições analisadas são verdadeiras ou se as duas são falsas. Caso contrário, retorna Falso. Ele pode ser escrito como "se, e somente se,".

| A | B | A ↔ B |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | V     |


### O que é uma tautologia?
Uma tautologia ocorre quando uma FBF resulta somente em verdades. As tautologias são de extrema importância, já que fornecem as bases para a construção de argumentos válidos, portanto, é relevante avaliar se uma FBF é uma tautologia. É possível visualizar uma tautologia ((a ∧ b) → a) através do exemplo:
| a | b | a ∧ b | (a ∧ b) → a |
| - | - | ----- | ----------- |
| V | V | V     | V           |
| V | F | F     | V           |
| F | V | F     | V           |
| F | F | F     | V           |

