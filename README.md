![Testando Tautologias! Prática em Ciência de Dados](https://github.com/user-attachments/assets/cde7591c-e2d8-4510-85ff-6ce42ebc2167)
### Ilum - escola de ciência - trabalho final de Práticas em Ciência de Dados
#### Professores: Daniel Cassar, James Almeida e Leandro Lemos
#### Integrantes: Aline Silva dos Santos, Ana Carolina Sayumi, Caio Cogo Beriam e Mariana Jann Luna

O projeto formulado visa testar se uma FBF (fórmula bem formulada, expressão lógica válida) é uma tautologia, em um contexto de lógica proposicional. 

Para utilizar o projeto, o usuário deve abrir o Jupyter Notebook presente neste github, ler atentamente a intodução e adicionar uma frase de acordo com as instruções na seção "Recebendo a frase". Em seguida, o usuário deve atribuir os significados das proposições na seção "Recebendo frases de linguagem natural para cada proposição". Ademais, basta rodar as células restantes na seção "Função principal" que será retornado por escrito ao usuário se a frase que ele escolheu é, ou não, uma tautologia. Além disso, o usuário também recebe uma tabela verdade gerada no processo, para ilustrar a possível tautologia.


Atenção, o projeto não inclui FBFs com parêntenses.

A seguir, encontra-se um breve resumo sobre lógica proposicional e tautologia.

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
| A | B | A ∧ B | (A ∧ B) → A |
| - | - | ----- | ----------- |
| V | V | V     | V           |
| V | F | F     | V           |
| F | V | F     | V           |
| F | F | F     | V           |


### Contribuições de cada integrante 
 * Aline Silva dos Santos: Programação das funções dos conectivos, auxilio na programação da função principal, ideia de criar um ordenador, formatação do notebook (Instruções ao usuário, DocStrings), Readme.
   
 * Ana Carolina Sayumi: Programação da função ordenador, adaptação da programação para mais de duas proposições, programação da tabela verdade e integração final das funções.
   
 * Caio Cogo Beriam: Lógica de tradução e substituição, programação das funções de conectivos, lógica de processamento de linguagem, interface gráfica (não foi aplicada).
   
 * Mariana Jann Luna: Ideia inicial do projeto (tautologia), programação das funções dos conectivos, programação de conectar as proposições com as funções a partir do index, identificação de erros no código, Readme e git.

### Referências

Aulas de Lógica Computacional - conteúdo de lógica proposicional - professor Daniel Cassar
