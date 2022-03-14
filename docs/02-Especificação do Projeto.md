# Especificações do Projeto

A definição precisa do problema e dos pontos mais relevantes deste projeto foi elaborada por meio de entrevistas com os usuários, além de observação de suas rotinas. O resultado deste processo foi consolidado em personas e histórias de usuários que estão listadas seguir.

## Personas
As personas elaboradas no processo de compreeensão do problema estão listadas nas figuras a seguir:
  


|Paulo Andre    | Informações:                       |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![image](https://user-images.githubusercontent.com/90978551/158086116-65bbaff2-06c5-489a-83d3-5d191e5324cd.png)| **Idade:** 28 <br> **Ocupação:** Personal trainer<br> |**Aplicativos:**<br>● Instagram<br>● Facebook<br>●  Whatsapp|
|**Motivações:**<br>● alimentação saudável<br>● Melhoraro corpo<br>|**Frustrações:**<br>● Comer besteira as vezes<br>● Dificuldade em manter uma dieta <br>|**Hobbies:**<br>● Fazer exercicios<br>● Corrida <br>● Viajar |

|isabela martins   | Informações:                       |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![image](https://user-images.githubusercontent.com/90978551/158086108-bce2d747-cbd5-467a-add9-5d3cd41fceab.jpg)| **Idade:** 34 <br> **Ocupação:** Advogada |**Aplicativos:**<br>● Whatsapp<br>● Gmail<br>●  Apps de Bancos|
|**Motivações:**<br>● Uma plataforma com <br> pagamento facil <br>● Acesso a comida caseira<br>● Montar meu prato|**Frustrações:**<br>● Demora na entrega de alguns pedidos<br>● Descrição de produtos não bate com a foto <br> divulgada nos aplicativos.|**Hobbies:**<br>● Caminhar com o <br> cachorro<br>● Explorar a cidade <br>● Pratica natação|

|Fernando Oliveira   | Informações:                       |                                        |
|--------------------|------------------------------------|----------------------------------------|
|![image](https://user-images.githubusercontent.com/90978551/158086112-e8d9cd0c-f1e5-46e9-aaa9-4ce7640deb24.jpg)| **Idade:** 27 <br> **Ocupação:** Medico cardiologista|**Aplicativos:**<br>● Twitter<br>● Instagram<br>● Facebook|
|**Motivações:**<br>● Encontrar uma maneira <br> rápida e fácil de comer saudável.|**Frustrações:** Não conseguir tempo pra cozinhar <br> na sua casa ou trabalho.|**Hobbies:**<br>● Jogar videogame<br>● Assistir séries <br>● Malhar|

## Histórias de Usuários

Com base na interpretação da realidade das personas identificadas para este projeto por meio das informações coletadas, foram registradas as histórias de usuários listadas a seguir:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|isabela martins     | Receber entrega através do delivery | Agilizar e otimizar meu tempo |
|isabela martins     | Uma plataforma que exiba <br> o cardápio de alimentos| escolher e personalisar meu prato |
|isabela martins     | Uma plataforma onde haja um sistema <br> de pagamento digital | Poder pagar, com <br> maior facilidade|
|Fernando Oliveira   | Ter alimentos com tempero caseiro sem ter <br> que cozinhar | Maior praticidade e menos tempo gasto com <br> preparo de refeições |
|Fernando Oliveira   | Ter acesso a quantidade de porçoes com preço de cada alimento adicionado| Poder saber quanto custa cada alimento
|Paulo Andre         | Poder adicionar e remover  <br> incredienteda refeição. | <br> Ter maior liberdade na hora de perzonalisar o prato. |
|Paulo Andre         | Poder escolher o peso de cada ingrediente | controlar dieta micros e macros nutrientes. |


## Requisitos

Os requisitos do projeto descrevem as características necessárias para alcançar a solução do problema apresentado de modo satisfatório, delimitando assim o escopo funcional do projeto. Os requisitos podem ser divididos em requisitos funcionais, que descrevem as funcionalidades que o sistema deve apresentar para possibilitar a interação dos usuários, e em requisitos não-funcionais, que descrevem as qualidades que o sistema e suas funcionalidades devem apresentar para sua aceitação. Os requisitos funcionais e não funcionais do projeto são apresentados nas tabelas a seguir.

### Requisitos Funcionais
|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| O site deve apresentar um mecanismo de busca que permita ao consumidor escolher os ingredientes que compõem a refeição. | ALTA | 
|RF-02| O site deve permitir que o usuário crie uma conta para salvar suas informações (local de entrega, meios de pagamento, histórico de pedidos, etc). | ALTA | 
|RF-03| O site deve permitir ao usuário visualizar preço de cada porção de alimento | MÉDIA |
|RF-04| O site deve permitir que o consumidor adicione e remova items e pesos da sua refeição . | MÉDIA|
|RF-05| O site deve apresentar na página principal a ferramenta para formação da nova refeição  | MÉDIA |
|RF-06| A plataforma deve fornecer ao cliente uma forma de filtra os alimentos por categorias | BAIXA |
|RF-07| O site deve permitir que o usuário cadastrado adicione os produtos a um carrinho de compras e submeta um pedido de compra. | ALTA |
|RF-08| O site deve permitir que o usuário veja o valor final de sua refeição. | ALTA |


### Requisitos não Funcionais

A tabela abaixo contém os requisitos não funcionais do projeto, também acompanhados de sua prioridade de entrega.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01|  processo de cadastro de cliente deve ser fácil e intuitivo | ALTA | 
|RNF-02| O processo de somar e subtrair valores das refeiçoes deve estar funcionado 100% | ALTA |
|RNF-03| O site deverá utilizar banco de dados relacional (MySQL). | ALTA |
|RNF-04| O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku) | ALTA |
|RNF-05| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada | MÉDIA|
|RNF-06| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox) | ALTA |


## Restrições

A tabela abaixo contém a a lista das questões que limitam a execução do projeto e que portanto impõem obrigações claras para seu desenvolvimento.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01|	O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 26/06/2022.
|RE-02|	A plataforma deverá se restringir às linguagens (e seus respectivos frameworks) HTML, CSS, JavaScript.
|RE-03|	A equipe não pode subcontratar o desenvolvimento do trabalho.

## Diagrama de Casos de Uso

![image](https://user-images.githubusercontent.com/90978551/158095656-7686fd52-0581-4635-88de-66265c7966af.png)
