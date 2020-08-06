# Análise de dados dos casos de Covid-19 da cidade de manaus

Os dados usados nesta análise foram baixados do [portal de acompanhamento da cidade de Manaus](https://covid19.manaus.am.gov.br/monitoramento/). Como esses dados são atualizados constantemente, escolheu-se salvar os dados no dia 5 de Agosto de 2020 no arquivo [dataset_covid19_manaus.csv](dataset_covid19_manaus.csv).

## Visão geral dos dados

A fim ter um entendimento mais geral dos dados, fez-se uma análise nos dados brutos sem pré-processamento, essa visão está disponível no arquivo [Visao_geral_dos_casos_confirmados.ipynb](Visao_geral_dos_casos_confirmados.ipynb).

## Pré-processando os dados
Para realizar a análise dos dados o dataset foi simplificado ao máximo, foram deletados atributos que não eram necessários para a análise, e todas as linhas de tinham pelo menos um dado faltando. O resultado pode ser visto no arquivo [dataset_limpo_covid19_manaus.csv](dataset/dataset_limpo_covid19_manaus.csv)