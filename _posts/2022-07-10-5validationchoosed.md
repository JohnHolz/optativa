---
layout: post
title: "5. Cross Validation"
categories: EDA
author:
  - João Holz
meta: "Ufes - IC 1 - Departamento de Estatística"
---

# Cross Validationw

Vamos utilizar um k-fold como forma de validção, dividiremos em 10. K-folds funciona separando o dataset em k subsets de dados, e como temos 10 partições agora, podemos treinar em k-1 e testamos em k, e repetiremos esse processo k vezes. Assim teremos métricas mais confiáveis.

    "daí que a universalidade empírica é uma extensão arbitraria de validade"

Sabendo que existem callbacks eu não adicionei pois tive de aguardar pacientemente pelo treinamento dos modelos. Depois de 2 bitcoins minerados pelo tensorflow chegamos aos seguintes resultadossw

# Conclusão

Vemos que as métricas incrivelmente melhoraram, pois em cada interação do k-folds tem mais dados do que utilizamos na escolha dos modelos, o que mostra que fizemos um bom trabalho. Conseguimos um nível de qualidade de modelos muito bom,
otimizamos a nossa métrica de falsos negativos, chegamos em 0 e nosso caso que mais erramos no k-folds erramos pouquissimos dados.

Achei que no final seriamos derrotados pelo asteroide invísivel desfarçado de bonzinho mas conseguimos fazer os modelos acusarem.

2,2,207,0.5,ADA
3,5,207,0.5,ADA
6,0,207,0.5,ADA
3,3,207,0.5,ADA
2,1,207,0.5,ADA
2,3,206,0.5,ADA
2,3,206,0.5,ADA
5,7,206,0.5,ADA
3,3,206,0.5,ADA
4,3,207,0.5,ADA

2,2,207,0.5,RF
4,5,207,0.5,RF
5,0,207,0.5,RF
3,2,207,0.5,RF
4,0,207,0.5,RF
1,2,206,0.5,RF
2,3,206,0.5,RF
7,7,206,0.5,RF
2,5,206,0.5,RF
5,2,207,0.5,RF

0,105,207,0.05,RF
0,155,207,0.05,RF
1,149,207,0.05,RF
0,240,207,0.05,RF
0,125,207,0.05,RF
0,157,206,0.05,RF
0,204,206,0.05,RF
2,170,206,0.05,RF
2,150,206,0.05,RF
0,157,207,0.05,RF

52,9,207,0.5,TF
4,62,207,0.5,TF
54,5,207,0.5,TF
35,1,207,0.5,TF
99,0,207,0.5,TF
75,5,206,0.5,TF
29,20,206,0.5,TF
15,38,206,0.5,TF
28,11,206,0.5,TF
17,12,207,0.5,TF

0,102,207,0.05,TF
0,226,207,0.05,TF
0,106,207,0.05,TF
0,105,207,0.05,TF
6,27,207,0.05,TF
0,50,206,0.05,TF
0,129,206,0.05,TF
0,183,206,0.05,TF
3,136,206,0.05,TF
0,126,207,0.05,TF

0,93026,207,0.05,ADA
0,93027,207,0.05,ADA
0,93027,207,0.05,ADA
0,93027,207,0.05,ADA
0,93027,207,0.05,ADA
0,93027,206,0.05,ADA
0,93027,206,0.05,ADA
0,93027,206,0.05,ADA
0,93027,206,0.05,ADA
0,93026,207,0.05,ADA