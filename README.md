# Análise de dados dos casos de Covid-19 da cidade de manaus

Os dados usados nesta análise foram baixados do [portal de acompanhamento da covid-19 da cidade de Manaus](https://covid19.manaus.am.gov.br/monitoramento/). Como esses dados são atualizados constantemente, escolheu-se salvar os dados no dia 5 de Agosto de 2020 no arquivo [dataset_covid19_manaus.csv](dataset/dataset_covid19_manaus.csv).

## Pré-processando os dados

Para realizar a análise dos dados o dataset foi simplificado ao máximo, foram deletados atributos que não eram necessários para a análise, e todas as linhas que possuiam pelo menos um dado faltando. O resultado pode ser visto no arquivo [dataset_limpo_covid19_manaus.csv](dataset/dataset_limpo_covid19_manaus.csv). Ao finalizar a retirada de colunas e linhas desejadas o arquivo ficou com 6 featues e 6361 linhas.

## Exploração de dados

### Visão geral dos casos da base de dados

No arquivo [visao_geral_casos_confirmados.ipynb](visao_geral_casos_confirmados.ipynb) é possível ter um panorama mais geral sobre os casos com base nos datasets.

### Propondo tarefas de Aprendizado de máquina para o dataset

Neste etapa buscou-se identificar os melhores atributos dentro da base de dados para serem usados como atributos preditores ou classes para tarefas de Aprendizado de máquina, embora houvesse limitações na tarefa por causa da base de dados, propôs-se essa tarefas e podem ser conferidas nesse arquivo: [tipo_de_tarefa.ipynb](tipos_de_tarefa.ipnyb)