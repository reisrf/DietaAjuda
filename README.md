# DietaAjuda
Dieta Ajuda - COLAB - Imersão IA - ALURA e GOOGLE

Exercício sugerido: criação de um projeto de IA com python de acordo com as aulas apresentadas na Imersão em IA ministrada pela ALURA e GOOGLE.

Meu projeto é o de uma Auxliar para dietas. Muitas vezes ao fazermos uma dieta calórica acabamos deixando de registrar a quantidade de calorias que estamos ingerindo durante o dia, por falta de tempo ou por esquecimento mesmo. Com a IA podemos criar um chat inteligente, para obter uma meta de calorias por dia, baseando-se no nosso gênero, idade, altura, peso atual, atividade física semana e quantidade de quilos que deseja perder ( 1Kg a 2Kg/mês para um emagrecimento saudável). De acordo com esses dados, o programa calcula uma quantidade de calorias que se não ultrapassarmos conseguiremos emagrecer.

O programa pergunta inicialmente as informações necessárias, calcula a meta e apresenta ao usuário.

Em seguida, o usuário pode ir informando o que consumiu, alimento e porção  (exemplo 1/2 cebola, 2 tomates, 1 ovo branco grande e 2 fatias de pão de forma integral)

A cada informe de alimentos, o sistema informa o consumo de calorias e vai acumulando a quantidade total no dia.

Exemplo de execução

DietaAjuda: Olá sou seu ajudante na sua dieta calórica.
Vou te ajudar a definir sua meta calórica.

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
> 1



DietaAjuda: Para perder 1kg por mês, consuma cerca de 2200-2300 calorias diárias, combinando com seus exercícios. Ajuste conforme o progresso.

DietaAjuda: Informe os alimentos e quantidade.
Exemplo:
1 pão francês
1 fatia de mussarela
...
Para sair o chat digite FIM

> 2 fatias de pão de forma integral

DietaAjuda: Duas fatias de pão de forma integral têm aproximadamente 140-160 calorias.

Continue informando o que você ingeriu (comidas e bebidas):

> 1 colher de sopa de requeijão, 1 xícara de café sem açucar

DietaAjuda: Adicione cerca de 50-60 calorias (requeijão) e praticamente zero calorias (café sem açúcar). Total até agora: 200-220 calorias.

Continue informando o que você ingeriu (comidas e bebidas):

> 1 suco de 200ml de laranja

DietaAjuda: Adicione aproximadamente 90-100 calorias (suco de laranja). Total estimado até agora: 290-320 calorias.

Continue informando o que você ingeriu (comidas e bebidas):
> FIM

Tchau, foi um prazer, continue firme na sua dieta.




