# INPI

O Instituto Nacional da Propriedade Industrial (INPI) é uma autarquia federal brasileira, criada em 1970, vinculada ao Ministério do Desenvolvimento, Indústria e Comércio Exterior (MDIC). Localiza-se na cidade do Rio de Janeiro, Brasil. Antecedido pelo Departamento Nacional da Propriedade Industrial.

## Sobre o Projeto

No ano de 2021, foi realizado um Hackathon para a construção de soluções que auxiliem o instituto na celeridade dos processos de registros de marcas e patentes. Foi disponibilizado para os participantes, a base de dados de marcas para realizar a tarefa. 

Foi utilizada técnicas de Data Science em especial MLP (Multi Layer Perceptron) que consistem em uma rede neural capaz de obter o comportamento e as nuâncias dos dados de forma eficiente e eficaz com o um baixo custo computacional. 

O algoritmo conseguiu uma eficiência de 70% nos testes preliminares mostrando ser uma solução promissora no papel de classificação dos dados fornecidos.

## Sobre a Base

A base de dados apresentada possui 19 atributos que represetam os dados de registro de marcas do INPI no período de Janeiro de 2018 à 30 de Novembro de 2018. 

A base registro um total de 541.796 instâncias contendo informações de marcas de produtos e serviços. 

Os atributos encontrados na base possuem os seguintes significados:
* **numero_processo** 		- Número do processo
* **nome_marca**			- Nome da marca
* **descricao_situacao** 		- Descrição da situação
* **descricao_apresentacao**		- Descrição da apresentação, representa a forma que a marca é apresentada. Sendo Nominativa, Figurativa, Mista ou Tridimencionais
* **descricao_natureza** 		- Descrição da natureza
* **classificacao_viena**		- Descrição da classificação Viena (é um sistema de classificação internacional de elementos figurativos de marcas)
* **nome_titular**			- Nome do titular
* **nome_representante_legal**	- Nome do representante legal
* **data_deposito** 			- Data de depósito (Data da solicitação de registro de marca)
* **data_concessao** 			- Data da concessão da marca
* **data_vigencia**			- Data da vigência da marca
* **numero_rpi** 			- Número da RPI (revista)	(Nro da revista da propridade industrial)
* **data_rpi** 			- Data da publicação da RPI
* **codigo_despacho**			- Código do despacho na RPI 	
* **descricao_despacho**		- Descricão do despacho
* **complemento_despacho** 		- Complemento do despacho
* **numero_revisao_classicacao_nice** - Número da revisão da classificação Nice
* **codigo_classificacao_nice** 	- Código da classificação Nice
* **especificacao_classificacao_nice**- Especificação da classificação Nice

## Sobre a solução

A solução consistem em criar um modelo capaz de generalizar a classificação do processo de registro de marcas informando ao usuário e a equipe do INPI se o processo tem chances de deferimento, indeferimento ou entrará em uma etapa intermediária. 

## Sobre a equipe

INPírico 

**Integrantes do Projeto**

* Maria Gardênia Santiago (gardeniasantiago@gmail.com)
* Marcos da Cruz Santos (marcosmult@outlook.com)
* Tácito Henrique da Silva Graça (tacito.graca@gmail.com)
* Vagner Simões Santos (vagnersantos.bsi@gmail.com)

## Projetos Futuros

Este algoritmo serve de modelo e rascunho para um processo mais elaborado de classificação. A base de dados deve ser minerada de forma mais criteriosa para evitar duplicação de registros e transformar informações relevantes para o modelo preditivo em dados numéricos. 

Ainda poderia ser utilizada outras técnicas como uma classificação supervisionada, o que pode aumentar a qualidade da classificação a curto prazo. 

