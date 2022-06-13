# Valor_Patrimonial

## Sumário
* [Objetivos](#objetivo)
* [Data Understanding](#EDA)
* [Resultados e Conclusões](#Resultados)
* [Tecnologias](#tecnologias)

## Objetivos
1° - Confirmar a hipótese "Imóveis protegem contra a inflação"

2° - Previsão do valor patrimonial mínimo (valor venal) de imóveis na cidade de São Paulo.

## Fonte dos Dados
O banco de dados foi obtido do novo sistema integrado da cidade de São Paulo, o GeoSampa.

## Data Understanding
Obtenção dos dados por webscraping de arquivos .csv da API GeoSampa utilizando as libs request, selenium, pandas, e glob.

Arquivo: data_extracting.ipynb.

Análise de proporção, e testes de hipóteses para a confirmação da hipótese levantada no item 1 da seção "Objetivos" utilizando as libs pandas e scipy.stats. 

Arquivo: projeto_parte2.ipynb (em produção).

## Resultados e Conclusões
Até o momento, foi possível confirmar numericamente a hipótese, pois aproximadamente 99% dos imóveis valorizaram mais do que a inflação do período. Como próxima etapa, 
iremos ir mais a fundo e entender como isso ocorreu, uniformimente ou heterogeneamente. Após o fim da análise, iniciaremos a preparação dos dados para a etapa de 
modelagem (objetivo número 2).
	
## Tecnologias
Projeto criado com:
* Python: 3.10.4
  * Biblioteca: Numpy, Matplotlib.pyplot, pandas, scipy.stats, pprint, uszipcode
* IDE: Google Colab
* Unix: OS version 18.7.0
* Git and Github
