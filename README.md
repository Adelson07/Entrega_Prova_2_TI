## Entrega_Prova_2_TI
##Disciplina de Tópicos Integradores (David Leal)
##Avaliação de Tópicos Integradores
##Professor: David Leal
#1. Por que devemos fazer testes automatizados nas aplicações que desenvolvemos?
R- Para garantir que a aplicação esteja funcionando após realizarmos alguma alteração na base do código.
#2. O que são testes unitários?
R- É o teste realizado para toda e qualquer função, já na orientação ao objeto, é o teste de um método de seu objeto.
3#. O que são testes automatizados?
R- São programas que executam testes em softwares que estão sendo construídos de formas padronizadas sem que haja intervenção humana.
#4. Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide.
R- A princípio a pirâmide de testes é uma forma gráfica de demonstrar de forma simples os tipos de testes, seus níveis, velocidade de implementação e complexidade dos testes realizados.
Existem algumas divisões diferentes quando trata-se da pirâmide de testes, porém vamos tratar da divisão mais comum, que é representada por 3 níveis, sendo eles:

#Base: Testes de Unidade
Conforme já foi citado na questão 2, teste unitário serve para testarem os menores pedaços possíveis do código de forma isolada. Os testes unitários tendem a ser extremamente pequenos e de rápida criação e execução. Essa característica permite que caso um dos testes falhe, seja possível saber com precisão o local da falha.

#Meio: Testes de Integração
O teste de integração ou como também é conhecido como teste do meio, tem a finalidade de testar um conjunto de unidades interagindo entre si. Exemplos comuns desse tipo de teste é a comunicação com banco de dados, comunicação de interfaces, APIs e micro serviços.

#Topo: Testes Ponta a Ponta (E2E, UI ou Testes de Interface)
Os testes de ponta a ponta (testes end to end ou testes de interface) têm como objetivo principal simular o comportamento de um usuário final em nossa aplicação. São testes que simulam o ambiente real, ou seja, iniciam a aplicação ou abrem o navegador, navegam dentro da aplicação, clicam em botões, preenchem formulários e, ao fim, validam se o comportamento apresentado condiz com o que seria esperado para tal funcionalidade.
