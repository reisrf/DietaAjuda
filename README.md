# DietaAjuda
Dieta Ajuda - COLAB - Imersão IA - ALURA e GOOGLE

Exercício sugerido: criação de um projeto de IA com python de acordo com as aulas apresentadas na Imersão em IA ministrada pela ALURA e GOOGLE.

Meu projeto é o de uma Auxliar para dietas. Muitas vezes ao fazermos uma dieta calórica acabamos deixando de registrar a quantidade de calorias que estamos ingerindo durante o dia, por falta de tempo ou por esquecimento mesmo. Com a IA podemos criar um chat inteligente, para obter uma meta de calorias por dia, baseando-se no nosso gênero, idade, altura, peso atual, atividade física semana e quantidade de quilos que deseja perder ( 1Kg a 2Kg/mês para um emagrecimento saudável). De acordo com esses dados, o programa calcula uma quantidade de calorias que se não ultrapassarmos conseguiremos emagrecer.

O programa pergunta inicialmente as informações necessárias, calcula a meta e apresenta ao usuário.

Em seguida, o usuário pode ir informando o que consumiu, alimento e porção  (exemplo 1/2 cebola, 2 tomates, 1 ovo branco grande e 2 fatias de pão de forma integral)

A cada informe de alimentos, o sistema informa o consumo de calorias e vai acumulando a quantidade total no dia.

Exemplo de execução:

DietaAjuda: Olá sou seu ajudante na sua dieta calórica.
Vou te ajudar a definir sua meta calórica. Mas lembre que é importante ter um acompanhamento de um profissional da saúde.

DietaAjuda: Preciso saber seu gênero: M ou F
> M
DietaAjuda: Qual sua idade? 5 - 95 anos
> 58
DietaAjuda: Qual sua altura em centimetros? 50 a 250 cm
> 190
DietaAjuda: Qual seu peso atual em quilos?
> 98
DietaAjuda: Você se exercita quantas vezes por semana?
Informe um número de 0 (sedentário) a 7 (super ativo)
> 4
DietaAjuda: Quantos quilos deseja emagrecer por mês
(recomendado de 1 a 2 Kg)
> 2

DietaAjuda: Olá! Para você, com 58 anos, 1,90m de altura, 98kg e se exercitando 4 vezes por semana, uma estimativa segura para perder cerca de 2kg por mês seria consumir entre 2200 e 2500 calorias por dia.

Lembre-se que essa é uma estimativa e pode variar de pessoa para pessoa. O ideal é consultar um nutricionista para um plano alimentar personalizado! 😊

DietaAjuda: Informe os alimentos e quantidade.
Exemplo:
1 pão francês
1 fatia de mussarela
...
Para sair o chat digite FIM
> 1 pão francês, 1 colher de sobremesa de manteiga, 1 fatia de mussarela, 1 ovo branco cozido

DietaAjuda: Com base nos alimentos que você mencionou:

1 pão francês: Aproximadamente 140 calorias
1 colher de sobremesa de manteiga: Aproximadamente 50 calorias
1 fatia de mussarela: Aproximadamente 85 calorias
1 ovo cozido: Aproximadamente 78 calorias
Somando tudo, você consumiu cerca de 353 calorias. 😊

Continue informando o que você ingeriu (comidas e bebidas):
> 1 suco de laranja 200ml

DietaAjuda: Adicionando o suco de laranja (200ml, aproximadamente 90 calorias) ao que você já havia consumido (353 calorias), o total fica em torno de 443 calorias. 😉
Continue informando o que você ingeriu (comidas e bebidas):

FIM


Tchau, foi um prazer, continue firme na sua dieta.




