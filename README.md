MVP de Análise de Dados - Alexandre Peixoto Marcet

A obesidade, que causa problemas físicos e mentais, é um problema de saúde global com graves consequências. A prevalência da obesidade está aumentando constantemente e, portanto, são necessárias novas pesquisas que examinem os fatores que influenciam a obesidade e como prever a ocorrência da doença de acordo com esses fatores. E como forma de contribuir para a divulgação e melhor compreensão desse problema, além da investigação e divulgação de soluções, decidi abordar esse tema no meu MVP de Análise de Dados.

Este MVP tem como objetivo coletar, analisar e tratar os dados sobre os níveis de obesidade de um conjunto de pessoas dos seguintes países: México, Peru e Colômbia, com idades entre 14 e 61 anos e diversos hábitos alimentares e condições físicas. E, a partir desses processos, gerar uma base de dados para ser utilizada na resolução dos seguintes problemas de agregação (clusterização) com aprendizado não supervisionado:

    Segmentação de grupos de pessoas em diferentes níveis de peso
    Analisar a relação entre os hábitos alimentares e a obesidade
    Analisar a relação entre as condições físicas e a obesidade

Os dados foram obtidos na plataforma kaggle no seguinte endereço: https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster/data

O dataset possui os seguintes atributos:

[0] - genero - gênero da pessoa

[1] - idade - idade da pessoa

[2] - altura - altura da pessoa (em metros)

[3] - peso - peso da pessoa (em kg)

[4] - hist_familiar_sobrepeso - existência (ou não) de histórico familiar de sobrepeso

[5] - alimentos_caloricos - ingestão (ou não) de alimentos com alto teor calórico com frequência

[6] - num_veg_refeicoes - quantidade de vegetais consumidos nas refeições

[7] - num_refeicoes_dia - número de refeições principais diárias

[8] - alim_entre_refeicoes - ingestão de alimentos entre as refeições principais

[9] - fumante - fumante ou não fumante

[10] - qtde_agua_dia - quantidade de água ingerida diariamente

[11] - verif_calorias_dia - se a pessoa monitora a quantidade de calorias ingeridas por dia

[12] - ativ_fisica_semana - número de vezes que a pessoa realiza atividades físicas por semana

[13] - tempo_disp_tech - tempo diário dedicado ao uso de dispositivos tecnológicos (tv, celular, computador)

[14] - alcool - frequência com que a pessoa ingere álcool

[15] - meio_transporte - meio de transporte usado com frequência

[16] - nivel_obesidade - nível de obesidade da pessoa

    abaixo do peso
    peso normal
    sobrepeso
    obesidade nível 1
    obesidade nível 2
    obesidade nível 3
