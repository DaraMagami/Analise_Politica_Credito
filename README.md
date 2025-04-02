# Análise de Dados de Fraude

## Acesso ao dados

Este estudo trata-se de um conjunto de análises de dados dos clientes de uma instituição financeira fictícia no que diz respeito às suas características como requerentes de crédito. São apresentados, a seguir, mais detalhes sobre o projeto.

Os dados utilizados podem ser obtidos em: https://www.kaggle.com/datasets/laotse/credit-risk-dataset

## Introdução

Desde a idade média as instituições financeiras desempenham importantes funções em suas regiões de atuação, a exemplo do Banco de Veneza, reconhecido como o primeiro banco do mundo, fundado em 1157, e responsável por, entre outras atribuições, financiar as atividades da monarquia. Além disso, os bancos figuram entre as organizações mais antigas ainda em atividade: atualmente, o banco reconhecido como o mais longevo, ainda em funcionamento, é o Banca Monte dei Paschi di Siena, fundado em 1472, na Itália. Entre os principais serviços fornecidos por essas empresas, não só hoje, mas desde a sua concepção, está a concessão de crédito a pessoas físicas e jurídicas. Ao acessar os recursos de um empréstimo, indivíduos e empresas têm a possibilidade de ampliar seu patrimônio, o que traz dinamismo econômico, seja por meio, exclusivamente, do consumo, seja pela geração de novos produtos, investimentos e postos de trabalho. Além desses benefícios, a possibilidade de requerer crédito junto a um banco, ou fintech, por exemplo, permite a expansão de pequenos negócios e oferece a oportunidade de apoiar organizações em momentos de baixa receita. 

No entanto, não se pode perder de vista que, ainda que seja crucial para a saúde financeira de famílias e outras corporações, os bancos também são negócios e precisam prezar por sua própria sustentabilidade como tal. Por isso, a fim de mitigar e prevenir riscos, os dados e as atividades de seus clientes são monitorados e analisados com técnicas a cada dia mais avançadas e que são indispensáveis à compreensão e prevenção de inadimplência, fraudes e outros cenários que prejudiquem as atividades bancárias. 

## Objetivo 

O objetivo central deste projeto foi, além de ampliar conhecimentos e habilidades em análise de dados, contemplar diferentes aspectos e combinações de variáveis na compreensão do público requerente. A construção destas análises possibilitou captar padrões e ajudou a definir quais perfis de públicos são mais inclinados à inadimplência. Os dados foram obtidos no repositório Kaggle e são fictícios

## Solução

Este estudo foi desenvolvido a partir da linguagem Python, utilizando a interface Jupyter Lab, e divide-se em duas etapas: a de ETL (Extract, Transform, Load) e EDA (Exploratory Data Analysis). 
Na etapa de ETL os dados foram carregados a partir do arquivo .csv, realizou-se as alterações necessárias, sendo salvo em um DataFrame Pandas.
Em seguida, na etapa de EDA, foi feita uma avaliação geral, uni e bivariada, das variáveis categóricas e numéricas, além de terem sido definidos tópicos de investigação mais específicos, a partir dos quais, também, foram criados gráficos.

## Conclusões

Após concluir o projeto, as principais conclusões obtidas foram:

1.A faixa de renda é a melhor variável para segregar adimplentes e inadimplentes;

2.A grosso modo, aqueles que possuem maior renda, em quase 100% dos casos, têm menor probabilidade de inadimplência, ao passo em que o contrário também é válido;

3.Há, principalmente, 3 grandes grupos de requerentes: conservadores, alavancados e medianos;

4.Dado o alto nível de inadimplência para determinados grupos, é válido mencionar que há espaço para o aprimoramento do modelo que define o nível de risco dos clientes.


